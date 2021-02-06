# Section:addColorPicker
```
<Color Picker> Section:addColorPicker(<table> options)
```
Creates a color picker.

## Parameters
* table `options`
> A table that configures the new color picker

| Field      | Type       | Default Value                   |  Description                         |
| ---------- | ---------- | ------------------------------- | ------------------------------------ |
| `title`    | `string`   | `nil text`                      | The title of the color picker        |
| `default`  | `Color3`   | `Color3.fromRGB(255, 150, 150)` | The inital color of the color picker |
| `callback` | `function` |                                 | Called when color changed            |

## Returns
* `table`

| Name       | Type       | Description                  |
| ---------- | ---------- | ---------------------------- |
| `Instance` | `Instance` | The UI Element Instance made |
| `Options`  | `table`    | See below                    |

## Options
| Field      | Type       | Default Value                   |  Description                         |
| ---------- | ---------- | ------------------------------- | ------------------------------------ |
| `title`    | `string`   | `nil text`                      | The title of the color picker        |
| `default`  | `Color3`   | `Color3.fromRGB(255, 150, 150)` | The inital color of the color picker |
| `callback` | `function` |                                 | Called when color changed            |