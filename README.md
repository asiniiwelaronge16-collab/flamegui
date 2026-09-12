--[[
 
     Created by flamemmbu
     Discord: https://discord.gg/J2hCyNtJk
     Roblox: https://www.roblox.com/share/g/97718870
     Youtube: https://www.youtube.com/channel/UCJk-zT_SXJddk7B1wXuuuGg
     ]]

local CoreGui = game:GetService("CoreGui")
local gui = CoreGui:FindFirstChild("CrimsonUI")

if gui then
game:GetService("StarterGui"):SetCore("SendNotification", {
		Title = "FlameGUI",
		Text = "FlameGUI revival is already loaded!",
		Icon = "http://www.roblox.com/asset/?id=117945919346512",
		Duration = 1.5,
	})
else
loadstring(game:HttpGet("https://raw.githubusercontent.com/hyperionhax/c00lgui/main/Source.lua"))()
end
