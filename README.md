local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("Tara Hub", "BloodTheme")

local Tab = Window:NewTab("main")
local Section = Tab:NewSection("Fake level")

Section:NewButton("กดตรงนี้", "Tara Hub", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/ToukaKung/fake-level/main/README.md"))()
end)

local Section = Tab:NewSection("Fake v4")

Section:NewButton("แปลงร่าง", "Tara Hub", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/ToukaKung/v4/main/README.md"))()
end)
Section:NewButton("อนิเมชั่น", "Tara Hub", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/ToukaKung/v4x2/main/README.md"))()
end)

local Tab = Window:NewTab("credit")
local Section = Tab:NewSection("! aExeur#4748")
local Section = Tab:NewSection("discord.gg/mzmMvMsrUM")

Section:NewKeybind("กดเพื่อเปลื่ยนปุ่ม", "KeybindInfo", Enum.KeyCode.F, function()
	Library:ToggleUI()
end)

