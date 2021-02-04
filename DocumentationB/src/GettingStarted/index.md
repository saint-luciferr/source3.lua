# Getting Started
Load the library from the Github repo using `loadstring` and `game:HttpGet`

```lua
local Venyx = loadstring(game:HttpGet("https://raw.githubusercontent.com/Stefanuk12/Venyx-UI-Library/main/source.lua"))()
```

Create a new UI using the `Venyx.new` function:

```lua
local Venyx = loadstring(game:HttpGet("https://raw.githubusercontent.com/Stefanuk12/Venyx-UI-Library/main/source.lua"))()

local UI = Venyx.new("Getting Started")
```

A page allows you add sections to a new UI. Create a page using the UI:addPage function:

```lua
local Venyx = loadstring(game:HttpGet("https://raw.githubusercontent.com/Stefanuk12/Venyx-UI-Library/main/source.lua"))()

local UI = Venyx.new("Getting Started")

local Page = UI:addPage("Main")
```

Then a section allows you to add UI elements to the section. Create a new section using the `UI:addSection` function:

```lua
local Venyx = loadstring(game:HttpGet("https://raw.githubusercontent.com/Stefanuk12/Venyx-UI-Library/main/source.lua"))()

local UI = Venyx.new("Getting Started")

local Page = UI:addPage("Main")

local Section = Page:addSection("Section")
```

Now we can add UI elements by calling their corresponding methods. For example, if we want to add a button to the UI, we can call `Section:addButton`:

```lua
local Venyx = loadstring(game:HttpGet("https://raw.githubusercontent.com/Stefanuk12/Venyx-UI-Library/main/source.lua"))()

local UI = Venyx.new("Getting Started")

local Page = UI:addPage("Main")

local Section = Page:addSection("Section")

Section:addButton({
    title = "Click Me!",
    callback = function()
        print("Clicked!")
    end
})
```

If you did everything correctly, you should get a UI which looks like this:

![UI](./UI.png)

Clicking the button will output a message in the developer console:

![Console Ouput](./ConsoleOutput.png)

Read the API Reference section of this documentation to learn about the available UI element methods.