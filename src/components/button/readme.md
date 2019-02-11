---
title: Button
---

# Button
Simple wrapper for the `<button>` element.

### Import
```javascript
import '@amber-ds/components/button';
```

### Markup
```html
<amber-button>
  Button label here
</amber-button>
```

### Attributes

| Name | Type | Default value | Description |
|------|------|---------------|-------------|
| `priority` | `String` | `'secondary'` | The visual priority of the element, options are: `'primary'`, `'secondary'` and `'tertiary'` |
| `state` | `String` | `''` | Visual state, options are: empty, `success`, `error`, `warning`, `info` |
| `disabled` | `Boolean` | `false` | If the element is disabled |
| `fitted` | `Boolean` | `false` | If the element will fit all the available space in width |
| `progress` | `String` | `''` | Switch content to progress states, available options: empty, `'pending'`, `'error'` and `'success'` |

### Storybook
<iframe width="100%" height="500px" src="https://bitrockteam.github.io/amber-components/?selectedKind=Button&selectedStory=Playground&full=0&addons=1&stories=0&panelRight=0&addonPanel=storybooks%2Fstorybook-addon-knobs"></iframe>