local library = game:GetObjects("url")[1];
local window = library.init({
    theme = "Dark",
    Highlight = Color3.fromRGB(69, 140, 255)
})

local tab = window:Tab({
	title = "Script"
})

local Toggle = tab:Toggle({
	title = "Toggle",
	false,
	callback = function(value)
		print(value)
	end,
})

local Slider = tab:Slider({
	title = "Slider",
	{min = 0, def = 0.5, max = 1},
	callback = function(value)
		print(value)
	end,
})

local Button = tab:Button({
	title = "Button",
	callback = function()
		print("Pressed")
	end,
})
-- window external features:
--[[
local pluginUI = window:FetchUI(); -- Gets UI;
window:Select(Tab); -- Selects page;

window:Toggle(true); -- Visible;

window:Close(Enum.KeyCode.F); -- Bindable Visibility;
window:Close(); -- Destroys UI;
]]--
