
local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local TextButton = Instance.new("TextButton")

--Properties:

ScreenGui.Parent = game.CoreGui

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Frame.Position = UDim2.new(0.147, 0, 0.199, 0)
Frame.Size = UDim2.new(0, 138, 0, 63)
Frame.Active = true
Frame.Draggable = False

TextButton.Parent = ScreenGui
TextButton.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
TextButton.BorderSizePixel = 3
TextButton.Position = UDim2.new(0.147, 0, 0.199, 0)
TextButton.Size = UDim2.new(0, 138, 0, 63)
TextButton.Font = Enum.Font.SourceSans
TextButton.Text = "Teleport Ke Atas"
TextButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton.TextSize = 17.000
TextButton.MouseButton1Down:connect(function()
	local pl = game.Players.LocalPlayer.Character.HumanoidRootPart
	local location = CFrame.new(29.7983475, 203.776627, -161.593323, 0.999224901, 4.28119371e-08, 0.0393646099, -4.27766302e-08, 1, -1.73919423e-09, -0.0393646099, 5.39608705e-11, 0.999224901)
	local humanoid = game.Players.LocalPlayer.Character.Humanoid
	humanoid:ChangeState(Enum.HumanoidStateType.Jumping)
	wait(0.1)
	pl.CFrame = location
end)
