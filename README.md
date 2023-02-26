# CLAY_HUB
CLAY_HUB
local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("CLAY-HUB", "Synapse")

local Tab = Window:NewTab("Cardits")
local Section = Tab:NewSection("Cardits")
local Section = Tab:NewSection("Edit UI By")
local Section = Tab:NewSection("CLAY-HUB")
local Section = Tab:NewSection("Edit Script By")
local Section = Tab:NewSection("CLAY-HUB")
local Tab = Window:NewTab("Game")
local Section = Tab:NewSection("Game Script")
local Section = Tab:NewSection("mad-city")
Section:NewButton("mad-city", "mad-city", function()

end)
local Section = Tab:NewSection("Kill Monsters to Save Princess")
Section:NewButton("Kill Monsters to Save Princess", "Kill Monsters to Save Princess", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/NOOBHUBX/Monsters/main/NOOBHUB.Lua"))()
setclipboard("NOOBKEY_MageTycoon")
end)
