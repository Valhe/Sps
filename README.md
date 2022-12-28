if game.PlaceId == 6875469709 then

local library = loadstring(game:HttpGet(('https://raw.githubusercontent.com/bloodball/-back-ups-for-libs/main/wall%20v3')))()

local w = library:CreateWindow("SPS - retpircS") -- Creates the window

local b = w:CreateFolder("Funciones") -- Creates the folder(U will put here your buttons,etc)

b:Label("Exploits",{
    TextSize = 25; -- Self Explaining
    TextColor = Color3.fromRGB(255,255,255); -- Self Explaining
    BgColor = Color3.fromRGB(69,69,69); -- Self Explaining
    
}) 

b:Button("AutoPunch",function()
    while true do
local args = {
    [1] = {
        [1] = "Activate_Punch"
    }
}

game:GetService("ReplicatedStorage").RemoteEvent:FireServer(unpack(args))
wait(0.2)

end
end)


end
