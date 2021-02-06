# Section:addKeybind
```
<Keybind> Section:addKeybind(<table> options)
```
Creates a keybind.

## Parameters
* table `options`
> A table that configures the new keybind

| Field             | Type       | Default Value          | Description                    |
| ----------------- | ---------- | ---------------------- | ------------------------------ |
| `title`           | `string`   | `nil text`             | The title of the keybind       |
| `key`             | `KeyCode`  | `Enum.KeyCode.Unknown` | The bounded key to the keybind |
| `callback`        | `function` |                        | Called when key is pressed     |
| `changedCallback` | `function` |                        | Called when keybind is changed |

## Returns
* `table`

| Name       | Type       | Description                  |
| ---------- | ---------- | ---------------------------- |
| `Instance` | `Instance` | The UI Element Instance made |
| `Options`  | `table`    | See below                    |

## Options
| Field             | Type       | Default Value          | Description                    |
| ----------------- | ---------- | ---------------------- | ------------------------------ |
| `title`           | `string`   | `nil text`             | The title of the keybind       |
| `key`             | `KeyCode`  | `Enum.KeyCode.Unknown` | The bounded key to the keybind |
| `callback`        | `function` |                        | Called when key is pressed     |
| `changedCallback` | `function` |                        | Called when keybind is changed |