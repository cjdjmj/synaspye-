
local ScreenGui = Instance.new("ScreenGui")
local Main = Instance.new("Frame")
local TextLabel = Instance.new("TextLabel")
local ImageLabel = Instance.new("ImageLabel")
local Execute = Instance.new("TextButton")
local UICorner = Instance.new("UICorner")
local Clear = Instance.new("TextButton")
local UICorner_2 = Instance.new("UICorner")
local OpenFile = Instance.new("TextButton")
local UICorner_3 = Instance.new("UICorner")
local ExecuteFile = Instance.new("TextButton")
local UICorner_4 = Instance.new("UICorner")
local SaveFile = Instance.new("TextButton")
local UICorner_5 = Instance.new("UICorner")
local Attach = Instance.new("TextButton")
local UICorner_6 = Instance.new("UICorner")
local ScriptHub = Instance.new("TextButton")
local UICorner_7 = Instance.new("UICorner")
local Code = Instance.new("TextBox")

--Properties:

ScreenGui.Parent = game.CoreGui
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Main.Name = "Main"
Main.Parent = ScreenGui
Main.BackgroundColor3 = Color3.fromRGB(45, 45, 45)
Main.Position = UDim2.new(0.148822755, 0, 0.267552167, 0)
Main.Size = UDim2.new(0, 730, 0, 302)
Main.Active = true
Main.Draggable = true

TextLabel.Parent = Main
TextLabel.BackgroundColor3 = Color3.fromRGB(59, 59, 59)
TextLabel.Size = UDim2.new(0, 730, 0, 42)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "Synaspye X"
TextLabel.TextColor3 = Color3.fromRGB(252, 252, 252)
TextLabel.TextSize = 17.000
TextLabel.TextStrokeColor3 = Color3.fromRGB(45, 45, 45)

ImageLabel.Parent = Main
ImageLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel.BackgroundTransparency = 1.000
ImageLabel.BorderColor3 = Color3.fromRGB(248, 248, 248)
ImageLabel.Position = UDim2.new(-0.0127737178, 0, -0.0200668741, 0)
ImageLabel.Size = UDim2.new(0, 50, 0, 48)
ImageLabel.Image = "http://www.roblox.com/asset/?id=6968191611"

Execute.Name = "Execute"
Execute.Parent = Main
Execute.BackgroundColor3 = Color3.fromRGB(59, 59, 59)
Execute.Position = UDim2.new(0.0181470644, 0, 0.839870453, 0)
Execute.Size = UDim2.new(0, 83, 0, 39)
Execute.Font = Enum.Font.SourceSans
Execute.Text = "Execute"
Execute.TextColor3 = Color3.fromRGB(255, 255, 255)
Execute.TextSize = 17.000

UICorner.Parent = Execute

Clear.Name = "Clear"
Clear.Parent = Main
Clear.BackgroundColor3 = Color3.fromRGB(59, 59, 59)
Clear.Position = UDim2.new(0.16565752, 0, 0.839870453, 0)
Clear.Size = UDim2.new(0, 83, 0, 39)
Clear.Font = Enum.Font.SourceSans
Clear.Text = "Clear"
Clear.TextColor3 = Color3.fromRGB(255, 255, 255)
Clear.TextSize = 17.000

UICorner_2.Parent = Clear

OpenFile.Name = "Open File"
OpenFile.Parent = Main
OpenFile.BackgroundColor3 = Color3.fromRGB(59, 59, 59)
OpenFile.Position = UDim2.new(0.311544865, 0, 0.839870453, 0)
OpenFile.Size = UDim2.new(0, 83, 0, 39)
OpenFile.Font = Enum.Font.SourceSans
OpenFile.Text = "Open File"
OpenFile.TextColor3 = Color3.fromRGB(255, 255, 255)
OpenFile.TextSize = 17.000

UICorner_3.Parent = OpenFile

ExecuteFile.Name = "Execute File"
ExecuteFile.Parent = Main
ExecuteFile.BackgroundColor3 = Color3.fromRGB(59, 59, 59)
ExecuteFile.Position = UDim2.new(0.455402851, 0, 0.839870453, 0)
ExecuteFile.Size = UDim2.new(0, 83, 0, 39)
ExecuteFile.Font = Enum.Font.SourceSans
ExecuteFile.Text = "Execute File"
ExecuteFile.TextColor3 = Color3.fromRGB(255, 255, 255)
ExecuteFile.TextSize = 17.000

UICorner_4.Parent = ExecuteFile

SaveFile.Name = "Save File"
SaveFile.Parent = Main
SaveFile.BackgroundColor3 = Color3.fromRGB(59, 59, 59)
SaveFile.Position = UDim2.new(0.593920708, 0, 0.839870453, 0)
SaveFile.Size = UDim2.new(0, 83, 0, 39)
SaveFile.Font = Enum.Font.SourceSans
SaveFile.Text = "Save File"
SaveFile.TextColor3 = Color3.fromRGB(255, 255, 255)
SaveFile.TextSize = 17.000

UICorner_5.Parent = SaveFile

Attach.Name = "Attach"
Attach.Parent = Main
Attach.BackgroundColor3 = Color3.fromRGB(59, 59, 59)
Attach.Position = UDim2.new(0.734413505, 0, 0.839870453, 0)
Attach.Size = UDim2.new(0, 83, 0, 39)
Attach.Font = Enum.Font.SourceSans
Attach.Text = "Attach"
Attach.TextColor3 = Color3.fromRGB(255, 255, 255)
Attach.TextSize = 17.000

UICorner_6.Parent = Attach

ScriptHub.Name = "Script Hub"
ScriptHub.Parent = Main
ScriptHub.BackgroundColor3 = Color3.fromRGB(59, 59, 59)
ScriptHub.Position = UDim2.new(0.872085929, 0, 0.839870453, 0)
ScriptHub.Size = UDim2.new(0, 83, 0, 39)
ScriptHub.Font = Enum.Font.SourceSans
ScriptHub.Text = "Script Hub"
ScriptHub.TextColor3 = Color3.fromRGB(255, 255, 255)
ScriptHub.TextSize = 17.000

UICorner_7.Parent = ScriptHub

Code.Name = "Code"
Code.Parent = Main
Code.BackgroundColor3 = Color3.fromRGB(67, 67, 67)
Code.BorderSizePixel = 0
Code.Position = UDim2.new(0, 0, 0.13907285, 0)
Code.Size = UDim2.new(0, 730, 0, 203)
Code.Font = Enum.Font.SourceSans
Code.Text = "-- By !IraqHavoc#9999"
Code.TextColor3 = Color3.fromRGB(98, 176, 61)
Code.TextSize = 18.000
Code.TextXAlignment = Enum.TextXAlignment.Left
Code.TextYAlignment = Enum.TextYAlignment.Top
--scripts
Execute.MouseButton1Down:connect(function()
	loadstring(Code.Text)
end)
Clear.MouseButton1Down:connect(function()
	Code.Text = ("")
end)
