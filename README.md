
-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local OutlineDesignFrame = Instance.new("Frame")
local UIGradient = Instance.new("UIGradient")
local UICorner = Instance.new("UICorner")
local FastTPFrame = Instance.new("Frame")
local frametitle = Instance.new("TextLabel")
local HelpButton = Instance.new("TextButton")
local GoButton = Instance.new("TextButton")
local TextBox = Instance.new("TextBox")
local CloseButton = Instance.new("TextButton")
local UICorner_2 = Instance.new("UICorner")
local Shadow = Instance.new("Frame")
local UICorner_3 = Instance.new("UICorner")
local TextLabel = Instance.new("TextLabel")
local Slot1Frame = Instance.new("Frame")
local Frame = Instance.new("Frame")
local Slot1title = Instance.new("TextLabel")
local westlake1 = Instance.new("TextLabel")
local eastside1 = Instance.new("TextLabel")
local rec1 = Instance.new("TextLabel")
local lobby1 = Instance.new("TextLabel")
local CloseSlot1 = Instance.new("TextButton")
local Slot2Frame = Instance.new("Frame")
local Frame_2 = Instance.new("Frame")
local Slot2title = Instance.new("TextLabel")
local westlake2 = Instance.new("TextLabel")
local eastside2 = Instance.new("TextLabel")
local rec2 = Instance.new("TextLabel")
local lobby2 = Instance.new("TextLabel")
local CloseSlot2 = Instance.new("TextButton")
local Slot3Frame = Instance.new("Frame")
local Frame_3 = Instance.new("Frame")
local Slot3title = Instance.new("TextLabel")
local westlake3 = Instance.new("TextLabel")
local eastside3 = Instance.new("TextLabel")
local rec3 = Instance.new("TextLabel")
local lobby3 = Instance.new("TextLabel")
local CloseSlot3 = Instance.new("TextButton")

--Properties:

ScreenGui.Parent = game.CoreGui

OutlineDesignFrame.Name = "OutlineDesignFrame"
OutlineDesignFrame.Parent = ScreenGui
OutlineDesignFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
OutlineDesignFrame.BorderColor3 = Color3.fromRGB(27, 42, 53)
OutlineDesignFrame.BorderSizePixel = 0
OutlineDesignFrame.Position = UDim2.new(0.30417496, 0, 0.238056019, 0)
OutlineDesignFrame.Size = UDim2.new(0, 394, 0, 317)
OutlineDesignFrame.Active = true
OutlineDesignFrame.Draggable = true

UIGradient.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(45, 168, 182)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(64, 96, 161))}
UIGradient.Parent = OutlineDesignFrame

UICorner.CornerRadius = UDim.new(0, 4)
UICorner.Parent = OutlineDesignFrame

FastTPFrame.Name = "FastTPFrame"
FastTPFrame.Parent = OutlineDesignFrame
FastTPFrame.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
FastTPFrame.Position = UDim2.new(0.0380710661, 0, 0.0441640392, 0)
FastTPFrame.Size = UDim2.new(0, 361, 0, 292)
FastTPFrame.Active = true
FastTPFrame.Draggable = false

frametitle.Name = "frametitle"
frametitle.Parent = FastTPFrame
frametitle.BackgroundColor3 = Color3.fromRGB(0, 170, 255)
frametitle.Position = UDim2.new(0.221606642, 0, 0.0308219176, 0)
frametitle.Size = UDim2.new(0, 200, 0, 41)
frametitle.Font = Enum.Font.SciFi
frametitle.Text = "Hello! "..game.LocalPlayer.Player.Name 
frametitle.TextColor3 = Color3.fromRGB(0, 0, 0)
frametitle.TextScaled = true
frametitle.TextSize = 14.000
frametitle.TextWrapped = true

HelpButton.Name = "HelpButton"
HelpButton.Parent = FastTPFrame
HelpButton.BackgroundColor3 = Color3.fromRGB(0, 170, 255)
HelpButton.Position = UDim2.new(0.227146819, 0, 0.239726022, 0)
HelpButton.Size = UDim2.new(0, 200, 0, 50)
HelpButton.Font = Enum.Font.SciFi
HelpButton.Text = "Help!"
HelpButton.TextColor3 = Color3.fromRGB(0, 0, 0)
HelpButton.TextSize = 36.000
HelpButton.MouseButton1Down:connect(function()
	game:GetService("StarterGui"):SetCore("SendNotification", {Title = "Join our discord!", Text = "https://discord.io/NitroHacks"})
	wait(2)
	game:GetService("StarterGui"):SetCore("SendNotification", {Title = "Ask for help!", Text = "Create a support ticket!"})
	wait(2)
	game:GetService("StarterGui"):SetCore("SendNotification", {Title = "Invite link:", Text = "Discord invite link has been copied!"})
	wait(2)
	game:GetService("StarterGui"):SetCore("SendNotification", {Title = "Paste the link!", Text = "Into any browser click ctrl+v"})
	setclipboard("https://discord.io/NitroHacks")
end)

GoButton.Name = "GoButton"
GoButton.Parent = FastTPFrame
GoButton.BackgroundColor3 = Color3.fromRGB(0, 170, 255)
GoButton.Position = UDim2.new(0.221606657, 0, 0.486301363, 0)
GoButton.Size = UDim2.new(0, 200, 0, 50)
GoButton.Font = Enum.Font.SciFi
GoButton.Text = "GO!"
GoButton.TextColor3 = Color3.fromRGB(0, 0, 0)
GoButton.TextSize = 36.000
GoButton.MouseButton1Down:connect(function()
	if TextBox.Text == "Slot 1" then
		Slot1Frame.Visible = true
		OutlineDesignFrame.Visible = false
	elseif TextBox.Text == "Slot 2" then
		Slot2Frame.Visible = true
		OutlineDesignFrame.Visible = false
	elseif TextBox.Text == "Slot 3"	then
		Slot3Frame.Visible = true
		OutlineDesignFrame.Visible = false
	end
end)

TextBox.Parent = FastTPFrame
TextBox.BackgroundColor3 = Color3.fromRGB(0, 170, 255)
TextBox.Position = UDim2.new(0.227146819, 0, 0.732876718, 0)
TextBox.Size = UDim2.new(0, 200, 0, 50)
TextBox.Font = Enum.Font.SciFi
TextBox.Text = "Destination Here!"
TextBox.TextColor3 = Color3.fromRGB(0, 0, 0)
TextBox.TextScaled = true
TextBox.TextSize = 31.000
TextBox.TextWrapped = true

CloseButton.Name = "CloseButton"
CloseButton.Parent = FastTPFrame
CloseButton.BackgroundColor3 = Color3.fromRGB(77, 100, 150)
CloseButton.BorderSizePixel = 0
CloseButton.Position = UDim2.new(0.813019395, 0, 0.0308219176, 0)
CloseButton.Size = UDim2.new(0, 58, 0, 41)
CloseButton.ZIndex = 2
CloseButton.Font = Enum.Font.GothamSemibold
CloseButton.Text = ""
CloseButton.TextColor3 = Color3.fromRGB(255, 255, 255)
CloseButton.TextScaled = true
CloseButton.TextSize = 14.000
CloseButton.TextWrapped = true
CloseButton.MouseButton1Down:connect(function()
	OutlineDesignFrame.Visible = false
end)

UICorner_2.Parent = CloseButton

Shadow.Name = "Shadow"
Shadow.Parent = CloseButton
Shadow.BackgroundColor3 = Color3.fromRGB(53, 69, 103)
Shadow.BorderSizePixel = 0
Shadow.Size = UDim2.new(1, 0, 1, 4)

UICorner_3.Parent = Shadow

TextLabel.Parent = CloseButton
TextLabel.AnchorPoint = Vector2.new(0.5, 0.5)
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.BorderColor3 = Color3.fromRGB(27, 42, 53)
TextLabel.BorderSizePixel = 0
TextLabel.Position = UDim2.new(0.5, 0, 0.5, 0)
TextLabel.Size = UDim2.new(1, -20, 1, -20)
TextLabel.ZIndex = 2
TextLabel.Font = Enum.Font.GothamSemibold
TextLabel.Text = "X"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextScaled = true
TextLabel.TextSize = 14.000
TextLabel.TextWrapped = true

Slot1Frame.Name = "Slot1Frame"
Slot1Frame.Parent = ScreenGui
Slot1Frame.BackgroundColor3 = Color3.fromRGB(0, 170, 255)
Slot1Frame.Position = UDim2.new(0.268389672, 0, 0.181219116, 0)
Slot1Frame.Size = UDim2.new(0, 465, 0, 370)
Slot1Frame.Visible = false
Slot1Frame.Active = true
Slot1Frame.Draggable = true

Frame.Parent = Slot1Frame
Frame.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Frame.Position = UDim2.new(0.0430107526, 0, 0.0453257784, 0)
Frame.Size = UDim2.new(0, 423, 0, 342)
Frame.Active = true
Frame.Draggable = false

Slot1title.Name = "Slot1title"
Slot1title.Parent = Frame
Slot1title.BackgroundColor3 = Color3.fromRGB(0, 170, 255)
Slot1title.Position = UDim2.new(0.262411356, 0, 0.0312258657, 0)
Slot1title.Size = UDim2.new(0, 200, 0, 50)
Slot1title.Font = Enum.Font.SciFi
Slot1title.Text = "Slot 1 Section"
Slot1title.TextColor3 = Color3.fromRGB(0, 0, 0)
Slot1title.TextSize = 26.000

westlake1.Name = "westlake1"
westlake1.Parent = Frame
westlake1.BackgroundColor3 = Color3.fromRGB(0, 170, 255)
westlake1.Position = UDim2.new(0.262411356, 0, 0.215822563, 0)
westlake1.Size = UDim2.new(0, 200, 0, 50)
westlake1.Font = Enum.Font.SciFi
westlake1.Text = "Westlake"
westlake1.TextColor3 = Color3.fromRGB(0, 0, 0)
westlake1.TextSize = 26.000
westlake1.MouseButton1Down:connect(function()
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

eastside1.Name = "eastside1"
eastside1.Parent = Frame
eastside1.BackgroundColor3 = Color3.fromRGB(0, 170, 255)
eastside1.Position = UDim2.new(0.262411356, 0, 0.417521775, 0)
eastside1.Size = UDim2.new(0, 200, 0, 50)
eastside1.Font = Enum.Font.SciFi
eastside1.Text = "Eastside"
eastside1.TextColor3 = Color3.fromRGB(0, 0, 0)
eastside1.TextSize = 26.000
eastside1.MouseButton1Down:connect(function()
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

rec1.Name = "rec1"
rec1.Parent = Frame
rec1.BackgroundColor3 = Color3.fromRGB(0, 170, 255)
rec1.Position = UDim2.new(0.262411356, 0, 0.615634978, 0)
rec1.Size = UDim2.new(0, 200, 0, 50)
rec1.Font = Enum.Font.SciFi
rec1.Text = "Rec. Center"
rec1.TextColor3 = Color3.fromRGB(0, 0, 0)
rec1.TextSize = 26.000
rec1.MouseButton1Down:connect(function()
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

lobby1.Name = "lobby1"
lobby1.Parent = Frame
lobby1.BackgroundColor3 = Color3.fromRGB(0, 170, 255)
lobby1.Position = UDim2.new(0.262411356, 0, 0.817389369, 0)
lobby1.Size = UDim2.new(0, 200, 0, 50)
lobby1.Font = Enum.Font.SciFi
lobby1.Text = "Lobby"
lobby1.TextColor3 = Color3.fromRGB(0, 0, 0)
lobby1.TextSize = 26.000
lobby1.MouseButton1Down:connect(function()
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
CloseSlot1.Parent = Frame
CloseSlot1.BackgroundColor3 = Color3.fromRGB(0, 170, 255)
CloseSlot1.Position = UDim2.new(0.805999994, 0, 0.0289999992, 0)
CloseSlot1.Size = UDim2.new(0, 74, 0, 50)
CloseSlot1.Font = Enum.Font.SciFi
CloseSlot1.Text = "X"
CloseSlot1.TextColor3 = Color3.fromRGB(0, 0, 0)
CloseSlot1.TextScaled = true
CloseSlot1.TextSize = 14.000
CloseSlot1.TextWrapped = true
CloseSlot1.MouseButton1Down:connect(function()
	Slot1Frame.Visible = false
	OutlineDesignFrame.Visible = true
end)

Slot2Frame.Name = "Slot2Frame"
Slot2Frame.Parent = ScreenGui
Slot2Frame.BackgroundColor3 = Color3.fromRGB(0, 170, 255)
Slot2Frame.Position = UDim2.new(0.268389672, 0, 0.181219116, 0)
Slot2Frame.Size = UDim2.new(0, 465, 0, 370)
Slot2Frame.Visible = false
Slot2Frame.Active = true
Slot2Frame.Draggable = true

Frame_2.Parent = Slot2Frame
Frame_2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Frame_2.Position = UDim2.new(0.0430107526, 0, 0.0453257784, 0)
Frame_2.Size = UDim2.new(0, 423, 0, 342)
Frame_2.Active = true
Frame_2.Draggable = false

Slot2title.Name = "Slot2title"
Slot2title.Parent = Frame_2
Slot2title.BackgroundColor3 = Color3.fromRGB(0, 170, 255)
Slot2title.Position = UDim2.new(0.262411356, 0, 0.0312258657, 0)
Slot2title.Size = UDim2.new(0, 200, 0, 50)
Slot2title.Font = Enum.Font.SciFi
Slot2title.Text = "Slot 2 Section"
Slot2title.TextColor3 = Color3.fromRGB(0, 0, 0)
Slot2title.TextSize = 26.000

westlake2.Name = "westlake2"
westlake2.Parent = Frame_2
westlake2.BackgroundColor3 = Color3.fromRGB(0, 170, 255)
westlake2.Position = UDim2.new(0.262411356, 0, 0.215822563, 0)
westlake2.Size = UDim2.new(0, 200, 0, 50)
westlake2.Font = Enum.Font.SciFi
westlake2.Text = "Westlake"
westlake2.TextColor3 = Color3.fromRGB(0, 0, 0)
westlake2.TextSize = 26.000
westlake2.MouseButton1Down:connect(function()
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

eastside2.Name = "eastside2"
eastside2.Parent = Frame_2
eastside2.BackgroundColor3 = Color3.fromRGB(0, 170, 255)
eastside2.Position = UDim2.new(0.262411356, 0, 0.417521775, 0)
eastside2.Size = UDim2.new(0, 200, 0, 50)
eastside2.Font = Enum.Font.SciFi
eastside2.Text = "Eastside"
eastside2.TextColor3 = Color3.fromRGB(0, 0, 0)
eastside2.TextSize = 26.000
eastside2.MouseButton1Down:connect(function()
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

rec2.Name = "rec2"
rec2.Parent = Frame_2
rec2.BackgroundColor3 = Color3.fromRGB(0, 170, 255)
rec2.Position = UDim2.new(0.262411356, 0, 0.615634978, 0)
rec2.Size = UDim2.new(0, 200, 0, 50)
rec2.Font = Enum.Font.SciFi
rec2.Text = "Rec. Center"
rec2.TextColor3 = Color3.fromRGB(0, 0, 0)
rec2.TextSize = 26.000
rec2.MouseButton1Down:connect(function()
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

lobby2.Name = "lobby2"
lobby2.Parent = Frame_2
lobby2.BackgroundColor3 = Color3.fromRGB(0, 170, 255)
lobby2.Position = UDim2.new(0.262411356, 0, 0.817389369, 0)
lobby2.Size = UDim2.new(0, 200, 0, 50)
lobby2.Font = Enum.Font.SciFi
lobby2.Text = "Lobby"
lobby2.TextColor3 = Color3.fromRGB(0, 0, 0)
lobby2.TextSize = 26.000
lobby2.MouseButton1Down:connect(function()
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
CloseSlot2.Parent = Frame_2
CloseSlot2.BackgroundColor3 = Color3.fromRGB(0, 170, 255)
CloseSlot2.Position = UDim2.new(0.806146562, 0, 0.0292397663, 0)
CloseSlot2.Size = UDim2.new(0, 74, 0, 50)
CloseSlot2.Font = Enum.Font.SciFi
CloseSlot2.Text = "X"
CloseSlot2.TextColor3 = Color3.fromRGB(0, 0, 0)
CloseSlot2.TextScaled = true
CloseSlot2.TextSize = 14.000
CloseSlot2.TextWrapped = true
CloseSlot2.MouseButton1Down:connect(function()
	Slot2Frame.Visible = false
	OutlineDesignFrame.Visible = true
end)

Slot3Frame.Name = "Slot3Frame"
Slot3Frame.Parent = ScreenGui
Slot3Frame.BackgroundColor3 = Color3.fromRGB(0, 170, 255)
Slot3Frame.Position = UDim2.new(0.268389672, 0, 0.181219116, 0)
Slot3Frame.Size = UDim2.new(0, 465, 0, 370)
Slot3Frame.Visible = false
Slot3Frame.Active = true
Slot3Frame.Draggable = true

Frame_3.Parent = Slot3Frame
Frame_3.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Frame_3.Position = UDim2.new(0.0430107526, 0, 0.0453257784, 0)
Frame_3.Size = UDim2.new(0, 423, 0, 342)
Frame_3.Active = true
Frame_3.Draggable = false

Slot3title.Name = "Slot3title"
Slot3title.Parent = Frame_3
Slot3title.BackgroundColor3 = Color3.fromRGB(0, 170, 255)
Slot3title.Position = UDim2.new(0.262411356, 0, 0.0312258657, 0)
Slot3title.Size = UDim2.new(0, 200, 0, 50)
Slot3title.Font = Enum.Font.SciFi
Slot3title.Text = "Slot 3 Section"
Slot3title.TextColor3 = Color3.fromRGB(0, 0, 0)
Slot3title.TextSize = 26.000

westlake3.Name = "westlake3"
westlake3.Parent = Frame_3
westlake3.BackgroundColor3 = Color3.fromRGB(0, 170, 255)
westlake3.Position = UDim2.new(0.262411356, 0, 0.215822563, 0)
westlake3.Size = UDim2.new(0, 200, 0, 50)
westlake3.Font = Enum.Font.SciFi
westlake3.Text = "Westlake"
westlake3.TextColor3 = Color3.fromRGB(0, 0, 0)
westlake3.TextSize = 26.000
westlake3.MouseButton1Down:connect(function()
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

eastside3.Name = "eastside3"
eastside3.Parent = Frame_3
eastside3.BackgroundColor3 = Color3.fromRGB(0, 170, 255)
eastside3.Position = UDim2.new(0.262411356, 0, 0.417521775, 0)
eastside3.Size = UDim2.new(0, 200, 0, 50)
eastside3.Font = Enum.Font.SciFi
eastside3.Text = "Eastside"
eastside3.TextColor3 = Color3.fromRGB(0, 0, 0)
eastside3.TextSize = 26.000
eastside3.MouseButton1Down:connect(function()
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

rec3.Name = "rec3"
rec3.Parent = Frame_3
rec3.BackgroundColor3 = Color3.fromRGB(0, 170, 255)
rec3.Position = UDim2.new(0.262411356, 0, 0.615634978, 0)
rec3.Size = UDim2.new(0, 200, 0, 50)
rec3.Font = Enum.Font.SciFi
rec3.Text = "Rec. Center"
rec3.TextColor3 = Color3.fromRGB(0, 0, 0)
rec3.TextSize = 26.000
rec3.MouseButton1Down:connect(function()
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

lobby3.Name = "lobby3"
lobby3.Parent = Frame_3
lobby3.BackgroundColor3 = Color3.fromRGB(0, 170, 255)
lobby3.Position = UDim2.new(0.262411356, 0, 0.817389369, 0)
lobby3.Size = UDim2.new(0, 200, 0, 50)
lobby3.Font = Enum.Font.SciFi
lobby3.Text = "Lobby"
lobby3.TextColor3 = Color3.fromRGB(0, 0, 0)
lobby3.TextSize = 26.000
lobby3.MouseButton1Down:connect(function()
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
CloseSlot3.Parent = Frame_3
CloseSlot3.BackgroundColor3 = Color3.fromRGB(0, 170, 255)
CloseSlot3.Position = UDim2.new(0.806146562, 0, 0.0292397663, 0)
CloseSlot3.Size = UDim2.new(0, 74, 0, 50)
CloseSlot3.Font = Enum.Font.SciFi
CloseSlot3.Text = "X"
CloseSlot3.TextColor3 = Color3.fromRGB(0, 0, 0)
CloseSlot3.TextScaled = true
CloseSlot3.TextSize = 14.000
CloseSlot3.TextWrapped = true
CloseSlot3.MouseButton1Down:connect(function()
	Slot3Frame.Visible = false
	OutlineDesignFrame.Visible = true
end)
