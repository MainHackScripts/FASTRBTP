
print("Script is Working!")

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local MainFrame = Instance.new("Frame")
local UIGradient = Instance.new("UIGradient")
local UICorner = Instance.new("UICorner")
local MainTitle = Instance.new("TextLabel")
local ImputFrame = Instance.new("Frame")
local Imput = Instance.new("TextBox")
local WelcomeTitle = Instance.new("TextLabel")
local GoButton = Instance.new("TextButton")
local UICorner_2 = Instance.new("UICorner")
local Shadow = Instance.new("Frame")
local UICorner_3 = Instance.new("UICorner")
local TextLabel = Instance.new("TextLabel")
local CloseMainFrame = Instance.new("TextButton")
local Shadow_2 = Instance.new("Frame")
local TextLabel_2 = Instance.new("TextLabel")
local Slot1 = Instance.new("Frame")
local UIGradient_2 = Instance.new("UIGradient")
local UICorner_4 = Instance.new("UICorner")
local Slot1title = Instance.new("TextLabel")
local Slot1Frame = Instance.new("Frame")
local Westlake1 = Instance.new("TextButton")
local Eastside1 = Instance.new("TextButton")
local Rec1 = Instance.new("TextButton")
local Lobby1 = Instance.new("TextButton")
local CloseSlot1 = Instance.new("TextButton")
local UICorner_5 = Instance.new("UICorner")
local Shadow_3 = Instance.new("Frame")
local UICorner_6 = Instance.new("UICorner")
local TextLabel_3 = Instance.new("TextLabel")
local Slot2 = Instance.new("Frame")
local UIGradient_3 = Instance.new("UIGradient")
local UICorner_7 = Instance.new("UICorner")
local Slot2title = Instance.new("TextLabel")
local Slot2Frame = Instance.new("Frame")
local Westlake2 = Instance.new("TextButton")
local Eastside2 = Instance.new("TextButton")
local Rec2 = Instance.new("TextButton")
local Lobby2 = Instance.new("TextButton")
local CloseSlot2 = Instance.new("TextButton")
local UICorner_8 = Instance.new("UICorner")
local Shadow_4 = Instance.new("Frame")
local UICorner_9 = Instance.new("UICorner")
local TextLabel_4 = Instance.new("TextLabel")
local Slot3 = Instance.new("Frame")
local UIGradient_4 = Instance.new("UIGradient")
local UICorner_10 = Instance.new("UICorner")
local Slot3title = Instance.new("TextLabel")
local Slot3Frame = Instance.new("Frame")
local Westlake3 = Instance.new("TextButton")
local Eastside3 = Instance.new("TextButton")
local Rec3 = Instance.new("TextButton")
local Lobby3 = Instance.new("TextButton")
local CloseSlot3 = Instance.new("TextButton")
local UICorner_11 = Instance.new("UICorner")
local Shadow_5 = Instance.new("Frame")
local UICorner_12 = Instance.new("UICorner")
local TextLabel_5 = Instance.new("TextLabel")

--Properties:

ScreenGui.Parent = game.CoreGui

MainFrame.Name = "MainFrame"
MainFrame.Parent = ScreenGui
MainFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
MainFrame.BorderColor3 = Color3.fromRGB(27, 42, 53)
MainFrame.BorderSizePixel = 0
MainFrame.Position = UDim2.new(0.210735589, 0, 0.18369028, 0)
MainFrame.Size = UDim2.new(0, 548, 0, 370)
MainFrame.Active = true
MainFrame.Draggable = true

UIGradient.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(102, 45, 113)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(197, 66, 110))}
UIGradient.Parent = MainFrame

UICorner.CornerRadius = UDim.new(0, 4)
UICorner.Parent = MainFrame

MainTitle.Name = "MainTitle"
MainTitle.Parent = MainFrame
MainTitle.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
MainTitle.Position = UDim2.new(0.152450085, 0, 0.0216216221, 0)
MainTitle.Size = UDim2.new(0, 369, 0, 66)
MainTitle.Font = Enum.Font.SourceSansBold
MainTitle.Text = "BoostedX TP Version 2"
MainTitle.TextColor3 = Color3.fromRGB(255, 0, 255)
MainTitle.TextSize = 41.000
MainTitle.TextWrapped = true

ImputFrame.Name = "ImputFrame"
ImputFrame.Parent = MainFrame
ImputFrame.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
ImputFrame.Position = UDim2.new(0.105263159, 0, 0.251351327, 0)
ImputFrame.Size = UDim2.new(0, 434, 0, 246)
ImputFrame.Active = true
ImputFrame.Draggable = false

Imput.Name = "Imput"
Imput.Parent = ImputFrame
Imput.BackgroundColor3 = Color3.fromRGB(86, 0, 86)
Imput.Position = UDim2.new(0.264976948, 0, 0.678861797, 0)
Imput.Size = UDim2.new(0, 205, 0, 66)
Imput.Font = Enum.Font.SciFi
Imput.Text = "Enter Location Here!"
Imput.TextColor3 = Color3.fromRGB(255, 255, 255)
Imput.TextSize = 14.000

WelcomeTitle.Name = "WelcomeTitle"
WelcomeTitle.Parent = ImputFrame
WelcomeTitle.BackgroundColor3 = Color3.fromRGB(207, 0, 207)
WelcomeTitle.Position = UDim2.new(0.110599078, 0, 0.0447154455, 0)
WelcomeTitle.Size = UDim2.new(0, 337, 0, 59)
WelcomeTitle.Font = Enum.Font.SourceSansItalic
WelcomeTitle.Text = "Hello! "..game.Players.LocalPlayer.Name
WelcomeTitle.TextColor3 = Color3.fromRGB(255, 255, 255)
WelcomeTitle.TextScaled = true
WelcomeTitle.TextSize = 14.000
WelcomeTitle.TextWrapped = true

GoButton.Name = "GoButton"
GoButton.Parent = ImputFrame
GoButton.BackgroundColor3 = Color3.fromRGB(207, 100, 150)
GoButton.BorderSizePixel = 0
GoButton.Position = UDim2.new(0.292626739, 0, 0.378048778, 0)
GoButton.Size = UDim2.new(0, 180, 0, 45)
GoButton.ZIndex = 2
GoButton.Font = Enum.Font.GothamSemibold
GoButton.Text = ""
GoButton.TextColor3 = Color3.fromRGB(255, 255, 255)
GoButton.TextScaled = true
GoButton.TextSize = 14.000
GoButton.TextWrapped = true
GoButton.MouseButton1Down:connect(function()
  if Imput.Text == "Slot 1" then
        Slot1.Visible = true
        MainFrame.Visible = false
    elseif Imput.Text == "Slot 2" then
        Slot2.Visible = true
        MainFrame.Visible = false
    elseif Imput.Text == "Slot 3" then
        Slot3.Visible = true
        MainFrame.Visible = false
    end
end)

UICorner_2.CornerRadius = UDim.new(0, 4)
UICorner_2.Parent = GoButton

Shadow.Name = "Shadow"
Shadow.Parent = GoButton
Shadow.BackgroundColor3 = Color3.fromRGB(53, 69, 103)
Shadow.BorderSizePixel = 0
Shadow.Size = UDim2.new(1, 0, 1, 4)

UICorner_3.CornerRadius = UDim.new(0, 4)
UICorner_3.Parent = Shadow

TextLabel.Parent = GoButton
TextLabel.AnchorPoint = Vector2.new(0.5, 0.5)
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.BorderColor3 = Color3.fromRGB(27, 42, 53)
TextLabel.BorderSizePixel = 0
TextLabel.Position = UDim2.new(0.5, 0, 0.5, 0)
TextLabel.Size = UDim2.new(1, -20, 1, -20)
TextLabel.ZIndex = 2
TextLabel.Font = Enum.Font.GothamSemibold
TextLabel.Text = "GO!"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextScaled = true
TextLabel.TextSize = 14.000
TextLabel.TextWrapped = true

CloseMainFrame.Name = "CloseMainFrame"
CloseMainFrame.Parent = MainFrame
CloseMainFrame.BackgroundColor3 = Color3.fromRGB(156, 102, 155)
CloseMainFrame.BorderSizePixel = 0
CloseMainFrame.Position = UDim2.new(0.850272238, 0, 0.0216216221, 0)
CloseMainFrame.Size = UDim2.new(0, 70, 0, 66)
CloseMainFrame.ZIndex = 2
CloseMainFrame.Font = Enum.Font.GothamSemibold
CloseMainFrame.Text = ""
CloseMainFrame.TextColor3 = Color3.fromRGB(255, 255, 255)
CloseMainFrame.TextScaled = true
CloseMainFrame.TextSize = 14.000
CloseMainFrame.TextWrapped = true
CloseMainFrame.MouseButton1Down:connect(function()
	MainFrame.Visible = false
end)

Shadow_2.Name = "Shadow"
Shadow_2.Parent = CloseMainFrame
Shadow_2.BackgroundColor3 = Color3.fromRGB(118, 74, 117)
Shadow_2.BorderSizePixel = 0
Shadow_2.Size = UDim2.new(1, 0, 1, 4)

TextLabel_2.Parent = CloseMainFrame
TextLabel_2.AnchorPoint = Vector2.new(0.5, 0.5)
TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.BackgroundTransparency = 1.000
TextLabel_2.BorderColor3 = Color3.fromRGB(27, 42, 53)
TextLabel_2.BorderSizePixel = 0
TextLabel_2.Position = UDim2.new(0.5, 0, 0.5, 0)
TextLabel_2.Size = UDim2.new(1, -20, 1, -20)
TextLabel_2.ZIndex = 2
TextLabel_2.Font = Enum.Font.GothamSemibold
TextLabel_2.Text = "X"
TextLabel_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.TextScaled = true
TextLabel_2.TextSize = 14.000
TextLabel_2.TextWrapped = true

Slot1.Name = "Slot1"
Slot1.Parent = ScreenGui
Slot1.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Slot1.BorderColor3 = Color3.fromRGB(27, 42, 53)
Slot1.BorderSizePixel = 0
Slot1.Position = UDim2.new(0.269383669, 0, 0.18369028, 0)
Slot1.Size = UDim2.new(0, 430, 0, 369)
Slot1.Visible = false
Slot1.Active = true
Slot1.Draggable = true

UIGradient_2.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(102, 45, 113)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(197, 66, 110))}
UIGradient_2.Parent = Slot1

UICorner_4.CornerRadius = UDim.new(0, 4)
UICorner_4.Parent = Slot1

Slot1title.Name = "Slot1title"
Slot1title.Parent = Slot1
Slot1title.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Slot1title.BackgroundTransparency = 1.000
Slot1title.Position = UDim2.new(0.267441869, 0, 0.0216802154, 0)
Slot1title.Size = UDim2.new(0, 200, 0, 56)
Slot1title.Font = Enum.Font.SourceSansItalic
Slot1title.Text = "Slot 1 Section"
Slot1title.TextColor3 = Color3.fromRGB(255, 255, 255)
Slot1title.TextSize = 36.000

Slot1Frame.Name = "Slot1Frame"
Slot1Frame.Parent = Slot1
Slot1Frame.BackgroundColor3 = Color3.fromRGB(166, 0, 166)
Slot1Frame.Position = UDim2.new(0.132558137, 0, 0.216802165, 0)
Slot1Frame.Size = UDim2.new(0, 304, 0, 256)
Slot1Frame.Active = true
Slot1Frame.Draggable = false

Westlake1.Name = "Westlake1"
Westlake1.Parent = Slot1Frame
Westlake1.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Westlake1.Position = UDim2.new(0.190789476, 0, 0.046875, 0)
Westlake1.Size = UDim2.new(0, 200, 0, 50)
Westlake1.Font = Enum.Font.SourceSansBold
Westlake1.Text = "Westlake"
Westlake1.TextColor3 = Color3.fromRGB(255, 255, 255)
Westlake1.TextSize = 31.000
Westlake1.MouseButton1Down:connect(function()
	local slot = 1
	local option = 'west'


	--// Fast TP made by BoostedX#0001 \\--

	--options--

	--west
	--east
	--rec
	--lobby















	local east = 591582661
	local west = 593223204
	local rec = 594402678
	local lobby = 856966839




	local Player = game.Players.LocalPlayer
	local TPService = game:GetService("TeleportService")
	local Storage = game:GetService("ReplicatedStorage")
	local v16 = TPService:GetLocalPlayerTeleportData();
	wait(1)

	if option == 'west' then
		if game.PlaceId == west then return end
	elseif option == 'east' then 
		if game.PlaceId == east then return end
	elseif option == 'rec' then 
		if game.PlaceId == rec then return end
	elseif option == 'lobby' then 
		if game.PlaceId == lobby then return end
	end

	if option == 'west' then
		TPService:Teleport(west, Player, slot);
	elseif option == 'east' then
		TPService:Teleport(east, Player, slot);
	elseif option == 'rec' then 
		TPService:Teleport(rec, Player, slot);
	elseif option == 'lobby' then 
		TPService:Teleport(lobby, Player, slot);
	end
end)

Eastside1.Name = "Eastside1"
Eastside1.Parent = Slot1Frame
Eastside1.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Eastside1.Position = UDim2.new(0.190789476, 0, 0.28515625, 0)
Eastside1.Size = UDim2.new(0, 200, 0, 50)
Eastside1.Font = Enum.Font.SourceSansBold
Eastside1.Text = "Eastside"
Eastside1.TextColor3 = Color3.fromRGB(255, 255, 255)
Eastside1.TextSize = 31.000
Eastside1.MouseButton1Down:connect(function()
	local slot = 1
	local option = 'east'


	--// Fast TP made by BoostedX#0001 \\--

	--options--

	--west
	--east
	--rec
	--lobby















	local east = 591582661
	local west = 593223204
	local rec = 594402678
	local lobby = 856966839




	local Player = game.Players.LocalPlayer
	local TPService = game:GetService("TeleportService")
	local Storage = game:GetService("ReplicatedStorage")
	local v16 = TPService:GetLocalPlayerTeleportData();
	wait(1)

	if option == 'west' then
		if game.PlaceId == west then return end
	elseif option == 'east' then 
		if game.PlaceId == east then return end
	elseif option == 'rec' then 
		if game.PlaceId == rec then return end
	elseif option == 'lobby' then 
		if game.PlaceId == lobby then return end
	end

	if option == 'west' then
		TPService:Teleport(west, Player, slot);
	elseif option == 'east' then
		TPService:Teleport(east, Player, slot);
	elseif option == 'rec' then 
		TPService:Teleport(rec, Player, slot);
	elseif option == 'lobby' then 
		TPService:Teleport(lobby, Player, slot);
	end
end)

Rec1.Name = "Rec1"
Rec1.Parent = Slot1Frame
Rec1.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Rec1.Position = UDim2.new(0.190789476, 0, 0.51953125, 0)
Rec1.Size = UDim2.new(0, 200, 0, 50)
Rec1.Font = Enum.Font.SourceSansBold
Rec1.Text = "Rec. Center"
Rec1.TextColor3 = Color3.fromRGB(255, 255, 255)
Rec1.TextSize = 31.000
Rec1.MouseButton1Down:connect(function()
	local slot = 1
	local option = 'rec'


	--// Fast TP made by BoostedX#0001 \\--

	--options--

	--west
	--east
	--rec
	--lobby















	local east = 591582661
	local west = 593223204
	local rec = 594402678
	local lobby = 856966839




	local Player = game.Players.LocalPlayer
	local TPService = game:GetService("TeleportService")
	local Storage = game:GetService("ReplicatedStorage")
	local v16 = TPService:GetLocalPlayerTeleportData();
	wait(1)

	if option == 'west' then
		if game.PlaceId == west then return end
	elseif option == 'east' then 
		if game.PlaceId == east then return end
	elseif option == 'rec' then 
		if game.PlaceId == rec then return end
	elseif option == 'lobby' then 
		if game.PlaceId == lobby then return end
	end

	if option == 'west' then
		TPService:Teleport(west, Player, slot);
	elseif option == 'east' then
		TPService:Teleport(east, Player, slot);
	elseif option == 'rec' then 
		TPService:Teleport(rec, Player, slot);
	elseif option == 'lobby' then 
		TPService:Teleport(lobby, Player, slot);
	end
end)

Lobby1.Name = "Lobby1"
Lobby1.Parent = Slot1Frame
Lobby1.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Lobby1.Position = UDim2.new(0.190789476, 0, 0.74609375, 0)
Lobby1.Size = UDim2.new(0, 200, 0, 50)
Lobby1.Font = Enum.Font.SourceSansBold
Lobby1.Text = "Lobby"
Lobby1.TextColor3 = Color3.fromRGB(255, 255, 255)
Lobby1.TextSize = 31.000
Lobby1.MouseButton1Down:connect(function()
	local slot = 1
	local option = 'lobby'


	--// Fast TP made by BoostedX#0001 \\--

	--options--

	--west
	--east
	--rec
	--lobby















	local east = 591582661
	local west = 593223204
	local rec = 594402678
	local lobby = 856966839




	local Player = game.Players.LocalPlayer
	local TPService = game:GetService("TeleportService")
	local Storage = game:GetService("ReplicatedStorage")
	local v16 = TPService:GetLocalPlayerTeleportData();
	wait(1)

	if option == 'west' then
		if game.PlaceId == west then return end
	elseif option == 'east' then 
		if game.PlaceId == east then return end
	elseif option == 'rec' then 
		if game.PlaceId == rec then return end
	elseif option == 'lobby' then 
		if game.PlaceId == lobby then return end
	end

	if option == 'west' then
		TPService:Teleport(west, Player, slot);
	elseif option == 'east' then
		TPService:Teleport(east, Player, slot);
	elseif option == 'rec' then 
		TPService:Teleport(rec, Player, slot);
	elseif option == 'lobby' then 
		TPService:Teleport(lobby, Player, slot);
	end
end)

CloseSlot1.Name = "CloseSlot1"
CloseSlot1.Parent = Slot1
CloseSlot1.BackgroundColor3 = Color3.fromRGB(120, 1, 150)
CloseSlot1.BorderSizePixel = 0
CloseSlot1.Position = UDim2.new(0.802325606, 0, 0.032520324, 0)
CloseSlot1.Size = UDim2.new(0, 78, 0, 56)
CloseSlot1.ZIndex = 2
CloseSlot1.Font = Enum.Font.GothamSemibold
CloseSlot1.Text = ""
CloseSlot1.TextColor3 = Color3.fromRGB(255, 255, 255)
CloseSlot1.TextScaled = true
CloseSlot1.TextSize = 14.000
CloseSlot1.TextWrapped = true
CloseSlot1.MouseButton1Down:connect(function()
	Slot1.Visible = false
	MainFrame.Visible = true
end)

UICorner_5.CornerRadius = UDim.new(0, 4)
UICorner_5.Parent = CloseSlot1

Shadow_3.Name = "Shadow"
Shadow_3.Parent = CloseSlot1
Shadow_3.BackgroundColor3 = Color3.fromRGB(204, 0, 157)
Shadow_3.BorderSizePixel = 0
Shadow_3.Size = UDim2.new(1, 0, 1, 4)

UICorner_6.CornerRadius = UDim.new(0, 4)
UICorner_6.Parent = Shadow_3

TextLabel_3.Parent = CloseSlot1
TextLabel_3.AnchorPoint = Vector2.new(0.5, 0.5)
TextLabel_3.BackgroundColor3 = Color3.fromRGB(165, 10, 255)
TextLabel_3.BackgroundTransparency = 1.000
TextLabel_3.BorderColor3 = Color3.fromRGB(27, 42, 53)
TextLabel_3.BorderSizePixel = 0
TextLabel_3.Position = UDim2.new(0.5, 0, 0.5, 0)
TextLabel_3.Size = UDim2.new(1, -20, 1, -20)
TextLabel_3.ZIndex = 2
TextLabel_3.Font = Enum.Font.GothamSemibold
TextLabel_3.Text = "X"
TextLabel_3.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.TextScaled = true
TextLabel_3.TextSize = 14.000
TextLabel_3.TextWrapped = true

Slot2.Name = "Slot2"
Slot2.Parent = ScreenGui
Slot2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Slot2.BorderColor3 = Color3.fromRGB(27, 42, 53)
Slot2.BorderSizePixel = 0
Slot2.Position = UDim2.new(0.286282301, 0, 0.195222408, 0)
Slot2.Size = UDim2.new(0, 430, 0, 369)
Slot2.Visible = false
Slot2.Active = true
Slot2.Draggable = true

UIGradient_3.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(102, 45, 113)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(197, 66, 110))}
UIGradient_3.Parent = Slot2

UICorner_7.CornerRadius = UDim.new(0, 4)
UICorner_7.Parent = Slot2

Slot2title.Name = "Slot2title"
Slot2title.Parent = Slot2
Slot2title.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Slot2title.BackgroundTransparency = 1.000
Slot2title.Position = UDim2.new(0.267441869, 0, 0.032520324, 0)
Slot2title.Size = UDim2.new(0, 200, 0, 56)
Slot2title.Font = Enum.Font.SourceSansItalic
Slot2title.Text = "Slot 2 Section"
Slot2title.TextColor3 = Color3.fromRGB(255, 255, 255)
Slot2title.TextSize = 36.000

Slot2Frame.Name = "Slot2Frame"
Slot2Frame.Parent = Slot2
Slot2Frame.BackgroundColor3 = Color3.fromRGB(166, 0, 166)
Slot2Frame.Position = UDim2.new(0.132558137, 0, 0.216802165, 0)
Slot2Frame.Size = UDim2.new(0, 304, 0, 256)
Slot2Frame.Active = true
Slot2Frame.Draggable = false

Westlake2.Name = "Westlake2"
Westlake2.Parent = Slot2Frame
Westlake2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Westlake2.Position = UDim2.new(0.190789476, 0, 0.046875, 0)
Westlake2.Size = UDim2.new(0, 200, 0, 50)
Westlake2.Font = Enum.Font.SourceSansBold
Westlake2.Text = "Westlake"
Westlake2.TextColor3 = Color3.fromRGB(255, 255, 255)
Westlake2.TextSize = 31.000
Westlake2.MouseButton1Down:connect(function()
	local slot = 2
	local option = 'west'


	--// Fast TP made by BoostedX#0001 \\--

	--options--

	--west
	--east
	--rec
	--lobby















	local east = 591582661
	local west = 593223204
	local rec = 594402678
	local lobby = 856966839




	local Player = game.Players.LocalPlayer
	local TPService = game:GetService("TeleportService")
	local Storage = game:GetService("ReplicatedStorage")
	local v16 = TPService:GetLocalPlayerTeleportData();
	wait(1)

	if option == 'west' then
		if game.PlaceId == west then return end
	elseif option == 'east' then 
		if game.PlaceId == east then return end
	elseif option == 'rec' then 
		if game.PlaceId == rec then return end
	elseif option == 'lobby' then 
		if game.PlaceId == lobby then return end
	end

	if option == 'west' then
		TPService:Teleport(west, Player, slot);
	elseif option == 'east' then
		TPService:Teleport(east, Player, slot);
	elseif option == 'rec' then 
		TPService:Teleport(rec, Player, slot);
	elseif option == 'lobby' then 
		TPService:Teleport(lobby, Player, slot);
	end
end)

Eastside2.Name = "Eastside2"
Eastside2.Parent = Slot2Frame
Eastside2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Eastside2.Position = UDim2.new(0.190789476, 0, 0.28515625, 0)
Eastside2.Size = UDim2.new(0, 200, 0, 50)
Eastside2.Font = Enum.Font.SourceSansBold
Eastside2.Text = "Eastside"
Eastside2.TextColor3 = Color3.fromRGB(255, 255, 255)
Eastside2.TextSize = 31.000
Eastside2.MouseButton1Down:connect(function()
	local slot = 2
	local option = 'east'


	--// Fast TP made by BoostedX#0001 \\--

	--options--

	--west
	--east
	--rec
	--lobby















	local east = 591582661
	local west = 593223204
	local rec = 594402678
	local lobby = 856966839




	local Player = game.Players.LocalPlayer
	local TPService = game:GetService("TeleportService")
	local Storage = game:GetService("ReplicatedStorage")
	local v16 = TPService:GetLocalPlayerTeleportData();
	wait(1)

	if option == 'west' then
		if game.PlaceId == west then return end
	elseif option == 'east' then 
		if game.PlaceId == east then return end
	elseif option == 'rec' then 
		if game.PlaceId == rec then return end
	elseif option == 'lobby' then 
		if game.PlaceId == lobby then return end
	end

	if option == 'west' then
		TPService:Teleport(west, Player, slot);
	elseif option == 'east' then
		TPService:Teleport(east, Player, slot);
	elseif option == 'rec' then 
		TPService:Teleport(rec, Player, slot);
	elseif option == 'lobby' then 
		TPService:Teleport(lobby, Player, slot);
	end
end)

Rec2.Name = "Rec2"
Rec2.Parent = Slot2Frame
Rec2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Rec2.Position = UDim2.new(0.190789476, 0, 0.51953125, 0)
Rec2.Size = UDim2.new(0, 200, 0, 50)
Rec2.Font = Enum.Font.SourceSansBold
Rec2.Text = "Rec. Center"
Rec2.TextColor3 = Color3.fromRGB(255, 255, 255)
Rec2.TextSize = 31.000
Rec2.MouseButton1Down:connect(function()
	local slot = 2
	local option = 'rec'


	--// Fast TP made by BoostedX#0001 \\--

	--options--

	--west
	--east
	--rec
	--lobby















	local east = 591582661
	local west = 593223204
	local rec = 594402678
	local lobby = 856966839




	local Player = game.Players.LocalPlayer
	local TPService = game:GetService("TeleportService")
	local Storage = game:GetService("ReplicatedStorage")
	local v16 = TPService:GetLocalPlayerTeleportData();
	wait(1)

	if option == 'west' then
		if game.PlaceId == west then return end
	elseif option == 'east' then 
		if game.PlaceId == east then return end
	elseif option == 'rec' then 
		if game.PlaceId == rec then return end
	elseif option == 'lobby' then 
		if game.PlaceId == lobby then return end
	end

	if option == 'west' then
		TPService:Teleport(west, Player, slot);
	elseif option == 'east' then
		TPService:Teleport(east, Player, slot);
	elseif option == 'rec' then 
		TPService:Teleport(rec, Player, slot);
	elseif option == 'lobby' then 
		TPService:Teleport(lobby, Player, slot);
	end
end)

Lobby2.Name = "Lobby2"
Lobby2.Parent = Slot2Frame
Lobby2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Lobby2.Position = UDim2.new(0.190789476, 0, 0.74609375, 0)
Lobby2.Size = UDim2.new(0, 200, 0, 50)
Lobby2.Font = Enum.Font.SourceSansBold
Lobby2.Text = "Lobby"
Lobby2.TextColor3 = Color3.fromRGB(255, 255, 255)
Lobby2.TextSize = 31.000
Lobby2.MouseButton1Down:connect(function()
	local slot = 2
	local option = 'lobby'


	--// Fast TP made by BoostedX#0001 \\--

	--options--

	--west
	--east
	--rec
	--lobby















	local east = 591582661
	local west = 593223204
	local rec = 594402678
	local lobby = 856966839




	local Player = game.Players.LocalPlayer
	local TPService = game:GetService("TeleportService")
	local Storage = game:GetService("ReplicatedStorage")
	local v16 = TPService:GetLocalPlayerTeleportData();
	wait(1)

	if option == 'west' then
		if game.PlaceId == west then return end
	elseif option == 'east' then 
		if game.PlaceId == east then return end
	elseif option == 'rec' then 
		if game.PlaceId == rec then return end
	elseif option == 'lobby' then 
		if game.PlaceId == lobby then return end
	end

	if option == 'west' then
		TPService:Teleport(west, Player, slot);
	elseif option == 'east' then
		TPService:Teleport(east, Player, slot);
	elseif option == 'rec' then 
		TPService:Teleport(rec, Player, slot);
	elseif option == 'lobby' then 
		TPService:Teleport(lobby, Player, slot);
	end
end)

CloseSlot2.Name = "CloseSlot2"
CloseSlot2.Parent = Slot2
CloseSlot2.BackgroundColor3 = Color3.fromRGB(120, 1, 150)
CloseSlot2.BorderSizePixel = 0
CloseSlot2.Position = UDim2.new(0.802325606, 0, 0.032520324, 0)
CloseSlot2.Size = UDim2.new(0, 78, 0, 56)
CloseSlot2.ZIndex = 2
CloseSlot2.Font = Enum.Font.GothamSemibold
CloseSlot2.Text = ""
CloseSlot2.TextColor3 = Color3.fromRGB(255, 255, 255)
CloseSlot2.TextScaled = true
CloseSlot2.TextSize = 14.000
CloseSlot2.TextWrapped = true
CloseSlot2.MouseButton1Down:connect(function()
	Slot2.Visible = false
	MainFrame.Visible = true
end)

UICorner_8.CornerRadius = UDim.new(0, 4)
UICorner_8.Parent = CloseSlot2

Shadow_4.Name = "Shadow"
Shadow_4.Parent = CloseSlot2
Shadow_4.BackgroundColor3 = Color3.fromRGB(204, 0, 157)
Shadow_4.BorderSizePixel = 0
Shadow_4.Size = UDim2.new(1, 0, 1, 4)

UICorner_9.CornerRadius = UDim.new(0, 4)
UICorner_9.Parent = Shadow_4

TextLabel_4.Parent = CloseSlot2
TextLabel_4.AnchorPoint = Vector2.new(0.5, 0.5)
TextLabel_4.BackgroundColor3 = Color3.fromRGB(165, 10, 255)
TextLabel_4.BackgroundTransparency = 1.000
TextLabel_4.BorderColor3 = Color3.fromRGB(27, 42, 53)
TextLabel_4.BorderSizePixel = 0
TextLabel_4.Position = UDim2.new(0.5, 0, 0.5, 0)
TextLabel_4.Size = UDim2.new(1, -20, 1, -20)
TextLabel_4.ZIndex = 2
TextLabel_4.Font = Enum.Font.GothamSemibold
TextLabel_4.Text = "X"
TextLabel_4.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_4.TextScaled = true
TextLabel_4.TextSize = 14.000
TextLabel_4.TextWrapped = true

Slot3.Name = "Slot3"
Slot3.Parent = ScreenGui
Slot3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Slot3.BorderColor3 = Color3.fromRGB(27, 42, 53)
Slot3.BorderSizePixel = 0
Slot3.Position = UDim2.new(0.286282301, 0, 0.195222408, 0)
Slot3.Size = UDim2.new(0, 430, 0, 369)
Slot3.Visible = false
Slot3.Active = true
Slot3.Draggable = true

UIGradient_4.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(102, 45, 113)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(197, 66, 110))}
UIGradient_4.Parent = Slot3

UICorner_10.CornerRadius = UDim.new(0, 4)
UICorner_10.Parent = Slot3

Slot3title.Name = "Slot3title"
Slot3title.Parent = Slot3
Slot3title.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Slot3title.BackgroundTransparency = 1.000
Slot3title.Position = UDim2.new(0.267441869, 0, 0.032520324, 0)
Slot3title.Size = UDim2.new(0, 200, 0, 56)
Slot3title.Font = Enum.Font.SourceSansItalic
Slot3title.Text = "Slot 3 Section"
Slot3title.TextColor3 = Color3.fromRGB(255, 255, 255)
Slot3title.TextSize = 36.000

Slot3Frame.Name = "Slot3Frame"
Slot3Frame.Parent = Slot3
Slot3Frame.BackgroundColor3 = Color3.fromRGB(166, 0, 166)
Slot3Frame.Position = UDim2.new(0.132558137, 0, 0.216802165, 0)
Slot3Frame.Size = UDim2.new(0, 304, 0, 256)
Slot3Frame.Active = true
Slot3Frame.Draggable = false

Westlake3.Name = "Westlake3"
Westlake3.Parent = Slot3Frame
Westlake3.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Westlake3.Position = UDim2.new(0.190789476, 0, 0.046875, 0)
Westlake3.Size = UDim2.new(0, 200, 0, 50)
Westlake3.Font = Enum.Font.SourceSansBold
Westlake3.Text = "Westlake"
Westlake3.TextColor3 = Color3.fromRGB(255, 255, 255)
Westlake3.TextSize = 31.000
Westlake3.MouseButton1Down:connect(function()
	local slot = 3
	local option = 'west'


	--// Fast TP made by BoostedX#0001 \\--

	--options--

	--west
	--east
	--rec
	--lobby















	local east = 591582661
	local west = 593223204
	local rec = 594402678
	local lobby = 856966839




	local Player = game.Players.LocalPlayer
	local TPService = game:GetService("TeleportService")
	local Storage = game:GetService("ReplicatedStorage")
	local v16 = TPService:GetLocalPlayerTeleportData();
	wait(1)

	if option == 'west' then
		if game.PlaceId == west then return end
	elseif option == 'east' then 
		if game.PlaceId == east then return end
	elseif option == 'rec' then 
		if game.PlaceId == rec then return end
	elseif option == 'lobby' then 
		if game.PlaceId == lobby then return end
	end

	if option == 'west' then
		TPService:Teleport(west, Player, slot);
	elseif option == 'east' then
		TPService:Teleport(east, Player, slot);
	elseif option == 'rec' then 
		TPService:Teleport(rec, Player, slot);
	elseif option == 'lobby' then 
		TPService:Teleport(lobby, Player, slot);
	end
end)

Eastside3.Name = "Eastside3"
Eastside3.Parent = Slot3Frame
Eastside3.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Eastside3.Position = UDim2.new(0.190789476, 0, 0.28515625, 0)
Eastside3.Size = UDim2.new(0, 200, 0, 50)
Eastside3.Font = Enum.Font.SourceSansBold
Eastside3.Text = "Eastside"
Eastside3.TextColor3 = Color3.fromRGB(255, 255, 255)
Eastside3.TextSize = 31.000
Eastside3.MouseButton1Down:connect(function()
	local slot = 3
	local option = 'east'


	--// Fast TP made by BoostedX#0001 \\--

	--options--

	--west
	--east
	--rec
	--lobby















	local east = 591582661
	local west = 593223204
	local rec = 594402678
	local lobby = 856966839




	local Player = game.Players.LocalPlayer
	local TPService = game:GetService("TeleportService")
	local Storage = game:GetService("ReplicatedStorage")
	local v16 = TPService:GetLocalPlayerTeleportData();
	wait(1)

	if option == 'west' then
		if game.PlaceId == west then return end
	elseif option == 'east' then 
		if game.PlaceId == east then return end
	elseif option == 'rec' then 
		if game.PlaceId == rec then return end
	elseif option == 'lobby' then 
		if game.PlaceId == lobby then return end
	end

	if option == 'west' then
		TPService:Teleport(west, Player, slot);
	elseif option == 'east' then
		TPService:Teleport(east, Player, slot);
	elseif option == 'rec' then 
		TPService:Teleport(rec, Player, slot);
	elseif option == 'lobby' then 
		TPService:Teleport(lobby, Player, slot);
	end
end)

Rec3.Name = "Rec3"
Rec3.Parent = Slot3Frame
Rec3.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Rec3.Position = UDim2.new(0.190789476, 0, 0.51953125, 0)
Rec3.Size = UDim2.new(0, 200, 0, 50)
Rec3.Font = Enum.Font.SourceSansBold
Rec3.Text = "Rec. Center"
Rec3.TextColor3 = Color3.fromRGB(255, 255, 255)
Rec3.TextSize = 31.000
Rec3.MouseButton1Down:connect(function()
	local slot = 3
	local option = 'rec'


	--// Fast TP made by BoostedX#0001 \\--

	--options--

	--west
	--east
	--rec
	--lobby















	local east = 591582661
	local west = 593223204
	local rec = 594402678
	local lobby = 856966839




	local Player = game.Players.LocalPlayer
	local TPService = game:GetService("TeleportService")
	local Storage = game:GetService("ReplicatedStorage")
	local v16 = TPService:GetLocalPlayerTeleportData();
	wait(1)

	if option == 'west' then
		if game.PlaceId == west then return end
	elseif option == 'east' then 
		if game.PlaceId == east then return end
	elseif option == 'rec' then 
		if game.PlaceId == rec then return end
	elseif option == 'lobby' then 
		if game.PlaceId == lobby then return end
	end

	if option == 'west' then
		TPService:Teleport(west, Player, slot);
	elseif option == 'east' then
		TPService:Teleport(east, Player, slot);
	elseif option == 'rec' then 
		TPService:Teleport(rec, Player, slot);
	elseif option == 'lobby' then 
		TPService:Teleport(lobby, Player, slot);
	end
end)

Lobby3.Name = "Lobby3"
Lobby3.Parent = Slot3Frame
Lobby3.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Lobby3.Position = UDim2.new(0.190789476, 0, 0.74609375, 0)
Lobby3.Size = UDim2.new(0, 200, 0, 50)
Lobby3.Font = Enum.Font.SourceSansBold
Lobby3.Text = "Lobby"
Lobby3.TextColor3 = Color3.fromRGB(255, 255, 255)
Lobby3.TextSize = 31.000
Lobby3.MouseButton1Down:connect(function()
	local slot = 3
	local option = 'lobby'


	--// Fast TP made by BoostedX#0001 \\--

	--options--

	--west
	--east
	--rec
	--lobby















	local east = 591582661
	local west = 593223204
	local rec = 594402678
	local lobby = 856966839




	local Player = game.Players.LocalPlayer
	local TPService = game:GetService("TeleportService")
	local Storage = game:GetService("ReplicatedStorage")
	local v16 = TPService:GetLocalPlayerTeleportData();
	wait(1)

	if option == 'west' then
		if game.PlaceId == west then return end
	elseif option == 'east' then 
		if game.PlaceId == east then return end
	elseif option == 'rec' then 
		if game.PlaceId == rec then return end
	elseif option == 'lobby' then 
		if game.PlaceId == lobby then return end
	end

	if option == 'west' then
		TPService:Teleport(west, Player, slot);
	elseif option == 'east' then
		TPService:Teleport(east, Player, slot);
	elseif option == 'rec' then 
		TPService:Teleport(rec, Player, slot);
	elseif option == 'lobby' then 
		TPService:Teleport(lobby, Player, slot);
	end
end)

CloseSlot3.Name = "CloseSlot3"
CloseSlot3.Parent = Slot3
CloseSlot3.BackgroundColor3 = Color3.fromRGB(120, 1, 150)
CloseSlot3.BorderSizePixel = 0
CloseSlot3.Position = UDim2.new(0.802325606, 0, 0.032520324, 0)
CloseSlot3.Size = UDim2.new(0, 78, 0, 56)
CloseSlot3.ZIndex = 2
CloseSlot3.Font = Enum.Font.GothamSemibold
CloseSlot3.Text = ""
CloseSlot3.TextColor3 = Color3.fromRGB(255, 255, 255)
CloseSlot3.TextScaled = true
CloseSlot3.TextSize = 14.000
CloseSlot3.TextWrapped = true
CloseSlot3.MouseButton1Down:connect(function()
	Slot3.Visible = false
	MainFrame.Visible = true
end)

UICorner_11.CornerRadius = UDim.new(0, 4)
UICorner_11.Parent = CloseSlot3

Shadow_5.Name = "Shadow"
Shadow_5.Parent = CloseSlot3
Shadow_5.BackgroundColor3 = Color3.fromRGB(204, 0, 157)
Shadow_5.BorderSizePixel = 0
Shadow_5.Size = UDim2.new(1, 0, 1, 4)

UICorner_12.CornerRadius = UDim.new(0, 4)
UICorner_12.Parent = Shadow_5

TextLabel_5.Parent = CloseSlot3
TextLabel_5.AnchorPoint = Vector2.new(0.5, 0.5)
TextLabel_5.BackgroundColor3 = Color3.fromRGB(165, 10, 255)
TextLabel_5.BackgroundTransparency = 1.000
TextLabel_5.BorderColor3 = Color3.fromRGB(27, 42, 53)
TextLabel_5.BorderSizePixel = 0
TextLabel_5.Position = UDim2.new(0.5, 0, 0.5, 0)
TextLabel_5.Size = UDim2.new(1, -20, 1, -20)
TextLabel_5.ZIndex = 2
TextLabel_5.Font = Enum.Font.GothamSemibold
TextLabel_5.Text = "X"
TextLabel_5.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_5.TextScaled = true
TextLabel_5.TextSize = 14.000
TextLabel_5.TextWrapped = true
