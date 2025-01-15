-- beta 1.0
local Fluent = loadstring(game:HttpGet("https://github.com/dawid-scripts/Fluent/releases/latest/download/main.lua"))()

local Window = Fluent:CreateWindow({
    Title = "carro roxo hub" .. Fluent.Version,
    TabWidth = 160, Size = UDim2.fromOffset(580, 460), Theme = "Dark"
})

local Tabs = {
    Main = Window:AddTab({ Title = "bem vindo" }),
    farms = Window:AddTab({ Title = "farms" }),
    player = Window:AddTab({ Title = "player", Icon = "player"}),
    Settings = Window:AddTab({ Title = "Settings", Icon = "settings" })
}

Tabs.Main:AddParagraph({ Title = "criator:hugo", Content = "ola" })

Tabs.farms:AddButton({ Title = "autofarm", Callback = function()
loadstring(game:HttpGet("https://github.com/HUGOHUGOHUGOHUGOHUGOHUGOHUGOHUGO/Jdhdhdhdh/blob/main/README.md"))()
end })
        
        local player = Tab:player("MyToggle", 
{
    Title = "player", 
    Description = "Toggle description",
    Default = false, -- esse "," e preciso coloque em qualquer situação 
    Callback = function(state)
	if state then
	    loadstring(game:HttpGet("https://github.com/HUGOHUGOHUGOHUGOHUGOHUGOHUGOHUGO/Jdhdhdhdh/blob/main/README.md"))()
	else
	    Fluent:Notify({ Title = "Notification", Content = "This is a notification" })
        end
    end 
})
