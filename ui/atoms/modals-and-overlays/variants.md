```yaml
componentName: CloseIcon
filename: close-icon
category: modals, overlays, icon
layout: inline, button
primaryUse: Renders a close (X) icon button for dismissing modals or overlays.
description: An accessible close icon button for modals and overlays, supporting custom click handlers and styling.
uses: modals, overlays, dialogs, notifications
dependencies: [react]
devDependencies: [typescript]
```

---

```yaml
componentName: DialogueTitle
filename: dialogue-title
category: modals, overlays, title
layout: flex, header
primaryUse: Displays a styled title for modal dialogs, with optional icon.
description: A title/header component for modal dialogs, supporting optional icon and custom styling.
uses: modals, overlays, dialogs
dependencies: [react]
devDependencies: [typescript]
```

---

```yaml
componentName: DialogueContent
filename: dialogue-content
category: modals, overlays, content
layout: block, container
primaryUse: Provides a styled content container for modal dialogs.
description: A content wrapper for modal dialogs, supporting size, padding, and rounded corners for flexible layouts.
uses: modals, overlays, dialogs
dependencies: [react]
devDependencies: [typescript]
```

---

```yaml
componentName: Overlay
filename: overlay
category: modals, overlays, backdrop
layout: fixed, overlay
primaryUse: Renders a fullscreen overlay for modals, with optional blur and click handler.
description: A fullscreen overlay component for modals and dialogs, supporting blur, click-to-close, and custom content.
uses: modals, overlays, dialogs, popups
dependencies: [react]
devDependencies: [typescript]
```

---

```yaml
componentName: Backdrop
filename: backdrop
category: modals, overlays, backdrop
layout: fixed, overlay
primaryUse: Provides a background layer for modals and overlays, with optional blur and color.
description: A backdrop component for modals and overlays, supporting blur, color, and custom content for accessibility and focus management.
uses: modals, overlays, dialogs, popups
dependencies: [react]
devDependencies: [typescript]
```

---
