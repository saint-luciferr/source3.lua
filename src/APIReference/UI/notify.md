# UI:Notify
```
<nil> UI:Notify(<table> options)
```
Creates and displays a notification.

## Parameters
* table `options`
> A table that configures the new Notification

| Field      | Type                        | Default Value  | Description                                                       |
| ---------- | --------------------------- | -------------- | ----------------------------------------------------------------- |
| `title`    | `string`                    | `Notification` | The title of the Notification                                     |
| `context`  | `string`                    | `nil text`     | The description of the Notification                               |
| `callback` | `function(<boolean> value)` |                | Called when the notification is accepted or cancelled. True/False |

## Returns
* nil