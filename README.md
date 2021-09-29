-- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local MainFrame = Instance.new("Frame")
local TopFrame = Instance.new("Frame")
local TopFrameHolder = Instance.new("Frame")
local ServersHolder = Instance.new("Folder")
local ServerFrame = Instance.new("Frame")
local ServerFrame1 = Instance.new("Frame")
local ServerFrame2 = Instance.new("Frame")
local ServerTitleFrame = Instance.new("Frame")
local ServerTitle = Instance.new("TextLabel")
local GlowFrame = Instance.new("Frame")
local Glow = Instance.new("ImageLabel")
local ServerContentFrame = Instance.new("Frame")
local ServerChannelHolder = Instance.new("ScrollingFrame")
local ServerChannelHolderLayout = Instance.new("UIListLayout")
local ServerChannelHolderPadding = Instance.new("UIPadding")
local UserStatsChannelBtn = Instance.new("TextButton")
local ChannelBtnCorner = Instance.new("UICorner")
local ChannelBtnHashtag = Instance.new("TextLabel")
local ChannelBtnTitle = Instance.new("TextLabel")
local ServerCorner = Instance.new("UICorner")
local ChannelTitleFrame = Instance.new("Frame")
local Hashtag = Instance.new("TextLabel")
local ChannelTitle = Instance.new("TextLabel")
local ChannelContentFrame = Instance.new("Frame")
local GlowChannel = Instance.new("ImageLabel")
local ChannelHolder = Instance.new("ScrollingFrame")
local ChannelHolderLayout = Instance.new("UIListLayout")
local Seperator1 = Instance.new("Frame")
local Seperator2 = Instance.new("Frame")
local Seperator1_2 = Instance.new("Frame")
local Seperator2_2 = Instance.new("Frame")
local Label = Instance.new("TextButton")
local LabelTitle = Instance.new("TextLabel")
local espbtn = Instance.new("TextButton")
local ButtonCorner = Instance.new("UICorner")
local chatspambtn = Instance.new("TextButton")
local ButtonCorner_2 = Instance.new("UICorner")
local grenadetpbtn = Instance.new("TextButton")
local ButtonCorner_3 = Instance.new("UICorner")
local espbtn_2 = Instance.new("TextButton")
local ButtonCorner_4 = Instance.new("UICorner")
local Aimbottttt = Instance.new("TextButton")
local ButtonCorner_5 = Instance.new("UICorner")
local ServerFrame_2 = Instance.new("Frame")
local ServerFrame1_2 = Instance.new("Frame")
local ServerFrame2_2 = Instance.new("Frame")
local ServerTitleFrame_2 = Instance.new("Frame")
local ServerTitle_2 = Instance.new("TextLabel")
local GlowFrame_2 = Instance.new("Frame")
local Glow_2 = Instance.new("ImageLabel")
local ServerContentFrame_2 = Instance.new("Frame")
local ServerChannelHolder_2 = Instance.new("ScrollingFrame")
local ServerChannelHolderLayout_2 = Instance.new("UIListLayout")
local ServerChannelHolderPadding_2 = Instance.new("UIPadding")
local FeaturesChannelBtn = Instance.new("TextButton")
local ChannelBtnCorner_2 = Instance.new("UICorner")
local ChannelBtnHashtag_2 = Instance.new("TextLabel")
local ChannelBtnTitle_2 = Instance.new("TextLabel")
local TipsChannelBtn = Instance.new("TextButton")
local ChannelBtnCorner_3 = Instance.new("UICorner")
local ChannelBtnHashtag_3 = Instance.new("TextLabel")
local ChannelBtnTitle_3 = Instance.new("TextLabel")
local CreditsChannelBtn = Instance.new("TextButton")
local ChannelBtnCorner_4 = Instance.new("UICorner")
local ChannelBtnHashtag_4 = Instance.new("TextLabel")
local ChannelBtnTitle_4 = Instance.new("TextLabel")
local ServerCorner_2 = Instance.new("UICorner")
local ChannelTitleFrame_2 = Instance.new("Frame")
local Hashtag_2 = Instance.new("TextLabel")
local ChannelTitle_2 = Instance.new("TextLabel")
local ChannelContentFrame_2 = Instance.new("Frame")
local GlowChannel_2 = Instance.new("ImageLabel")
local ChannelHolder_2 = Instance.new("ScrollingFrame")
local ChannelHolderLayout_2 = Instance.new("UIListLayout")
local Label_2 = Instance.new("TextButton")
local LabelTitle_2 = Instance.new("TextLabel")
local Seperator1_3 = Instance.new("Frame")
local Seperator2_3 = Instance.new("Frame")
local Label_3 = Instance.new("TextButton")
local LabelTitle_3 = Instance.new("TextLabel")
local Label_4 = Instance.new("TextButton")
local LabelTitle_4 = Instance.new("TextLabel")
local Label_5 = Instance.new("TextButton")
local LabelTitle_5 = Instance.new("TextLabel")
local Label_6 = Instance.new("TextButton")
local LabelTitle_6 = Instance.new("TextLabel")
local Label_7 = Instance.new("TextButton")
local LabelTitle_7 = Instance.new("TextLabel")
local Label_8 = Instance.new("TextButton")
local LabelTitle_8 = Instance.new("TextLabel")
local Label_9 = Instance.new("TextButton")
local LabelTitle_9 = Instance.new("TextLabel")
local ChannelHolder_3 = Instance.new("ScrollingFrame")
local ChannelHolderLayout_3 = Instance.new("UIListLayout")
local Label_10 = Instance.new("TextButton")
local LabelTitle_10 = Instance.new("TextLabel")
local Label_11 = Instance.new("TextButton")
local LabelTitle_11 = Instance.new("TextLabel")
local Label_12 = Instance.new("TextButton")
local LabelTitle_12 = Instance.new("TextLabel")
local Label_13 = Instance.new("TextButton")
local LabelTitle_13 = Instance.new("TextLabel")
local ChannelHolder_4 = Instance.new("ScrollingFrame")
local ChannelHolderLayout_4 = Instance.new("UIListLayout")
local Label_14 = Instance.new("TextButton")
local LabelTitle_14 = Instance.new("TextLabel")
local Label_15 = Instance.new("TextButton")
local LabelTitle_15 = Instance.new("TextLabel")
local Label_16 = Instance.new("TextButton")
local LabelTitle_16 = Instance.new("TextLabel")
local Userpad = Instance.new("Frame")
local UserName = Instance.new("TextLabel")
local Title = Instance.new("TextLabel")
local CloseBtn = Instance.new("TextButton")
local CloseIcon = Instance.new("ImageLabel")
local MinimizeButton = Instance.new("TextButton")
local MinimizeLabel = Instance.new("ImageLabel")
local ServersHoldFrame = Instance.new("Frame")
local ServersHold = Instance.new("ScrollingFrame")
local ServersHoldLayout = Instance.new("UIListLayout")
local ServersHoldPadding = Instance.new("UIPadding")
local MainUIServer = Instance.new("TextButton")
local ServerCorner_3 = Instance.new("UICorner")
local ServerIco = Instance.new("ImageLabel")
local ServerWhiteFrame = Instance.new("Frame")
local ServerWhiteFrameCorner = Instance.new("UICorner")

--Properties:

ScreenGui.Parent = game.CoreGui
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

MainFrame.Name = "MainFrame"
MainFrame.Parent = ScreenGui
MainFrame.AnchorPoint = Vector2.new(0.5, 0.5)
MainFrame.BackgroundColor3 = Color3.fromRGB(32, 34, 37)
MainFrame.BorderSizePixel = 0
MainFrame.ClipsDescendants = true
MainFrame.Position = UDim2.new(0.443674088, 0, 0.473842114, 0)
MainFrame.Size = UDim2.new(0, 681, 0, 396)
MainFrame.Draggable = true
MainFrame.Selectable = true
MainFrame.Active = true

TopFrame.Name = "TopFrame"
TopFrame.Parent = MainFrame
TopFrame.BackgroundColor3 = Color3.fromRGB(32, 34, 37)
TopFrame.BackgroundTransparency = 1.000
TopFrame.BorderSizePixel = 0
TopFrame.Position = UDim2.new(-0.000658480625, 0, 0, 0)
TopFrame.Size = UDim2.new(0, 681, 0, 22)

TopFrameHolder.Name = "TopFrameHolder"
TopFrameHolder.Parent = TopFrame
TopFrameHolder.BackgroundColor3 = Color3.fromRGB(32, 34, 37)
TopFrameHolder.BackgroundTransparency = 1.000
TopFrameHolder.BorderSizePixel = 0
TopFrameHolder.Position = UDim2.new(-0.000658480625, 0, 0, 0)
TopFrameHolder.Size = UDim2.new(0, 681, 0, 22)

ServersHolder.Name = "ServersHolder"
ServersHolder.Parent = TopFrameHolder

ServerFrame.Name = "ServerFrame"
ServerFrame.Parent = ServersHolder
ServerFrame.BackgroundColor3 = Color3.fromRGB(47, 49, 54)
ServerFrame.BorderSizePixel = 0
ServerFrame.ClipsDescendants = true
ServerFrame.Position = UDim2.new(0.105726875, 0, 1.01262593, 0)
ServerFrame.Size = UDim2.new(0, 609, 0, 373)

ServerFrame1.Name = "ServerFrame1"
ServerFrame1.Parent = ServerFrame
ServerFrame1.BackgroundColor3 = Color3.fromRGB(47, 49, 54)
ServerFrame1.BorderSizePixel = 0
ServerFrame1.Position = UDim2.new(0, 0, 0.972290039, 0)
ServerFrame1.Size = UDim2.new(0, 12, 0, 10)

ServerFrame2.Name = "ServerFrame2"
ServerFrame2.Parent = ServerFrame
ServerFrame2.BackgroundColor3 = Color3.fromRGB(47, 49, 54)
ServerFrame2.BorderSizePixel = 0
ServerFrame2.Position = UDim2.new(0.980295539, 0, 0.972290039, 0)
ServerFrame2.Size = UDim2.new(0, 12, 0, 9)

ServerTitleFrame.Name = "ServerTitleFrame"
ServerTitleFrame.Parent = ServerFrame
ServerTitleFrame.BackgroundColor3 = Color3.fromRGB(47, 49, 54)
ServerTitleFrame.BackgroundTransparency = 1.000
ServerTitleFrame.BorderSizePixel = 0
ServerTitleFrame.Position = UDim2.new(-0.0010054264, 0, -0.000900391256, 0)
ServerTitleFrame.Size = UDim2.new(0, 180, 0, 40)

ServerTitle.Name = "ServerTitle"
ServerTitle.Parent = ServerTitleFrame
ServerTitle.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ServerTitle.BackgroundTransparency = 1.000
ServerTitle.BorderSizePixel = 0
ServerTitle.Position = UDim2.new(0.0751359761, 0, 0, 0)
ServerTitle.Size = UDim2.new(0, 97, 0, 39)
ServerTitle.Font = Enum.Font.GothamSemibold
ServerTitle.Text = "Main UI"
ServerTitle.TextColor3 = Color3.fromRGB(255, 255, 255)
ServerTitle.TextSize = 15.000
ServerTitle.TextXAlignment = Enum.TextXAlignment.Left

GlowFrame.Name = "GlowFrame"
GlowFrame.Parent = ServerFrame
GlowFrame.BackgroundColor3 = Color3.fromRGB(47, 49, 54)
GlowFrame.BackgroundTransparency = 1.000
GlowFrame.BorderSizePixel = 0
GlowFrame.Position = UDim2.new(-0.0010054264, 0, -0.000900391256, 0)
GlowFrame.Size = UDim2.new(0, 609, 0, 40)

Glow.Name = "Glow"
Glow.Parent = GlowFrame
Glow.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Glow.BackgroundTransparency = 1.000
Glow.BorderSizePixel = 0
Glow.Position = UDim2.new(0, -15, 0, -15)
Glow.Size = UDim2.new(1, 30, 1, 30)
Glow.ZIndex = 0
Glow.Image = "rbxassetid://4996891970"
Glow.ImageColor3 = Color3.fromRGB(15, 15, 15)
Glow.ScaleType = Enum.ScaleType.Slice
Glow.SliceCenter = Rect.new(20, 20, 280, 280)

ServerContentFrame.Name = "ServerContentFrame"
ServerContentFrame.Parent = ServerFrame
ServerContentFrame.BackgroundColor3 = Color3.fromRGB(47, 49, 54)
ServerContentFrame.BackgroundTransparency = 1.000
ServerContentFrame.BorderSizePixel = 0
ServerContentFrame.Position = UDim2.new(-0.0010054264, 0, 0.106338218, 0)
ServerContentFrame.Size = UDim2.new(0, 180, 0, 333)

ServerChannelHolder.Name = "ServerChannelHolder"
ServerChannelHolder.Parent = ServerContentFrame
ServerChannelHolder.Active = true
ServerChannelHolder.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ServerChannelHolder.BackgroundTransparency = 1.000
ServerChannelHolder.BorderSizePixel = 0
ServerChannelHolder.Position = UDim2.new(0.00535549596, 0, 0.0241984241, 0)
ServerChannelHolder.Selectable = false
ServerChannelHolder.Size = UDim2.new(0, 179, 0, 278)
ServerChannelHolder.CanvasSize = UDim2.new(0, 0, 0, 166)
ServerChannelHolder.ScrollBarThickness = 4

ServerChannelHolderLayout.Name = "ServerChannelHolderLayout"
ServerChannelHolderLayout.Parent = ServerChannelHolder
ServerChannelHolderLayout.SortOrder = Enum.SortOrder.LayoutOrder
ServerChannelHolderLayout.Padding = UDim.new(0, 4)

ServerChannelHolderPadding.Name = "ServerChannelHolderPadding"
ServerChannelHolderPadding.Parent = ServerChannelHolder
ServerChannelHolderPadding.PaddingLeft = UDim.new(0, 9)

UserStatsChannelBtn.Name = "User StatsChannelBtn"
UserStatsChannelBtn.Parent = ServerChannelHolder
UserStatsChannelBtn.BackgroundColor3 = Color3.fromRGB(57, 60, 67)
UserStatsChannelBtn.BorderSizePixel = 0
UserStatsChannelBtn.Position = UDim2.new(0.24118948, 0, 0.578947365, 0)
UserStatsChannelBtn.Size = UDim2.new(0, 160, 0, 30)
UserStatsChannelBtn.AutoButtonColor = false
UserStatsChannelBtn.Font = Enum.Font.SourceSans
UserStatsChannelBtn.Text = ""
UserStatsChannelBtn.TextColor3 = Color3.fromRGB(0, 0, 0)
UserStatsChannelBtn.TextSize = 14.000

ChannelBtnCorner.CornerRadius = UDim.new(0, 6)
ChannelBtnCorner.Name = "ChannelBtnCorner"
ChannelBtnCorner.Parent = UserStatsChannelBtn

ChannelBtnHashtag.Name = "ChannelBtnHashtag"
ChannelBtnHashtag.Parent = UserStatsChannelBtn
ChannelBtnHashtag.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ChannelBtnHashtag.BackgroundTransparency = 1.000
ChannelBtnHashtag.BorderSizePixel = 0
ChannelBtnHashtag.Position = UDim2.new(0.0279720314, 0, 0, 0)
ChannelBtnHashtag.Size = UDim2.new(0, 24, 0, 30)
ChannelBtnHashtag.Font = Enum.Font.Gotham
ChannelBtnHashtag.Text = "#"
ChannelBtnHashtag.TextColor3 = Color3.fromRGB(114, 118, 125)
ChannelBtnHashtag.TextSize = 21.000

ChannelBtnTitle.Name = "ChannelBtnTitle"
ChannelBtnTitle.Parent = UserStatsChannelBtn
ChannelBtnTitle.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ChannelBtnTitle.BackgroundTransparency = 1.000
ChannelBtnTitle.BorderSizePixel = 0
ChannelBtnTitle.Position = UDim2.new(0.173747092, 0, -0.166666672, 0)
ChannelBtnTitle.Size = UDim2.new(0, 95, 0, 39)
ChannelBtnTitle.Font = Enum.Font.Gotham
ChannelBtnTitle.Text = "Main Player"
ChannelBtnTitle.TextColor3 = Color3.fromRGB(255, 255, 255)
ChannelBtnTitle.TextSize = 14.000
ChannelBtnTitle.TextXAlignment = Enum.TextXAlignment.Left

ServerCorner.CornerRadius = UDim.new(0, 9)
ServerCorner.Name = "ServerCorner"
ServerCorner.Parent = ServerFrame

ChannelTitleFrame.Name = "ChannelTitleFrame"
ChannelTitleFrame.Parent = ServerFrame
ChannelTitleFrame.BackgroundColor3 = Color3.fromRGB(54, 57, 63)
ChannelTitleFrame.BorderSizePixel = 0
ChannelTitleFrame.Position = UDim2.new(0.294561088, 0, -0.000900391256, 0)
ChannelTitleFrame.Size = UDim2.new(0, 429, 0, 40)

Hashtag.Name = "Hashtag"
Hashtag.Parent = ChannelTitleFrame
Hashtag.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Hashtag.BackgroundTransparency = 1.000
Hashtag.BorderSizePixel = 0
Hashtag.Position = UDim2.new(0.0279720277, 0, 0, 0)
Hashtag.Size = UDim2.new(0, 19, 0, 39)
Hashtag.Font = Enum.Font.Gotham
Hashtag.Text = "#"
Hashtag.TextColor3 = Color3.fromRGB(114, 118, 125)
Hashtag.TextSize = 25.000

ChannelTitle.Name = "ChannelTitle"
ChannelTitle.Parent = ChannelTitleFrame
ChannelTitle.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ChannelTitle.BackgroundTransparency = 1.000
ChannelTitle.BorderSizePixel = 0
ChannelTitle.Position = UDim2.new(0.0862470865, 0, 0, 0)
ChannelTitle.Size = UDim2.new(0, 95, 0, 39)
ChannelTitle.Font = Enum.Font.GothamSemibold
ChannelTitle.Text = "Main Player"
ChannelTitle.TextColor3 = Color3.fromRGB(255, 255, 255)
ChannelTitle.TextSize = 15.000
ChannelTitle.TextXAlignment = Enum.TextXAlignment.Left

ChannelContentFrame.Name = "ChannelContentFrame"
ChannelContentFrame.Parent = ServerFrame
ChannelContentFrame.BackgroundColor3 = Color3.fromRGB(54, 57, 63)
ChannelContentFrame.BorderSizePixel = 0
ChannelContentFrame.ClipsDescendants = true
ChannelContentFrame.Position = UDim2.new(0.294561088, 0, 0.106338218, 0)
ChannelContentFrame.Size = UDim2.new(0, 429, 0, 333)

GlowChannel.Name = "GlowChannel"
GlowChannel.Parent = ChannelContentFrame
GlowChannel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
GlowChannel.BackgroundTransparency = 1.000
GlowChannel.BorderSizePixel = 0
GlowChannel.Position = UDim2.new(0, -33, 0, -91)
GlowChannel.Size = UDim2.new(1.06396091, 30, 0.228228226, 30)
GlowChannel.ZIndex = 0
GlowChannel.Image = "rbxassetid://4996891970"
GlowChannel.ImageColor3 = Color3.fromRGB(15, 15, 15)
GlowChannel.ScaleType = Enum.ScaleType.Slice
GlowChannel.SliceCenter = Rect.new(20, 20, 280, 280)

ChannelHolder.Name = "ChannelHolder"
ChannelHolder.Parent = ChannelContentFrame
ChannelHolder.Active = true
ChannelHolder.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ChannelHolder.BackgroundTransparency = 1.000
ChannelHolder.BorderSizePixel = 0
ChannelHolder.ClipsDescendants = false
ChannelHolder.Position = UDim2.new(0.0360843204, 0, 0.0241984241, 0)
ChannelHolder.Size = UDim2.new(0, 412, 0, 314)
ChannelHolder.CanvasSize = UDim2.new(0, 0, 0, 418)
ChannelHolder.ScrollBarThickness = 6

ChannelHolderLayout.Name = "ChannelHolderLayout"
ChannelHolderLayout.Parent = ChannelHolder
ChannelHolderLayout.SortOrder = Enum.SortOrder.LayoutOrder
ChannelHolderLayout.Padding = UDim.new(0, 6)

Seperator1.Name = "Seperator1"
Seperator1.Parent = ChannelHolder
Seperator1.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Seperator1.BackgroundTransparency = 1.000
Seperator1.Position = UDim2.new(0, 0, 0.350318581, 0)
Seperator1.Size = UDim2.new(0, 100, 0, 8)

Seperator2.Name = "Seperator2"
Seperator2.Parent = Seperator1
Seperator2.BackgroundColor3 = Color3.fromRGB(66, 69, 74)
Seperator2.BorderSizePixel = 0
Seperator2.Position = UDim2.new(0, 0, 0, 4)
Seperator2.Size = UDim2.new(0, 401, 0, 1)

Seperator1_2.Name = "Seperator1"
Seperator1_2.Parent = ChannelHolder
Seperator1_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Seperator1_2.BackgroundTransparency = 1.000
Seperator1_2.Position = UDim2.new(0, 0, 0.350318581, 0)
Seperator1_2.Size = UDim2.new(0, 100, 0, 8)

Seperator2_2.Name = "Seperator2"
Seperator2_2.Parent = Seperator1_2
Seperator2_2.BackgroundColor3 = Color3.fromRGB(66, 69, 74)
Seperator2_2.BorderSizePixel = 0
Seperator2_2.Position = UDim2.new(0, 0, 0, 4)
Seperator2_2.Size = UDim2.new(0, 401, 0, 1)

Label.Name = "Label"
Label.Parent = ChannelHolder
Label.BackgroundColor3 = Color3.fromRGB(54, 57, 63)
Label.BorderSizePixel = 0
Label.Position = UDim2.new(0.261979163, 0, 0.190789461, 0)
Label.Size = UDim2.new(0, 401, 0, 30)
Label.AutoButtonColor = false
Label.Font = Enum.Font.Gotham
Label.Text = ""
Label.TextColor3 = Color3.fromRGB(255, 255, 255)
Label.TextSize = 14.000

LabelTitle.Name = "LabelTitle"
LabelTitle.Parent = Label
LabelTitle.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
LabelTitle.BackgroundTransparency = 1.000
LabelTitle.Position = UDim2.new(0, 5, 0, 0)
LabelTitle.Size = UDim2.new(0, 200, 0, 30)
LabelTitle.Font = Enum.Font.Gotham
LabelTitle.Text = "PF CHEATS:"
LabelTitle.TextColor3 = Color3.fromRGB(127, 131, 137)
LabelTitle.TextSize = 14.000
LabelTitle.TextXAlignment = Enum.TextXAlignment.Left

espbtn.Name = "espbtn"
espbtn.Parent = ChannelHolder
espbtn.BackgroundColor3 = Color3.fromRGB(114, 137, 228)
espbtn.Size = UDim2.new(0, 401, 0, 30)
espbtn.AutoButtonColor = false
espbtn.Font = Enum.Font.Gotham
espbtn.Text = "All"
espbtn.TextColor3 = Color3.fromRGB(255, 255, 255)
espbtn.TextSize = 14.000
espbtn.MouseButton1Click:Connect(function()
	for i, a in pairs(getgc(true)) do
		if type(a) == 'table' and rawget(a, "aimrotkickmin") then
			a.aimrotkickmin = Vector3.new(0,0,0)
			a.aimrotkickmax = Vector3.new(0,0,0)
			a.aimtranskickmin = Vector3.new(0,0,0)
			a.aimtranskickmax = Vector3.new(0,0,0)
			a.aimcamkickmin = Vector3.new(0,0,0)
			a.aimcamkickmax = Vector3.new(0,0,0)
			a.rotkickmin = Vector3.new(0,0,0)
			a.rotkickmax = Vector3.new(0,0,0)
			a.transkickmin = Vector3.new(0,0,0)
			a.transkickmax = Vector3.new(0,0,0)
			a.camkickmin = Vector3.new(0,0,0)
			a.camkickmax = Vector3.new(0,0,0)
			a.aimcamkickspeed = 99999
			a.modelkickspeed = 9999
			a.modelrecoverspeed = 9999
			a.firerate = 1000 --Change to your own
		end
	end
end)	



ButtonCorner.CornerRadius = UDim.new(0, 4)
ButtonCorner.Name = "ButtonCorner"
ButtonCorner.Parent = espbtn

chatspambtn.Name = "chatspambtn"
chatspambtn.Parent = ChannelHolder
chatspambtn.BackgroundColor3 = Color3.fromRGB(114, 137, 228)
chatspambtn.Size = UDim2.new(0, 401, 0, 30)
chatspambtn.AutoButtonColor = false
chatspambtn.Font = Enum.Font.Gotham
chatspambtn.Text = "Chat Spam"
chatspambtn.TextColor3 = Color3.fromRGB(255, 255, 255)
chatspambtn.TextSize = 14.000
chatspambtn.MouseButton1Click:Connect(function()
	spawn(function()
		while wait(1) do
			math.randomseed(os.time())
		end
	end)
	local n

	for index, garbage_collected in next, getgc(true) do
		if (type(garbage_collected) == "table" and rawget(garbage_collected, "send")) then
			n = garbage_collected
			break
		end
	end

	local phrases = {"VoteKick him hes hacking 🔥 🔥 🔥  Votekick hime hes hacking 🔥 🔥 🔥  Votekick hime hes hacking 🔥 🔥 🔥  Votekick hime hes hacking 🔥 🔥 🔥  Votekick hime hes hacking 🔥 🔥 🔥 ","Im not hacking 🤡 🤡 🤡 🤡 🤡 🤡 Im not hacking 🤡 🤡 🤡 🤡 🤡 🤡  Im not hacking 🤡 🤡 🤡 🤡 🤡 🤡 Im not hacking 🤡 🤡 🤡 🤡 🤡 🤡Im not hacking 🤡 🤡 🤡 🤡 🤡 🤡Im not hacking 🤡 🤡 🤡 🤡 🤡 🤡","Kid u suck😳 Kid u suck😳 Kid u suck😳 Kid u suck😳 Kid u suck😳 Kid u suck😳 Kid u suck😳 Kid u suck😳 Kid u suck😳 Kid u suck😳 Kid u suck😳 Kid u suck😳 Kid u suck😳 ","Your Bad At The Game 🤮🤮🤮 Im Good At The Game 🔥 🔥 🔥 Your Bad At The Game 🤮🤮🤮 Im Good At The Game 🔥 🔥 🔥 Your Bad At The Game 🤮🤮🤮 Your Bad At The Game 🤮🤮🤮 Your Bad At The Game 🤮🤮🤮","Your script = 🤮. My Script = 🔥 Your script = 🤮. My Script = 🔥Your script = 🤮. My Script = 🔥Your script = 🤮. My Script = 🔥Your script = 🤮. My Script = 🔥Your script = 🤮. My Script = 🔥","PH-ON-TOP     PH-ON-TOP     PH-ON-TOP     PH-ON-TOP     PH-ON-TOP     PH-ON-TOP     PH-ON-TOP     PH-ON-TOP     PH-ON-TOP     PH-ON-TOP     PH-ON-TOP     PH-ON-TOP     PH-ON-TOP     PH-ON-TOP","You: I Dont have PH 😢😢 You: I Dont have PH 😢😢 You: I Dont have PH 😢😢 You: I Dont have PH 😢😢 You: I Dont have PH 😢😢 You: I Dont have PH 😢😢 You: I Dont have PH 😢😢 You: I Dont have PH 😢😢","How to gain access I need it.🔑🔑 How to gain access I need it.🔑🔑How to gain access I need it.🔑🔑How to gain access I need it.🔑🔑How to gain access I need it.🔑🔑How to gain access I need it.🔑🔑How to gain access I need it.🔑🔑","Is that PH omg 😲😲😲. Is that PH omg 😲😲😲. Is that PH omg 😲😲😲. Is that PH omg 😲😲😲. Is that PH omg 😲😲😲. Is that PH omg 😲😲😲. Is that PH omg 😲😲😲. Is that PH omg 😲😲😲. Is that PH omg 😲😲😲. Is that PH omg 😲😲😲.","Join Us. Join Us. Join Us. Join Us. Join Us. Join Us. Join Us. Join Us. Join Us. Join Us. Join Us. Join Us. Join Us. Join Us. Join Us. Join Us. Join Us. Join Us. Join Us. Join Us. Join Us. Join Us. Join Us. Join Us. Join Us.","You should join us. You should join us. You should join us. You should join us. You should join us. You should join us. You should join us. You should join us. You should join us. You should join us. You should join us.","Whats that script 📜📜. Whats that script 📜📜. Whats that script 📜📜. Whats that script 📜📜. Whats that script 📜📜. Whats that script 📜📜. Whats that script 📜📜. Whats that script 📜📜. Whats that script 📜📜. Whats that script 📜📜.","Imagine not having PH 🤦‍♂️🤦‍♂️. Imagine not having PH 🤦‍♂️🤦‍♂️. Imagine not having PH 🤦‍♂️🤦‍♂️. Imagine not having PH 🤦‍♂️🤦‍♂️. Imagine not having PH 🤦‍♂️🤦‍♂️. Imagine not having PH 🤦‍♂️🤦‍♂️. Imagine not having PH 🤦‍♂️🤦‍♂️. Imagine not having PH 🤦‍♂️🤦‍♂️.","You Paid 💰💰 You Paid 💰💰 You Paid 💰💰 You Paid 💰💰 You Paid 💰💰 You Paid 💰💰 You Paid 💰💰 You Paid 💰💰 You Paid 💰💰 You Paid 💰💰 You Paid 💰💰 You Paid 💰💰 You Paid 💰💰 You Paid 💰💰 You Paid 💰💰 You Paid 💰💰 You Paid 💰💰 You Paid 💰💰","⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️⚠️","dis💠rd.io/ph-on-top. its FREE 🤑🤑 dis💠rd.io/ph-on-top. its FREE 🤑🤑 dis💠rd.io/ph-on-top. its FREE 🤑🤑 dis💠rd.io/ph-on-top. its FREE 🤑🤑 dis💠rd.io/ph-on-top. its FREE 🤑🤑 dis💠rd.io/ph-on-top. its FREE 🤑🤑 dis💠rd.io/ph-on-top. its FREE 🤑🤑","Stop trying. Stop trying. Stop trying. Stop trying. Stop trying. Stop trying. Stop trying. Stop trying. Stop trying. Stop trying. Stop trying. Stop trying. Stop trying. Stop trying. Stop trying. Stop trying. Stop trying. Stop trying. Stop trying. ","I wish I had chat spam BoooHoooo. 😢😢😢I wish I had chat spam BoooHoooo. 😢😢😢I wish I had chat spam BoooHoooo. 😢😢😢I wish I had chat spam BoooHoooo. 😢😢😢I wish I had chat spam BoooHoooo. 😢😢😢I wish I had chat spam BoooHoooo. 😢😢😢I wish I had chat spam BoooHoooo. 😢😢😢","Kick Him Hes Annoying.Kick Him Hes Annoying.Kick Him Hes Annoying.Kick Him Hes Annoying.Kick Him Hes Annoying.Kick Him Hes Annoying.Kick Him Hes Annoying.Kick Him Hes Annoying.Kick Him Hes Annoying.Kick Him Hes Annoying.Kick Him Hes Annoying.","Im not racist ❌❌👨🏿👨🏿❌❌ Im not racist ✔️✔️👨🏿👨🏿✔️✔️Im not racist ❌❌👨🏿👨🏿❌❌ Im not racist ✔️✔️👨🏿👨🏿✔️✔️Im not racist ❌❌👨🏿👨🏿❌❌ Im not racist ✔️✔️👨🏿👨🏿✔️✔️Im not racist ❌❌👨🏿👨🏿❌❌ Im not racist ✔️✔️👨🏿👨🏿✔️✔️Im not racist ❌❌👨🏿👨🏿❌❌ Im not racist ✔️✔️👨🏿👨🏿✔️✔️","You look lost..You look lost..You look lost..You look lost..You look lost..You look lost..You look lost..You look lost..You look lost..You look lost..You look lost..You look lost..You look lost..You look lost..You look lost..You look lost..You look lost..You look lost..You look lost..","Im not racist ❌❌👨🏿👨🏿❌❌ Im not racist ✔️✔️👨🏿👨🏿✔️✔️Im not racist ❌❌👨🏿👨🏿❌❌ Im not racist ✔️✔️👨🏿👨🏿✔️✔️Im not racist ❌❌👨🏿👨🏿❌❌ Im not racist ✔️✔️👨🏿👨🏿✔️✔️Im not racist ❌❌👨🏿👨🏿❌❌ Im not racist ✔️✔️👨🏿👨🏿✔️✔️Im not racist ❌❌👨🏿👨🏿❌❌ Im not racist ✔️✔️👨🏿👨🏿✔️✔️","Me before PH 😔🔫. Me now 😜😜😜 Me before PH 😔🔫. Me now 😜😜😜 Me before PH 😔🔫. Me now 😜😜😜 Me before PH 😔🔫. Me now 😜😜😜 Me before PH 😔🔫. Me now 😜😜😜 Me before PH 😔🔫. Me now 😜😜😜 Me before PH 😔🔫. Me now 😜😜😜 Me before PH 😔🔫. Me now 😜😜😜 Me before PH 😔🔫. Me now 😜😜😜","OMG Look At Me Mom No Hands 🤣🤣🤣 OMG Look At Me Mom No Hands 🤣🤣🤣 OMG Look At Me Mom No Hands 🤣🤣🤣 OMG Look At Me Mom No Hands 🤣🤣🤣 OMG Look At Me Mom No Hands 🤣🤣🤣 OMG Look At Me Mom No Hands 🤣🤣🤣 OMG Look At Me Mom No Hands 🤣🤣🤣","0 Brain Cells ❌🧠🧠🧠❌ 0 Brain Cells ❌🧠🧠🧠❌ 0 Brain Cells ❌🧠🧠🧠❌ 0 Brain Cells ❌🧠🧠🧠❌ 0 Brain Cells ❌🧠🧠🧠❌ 0 Brain Cells ❌🧠🧠🧠❌ 0 Brain Cells ❌🧠🧠🧠❌ 0 Brain Cells ❌🧠🧠🧠❌ 0 Brain Cells ❌🧠🧠🧠❌ 0 Brain Cells ❌🧠🧠🧠❌","#Winning - #Winning - #Winning - #Winning - #Winning - #Winning - #Winning - #Winning - #Winning - #Winning - #Winning - #Winning - #Winning - #Winning - #Winning - #Winning - #Winning - #Winning - #Winning - #Winning - #Winning","Kid stop trying u almost lost an ankle 🏀🏀🏀  Kid stop trying u almost lost an ankle 🏀🏀🏀  Kid stop trying u almost lost an ankle 🏀🏀🏀  Kid stop trying u almost lost an ankle 🏀🏀🏀  Kid stop trying u almost lost an ankle 🏀🏀🏀  Kid stop trying u almost lost an ankle 🏀🏀🏀","Made You Look Imao 👌🧐🧐👌👌 Made You Look Imao 👌🧐🧐👌👌 Made You Look Imao 👌🧐🧐👌👌 Made You Look Imao 👌🧐🧐👌👌 Made You Look Imao 👌🧐🧐👌👌 Made You Look Imao 👌🧐🧐👌👌 Made You Look Imao 👌🧐🧐👌👌 Made You Look Imao 👌🧐🧐👌👌 Made You Look Imao 👌🧐🧐👌👌 Made You Look Imao 👌🧐🧐👌👌","Why Are You Still Here 🤷‍♂️🤷‍♂️🤷‍♂️ Why Are You Still Here 🤷‍♂️🤷‍♂️🤷‍♂️ Why Are You Still Here 🤷‍♂️🤷‍♂️🤷‍♂️ Why Are You Still Here 🤷‍♂️🤷‍♂️🤷‍♂️ Why Are You Still Here 🤷‍♂️🤷‍♂️🤷‍♂️ Why Are You Still Here 🤷‍♂️🤷‍♂️🤷‍♂️ Why Are You Still Here 🤷‍♂️🤷‍♂️🤷‍♂️ Why Are You Still Here 🤷‍♂️🤷‍♂️🤷‍♂️ Why Are You Still Here 🤷‍♂️🤷‍♂️🤷‍♂️",}

	while true do
		local sleep = math.random(1, 2)
		wait(sleep)
		local spam = phrases[math.random(#phrases)]
		n:send("chatted", spam)
	end
end)

ButtonCorner_2.CornerRadius = UDim.new(0, 4)
ButtonCorner_2.Name = "ButtonCorner"
ButtonCorner_2.Parent = chatspambtn

grenadetpbtn.Name = "grenadetpbtn"
grenadetpbtn.Parent = ChannelHolder
grenadetpbtn.BackgroundColor3 = Color3.fromRGB(114, 137, 228)
grenadetpbtn.Size = UDim2.new(0, 401, 0, 30)
grenadetpbtn.AutoButtonColor = false
grenadetpbtn.Font = Enum.Font.Gotham
grenadetpbtn.Text = "Grenade TP"
grenadetpbtn.TextColor3 = Color3.fromRGB(255, 255, 255)
grenadetpbtn.TextSize = 14.000
grenadetpbtn.MouseButton1Click:Connect(function()
	local Camera = game:GetService("Workspace").CurrentCamera
	local RunService = game:GetService("RunService")
	local UserInputService = game:GetService("UserInputService")
	local FontValue = 3
	local Visibility = true 

	local function ClosestPlayer()
		local closestPlayer = nil
		local shortestDistance = math.huge
		for _, a in pairs(game.Workspace.Players:GetChildren()) do
			if a.Name ~= game.Players.LocalPlayer.Team.Name then
				for _, b in pairs(a:GetChildren()) do
					if (b.Head.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude < shortestDistance then
						closestPlayer = b
						shortestDistance = (b.Head.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude
					end
				end
			end
		end
		return closestPlayer
	end
	local b = Vector3.new()
	game.RunService.RenderStepped:Connect(function()
		b = ClosestPlayer().HumanoidRootPart.Position
	end)
	local mt = getrawmetatable(game)
	local oldNamecall = mt.__namecall
	local oldIndex = mt.__index
	setreadonly(mt, false)
	mt.__namecall = newcclosure(function(...)
		local method = getnamecallmethod()
		local args = {
			...
		}
		if tostring(method) == "FireServer" and args[2] == "newgrenade" then
			for i = 1, #args[4]["frames"] do
				if i ~= 1 then
					args[4]["frames"][i]["p0"] = b
				end
			end
			args[4]["blowuptime"] = 0
		end
		return oldNamecall(unpack(args))
	end)
	setreadonly(mt, true)
end)

ButtonCorner_3.CornerRadius = UDim.new(0, 4)
ButtonCorner_3.Name = "ButtonCorner"
ButtonCorner_3.Parent = grenadetpbtn

espbtn_2.Name = "espbtn"
espbtn_2.Parent = ChannelHolder
espbtn_2.BackgroundColor3 = Color3.fromRGB(114, 137, 228)
espbtn_2.Size = UDim2.new(0, 401, 0, 30)
espbtn_2.AutoButtonColor = false
espbtn_2.Font = Enum.Font.Gotham
espbtn_2.Text = "ESP"
espbtn_2.TextColor3 = Color3.fromRGB(255, 255, 255)
espbtn_2.TextSize = 14.000
espbtn_2.MouseButton1Click:Connect(function()
	local client = {}; do
		-- Tables
		client.esp = {}

		-- Modules
		for i,v in pairs(getgc(true)) do
			if (type(v) == "table") then
				if (rawget(v, "getplayerhealth")) then
					client.hud = v
				elseif (rawget(v, "getplayerhit")) then
					client.replication = v
				end
			end
		end

		client.chartable = debug.getupvalue(client.replication.getbodyparts, 1)
	end

	client.esp.Options = {
		Enable = true,
		TeamCheck = true,
		TeamColor = false,
		VisibleOnly = false,
		Color = Color3.fromRGB(255, 0, 255),
		Name = true,
		Box = true,
		Health = true,
		Distance = true,
		Tracer = true
	}

	client.esp.Services = setmetatable({}, {
		__index = function(Self, Index)
			local GetService = game.GetService
			local Service = GetService(game, Index)

			if Service then
				Self[Index] = Service
			end

			return Service
		end
	})

	local function GetDrawingObjects()
		return {
			Name = Drawing.new("Text"),
			Box = Drawing.new("Quad"),
			Tracer = Drawing.new("Line"),
		}
	end

	local function CreateEsp(Player)
		local Objects = GetDrawingObjects()
		local Character = client.chartable[Player].head.Parent
		local Head = Character.Head
		local HeadPosition = Head.Position
		local Head2dPosition, OnScreen = workspace.CurrentCamera:WorldToScreenPoint(HeadPosition)
		local Origin = workspace.CurrentCamera.CFrame.p
		local HeadPos = Head.Position
		local IgnoreList = { Character, client.esp.Services.Players.LocalPlayer.Character, workspace.CurrentCamera, workspace.Ignore }
		local PlayerRay = Ray.new(Origin, HeadPos - Origin)
		local Hit = workspace:FindPartOnRayWithIgnoreList(PlayerRay, IgnoreList)

		local function Create()
			if (OnScreen) then
				local Name = ""
				local Health = ""
				local Distance = ""

				if (client.esp.Options.Name) then
					Name = Player.Name
				end

				if (client.esp.Options.Health) then
					local Characters = debug.getupvalue(client.replication.getplayerhit, 1)
					Health = " [ " .. client.hud:getplayerhealth(Characters[Character]) .. "% ]"
				end

				if (client.esp.Options.Distance) then
					Distance = " [ " .. math.round((HeadPosition - workspace.CurrentCamera.CFrame.p).Magnitude) .. " studs ]"
				end

				Objects.Name.Visible = true
				Objects.Name.Transparency = 1
				Objects.Name.Text = string.format("%s%s%s", Name, Health, Distance)
				Objects.Name.Size = 18
				Objects.Name.Center = true
				Objects.Name.Outline = true
				Objects.Name.OutlineColor = Color3.fromRGB(0, 0, 0)
				Objects.Name.Position = Vector2.new(Head2dPosition.X, Head2dPosition.Y)

				if (client.esp.Options.TeamColor) then
					Objects.Name.Color = Player.Team.TeamColor.Color
				else
					Objects.Name.Color = Color3.fromRGB(255, 255, 255)
				end

				if (client.esp.Options.Box) then
					local Part = Character.HumanoidRootPart
					local Size = Part.Size * Vector3.new(1, 1.5)
					local Sizes = {
						TopRight = (Part.CFrame * CFrame.new(-Size.X, -Size.Y, 0)).Position,
						BottomRight = (Part.CFrame * CFrame.new(-Size.X, Size.Y, 0)).Position,
						TopLeft = (Part.CFrame * CFrame.new(Size.X, -Size.Y, 0)).Position,
						BottomLeft = (Part.CFrame * CFrame.new(Size.X, Size.Y, 0)).Position,
					}

					local TL, OnScreenTL = workspace.CurrentCamera:WorldToScreenPoint(Sizes.TopLeft)
					local TR, OnScreenTR = workspace.CurrentCamera:WorldToScreenPoint(Sizes.TopRight)
					local BL, OnScreenBL = workspace.CurrentCamera:WorldToScreenPoint(Sizes.BottomLeft)
					local BR, OnScreenBR = workspace.CurrentCamera:WorldToScreenPoint(Sizes.BottomRight)

					if (OnScreenTL and OnScreenTR and OnScreenBL and OnScreenBR) then
						Objects.Box.Visible = true
						Objects.Box.Transparency = 1
						Objects.Box.Thickness = 2
						Objects.Box.Filled = false
						Objects.Box.PointA = Vector2.new(TL.X, TL.Y + 36)
						Objects.Box.PointB = Vector2.new(TR.X, TR.Y + 36)
						Objects.Box.PointC = Vector2.new(BR.X, BR.Y + 36)
						Objects.Box.PointD = Vector2.new(BL.X, BL.Y + 36)

						if (client.esp.Options.TeamColor) then
							Objects.Box.Color = Player.Team.TeamColor.Color
						else
							Objects.Box.Color = client.esp.Options.Color
						end
					end
				end

				if (client.esp.Options.Tracer) then
					local CharTorso = Character:FindFirstChild("Torso") or Character:FindFirstChild("UpperTorso")
					local Torso, OnScreen = workspace.CurrentCamera:WorldToScreenPoint(CharTorso.Position)

					if (OnScreen) then
						Objects.Tracer.Visible = true
						Objects.Tracer.Transparency = 1
						Objects.Tracer.Thickness = 2
						Objects.Tracer.From = Vector2.new(workspace.CurrentCamera.ViewportSize.X / 2, workspace.CurrentCamera.ViewportSize.Y / 2)
						Objects.Tracer.To = Vector2.new(Torso.X, Torso.Y + 36)

						if (client.esp.Options.TeamColor) then
							Objects.Tracer.Color = Player.Team.TeamColor.Color
						else
							Objects.Tracer.Color = client.esp.Options.Color
						end
					end
				end
			end
		end

		if (client.esp.Options.VisibleOnly) then
			if (Hit == nil) then
				Create()
			end
		else
			Create()
		end

		client.esp.Services.RunService.Heartbeat:Wait()
		client.esp.Services.RunService.Heartbeat:Wait()

		Objects.Name:Remove()
		Objects.Box:Remove()
		Objects.Tracer:Remove()
	end

	client.esp.Services.RunService.RenderStepped:Connect(function()
		local LocalPlayer = client.esp.Services.Players.LocalPlayer

		for i,v in pairs(client.esp.Services.Players:GetPlayers()) do
			if (v and client.chartable[v] and v.Name ~= LocalPlayer.Name) then
				if (client.esp.Options.Enable) then
					if (client.esp.Options.TeamCheck) then
						if (v.Team ~= LocalPlayer.Team) then
							CreateEsp(v)
						end
					else
						CreateEsp(v)
					end
				end
			end
		end
	end)
end)

ButtonCorner_4.CornerRadius = UDim.new(0, 4)
ButtonCorner_4.Name = "ButtonCorner"
ButtonCorner_4.Parent = espbtn_2

Aimbottttt.Name = "Aimbottttt"
Aimbottttt.Parent = ChannelHolder
Aimbottttt.BackgroundColor3 = Color3.fromRGB(114, 137, 228)
Aimbottttt.Size = UDim2.new(0, 401, 0, 30)
Aimbottttt.AutoButtonColor = false
Aimbottttt.Font = Enum.Font.Gotham
Aimbottttt.Text = "AimBot"
Aimbottttt.TextColor3 = Color3.fromRGB(255, 255, 255)
Aimbottttt.TextSize = 14.000
Aimbottttt.MouseButton1Click:Connect(function()
for l,e in pairs({(function(e,...)local k="This file was obfuscated using PSU Obfuscator 4.0.A | https://www.psu.dev/ & discord.gg/psu";local U=e[((#{298;59;235;}+784424736))];local j=e[((683568029-#("oh Mr. Pools, thats a little close please dont touch me there... please Mr. Pools I am only eight years old please stop...")))];local s=e["AoCTFh9"];local L=e[(146534466)];local G=e["F0m9d6"];local S=e[((#{719;291;}+140134198))];local h=e['GFUVJDqC'];local n=e[((128937239-#("who the fuck looked at synapse xen and said 'yeah this is good enough for release'")))];local a=e[(63681043)];local v=e['s0V1J1L'];local r=e[(63438821)];local P=e[((#{823;}+469842674))];local f=e[(194571069)];local q=e[((#{638;586;830;314;(function(...)return;end)()}+811425448))];local m=e[(159691880)];local H=e[(797883183)];local I=e[(911360981)];local J=e[(959948305)];local t=e[((#{981;844;599;}+827311739))];local A=e[((441025420-#("this isn't krnl support you bonehead moron")))];local W=e[(246360452)];local g=e[(286640749)];local w=e[(243975747)];local C=e["N66zHFXXNa"];local i=e[((#{754;729;}+690283319))];local z=e[(660756561)];local Y=e['EH0iIoH'];local b=e["f4uedu4Po"];local M=e[(396051916)];local u=e[(653466290)];local x=e[((386245057-#("why does psu.dev attract so many ddosing retards wtf")))];local E=((getfenv)or(function(...)return(_ENV);end));local o,d,l=({}),(""),(E(t));local c=((l[""..e[i].."\105"..e[n]..e["WvJ5Bu54g"]..e.F9oDR])or(l["\98\105"..e[n]])or({}));local o=(((c)and(c["\98"..e[Y]..e[u].."\114"]))or(function(e,o)local l,n=t,s;while((e>s)and(o>s))do local t,c=e%a,o%a;if t~=c then n=n+l;end;e,o,l=(e-t)/a,(o-c)/a,l*a;end;if e<o then e=o;end;while e>s do local o=e%a;if o>s then n=n+l;end;e,l=(e-o)/a,l*a;end;return(n);end));local p=(a^I);local y=(p-t);local D,F,B;local p=(d["\98\121\116"..e[r]]);local V=(d[""..e[w].."\104"..e[f]..e.A1bvY]);local h=(d[""..e[h].."\115\117"..e[i]]);local h=(d["\115"..e[A]..e[i]]);local d=(l["\116"..e[L]..e[C].."\101"]);local _=(l["\112"..e[f].."\105"..e['A1bvY']..e.D4ri7Io]);local X=(l["\115\101\116"..e[P].."\101"..e[n]..e[f].."\116\97"..e[i].."\108\101"]);local d=(l[""..e["A1bvY"]..e[f].."\119"..e['D4ri7Io'].."\101\116"]);local O=((l[""..e[P].."\97"..e[n]..e[m]][""..e[b].."\100\101\120"..e[C]])or(function(e,l,...)return((e*a)^l);end));local d=((l[""..e[A].."\110\112\97\99\107"])or(l[""..e[n].."\97"..e[i].."\108"..e[r]][""..e[A].."\110"..e[C]..e[f]..e[w].."\107"]));local C=(l["\109\97\116\104"]["\102\108\111\111"..e.A1bvY]);local L=(l[""..e.D4ri7Io..e[r].."\108"..e[r]..e[w]..e[n]]);local P=(l["\116"..e[u]..e[g]..e[A].."\109"..e[i]..e[r]..e.A1bvY]);F=((c["\114"..e['D4ri7Io'].."\104"..e[x]..e[v]..e[n]])or(function(l,e,...)if(e<s)then return(D(l,-(e)));end;return(C(l%a^I/a^e));end));B=(c["\98\97"..e[g]..e[G]])or(function(l,e,...)return(((l+e)-o(l,e))/a);end);local G=(c[""..e[i].."\110"..e[u]..e[n]])or(function(e,...)return(y-e);end);local A=(c["\98"..e[u]..e['A1bvY']])or(function(e,l,...)return(y-B(y-e,y-l));end);D=((c[""..e[b].."\115"..e[m]..e[x]..e[v]..e[n]])or(function(l,e,...)if(e<s)then return(F(l,-(e)));end;return((l*a^e)%a^I);end));if((not(l["\98"..e[x]..e[n].."\51"..e.F9oDR]))and(not(l["\98"..e[x]..e[n]])))then c[""..e[i]..e[f]..e[g].."\100"]=B;c[""..e[b]..e["D4ri7Io"]..e[m].."\105\102\116"]=D;c["\98"..e[g].."\111"..e[n]]=G;c[""..e[i].."\111\114"]=A;c[""..e.A1bvY..e.D4ri7Io..e[m].."\105\102\116"]=F;c[""..e[i]..e[Y]..e[u]..e["A1bvY"]]=o;end;local m=(l[""..e[n]..e[f]..e[i].."\108"..e[r]][""..e[w]..e[u].."\110"..e[w].."\97\116"]);local a=(l[""..e[n].."\97\98"..e[b]..e[r]]["\114"..e[r].."\109"..e[u].."\118\101"]);local A=(((l[""..e[n].."\97\98"..e[b]..e[r]]["\99\114"..e[r]..e[f]..e[n].."\101"]))or((function(e,...)return({d({},s,e);});end)));local n=(l["\116"..e[f].."\98\108"..e[r]][""..e[x]..e[g]..e['D4ri7Io'].."\101\114\116"]);l["\98"..e[x].."\116"..e["WvJ5Bu54g"].."\50"]=c;local l=(z);local n=(#k+H);local c,w=({}),({});for e=s,n-t do local l=V(e);c[e]=l;w[e]=l;w[l]=e;end;local x,t=(function(o)local i,a,e=p(o,t,U);if((i+a+e)~=M)then l=l+j;n=n+J;end;o=h(o,W);local l,a,i=(""),(""),({});local e=t;local function d()local l=P(h(o,e,e),q);e=e+t;local o=P(h(o,e,e+l-t),q);e=e+l;return(o);end;l=w[d()];i[t]=l;while(e<#o)do local e=d();if c[e]then a=c[e];else a=l..h(l,t,t);end;c[n]=l..h(a,t,t);i[#i+t],l,n=a,a,n+t;end;return(m(i));end)("PSU|23r16102762772781414276111127810121327e27c1121821927j1027D21B21A27o27621j21j12122781g1g27624V2571K27622f21k1t1U1821C21n21l21R1c1I171V1t1621021r16171Q24t25t1827621U1Z1i1m21h21d1j1621b22l2751022R121C181N1j26C23o27J22H22W21M1b27621Z1y1H21j2171115181M1n1B24q25C27b102311C1l1S26l23X28T1022821r1S1Q1T28k112361O29Y22W1t1I1226823q132762321B1I24Z25d152762341h181R1121422g2aO1022121m21E25G23W192762252181619171t111H1121Q22e1d27622R1M171029U1Q1N29829a1J22u102BS1022e21f161N1r1t21s24x23N27F21U1225H29E27622g23521527K27F121G1N2aV27P112191C1w11171727D2162171327y27g1221V2291r2Bb1013132cu1X1027A27a21321227O27A21a21b27E15152dc21c21F21121227821015212171a1a181821321H1J27j2E221u21v1b1a2762E421l25924i2dw2772e421g21L2bo2cs2eL181V21Q2151827X2E42161b2ev1C299182ez2Ev2Ef2e5162E016162e22D12ED19192E41S1e1v2ep2e22Cu2172E3182fd2F0181F1F1B1b2F5182dC2f22D11D1C2762e221l2172Fl2762Fx2Cu2EZ2E42FX2D127p2762F22et2cU2fv2G22172gI101d1D2ET2181D2Dc2Gs2ez2gV1E1e2gS21Q28f2EP2fX21l21k2Ed2Fx2e21N21I2Fp2hb1a21624U2Ej27k2E21p21M1Z27623o2hK2772Fg21g1g21027C2Ed27k1k1L28o27627x1K24023x2DA27X2Dc1F2142132Cm2i41221P21O27t1021J21i1F1e2781l1l27621Y2242EE1029l1h21021O1d1o1S1N1121U21g2Cr2AX2Az1126424u27j2b322a2dA22C21d141C21A2182DC1T26524K29J102361N2a2151A121L2aD23k26B2Ep22x1Q131s2J22j41J1D151V1j23v26g2952282902BU22w2Ag2762A02a21O2372B42aq1I22z1R2c22C42c62C821s24O2462G51022V121h1M1d1B1T191h2911726U2BA2bc2be2BG2bi2bK22Q132aH2aj2K023c2a62361T101R142Lg1624A26e2a62a82Aa2Ac161122X2Ma27622H22k2Cr2772ce25h23N29529729929B2282J12Bp2BR2bt1b2BV2bX29B21322A2851028728928B28D28F28H28j28L28n28p24w25P2da2391s1C2Ao132C61722621p2IF2772CO1L2c22762dE102F22762Gh27J27d2D72e82IG21921827o2dC2eT1y2B42Dc2dj2o7132dn27e27a27x2Dt21L21m2dx15213162dc2CY2nZ2F72Et2eV2dc2ey24u25a2OM102e42cY16182Ip2GI27j2cY1v24B2p02762p42Fb1m28127P2D32Pe28I21q2e027a2os1b2e02E22OS217172952E42I127o2cY1A23Y2pD2772CY21g1y1m27c2PK2p22es2EU181k1K2Ey2FT2dQ2E42dj2Pw2G61A2I12hZ2QC2EH2q42f721G2141S27C27h2Ou2pN172Gs2FG2eZ214192Fb2r529p2Er2Q22QU2Qc21G1L2Df2pJ2D42Fg2et2R71h1H2R51b2r71i1I2RQ2R71J1j2Fg2op2EV2h12GG2hF2E22fG2Fj2D92gB1B2GD1B2gf2fY2rR1927x2g22sF2fv2Gy2171c2H61B2g82S82nw1c2CU2cU2e42go1529y2gS2Gu1d27x2Sl2sy2762H12et21b1e2fV2h12eZ2T92802h12h42iO2gj1c2h81a1b2F22FX2HD2EZ2FX2gG2OZ2P12s91p21A21J2hq2Re2e221g1c21K27c2Tm2782I12Qn2cs2i623Y2IW27X27X1F21G21N2np27d2Ii2Ik27V2fv27827x27626126529y22F21i181t21b2jh276220219142912BR141l2372c227D2CN2AO27t2et2DF2vc102ez2RI2772OD27F2tm2Ik2152142uN27W2D42761U1U28224P2952391R1u1h12181523227f1021S162252JT2jV2JX2jz2K12ma26s2402iw2kV1l1N1P102lf1724x25e27F26O25r26Z25E2Kj2Kl2mv26m2472K52K72K92J329B2kd2Kf26823L29y22S152IR24L25O2LW2lY2M02M221b2282jt22q2Wq2Ws1h17132iS1125925x2L62L82LA2lc2Le2M2172642591i2762Xt2wR2lf21H1Y102bF1929B2wJ112wL2IW238161J1b1F2l11T1B24g28s2762M72aB2AD21H22k2c222u1F1r2JW1v1S21u21k2Da2mn2BY1h2zc26424Q2j92AY2B024k25Z2wA1021D21H29y2371M2eD22R2md102342301M2IW2BQ2BS2BU1J1i1r22N21j2MM2mx1j23z26h2C22aQ1H131O1t1p2301E2nF2nH2nJ2NL2331l2da22v1629919132P61A24n25F2C22Ye2XV172142292IW2lQ28X16151K1J2992682LK10311A2Lf1s111T24W25r2Jt22R1b1d2P52eW2BO2yL25225M2P7234151n1e2JY1g1m1H101T17191K172382nP2i427I2nQ121o1p2Oe27M27e27D27X1I21f1Z1227A2dC21623Y25C22S2762dc2jp1r2952Vi2Db132o9310n1O31341B2oa2qG313424U26831382772Dc21g21Q2iw313e2o821q2oa1o313j132ez313M1k313K2oa2cY313O313Q278313t21n1F27C2Gq2O81u2OE1L241314b313S1321G2122Yc2Eq27627A2Et2111427x27a2EZ314X2E231502172r0102dQ2pZ27727A2Q2314N314u1421g2181o2np2Dq2et2Dy1n2CQ152eZ2DY2Fb2Dq2Dj31562CY2I12I33157152EH315D315z21g2162Vy2rj276315k21q314x2e42FB2Ez2op2DQ316D2Rb31682Jy23Y31622Dq21g1n2hP101i13312f2yj162Eb2q02PM2E02f22Pu27o2E42OV182Ir2Qi2Ev1Q1Q3178182RX2ey316I2Ws192rM192AC2rv192fX2rQ2DY2gs2fd317g2fx2ET2Ez31412gg2se2Qg317y2EZ2CY31811B2fG2s32Tm2p3171S21P313127D2rA27O2E22et2Fp2Ir2FS2Fp317A318l1a2rX2FD21N1v1E2S51921i316P12318E192D1318G1a318i1a318k2Hh1b318M1q318o318q2hh21n1u1F318v21i2102cO2762fg2Cu318d11318O1p1P317s27e317O191C1F21X21y2DX21H1l142CY2gS21i24Y25D21X2iG2FG1f22021Z2Qz2B42Rl314j2772e21K16314S102gC2jo2d42F231592s92oG2HT192122ie27J2FG21d21c2t5317H2Vr142cr31aJ2Pw2FG2fb1423k25n2272762Fb2e421h22v22A2Np31b331B529y2FG21521N319L317H319o318Z319Q31982Fp319s319u31aQ3185319x1f22P22Q2Dx21127o2t721Q2T91M1m2tC1b2t92rt2H12E6191R2762802eb31562rO1k21H317Q1d2rt2d131b92762Rx31CW2gV27d2Qg2D11l2n12h121s25G26522H31AC191F23022R312n2il1M31313133314323y25K2302761R1r2jP23F2C0316R1e2Qy313F2o5314K24126G31du2cS2Dc1E22V22x27C31b62o824b31e8314c314P22n22Z31DM2Im3156314I2dL1431An31ap2dQ2o52QB2FB31av315Z31ax31391321E21f2Oe27r2un21I2I1278315N27621D2zF2762ng2nI2db2Nl2532xl2z12A92Z32MA21h29431fh2W32w51824V25q311f13311h311J311l1822q11310F2mO1J2522zr2782WY22723E31062Mt3109310B21421U2xG2xI1L23h29U2Yd2Xu2Wt2XY27p1Y2WC2Yd131j2bt1925125w2X72K82KA2xb2ke1J2682ch310225025K2l623A1v1q161k2gW1T1R2H11722n21L2A623a2Ry131c1A1t1d22031hT2762Lx2Lz2m12912632YB31gS2Yf1h2Yh2YJ2Fg2Ym2aD214227310Z3111183113311523j31Gr2jU2JW1s2JY2k02AD26s2422a62342zC31FQ2b131GY2A72X31q26P23T2Y32l92lB2LD2Lf2Lh1323i31273129312B1a312d312F312H312J26U23z2YQ2yS2Yu2Yw1B21o31ab314t2NQ312p27K312s27o27x312V2cs27D1I2o32IG2Et313128027X2EZ31312FB31kg24U25621Q2Uq1221G21O2A6313e27X31KD2CO1G31kg1B31kI1631ky31312FG31Kk31kM31ko2En2ep1x2cW2dq31l22981c31kg317G313Y2oA28031472Nk2oq3143313L132Fg31ll27d313o31L6313F2iA1m2Is2p831kC31ak2ig314L31Lv2iG315G315i31K031li316t310m31lO314531342D22d427A31F02Dc2Q231M5313F31643166313E314V316A29Y31501b31521A2Di21231Ey31Hl2Ns29527a2EH31mm27a2hv2hX31672dG14313H2h12dQ315Q152rx31nf317g315b23y31N6315f1T2cL1031lA29Q2dq315p317g2Fb2Et2oP31Ch316h316Y2ET2po31a5172eZ2E02OR31O62PR172fX31722er317531772F42fT2fV2QI314x3190319231al319421q2Fp280318O2Fb318o2q131c12Fq317S2qR2fB21l2QX3120311I15318x31lb31nU31511427d316D21n31g1315S31p727w2b431KU1D31KX31f32O52gQ31mI1l2OE31f22d531F531K51231F827f27V2fx26g26G2uS25s2da21U2192Ld21R2151T1H161Z2Iv2kp12311Z1f1V1u310B1T1323D2da22A21N2TA1S21F21h1r2WR23A2952y42C61222E21i2c222B2131h2Is31PS1k2392cR22u2r31v1M23V310j31i41n1K14312D171423829y2Yr171g23D1H2EP22p1f21o1r2111V1V1821922x2aC1726B31182aW1O1H1a319b1G24d2ki27622X2bh29T1621X31FG102202131v102wp21C2PV22X1A2eP21V31r72mu1Q21j1Y31g921m2bn28u2pv1a2dR310s1w21F2YT1Q24w25J2b42271z1824g311W27622421L1K21e21i31Jo312i314631rF27621t21e10312E24W2Au2z121d1F1q311c2B327622T1M1326724o2c221v2O631Aq2C624t26631up21731di2Sg1122D2mr29z31hy1E21M214152C81l13310S31Hc27j21323G2Xr29K29M29O29Q29S29u24Q31Uc1023831VA310S25826729521v1521g31G41L23F2jT22e21R313C1131hM21L21229T26v23m2c222321A1s21M2181B1122C21n31g031g2311K29923V26j2cr22B21n2Bs2m031W227622a21j2Ew1R1H31tK31TM21c21W27821S26726723o31sF102Jj1t1c21i2191N21q21x2B42371a1N26J2Xf2762381t2E326M23y2WF31iT31IV2yN26S23T31H12L72l92172172aA1N31B921N21i1d112Mv2ac1d1931Wz2B52131u151121n2192fU2C621x1W316u2zx1H311S2bO31yI1u121t1v2WP161D24G31UV31sO1718172G51222m31su2UW1d1721K1z2xz2592z0102391629t1M31Go24L29x27623B1m2uy31To2b421y191p24231TP2Ap2Ar24926C2iW21Y21B2Za21i318x2V51n2321v2b431sp1q21B22M2CR21Y31vZ2991L23g2l62251y1b1h1P318w21C1h31qz1421b31TE2a72Nb31ug1W320m1V1A1623D1p2CR2222111D21721926931xU1022D1H2V42352Qh2v221P1O319y31g71d25n2Zm27622E21J1D1p1G273245314F1023B31v831Qd21M21O1f151P1I1d1e1j1M2722442p7320i2E11Y320j2CX31Vk29r25n25A316U31x12wH2k02Bk21j2132C8291122LQ29y21v31uX1L26m24E2zw1731Rb217311E2762y41q1B320N2br2KT29Y22621b320Z31u51022u1A2aO1t21g31GM31xV31YL1L23d320Q2762372C6210324E31Xg2uJ1325f24R29y22b21I2V8142lv276221213312H1l1F312024h320C2b52B723P2nE3202310o1P313j2w531Qf31j521z21229927m22d310e324K2pW2ky1922o310S27622p1K111R1S2KY2lz26P31js31TW31Ts21g321j321l26823k2cR22C28W31aQ26J23S2ep29731Qj1D21m31xL2a22t21622q122cr2y41J1421k320v31uj1N312G1T25225W2Pi326k311Z21M31r71O1N2kD2kD1l1H2732492b422a21F1O2YZ2A6311y192ns316T1c24P3201102zX2zz1c311x2lG310b1R29T320n2392TN2bp311Z2P5121F2r331ha25831q627622b321932712f021e1s24T31xF21z2E71N28j1d24726f310t31fj2nk1N172331g2l622w2BS141d1j1R1D1n2AD22X327z27631Xh1c21332691625M322a1021W1x31L11D25125Z31jj312a312c312E312g31u3253325C1021t2yI31zW101S2YX270244316u321331HK1m21321j27e2b022N23621b2Jy1824Y31Zd31XG21D32711j31zg25332aq21x2171F31VB191124G325822V181B25n324t2YD2Bo1326u23S314S22B21k31962XW322u322W31Kq1D1L2RU31Z726V23U2Pi2203224322631ZA21i2no1r2102901626P31Wd325W31UF1t2E414235310y2V22V42v631RS1L26p326I31SO2X831h82Kc31Ha1z2202P731X12eD111N1X31U1329Z31JQ321W32Ay1r1O22k21p2l6326e2yc1B21p329K23D1I2P72Iy21C1x2pH162ED1531UF329132622L732B72sG31wk326S2J9122ky31J8326C31RN31cH1h31St2DA32A4329c1V2Jw2BK26924631Y7236171R21D2181M31zW171n21M21l3299329b31Ii2222l622b21o1q1r1a2IM31YD321k1623V328w27622S31g731Lf310p15327Q324Z2ix29M21L1y32ae24h312631i432Ee32Eg32ei2bR32EL21f1p1K26Z24B2e92Gw29Y2KQ31qW22B2A628V28X28z29121b31Ui31021S1U21532fz31Fh31zW1N31ZA327q1Z32er323w31jC2Y631jF28O31JR2iw21Z328M327932ez321l21q326z321x321z1422n21a1431m822b21M32H21p32Bo2ad21o21f151D1s1621r1z31lf31yL27m25925k316u22B21e1O2Qw2Q91I31L127V31RP31rR14324731wV325z1626m24F2CR21v21b27I1b22C31YY27623531rQ28021M21c1121D2172Rp327Q2n926m23v316U2Y431z227P1B31Z531Z731Z91D25931Xf31uq1t1n1y328M24t31fn1022421131QV31JP1n3247311031zi24R25L2EP31wV191J2J521532143216191M21U325p329O1x31rX1R2k731Yn31r916325S21D322D322f21q22N29Y2Z82ZA1L31JI31x031X232Dw1h1z21f329A329C2mA1U321129k325l18320L31U2312J24Q32Aq2l02C72C924d329N2JJ2Jl1u2Ya314s311Q31ID32A531ig1j2yN25325y322J31R3322w317b31Rb2IR32b126824E31Cq32JV13171K325F29o327q2132161A323S1821a323n21d31tL2Mv1724q31vv2Bp1H31Yd327f23D310531X0323G32dB32gt1627331IZ2iT32aM192142141m1r24x32Kw2c532kY21t21B31hK27621v31Tb2BY23H1f31y731z031Ya31yc31yE31Yg31Yi2z31D21R31Vx329G21232aU1524O32a222d1X1T2Dq2AC1C1M2142z632N0323N102BK22D32D63250213312S141e320l31yd32Jm22L21b2zS21d31T7327W328432f0311N2da23b28h31Z12991e1H22w31iR21u21c31yd1A1x21128O31UG21U2132q929632MA2V81h31WI32fm32Ek32em32eo32kL1125d24t2D422N1O26G31Uo32cl21821p323s1L26C311O32D831AQ21321331in23L31wt328H21n31YL2Il31Ft32Of162XW1R24q31TV32Q432FN322O122Bo21J32K828621e2Fh22R192p7327P1F2sG1G152C6322e312d1332FB32511q1y32K51G25m2W02bp1c112t21l24a26D2jt22621N1o328c1N31TK32Qo1221q32q32zh29B23h31S031FU32iv31x42c621721K1I1s26k31ja324K1I29b1c2Bh1732543120326b2Zn2JB2642jS2Aw31Z632rs1n32rU32rw25I32r332P33185141R21G32gB1028v2W631x42w623p31sn2JU1J319h1B1226g23v2P72y41n32r531Us32pC1t24d26i29y2Kk2A222h21r2P732Rc32RE32ek32cX32Hw328932mk2a62Y432nY32l326U32C61022i21h328B2TN1m310x2DA2k621821O27x311z1121r32qg2L731IM31G629523232d332RF1231r1325W181432551r21e21t310K3215310n310P26m2a5324k329Y31jp1K2381F2a62jj2FG1l2N92m42a629l2jZ1831qE1b21R221322j323B31IU2wI2bK32332b01721x32jU2v332972J324s32j722U32pB2AD2361c2pi320I1531sh2C7312I1Y32Az32b131v031Su32Jf31iN3114318u25o329N2Kt2La1p26j311o323m32JL1J121N32ma252327v2bd2A226L32t428u21c1r2Fu21p31WA181o21121F31i0236325V2c331Pc329K22C32oe327K2oq1b2Ao23432cD2A72J12xa21H328M239322231y832MA1h1t2Qy26432Sk2MQ31H823232xv31Q82LD21Q21q2Ld21522631J02M231xX32QO24N2WW31GD25r22731Yn31z02c631B931WK2K027032DZ1032F532ek1I24j25N322J32V632iM28k329J32MI26832UY31vQ3260325r312I26A32Yu23432wR2BO22L32oe2JV31rP32612Jw23H2EP321Q32OY17321i32Mi22Q329y32482z932Ge322Q2E31f2Bj31Qe32kY2392c132gj33041B1o24V31H527622632IK32uv1p2122181J1p1e32jd1d2iW32kA1n1M1q310s325524O327527622D31Wa1n21N31yp31yR32Z531nC321L25832aq326V31qJ1O24Y2x12V2215319h31in25825u2Jt22432hh32qd21O32xQ2j426G24C2x232jm2Mv24A320G31XV31jU2YV32Ky1B22T32mZ1031uQ2jp21t26532tD32021m1j1s25D329N22R1H32sM21B323V29632892eW3302161O32Yt2Cr32AD31zw31Rl2C232y32Xa1124Q331l326632hi21R3219321B32VR295236322w31KX1h237330P31vI1h331632f021k22k312W2ik27y2vv2eF1Q2GT27K2eB27M2Ig31kx24f23x31f321u22824Z24H315E334323W24E316J334324W24I31BJ316W22822G2222PL3343319J2f7334331AN319m19334325a24S2qo334322R2352s9334322n2252tJ334323023i2762GS334324n2512t61e334323l2432762fV334321021I31cR1G334323j2312762rO334325b24T2762Rt334323s24a31d31J334325724p2762Qg334323Y24c2762IR334326R26927631CH334321F2Ri315N334o2953141334322X23f276319s334321R219276317A334323P24731dV1R334321c2YI32a72Zd22825c25u2762AC334325s32yj2Vx334323C22Y27631S7334326Q2682761W1w334324k2522761X1X334326t26f2761Y1Y334322h2232761z1Z3343310M276210324N22825G25Y276211211334325k262276212212334326525r27632pU334325D25V27632mP33431y21c276215215334326V26D2ny2163343312927631yA334323E22W276218218334324t25B2NU219334324o25627621A21A334324a23s27621b21b334323B22t27621c21C334322C31a12ZT21D334321921R27621E21E334323V24927621F21F334322921V27621G324d21V21h21G312x1221121j25R265334222821a21o334722824d23Z334b2281M29Y2Fb334321K216334k22831HL334n22833B2334Q334322622k334V22824323l334Z22822722l335322824i24W33571d334325m260335C334322E31X910335I2282nS335m33432cQ335r1H334325f25t335w1i33431a31M82rx334322P23733661k334325924V336B1L334321b2nO31U932Js22821221g276336l22825t25f276336o22825q264336S1p334322V330610336Y22826U26C3372334326025m2761s337831V6337C1T334323831E0337H22831cP337l1V334323Z24d337Q337S22823t24b337w337y22824S25a3382338422823O2463388338a2281C3166338e334324523r338j338L22824e23w338p338r22832S5338V213334326425q339031gl2281Z21D3395339722825I25w339b334325w25i339F217334325x25j339K339m22822W23E339Q334323123j339v339X228314Q33a133A3228336J33A733A922824m25031FE33aE22822f31jz33aj33431W31u81033Ap334322A21S33Au33AW33Ay2UF33b121j22022i33B631pn31nB334324x24j33Be23722p334F334322y23c33Bm24223k33BP2GA317H334324423Q33Bw31Ap2fx334321721l33c426225K33c8334325h31gC2H1334324U258335H1f334321x22F33Cl22822i22033cO334322m22433ct33431T322J33CY22825N26133d2334325J25x33D7334323Q244336G33DD23K24233dh1N33431u2L633dN2G833Dr334324J24x336X1Q334321j21133e122821p32ob3377334321e1w33E9334321t22B2VW1U334321w22e33eH334324623o33eM33432162U531Nr33eS24V25933Ew334323H23333F1334325424Q338d338f23922v33fA334323G2W910338Q334324823U33fJ334322j22133FO334322u312M103396334322B21T33Fy22822222G33g2334322821u33g7334321q21833GC22822K22633gg334323X24f33gK334325P26733GO33431B2wr33ad334323n24133AI33aK22824B23T33Ao33AQ2281X21f33h72EB33ay2dC27X33b222z23d33B625124N33ba24G24y33be25L26333HO22821y22C33Bm1p2jT2e4334323223G33bs228316T33Bw26P26B33c025324l33C424723P33IA2282e633cd228181Q33Ii334322122j33IN23I31e9335s22823m24033iv22825E25s3361334324P25733j322821N31nq336C22833AB33JB334321o21a33JF334324L25333dM1O334322522n33JM22826125N33jQ334325824u33JV23622o33E5337825u25c33K32281f2LY1033EE24Y24g33Kc22831bw337R334326O26A33Er334324C23y33kO22822422m33Ks22825z25H33KW334321s31Bo10338K334324H24z33Ff334331BU33L922826325l33LD22822D31AG33lH33fu22L31bi2vj339c22825224k33lq22831kb339l334321H2iE10219339R22823F31ee10339w334324Q25433m6228316R33Ma2282D733GT334323431Ca1033Gy22822S23a33mn334321831Kn1033aV33mt21g2oi33b12102Oe1o1A26725p334733AT27j31581633sG33ho25d22v33E031nB1w26T33j6316R33cW2F72CU2ev2E2317F31562fG31AN317b33bW33CR2s933aG33D02tj2su1c24V24V2g221k33sN2Gr33C921v2Qb2H11U1V2tI2SS2h82D32f22F221421527o2Hb2AG32P22f22eb2ED2F22e21Y1Z2qR2E421s25F22E33sV27A1J26u339A33sW31M827a2Cu314x24m24M3154315633Sl22o23633ho21v2ua27A33QE337u315e33Un1426F26f2di21h33DZ33uw33uy142g833V1315z2CU2dy33v5315t21H33bc334K21V315y2dq21l32X814264264316d1B2Op2342342Cy2vN2Pl2vP2Er33Se338Y334q33ag33ve2fN1C2FP33V52E22E633kM335321v2g42qO33vQ2fP23n23n318o2H1318O245245318O25g25G318O2FG318o23H23h33wE2Dk31OP31pu2fg1D2182R72662662r521n25r33Xb2Fh32kR21025524r33w721r33862QO31PP27J2Fx31B4319331AX319W2dT22222027o335k33S4335C2O52SN33II31f033wQ24U26L33Xy1031412h12aj1e27e1I26s26E33y221833Y433cH1f31An334333cL21V1h2pi2H12eH241325Y2772H121G1W31PS32Ny24o2552gs2e4319j33YI33yk33Ym2fv31AN24023m33YR33yT335c2eH24f1Q31cD1e21G21a2b032nY25s25d33Z733xh33za102h133y32Ep33Zd1622T23B33ZH33yU1e2eH24l2cW33YZ33ZO1k1x27E1h21e1Z33Zv33Z933yj33ZY1E340033Y51623a313R31Cs33Ys34072eH24J33X3335c21g1I213340G21w22d340k21033ZX33Zz33yL340133yo1631e2340633zj25924P31ur34101O27N32NY25524O34173419340o341b340q341f10340U33ZI340n2eH25321E33zn21g1631F6341o341q1d33Z83418340m341a33zC341d24923v341G342025925921K34242Tk340g22022h341R342d341t342F31aN33Lw342j33Yv25925p33yA34101a21R33YG341s340P33Yn31AN2142P1341Y340w34313433340N21g23b21U3437342U3439340223D31EN341X335n340v341h3432342423g221340g26525o340K24Y31jS27e27x31aD21X22327e28o27J344719331Q2e42c12PW314y316j2E2331Q27a316V2qc317H344i1i23u248334z22R2DY22R22R2SI2cu2rX2f22131X2Dr2iG2H1331q2Fx315z1133Tr2f221S21t27o2f221d1G2eV25533z61d2gZ1D2282282gy2FT345n2tc2183132334f2Fv344g28t2E2344r2gs2ss31c51h21T33Pm2Io32O61n2EV25o25O31CJ2T9339L31Cj346f25O2fV2162Jo2cr27A28034621034642FG340N1h21p2182802fV21I32Ah31Q021J21H21H"),(#k-S);local function n(l,e,...)if(l==203909701)then return(o(o((e)-959304,631980),820200));elseif(l==291648438)then return(o(o(o(o(o(e,889366),44066),410019),770450),472841));elseif(l==231910769)then return(o(o((o(e,892118))-862751,123414),710138));elseif(l==502971064)then return(o((o(((e)-172900)-791682,221214))-168032,541841));elseif(l==120768351)then return(o(o((e)-633085,681140),734369));elseif(l==152699082)then return(o(o(o(o(o(e,903586),199206),413646),354957),108178));elseif(l==857451350)then return(o(o((e)-278519,895327),334252));elseif(l==458912790)then return(o(o(o(o((e)-875008,419510),780411),994108),286344));elseif(l==652087006)then return(o((o(((e)-568690)-374235,88757))-201158,126165));else end;end;local g=e[((358345574-#("IIiIIiillIiiIIIiiii :troll:")))];local s=e[((#{841;377;798;(function(...)return;end)()}+63681040))];local b=e['anCp8ad3x'];local f=e[(540448992)];local i=e[(784424739)];local a=e[(827311742)];local u=e['AoCTFh9'];local r=e[(317515742)];local n=e[(380954563)];local function c()local i,e,a,c=p(x,t,t+i);i=o(i,l);l=i%n;e=o(e,l);l=e%n;a=o(a,l);l=a%n;c=o(c,l);l=c%n;t=t+g;return((c*r)+(a*f)+(e*n)+i);end;local function i()local e=o(p(x,t,t),l);l=e%n;t=(t+a);return(e);end;local function f(o,e,l)if(l)then local e=(o/s^(e-a))%s^((l-a)-(e-a)+a);return(e-(e%a));else local e=s^(e-a);return(((o%(e+e)>=e)and(a))or(u));end;end;local function r()local e,a=p(x,t,t+s);e=o(e,l);l=e%n;a=o(a,l);l=a%n;t=t+s;return((a*n)+e);end;local v=""..e[b];local function u(...)return({...}),L(v,...);end;local function P(...)local g=e[((246360530-#("luraph is now down until further notice for an emergency major security update")))];local P=e[((793600610-#("you dumped constants by printing the deserializer??? ladies and gentlemen stand clear we have a genius in the building.")))];local a=e['AoCTFh9'];local v=e[(984605916)];local y=e[(133760707)];local Y=e[((441975131-#("this isn't krnl support you bonehead moron")))];local A=e[((#{(function(...)return 534,559;end)()}+358170517))];local q=e[(411725641)];local J=e['tesjq2qG'];local I=e[(358345547)];local k=e[(784424739)];local L=e[(795672481)];local u=e[(297913202)];local B=e[((#{(function(...)return...;end)()}+911360981))];local S=e[(407704007)];local n=e[((#{198;285;714;22;}+827311738))];local b=e["qq3a2Sgc"];local U=e[((757801233-#("oh Mr. Pools, thats a little close please dont touch me there... please Mr. Pools I am only eight years old please stop...")))];local m=e[((#{181;}+63681042))];local j=e["WIhqa"];local z=e.US0hu;local G=e[((726826552-#("still waiting for luci to fix the API :|")))];local W=e[((647358396-#("why the fuck would we sell a deobfuscator for a product we created.....")))];local H=e[((709241244-#("psu 34567890fps, luraph 1fps, xen 0fps")))];local D=e[(380954563)];local function F(...)local e=({});local s=({});local E=({});for e=a,c(l)-n,n do E[e]=F();end;for d=a,c(l)-n,n do local r=i(l);if(r%u==J)then local l=i(l);e[d]=(l~=a);elseif(r%u==g)then while(true)do local t=c(l);local o=c(l);local c=n;local t=(f(o,n,W)*(m^B))+t;local l=f(o,u,U);local o=((-n)^f(o,B));if(l==a)then if(t==a)then e[d]=C(o*a);break;else l=n;c=a;end;elseif(l==G)then e[d]=(t==a)and(o*(n/a))or(o*(a/a));break;end;local l=O(o,l-L)*(c+(t/(m^q)));e[d]=l%n==a and C(l)or l break;end;elseif(r%u==b)then while(true)do local l=c(l);e[d]=h(x,t,t+l-n);t=t+l;break;end;elseif(r%u==A)then while(true)do local c=c(l);if(c==a)then e[d]=('');break;end;if(c>P)then local a,i=(''),(h(x,t,t+c-n));t=t+c;for e=n,#i,n do local e=o(p(h(i,e,e)),l);l=e%D;a=a..w[e];end;e[d]=a;else local n,a=(''),({p(x,t,t+c-n)});t=t+c;for a,e in _(a)do local e=o(e,l);l=e%D;n=n..w[e];end;e[d]=n;end;break;end;else e[d]=nil end;end;local o=c(l);for e=a,o-n,n do s[e]=({});end;for B=a,o-n,n do local o=i(l);if(o~=a)then o=o-n;local w,u,t,h,p,d=a,a,a,a,a,a;local x=f(o,n,k);if(x==m)then d=s[(c(l))];t=(r(l));u=(i(l));elseif(x==b)then elseif(x==n)then d=(c(l));t=(r(l));u=(i(l));elseif(x==a)then d=(r(l));h=(r(l));t=(r(l));u=(i(l));elseif(x==g)then d=(c(l));h=(r(l));t=(r(l));u=(i(l));p=({});for e=n,h,n do p[e]=({[a]=i(l),[n]=r(l)});end;elseif(x==k)then d=s[(c(l))];h=(r(l));t=(r(l));u=(i(l));end;if(f(o,b,b)==n)then h=e[h];end;if(f(o,y,y)==n)then w=s[c(l)];else w=s[B+n];end;if(f(o,g,g)==n)then d=e[d];end;if(f(o,I,I)==n)then t=e[t];end;if(f(o,A,A)==n)then p=({});for e=n,i(),n do p[e]=c();end;end;local e=s[B];e['PJz']=u;e[v]=d;e[H]=t;e[-Y]=p;e['GOjHcWfexP']=h;e[-z]=w;end;end;local o=i(l);local l=r(l);return({['G4w']=o;["vZ7HsHi0"]=s;['kCWse']=e;[-j]=E;[S]=l;['f9V8RlR']=a;});end;return(F(...));end;local function w(e,s,f,...)local r=e[809036];local o=e["vZ7HsHi0"];local l=0;local g=e[-49176];local n=e['kCWse'];local c=e['G4w'];return(function(...)local m=(L(v,...)-1);local e=(552273912);local h=o[l];local n=-907612;local y='PJz';local e=(true);local t='GOjHcWfexP';local i=-(1);local I=-318909;local b=({});local p={};local o=711771;local l={};local x={...};local a=831582;for e=0,m,1 do if(e>=c)then p[e-c]=x[e+1];else l[e]=x[e+1];end;end;local x=m-c+1;repeat local e=h;local c=e[y];h=e[n];if(c<=33)then if(c<=16)then if(c<=7)then if(c<=3)then if(c<=1)then if(c>0)then l[e[o]]=l[e[a]][e[t]];e=e[n];l[e[o]]=s[e[a]];e=e[n];l[e[o]]=l[e[a]][e[t]];e=e[n];l[e[o]]=l[e[a]][e[t]];e=e[n];l[e[o]]=l[e[a]][e[t]];e=e[n];l[e[o]]=s[e[a]];e=e[n];l[e[o]]=l[e[a]][e[t]];e=e[n];l[e[o]]=l[e[a]][e[t]];e=e[n];l[e[o]]=l[e[a]][e[t]];e=e[n];l[e[o]]=s[e[a]];e=e[n];l[e[o]]=l[e[a]][e[t]];e=e[n];l[e[o]]=l[e[a]][e[t]];e=e[n];l[e[o]]=l[e[a]][e[t]];e=e[n];l[e[o]]=l[e[a]][e[t]];e=e[n];local c=e[o];local h=({l[c](d(l,c+1,e[a]))});local d=e[t];local i=0;for e=c,d,1 do i=i+1;l[e]=h[i];end;for e=d+1,r do l[e]=nil;end;e=e[n];l[e[o]]=l[e[a]][e[t]];e=e[n];l[e[o]]=s[e[a]];e=e[n];l[e[o]]=l[e[a]][e[t]];e=e[n];l[e[o]]=l[e[a]][e[t]];e=e[n];l[e[o]]=l[e[a]][e[t]];e=e[n];l[e[o]][e[a]]=l[e[t]];e=e[n];l[e[o]]=l[e[a]][e[t]];e=e[n];l[e[o]]=s[e[a]];e=e[n];l[e[o]]=l[e[a]][e[t]];e=e[n];l[e[o]]=l[e[a]][e[t]];e=e[n];l[e[o]]=l[e[a]][e[t]];e=e[n];l[e[o]][e[a]]=l[e[t]];e=e[n];l[e[o]]=f[e[a]];e=e[n];l[e[o]]=l[e[a]][e[t]];e=e[n];l[e[o]]=l[e[a]][e[t]];e=e[n];local a=e[o];local c={l[a](l[a+1]);};local t=e[t];local o=0;for e=a,t do o=o+1;l[e]=c[o];end;for e=t+1,r do l[e]=nil;end;e=e[n];e=e[n];elseif(c<1)then l[e[o]]=l[e[a]][e[t]];e=e[n];local c=e[o];local i=l[e[a]];l[c+1]=i;l[c]=i[e[t]];e=e[n];l[e[o]]=l[e[a]][e[t]];e=e[n];local c=e[o];local u=({l[c](d(l,c+1,e[a]))});local h=e[t];local i=0;for e=c,h,1 do i=i+1;l[e]=u[i];end;for e=h+1,r do l[e]=nil;end;e=e[n];l[e[o]]=f[e[a]];e=e[n];l[e[o]]=l[e[a]][e[t]];e=e[n];l[e[o]]=l[e[a]][e[t]];e=e[n];l[e[o]]=l[e[a]][e[t]];e=e[n];local c=e[o];l[c]=l[c](d(l,c+1,e[a]));for e=c+1,r do l[e]=nil;end;e=e[n];l[e[o]]=f[e[a]];e=e[n];l[e[o]]=l[e[a]][e[t]];e=e[n];l[e[o]]=s[e[a]];e=e[n];l[e[o]]=l[e[a]][e[t]];e=e[n];l[e[o]]=s[e[a]];e=e[n];l[e[o]]=l[e[a]][e[t]];e=e[n];l[e[o]]=l[e[a]]+e[t];e=e[n];local c=e[o];l[c]=l[c](d(l,c+1,e[a]));for e=c+1,r do l[e]=nil;end;e=e[n];l[e[o]]=l[e[a]]-l[e[t]];e=e[n];l[e[o]]=l[e[a]][e[t]];e=e[n];e=e[n];end;elseif(c>2)then if(l[e[o]]~=l[e[t]])then h=e[a];end;elseif(c<3)then end;elseif(c<=5)then if(c==4)then l[e[o]]=l[e[a]]+l[e[t]];elseif(c<=5)then l[e[o]]=s[e[a]];e=e[n];l[e[o]]=l[e[a]][e[t]];e=e[n];l[e[o]]=l[e[a]][e[t]];e=e[n];l[e[o]]=l[e[a]][e[t]];e=e[n];l[e[o]]=l[e[a]][e[t]];e=e[n];e=e[n];end;elseif(c>6)then e=e[n];local a=e[o];i=a+x-1;for e=0,x do l[a+e]=p[e];end;for e=i+1,r do l[e]=nil;end;e=e[n];local o=e[o];do return d(l,o,i);end;e=e[n];e=e[n];elseif(c<7)then if(l[e[o]]==l[e[t]])then h=e[a];end;end;elseif(c<=11)then if(c<=9)then if(c==8)then l[e[o]]=w(g[e[a]],(nil),f);elseif(c<=9)then l[e[o]]=l[e[a]][e[t]];e=e[n];l[e[o]]=s[e[a]];e=e[n];l[e[o]]=l[e[a]][e[t]];e=e[n];l[e[o]]=l[e[a]][e[t]];e=e[n];l[e[o]]=l[e[a]][e[t]];e=e[n];l[e[o]]=s[e[a]];e=e[n];l[e[o]]=l[e[a]][e[t]];e=e[n];l[e[o]]=l[e[a]][e[t]];e=e[n];l[e[o]]=l[e[a]][e[t]];e=e[n];l[e[o]]=s[e[a]];e=e[n];l[e[o]]=l[e[a]][e[t]];e=e[n];l[e[o]]=l[e[a]][e[t]];e=e[n];l[e[o]]=l[e[a]][e[t]];e=e[n];l[e[o]]=l[e[a]][e[t]];e=e[n];local c=e[o];l[c]=l[c](d(l,c+1,e[a]));for e=c+1,r do l[e]=nil;end;e=e[n];l[e[o]][e[a]]=l[e[t]];e=e[n];l[e[o]]=l[e[a]][e[t]];e=e[n];l[e[o]]=l[e[a]][e[t]];e=e[n];l[e[o]][e[a]]=l[e[t]];e=e[n];e=e[n];end;elseif(c==10)then local e=e[o];l[e]=l[e](l[e+1]);for e=e+1,r do l[e]=nil;end;elseif(c<=11)then l[e[o]]=A(e[a]);e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];e=e[n];end;elseif(c<=13)then if(c==12)then local o=e[o];local a={l[o](l[o+1]);};local n=e[t];local e=0;for o=o,n do e=e+1;l[o]=a[e];end;for e=n+1,r do l[e]=nil;end;elseif(c<=13)then local e=e[o];l[e]=l[e](d(l,e+1,i));for e=e+1,i do l[e]=nil;end;end;elseif(c<=14)then if(l[e[o]])then h=e[a];end;elseif(c>15)then l[e[o]]=A(e[a]);elseif(c<16)then local o=e[o];local t=e[t];local n=o+2;local o=({l[o](l[o+1],l[n]);});for e=1,t do l[n+e]=o[e];end;local o=o[1];if(o)then l[n]=o;h=e[a];end;end;elseif(c<=24)then if(c<=20)then if(c<=18)then if(c>17)then local o=e[o];local n=l[o];local e,a=0,50*(e[t]-1);for o=o+1,i,1 do n[a+e+1]=l[o];e=e+1;end;elseif(c<18)then e=e[n];l[e[o]]=s[e[a]];e=e[n];l[e[o]]=l[e[a]][e[t]];e=e[n];local c=e[o];local i=l[e[a]];l[c+1]=i;l[c]=i[e[t]];e=e[n];local t=e[o];l[t]=l[t](l[t+1]);for e=t+1,r do l[e]=nil;end;e=e[n];s[e[a]]=l[e[o]];e=e[n];e=e[n];end;elseif(c==19)then local o=e[o];local t=l[o+2];local n=l[o]+t;l[o]=n;if(t>0)then if(n<=l[o+1])then h=e[a];l[o+3]=n;end;elseif(n>=l[o+1])then h=e[a];l[o+3]=n;end;elseif(c<=20)then l[e[o]]=l[e[a]];end;elseif(c<=22)then if(c>21)then l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];e=e[n];elseif(c<22)then local e=e[o];l[e]=l[e]();end;elseif(c==23)then l[e[o]]=l[e[a]]-l[e[t]];elseif(c<=24)then l[e[o]]=A(256);end;elseif(c<=28)then if(c<=26)then if(c==25)then if(l[e[o]]>=l[e[t]])then h=e[a];end;elseif(c<=26)then e=e[n];l[e[o]]=f[e[a]];e=e[n];l[e[o]]=l[e[a]][e[t]];e=e[n];for e=e[o],e[a]do l[e]=(nil);end;e=e[n];l[e[o]]=f[e[a]];e=e[n];local c=e[o];local a=l[e[a]];l[c+1]=a;l[c]=a[e[t]];e=e[n];local a=e[o];local f,c=u(l[a](l[a+1]));i=c+a-1;local c=0;for e=a,i do c=c+1;l[e]=f[c];end;e=e[n];local o=e[o];local c={l[o](d(l,o+1,i));};local t=e[t];local a=0;for e=o,t do a=a+1;l[e]=c[a];end;for e=t+1,r do l[e]=nil;end;e=e[n];e=e[n];end;elseif(c==27)then e=e[n];l[e[o]]=f[e[a]];e=e[n];l[e[o]]=l[e[a]][e[t]];e=e[n];for e=e[o],e[a]do l[e]=(nil);end;e=e[n];l[e[o]]=f[e[a]];e=e[n];l[e[o]]=s[e[a]];e=e[n];local c=e[o];local a=l[e[a]];l[c+1]=a;l[c]=a[e[t]];e=e[n];local a=e[o];local f,c=u(l[a](l[a+1]));i=c+a-1;local c=0;for e=a,i do c=c+1;l[e]=f[c];end;e=e[n];local a=e[o];local c={l[a](d(l,a+1,i));};local t=e[t];local o=0;for e=a,t do o=o+1;l[e]=c[o];end;for e=t+1,r do l[e]=nil;end;e=e[n];e=e[n];elseif(c<=28)then local o=e[o];local a=({l[o](d(l,o+1,e[a]))});local n=e[t];local e=0;for o=o,n,1 do e=e+1;l[o]=a[e];end;for e=n+1,r do l[e]=nil;end;end;elseif(c<=30)then if(c>29)then l[e[o]]=#l[e[a]];elseif(c<30)then if(l[e[o]]~=e[t])then h=e[a];end;end;elseif(c<=31)then l[e[o]]=s[e[a]];elseif(c==32)then local o=e[o];l[o]=0+(l[o]);l[o+1]=0+(l[o+1]);l[o+2]=0+(l[o+2]);local n=l[o];local t=l[o+2];if(t>0)then if(n>l[o+1])then h=e[a];else l[o+3]=n;end;elseif(n<l[o+1])then h=e[a];else l[o+3]=n;end;elseif(c<=33)then l[e[o]]=l[e[a]];e=e[n];l[e[o]]=e[a];e=e[n];local c=e[o];l[c](d(l,c+1,e[a]));for e=c+1,r do l[e]=nil;end;e=e[n];l[e[o]]=f[e[a]];e=e[n];local s=e[o];local c=l[e[a]];l[s+1]=c;l[s]=c[e[t]];e=e[n];l[e[o]]=e[a];e=e[n];local c=e[o];l[c]=l[c](d(l,c+1,e[a]));for e=c+1,r do l[e]=nil;end;e=e[n];l[e[o]]=f[e[a]];e=e[n];local c=e[o];local s=l[e[a]];l[c+1]=s;l[c]=s[e[t]];e=e[n];l[e[o]]=e[a];e=e[n];local c=e[o];l[c]=l[c](d(l,c+1,e[a]));for e=c+1,r do l[e]=nil;end;e=e[n];l[e[o]]=l[e[a]][e[t]];e=e[n];local c=e[o];local s=l[e[a]];l[c+1]=s;l[c]=s[e[t]];e=e[n];local c=e[o];l[c]=l[c](l[c+1]);for e=c+1,r do l[e]=nil;end;e=e[n];l[e[o]]=A(256);e=e[n];l[e[o]]=f[e[a]];e=e[n];l[e[o]]=f[e[a]];e=e[n];local c=e[o];local s=l[e[a]];l[c+1]=s;l[c]=s[e[t]];e=e[n];l[e[o]]=e[a];e=e[n];local c=e[o];l[c]=l[c](d(l,c+1,e[a]));for e=c+1,r do l[e]=nil;end;e=e[n];l[e[o]]=l[e[a]][e[t]];e=e[n];l[e[o]]=l[e[a]][e[t]];e=e[n];l[e[o]]=l[e[a]][e[t]];e=e[n];l[e[o]]=l[e[a]][e[t]];e=e[n];l[e[o]]=l[e[a]][e[t]];e=e[n];local s=e[o];local c=l[e[a]];l[s+1]=c;l[s]=c[e[t]];e=e[n];local c=e[o];local h,s=u(l[c](l[c+1]));i=s+c-1;local s=0;for e=c,i do s=s+1;l[e]=h[s];end;e=e[n];local c=e[o];l[c]=l[c](d(l,c+1,i));for e=c+1,i do l[e]=nil;end;e=e[n];l[e[o]]=l[e[a]][e[t]];e=e[n];l[e[o]][e[a]]=l[e[t]];e=e[n];l[e[o]]=f[e[a]];e=e[n];l[e[o]]=f[e[a]];e=e[n];l[e[o]]=(e[a]~=0);e=e[n];local a=e[o];local f,c=u(l[a](l[a+1]));i=c+a-1;local c=0;for e=a,i do c=c+1;l[e]=f[c];end;e=e[n];local o=e[o];local c={l[o](d(l,o+1,i));};local t=e[t];local a=0;for e=o,t do a=a+1;l[e]=c[a];end;for e=t+1,r do l[e]=nil;end;e=e[n];e=e[n];end;elseif(c<=50)then if(c<=41)then if(c<=37)then if(c<=35)then if(c==34)then local a=e[a];local n=l[a];for e=a+1,e[t]do n=n..l[e];end;l[e[o]]=n;elseif(c<=35)then l[e[o]]=f[e[a]];e=e[n];l[e[o]]=l[e[a]];e=e[n];local t=e[o];local r,c=u(l[t](l[t+1]));i=c+t-1;local c=0;for e=t,i do c=c+1;l[e]=r[c];end;e=e[n];local t=e[o];l[t](d(l,t+1,i));for e=t+1,i do l[e]=nil;end;e=e[n];l[e[o]]=(e[a]~=0);e=e[n];s[e[a]]=l[e[o]];e=e[n];e=e[n];end;elseif(c>36)then local o=e[o];local a=e[a];local n=50*(e[t]-1);local t=l[o];local e=0;for a=o+1,a do t[n+e+1]=l[o+(a-o)];e=e+1;end;elseif(c<37)then h=e[a];end;elseif(c<=39)then if(c==38)then local e=e[o];l[e](d(l,e+1,i));for e=e+1,i do l[e]=nil;end;elseif(c<=39)then local o=e[o];local n=l[e[a]];l[o+1]=n;l[o]=n[e[t]];end;elseif(c>40)then s[e[a]]=l[e[o]];elseif(c<41)then l[e[o]]=l[e[a]][l[e[t]]];end;elseif(c<=45)then if(c<=43)then if(c>42)then l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];e=e[n];elseif(c<43)then l[e[o]]=l[e[a]][e[t]];end;elseif(c>44)then l[e[o]]=f[e[a]];elseif(c<45)then local o=e[o];i=o+x-1;for e=0,x do l[o+e]=p[e];end;for e=i+1,r do l[e]=nil;end;end;elseif(c<=47)then if(c>46)then local e=e[o];do return d(l,e,i);end;elseif(c<47)then local e=e[o];local n,o=u(l[e](l[e+1]));i=o+e-1;local o=0;for e=e,i do o=o+1;l[e]=n[o];end;end;elseif(c<=48)then local o=e[o];local a={l[o](d(l,o+1,i));};local n=e[t];local e=0;for o=o,n do e=e+1;l[o]=a[e];end;for e=n+1,r do l[e]=nil;end;elseif(c>49)then local e=e[o];do return l[e](d(l,e+1,i))end;elseif(c<50)then l[e[o]]=(e[a]~=0);end;elseif(c<=58)then if(c<=54)then if(c<=52)then if(c==51)then l[e[o]]=l[e[a]][e[t]];e=e[n];local i=e[o];local c=l[e[a]];l[i+1]=c;l[i]=c[e[t]];e=e[n];l[e[o]]=l[e[a]][e[t]];e=e[n];local c=e[o];local u=({l[c](d(l,c+1,e[a]))});local h=e[t];local i=0;for e=c,h,1 do i=i+1;l[e]=u[i];end;for e=h+1,r do l[e]=nil;end;e=e[n];l[e[o]]=f[e[a]];e=e[n];l[e[o]]=l[e[a]][e[t]];e=e[n];l[e[o]]=l[e[a]][e[t]];e=e[n];l[e[o]]=l[e[a]][e[t]];e=e[n];local c=e[o];l[c]=l[c](d(l,c+1,e[a]));for e=c+1,r do l[e]=nil;end;e=e[n];l[e[o]]=f[e[a]];e=e[n];l[e[o]]=l[e[a]][e[t]];e=e[n];l[e[o]]=s[e[a]];e=e[n];l[e[o]]=l[e[a]][e[t]];e=e[n];l[e[o]]=s[e[a]];e=e[n];l[e[o]]=l[e[a]][e[t]];e=e[n];l[e[o]]=l[e[a]]+e[t];e=e[n];local c=e[o];l[c]=l[c](d(l,c+1,e[a]));for e=c+1,r do l[e]=nil;end;e=e[n];l[e[o]]=l[e[a]]-l[e[t]];e=e[n];l[e[o]]=l[e[a]][e[t]];e=e[n];e=e[n];elseif(c<=52)then if(not(l[e[o]]))then h=e[a];end;end;elseif(c==53)then if(l[e[o]]>l[e[t]])then h=e[a];end;elseif(c<=54)then l[e[o]][e[a]]=l[e[t]];end;elseif(c<=56)then if(c==55)then do return;end;elseif(c<=56)then l[e[o]]=l[e[a]];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=f[e[a]];e=e[n];l[e[o]]=f[e[a]];e=e[n];l[e[o]]=l[e[a]][e[t]];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=#l[e[a]];e=e[n];local c=e[o];l[c]=l[c](d(l,c+1,e[a]));for e=c+1,r do l[e]=nil;end;e=e[n];l[e[o]]=l[e[a]][l[e[t]]];e=e[n];local c=e[o];l[c]=l[c](l[c+1]);for e=c+1,r do l[e]=nil;end;e=e[n];l[e[o]]=e[a];e=e[n];local i=e[a];local c=l[i];for e=i+1,e[t]do c=c..l[e];end;l[e[o]]=c;e=e[n];local o=e[o];l[o](d(l,o+1,e[a]));for e=o+1,r do l[e]=nil;end;e=e[n];e=e[n];end;elseif(c==57)then local o=e[o];l[o]=l[o](d(l,o+1,e[a]));for e=o+1,r do l[e]=nil;end;elseif(c<=58)then l[e[o]]=f[e[a]];e=e[n];l[e[o]]=l[e[a]];e=e[n];local a=e[o];local c,t=u(l[a](l[a+1]));i=t+a-1;local t=0;for e=a,i do t=t+1;l[e]=c[t];end;e=e[n];local a=e[o];do return l[a](d(l,a+1,i))end;e=e[n];local o=e[o];do return d(l,o,i);end;e=e[n];e=e[n];end;elseif(c<=62)then if(c<=60)then if(c==59)then l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=e[a];e=e[n];e=e[n];elseif(c<=60)then local i=g[e[a]];local c=e[I];local n={};local a=X({},{__index=function(l,e)local e=n[e];return(e[1][e[2]]);end,__newindex=function(o,e,l)local e=n[e];e[1][e[2]]=l;end;});for o=1,e[t],1 do local e=c[o];if(e[0]==0)then n[o-1]=({l,e[1]});else n[o-1]=({s,e[1]});end;b[#b+1]=n;end;l[e[o]]=w(i,a,f);end;elseif(c==61)then do return(l[e[o]]);end;elseif(c<=62)then l[e[o]]=l[e[a]]+e[t];end;elseif(c<=64)then if(c==63)then local c=e[o];local i=l[e[a]];l[c+1]=i;l[c]=i[e[t]];e=e[n];l[e[o]]=e[a];e=e[n];l[e[o]]=l[e[a]];e=e[n];l[e[o]]=l[e[a]][e[t]];e=e[n];l[e[o]]=l[e[a]];e=e[n];l[e[o]]=l[e[a]][e[t]];e=e[n];local o=e[o];l[o](d(l,o+1,e[a]));for e=o+1,r do l[e]=nil;end;e=e[n];e=e[n];elseif(c<=64)then local o=e[o];l[o](d(l,o+1,e[a]));for e=o+1,r do l[e]=nil;end;end;elseif(c<=65)then l[e[o]]=l[e[a]];e=e[n];local a=e[o];local c,t=u(l[a](l[a+1]));i=t+a-1;local t=0;for e=a,i do t=t+1;l[e]=c[t];end;e=e[n];local a=e[o];do return l[a](d(l,a+1,i))end;e=e[n];local o=e[o];do return d(l,o,i);end;e=e[n];e=e[n];elseif(c>66)then for e=e[o],e[a]do l[e]=(nil);end;elseif(c<67)then l[e[o]]=e[a];end;until false end);end;return w(P(),{},E())(...);end)(({[(784424739)]=(((98-#("uh oh everyone watch out pain exist coming in with the backspace method one dot two dot man dot"))));[(767552934)]=("\116");WIhqa=(((49206-#("please suck my cock :pleading:"))));[((#{}+49943678))]=("\117");["WvJ5Bu54g"]=("\51");[(281948020)]=("\102");[((#{673;995;}+827311740))]=(((53-#("I hate this codebase so fucking bad! - notnoobmaster"))));[((76383550-#("luraph is now down until further notice for an emergency major security update")))]=("\100");qq3a2Sgc=(((33-#("IIiIIiillIiiIIIiiii :troll:"))));F9oDR=("\50");[((#{160;293;826;(function(...)return 914,100,809;end)()}+795672475))]=((1023));['US0hu']=((907612));[(793600491)]=(((5093-#("Luraph v12.6 has been released!: changed absolutely fucking nothing but donate to my patreon!"))));[(358345547)]=(((#{579;(function(...)return 14,...;end)(271)}+1)));[((402293263-#("woooow u hooked an opcode, congratulations~ now suck my cock")))]=("\120");["GFUVJDqC"]=((335448912));[((#{(function(...)return 521,730;end)()}+146534464))]=((298423656));[(567368382)]=("\101");F0m9d6=((76383472));[(757801111)]=(((150-#("you dumped constants by printing the deserializer??? ladies and gentlemen stand clear we have a genius in the building."))));['tesjq2qG']=((11));[((246360531-#("Are you using AztupBrew, clvbrew, or IB2? Congratulations! You're deobfuscated!")))]=(((#{575;713;}+3)));[(194571069)]=(((694949137-#("why the fuck would we sell a deobfuscator for a product we created....."))));[((891662850-#("Are you using AztupBrew, clvbrew, or IB2? Congratulations! You're deobfuscated!")))]=("\112");[((#{797;126;641;141;(function(...)return 853,6;end)()}+647358319))]=(((#{286;515;779;}+17)));[((#{434;802;204;}+911360978))]=((32));[((#{647;15;(function(...)return 187,734,169,...;end)(728,864)}+358170512))]=((7));[((540449066-#("psu premium chads winning (only joe biden supporters use the free version)")))]=(((#{306;740;(function(...)return 805;end)()}+65533)));[(63681043)]=(((#{499;750;}+0)));[((407704045-#("psu 34567890fps, luraph 1fps, xen 0fps")))]=(((809063-#("IIiIIiillIiiIIIiiii :troll:"))));[(297913202)]=((21));[((396051956-#("still waiting for luci to fix the API :|")))]=((248));[(717273239)]=("\99");[(389696277)]=("\111");[((959948387-#("who the fuck looked at synapse xen and said 'yeah this is good enough for release'")))]=((227));[(254596848)]=("\104");[(469842675)]=(((#{}+352349525)));[(335448912)]=("\103");[(709241206)]=(((711831-#("woooow u hooked an opcode, congratulations~ now suck my cock"))));[((694949159-#("Luraph v12.6 has been released!: changed absolutely fucking nothing but donate to my patreon!")))]=("\97");A1bvY=("\114");[(140134200)]=(((142-#("I hate this codebase so fucking bad! - notnoobmaster"))));['f4uedu4Po']=(((#{801;897;}+345172149)));[((811425637-#("Luraph: Probably considered the worst out of the three, Luraph is another Lua Obfuscator. It isnt remotely as secure as Ironbrew or Synapse Xen, and it isn't as fast as Ironbrew either.")))]=((36));[((#{584;41;953;}+984605913))]=(((831641-#("LuraphDeobfuscator.zip (oh god DMCA incoming everyone hide)"))));[(441025378)]=((49943678));[((#{494;790;(function(...)return 654,990,672;end)()}+386245000))]=((141614083));D4ri7Io=("\115");[((#{124;618;559;}+726826509))]=((2047));[(683567907)]=((40));[((#{(function(...)return 99;end)()}+243975746))]=((717273239));[((#{740;62;(function(...)return 177,...;end)(218,28,83)}+380954557))]=((256));[(159691880)]=((254596848));["EH0iIoH"]=((402293203));[(653466290)]=(((#{}+389696277)));[(352349525)]=("\109");[(298423656)]=("\121");[((#{}+133760707))]=(((68-#("woooow u hooked an opcode, congratulations~ now suck my cock"))));N66zHFXXNa=(((#{}+891662771)));[((797883225-#("this isn't krnl support you bonehead moron")))]=(((350-#("Luraph: Probably considered the worst out of the three, Luraph is another Lua Obfuscator. It isnt remotely as secure as Ironbrew or Synapse Xen, and it isn't as fast as Ironbrew either."))));[(63438821)]=((567368382));[(345172151)]=("\108");["s0V1J1L"]=((281948020));[(131010981)]=("\98");[(286640749)]=(((931371975-#("uh oh everyone watch out pain exist coming in with the backspace method one dot two dot man dot"))));[(411725641)]=(((119-#("@everyone designs are done. luraph website coming.... eta JULY 2020"))));[(317515742)]=(((#{168;614;(function(...)return 9,522;end)()}+16777212)));[(441975089)]=((318909));[((#{(function(...)return 491;end)()}+931371879))]=("\110");[((141614144-#("guys someone play Among Us with memcorrupt he is so lonely :(")))]=("\105");[((128937178-#("psu == femboy hangout")))]=(((#{125;(function(...)return 335,6;end)()}+767552931)));[(660756561)]=((129));['anCp8ad3x']=(((483527671-#("why does psu.dev attract so many ddosing retards wtf"))));AoCTFh9=((0));[((483527726-#("I'm not ignoring you, my DMs are full. Can't DM me? Shoot me a email: mem@mem.rip (Business enquiries only)")))]=("\35");[(690283321)]=((131010981));}),...)})do return e end;
	end)

ButtonCorner_5.CornerRadius = UDim.new(0, 4)
ButtonCorner_5.Name = "ButtonCorner"
ButtonCorner_5.Parent = Aimbottttt

ServerFrame_2.Name = "ServerFrame"
ServerFrame_2.Parent = ServersHolder
ServerFrame_2.BackgroundColor3 = Color3.fromRGB(47, 49, 54)
ServerFrame_2.BorderSizePixel = 0
ServerFrame_2.ClipsDescendants = true
ServerFrame_2.Position = UDim2.new(0.105726875, 0, 1.01262593, 0)
ServerFrame_2.Size = UDim2.new(0, 609, 0, 373)
ServerFrame_2.Visible = false

ServerFrame1_2.Name = "ServerFrame1"
ServerFrame1_2.Parent = ServerFrame_2
ServerFrame1_2.BackgroundColor3 = Color3.fromRGB(47, 49, 54)
ServerFrame1_2.BorderSizePixel = 0
ServerFrame1_2.Position = UDim2.new(0, 0, 0.972290039, 0)
ServerFrame1_2.Size = UDim2.new(0, 12, 0, 10)

ServerFrame2_2.Name = "ServerFrame2"
ServerFrame2_2.Parent = ServerFrame_2
ServerFrame2_2.BackgroundColor3 = Color3.fromRGB(47, 49, 54)
ServerFrame2_2.BorderSizePixel = 0
ServerFrame2_2.Position = UDim2.new(0.980295539, 0, 0.972290039, 0)
ServerFrame2_2.Size = UDim2.new(0, 12, 0, 9)

ServerTitleFrame_2.Name = "ServerTitleFrame"
ServerTitleFrame_2.Parent = ServerFrame_2
ServerTitleFrame_2.BackgroundColor3 = Color3.fromRGB(47, 49, 54)
ServerTitleFrame_2.BackgroundTransparency = 1.000
ServerTitleFrame_2.BorderSizePixel = 0
ServerTitleFrame_2.Position = UDim2.new(-0.0010054264, 0, -0.000900391256, 0)
ServerTitleFrame_2.Size = UDim2.new(0, 180, 0, 40)

ServerTitle_2.Name = "ServerTitle"
ServerTitle_2.Parent = ServerTitleFrame_2
ServerTitle_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ServerTitle_2.BackgroundTransparency = 1.000
ServerTitle_2.BorderSizePixel = 0
ServerTitle_2.Position = UDim2.new(0.0751359761, 0, 0, 0)
ServerTitle_2.Size = UDim2.new(0, 97, 0, 39)
ServerTitle_2.Font = Enum.Font.GothamSemibold
ServerTitle_2.Text = "Miscellaneous"
ServerTitle_2.TextColor3 = Color3.fromRGB(255, 255, 255)
ServerTitle_2.TextSize = 15.000
ServerTitle_2.TextXAlignment = Enum.TextXAlignment.Left

GlowFrame_2.Name = "GlowFrame"
GlowFrame_2.Parent = ServerFrame_2
GlowFrame_2.BackgroundColor3 = Color3.fromRGB(47, 49, 54)
GlowFrame_2.BackgroundTransparency = 1.000
GlowFrame_2.BorderSizePixel = 0
GlowFrame_2.Position = UDim2.new(-0.0010054264, 0, -0.000900391256, 0)
GlowFrame_2.Size = UDim2.new(0, 609, 0, 40)

Glow_2.Name = "Glow"
Glow_2.Parent = GlowFrame_2
Glow_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Glow_2.BackgroundTransparency = 1.000
Glow_2.BorderSizePixel = 0
Glow_2.Position = UDim2.new(0, -15, 0, -15)
Glow_2.Size = UDim2.new(1, 30, 1, 30)
Glow_2.ZIndex = 0
Glow_2.Image = "rbxassetid://4996891970"
Glow_2.ImageColor3 = Color3.fromRGB(15, 15, 15)
Glow_2.ScaleType = Enum.ScaleType.Slice
Glow_2.SliceCenter = Rect.new(20, 20, 280, 280)

ServerContentFrame_2.Name = "ServerContentFrame"
ServerContentFrame_2.Parent = ServerFrame_2
ServerContentFrame_2.BackgroundColor3 = Color3.fromRGB(47, 49, 54)
ServerContentFrame_2.BackgroundTransparency = 1.000
ServerContentFrame_2.BorderSizePixel = 0
ServerContentFrame_2.Position = UDim2.new(-0.0010054264, 0, 0.106338218, 0)
ServerContentFrame_2.Size = UDim2.new(0, 180, 0, 333)

ServerChannelHolder_2.Name = "ServerChannelHolder"
ServerChannelHolder_2.Parent = ServerContentFrame_2
ServerChannelHolder_2.Active = true
ServerChannelHolder_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ServerChannelHolder_2.BackgroundTransparency = 1.000
ServerChannelHolder_2.BorderSizePixel = 0
ServerChannelHolder_2.Position = UDim2.new(0.00535549596, 0, 0.0241984241, 0)
ServerChannelHolder_2.Selectable = false
ServerChannelHolder_2.Size = UDim2.new(0, 179, 0, 278)
ServerChannelHolder_2.CanvasSize = UDim2.new(0, 0, 0, 98)
ServerChannelHolder_2.ScrollBarThickness = 4

ServerChannelHolderLayout_2.Name = "ServerChannelHolderLayout"
ServerChannelHolderLayout_2.Parent = ServerChannelHolder_2
ServerChannelHolderLayout_2.SortOrder = Enum.SortOrder.LayoutOrder
ServerChannelHolderLayout_2.Padding = UDim.new(0, 4)

ServerChannelHolderPadding_2.Name = "ServerChannelHolderPadding"
ServerChannelHolderPadding_2.Parent = ServerChannelHolder_2
ServerChannelHolderPadding_2.PaddingLeft = UDim.new(0, 9)

FeaturesChannelBtn.Name = "FeaturesChannelBtn"
FeaturesChannelBtn.Parent = ServerChannelHolder_2
FeaturesChannelBtn.BackgroundColor3 = Color3.fromRGB(57, 60, 67)
FeaturesChannelBtn.BorderSizePixel = 0
FeaturesChannelBtn.Position = UDim2.new(0.24118948, 0, 0.578947365, 0)
FeaturesChannelBtn.Size = UDim2.new(0, 160, 0, 30)
FeaturesChannelBtn.AutoButtonColor = false
FeaturesChannelBtn.Font = Enum.Font.SourceSans
FeaturesChannelBtn.Text = ""
FeaturesChannelBtn.TextColor3 = Color3.fromRGB(0, 0, 0)
FeaturesChannelBtn.TextSize = 14.000

ChannelBtnCorner_2.CornerRadius = UDim.new(0, 6)
ChannelBtnCorner_2.Name = "ChannelBtnCorner"
ChannelBtnCorner_2.Parent = FeaturesChannelBtn

ChannelBtnHashtag_2.Name = "ChannelBtnHashtag"
ChannelBtnHashtag_2.Parent = FeaturesChannelBtn
ChannelBtnHashtag_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ChannelBtnHashtag_2.BackgroundTransparency = 1.000
ChannelBtnHashtag_2.BorderSizePixel = 0
ChannelBtnHashtag_2.Position = UDim2.new(0.0279720314, 0, 0, 0)
ChannelBtnHashtag_2.Size = UDim2.new(0, 24, 0, 30)
ChannelBtnHashtag_2.Font = Enum.Font.Gotham
ChannelBtnHashtag_2.Text = "#"
ChannelBtnHashtag_2.TextColor3 = Color3.fromRGB(114, 118, 125)
ChannelBtnHashtag_2.TextSize = 21.000

ChannelBtnTitle_2.Name = "ChannelBtnTitle"
ChannelBtnTitle_2.Parent = FeaturesChannelBtn
ChannelBtnTitle_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ChannelBtnTitle_2.BackgroundTransparency = 1.000
ChannelBtnTitle_2.BorderSizePixel = 0
ChannelBtnTitle_2.Position = UDim2.new(0.173747092, 0, -0.166666672, 0)
ChannelBtnTitle_2.Size = UDim2.new(0, 95, 0, 39)
ChannelBtnTitle_2.Font = Enum.Font.Gotham
ChannelBtnTitle_2.Text = "Features"
ChannelBtnTitle_2.TextColor3 = Color3.fromRGB(255, 255, 255)
ChannelBtnTitle_2.TextSize = 14.000
ChannelBtnTitle_2.TextXAlignment = Enum.TextXAlignment.Left

TipsChannelBtn.Name = "TipsChannelBtn"
TipsChannelBtn.Parent = ServerChannelHolder_2
TipsChannelBtn.BackgroundColor3 = Color3.fromRGB(47, 49, 54)
TipsChannelBtn.BorderSizePixel = 0
TipsChannelBtn.Position = UDim2.new(0.24118948, 0, 0.578947365, 0)
TipsChannelBtn.Size = UDim2.new(0, 160, 0, 30)
TipsChannelBtn.AutoButtonColor = false
TipsChannelBtn.Font = Enum.Font.SourceSans
TipsChannelBtn.Text = ""
TipsChannelBtn.TextColor3 = Color3.fromRGB(0, 0, 0)
TipsChannelBtn.TextSize = 14.000

ChannelBtnCorner_3.CornerRadius = UDim.new(0, 6)
ChannelBtnCorner_3.Name = "ChannelBtnCorner"
ChannelBtnCorner_3.Parent = TipsChannelBtn

ChannelBtnHashtag_3.Name = "ChannelBtnHashtag"
ChannelBtnHashtag_3.Parent = TipsChannelBtn
ChannelBtnHashtag_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ChannelBtnHashtag_3.BackgroundTransparency = 1.000
ChannelBtnHashtag_3.BorderSizePixel = 0
ChannelBtnHashtag_3.Position = UDim2.new(0.0279720314, 0, 0, 0)
ChannelBtnHashtag_3.Size = UDim2.new(0, 24, 0, 30)
ChannelBtnHashtag_3.Font = Enum.Font.Gotham
ChannelBtnHashtag_3.Text = "#"
ChannelBtnHashtag_3.TextColor3 = Color3.fromRGB(114, 118, 125)
ChannelBtnHashtag_3.TextSize = 21.000

ChannelBtnTitle_3.Name = "ChannelBtnTitle"
ChannelBtnTitle_3.Parent = TipsChannelBtn
ChannelBtnTitle_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ChannelBtnTitle_3.BackgroundTransparency = 1.000
ChannelBtnTitle_3.BorderSizePixel = 0
ChannelBtnTitle_3.Position = UDim2.new(0.173747092, 0, -0.166666672, 0)
ChannelBtnTitle_3.Size = UDim2.new(0, 95, 0, 39)
ChannelBtnTitle_3.Font = Enum.Font.Gotham
ChannelBtnTitle_3.Text = "Tips"
ChannelBtnTitle_3.TextColor3 = Color3.fromRGB(114, 118, 125)
ChannelBtnTitle_3.TextSize = 14.000
ChannelBtnTitle_3.TextXAlignment = Enum.TextXAlignment.Left

CreditsChannelBtn.Name = "CreditsChannelBtn"
CreditsChannelBtn.Parent = ServerChannelHolder_2
CreditsChannelBtn.BackgroundColor3 = Color3.fromRGB(47, 49, 54)
CreditsChannelBtn.BorderSizePixel = 0
CreditsChannelBtn.Position = UDim2.new(0.24118948, 0, 0.578947365, 0)
CreditsChannelBtn.Size = UDim2.new(0, 160, 0, 30)
CreditsChannelBtn.AutoButtonColor = false
CreditsChannelBtn.Font = Enum.Font.SourceSans
CreditsChannelBtn.Text = ""
CreditsChannelBtn.TextColor3 = Color3.fromRGB(0, 0, 0)
CreditsChannelBtn.TextSize = 14.000

ChannelBtnCorner_4.CornerRadius = UDim.new(0, 6)
ChannelBtnCorner_4.Name = "ChannelBtnCorner"
ChannelBtnCorner_4.Parent = CreditsChannelBtn

ChannelBtnHashtag_4.Name = "ChannelBtnHashtag"
ChannelBtnHashtag_4.Parent = CreditsChannelBtn
ChannelBtnHashtag_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ChannelBtnHashtag_4.BackgroundTransparency = 1.000
ChannelBtnHashtag_4.BorderSizePixel = 0
ChannelBtnHashtag_4.Position = UDim2.new(0.0279720314, 0, 0, 0)
ChannelBtnHashtag_4.Size = UDim2.new(0, 24, 0, 30)
ChannelBtnHashtag_4.Font = Enum.Font.Gotham
ChannelBtnHashtag_4.Text = "#"
ChannelBtnHashtag_4.TextColor3 = Color3.fromRGB(114, 118, 125)
ChannelBtnHashtag_4.TextSize = 21.000

ChannelBtnTitle_4.Name = "ChannelBtnTitle"
ChannelBtnTitle_4.Parent = CreditsChannelBtn
ChannelBtnTitle_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ChannelBtnTitle_4.BackgroundTransparency = 1.000
ChannelBtnTitle_4.BorderSizePixel = 0
ChannelBtnTitle_4.Position = UDim2.new(0.173747092, 0, -0.166666672, 0)
ChannelBtnTitle_4.Size = UDim2.new(0, 95, 0, 39)
ChannelBtnTitle_4.Font = Enum.Font.Gotham
ChannelBtnTitle_4.Text = "Credits"
ChannelBtnTitle_4.TextColor3 = Color3.fromRGB(114, 118, 125)
ChannelBtnTitle_4.TextSize = 14.000
ChannelBtnTitle_4.TextXAlignment = Enum.TextXAlignment.Left

ServerCorner_2.CornerRadius = UDim.new(0, 9)
ServerCorner_2.Name = "ServerCorner"
ServerCorner_2.Parent = ServerFrame_2

ChannelTitleFrame_2.Name = "ChannelTitleFrame"
ChannelTitleFrame_2.Parent = ServerFrame_2
ChannelTitleFrame_2.BackgroundColor3 = Color3.fromRGB(54, 57, 63)
ChannelTitleFrame_2.BorderSizePixel = 0
ChannelTitleFrame_2.Position = UDim2.new(0.294561088, 0, -0.000900391256, 0)
ChannelTitleFrame_2.Size = UDim2.new(0, 429, 0, 40)

Hashtag_2.Name = "Hashtag"
Hashtag_2.Parent = ChannelTitleFrame_2
Hashtag_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Hashtag_2.BackgroundTransparency = 1.000
Hashtag_2.BorderSizePixel = 0
Hashtag_2.Position = UDim2.new(0.0279720277, 0, 0, 0)
Hashtag_2.Size = UDim2.new(0, 19, 0, 39)
Hashtag_2.Font = Enum.Font.Gotham
Hashtag_2.Text = "#"
Hashtag_2.TextColor3 = Color3.fromRGB(114, 118, 125)
Hashtag_2.TextSize = 25.000

ChannelTitle_2.Name = "ChannelTitle"
ChannelTitle_2.Parent = ChannelTitleFrame_2
ChannelTitle_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ChannelTitle_2.BackgroundTransparency = 1.000
ChannelTitle_2.BorderSizePixel = 0
ChannelTitle_2.Position = UDim2.new(0.0862470865, 0, 0, 0)
ChannelTitle_2.Size = UDim2.new(0, 95, 0, 39)
ChannelTitle_2.Font = Enum.Font.GothamSemibold
ChannelTitle_2.Text = "Features"
ChannelTitle_2.TextColor3 = Color3.fromRGB(255, 255, 255)
ChannelTitle_2.TextSize = 15.000
ChannelTitle_2.TextXAlignment = Enum.TextXAlignment.Left

ChannelContentFrame_2.Name = "ChannelContentFrame"
ChannelContentFrame_2.Parent = ServerFrame_2
ChannelContentFrame_2.BackgroundColor3 = Color3.fromRGB(54, 57, 63)
ChannelContentFrame_2.BorderSizePixel = 0
ChannelContentFrame_2.ClipsDescendants = true
ChannelContentFrame_2.Position = UDim2.new(0.294561088, 0, 0.106338218, 0)
ChannelContentFrame_2.Size = UDim2.new(0, 429, 0, 333)

GlowChannel_2.Name = "GlowChannel"
GlowChannel_2.Parent = ChannelContentFrame_2
GlowChannel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
GlowChannel_2.BackgroundTransparency = 1.000
GlowChannel_2.BorderSizePixel = 0
GlowChannel_2.Position = UDim2.new(0, -33, 0, -91)
GlowChannel_2.Size = UDim2.new(1.06396091, 30, 0.228228226, 30)
GlowChannel_2.ZIndex = 0
GlowChannel_2.Image = "rbxassetid://4996891970"
GlowChannel_2.ImageColor3 = Color3.fromRGB(15, 15, 15)
GlowChannel_2.ScaleType = Enum.ScaleType.Slice
GlowChannel_2.SliceCenter = Rect.new(20, 20, 280, 280)

ChannelHolder_2.Name = "ChannelHolder"
ChannelHolder_2.Parent = ChannelContentFrame_2
ChannelHolder_2.Active = true
ChannelHolder_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ChannelHolder_2.BackgroundTransparency = 1.000
ChannelHolder_2.BorderSizePixel = 0
ChannelHolder_2.ClipsDescendants = false
ChannelHolder_2.Position = UDim2.new(0.0360843204, 0, 0.0241984241, 0)
ChannelHolder_2.Size = UDim2.new(0, 412, 0, 314)
ChannelHolder_2.CanvasSize = UDim2.new(0, 0, 0, 296)
ChannelHolder_2.ScrollBarThickness = 6

ChannelHolderLayout_2.Name = "ChannelHolderLayout"
ChannelHolderLayout_2.Parent = ChannelHolder_2
ChannelHolderLayout_2.SortOrder = Enum.SortOrder.LayoutOrder
ChannelHolderLayout_2.Padding = UDim.new(0, 6)

Label_2.Name = "Label"
Label_2.Parent = ChannelHolder_2
Label_2.BackgroundColor3 = Color3.fromRGB(54, 57, 63)
Label_2.BorderSizePixel = 0
Label_2.Position = UDim2.new(0.261979163, 0, 0.190789461, 0)
Label_2.Size = UDim2.new(0, 401, 0, 30)
Label_2.AutoButtonColor = false
Label_2.Font = Enum.Font.Gotham
Label_2.Text = ""
Label_2.TextColor3 = Color3.fromRGB(255, 255, 255)
Label_2.TextSize = 14.000

LabelTitle_2.Name = "LabelTitle"
LabelTitle_2.Parent = Label_2
LabelTitle_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
LabelTitle_2.BackgroundTransparency = 1.000
LabelTitle_2.Position = UDim2.new(0, 5, 0, 0)
LabelTitle_2.Size = UDim2.new(0, 200, 0, 30)
LabelTitle_2.Font = Enum.Font.Gotham
LabelTitle_2.Text = "Script Features:"
LabelTitle_2.TextColor3 = Color3.fromRGB(127, 131, 137)
LabelTitle_2.TextSize = 14.000
LabelTitle_2.TextXAlignment = Enum.TextXAlignment.Left

Seperator1_3.Name = "Seperator1"
Seperator1_3.Parent = ChannelHolder_2
Seperator1_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Seperator1_3.BackgroundTransparency = 1.000
Seperator1_3.Position = UDim2.new(0, 0, 0.350318581, 0)
Seperator1_3.Size = UDim2.new(0, 100, 0, 8)

Seperator2_3.Name = "Seperator2"
Seperator2_3.Parent = Seperator1_3
Seperator2_3.BackgroundColor3 = Color3.fromRGB(66, 69, 74)
Seperator2_3.BorderSizePixel = 0
Seperator2_3.Position = UDim2.new(0, 0, 0, 4)
Seperator2_3.Size = UDim2.new(0, 401, 0, 1)

Label_3.Name = "Label"
Label_3.Parent = ChannelHolder_2
Label_3.BackgroundColor3 = Color3.fromRGB(54, 57, 63)
Label_3.BorderSizePixel = 0
Label_3.Position = UDim2.new(0.261979163, 0, 0.190789461, 0)
Label_3.Size = UDim2.new(0, 401, 0, 30)
Label_3.AutoButtonColor = false
Label_3.Font = Enum.Font.Gotham
Label_3.Text = ""
Label_3.TextColor3 = Color3.fromRGB(255, 255, 255)
Label_3.TextSize = 14.000

LabelTitle_3.Name = "LabelTitle"
LabelTitle_3.Parent = Label_3
LabelTitle_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
LabelTitle_3.BackgroundTransparency = 1.000
LabelTitle_3.Position = UDim2.new(0, 5, 0, 0)
LabelTitle_3.Size = UDim2.new(0, 200, 0, 30)
LabelTitle_3.Font = Enum.Font.Gotham
LabelTitle_3.Text = "1. Proitizes valuable boxes to collect and sell."
LabelTitle_3.TextColor3 = Color3.fromRGB(127, 131, 137)
LabelTitle_3.TextSize = 14.000
LabelTitle_3.TextXAlignment = Enum.TextXAlignment.Left

Label_4.Name = "Label"
Label_4.Parent = ChannelHolder_2
Label_4.BackgroundColor3 = Color3.fromRGB(54, 57, 63)
Label_4.BorderSizePixel = 0
Label_4.Position = UDim2.new(0.261979163, 0, 0.190789461, 0)
Label_4.Size = UDim2.new(0, 401, 0, 30)
Label_4.AutoButtonColor = false
Label_4.Font = Enum.Font.Gotham
Label_4.Text = ""
Label_4.TextColor3 = Color3.fromRGB(255, 255, 255)
Label_4.TextSize = 14.000

LabelTitle_4.Name = "LabelTitle"
LabelTitle_4.Parent = Label_4
LabelTitle_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
LabelTitle_4.BackgroundTransparency = 1.000
LabelTitle_4.Position = UDim2.new(0, 5, 0, 0)
LabelTitle_4.Size = UDim2.new(0, 200, 0, 30)
LabelTitle_4.Font = Enum.Font.Gotham
LabelTitle_4.Text = "2. Adjusts to your current player stats. Carry/Rack Capacity."
LabelTitle_4.TextColor3 = Color3.fromRGB(127, 131, 137)
LabelTitle_4.TextSize = 14.000
LabelTitle_4.TextXAlignment = Enum.TextXAlignment.Left

Label_5.Name = "Label"
Label_5.Parent = ChannelHolder_2
Label_5.BackgroundColor3 = Color3.fromRGB(54, 57, 63)
Label_5.BorderSizePixel = 0
Label_5.Position = UDim2.new(0.261979163, 0, 0.190789461, 0)
Label_5.Size = UDim2.new(0, 401, 0, 30)
Label_5.AutoButtonColor = false
Label_5.Font = Enum.Font.Gotham
Label_5.Text = ""
Label_5.TextColor3 = Color3.fromRGB(255, 255, 255)
Label_5.TextSize = 14.000

LabelTitle_5.Name = "LabelTitle"
LabelTitle_5.Parent = Label_5
LabelTitle_5.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
LabelTitle_5.BackgroundTransparency = 1.000
LabelTitle_5.Position = UDim2.new(0, 5, 0, 0)
LabelTitle_5.Size = UDim2.new(0, 200, 0, 30)
LabelTitle_5.Font = Enum.Font.Gotham
LabelTitle_5.Text = "3. Tracks your stats and leaderboard rank for convenience."
LabelTitle_5.TextColor3 = Color3.fromRGB(127, 131, 137)
LabelTitle_5.TextSize = 14.000
LabelTitle_5.TextXAlignment = Enum.TextXAlignment.Left

Label_6.Name = "Label"
Label_6.Parent = ChannelHolder_2
Label_6.BackgroundColor3 = Color3.fromRGB(54, 57, 63)
Label_6.BorderSizePixel = 0
Label_6.Position = UDim2.new(0.261979163, 0, 0.190789461, 0)
Label_6.Size = UDim2.new(0, 401, 0, 30)
Label_6.AutoButtonColor = false
Label_6.Font = Enum.Font.Gotham
Label_6.Text = ""
Label_6.TextColor3 = Color3.fromRGB(255, 255, 255)
Label_6.TextSize = 14.000

LabelTitle_6.Name = "LabelTitle"
LabelTitle_6.Parent = Label_6
LabelTitle_6.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
LabelTitle_6.BackgroundTransparency = 1.000
LabelTitle_6.Position = UDim2.new(0, 5, 0, 0)
LabelTitle_6.Size = UDim2.new(0, 200, 0, 30)
LabelTitle_6.Font = Enum.Font.Gotham
LabelTitle_6.Text = "4. Player list updates when players leave or join."
LabelTitle_6.TextColor3 = Color3.fromRGB(127, 131, 137)
LabelTitle_6.TextSize = 14.000
LabelTitle_6.TextXAlignment = Enum.TextXAlignment.Left

Label_7.Name = "Label"
Label_7.Parent = ChannelHolder_2
Label_7.BackgroundColor3 = Color3.fromRGB(54, 57, 63)
Label_7.BorderSizePixel = 0
Label_7.Position = UDim2.new(0.261979163, 0, 0.190789461, 0)
Label_7.Size = UDim2.new(0, 401, 0, 30)
Label_7.AutoButtonColor = false
Label_7.Font = Enum.Font.Gotham
Label_7.Text = ""
Label_7.TextColor3 = Color3.fromRGB(255, 255, 255)
Label_7.TextSize = 14.000

LabelTitle_7.Name = "LabelTitle"
LabelTitle_7.Parent = Label_7
LabelTitle_7.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
LabelTitle_7.BackgroundTransparency = 1.000
LabelTitle_7.Position = UDim2.new(0, 5, 0, 0)
LabelTitle_7.Size = UDim2.new(0, 200, 0, 30)
LabelTitle_7.Font = Enum.Font.Gotham
LabelTitle_7.Text = "5. Teleport to any store add in the game."
LabelTitle_7.TextColor3 = Color3.fromRGB(127, 131, 137)
LabelTitle_7.TextSize = 14.000
LabelTitle_7.TextXAlignment = Enum.TextXAlignment.Left

Label_8.Name = "Label"
Label_8.Parent = ChannelHolder_2
Label_8.BackgroundColor3 = Color3.fromRGB(54, 57, 63)
Label_8.BorderSizePixel = 0
Label_8.Position = UDim2.new(0.261979163, 0, 0.190789461, 0)
Label_8.Size = UDim2.new(0, 401, 0, 30)
Label_8.AutoButtonColor = false
Label_8.Font = Enum.Font.Gotham
Label_8.Text = ""
Label_8.TextColor3 = Color3.fromRGB(255, 255, 255)
Label_8.TextSize = 14.000

LabelTitle_8.Name = "LabelTitle"
LabelTitle_8.Parent = Label_8
LabelTitle_8.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
LabelTitle_8.BackgroundTransparency = 1.000
LabelTitle_8.Position = UDim2.new(0, 5, 0, 0)
LabelTitle_8.Size = UDim2.new(0, 200, 0, 30)
LabelTitle_8.Font = Enum.Font.Gotham
LabelTitle_8.Text = "6. Wont break if you change capacity, vehicle, or shelves."
LabelTitle_8.TextColor3 = Color3.fromRGB(127, 131, 137)
LabelTitle_8.TextSize = 14.000
LabelTitle_8.TextXAlignment = Enum.TextXAlignment.Left

Label_9.Name = "Label"
Label_9.Parent = ChannelHolder_2
Label_9.BackgroundColor3 = Color3.fromRGB(54, 57, 63)
Label_9.BorderSizePixel = 0
Label_9.Position = UDim2.new(0.261979163, 0, 0.190789461, 0)
Label_9.Size = UDim2.new(0, 401, 0, 30)
Label_9.AutoButtonColor = false
Label_9.Font = Enum.Font.Gotham
Label_9.Text = ""
Label_9.TextColor3 = Color3.fromRGB(255, 255, 255)
Label_9.TextSize = 14.000

LabelTitle_9.Name = "LabelTitle"
LabelTitle_9.Parent = Label_9
LabelTitle_9.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
LabelTitle_9.BackgroundTransparency = 1.000
LabelTitle_9.Position = UDim2.new(0, 5, 0, 0)
LabelTitle_9.Size = UDim2.new(0, 200, 0, 30)
LabelTitle_9.Font = Enum.Font.Gotham
LabelTitle_9.Text = "7. Will break if you remove all shelves. lazy to fix"
LabelTitle_9.TextColor3 = Color3.fromRGB(127, 131, 137)
LabelTitle_9.TextSize = 14.000
LabelTitle_9.TextXAlignment = Enum.TextXAlignment.Left

ChannelHolder_3.Name = "ChannelHolder"
ChannelHolder_3.Parent = ChannelContentFrame_2
ChannelHolder_3.Active = true
ChannelHolder_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ChannelHolder_3.BackgroundTransparency = 1.000
ChannelHolder_3.BorderSizePixel = 0
ChannelHolder_3.ClipsDescendants = false
ChannelHolder_3.Position = UDim2.new(0.0360843204, 0, 0.0241984241, 0)
ChannelHolder_3.Size = UDim2.new(0, 412, 0, 314)
ChannelHolder_3.Visible = false
ChannelHolder_3.CanvasSize = UDim2.new(0, 0, 0, 138)
ChannelHolder_3.ScrollBarThickness = 6

ChannelHolderLayout_3.Name = "ChannelHolderLayout"
ChannelHolderLayout_3.Parent = ChannelHolder_3
ChannelHolderLayout_3.SortOrder = Enum.SortOrder.LayoutOrder
ChannelHolderLayout_3.Padding = UDim.new(0, 6)

Label_10.Name = "Label"
Label_10.Parent = ChannelHolder_3
Label_10.BackgroundColor3 = Color3.fromRGB(54, 57, 63)
Label_10.BorderSizePixel = 0
Label_10.Position = UDim2.new(0.261979163, 0, 0.190789461, 0)
Label_10.Size = UDim2.new(0, 401, 0, 30)
Label_10.AutoButtonColor = false
Label_10.Font = Enum.Font.Gotham
Label_10.Text = ""
Label_10.TextColor3 = Color3.fromRGB(255, 255, 255)
Label_10.TextSize = 14.000

LabelTitle_10.Name = "LabelTitle"
LabelTitle_10.Parent = Label_10
LabelTitle_10.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
LabelTitle_10.BackgroundTransparency = 1.000
LabelTitle_10.Position = UDim2.new(0, 5, 0, 0)
LabelTitle_10.Size = UDim2.new(0, 200, 0, 30)
LabelTitle_10.Font = Enum.Font.Gotham
LabelTitle_10.Text = "1. The autofarm gets faster the more boxes you can hold."
LabelTitle_10.TextColor3 = Color3.fromRGB(127, 131, 137)
LabelTitle_10.TextSize = 14.000
LabelTitle_10.TextXAlignment = Enum.TextXAlignment.Left

Label_11.Name = "Label"
Label_11.Parent = ChannelHolder_3
Label_11.BackgroundColor3 = Color3.fromRGB(54, 57, 63)
Label_11.BorderSizePixel = 0
Label_11.Position = UDim2.new(0.261979163, 0, 0.190789461, 0)
Label_11.Size = UDim2.new(0, 401, 0, 30)
Label_11.AutoButtonColor = false
Label_11.Font = Enum.Font.Gotham
Label_11.Text = ""
Label_11.TextColor3 = Color3.fromRGB(255, 255, 255)
Label_11.TextSize = 14.000

LabelTitle_11.Name = "LabelTitle"
LabelTitle_11.Parent = Label_11
LabelTitle_11.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
LabelTitle_11.BackgroundTransparency = 1.000
LabelTitle_11.Position = UDim2.new(0, 5, 0, 0)
LabelTitle_11.Size = UDim2.new(0, 200, 0, 30)
LabelTitle_11.Font = Enum.Font.Gotham
LabelTitle_11.Text = "2. Maximize profit by proritizing your truck upgrade."
LabelTitle_11.TextColor3 = Color3.fromRGB(127, 131, 137)
LabelTitle_11.TextSize = 14.000
LabelTitle_11.TextXAlignment = Enum.TextXAlignment.Left

Label_12.Name = "Label"
Label_12.Parent = ChannelHolder_3
Label_12.BackgroundColor3 = Color3.fromRGB(54, 57, 63)
Label_12.BorderSizePixel = 0
Label_12.Position = UDim2.new(0.261979163, 0, 0.190789461, 0)
Label_12.Size = UDim2.new(0, 401, 0, 30)
Label_12.AutoButtonColor = false
Label_12.Font = Enum.Font.Gotham
Label_12.Text = ""
Label_12.TextColor3 = Color3.fromRGB(255, 255, 255)
Label_12.TextSize = 14.000

LabelTitle_12.Name = "LabelTitle"
LabelTitle_12.Parent = Label_12
LabelTitle_12.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
LabelTitle_12.BackgroundTransparency = 1.000
LabelTitle_12.Position = UDim2.new(0, 5, 0, 0)
LabelTitle_12.Size = UDim2.new(0, 200, 0, 30)
LabelTitle_12.Font = Enum.Font.Gotham
LabelTitle_12.Text = "3. Maxizmize deliveries by buying the best delivery drones."
LabelTitle_12.TextColor3 = Color3.fromRGB(127, 131, 137)
LabelTitle_12.TextSize = 14.000
LabelTitle_12.TextXAlignment = Enum.TextXAlignment.Left

Label_13.Name = "Label"
Label_13.Parent = ChannelHolder_3
Label_13.BackgroundColor3 = Color3.fromRGB(54, 57, 63)
Label_13.BorderSizePixel = 0
Label_13.Position = UDim2.new(0.261979163, 0, 0.190789461, 0)
Label_13.Size = UDim2.new(0, 401, 0, 30)
Label_13.AutoButtonColor = false
Label_13.Font = Enum.Font.Gotham
Label_13.Text = ""
Label_13.TextColor3 = Color3.fromRGB(255, 255, 255)
Label_13.TextSize = 14.000

LabelTitle_13.Name = "LabelTitle"
LabelTitle_13.Parent = Label_13
LabelTitle_13.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
LabelTitle_13.BackgroundTransparency = 1.000
LabelTitle_13.Position = UDim2.new(0, 5, 0, 0)
LabelTitle_13.Size = UDim2.new(0, 200, 0, 30)
LabelTitle_13.Font = Enum.Font.Gotham
LabelTitle_13.Text = "4. Rejoin until delivering to the best neighborhood."
LabelTitle_13.TextColor3 = Color3.fromRGB(127, 131, 137)
LabelTitle_13.TextSize = 14.000
LabelTitle_13.TextXAlignment = Enum.TextXAlignment.Left

ChannelHolder_4.Name = "ChannelHolder"
ChannelHolder_4.Parent = ChannelContentFrame_2
ChannelHolder_4.Active = true
ChannelHolder_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ChannelHolder_4.BackgroundTransparency = 1.000
ChannelHolder_4.BorderSizePixel = 0
ChannelHolder_4.ClipsDescendants = false
ChannelHolder_4.Position = UDim2.new(0.0360843204, 0, 0.0241984241, 0)
ChannelHolder_4.Size = UDim2.new(0, 412, 0, 314)
ChannelHolder_4.Visible = false
ChannelHolder_4.CanvasSize = UDim2.new(0, 0, 0, 102)
ChannelHolder_4.ScrollBarThickness = 6

ChannelHolderLayout_4.Name = "ChannelHolderLayout"
ChannelHolderLayout_4.Parent = ChannelHolder_4
ChannelHolderLayout_4.SortOrder = Enum.SortOrder.LayoutOrder
ChannelHolderLayout_4.Padding = UDim.new(0, 6)

Label_14.Name = "Label"
Label_14.Parent = ChannelHolder_4
Label_14.BackgroundColor3 = Color3.fromRGB(54, 57, 63)
Label_14.BorderSizePixel = 0
Label_14.Position = UDim2.new(0.261979163, 0, 0.190789461, 0)
Label_14.Size = UDim2.new(0, 401, 0, 30)
Label_14.AutoButtonColor = false
Label_14.Font = Enum.Font.Gotham
Label_14.Text = ""
Label_14.TextColor3 = Color3.fromRGB(255, 255, 255)
Label_14.TextSize = 14.000

LabelTitle_14.Name = "LabelTitle"
LabelTitle_14.Parent = Label_14
LabelTitle_14.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
LabelTitle_14.BackgroundTransparency = 1.000
LabelTitle_14.Position = UDim2.new(0, 5, 0, 0)
LabelTitle_14.Size = UDim2.new(0, 200, 0, 30)
LabelTitle_14.Font = Enum.Font.Gotham
LabelTitle_14.Text = "Made by GabrasticYT"
LabelTitle_14.TextColor3 = Color3.fromRGB(127, 131, 137)
LabelTitle_14.TextSize = 14.000
LabelTitle_14.TextXAlignment = Enum.TextXAlignment.Left

Label_15.Name = "Label"
Label_15.Parent = ChannelHolder_4
Label_15.BackgroundColor3 = Color3.fromRGB(54, 57, 63)
Label_15.BorderSizePixel = 0
Label_15.Position = UDim2.new(0.261979163, 0, 0.190789461, 0)
Label_15.Size = UDim2.new(0, 401, 0, 30)
Label_15.AutoButtonColor = false
Label_15.Font = Enum.Font.Gotham
Label_15.Text = ""
Label_15.TextColor3 = Color3.fromRGB(255, 255, 255)
Label_15.TextSize = 14.000

LabelTitle_15.Name = "LabelTitle"
LabelTitle_15.Parent = Label_15
LabelTitle_15.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
LabelTitle_15.BackgroundTransparency = 1.000
LabelTitle_15.Position = UDim2.new(0, 5, 0, 0)
LabelTitle_15.Size = UDim2.new(0, 200, 0, 30)
LabelTitle_15.Font = Enum.Font.Gotham
LabelTitle_15.Text = "Discord: gabe#0002"
LabelTitle_15.TextColor3 = Color3.fromRGB(127, 131, 137)
LabelTitle_15.TextSize = 14.000
LabelTitle_15.TextXAlignment = Enum.TextXAlignment.Left

Label_16.Name = "Label"
Label_16.Parent = ChannelHolder_4
Label_16.BackgroundColor3 = Color3.fromRGB(54, 57, 63)
Label_16.BorderSizePixel = 0
Label_16.Position = UDim2.new(0.261979163, 0, 0.190789461, 0)
Label_16.Size = UDim2.new(0, 401, 0, 30)
Label_16.AutoButtonColor = false
Label_16.Font = Enum.Font.Gotham
Label_16.Text = ""
Label_16.TextColor3 = Color3.fromRGB(255, 255, 255)
Label_16.TextSize = 14.000

LabelTitle_16.Name = "LabelTitle"
LabelTitle_16.Parent = Label_16
LabelTitle_16.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
LabelTitle_16.BackgroundTransparency = 1.000
LabelTitle_16.Position = UDim2.new(0, 5, 0, 0)
LabelTitle_16.Size = UDim2.new(0, 200, 0, 30)
LabelTitle_16.Font = Enum.Font.Gotham
LabelTitle_16.Text = "Youtube: Gabrastic"
LabelTitle_16.TextColor3 = Color3.fromRGB(127, 131, 137)
LabelTitle_16.TextSize = 14.000
LabelTitle_16.TextXAlignment = Enum.TextXAlignment.Left

Userpad.Name = "Userpad"
Userpad.Parent = TopFrameHolder
Userpad.BackgroundColor3 = Color3.fromRGB(41, 43, 47)
Userpad.BorderSizePixel = 0
Userpad.Position = UDim2.new(0.106243297, 0, 15.9807148, 0)
Userpad.Size = UDim2.new(0, 179, 0, 43)

UserName.Name = "UserName"
UserName.Parent = Userpad
UserName.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
UserName.BackgroundTransparency = 1.000
UserName.BorderSizePixel = 0
UserName.ClipsDescendants = true
UserName.Position = UDim2.new(0.157374308, 0, 0.302046537, 0)
UserName.Size = UDim2.new(0, 98, 0, 17)
UserName.Font = Enum.Font.GothamSemibold
UserName.Text = "SkyHax"
UserName.TextColor3 = Color3.fromRGB(255, 255, 255)
UserName.TextSize = 13.000
UserName.TextXAlignment = Enum.TextXAlignment.Left

Title.Name = "Title"
Title.Parent = TopFrame
Title.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Title.BackgroundTransparency = 1.000
Title.Position = UDim2.new(0.0102790017, 0, 0, 0)
Title.Size = UDim2.new(0, 192, 0, 23)
Title.Font = Enum.Font.Gotham
Title.Text = "SkyHax"
Title.TextColor3 = Color3.fromRGB(99, 102, 109)
Title.TextSize = 13.000
Title.TextXAlignment = Enum.TextXAlignment.Left

CloseBtn.Name = "CloseBtn"
CloseBtn.Parent = TopFrame
CloseBtn.BackgroundColor3 = Color3.fromRGB(32, 34, 37)
CloseBtn.BorderSizePixel = 0
CloseBtn.Position = UDim2.new(0.959063113, 0, -0.0169996787, 0)
CloseBtn.Size = UDim2.new(0, 28, 0, 22)
CloseBtn.AutoButtonColor = false
CloseBtn.Font = Enum.Font.Gotham
CloseBtn.Text = ""
CloseBtn.TextColor3 = Color3.fromRGB(255, 255, 255)
CloseBtn.TextSize = 14.000

CloseIcon.Name = "CloseIcon"
CloseIcon.Parent = CloseBtn
CloseIcon.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
CloseIcon.BackgroundTransparency = 1.000
CloseIcon.Position = UDim2.new(0.189182192, 0, 0.128935531, 0)
CloseIcon.Size = UDim2.new(0, 17, 0, 17)
CloseIcon.Image = "http://www.roblox.com/asset/?id=6035047409"
CloseIcon.ImageColor3 = Color3.fromRGB(220, 221, 222)

MinimizeButton.Name = "MinimizeButton"
MinimizeButton.Parent = TopFrame
MinimizeButton.BackgroundColor3 = Color3.fromRGB(32, 34, 37)
MinimizeButton.BorderSizePixel = 0
MinimizeButton.Position = UDim2.new(0.917947114, 0, -0.0169996787, 0)
MinimizeButton.Size = UDim2.new(0, 28, 0, 22)
MinimizeButton.AutoButtonColor = false
MinimizeButton.Font = Enum.Font.Gotham
MinimizeButton.Text = ""
MinimizeButton.TextColor3 = Color3.fromRGB(255, 255, 255)
MinimizeButton.TextSize = 14.000

MinimizeLabel.Name = "MinimizeLabel"
MinimizeLabel.Parent = MinimizeButton
MinimizeLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
MinimizeLabel.BackgroundTransparency = 1.000
MinimizeLabel.Position = UDim2.new(0.189182192, 0, 0.128935531, 0)
MinimizeLabel.Size = UDim2.new(0, 17, 0, 17)
MinimizeLabel.Image = "http://www.roblox.com/asset/?id=6035067836"
MinimizeLabel.ImageColor3 = Color3.fromRGB(220, 221, 222)

ServersHoldFrame.Name = "ServersHoldFrame"
ServersHoldFrame.Parent = MainFrame
ServersHoldFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ServersHoldFrame.BackgroundTransparency = 1.000
ServersHoldFrame.BorderColor3 = Color3.fromRGB(27, 42, 53)
ServersHoldFrame.Size = UDim2.new(0, 71, 0, 396)

ServersHold.Name = "ServersHold"
ServersHold.Parent = ServersHoldFrame
ServersHold.Active = true
ServersHold.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ServersHold.BackgroundTransparency = 1.000
ServersHold.BorderSizePixel = 0
ServersHold.Position = UDim2.new(-0.000359333731, 0, 0.0580808073, 0)
ServersHold.Size = UDim2.new(0, 71, 0, 373)
ServersHold.CanvasSize = UDim2.new(0, 0, 0, 101)
ServersHold.ScrollBarThickness = 1

ServersHoldLayout.Name = "ServersHoldLayout"
ServersHoldLayout.Parent = ServersHold
ServersHoldLayout.SortOrder = Enum.SortOrder.LayoutOrder
ServersHoldLayout.Padding = UDim.new(0, 7)

ServersHoldPadding.Name = "ServersHoldPadding"
ServersHoldPadding.Parent = ServersHold
ServersHoldPadding.PaddingLeft = UDim.new(0, 14)

MainUIServer.Name = "Main UIServer"
MainUIServer.Parent = ServersHold
MainUIServer.BackgroundColor3 = Color3.fromRGB(113, 137, 228)
MainUIServer.Position = UDim2.new(0.125, 0, 0, 0)
MainUIServer.Size = UDim2.new(0, 47, 0, 47)
MainUIServer.AutoButtonColor = false
MainUIServer.Font = Enum.Font.Gotham
MainUIServer.Text = ""
MainUIServer.TextColor3 = Color3.fromRGB(255, 255, 255)
MainUIServer.TextSize = 18.000

ServerCorner_3.CornerRadius = UDim.new(0, 15)
ServerCorner_3.Name = "ServerCorner"
ServerCorner_3.Parent = MainUIServer

ServerIco.Name = "ServerIco"
ServerIco.Parent = MainUIServer
ServerIco.AnchorPoint = Vector2.new(0.5, 0.5)
ServerIco.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ServerIco.BackgroundTransparency = 1.000
ServerIco.Position = UDim2.new(0.489361703, 0, 0.489361703, 0)
ServerIco.Size = UDim2.new(0, 26, 0, 26)
ServerIco.Image = "http://www.roblox.com/asset/?id=6031075938"

ServerWhiteFrame.Name = "ServerWhiteFrame"
ServerWhiteFrame.Parent = MainUIServer
ServerWhiteFrame.AnchorPoint = Vector2.new(0.5, 0.5)
ServerWhiteFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ServerWhiteFrame.Position = UDim2.new(-0.347378343, 0, 0.502659559, 0)
ServerWhiteFrame.Size = UDim2.new(0, 11, 0, 46)

ServerWhiteFrameCorner.CornerRadius = UDim.new(1, 0)
ServerWhiteFrameCorner.Name = "ServerWhiteFrameCorner"
	ServerWhiteFrameCorner.Parent = ServerWhiteFrame
	

	-- Scripts:


	local script = Instance.new('LocalScript', ScreenGui)

	local button = "RightControl"
	local screengui = script.Parent
	game:GetService("UserInputService").InputBegan:connect(function(key)
		if key.KeyCode == Enum.KeyCode.RightControl then
			if screengui.Enabled == true then 
				screengui.Enabled = false
			else
				screengui.Enabled = true
			end
		end
	end)


	local script = Instance.new('LocalScript', mainfuncbtn)

	local button = script.Parent
	local frame = script.Parent.Parent.Parent.functionsframe
	local frame2 = script.Parent.Parent.Parent.otherframe


	button.MouseButton1Click:Connect(function()
		frame:TweenPosition(UDim2.new(0.324, 0, 0, 10), "InOut", "Quad", .5, true)
		frame2:TweenPosition(UDim2.new(0.324, 0, -1, 0), "InOut", "Quad", .5, true)
	end)

	local script = Instance.new('LocalScript', otherbtn)

	local button = script.Parent
	local frame2 = script.Parent.Parent.Parent.functionsframe
	local frame = script.Parent.Parent.Parent.otherframe


	button.MouseButton1Click:Connect(function()
		frame:TweenPosition(UDim2.new(0.324, 0, 0, 10), "InOut", "Quad", .5, true)
		frame2:TweenPosition(UDim2.new(0.324, 0, 1, 0), "InOut", "Quad", .5, true)
	end)

	local script = Instance.new('LocalScript', worldchangecolourbtn)

	local button = script.Parent
	local toggle = script.Parent.TextLabel

	button.MouseButton1Click:Connect(function()
		if toggle.BackgroundColor3 == Color3.new(1, 1, 1) then
			game:GetService("TweenService"):Create(toggle, TweenInfo.new(.5), {
				["BackgroundColor3"] = Color3.fromRGB(0, 255, 0)
			}):Play()
		elseif toggle.BackgroundColor3 == Color3.new(0, 1, 0) then
			game:GetService("TweenService"):Create(toggle, TweenInfo.new(.5), {
				["BackgroundColor3"] = Color3.fromRGB(255, 255, 255)
			}):Play()
		end
	end)


	local script = Instance.new('LocalScript', grenadetpbtn)

	local button = script.Parent
	local toggle = script.Parent.TextLabel

	button.MouseButton1Click:Connect(function()
		if toggle.BackgroundColor3 == Color3.new(1, 1, 1) then
			game:GetService("TweenService"):Create(toggle, TweenInfo.new(.5), {
				["BackgroundColor3"] = Color3.fromRGB(0, 255, 0)
			}):Play()
		elseif toggle.BackgroundColor3 == Color3.new(0, 1, 0) then
			game:GetService("TweenService"):Create(toggle, TweenInfo.new(.5), {
				["BackgroundColor3"] = Color3.fromRGB(255, 255, 255)
			}):Play()
		end
	end)


	local script = Instance.new('LocalScript', chatspambtn)

	local button = script.Parent
	local toggle = script.Parent.TextLabel

	button.MouseButton1Click:Connect(function()
		if toggle.BackgroundColor3 == Color3.new(1, 1, 1) then
			game:GetService("TweenService"):Create(toggle, TweenInfo.new(.5), {
				["BackgroundColor3"] = Color3.fromRGB(0, 255, 0)
			}):Play()
		elseif toggle.BackgroundColor3 == Color3.new(0, 1, 0) then
			game:GetService("TweenService"):Create(toggle, TweenInfo.new(.5), {
				["BackgroundColor3"] = Color3.fromRGB(255, 255, 255)
			}):Play()
		end
	end)


	local script = Instance.new('LocalScript', killsaybtn)

	local button = script.Parent
	local toggle = script.Parent.TextLabel

	button.MouseButton1Click:Connect(function()
		if toggle.BackgroundColor3 == Color3.new(1, 1, 1) then
			game:GetService("TweenService"):Create(toggle, TweenInfo.new(.5), {
				["BackgroundColor3"] = Color3.fromRGB(0, 255, 0)
			}):Play()
		elseif toggle.BackgroundColor3 == Color3.new(0, 1, 0) then
			game:GetService("TweenService"):Create(toggle, TweenInfo.new(.5), {
				["BackgroundColor3"] = Color3.fromRGB(255, 255, 255)
			}):Play()
		end
	end)


	local script = Instance.new('LocalScript', flybtn)

	local button = script.Parent
	local toggle = script.Parent.TextLabel

	button.MouseButton1Click:Connect(function()
		if toggle.BackgroundColor3 == Color3.new(1, 1, 1) then
			game:GetService("TweenService"):Create(toggle, TweenInfo.new(.5), {
				["BackgroundColor3"] = Color3.fromRGB(0, 255, 0)
			}):Play()
		elseif toggle.BackgroundColor3 == Color3.new(0, 1, 0) then
			game:GetService("TweenService"):Create(toggle, TweenInfo.new(.5), {
				["BackgroundColor3"] = Color3.fromRGB(255, 255, 255)
			}):Play()
		end
	end)


	local script = Instance.new('LocalScript', silentaimtbtn)

	local button = script.Parent
	local toggle = script.Parent.TextLabel

	button.MouseButton1Click:Connect(function()
		if toggle.BackgroundColor3 == Color3.new(1, 1, 1) then
			game:GetService("TweenService"):Create(toggle, TweenInfo.new(.5), {
				["BackgroundColor3"] = Color3.fromRGB(0, 255, 0)
			}):Play()
		elseif toggle.BackgroundColor3 == Color3.new(0, 1, 0) then
			game:GetService("TweenService"):Create(toggle, TweenInfo.new(.5), {
				["BackgroundColor3"] = Color3.fromRGB(255, 255, 255)
			}):Play()
		end
	end)


	local script = Instance.new('LocalScript', espbtn)

	local button = script.Parent
	local toggle = script.Parent.TextLabel

	button.MouseButton1Click:Connect(function()
		if toggle.BackgroundColor3 == Color3.new(1, 1, 1) then
			game:GetService("TweenService"):Create(toggle, TweenInfo.new(.5), {
				["BackgroundColor3"] = Color3.fromRGB(0, 255, 0)
			}):Play()
		elseif toggle.BackgroundColor3 == Color3.new(0, 1, 0) then
			game:GetService("TweenService"):Create(toggle, TweenInfo.new(.5), {
				["BackgroundColor3"] = Color3.fromRGB(255, 255, 255)
			}):Play()
		end
	end)


	local script = Instance.new('LocalScript', TextButton)

	local gui = script.Parent.Parent.Parent.Parent
	local button = script.Parent
	button.MouseButton1Click:Connect(function()
		gui:Destroy()
	end)



	local script = Instance.new('LocalScript', ScreenGui)

	local Drag = script.Parent.Frame
	gsCoreGui = game:GetService("CoreGui")
	gsTween = game:GetService("TweenService")
	local UserInputService = game:GetService("UserInputService")
	local dragging
	local dragInput
	local dragStart
	local startPos
	local function update(input)
		local delta = input.Position - dragStart
		local dragTime = 0.2
		local SmoothDrag = {}
		SmoothDrag.Position =
			UDim2.new(startPos.X.Scale, startPos.X.Offset + delta.X, startPos.Y.Scale, startPos.Y.Offset + delta.Y)
		local dragSmoothFunction =
			gsTween:Create(Drag, TweenInfo.new(dragTime, Enum.EasingStyle.Linear, Enum.EasingDirection.InOut), SmoothDrag)
		dragSmoothFunction:Play()
	end
	Drag.InputBegan:Connect(
		function(input)
			if input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch then
				dragging = true
				dragStart = input.Position
				startPos = Drag.Position
				input.Changed:Connect(
					function()
						if input.UserInputState == Enum.UserInputState.End then
							dragging = false
						end
					end
				)
			end
		end
	)
	Drag.InputChanged:Connect(
		function(input)
			if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
				dragInput = input
			end
		end
	)
	UserInputService.InputChanged:Connect(
		function(input)
			if input == dragInput and dragging and Drag.Size then
				update(input)
			end
		end
	)


	local script = Instance.new('LocalScript', wlframe)

	local Drag = script.Parent
	gsCoreGui = game:GetService("CoreGui")
	gsTween = game:GetService("TweenService")
	local UserInputService = game:GetService("UserInputService")
	local dragging
	local dragInput
	local dragStart
	local startPos
	local function update(input)
		local delta = input.Position - dragStart
		local dragTime = 0.2
		local SmoothDrag = {}
		SmoothDrag.Position =
			UDim2.new(startPos.X.Scale, startPos.X.Offset + delta.X, startPos.Y.Scale, startPos.Y.Offset + delta.Y)
		local dragSmoothFunction = gsTween:Create(Drag, TweenInfo.new(dragTime, Enum.EasingStyle.Linear, Enum.EasingDirection.InOut), SmoothDrag)
		dragSmoothFunction:Play()
	end
	Drag.InputBegan:Connect(
		function(input)
			if input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch then
				dragging = true
				dragStart = input.Position
				startPos = Drag.Position
				input.Changed:Connect(
					function()
						if input.UserInputState == Enum.UserInputState.End then
							dragging = false
						end
					end
				)
			end
		end
	)
	Drag.InputChanged:Connect(
		function(input)
			if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
				dragInput = input
			end
		end
	)
	UserInputService.InputChanged:Connect(
		function(input)
			if input == dragInput and dragging and Drag.Size then
				update(input)
			end
		end
	)


	local script = Instance.new('LocalScript', wlframe)

	local frame = script.Parent
	local passfrm = script.Parent.password
	local guifrm = script.Parent.Parent.Frame
	local enter = script.Parent.enterbutton
	local textlabel = script.Parent.Whitlist
	enter.MouseButton1Click:Connect(function()
		if true then
			textlabel.Text = "Enjoy!"
			wait(2)
			frame:TweenPosition(UDim2.new(0.41, 0, -1.0, 0), "In", "Back", 1.5)
			wait(2)
			guifrm.Visible = true
			frame:Destroy()
		else
			textlabel.Text = "Don't know how you fucked that up."
			wait(1)
			textlabel.Text = "Whitelist"
		end	
	end)



	local script = Instance.new('LocalScript', copydisc)

	local label = script.Parent.TextLabel
	local parent = script.Parent

	parent.MouseEnter:Connect(function()
		label:TweenSize(UDim2.new(0, 78, 0, 1), "Out", "Quad", 0.5, true)
	end)
	parent.MouseLeave:Connect(function()
		label:TweenSize(UDim2.new(0, 0, 0, 1), "Out", "Quad", 0.5, true)
	end)
	parent.MouseButton1Click:Connect(function()
		label.BackgroundColor3 = Color3.new(0, 255, 0)
	end)
	parent.MouseLeave:Connect(function()
		label.BackgroundColor3 = Color3.new(255, 0, 0)
	end)


	local script = Instance.new('LocalScript', password)

	local main = script.Parent



	main.MouseEnter:Connect(function()
		game:GetService("TweenService"):Create(main, TweenInfo.new(.8), {
			["BorderColor3"] = Color3.fromRGB(255, 0, 0);
		}):Play()
	end)

	main.MouseLeave:Connect(function()
		game:GetService("TweenService"):Create(main, TweenInfo.new(.8), {
			["BorderColor3"] = Color3.fromRGB(94, 94, 94);
		}):Play()
	end)



	local script = Instance.new('LocalScript', enterbutton)

	local label = script.Parent.TextLabel
	local parent = script.Parent

	parent.MouseEnter:Connect(function()
		label:TweenSize(UDim2.new(0, 78, 0, 1), "Out", "Quad", 0.5, true)
	end)
	parent.MouseLeave:Connect(function()
		label:TweenSize(UDim2.new(0, 0, 0, 1), "Out", "Quad", 0.5, true)
	end)
