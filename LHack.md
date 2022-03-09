local PlaceId = game.PlaceId
local ScreenGui = Instance.new("ScreenGui")
local Logo = Instance.new("TextLabel")
--ScreenGui.Parent = game.CoreGui
ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
Logo.BackgroundTransparency = 1
Logo.Position = UDim2.new(0.457, 0,0.478, 0)
Logo.Size = UDim2.new(0.084, 0,0.042, 0)
Logo.Font = Enum.Font.SourceSansBold
Logo.Text = "B A D H U B"
Logo.TextSize = 27
Logo.TextStrokeTransparency = 1
Logo.TextTransparency = 1
Logo.TextColor3 = Color3.fromRGB(255, 255, 255)
Logo.TextScaled = true
Logo.TextXAlignment = Enum.TextXAlignment.Center
Logo.Parent = ScreenGui
Logo.ZIndex = 100
local blur = Instance.new("BlurEffect", game.Lighting)
blur.Size = 0
repeat
	wait(0.01)
	blur.Size = blur.Size + 1
until blur.Size == 24
wait(1)
Logo.TextTransparency = 0.9
wait(0.025)
Logo.TextTransparency = 0.8
wait(0.025)
Logo.TextTransparency = 0.7
wait(0.025)
Logo.TextTransparency = 0.6
wait(0.025)
Logo.TextTransparency = 0.5
wait(0.025)
Logo.TextTransparency = 0.4
wait(0.025)
Logo.TextTransparency = 0.3
wait(0.025)
Logo.TextTransparency = 0.2
wait(0.025)
Logo.TextTransparency = 0.1
wait(0.025)
Logo.TextTransparency = 0
wait(2)
Logo.TextTransparency = 0.1
wait(0.025)
Logo.TextTransparency = 0.2
wait(0.025)
Logo.TextTransparency = 0.3
wait(0.025)
Logo.TextTransparency = 0.4
wait(0.025)
Logo.TextTransparency = 0.5
wait(0.025)
Logo.TextTransparency = 0.6
wait(0.025)
Logo.TextTransparency = 0.7
wait(0.025)
Logo.TextTransparency = 0.8
wait(0.025)
Logo.TextTransparency = 0.9
wait(0.025)
Logo.TextTransparency = 1
repeat
	wait(0.01)
	game.Lighting.Blur.Size = game.Lighting.Blur.Size - 1
until game.Lighting.Blur.Size == 0
blur:Destroy()
wait(0.5)
if PlaceId == 8645723106 then
        loadstring(game:HttpGet(('https://raw.githubusercontent.com/idkfffff/kkk/main/kkkk'),true))()
	wait(2)
	ScreenGui:Destroy()
else
	game.Players.LocalPlayer:kick("Sus")
	wait(2)
	game:Shutdown()
end
