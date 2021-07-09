--Made by Lynx._.x#3236
--loadstring(game:HttpGet(""))()

local RedFirev20 = Instance.new("ScreenGui")
local MainFrame = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local Split = Instance.new("TextLabel")
local Name_TAB1 = Instance.new("TextLabel")
local Tabs = Instance.new("TextButton")
local Tab1 = Instance.new("TextButton")
local TABSTART = Instance.new("Frame")
local Name1 = Instance.new("TextButton")
local UICorner_2 = Instance.new("UICorner")
local Name2 = Instance.new("TextButton")
local UICorner_3 = Instance.new("UICorner")
local Name3 = Instance.new("TextButton")
local UICorner_4 = Instance.new("UICorner")
local JOINDC = Instance.new("TextButton")
local UICorner_5 = Instance.new("UICorner")
local Name4 = Instance.new("TextButton")
local UICorner_6 = Instance.new("UICorner")
local Info = Instance.new("TextButton")
local UICorner_7 = Instance.new("UICorner")
local Tab_Player = Instance.new("Frame")
local UICorner_8 = Instance.new("UICorner")
local Name1_2 = Instance.new("TextButton")
local UICorner_9 = Instance.new("UICorner")

--Properties:

RedFirev20.Name = "RedFire-v2.0"
RedFirev20.Parent = game.CoreGui
RedFirev20.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

MainFrame.Name = "MainFrame"
MainFrame.Parent = RedFirev20
MainFrame.BackgroundColor3 = Color3.fromRGB(68, 68, 68)
MainFrame.Position = UDim2.new(0.297163993, 0, 0.203680992, 0)
MainFrame.Size = UDim2.new(0, 657, 0, 452)
MainFrame.Active = true
MainFrame.Draggable = true

UICorner.Parent = MainFrame

Split.Name = "Split"
Split.Parent = MainFrame
Split.BackgroundColor3 = Color3.fromRGB(10, 161, 255)
Split.BorderSizePixel = 0
Split.Position = UDim2.new(0.00152207003, 0, 0.0862831846, 0)
Split.Size = UDim2.new(0, 115, 0, 2)
Split.Font = Enum.Font.SourceSans
Split.Text = ""
Split.TextColor3 = Color3.fromRGB(0, 0, 0)
Split.TextSize = 14.000

Name_TAB1.Name = "Name_TAB-1"
Name_TAB1.Parent = MainFrame
Name_TAB1.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Name_TAB1.BackgroundTransparency = 1.000
Name_TAB1.Position = UDim2.new(0.0304414015, 0, 0, 0)
Name_TAB1.Size = UDim2.new(0, 76, 0, 50)
Name_TAB1.Font = Enum.Font.SourceSansBold
Name_TAB1.Text = "Universal RedFireHub"
Name_TAB1.TextColor3 = Color3.fromRGB(255, 255, 255)
Name_TAB1.TextSize = 14.000

Tabs.Name = "Tabs"
Tabs.Parent = MainFrame
Tabs.BackgroundColor3 = Color3.fromRGB(57, 57, 57)
Tabs.BorderSizePixel = 0
Tabs.Position = UDim2.new(0, 0, 0.11061947, 0)
Tabs.Size = UDim2.new(0, 126, 0, 50)
Tabs.Font = Enum.Font.SourceSansBold
Tabs.Text = "TABS"
Tabs.TextColor3 = Color3.fromRGB(255, 255, 255)
Tabs.TextSize = 14.000

Tab1.Name = "Tab1"
Tab1.Parent = MainFrame
Tab1.BackgroundColor3 = Color3.fromRGB(57, 57, 57)
Tab1.BorderSizePixel = 0
Tab1.Position = UDim2.new(0.00152207003, 0, 0.243362829, 0)
Tab1.Size = UDim2.new(0, 125, 0, 50)
Tab1.Font = Enum.Font.SourceSansBold
Tab1.Text = "Player"
Tab1.TextColor3 = Color3.fromRGB(255, 255, 255)
Tab1.TextSize = 14.000
Tab1.MouseButton1Click:Connect(function()
	TABSTART.Visible = false
	Tab1.Visible = true
end)

TABSTART.Name = "TABSTART"
TABSTART.Parent = MainFrame
TABSTART.BackgroundColor3 = Color3.fromRGB(61, 61, 61)
TABSTART.BorderSizePixel = 0
TABSTART.Position = UDim2.new(0.19178082, 0, 0.024336284, 0)
TABSTART.Size = UDim2.new(0, 514, 0, 417)
TABSTART.MouseButton1Click:Connect(function()
	TABSTART.Visible = true
	Tab1.Visible = false
end)

Name1.Name = "Name1"
Name1.Parent = TABSTART
Name1.BackgroundColor3 = Color3.fromRGB(59, 59, 59)
Name1.BorderSizePixel = 0
Name1.Position = UDim2.new(0.0240303967, 0, 0.0245060548, 0)
Name1.Size = UDim2.new(0, 84, 0, 50)
Name1.Font = Enum.Font.SourceSansBold
Name1.Text = "Kill all"
Name1.TextColor3 = Color3.fromRGB(255, 255, 255)
Name1.TextSize = 14.000
Name1.MouseButton1Down:connect(function()
	local plr = game.Players.LocalPlayer
	plr.Character.Humnoid.Health = 0
end)

UICorner_2.Parent = Name1

Name2.Name = "Name2"
Name2.Parent = TABSTART
Name2.BackgroundColor3 = Color3.fromRGB(59, 59, 59)
Name2.BorderSizePixel = 0
Name2.Position = UDim2.new(0.2010732, 0, 0.0245060548, 0)
Name2.Size = UDim2.new(0, 84, 0, 50)
Name2.Font = Enum.Font.SourceSansBold
Name2.Text = "Erage Server"
Name2.TextColor3 = Color3.fromRGB(255, 255, 255)
Name2.TextSize = 14.000
Name2.MouseButton1Down:connect(function()
	local plr = game.Players.LocalPlayer
	plr:Kick("ErageServer_Folder Was not Found! PLEASE UPDATE UR SCRIPT !")
end)

UICorner_3.Parent = Name2

Name3.Name = "Name3"
Name3.Parent = TABSTART
Name3.BackgroundColor3 = Color3.fromRGB(59, 59, 59)
Name3.BorderSizePixel = 0
Name3.Position = UDim2.new(0.385898113, 0, 0.0245060548, 0)
Name3.Size = UDim2.new(0, 295, 0, 50)
Name3.Font = Enum.Font.SourceSansBold
Name3.Text = "Copy DiscordLink"
Name3.TextColor3 = Color3.fromRGB(255, 255, 255)
Name3.TextSize = 14.000
Name3.MouseButton1Down:connect(function()
	local plr = game.Players.LocalPlayer
	plr:Kick("https://discord.gg/Ksf2u5wTNy")
end)

UICorner_4.Parent = Name3

JOINDC.Name = "JOINDC"
JOINDC.Parent = TABSTART
JOINDC.BackgroundColor3 = Color3.fromRGB(59, 59, 59)
JOINDC.BorderSizePixel = 0
JOINDC.Position = UDim2.new(-0.00126143277, 0, 0.165992871, 0)
JOINDC.Size = UDim2.new(0, 514, 0, 50)
JOINDC.Font = Enum.Font.SourceSansBold
JOINDC.Text = "Join Discord"
JOINDC.TextColor3 = Color3.fromRGB(255, 255, 255)
JOINDC.TextSize = 14.000
JOINDC.MouseButton1Down:connect(function()
	local plr = game.Players.LocalPlayer
	plr:Kick("https://discord.gg/Ksf2u5wTNy")
end)


UICorner_5.Parent = JOINDC

Name4.Name = "Name4"
Name4.Parent = TABSTART
Name4.BackgroundColor3 = Color3.fromRGB(59, 59, 59)
Name4.BorderSizePixel = 0
Name4.Position = UDim2.new(0.0240304004, 0, 0.302683532, 0)
Name4.Size = UDim2.new(0, 84, 0, 50)
Name4.Font = Enum.Font.SourceSansBold
Name4.Text = "Kick all"
Name4.TextColor3 = Color3.fromRGB(255, 255, 255)
Name4.TextSize = 14.000
Name4.MouseButton1Down:connect(function()
	local plr = game.Players.LocalPlayer
	plr:Kick("I belive i can Kick... ohh U can!")
end)

UICorner_6.Parent = Name4

Info.Name = "Info"
Info.Parent = TABSTART
Info.BackgroundColor3 = Color3.fromRGB(59, 59, 59)
Info.BorderSizePixel = 0
Info.Position = UDim2.new(0.0240303967, 0, 0.465753138, 0)
Info.Size = UDim2.new(0, 492, 0, 222)
Info.Font = Enum.Font.SourceSansBold
Info.Text = "Add More Soon Get Updated Script at Github or Join Our Discord"
Info.TextColor3 = Color3.fromRGB(255, 255, 255)
Info.TextSize = 14.000

UICorner_7.Parent = Info

Tab_Player.Name = "Tab_Player"
Tab_Player.Parent = MainFrame
Tab_Player.BackgroundColor3 = Color3.fromRGB(61, 61, 61)
Tab_Player.Position = UDim2.new(0.190258756, 0, 0.024336284, 0)
Tab_Player.Size = UDim2.new(0, 514, 0, 417)
Tab_Player.Visible = false

UICorner_8.Parent = Tab_Player

Name1_2.Name = "Name1"
Name1_2.Parent = Tab_Player
Name1_2.BackgroundColor3 = Color3.fromRGB(59, 59, 59)
Name1_2.BorderSizePixel = 0
Name1_2.Position = UDim2.new(0.0240303967, 0, 0.0245060548, 0)
Name1_2.Size = UDim2.new(0, 492, 0, 398)
Name1_2.Font = Enum.Font.SourceSansBold
Name1_2.Text = "UGH... Dont Expected That Player and Other Tabs Will be added in The First Update Stay Tuned"
Name1_2.TextColor3 = Color3.fromRGB(255, 255, 255)
Name1_2.TextSize = 14.000

UICorner_9.Parent = Name1_2
