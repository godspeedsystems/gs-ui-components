```yaml
componentName: ErrorMessage
filename: error-message
category: forms, helpers, feedback
layout: inline, flex
primaryUse: Displays an error message with optional icon for form validation feedback.
description: A small, accessible error message component for forms, supporting custom icons and flexible styling.
uses: forms, validation, feedback
dependencies: [react]
devDependencies: [typescript]
```

---

```yaml
componentName: FormLabel
filename: form-label
category: forms, helpers, label
layout: block, label
primaryUse: Renders a label for form fields, with optional required indicator.
description: An accessible label component for form fields, supporting required state and custom styling.
uses: forms, inputs, accessibility
dependencies: [react]
devDependencies: [typescript]
```

---

```yaml
componentName: HelperText
filename: helper-text
category: forms, helpers, info
layout: inline, text
primaryUse: Provides contextual helper or info text for form fields.
description: A small, flexible helper text component for forms, supporting color variants for info, success, and warning states.
uses: forms, inputs, guidance
dependencies: [react]
devDependencies: [typescript]
```

---

```yaml
componentName: FieldWrapper
filename: field-wrapper
category: forms, helpers, layout
layout: flex, column
primaryUse: Wraps form fields with label, helper, and error message support.
description: A layout component for grouping form fields with associated label, helper text, and error message, improving form structure and accessibility.
uses: forms, inputs, validation
dependencies: [react]
devDependencies: [typescript]
```

---
