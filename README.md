-- Gui to Lua
-- Version: 3.2
 
local reloaded = false
 
if game.CoreGui:FindFirstChild("Order1Gui") ~= nil then
	game.CoreGui.Order1Gui.Parent = nil
	reloaded = true
	task.wait(0.7)
end
 
-- Instances:
 
local Order1Gui = Instance.new("ScreenGui")
local MainFrame = Instance.new("Frame")
local TabsFrame = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local HideButton = Instance.new("ImageButton")
local UICorner_2 = Instance.new("UICorner")
local DupeButton = Instance.new("ImageButton")
local UICorner_3 = Instance.new("UICorner")
local InfoButton = Instance.new("ImageButton")
local UICorner_4 = Instance.new("UICorner")
local UICorner_5 = Instance.new("UICorner")
local InfoFrame = Instance.new("Frame")
local UICorner_6 = Instance.new("UICorner")
local PlayerInfoFrame = Instance.new("Frame")
local UICorner_7 = Instance.new("UICorner")
local PlayerName = Instance.new("TextLabel")
local Stand = Instance.new("TextLabel")
local FAQFrame = Instance.new("Frame")
local UICorner_8 = Instance.new("UICorner")
local Hint = Instance.new("TextLabel")
local FAQItself = Instance.new("ScrollingFrame")
local Q1 = Instance.new("TextLabel")
local UIListLayout = Instance.new("UIListLayout")
local A1 = Instance.new("TextLabel")
local Q2 = Instance.new("TextLabel")
local A2 = Instance.new("TextLabel")
local DupeFrame = Instance.new("Frame")
local UICorner_9 = Instance.new("UICorner")
local DupeFrame_2 = Instance.new("Frame")
local UICorner_10 = Instance.new("UICorner")
local Hint_2 = Instance.new("TextLabel")
local Dupe = Instance.new("TextButton")
local UICorner_11 = Instance.new("UICorner")
local SaveData = Instance.new("TextButton")
local UICorner_12 = Instance.new("UICorner")
local StatusInfoFrame = Instance.new("Frame")
local UICorner_13 = Instance.new("UICorner")
local PlayerName_2 = Instance.new("TextLabel")
local Stand_2 = Instance.new("TextLabel")
local LogFrame = Instance.new("Frame")
local UICorner_14 = Instance.new("UICorner")
local Hint_3 = Instance.new("TextLabel")
local Logs = Instance.new("ScrollingFrame")
local UIListLayout_2 = Instance.new("UIListLayout")
local GoodLog = Instance.new("TextLabel")
local BadLog = Instance.new("TextLabel")
local ShowButton = Instance.new("ImageButton")
local UICorner_15 = Instance.new("UICorner")
 
--Properties:
 
Order1Gui.Name = "Order1Gui"
Order1Gui.Parent = game.CoreGui
Order1Gui.Enabled = true
 
MainFrame.Name = "MainFrame"
MainFrame.Parent = Order1Gui
MainFrame.BackgroundColor3 = Color3.fromRGB(45, 47, 53)
MainFrame.BorderSizePixel = 0
MainFrame.Position = UDim2.new(0.24363327, 0, 0.273809522, 0)
MainFrame.Size = UDim2.new(0, 364, 0, 265)
MainFrame.Visible = true
MainFrame.Draggable = true
MainFrame.Active = true
 
TabsFrame.Name = "TabsFrame"
TabsFrame.Parent = MainFrame
TabsFrame.BackgroundColor3 = Color3.fromRGB(29, 30, 34)
TabsFrame.BorderSizePixel = 0
TabsFrame.LayoutOrder = 1
TabsFrame.Position = UDim2.new(-0.0283447132, 0, -0.0286611877, 0)
TabsFrame.Size = UDim2.new(0, 55, 0, 280)
TabsFrame.Draggable = true
 
UICorner.Parent = TabsFrame
 
HideButton.Name = "HideButton"
HideButton.Parent = TabsFrame
HideButton.BackgroundColor3 = Color3.fromRGB(99, 103, 116)
HideButton.Position = UDim2.new(0.0909090936, 0, 0.846428573, 0)
HideButton.Size = UDim2.new(0, 45, 0, 29)
HideButton.Image = "rbxassetid://54479709"
 
UICorner_2.Parent = HideButton
 
DupeButton.Name = "DupeButton"
DupeButton.Parent = TabsFrame
DupeButton.BackgroundColor3 = Color3.fromRGB(99, 103, 116)
DupeButton.Position = UDim2.new(0.0909090936, 0, 0.232142851, 0)
DupeButton.Size = UDim2.new(0, 45, 0, 45)
DupeButton.Image = "rbxassetid://2876994160"
 
UICorner_3.Parent = DupeButton
 
InfoButton.Name = "InfoButton"
InfoButton.Parent = TabsFrame
InfoButton.BackgroundColor3 = Color3.fromRGB(131, 136, 153)
InfoButton.Position = UDim2.new(0.0909090936, 0, 0.0249999911, 0)
InfoButton.Size = UDim2.new(0, 45, 0, 45)
InfoButton.Image = "rbxassetid://8130360540"
 
UICorner_4.Parent = InfoButton
 
UICorner_5.Parent = MainFrame
 
InfoFrame.Name = "InfoFrame"
InfoFrame.Parent = MainFrame
InfoFrame.BackgroundColor3 = Color3.fromRGB(60, 63, 72)
InfoFrame.BorderSizePixel = 0
InfoFrame.Position = UDim2.new(0.142857149, 0, 0.0377358496, 0)
InfoFrame.Size = UDim2.new(0, 304, 0, 248)
 
UICorner_6.Parent = InfoFrame
 
PlayerInfoFrame.Name = "PlayerInfoFrame"
PlayerInfoFrame.Parent = InfoFrame
PlayerInfoFrame.BackgroundColor3 = Color3.fromRGB(39, 41, 47)
PlayerInfoFrame.Position = UDim2.new(0.0296052638, 0, 0.0322580636, 0)
PlayerInfoFrame.Size = UDim2.new(0, 286, 0, 100)
 
UICorner_7.Parent = PlayerInfoFrame
 
PlayerName.Name = "PlayerName"
PlayerName.Parent = PlayerInfoFrame
PlayerName.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
PlayerName.BackgroundTransparency = 1.000
PlayerName.Position = UDim2.new(0.150349647, 0, 0.0500000007, 0)
PlayerName.Size = UDim2.new(0, 200, 0, 50)
PlayerName.Font = Enum.Font.SourceSans
PlayerName.Text = "Username: PLAYERNAME"
PlayerName.TextColor3 = Color3.fromRGB(255, 255, 255)
PlayerName.TextSize = 26.000
 
Stand.Name = "Stand"
Stand.Parent = PlayerInfoFrame
Stand.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Stand.BackgroundTransparency = 1.000
Stand.Position = UDim2.new(0.150349647, 0, 0.439999998, 0)
Stand.Size = UDim2.new(0, 200, 0, 50)
Stand.Font = Enum.Font.SourceSans
Stand.Text = "Stand: STANDNAME"
Stand.TextColor3 = Color3.fromRGB(255, 255, 255)
Stand.TextSize = 26.000
 
FAQFrame.Name = "FAQFrame"
FAQFrame.Parent = InfoFrame
FAQFrame.BackgroundColor3 = Color3.fromRGB(39, 41, 47)
FAQFrame.Position = UDim2.new(0.0296052638, 0, 0.463709682, 0)
FAQFrame.Size = UDim2.new(0, 286, 0, 127)
 
UICorner_8.Parent = FAQFrame
 
Hint.Name = "Hint"
Hint.Parent = FAQFrame
Hint.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Hint.BackgroundTransparency = 1.000
Hint.Position = UDim2.new(0.150349647, 0, -0.00511806225, 0)
Hint.Size = UDim2.new(0, 200, 0, 27)
Hint.Font = Enum.Font.SourceSans
Hint.Text = "FAQ"
Hint.TextColor3 = Color3.fromRGB(255, 255, 255)
Hint.TextSize = 26.000
 
FAQItself.Name = "FAQItself"
FAQItself.Parent = FAQFrame
FAQItself.Active = true
FAQItself.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
FAQItself.BackgroundTransparency = 1.000
FAQItself.BorderSizePixel = 0
FAQItself.Position = UDim2.new(0.0244755242, 0, 0.204724416, 0)
FAQItself.Size = UDim2.new(0, 279, 0, 100)
FAQItself.CanvasPosition = Vector2.new(0, 128.599991)
FAQItself.CanvasSize = UDim2.new(0, 0, 1.79999995, 0)
 
Q1.Name = "Q1"
Q1.Parent = FAQItself
Q1.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Q1.BackgroundTransparency = 1.000
Q1.Position = UDim2.new(0, 0, -1.28599977, 0)
Q1.Size = UDim2.new(0, 262, 0, 50)
Q1.Font = Enum.Font.SourceSansBold
Q1.Text = "Q: How to dupe items?"
Q1.TextColor3 = Color3.fromRGB(255, 255, 255)
Q1.TextSize = 23.000
Q1.TextXAlignment = Enum.TextXAlignment.Left
 
UIListLayout.Parent = FAQItself
UIListLayout.SortOrder = Enum.SortOrder.LayoutOrder
UIListLayout.Padding = UDim.new(-0.100000001, 0)
 
A1.Name = "A1"
A1.Parent = FAQItself
A1.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
A1.BackgroundTransparency = 1.000
A1.Position = UDim2.new(0, 0, -1.01459956, 0)
A1.Size = UDim2.new(0, 262, 0, 99)
A1.Font = Enum.Font.SourceSans
A1.Text = "A: That's simple. Launch Roblox Multi, click \"Save Data\" and then click \"Dupe\"."
A1.TextColor3 = Color3.fromRGB(255, 255, 255)
A1.TextSize = 23.000
A1.TextWrapped = true
A1.TextXAlignment = Enum.TextXAlignment.Left
 
Q2.Name = "Q2"
Q2.Parent = FAQItself
Q2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Q2.BackgroundTransparency = 1.000
Q2.Position = UDim2.new(0, 0, -0.253199756, 0)
Q2.Size = UDim2.new(0, 262, 0, 50)
Q2.Font = Enum.Font.SourceSansBold
Q2.Text = "Q: Can I get banned for this?"
Q2.TextColor3 = Color3.fromRGB(255, 255, 255)
Q2.TextSize = 23.000
Q2.TextXAlignment = Enum.TextXAlignment.Left
 
A2.Name = "A2"
A2.Parent = FAQItself
A2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
A2.BackgroundTransparency = 1.000
A2.Position = UDim2.new(0, 0, 0.0182000734, 0)
A2.Size = UDim2.new(0, 262, 0, 99)
A2.Font = Enum.Font.SourceSans
A2.Text = "A: Absolutely not. This dupe method is undetectable, and you will not get banned."
A2.TextColor3 = Color3.fromRGB(255, 255, 255)
A2.TextSize = 23.000
A2.TextWrapped = true
A2.TextXAlignment = Enum.TextXAlignment.Left
 
DupeFrame.Name = "DupeFrame"
DupeFrame.Parent = MainFrame
DupeFrame.BackgroundColor3 = Color3.fromRGB(60, 63, 72)
DupeFrame.BorderSizePixel = 0
DupeFrame.Position = UDim2.new(0.142857149, 0, 0.0377358496, 0)
DupeFrame.Size = UDim2.new(0, 304, 0, 248)
DupeFrame.Visible = false
 
UICorner_9.Parent = DupeFrame
 
DupeFrame_2.Name = "DupeFrame"
DupeFrame_2.Parent = DupeFrame
DupeFrame_2.BackgroundColor3 = Color3.fromRGB(39, 41, 47)
DupeFrame_2.Position = UDim2.new(0.0296052638, 0, 0.463709682, 0)
DupeFrame_2.Size = UDim2.new(0, 152, 0, 127)
 
UICorner_10.Parent = DupeFrame_2
 
Hint_2.Name = "Hint"
Hint_2.Parent = DupeFrame_2
Hint_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Hint_2.BackgroundTransparency = 1.000
Hint_2.Position = UDim2.new(-0.172018766, 0, -0.00511806225, 0)
Hint_2.Size = UDim2.new(0, 200, 0, 27)
Hint_2.Font = Enum.Font.SourceSans
Hint_2.Text = "Duper"
Hint_2.TextColor3 = Color3.fromRGB(255, 255, 255)
Hint_2.TextSize = 26.000
 
Dupe.Name = "Dupe"
Dupe.Parent = DupeFrame_2
Dupe.BackgroundColor3 = Color3.fromRGB(140, 255, 134)
Dupe.Position = UDim2.new(0.0612375103, 0, 0.286220521, 0)
Dupe.Size = UDim2.new(0, 133, 0, 42)
Dupe.Font = Enum.Font.SourceSans
Dupe.Text = "Dupe"
Dupe.TextColor3 = Color3.fromRGB(25, 25, 25)
Dupe.TextSize = 38.000
 
UICorner_11.Parent = Dupe
 
SaveData.Name = "SaveData"
SaveData.Parent = DupeFrame_2
SaveData.BackgroundColor3 = Color3.fromRGB(99, 103, 116)
SaveData.Position = UDim2.new(0.0612375103, 0, 0.664173245, 0)
SaveData.Size = UDim2.new(0, 133, 0, 20)
SaveData.Font = Enum.Font.SourceSans
SaveData.Text = "Save Data"
SaveData.TextColor3 = Color3.fromRGB(255, 255, 255)
SaveData.TextSize = 23.000
 
UICorner_12.Parent = SaveData
 
StatusInfoFrame.Name = "StatusInfoFrame"
StatusInfoFrame.Parent = DupeFrame
StatusInfoFrame.BackgroundColor3 = Color3.fromRGB(39, 41, 47)
StatusInfoFrame.Position = UDim2.new(0.0296052638, 0, 0.0322580636, 0)
StatusInfoFrame.Size = UDim2.new(0, 286, 0, 100)
 
UICorner_13.Parent = StatusInfoFrame
 
PlayerName_2.Name = "PlayerName"
PlayerName_2.Parent = StatusInfoFrame
PlayerName_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
PlayerName_2.BackgroundTransparency = 1.000
PlayerName_2.Position = UDim2.new(0.150349647, 0, 0.0500000007, 0)
PlayerName_2.Size = UDim2.new(0, 200, 0, 50)
PlayerName_2.Font = Enum.Font.SourceSans
PlayerName_2.Text = "Roblox: Detected"
PlayerName_2.TextColor3 = Color3.fromRGB(255, 255, 255)
PlayerName_2.TextSize = 26.000
 
Stand_2.Name = "Stand"
Stand_2.Parent = StatusInfoFrame
Stand_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Stand_2.BackgroundTransparency = 1.000
Stand_2.Position = UDim2.new(0.150349647, 0, 0.439999998, 0)
Stand_2.Size = UDim2.new(0, 200, 0, 50)
Stand_2.Font = Enum.Font.SourceSans
Stand_2.Text = "Roblox Multi: Detected"
Stand_2.TextColor3 = Color3.fromRGB(255, 255, 255)
Stand_2.TextSize = 26.000
 
LogFrame.Name = "LogFrame"
LogFrame.Parent = DupeFrame
LogFrame.BackgroundColor3 = Color3.fromRGB(39, 41, 47)
LogFrame.Position = UDim2.new(0.552631557, 0, 0.463709682, 0)
LogFrame.Size = UDim2.new(0, 127, 0, 127)
 
UICorner_14.Parent = LogFrame
 
Hint_3.Name = "Hint"
Hint_3.Parent = LogFrame
Hint_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Hint_3.BackgroundTransparency = 1.000
Hint_3.Position = UDim2.new(-0.290129006, 0, -0.00511806225, 0)
Hint_3.Size = UDim2.new(0, 200, 0, 27)
Hint_3.Font = Enum.Font.SourceSans
Hint_3.Text = "Logs"
Hint_3.TextColor3 = Color3.fromRGB(255, 255, 255)
Hint_3.TextSize = 26.000
 
Logs.Name = "Logs"
Logs.Parent = LogFrame
Logs.Active = true
Logs.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Logs.BackgroundTransparency = 1.000
Logs.Position = UDim2.new(0.05511811, 0, 0.204724416, 0)
Logs.Size = UDim2.new(0, 120, 0, 90)
Logs.CanvasSize = UDim2.new(0, 0, 1, 0)
 
UIListLayout_2.Parent = Logs
UIListLayout_2.SortOrder = Enum.SortOrder.LayoutOrder
 
GoodLog.Name = "GoodLog"
GoodLog.Parent = LogFrame
GoodLog.BackgroundColor3 = Color3.fromRGB(57, 59, 67)
GoodLog.Size = UDim2.new(0, 103, 0, 20)
GoodLog.Visible = false
GoodLog.Font = Enum.Font.SourceSans
GoodLog.Text = "Example Good Log Text"
GoodLog.TextColor3 = Color3.fromRGB(85, 255, 0)
GoodLog.TextSize = 14.000
GoodLog.TextWrapped = true
 
BadLog.Name = "BadLog"
BadLog.Parent = LogFrame
BadLog.BackgroundColor3 = Color3.fromRGB(57, 59, 67)
BadLog.Size = UDim2.new(0, 103, 0, 20)
BadLog.Visible = false
BadLog.Font = Enum.Font.SourceSans
BadLog.Text = "Example Bad Log Text"
BadLog.TextColor3 = Color3.fromRGB(255, 0, 0)
BadLog.TextSize = 14.000
BadLog.TextWrapped = true
 
ShowButton.Name = "ShowButton"
ShowButton.Parent = Order1Gui
ShowButton.BackgroundColor3 = Color3.fromRGB(99, 103, 116)
ShowButton.Position = UDim2.new(0.00601325929, 0, 0.964021146, 0)
ShowButton.Rotation = 180.000
ShowButton.Size = UDim2.new(0, 45, 0, 29)
ShowButton.Visible = false
ShowButton.Image = "rbxassetid://54479709"
 
UICorner_15.Parent = ShowButton
 
-- My Instances
 
local players = game:GetService("Players")
local GUI = Order1Gui
local ActiveColor = Color3.fromRGB(131, 136, 153)
local InactiveColor = Color3.fromRGB(99, 103, 116)
local RobloxMulti = false
local DupeButton = GUI.MainFrame.DupeFrame.DupeFrame.Dupe
local SaveDataButton = GUI.MainFrame.DupeFrame.DupeFrame.SaveData
 
local CurrentTime = math.floor(tick())
 
-- Script Logic
 
-- Hint Tweener
for i,v in pairs(GUI.MainFrame.TabsFrame:GetChildren()) do
	if v:IsA("ImageButton") then
 
		-- Hint Creation
		local Hint = Instance.new("TextLabel")
		Hint.Parent = v
		Hint.BackgroundTransparency = 1
		Hint.TextColor3 = Color3.fromRGB(255,255,255)
		Hint.Size = v.Size
		Hint.Visible = false
 
		-- Hint Text Creation
		Hint.Text = v.Name:gsub("Button","")
 
		-- Hint Mover and visibility
		local Hovering = false -- Checking if the mouse is hovering
		v.MouseEnter:Connect(function() -- On Enter Event
			Hovering = true
			Hint.Visible = true
			Hint:TweenPosition(UDim2.new(0,0,0.65,0),Enum.EasingDirection.InOut,Enum.EasingStyle.Quad,0.1,0)
		end)
		v.MouseLeave:Connect(function() -- On Leave Event
			Hovering = false
			Hint:TweenPosition(UDim2.new(0,0,0,0),Enum.EasingDirection.InOut,Enum.EasingStyle.Quad,0.1,0)
			wait(.07)
			if Hovering == false then
				Hint.Visible = false				
			end
		end)	
	end
end
 
-- Tab changer and GUI hider
for i,v in pairs(GUI.MainFrame.TabsFrame:GetChildren()) do
	if v:IsA("ImageButton") then
		v.MouseButton1Up:Connect(function()
 
			-- GUI hider
			if v.Name == "HideButton" then
				GUI.MainFrame.Visible = false
				GUI.ShowButton.Visible = true
			end
 
			-- Other Frames hider
			local frametoshow = v.Name:gsub("Button","Frame")
			if v.BackgroundColor3 ~= ActiveColor and v.Name ~= "HideButton" then
				v.BackgroundColor3 = ActiveColor
				GUI.MainFrame[frametoshow].Visible = true
 
				-- Inactive Color Assigner and Tab hider
				for i,v2 in pairs(GUI.MainFrame.TabsFrame:GetChildren()) do
					if v2:IsA("ImageButton") and v2.Name ~= v.Name and v2.Name ~= "HideButton" then
						local frametohide = v2.Name:gsub("Button","Frame")
						if frametohide ~= frametoshow then
							v2.BackgroundColor3 = InactiveColor
							GUI.MainFrame[frametohide].Visible = false							
						end
					end
				end
			end
		end)
	end
end
 
-- Gui Activator
GUI.ShowButton.MouseButton1Up:Connect(function()
	GUI.ShowButton.Visible = false
	GUI.MainFrame.Visible = true
end)
 
-- Username ASSigner
GUI.MainFrame.InfoFrame.PlayerInfoFrame.PlayerName.Text = ("Username: "..players.LocalPlayer.Name)
 
-- Stand ASSigner
local playerstats = players.LocalPlayer:FindFirstChild("PlayerStats")
if playerstats ~= nil then
	-- First ASSign
	GUI.MainFrame.InfoFrame.PlayerInfoFrame.Stand.Text = ("Stand: "..playerstats.Stand.Value)
 
	-- Any other time
	playerstats.Stand.Changed:Connect(function()
		GUI.MainFrame.InfoFrame.PlayerInfoFrame.Stand.Text = ("Stand: "..playerstats.Stand.Value)
	end)
else
	GUI.MainFrame.InfoFrame.PlayerInfoFrame.Stand.Text = "Player Statistics is not found."
	GUI.MainFrame.InfoFrame.PlayerInfoFrame.Stand.TextColor3 = Color3.fromRGB(255,0,0)
end
 
-- Give Textlabel Size
function GiveSize(Label)
	local Lenght = (#Label.Text)
	local RecommendedSize = 0
 
	if Lenght <= 20 then
		RecommendedSize = 30
	else
		RecommendedSize = math.floor(Lenght / 20 * 30)
	end
 
	Label.Size = UDim2.new(0,103,0,RecommendedSize)
end
 
-- Add Log
function AddLog(Type,Message)
 
	local logframe = GUI.MainFrame.DupeFrame.LogFrame
	local GoodLogTemplate = logframe.GoodLog
	local BadLogTemplate = logframe.BadLog
 
	if Type == "Good" then
		-- Adding log
		local NewLog = GoodLogTemplate:Clone()
		NewLog.Parent = logframe.Logs
		NewLog.Visible = true
		NewLog.Text = "CT:"..math.floor(tick())-CurrentTime.." "..Message
		GiveSize(NewLog)
	end
	if Type == "Bad" then
		-- Adding log
		local NewLog = BadLogTemplate:Clone()
		NewLog.Parent = logframe.Logs
		NewLog.Visible = true
		NewLog.Text = "CT:"..math.floor(tick())-CurrentTime.." "..Message
		GiveSize(NewLog)
	end
	if Type ~= "Good" and Type ~= "Bad" then
		local NewLog = BadLogTemplate:Clone()
		NewLog.Parent = logframe.Logs
		NewLog.Visible = true
		NewLog.Text = "CT:"..math.floor(tick())-CurrentTime.." Error happened while creating a log."
		GiveSize(NewLog)
		print("Whoops, looks like the log type is incorrect!")
	end
 
	-- expanding canvas size
	logframe.Logs.CanvasSize = UDim2.new(0,0,0,logframe.Logs.UIListLayout.AbsoluteContentSize.Y)
end
 
-- Dupe Button Template
 
DupeButton.MouseButton1Up:Connect(function()
	if RobloxMulti == false then
		AddLog("Good","Action completed!")
	end
end)
 
-- Save Data Button Template
SaveDataButton.MouseButton1Up:Connect(function()
	AddLog("Good","TemplateSave")
end)

if reloaded == true then
	game.StarterGui:SetCore("SendNotification", {
		Title = "Gui Reloaded";
		Text = "Successfully reloaded the GUI.";
		Duration = 2;
	})
end
 
