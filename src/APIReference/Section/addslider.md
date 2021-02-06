# Section:addSlider
```
<Slider> Section:addSlider(<table> options)
```
Creates a slider.

## Parameters
* table `options`
> A table that configures the new slider

| Field      | Type       | Default Value       |  Description                     |
| ---------- | ---------- | ------------------- | -------------------------------- |
| `title`    | `string`   | `nil text`          | The title of the slider          |
| `min`      | `number`   | `0`                 | The minimum value of the slider  |
| `default`  | `number`   | `Options.min`       | The inital value of the slider   |
| `max`      | `number`   | `100`               | The maximum value of the slider  |
| `value`    | `number`   | `Options.default`   | The current value of the slider  |
| `callback` | `function` |                     | Called when slider changed       |

## Returns
* `table`

| Name       | Type       | Description                  |
| ---------- | ---------- | ---------------------------- |
| `Instance` | `Instance` | The UI Element Instance made |
| `Options`  | `table`    | See below                    |

## Options
| Field      | Type       | Default Value       |  Description                     |
| ---------- | ---------- | ------------------- | -------------------------------- |
| `title`    | `string`   | `nil text`          | The title of the slider          |
| `min`      | `number`   | `0`                 | The minimum value of the slider  |
| `default`  | `number`   | `Options.min`       | The inital value of the slider   |
| `max`      | `number`   | `100`               | The maximum value of the slider  |
| `value`    | `number`   | `Options.default`   | The current value of the slider  |
| `callback` | `function` |                     | Called when slider changed       |