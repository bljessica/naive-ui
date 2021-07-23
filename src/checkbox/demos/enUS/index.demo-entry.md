# Checkbox

Yo, yo, check it out.

## Demos

```demo
basic
group
grid
indeterminate
controlled
event
```

## Props

### Checkbox Props

| Name | Type | Default | Description |
| --- | --- | --- | --- |
| checked | `boolean` | `false` | Whether it is selected in the controlled mode. |
| default-checked | `boolean` | `false` | Whether selected by default in uncontrolled mode. |
| disabled | `boolean` | `false` | Whether to disable. |
| focusable | `boolean` | `true` | Whether to focus on selection. |
| indeterminate | `boolean` | `false` | Whether partly selected. |
| label | `string` | `undefined` | Checkbox label. |
| value | `string \| number` | `undefined` | The value of the checkbox to be used in checkbox group. |
| on-update:checked | `(checked: boolean) => void` | `undefined` | Callback function triggered on checked status changes. |

### Checkbox Group Props

| Name | Type | Default | Description |
| --- | --- | --- | --- |
| disabled | `boolean` | `false` | Whether the checkbox group is disabled. |
| default-value | `Array<string \| number>` | `null` | Checkbox group's default selected value. |
| max | `number` | `undefined` | The maximum number of checkboxes that can be checked. |
| min | `number` | `undefined` | The minimum number of checkboxes that can be checked. |
| value | `Array<string \| number> \| null` | `undefined` | Controlled value of checkbox group. |
| on-update:value | `(value: string \| number)` | `undefined` | Callback when checkbox group's value changes. |

## Slots

### Checkbox Slots

| Name    | Parameters | Description              |
| ------- | ---------- | ------------------------ |
| default | `()`       | Content of the checkbox. |

### Checkbox Group Slots

| Name    | Parameters | Description                    |
| ------- | ---------- | ------------------------------ |
| default | `()`       | Content of the checkbox group. |
