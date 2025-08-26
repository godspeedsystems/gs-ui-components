```yaml
componentName: ProgressBar
filename: progress-bar
category: status, indicators, progress
layout: block, bar
primaryUse: Displays a horizontal progress bar with customizable color and label.
description: A progress bar component for visualizing completion percentage, supporting color variants and labels.
uses: forms, onboarding, dashboards, uploads
dependencies: [react]
devDependencies: [typescript]
```

---

```yaml
componentName: Spinner
filename: spinner
category: status, indicators, loading
layout: inline, spinner
primaryUse: Shows a spinning loader for indicating loading state.
description: A spinner component for loading indicators, supporting size and color variants for flexible UI feedback.
uses: loading, async actions, dashboards
dependencies: [react]
devDependencies: [typescript]
```

---

```yaml
componentName: Loader
filename: loader
category: status, indicators, loading
layout: inline, spinner
primaryUse: Displays a circular loader for indicating loading state, with customizable size and color.
description: A circular loader component for loading indicators, supporting size and color variants for flexible UI feedback.
uses: loading, async actions, dashboards
dependencies: [react]
devDependencies: [typescript]
```

---

```yaml
componentName: Alert
filename: alert
category: status, indicators, alert
layout: flex, alert
primaryUse: Renders an alert message with type, icon, and optional close button.
description: An alert component for displaying messages, supporting type (success, error, info, warning), icons, and dismiss functionality.
uses: notifications, forms, dashboards, feedback
dependencies: [react]
devDependencies: [typescript]
```

---

```yaml
componentName: Chip
filename: chip
category: status, indicators, chip
layout: inline, pill
primaryUse: Displays a pill-shaped chip with label, color, and optional close button.
description: A chip component for status, tags, or filters, supporting color variants and dismiss functionality.
uses: filters, tags, dashboards, lists
dependencies: [react]
devDependencies: [typescript]
```

---

```yaml
componentName: Badge
filename: badge
category: status, indicators, badge
layout: inline, badge
primaryUse: Renders a badge with label, color, and optional dot indicator.
description: A badge component for status, notifications, or counts, supporting color variants and dot indicator.
uses: notifications, lists, dashboards, avatars
dependencies: [react]
devDependencies: [typescript]
```

---
