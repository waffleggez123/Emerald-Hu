local EmeraldHUB = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local White = Instance.new("TextButton")
local UICorner = Instance.new("UICorner")
local black = Instance.new("TextButton")
local red = Instance.new("TextButton")
local yellow = Instance.new("TextButton")
local pueple = Instance.new("TextButton")
local green = Instance.new("TextButton")
local blue = Instance.new("TextButton")
local Admin1 = Instance.new("TextButton")
local Admin2 = Instance.new("TextButton")
local HackBuildABoatForTreasureByEmeraldHUB = Instance.new("TextBox")

EmeraldHUB.Name = "Emerald HUB"
EmeraldHUB.Parent = game.CoreGui
EmeraldHUB.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Frame.Parent = EmeraldHUB
Frame.BackgroundColor3 = Color3.fromRGB(25, 255, 148)
Frame.BorderColor3 = Color3.fromRGB(33, 31, 23)
Frame.Position = UDim2.new(0.205108359, 0, 0.0244798046, 0)
Frame.Size = UDim2.new(0, 383, 0, 598)

White.Name = "White"
White.Parent = Frame
White.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
White.Position = UDim2.new(0, 0, 0.0150501672, 0)
White.Size = UDim2.new(0, 200, 0, 50)
White.Font = Enum.Font.SourceSans
White.Text = "White"
White.TextColor3 = Color3.fromRGB(0, 0, 0)
White.TextSize = 14.000
White.MouseButton1Down:connect(function()
	local TweenService = game:GetService("TweenService")

	local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(2, Enum.EasingStyle.Linear, Enum.EasingDirection.Out,0,false,0),
		{CFrame = CFrame.new(-54.20122528076172, 38.59809494018555, 38.39418029785156)}):Play()
	_G.WARO = true
	wait(2)

	local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(15, Enum.EasingStyle.Linear, Enum.EasingDirection.Out,0,false,0),
		{CFrame = CFrame.new(-162.6615753173828, 114.38322448730469, 8732.8681640625)}):Play()
	_G.WARO = true
	wait(14)

	local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(2, Enum.EasingStyle.Linear, Enum.EasingDirection.Out,0,false,0),
		{CFrame = CFrame.new(-55.72788619995117, -360.4100646972656, 9489.38671875)}):Play()
end)

UICorner.Parent = Frame

black.Name = "black"
black.Parent = Frame
black.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
black.Position = UDim2.new(0, 0, 0.14046824, 0)
black.Size = UDim2.new(0, 200, 0, 50)
black.Font = Enum.Font.SourceSans
black.Text = "black"
black.TextColor3 = Color3.fromRGB(0, 0, 0)
black.TextSize = 14.000
black.MouseButton1Down:connect(function()
	local TweenService = game:GetService("TweenService")

	local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(2, Enum.EasingStyle.Linear, Enum.EasingDirection.Out,0,false,0),
		{CFrame = CFrame.new(-32.724937438964844, 35.59797668457031, -64.70987701416016)}):Play()
	_G.WARO = true
	wait(2)

	local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(18, Enum.EasingStyle.Linear, Enum.EasingDirection.Out,0,false,0),
		{CFrame = CFrame.new(-162.6615753173828, 114.38322448730469, 8732.8681640625)}):Play()
	_G.WARO = true
	wait(18)

	local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(3, Enum.EasingStyle.Linear, Enum.EasingDirection.Out,0,false,0),
		{CFrame = CFrame.new(-55.72788619995117, -360.4100646972656, 9489.38671875)}):Play()
end)

red.Name = "red"
red.Parent = Frame
red.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
red.Position = UDim2.new(0, 0, 0.265886307, 0)
red.Size = UDim2.new(0, 200, 0, 50)
red.Font = Enum.Font.SourceSans
red.Text = "red"
red.TextColor3 = Color3.fromRGB(0, 0, 0)
red.TextSize = 14.000
red.MouseButton1Down:connect(function()
	local TweenService = game:GetService("TweenService")

	local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(2, Enum.EasingStyle.Linear, Enum.EasingDirection.Out,0,false,0),
		{CFrame = CFrame.new(-57.39373779296875, 38.59823989868164, -67.10887908935547)}):Play()
	_G.WARO = true
	wait(2)

	local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(18, Enum.EasingStyle.Linear, Enum.EasingDirection.Out,0,false,0),
		{CFrame = CFrame.new(-162.6615753173828, 114.38322448730469, 8732.8681640625)}):Play()
	_G.WARO = true
	wait(18)

	local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(3, Enum.EasingStyle.Linear, Enum.EasingDirection.Out,0,false,0),
		{CFrame = CFrame.new(-55.72788619995117, -360.4100646972656, 9489.38671875)}):Play()
end)

yellow.Name = "yellow"
yellow.Parent = Frame
yellow.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
yellow.Position = UDim2.new(0, 0, 0.384615421, 0)
yellow.Size = UDim2.new(0, 200, 0, 50)
yellow.Font = Enum.Font.SourceSans
yellow.Text = "yellow"
yellow.TextColor3 = Color3.fromRGB(0, 0, 0)
yellow.TextSize = 14.000
yellow.MouseButton1Down:connect(function()
	local TweenService = game:GetService("TweenService")

	local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(2, Enum.EasingStyle.Linear, Enum.EasingDirection.Out,0,false,0),
		{CFrame = CFrame.new(-59.27516555786133, 38.59823226928711, 649.7964477539062)}):Play()
	_G.WARO = true
	wait(2)

	local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(18, Enum.EasingStyle.Linear, Enum.EasingDirection.Out,0,false,0),
		{CFrame = CFrame.new(-162.6615753173828, 114.38322448730469, 8732.8681640625)}):Play()
	_G.WARO = true
	wait(18)

	local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(3, Enum.EasingStyle.Linear, Enum.EasingDirection.Out,0,false,0),
		{CFrame = CFrame.new(-55.72788619995117, -360.4100646972656, 9489.38671875)}):Play()
end)

pueple.Name = "pueple"
pueple.Parent = Frame
pueple.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
pueple.Position = UDim2.new(0, 0, 0.50000006, 0)
pueple.Size = UDim2.new(0, 200, 0, 50)
pueple.Font = Enum.Font.SourceSans
pueple.Text = "pueple"
pueple.TextColor3 = Color3.fromRGB(0, 0, 0)
pueple.TextSize = 14.000
pueple.MouseButton1Down:connect(function()
	local TweenService = game:GetService("TweenService")

	local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(2, Enum.EasingStyle.Linear, Enum.EasingDirection.Out,0,false,0),
		{CFrame = CFrame.new(-60.45097351074219, 38.59823989868164, 647.97607421875)}):Play()
	_G.WARO = true
	wait(2)

	local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(18, Enum.EasingStyle.Linear, Enum.EasingDirection.Out,0,false,0),
		{CFrame = CFrame.new(-162.6615753173828, 114.38322448730469, 8732.8681640625)}):Play()
	_G.WARO = true
	wait(18)

	local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(3, Enum.EasingStyle.Linear, Enum.EasingDirection.Out,0,false,0),
		{CFrame = CFrame.new(-55.72788619995117, -360.4100646972656, 9489.38671875)}):Play()
end)

green.Name = "green"
green.Parent = Frame
green.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
green.Position = UDim2.new(0, 0, 0.62207365, 0)
green.Size = UDim2.new(0, 200, 0, 50)
green.Font = Enum.Font.SourceSans
green.Text = "green"
green.TextColor3 = Color3.fromRGB(0, 0, 0)
green.TextSize = 14.000
green.MouseButton1Down:connect(function()
	local TweenService = game:GetService("TweenService")

	local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(2, Enum.EasingStyle.Linear, Enum.EasingDirection.Out,0,false,0),
		{CFrame = CFrame.new(-64.93089294433594, 38.59842300415039, 285.4038391113281)}):Play()
	_G.WARO = true
	wait(2)

	local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(18, Enum.EasingStyle.Linear, Enum.EasingDirection.Out,0,false,0),
		{CFrame = CFrame.new(-162.6615753173828, 114.38322448730469, 8732.8681640625)}):Play()
	_G.WARO = true
	wait(18)

	local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(3, Enum.EasingStyle.Linear, Enum.EasingDirection.Out,0,false,0),
		{CFrame = CFrame.new(-55.72788619995117, -360.4100646972656, 9489.38671875)}):Play()
end)

blue.Name = "blue"
blue.Parent = Frame
blue.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
blue.Position = UDim2.new(0, 0, 0.744147241, 0)
blue.Size = UDim2.new(0, 200, 0, 50)
blue.Font = Enum.Font.SourceSans
blue.Text = "blue"
blue.TextColor3 = Color3.fromRGB(0, 0, 0)
blue.TextSize = 14.000
blue.MouseButton1Down:connect(function()
	local TweenService = game:GetService("TweenService")

	local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(2, Enum.EasingStyle.Linear, Enum.EasingDirection.Out,0,false,0),
		{CFrame = CFrame.new(-58.11162185668945, 38.59823226928711, 290.84100341796875)}):Play()
	_G.WARO = true
	wait(2)

	local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(18, Enum.EasingStyle.Linear, Enum.EasingDirection.Out,0,false,0),
		{CFrame = CFrame.new(-162.6615753173828, 114.38322448730469, 8732.8681640625)}):Play()
	_G.WARO = true
	wait(18)

	local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(3, Enum.EasingStyle.Linear, Enum.EasingDirection.Out,0,false,0),
		{CFrame = CFrame.new(-55.72788619995117, -360.4100646972656, 9489.38671875)}):Play()
end)

Admin1.Name = "Admin 1"
Admin1.Parent = Frame
Admin1.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Admin1.Position = UDim2.new(0, 0, 0.916387975, 0)
Admin1.Size = UDim2.new(0, 194, 0, 50)
Admin1.Font = Enum.Font.SourceSans
Admin1.Text = "Admin 1"
Admin1.TextColor3 = Color3.fromRGB(0, 0, 0)
Admin1.TextSize = 14.000
Admin1.MouseButton1Down:connect(function()
	local AnnGUI = Instance.new("Frame")
	local background = Instance.new("Frame")
	local TextBox = Instance.new("TextLabel")
	local shadow = Instance.new("Frame")
	local PopupText = Instance.new("TextLabel")
	local Exit = Instance.new("ImageButton")

	screenGui = Instance.new("ScreenGui",game.CoreGui)

	AnnGUI.Name = 'Boomer'
	AnnGUI.Parent = screenGui
	AnnGUI.Active = true
	AnnGUI.BackgroundTransparency = 1
	AnnGUI.Position = UDim2.new(0.5, -180, 0, -400)
	AnnGUI.Size = UDim2.new(0, 360, 0, 20)
	AnnGUI.ZIndex = 4

	background.Name = "background"
	background.Parent = AnnGUI
	background.BackgroundColor3 = Color3.fromRGB(36, 36, 37)
	background.BorderSizePixel = 0
	background.Position = UDim2.new(0, 0, 0, 20)
	background.Size = UDim2.new(0, 360, 0, 135)

	TextBox.Parent = background
	TextBox.BackgroundTransparency = 1
	TextBox.Position = UDim2.new(0.017, 0, 0.06, 0)
	TextBox.Size = UDim2.new(0, 348, 0, 120)
	TextBox.Font = Enum.Font.SourceSans
	TextBox.TextSize = 18
	TextBox.TextWrapped = true
	TextBox.Text = 'Please use the new Infinite Yield loadstring. You can find it in the Discord.\n\ndiscord.io/infiniteyield\n\nYou will now be re-directed to the new loadstring.'
	TextBox.TextColor3 = Color3.new(1, 1, 1)
	TextBox.TextXAlignment = Enum.TextXAlignment.Left
	TextBox.TextYAlignment = Enum.TextYAlignment.Top

	shadow.Name = "shadow"
	shadow.Parent = AnnGUI
	shadow.BackgroundColor3 = Color3.fromRGB(46, 46, 47)
	shadow.BorderSizePixel = 0
	shadow.Size = UDim2.new(0, 360, 0, 20)
	shadow.ZIndex = 4

	PopupText.Name = "PopupText"
	PopupText.Parent = shadow
	PopupText.BackgroundTransparency = 1
	PopupText.Position = UDim2.new(0, 51, 0, 0)
	PopupText.Size = UDim2.new(0.76, -16, 0.95, 0)
	PopupText.ZIndex = 4
	PopupText.Font = Enum.Font.SourceSans
	PopupText.TextSize = 14
	PopupText.Text = "Server Announcement"
	PopupText.TextColor3 = Color3.new(1, 1, 1)
	PopupText.TextWrapped = true

	Exit.Name = "Exit"
	Exit.Parent = shadow
	Exit.BackgroundTransparency = 1
	Exit.Size = UDim2.new(0, 20, 0, 20)
	Exit.ZIndex = 4
	Exit.Image = "rbxassetid://2132544126"

	wait(1)
	AnnGUI:TweenPosition(UDim2.new(0.5, -180, 0, 150), "InOut", "Quart", 0.5, true, nil)

	Exit.MouseButton1Click:Connect(function()
		AnnGUI:TweenPosition(UDim2.new(0.5, -180, 0, -400), "InOut", "Quart", 0.5, true, nil)
		wait(0.6)
		AnnGUI:Destroy()
	end)

	wait(5)
	loadstring(game:HttpGet(('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'),true))()
end)

Admin2.Name = "Admin 2"
Admin2.Parent = Frame
Admin2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Admin2.Position = UDim2.new(0.545691907, 0, 0.916387975, 0)
Admin2.Size = UDim2.new(0, 174, 0, 50)
Admin2.Font = Enum.Font.SourceSans
Admin2.Text = "Admin 2"
Admin2.TextColor3 = Color3.fromRGB(0, 0, 0)
Admin2.TextSize = 14.000
Admin2.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/CMD-X/CMD-X/master/Source",true))()
end)












----------------------------------------------------------



do
    local ToggleUi = game.CoreGui:FindFirstChild("Emerald")
	if ToggleUi then 
		 ToggleUi:Destory()
         end
    end
local Emerald = Instance.new("ScreenGui")
local EmeraldHUB = Instance.new("TextButton")
local UICorner = Instance.new("UICorner")

Emerald.Name = "Emerald"
Emerald.Parent = game.CoreGui
Emerald.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

EmeraldHUB.Name = "Emerald HUB"
EmeraldHUB.Parent = Emerald
EmeraldHUB.BackgroundColor3 = Color3.fromRGB(0, 255, 0)
EmeraldHUB.Position = UDim2.new(0.0944272354, 0, 0.225214198, 0)
EmeraldHUB.Size = UDim2.new(0, 116, 0, 70)
EmeraldHUB.Font = Enum.Font.SpecialElite
EmeraldHUB.Text = "Emerald"
EmeraldHUB.TextColor3 = Color3.fromRGB(0, 0, 0)
EmeraldHUB.TextSize = 14.000
EmeraldHUB.MouseButton1Down:connect(function()
game.CoreGui:FindFirstChild("Emerald HUB").Enabled = not game.CoreGui:FindFirstChild("Emerald HUB").Enabled
end)
UICorner.Parent = EmeraldHUB
