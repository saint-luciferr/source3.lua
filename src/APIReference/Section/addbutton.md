# Section:addButton
```
<Button> Section:addButton(<table> options)
```
Creates a button.

## Parameters
* table `options`
> A table that configures the new button

| Field      | Type       | Default Value  | Description             |
| ---------- | ---------- | -------------- | ----------------------- |
| `title`    | `string`   | `nil text`     | The title of the button |
| `callback` | `function` |                | Called when clicked     |

## Returns
* `table`

| Name       | Type       | Description                  |
| ---------- | ---------- | ---------------------------- |
| `Instance` | `Instance` | The UI Element Instance made |
| `Options`  | `table`    | See below                    |

## Options
| Field      | Type       | Default Value  | Description             |
| ---------- | ---------- | -------------- | ----------------------- |
| `title`    | `string`   | `nil text`     | The title of the button |
| `callback` | `function` |                | Called when clicked     |