 local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()
local Window = OrionLib:MakeWindow({Name = "Thanhden scriptVn", HidePremium = false, SaveConfig = true, ConfigFolder = "VNSCRIPT"})

OrionLib:MakeNotification({
	Name = "Thanhdenscrip",
	Content = "đang load",
	Image = "rbxassetid://4483345998",
	Time = 5
})

local Tab = Window:MakeTab({
	Name = "Thanhden scriptVn",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

local Section = Tab:AddSection({
	Name = "Tab Thanhden scriptVn"
})

Tutab:AddButton({
	Name = "O",
	Callback = function()
   
      		print("button pressed")
  	end    
})

Tab:AddSlider({
	Name = "Slider",
	Min = 0,
	Max = 20,
	Default = 5,
	Color = Color3.fromRGB(255,255,255),
	Increment = 1,
	ValueName = "bananas",
	Callback = function(Value)
		print(Value)
	end    
})

OrionLib:Init()
