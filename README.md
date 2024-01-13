-- Gui to Lua
-- Version: 3.2

-- Instances:

local ScriptHa_k = Instance.new("ScreenGui")
local BG = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local Frame = Instance.new("Frame")
local UICorner_2 = Instance.new("UICorner")
local TextLabel = Instance.new("TextLabel")
local UIAspectRatioConstraint = Instance.new("UIAspectRatioConstraint")
local UITextSizeConstraint = Instance.new("UITextSizeConstraint")
local UIAspectRatioConstraint_2 = Instance.new("UIAspectRatioConstraint")
local TextBox = Instance.new("TextBox")
local UICorner_3 = Instance.new("UICorner")
local UIAspectRatioConstraint_3 = Instance.new("UIAspectRatioConstraint")
local UITextSizeConstraint_2 = Instance.new("UITextSizeConstraint")
local maru = Instance.new("TextButton")
local UICorner_4 = Instance.new("UICorner")
local UIAspectRatioConstraint_4 = Instance.new("UIAspectRatioConstraint")
local UITextSizeConstraint_3 = Instance.new("UITextSizeConstraint")
local sp = Instance.new("TextButton")
local UICorner_5 = Instance.new("UICorner")
local UIAspectRatioConstraint_5 = Instance.new("UIAspectRatioConstraint")
local UITextSizeConstraint_4 = Instance.new("UITextSizeConstraint")
local sub = Instance.new("TextButton")
local UIAspectRatioConstraint_6 = Instance.new("UIAspectRatioConstraint")
local UITextSizeConstraint_5 = Instance.new("UITextSizeConstraint")
local TextLabel_2 = Instance.new("TextLabel")
local UIAspectRatioConstraint_7 = Instance.new("UIAspectRatioConstraint")
local UITextSizeConstraint_6 = Instance.new("UITextSizeConstraint")
local UIAspectRatioConstraint_8 = Instance.new("UIAspectRatioConstraint")
local input = Instance.new("ImageButton")
local UICorner_6 = Instance.new("UICorner")
local UIAspectRatioConstraint_9 = Instance.new("UIAspectRatioConstraint")

--Properties:

ScriptHa_k.Name = "ScriptHa_k!"
ScriptHa_k.Parent = game.CoreGui
ScriptHa_k.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

BG.Name = "BG"
BG.Parent = ScriptHa_k
BG.BackgroundColor3 = Color3.fromRGB(38, 38, 38)
BG.BackgroundTransparency = 0.700
BG.BorderColor3 = Color3.fromRGB(0, 0, 0)
BG.BorderSizePixel = 0
BG.Position = UDim2.new(0.312180877, 0, 0.225728154, 0)
BG.Size = UDim2.new(0.375638217, 0, 0.564294577, 0)
BG.Visible = false

UICorner.Parent = BG

Frame.Parent = BG
Frame.BackgroundColor3 = Color3.fromRGB(38, 38, 38)
Frame.BackgroundTransparency = 0.700
Frame.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame.BorderSizePixel = 0
Frame.Position = UDim2.new(0.0155339809, 0, 0.0154867256, 0)
Frame.Size = UDim2.new(0.966990292, 0, 0.221238956, 0)

UICorner_2.Parent = Frame

TextLabel.Parent = Frame
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.BorderSizePixel = 0
TextLabel.Position = UDim2.new(0.0261044186, 0, 0.100000001, 0)
TextLabel.Size = UDim2.new(0.94979918, 0, 0.800000012, 0)
TextLabel.Font = Enum.Font.GothamBold
TextLabel.Text = "โปร Roblox"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextScaled = true
TextLabel.TextSize = 14.000
TextLabel.TextWrapped = true

UIAspectRatioConstraint.Parent = TextLabel
UIAspectRatioConstraint.AspectRatio = 5.912

UITextSizeConstraint.Parent = TextLabel
UITextSizeConstraint.MaxTextSize = 80

UIAspectRatioConstraint_2.Parent = Frame
UIAspectRatioConstraint_2.AspectRatio = 4.980

TextBox.Parent = BG
TextBox.BackgroundColor3 = Color3.fromRGB(53, 53, 53)
TextBox.BackgroundTransparency = 0.650
TextBox.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextBox.BorderSizePixel = 0
TextBox.Position = UDim2.new(0.0407766998, 0, 0.853982329, 0)
TextBox.Size = UDim2.new(0.941747546, 0, 0.103982307, 0)
TextBox.Font = Enum.Font.Unknown
TextBox.PlaceholderText = ">>> Script Here !"
TextBox.Text = ""
TextBox.TextColor3 = Color3.fromRGB(190, 190, 190)
TextBox.TextScaled = true
TextBox.TextSize = 14.000
TextBox.TextWrapped = true
TextBox.TextXAlignment = Enum.TextXAlignment.Left
TextBox.TextYAlignment = Enum.TextYAlignment.Top

UICorner_3.Parent = TextBox

UIAspectRatioConstraint_3.Parent = TextBox
UIAspectRatioConstraint_3.AspectRatio = 10.319

UITextSizeConstraint_2.Parent = TextBox
UITextSizeConstraint_2.MaxTextSize = 14

maru.Name = "maru"
maru.Parent = BG
maru.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
maru.BorderColor3 = Color3.fromRGB(0, 0, 0)
maru.BorderSizePixel = 0
maru.Position = UDim2.new(0.0407766998, 0, 0.285398245, 0)
maru.Size = UDim2.new(0.9184466, 0, 0.110619478, 0)
maru.Font = Enum.Font.SourceSans
maru.Text = "Maru Hub"
maru.TextColor3 = Color3.fromRGB(0, 0, 0)
maru.TextScaled = true
maru.TextSize = 14.000
maru.TextWrapped = true

UICorner_4.Parent = maru

UIAspectRatioConstraint_4.Parent = maru
UIAspectRatioConstraint_4.AspectRatio = 9.460

UITextSizeConstraint_3.Parent = maru
UITextSizeConstraint_3.MaxTextSize = 50

sp.Name = "sp"
sp.Parent = BG
sp.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
sp.BorderColor3 = Color3.fromRGB(0, 0, 0)
sp.BorderSizePixel = 0
sp.Position = UDim2.new(0.0407766998, 0, 0.444690257, 0)
sp.Size = UDim2.new(0.9184466, 0, 0.110619478, 0)
sp.Font = Enum.Font.SourceSans
sp.Text = "เสกRain !"
sp.TextColor3 = Color3.fromRGB(0, 0, 0)
sp.TextScaled = true
sp.TextSize = 14.000
sp.TextWrapped = true

UICorner_5.Parent = sp

UIAspectRatioConstraint_5.Parent = sp
UIAspectRatioConstraint_5.AspectRatio = 9.460

UITextSizeConstraint_4.Parent = sp
UITextSizeConstraint_4.MaxTextSize = 50

sub.Name = "sub"
sub.Parent = BG
sub.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
sub.BackgroundTransparency = 1.000
sub.BorderColor3 = Color3.fromRGB(0, 0, 0)
sub.BorderSizePixel = 0
sub.Position = UDim2.new(0.0407766998, 0, 0.816371679, 0)
sub.Size = UDim2.new(0.9184466, 0, 0.024336284, 0)
sub.Font = Enum.Font.Unknown
sub.Text = "- Submit -"
sub.TextColor3 = Color3.fromRGB(255, 255, 255)
sub.TextScaled = true
sub.TextSize = 14.000
sub.TextWrapped = true

UIAspectRatioConstraint_6.Parent = sub
UIAspectRatioConstraint_6.AspectRatio = 43.000

UITextSizeConstraint_5.Parent = sub
UITextSizeConstraint_5.MaxTextSize = 11

TextLabel_2.Parent = BG
TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.BackgroundTransparency = 1.000
TextLabel_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.BorderSizePixel = 0
TextLabel_2.Position = UDim2.new(0.0407766998, 0, 0.692477882, 0)
TextLabel_2.Size = UDim2.new(0.9184466, 0, 0.110619478, 0)
TextLabel_2.Visible = false
TextLabel_2.Font = Enum.Font.SourceSansBold
TextLabel_2.Text = "Command"
TextLabel_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.TextScaled = true
TextLabel_2.TextSize = 14.000
TextLabel_2.TextWrapped = true

UIAspectRatioConstraint_7.Parent = TextLabel_2
UIAspectRatioConstraint_7.AspectRatio = 9.460

UITextSizeConstraint_6.Parent = TextLabel_2
UITextSizeConstraint_6.MaxTextSize = 50

UIAspectRatioConstraint_8.Parent = BG
UIAspectRatioConstraint_8.AspectRatio = 1.139

input.Name = "input"
input.Parent = ScriptHa_k
input.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
input.BackgroundTransparency = 1.000
input.BorderColor3 = Color3.fromRGB(0, 0, 0)
input.BorderSizePixel = 0
input.Position = UDim2.new(0.0299051795, 0, 0.387135923, 0)
input.Size = UDim2.new(0.0488694385, 0, 0.0848938823, 0)
input.Image = "rbxassetid://14520700302"

UICorner_6.Parent = input

UIAspectRatioConstraint_9.Parent = input
UIAspectRatioConstraint_9.AspectRatio = 0.985

-- Scripts:

local function CUBDW_fake_script() -- maru.LocalScript 
	local script = Instance.new('LocalScript', maru)

	script.Parent.MouseButton1Click:Connect(function()
		game.Players.LocalPlayer.Humanoid.Health = 0
		wait(1)
		script.Parent.Parent.Parent.Parent["ScriptHa_k!"]:Destroy()
	end)
end
coroutine.wrap(CUBDW_fake_script)()
local function NBQQUS_fake_script() -- sp.LocalScript 
	local script = Instance.new('LocalScript', sp)

	function a()
		local Tool = Instance.new("Tool",workspace)	
		local apple = Instance.new("Part",Tool)
		local mesh = Instance.new("SpecialMesh",apple)
		Tool.Name = "Apple # Can't Eat"
		apple.Name = "Handle"
	
		apple.CanCollide = false
		mesh.TextureId = "http://www.roblox.com/asset/?id=125755118"
		mesh.MeshId = "http://www.roblox.com/asset/?id=125755971"
		apple.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,20,0)
		wait(0.1)
		game.Debris:AddItem(Tool,2)
	end
	
	
	script.Parent.MouseButton1Click:Connect(function()
		local PB = game.Players.LocalPlayer.Backpack
		
		while true do
			a()
		end
		
	end)
end
coroutine.wrap(NBQQUS_fake_script)()
local function CMAOYVG_fake_script() -- sub.LocalScript 
	local script = Instance.new('LocalScript', sub)

	script.Parent.MouseButton1Click:Connect(function(Test)
		local texbox = script.Parent.Parent.TextBox
		if texbox.Text == "WalkSpeed" then
			texbox.Text = " >>> How WalkSpeed?..."
			script.Parent.MouseButton1Click:Connect(function()
				game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = texbox.Text
				texbox.Text = " >>> You Wan't na reset your Code?"
				
				if texbox.Text == "Ok" then
					game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 16
					wait(2)
					texbox.Text = "Suscess!"
					print("yes")
					wait(1)
					
				elseif texbox.Text == "No" then
					print('no')
					texbox.Text = "Reset Text..."
					wait(0.2)
					texbox.Text = "Reset Text.."
					wait(0.2)
					texbox.Text = "Reset Text."
					wait(0.2)
					texbox.Text = "Reset Text"
					wait(0.2)
					texbox.Text = "Reset Text..."
					wait(0.2)
					texbox.Text = "Reset Text.."
					wait(0.2)
					texbox.Text = "Reset Text."
					wait(0.2)
					texbox.Text = "Reset Text"
					wait(0.2)
					texbox.Text = "Suscess!"
					wait(1)
					texbox.Text = " >>> Script Here !"
				end
			end)
		elseif texbox.Text == "New_Item" then
			texbox.PlaceholderText = "What Item?"
			script.Parent.MouseButton1Click:Connect(function()
				if texbox.Text == "Apple" then
					local PB = game.Players.LocalPlayer.Backpack
	
					local Tool = Instance.new("Tool",PB)	
					local apple = Instance.new("Part",Tool)
					local mesh = Instance.new("SpecialMesh",apple)
					Tool.Name = "Apple # Can't Eat"
					apple.Name = "Handle"
	
					apple.CanCollide = false
					mesh.TextureId = "http://www.roblox.com/asset/?id=125755118"
					mesh.MeshId = "http://www.roblox.com/asset/?id=125755971"
					mesh.Scale = "1,1,1"
					mesh.VertexColor = "1,1,1"
				else
					texbox.PlaceholderText = "NotFound!"
					wait(1)
					texbox.PlaceholderText = "Reset Text..."
					wait(0.2)
					texbox.PlaceholderText = "Reset Text.."
					wait(0.2)
					texbox.PlaceholderText = "Reset Text."
					wait(0.2)
					texbox.PlaceholderText = "Reset Text"
					wait(0.2)
					texbox.PlaceholderText = "Reset Text..."
					wait(0.2)
					texbox.PlaceholderText = "Reset Text.."
					wait(0.2)
					texbox.PlaceholderText = "Reset Text."
					wait(0.2)
					texbox.PlaceholderText = "Reset Text"
					wait(0.2)
					texbox.PlaceholderText = "Suscess!"
					wait(1)
					texbox.PlaceholderText = " >>> Script Here !"
				end
			end)
		end
		
	end)
end
coroutine.wrap(CMAOYVG_fake_script)()
local function TFPB_fake_script() -- input.LocalScript 
	local script = Instance.new('LocalScript', input)

	local button = script.Parent
	local BG = script.Parent.Parent.BG
	
	button.MouseButton1Click:Connect(function()
		if BG.Visible == false then
			BG.Visible = true
		elseif BG.Visible == true then
			BG.Visible = false
		end
	end)
end
coroutine.wrap(TFPB_fake_script)()
