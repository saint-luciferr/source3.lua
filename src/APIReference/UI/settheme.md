# UI:setTheme
```
<nil> UI:setTheme(<table> options)
```
Sets the UIs Colour Theme.

## ThemeType
Theme Type is a string, you may choose from this table:

| Name               | Default Value (RGB) | Description                    |
| ------------------ | ------------------- | ------------------------------ |
| `Background`       | `24, 24, 24`        | `The background of the UI`     |
| `Glow`             | `0, 0, 0`           | `The outer glow of the UI`     |
| `Accent`           | `10, 10, 10`        | `The accent colour of the UI`  |
| `LightContrast`    | `20, 20, 20`        | `The 'light' colour of the UI` |
| `DarkContrast`     | `14, 14, 14`        | `The 'dark' colour of the UI`  |
| `TextColor`        | `255, 255, 255`     | `The text color`               |

## Parameters
* table `options`
> A table that configures the theme

| Field      | Type                    | Default Value | Description                       |
| ---------- | ----------------------- | ------------- | --------------------------------- |
| `theme`    | `ThemeType (see above)` |               | `The page you want to select`     |
| `color`    | `Color3`                |               | `Whether to show the page or not` |

## Returns
* nil