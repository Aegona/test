-- Test ScriptAegonaHub [+] - GrabBox [+] FarmLevel

_G.HideHB = true
_G.ABC = false

local Toogle = Instance.new("ScreenGui")
local button = Instance.new("TextButton")
local UICorner = Instance.new("UICorner")
local ImageLabel = Instance.new("ImageLabel")

Toogle.Name = "Toogle"
Toogle.Parent = game.CoreGui
Toogle.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

button.Name = "button"
button.Parent = Toogle
button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
button.BorderSizePixel = 0
button.Position = UDim2.new(0.0477326959, 0, 0.469606668, 0)
button.Size = UDim2.new(0, 64, 0, 50)
button.Font = Enum.Font.SourceSans
button.TextColor3 = Color3.fromRGB(0, 0, 0)
button.TextSize = 14.000
button.MouseButton1Click:Connect(function()
	game.CoreGui:FindFirstChild("Discord").Enabled = not  game.CoreGui:FindFirstChild("Discord").Enabled
end)

UICorner.Parent = button

ImageLabel.Parent = button
ImageLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel.BorderSizePixel = 0
ImageLabel.Position = UDim2.new(0.125, 0, 0, 0)
ImageLabel.Size = UDim2.new(0, 48, 0, 50)
ImageLabel.Image = "http://www.roblox.com/asset/?id=2869969022"

function CheckQuest()
   local Lv =  game.Players.LocalPlayer.Data.Level.Value
   if game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Visible == true then
   elseif  Lv == 1 or Lv <= 9 then
       Ms = "Bandit [Lv. 5]"
       CQ = CFrame.new(1059.838623046875, 16.516624450683594, 1545.941162109375)
       CM = CFrame.new(1177.2108154296875, 16.43285369873047, 1616.587646484375)
       NQ = "BanditQuest1"
       NM = "Bandit"
       LQ = 1
   elseif Lv == 10 or Lv <= 14 then
       Ms = "Monkey [Lv. 14]"
       CQ = CFrame.new(-1601.58642578125, 36.852134704589844, 153.4748077392578)
       CM = CFrame.new(-1447.85400390625, 22.852529525756836, 224.74119567871094)
       NQ = "JungleQuest"
       NM = "Monkey"
       LQ = 1
   elseif Lv == 15 or Lv <= 29 then
            
       Ms = "Gorilla [Lv. 20]"
       CQ = CFrame.new(-1601.58642578125, 36.852134704589844, 153.4748077392578)
       CM = CFrame.new(-1226.2562255859375, 6.279374599456787, -490.89447021484375)
       NQ = "JungleQuest"
       NM = "Gorilla"
       LQ = 2

        elseif Lv == 30 or Lv <= 39 then
       Ms = "Pirate [Lv. 35]"
       CQ = CFrame.new(-1139.8831787109375, 4.752061367034912, 3824.586181640625)
       CM = CFrame.new(-1210.2435302734375, 4.752061367034912, 3918.926513671875)
       NQ = "BuggyQuest1"
       NM = "Pirate"
       LQ = 1

            elseif Lv == 40 or Lv <= 59 then
       Ms = "Brute [Lv. 45]"
       CQ = CFrame.new(-1139.8831787109375, 4.752061367034912, 3824.586181640625)
       CM = CFrame.new(-996.4336547851562, 14.869884490966797, 4305.337890625)
       NQ = "BuggyQuest1"
       NM = "Brute"
       LQ = 2

                   elseif Lv == 60 or Lv <= 74 then
       Ms = "Desert Bandit [Lv. 60]"
       CQ = CFrame.new(900.2313232421875, 6.513261318206787, 4385.94287109375)
       CM = CFrame.new(932.9173583984375, 6.450429439544678, 4463.5068359375)
       NQ = "DesertQuest"
       NM = "Desert Bandit"
       LQ = 1

               elseif Lv == 75 or Lv <= 89 then
       Ms = "Desert Officer [Lv. 70]"
       CQ = CFrame.new(900.2313232421875, 6.513261318206787, 4385.94287109375)
       CM = CFrame.new(1617.895263671875, 1.6109663248062134, 4367.8779296875)
       NQ = "DesertQuest"
       NM = "Desert Officer"
       LQ = 2

       elseif Lv == 90 or Lv <= 99 then
       Ms = "Snow Bandit [Lv. 90]"
       CQ = CFrame.new(1384.1134033203125, 87.27277374267578, -1298.09130859375)
       CM = CFrame.new(1340.1405029296875, 87.27277374267578, -1376.2293701171875)
       NQ = "SnowQuest"
       NM = "Snow Bandit"
       LQ = 1
       elseif Lv == 100 or Lv <= 119 then
       Ms = "Snowman [Lv. 100]"
       CQ = CFrame.new(1384.1134033203125, 87.27277374267578, -1298.09130859375)
       CM = CFrame.new(1202.4942626953125, 105.77490997314453, -1475.2557373046875)
       NQ = "SnowQuest"
       NM = "Snowman"
       LQ = 2
              elseif Lv == 119 or Lv <= 2298 then
       Ms = "Chief Petty Officer [Lv. 120]"
       CQ = CFrame.new(-5034.1435546875, 28.777360916137695, 4322.96142578125)
       CM = CFrame.new(-4891.8876953125, 20.777360916137695, 4070.431396484375)
       NQ = "MarineQuest2"
       NM = "MarineQuest2"
       LQ = 1
    end
end



function attack() -- AUTO ATTACK
    game:GetService'VirtualUser':CaptureController()
game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
end


function hitbox() -- HITBOX
    local enamie = game:GetService("Workspace").Enemies:GetChildren()
    
    for i,v in pairs(enamie) do
        v.HumanoidRootPart.Size = Vector3.new(100,100,100)
        v.HumanoidRootPart.CanCollide = true
        if _G.HideHB == true then
        v.HumanoidRootPart.Transparency = 1
        elseif _G.HideHB == false then
            v.HumanoidRootPart.Transparency = 0.5
            end
        end
    
end




local Weaponlist = {}
local Weapon = nil


--- guiลอย , toogle



local GUImove = Instance.new("ScreenGui")
local bg = Instance.new("Frame")
local TextLabel = Instance.new("TextLabel")


GUImove.Name = "GUImove"
GUImove.Parent = game.CoreGui
GUImove.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

bg.Name = "bg"
bg.Parent = GUImove
bg.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
bg.BackgroundTransparency = 0.500
bg.BorderSizePixel = 0
bg.Position = UDim2.new(0.354017496, 0, 0.249106064, 0)
bg.Size = UDim2.new(0, 498, 0, 30)

TextLabel.Parent = bg
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.Position = UDim2.new(-0.763052225, 0, 0, 0)
TextLabel.Size = UDim2.new(0, 1257, 0, 29)
TextLabel.Font = Enum.Font.SourceSansSemibold
TextLabel.Text = "AEGONA HUB FREE SCRIPT BLOXFRUIT "
TextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.TextScaled = true
TextLabel.TextSize = 14.000
TextLabel.TextWrapped = true

-- Scripts:

local function EMLIE_fake_script() -- bg.Script 
	local script = Instance.new('Script', bg)

	local Pic = script.Parent
	
	local xPosition = 1
	local speed = 0.0025
	while true do
		xPosition = xPosition - speed
		Pic.Position = UDim2.new(xPosition, 0, 0, 0)
		if xPosition < -0.1 then
			xPosition = 1
		end
		wait()
	end
end

coroutine.wrap(EMLIE_fake_script)()

function TP(P)
    NoClip = true
    Distance = (P.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
    if Distance < 10 then
        Speed = 1000
    elseif Distance < 170 then
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = P
        Speed = 360
    elseif Distance < 1000 then
        Speed = 360
    elseif Distance >= 1000 then
        Speed = 280
    end
    game:GetService("TweenService"):Create(
        game.Players.LocalPlayer.Character.HumanoidRootPart,
        TweenInfo.new(Distance/Speed, Enum.EasingStyle.Linear),
        {CFrame = P}
    ):Play()
    NoClip = false
end

spawn(function()
    while wait() do
        if _G.Farm then
            CheckQuest()
            if game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Visible == false then
                wait(.3)
                TP(CQ)
                wait(0.5)
                game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("StartQuest",NQ,LQ)
                
            elseif game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Visible == true then
                for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                    if v.Name == Ms then
                        posmon = v.HumanoidRootPart.CFrame
                        TP(v.HumanoidRootPart.CFrame * CFrame.new(0,25,0))
                        end
                    end
                end
            end    
        end
    end)

spawn(function()
    pcall(function()
        while task.wait() do
            if _G.Farm then
                if not game.Players.LocalPlayer.Character.HumanoidRootPart:FindFirstChild("BodyClip") then
                    local Noclip = Instance.new("BodyVelocity")
                    Noclip.Name = "BodyClip"
                    Noclip.Parent = game.Players.LocalPlayer.Character.HumanoidRootPart
                    Noclip.MaxForce = Vector3.new(100000,100000,100000)
                    Noclip.Velocity = Vector3.new(0,0,0)
                end
            else
                if game.Players.LocalPlayer.Character.HumanoidRootPart:FindFirstChild("BodyClip") then
                    game.Players.LocalPlayer.Character.HumanoidRootPart:FindFirstChild("BodyClip"):Destroy()
                end
            end
        end
    end)
end)



spawn(function()
    while task.wait() do
        if _G.Farm then
        for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
            if v.Name == Ms then
                v.HumanoidRootPart.CFrame = CM
                v.HumanoidRootPart.CanCollide = false
                sethiddenproperty(game.Players.LocalPlayer, "SimulationRadius", math.huge)
                end
            end
        end
    end
end)


             while _G.BringMob do wait()
            for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                 for i2,v2 in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
                    if v.Name == MON and v2.Name == MON then
                        v2.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame
                        v2.HumanoidRootPart.CanCollide = false
                           game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame * Method
                            sethiddenproperty(game.Players.LocalPlayer, "SimulationRadius", math.huge)
                    end
                 end
            end
             end
        

local Weaponlist = {}
local Weapon = nil

local DiscordLib = loadstring(game:HttpGet"https://raw.githubusercontent.com/dawid-scripts/UI-Libs/main/discord%20lib.txt")()
local win = DiscordLib:Window("AegonaHub")
local serv = win:Server("BLOXFRUIT", "")
local btns = serv:Channel("(> Auto-Farm <)")
local pt = serv:Channel("(> Point <)")

btns:Toggle("Auto-Farm",false, function(t)
_G.Farm = t
end)

btns:Toggle("BringMob",false, function(t)
_G.BringMob = t
end)

btns:Toggle("GrabBox",false, function(t)
_G.box1 = t
wait(3)
_G.box2 = t
wait(3)
_G.box3 = t
end)

pt:Toggle("Melee",false, function(t)
    while true do wait()
game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("AddPoint","Melee",1)
end
end)

pt:Toggle("Defense",false, function(t)
    while true do wait()
game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("AddPoint","Defense",1)
end
end)

pt:Toggle("Sword",false, function(t)
    while true do wait()
game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("AddPoint","Sword",1)
end
end)

pt:Toggle("Gun",false, function(t)
    while true do wait()
game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("AddPoint","Gun",1)
end
end)

pt:Toggle("BloxFruit",false, function(t)
    while true do wait()
game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("AddPoint","BloxFruit",1)
end
end)

btns:Toggle("FastAttck PC", false, function(value)
local CombatFramework = require(game:GetService("Players").LocalPlayer.PlayerScripts.CombatFramework)
local Camera = require(game.ReplicatedStorage.Util.CameraShaker)
Camera:Stop()
coroutine.wrap(function()
    game:GetService("RunService").Stepped:Connect(function()
        if getupvalues(CombatFramework)[2]['activeController'].timeToNextAttack then
            getupvalues(CombatFramework)[2]['activeController'].timeToNextAttack = 0
            getupvalues(CombatFramework)[2]['activeController'].hitboxMagnitude = 60
            getupvalues(CombatFramework)[2]['activeController']:attack()
        end
    end)
end)()
end)

btns:Toggle("FastAttck Mobile", false, function(value)
    _G.ABC = value
end)   
   
   spawn(function()
       while wait() do
       if _G.ABC then
    hitbox()
    attack()
       end
end
end)

spawn(function()
    while wait() do
        if _G.box1 then
            for i,v in pairs(game:GetService("Workspace").Chest1:GetDescendants()) do
    if v.Name == "TouchInterest" then
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.Parent.CFrame
        game.Players.LocalPlayer.Character.Humanoid.Health = 0
        
end
end
end
end
end)

spawn(function()
    while wait() do
        if _G.box2 then
            for i,v in pairs(game:GetService("Workspace").Chest2:GetDescendants()) do
    if v.Name == "TouchInterest" then
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.Parent.CFrame
        game.Players.LocalPlayer.Character.Humanoid.Health = 0
        
end
end
end
end
end)

spawn(function()
    while wait() do
        if _G.box3 then
            for i,v in pairs(game:GetService("Workspace").Chest3:GetDescendants()) do
    if v.Name == "TouchInterest" then
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.Parent.CFrame
        game.Players.LocalPlayer.Character.Humanoid.Health = 0
        
end
end
end
end
end)

 
