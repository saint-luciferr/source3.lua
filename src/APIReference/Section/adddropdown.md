# Section:addDropdown
```
<Dropdown> Section:addDropdown(<table> options)
```
Creates a dropdown.

## Parameters
* table `options`
> A table that configures the new dropdown

| Field        | Type       | Default Value      | Description                                 |
| ------------ | ---------- | ------------------ | ------------------------------------------- |
| `title`      | `string`   | `nil text`         | The title of the dropdown                   |
| `default`    | `string`   |                    | The default value of thing selected         |
| `list`       | `table`    | `{}`               | The inital value of the dropdown            |
| `backuplist` | `table`    | `Options.list`     | The backup list when everything is removed  |
| `callback`   | `function` |                    | Called when clicked                         |

## Returns
* `table`

| Name       | Type       | Description                  |
| ---------- | ---------- | ---------------------------- |
| `Instance` | `Instance` | The UI Element Instance made |
| `Options`  | `table`    | See below                    |

## Options
| Field        | Type       | Default Value      | Description                                 |
| ------------ | ---------- | ------------------ | ------------------------------------------- |
| `title`      | `string`   | `nil text`         | The title of the dropdown                   |
| `default`    | `string`   |                    | The default value of thing selected         |
| `list`       | `table`    | `{}`               | The inital value of the dropdown            |
| `backuplist` | `table`    | `Options.list`     | The backup list when everything is removed  |
| `callback`   | `function` |                    | Called when clicked                         |