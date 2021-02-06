# Section:addToggle
```
<Toggle> Section:addToggle(<table> options)
```
Creates a toggle.

## Parameters
* table `options`
> A table that configures the new toggle

| Field      | Type       | Default Value  | Description                    |
| ---------- | ---------- | -------------- | ------------------------------ |
| `title`    | `string`   | `nil text`     | The title of the button        |
| `default`  | `boolean`  | `false`        | The inital value of the toggle |
| `callback` | `function` |                | Called when clicked            |

## Returns
* `table`

| Name       | Type       | Description                  |
| ---------- | ---------- | ---------------------------- |
| `Instance` | `Instance` | The UI Element Instance made |
| `Options`  | `table`    | See below                    |

## Options
| Field                          | Type       | Default Value  | Description                                     |
| ------------------------------ | ---------- | -------------- | ----------------------------------------------- |
| `title`                        | `string`   | `nil text`     | The title of the button                         |
| `default`                      | `boolean`  | `false`        | The inital value of the toggle                  |
| `callback`                     | `function` |                | Called when clicked                             |
| `<?> :Update(<table> Options)` | `method`   |                | Update any of the options present in this table |