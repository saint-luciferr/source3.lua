# Section:addTextbox
```
<Text Box> Section:addTextbox(<table> options)
```
Creates a text box.

## Parameters
* table `options`
> A table that configures the new text box

| Field      | Type       | Default Value  | Description                      |
| ---------- | ---------- | -------------- | -------------------------------- |
| `title`    | `string`   | `nil text`     | The title of the text box        |
| `default`  | `boolean`  | `nil text`     | The inital value of the text box |
| `callback` | `function` |                | Called when clicked              |

## Returns
* `table`

| Name       | Type       | Description                  |
| ---------- | ---------- | ---------------------------- |
| `Instance` | `Instance` | The UI Element Instance made |
| `Options`  | `table`    | See below                    |

## Options
| Field                          | Type       | Default Value  | Description                                     |
| ------------------------------ | ---------- | -------------- | ----------------------------------------------- |
| `title`                        | `string`   | `nil text`     | The title of the text box                       |
| `default`                      | `boolean`  | `nil text`     | The inital value of the text box                |
| `callback`                     | `function` |                | Called when clicked                             |
| `<?> :Update(<table> Options)` | `method`   |                | Update any of the options present in this table |