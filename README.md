local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("OP SCRIPT HUB", "DarkTheme")

--MAIN
local Main = Window:NewTab("Main")
local MainSection = Main:NewSection("Main")


MainSection:NewButton("cmd x", "is a very cool gui", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/CMD-X/CMD-X/master/Source", true))()
end)


MainSection:NewButton("fates admin", "fuck off", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/fatesc/fates-admin/main/main.lua"))();
end)


MainSection:NewButton("vhub", "vhub very cool gui", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/SourceScript5315/sauce/main/VH-Launcher.lua"))()
end)


MainSection:NewButton("hypertotal gui", "very cool guii", function()
    -- Credit to Timeless/xFunnieuss for the partial names/short names

-- Objects

local HyperTotal = Instance.new("ScreenGui")
local MainFrame = Instance.new("Frame")
local TopFrame = Instance.new("Frame")
local Title = Instance.new("TextLabel")
local EnterUsername = Instance.new("TextBox")
local CloseGUI = Instance.new("TextButton")
local CreditTXT = Instance.new("TextLabel")
local Sections = Instance.new("Frame")
local INTRO = Instance.new("Frame")
local FE_CHECK = Instance.new("TextLabel")
local Guide1 = Instance.new("TextLabel")
local Guide2 = Instance.new("TextLabel")
local Credit = Instance.new("TextLabel")
local RocketPropulsion = Instance.new("Frame")
local ROCKETPROPULSIONGUIDE = Instance.new("TextLabel")
local Push = Instance.new("TextButton")
local Flatten = Instance.new("TextButton")
local Float = Instance.new("TextButton")
local Max = Instance.new("TextButton")
local AimHead = Instance.new("TextButton")
local SlowAttract = Instance.new("TextButton")
local Experimental = Instance.new("TextButton")
local Multiple = Instance.new("TextButton")
local Teleportation = Instance.new("Frame")
local TELEPORTATIONGUIDE = Instance.new("TextLabel")
local TeleportTo = Instance.new("TextButton")
local LockOn = Instance.new("TextButton")
local LockArm = Instance.new("TextButton")
local LockLeg = Instance.new("TextButton")
local LockHead = Instance.new("TextButton")
local LockMax = Instance.new("TextButton")
local LockAbove = Instance.new("TextButton")
local Trail = Instance.new("TextButton")
local Tools = Instance.new("Frame")
local TOOLSGUIDE = Instance.new("TextLabel")
local Kill = Instance.new("TextButton")
local KillSurvive = Instance.new("TextButton")
local Attach = Instance.new("TextButton")
local Bring = Instance.new("TextButton")
local SuperSpin = Instance.new("TextButton")
local FreeFall = Instance.new("TextButton")
local AttachExperimental = Instance.new("TextButton")
local GiveTool = Instance.new("TextButton")
local Basic = Instance.new("Frame")
local BASICGUIDE = Instance.new("TextLabel")
local Speed = Instance.new("TextButton")
local JumpHeight = Instance.new("TextButton")
local Chat = Instance.new("TextButton")
local Spam = Instance.new("TextButton")
local Fly = Instance.new("TextButton")
local Noclip = Instance.new("TextButton")
local HipHeight = Instance.new("TextButton")
local STATCHANGE = Instance.new("TextBox")
local CHATBOX = Instance.new("TextBox")
local Local_Player = Instance.new("Frame")
local Local_PlayerGUIDE = Instance.new("TextLabel")
local CrazySpin = Instance.new("TextButton")
local CrouchRocket = Instance.new("TextButton")
local Haunted = Instance.new("TextButton")
local CloneIllusion = Instance.new("TextButton")
local Levitate = Instance.new("TextButton")
local Dinosaur = Instance.new("TextButton")
local Glitchy = Instance.new("TextButton")
local NoLimbs = Instance.new("TextButton")
local Animations = Instance.new("Frame")
local ANIMATIONSGUIDE = Instance.new("TextLabel")
local _18 = Instance.new("TextButton")
local Hide = Instance.new("TextButton")
local PushLock = Instance.new("TextButton")
local SlamOn = Instance.new("TextButton")
local LevitateOn = Instance.new("TextButton")
local Dance = Instance.new("TextButton")
local ExperimentalAnimation = Instance.new("TextButton")
local Carpet = Instance.new("TextButton")
local Extra = Instance.new("Frame")
local EXTRAGUIDE = Instance.new("TextLabel")
local Sit = Instance.new("TextButton")
local Jump = Instance.new("TextButton")
local PlatformStand = Instance.new("TextButton")
local Freeze = Instance.new("TextButton")
local Insane = Instance.new("TextButton")
local TPVoid = Instance.new("TextButton")
local Unknown = Instance.new("TextButton")
local Reset = Instance.new("TextButton")
local SelectTabs = Instance.new("ScrollingFrame")
local RocketPropulsionTAB = Instance.new("TextButton")
local TeleportationTAB = Instance.new("TextButton")
local ToolsTAB = Instance.new("TextButton")
local AnimationsTAB = Instance.new("TextButton")
local BasicTAB = Instance.new("TextButton")
local Local_PlayerTAB = Instance.new("TextButton")
local ExtraTAB = Instance.new("TextButton")
local SideTopFrame = Instance.new("Frame")
local SideTitle = Instance.new("TextLabel")
local OpenGUI = Instance.new("TextButton")
local SideCreditTXT = Instance.new("TextLabel")
local SideFrame = Instance.new("Frame")
local BrickFrame = Instance.new("Frame")

-- Properties

HyperTotal.Name = "HyperTotal"
HyperTotal.Parent = game.CoreGui

MainFrame.Name = "MainFrame"
MainFrame.Parent = HyperTotal
MainFrame.Active = true
MainFrame.BackgroundColor3 = Color3.new(1, 1, 1)
MainFrame.BackgroundTransparency = 1
MainFrame.Draggable = true
MainFrame.Position = UDim2.new(0.348623842, 0, 1, 0)
MainFrame.Size = UDim2.new(0, 350, 0, 270)

TopFrame.Name = "TopFrame"
TopFrame.Parent = MainFrame
TopFrame.BackgroundColor3 = Color3.new(0.121569, 0.121569, 0.121569)
TopFrame.BorderColor3 = Color3.new(0.121569, 0.121569, 0.121569)
TopFrame.BorderSizePixel = 2
TopFrame.Position = UDim2.new(-0.286500663, 0, 0, 0)
TopFrame.Size = UDim2.new(0, 450, 0, 40)
TopFrame.ZIndex = 9

Title.Name = "Title"
Title.Parent = TopFrame
Title.BackgroundColor3 = Color3.new(1, 1, 1)
Title.BackgroundTransparency = 1
Title.Position = UDim2.new(0.356534153, 0, 0, 0)
Title.Size = UDim2.new(0, 150, 0, 40)
Title.ZIndex = 10
Title.Font = Enum.Font.SourceSansItalic
Title.FontSize = Enum.FontSize.Size36
Title.Text = "HyperTotal"
Title.TextColor3 = Color3.new(0.933333, 0.670588, 0.0509804)
Title.TextSize = 35
Title.TextWrapped = true

EnterUsername.Name = "EnterUsername"
EnterUsername.Parent = TopFrame
EnterUsername.BackgroundColor3 = Color3.new(1, 1, 1)
EnterUsername.BorderColor3 = Color3.new(0.968628, 0.698039, 0.0588235)
EnterUsername.BorderSizePixel = 2
EnterUsername.Position = UDim2.new(0.0199999996, 0, 0.200000003, 0)
EnterUsername.Size = UDim2.new(0, 120, 0, 24)
EnterUsername.ZIndex = 10
EnterUsername.Font = Enum.Font.SourceSans
EnterUsername.FontSize = Enum.FontSize.Size14
EnterUsername.Text = ""
EnterUsername.TextScaled = true
EnterUsername.TextSize = 14
EnterUsername.TextWrapped = true

CloseGUI.Name = "CloseGUI"
CloseGUI.Parent = TopFrame
CloseGUI.BackgroundColor3 = Color3.new(1, 1, 1)
CloseGUI.BackgroundTransparency = 1
CloseGUI.Position = UDim2.new(0.913618803, 0, 0, 0)
CloseGUI.Size = UDim2.new(0, 40, 0, 40)
CloseGUI.ZIndex = 10
CloseGUI.Font = Enum.Font.SourceSansBold
CloseGUI.FontSize = Enum.FontSize.Size60
CloseGUI.Text = "X"
CloseGUI.TextColor3 = Color3.new(1, 0.631373, 0.109804)
CloseGUI.TextSize = 50
CloseGUI.TextWrapped = true

CreditTXT.Name = "CreditTXT"
CreditTXT.Parent = TopFrame
CreditTXT.BackgroundColor3 = Color3.new(1, 1, 1)
CreditTXT.BackgroundTransparency = 1
CreditTXT.Position = UDim2.new(0.690784931, 0, 0.250416666, 0)
CreditTXT.Rotation = -17
CreditTXT.Size = UDim2.new(0, 90, 0, 20)
CreditTXT.ZIndex = 10
CreditTXT.Font = Enum.Font.SourceSansItalic
CreditTXT.FontSize = Enum.FontSize.Size24
CreditTXT.Text = "illremember"
CreditTXT.TextColor3 = Color3.new(0.933333, 0.819608, 0.737255)
CreditTXT.TextSize = 20
CreditTXT.TextWrapped = true

Sections.Name = "Sections"
Sections.Parent = MainFrame
Sections.BackgroundColor3 = Color3.new(0.278431, 0.278431, 0.278431)
Sections.BackgroundTransparency = 1
Sections.BorderColor3 = Color3.new(0.121569, 0.121569, 0.121569)
Sections.BorderSizePixel = 2
Sections.Position = UDim2.new(0, 0, 0.148395061, 0)
Sections.Size = UDim2.new(0, 350, 0, 230)

INTRO.Name = "INTRO"
INTRO.Parent = Sections
INTRO.BackgroundColor3 = Color3.new(0.278431, 0.278431, 0.278431)
INTRO.BorderColor3 = Color3.new(0.121569, 0.121569, 0.121569)
INTRO.BorderSizePixel = 2
INTRO.Size = UDim2.new(0, 350, 0, 230)

FE_CHECK.Name = "FE_CHECK"
FE_CHECK.Parent = INTRO
FE_CHECK.BackgroundColor3 = Color3.new(1, 1, 1)
FE_CHECK.BackgroundTransparency = 1
FE_CHECK.Position = UDim2.new(0.0286500659, 0, 0.0435507223, 0)
FE_CHECK.Size = UDim2.new(0, 332, 0, 50)
FE_CHECK.Font = Enum.Font.ArialBold
FE_CHECK.FontSize = Enum.FontSize.Size14
FE_CHECK.Text = "Error loading FE Checker"
FE_CHECK.TextScaled = true
FE_CHECK.TextSize = 14
FE_CHECK.TextWrapped = true

Guide1.Name = "Guide1"
Guide1.Parent = INTRO
Guide1.BackgroundColor3 = Color3.new(1, 1, 1)
Guide1.BackgroundTransparency = 1
Guide1.Position = UDim2.new(0.0286500659, 0, 0.653260887, 0)
Guide1.Size = UDim2.new(0, 332, 0, 80)
Guide1.Font = Enum.Font.ArialBold
Guide1.FontSize = Enum.FontSize.Size14
Guide1.Text = "Click on one of the sections to the left to begin exploiting FE Sections! Enter a name in the textbox (top left) to affect that player. You don't have to write their full username."
Guide1.TextScaled = true
Guide1.TextSize = 14
Guide1.TextStrokeColor3 = Color3.new(0.831373, 0.831373, 0.831373)
Guide1.TextStrokeTransparency = 0.5
Guide1.TextWrapped = true

Guide2.Name = "Guide2"
Guide2.Parent = INTRO
Guide2.BackgroundColor3 = Color3.new(1, 1, 1)
Guide2.BackgroundTransparency = 1
Guide2.Position = UDim2.new(0.0286500659, 0, 0.217753619, 0)
Guide2.Size = UDim2.new(0, 332, 0, 50)
Guide2.Font = Enum.Font.ArialBold
Guide2.FontSize = Enum.FontSize.Size14
Guide2.Text = "This GUI is dedicated to exploiting FE Sections, affecting yourself and others"
Guide2.TextScaled = true
Guide2.TextSize = 14
Guide2.TextStrokeColor3 = Color3.new(1, 0.658824, 0.0666667)
Guide2.TextStrokeTransparency = 0
Guide2.TextWrapped = true

Credit.Name = "Credit"
Credit.Parent = INTRO
Credit.BackgroundColor3 = Color3.new(1, 1, 1)
Credit.BackgroundTransparency = 1
Credit.Position = UDim2.new(0.0286500659, 0, 0.435507238, 0)
Credit.Size = UDim2.new(0, 332, 0, 50)
Credit.Font = Enum.Font.ArialBold
Credit.FontSize = Enum.FontSize.Size14
Credit.Text = "By illremember"
Credit.TextColor3 = Color3.new(0.92549, 0.607843, 0.0901961)
Credit.TextScaled = true
Credit.TextSize = 14
Credit.TextStrokeColor3 = Color3.new(1, 0.658824, 0.0666667)
Credit.TextWrapped = true

RocketPropulsion.Name = "RocketPropulsion"
RocketPropulsion.Parent = Sections
RocketPropulsion.BackgroundColor3 = Color3.new(0.278431, 0.278431, 0.278431)
RocketPropulsion.BorderColor3 = Color3.new(0.121569, 0.121569, 0.121569)
RocketPropulsion.BorderSizePixel = 2
RocketPropulsion.Size = UDim2.new(0, 350, 0, 230)
RocketPropulsion.Visible = false

ROCKETPROPULSIONGUIDE.Name = "ROCKETPROPULSIONGUIDE"
ROCKETPROPULSIONGUIDE.Parent = RocketPropulsion
ROCKETPROPULSIONGUIDE.BackgroundColor3 = Color3.new(1, 1, 1)
ROCKETPROPULSIONGUIDE.BackgroundTransparency = 1
ROCKETPROPULSIONGUIDE.Position = UDim2.new(0.0286500659, 0, 0.0435507223, 0)
ROCKETPROPULSIONGUIDE.Size = UDim2.new(0, 332, 0, 35)
ROCKETPROPULSIONGUIDE.Font = Enum.Font.ArialBold
ROCKETPROPULSIONGUIDE.FontSize = Enum.FontSize.Size14
ROCKETPROPULSIONGUIDE.Text = "Fling and push others, works best in a group of people."
ROCKETPROPULSIONGUIDE.TextScaled = true
ROCKETPROPULSIONGUIDE.TextSize = 14
ROCKETPROPULSIONGUIDE.TextStrokeColor3 = Color3.new(1, 0.658824, 0.0666667)
ROCKETPROPULSIONGUIDE.TextStrokeTransparency = 0
ROCKETPROPULSIONGUIDE.TextWrapped = true

Push.Name = "Push"
Push.Parent = RocketPropulsion
Push.BackgroundColor3 = Color3.new(0.854902, 0.854902, 0.854902)
Push.BorderColor3 = Color3.new(0.941177, 0.701961, 0.133333)
Push.Position = UDim2.new(0.0286500659, 0, 0.261304349, 0)
Push.Size = UDim2.new(0, 140, 0, 25)
Push.Font = Enum.Font.SourceSans
Push.FontSize = Enum.FontSize.Size14
Push.Text = "Push"
Push.TextScaled = true
Push.TextSize = 14
Push.TextWrapped = true

Flatten.Name = "Flatten"
Flatten.Parent = RocketPropulsion
Flatten.BackgroundColor3 = Color3.new(0.854902, 0.854902, 0.854902)
Flatten.BorderColor3 = Color3.new(0.941177, 0.701961, 0.133333)
Flatten.Position = UDim2.new(0.54435122, 0, 0.261304349, 0)
Flatten.Size = UDim2.new(0, 140, 0, 25)
Flatten.Font = Enum.Font.SourceSans
Flatten.FontSize = Enum.FontSize.Size14
Flatten.Text = "Flatten"
Flatten.TextScaled = true
Flatten.TextSize = 14
Flatten.TextWrapped = true

Float.Name = "Float"
Float.Parent = RocketPropulsion
Float.BackgroundColor3 = Color3.new(0.854902, 0.854902, 0.854902)
Float.BorderColor3 = Color3.new(0.941177, 0.701961, 0.133333)
Float.Position = UDim2.new(0.54435122, 0, 0.435507238, 0)
Float.Size = UDim2.new(0, 140, 0, 25)
Float.Font = Enum.Font.SourceSans
Float.FontSize = Enum.FontSize.Size14
Float.Text = "Float"
Float.TextScaled = true
Float.TextSize = 14
Float.TextWrapped = true

Max.Name = "Max"
Max.Parent = RocketPropulsion
Max.BackgroundColor3 = Color3.new(0.854902, 0.854902, 0.854902)
Max.BorderColor3 = Color3.new(0.941177, 0.701961, 0.133333)
Max.Position = UDim2.new(0.0286500659, 0, 0.435507238, 0)
Max.Size = UDim2.new(0, 140, 0, 25)
Max.Font = Enum.Font.SourceSans
Max.FontSize = Enum.FontSize.Size14
Max.Text = "Max"
Max.TextScaled = true
Max.TextSize = 14
Max.TextWrapped = true

AimHead.Name = "AimHead"
AimHead.Parent = RocketPropulsion
AimHead.BackgroundColor3 = Color3.new(0.854902, 0.854902, 0.854902)
AimHead.BorderColor3 = Color3.new(0.941177, 0.701961, 0.133333)
AimHead.Position = UDim2.new(0.0286500659, 0, 0.609710157, 0)
AimHead.Size = UDim2.new(0, 140, 0, 25)
AimHead.Font = Enum.Font.SourceSans
AimHead.FontSize = Enum.FontSize.Size14
AimHead.Text = "AimHead"
AimHead.TextScaled = true
AimHead.TextSize = 14
AimHead.TextWrapped = true

SlowAttract.Name = "SlowAttract"
SlowAttract.Parent = RocketPropulsion
SlowAttract.BackgroundColor3 = Color3.new(0.854902, 0.854902, 0.854902)
SlowAttract.BorderColor3 = Color3.new(0.941177, 0.701961, 0.133333)
SlowAttract.Position = UDim2.new(0.54435122, 0, 0.609710157, 0)
SlowAttract.Size = UDim2.new(0, 140, 0, 25)
SlowAttract.Font = Enum.Font.SourceSans
SlowAttract.FontSize = Enum.FontSize.Size14
SlowAttract.Text = "SlowAttract"
SlowAttract.TextScaled = true
SlowAttract.TextSize = 14
SlowAttract.TextWrapped = true

Experimental.Name = "Experimental"
Experimental.Parent = RocketPropulsion
Experimental.BackgroundColor3 = Color3.new(0.854902, 0.854902, 0.854902)
Experimental.BorderColor3 = Color3.new(0.941177, 0.701961, 0.133333)
Experimental.Position = UDim2.new(0.54435122, 0, 0.783913076, 0)
Experimental.Size = UDim2.new(0, 140, 0, 25)
Experimental.Font = Enum.Font.SourceSans
Experimental.FontSize = Enum.FontSize.Size14
Experimental.Text = "Experimental"
Experimental.TextScaled = true
Experimental.TextSize = 14
Experimental.TextWrapped = true

Multiple.Name = "Multiple"
Multiple.Parent = RocketPropulsion
Multiple.BackgroundColor3 = Color3.new(0.854902, 0.854902, 0.854902)
Multiple.BorderColor3 = Color3.new(0.941177, 0.701961, 0.133333)
Multiple.Position = UDim2.new(0.0286500659, 0, 0.783913076, 0)
Multiple.Size = UDim2.new(0, 140, 0, 25)
Multiple.Font = Enum.Font.SourceSans
Multiple.FontSize = Enum.FontSize.Size14
Multiple.Text = "Multiple"
Multiple.TextScaled = true
Multiple.TextSize = 14
Multiple.TextWrapped = true

Teleportation.Name = "Teleportation"
Teleportation.Parent = Sections
Teleportation.BackgroundColor3 = Color3.new(0.278431, 0.278431, 0.278431)
Teleportation.BorderColor3 = Color3.new(0.121569, 0.121569, 0.121569)
Teleportation.BorderSizePixel = 2
Teleportation.Size = UDim2.new(0, 350, 0, 230)
Teleportation.Visible = false

TELEPORTATIONGUIDE.Name = "TELEPORTATIONGUIDE"
TELEPORTATIONGUIDE.Parent = Teleportation
TELEPORTATIONGUIDE.BackgroundColor3 = Color3.new(1, 1, 1)
TELEPORTATIONGUIDE.BackgroundTransparency = 1
TELEPORTATIONGUIDE.Position = UDim2.new(0.0286500659, 0, 0.0435507223, 0)
TELEPORTATIONGUIDE.Size = UDim2.new(0, 332, 0, 35)
TELEPORTATIONGUIDE.Font = Enum.Font.ArialBold
TELEPORTATIONGUIDE.FontSize = Enum.FontSize.Size14
TELEPORTATIONGUIDE.Text = "Teleport to and annoy other players."
TELEPORTATIONGUIDE.TextScaled = true
TELEPORTATIONGUIDE.TextSize = 14
TELEPORTATIONGUIDE.TextStrokeColor3 = Color3.new(1, 0.658824, 0.0666667)
TELEPORTATIONGUIDE.TextStrokeTransparency = 0
TELEPORTATIONGUIDE.TextWrapped = true

TeleportTo.Name = "TeleportTo"
TeleportTo.Parent = Teleportation
TeleportTo.BackgroundColor3 = Color3.new(0.854902, 0.854902, 0.854902)
TeleportTo.BorderColor3 = Color3.new(0.941177, 0.701961, 0.133333)
TeleportTo.Position = UDim2.new(0.0286500659, 0, 0.261304349, 0)
TeleportTo.Size = UDim2.new(0, 140, 0, 25)
TeleportTo.Font = Enum.Font.SourceSans
TeleportTo.FontSize = Enum.FontSize.Size14
TeleportTo.Text = "Teleport To"
TeleportTo.TextScaled = true
TeleportTo.TextSize = 14
TeleportTo.TextWrapped = true

LockOn.Name = "LockOn"
LockOn.Parent = Teleportation
LockOn.BackgroundColor3 = Color3.new(0.854902, 0.854902, 0.854902)
LockOn.BorderColor3 = Color3.new(0.941177, 0.701961, 0.133333)
LockOn.Position = UDim2.new(0.54435122, 0, 0.261304349, 0)
LockOn.Size = UDim2.new(0, 140, 0, 25)
LockOn.Font = Enum.Font.SourceSans
LockOn.FontSize = Enum.FontSize.Size14
LockOn.Text = "Lock On"
LockOn.TextScaled = true
LockOn.TextSize = 14
LockOn.TextWrapped = true

LockArm.Name = "LockArm"
LockArm.Parent = Teleportation
LockArm.BackgroundColor3 = Color3.new(0.854902, 0.854902, 0.854902)
LockArm.BorderColor3 = Color3.new(0.941177, 0.701961, 0.133333)
LockArm.Position = UDim2.new(0.54435122, 0, 0.435507238, 0)
LockArm.Size = UDim2.new(0, 140, 0, 25)
LockArm.Font = Enum.Font.SourceSans
LockArm.FontSize = Enum.FontSize.Size14
LockArm.Text = "Lock Arm"
LockArm.TextScaled = true
LockArm.TextSize = 14
LockArm.TextWrapped = true

LockLeg.Name = "LockLeg"
LockLeg.Parent = Teleportation
LockLeg.BackgroundColor3 = Color3.new(0.854902, 0.854902, 0.854902)
LockLeg.BorderColor3 = Color3.new(0.941177, 0.701961, 0.133333)
LockLeg.Position = UDim2.new(0.0286500659, 0, 0.435507238, 0)
LockLeg.Size = UDim2.new(0, 140, 0, 25)
LockLeg.Font = Enum.Font.SourceSans
LockLeg.FontSize = Enum.FontSize.Size14
LockLeg.Text = "Lock Leg"
LockLeg.TextScaled = true
LockLeg.TextSize = 14
LockLeg.TextWrapped = true

LockHead.Name = "LockHead"
LockHead.Parent = Teleportation
LockHead.BackgroundColor3 = Color3.new(0.854902, 0.854902, 0.854902)
LockHead.BorderColor3 = Color3.new(0.941177, 0.701961, 0.133333)
LockHead.Position = UDim2.new(0.0286500659, 0, 0.609710157, 0)
LockHead.Size = UDim2.new(0, 140, 0, 25)
LockHead.Font = Enum.Font.SourceSans
LockHead.FontSize = Enum.FontSize.Size14
LockHead.Text = "LockHead"
LockHead.TextScaled = true
LockHead.TextSize = 14
LockHead.TextWrapped = true

LockMax.Name = "LockMax"
LockMax.Parent = Teleportation
LockMax.BackgroundColor3 = Color3.new(0.854902, 0.854902, 0.854902)
LockMax.BorderColor3 = Color3.new(0.941177, 0.701961, 0.133333)
LockMax.Position = UDim2.new(0.54435122, 0, 0.609710157, 0)
LockMax.Size = UDim2.new(0, 140, 0, 25)
LockMax.Font = Enum.Font.SourceSans
LockMax.FontSize = Enum.FontSize.Size14
LockMax.Text = "Lock Max"
LockMax.TextScaled = true
LockMax.TextSize = 14
LockMax.TextWrapped = true

LockAbove.Name = "LockAbove"
LockAbove.Parent = Teleportation
LockAbove.BackgroundColor3 = Color3.new(0.854902, 0.854902, 0.854902)
LockAbove.BorderColor3 = Color3.new(0.941177, 0.701961, 0.133333)
LockAbove.Position = UDim2.new(0.54435122, 0, 0.783913076, 0)
LockAbove.Size = UDim2.new(0, 140, 0, 25)
LockAbove.Font = Enum.Font.SourceSans
LockAbove.FontSize = Enum.FontSize.Size14
LockAbove.Text = "Lock Above"
LockAbove.TextScaled = true
LockAbove.TextSize = 14
LockAbove.TextWrapped = true

Trail.Name = "Trail"
Trail.Parent = Teleportation
Trail.BackgroundColor3 = Color3.new(0.854902, 0.854902, 0.854902)
Trail.BorderColor3 = Color3.new(0.941177, 0.701961, 0.133333)
Trail.Position = UDim2.new(0.0286500659, 0, 0.783913076, 0)
Trail.Size = UDim2.new(0, 140, 0, 25)
Trail.Font = Enum.Font.SourceSans
Trail.FontSize = Enum.FontSize.Size14
Trail.Text = "Trail"
Trail.TextScaled = true
Trail.TextSize = 14
Trail.TextWrapped = true

Tools.Name = "Tools"
Tools.Parent = Sections
Tools.BackgroundColor3 = Color3.new(0.278431, 0.278431, 0.278431)
Tools.BorderColor3 = Color3.new(0.121569, 0.121569, 0.121569)
Tools.BorderSizePixel = 2
Tools.Size = UDim2.new(0, 350, 0, 230)
Tools.Visible = false

TOOLSGUIDE.Name = "TOOLSGUIDE"
TOOLSGUIDE.Parent = Tools
TOOLSGUIDE.BackgroundColor3 = Color3.new(1, 1, 1)
TOOLSGUIDE.BackgroundTransparency = 1
TOOLSGUIDE.Position = UDim2.new(0.0286500659, 0, 0.0435507223, 0)
TOOLSGUIDE.Size = UDim2.new(0, 332, 0, 35)
TOOLSGUIDE.Font = Enum.Font.ArialBold
TOOLSGUIDE.FontSize = Enum.FontSize.Size14
TOOLSGUIDE.Text = "Do cool commands on others, as long as you have tools in your inventory."
TOOLSGUIDE.TextScaled = true
TOOLSGUIDE.TextSize = 14
TOOLSGUIDE.TextStrokeColor3 = Color3.new(1, 0.658824, 0.0666667)
TOOLSGUIDE.TextStrokeTransparency = 0
TOOLSGUIDE.TextWrapped = true

Kill.Name = "Kill"
Kill.Parent = Tools
Kill.BackgroundColor3 = Color3.new(0.854902, 0.854902, 0.854902)
Kill.BorderColor3 = Color3.new(0.941177, 0.701961, 0.133333)
Kill.Position = UDim2.new(0.0286500659, 0, 0.261304349, 0)
Kill.Size = UDim2.new(0, 140, 0, 25)
Kill.Font = Enum.Font.SourceSans
Kill.FontSize = Enum.FontSize.Size14
Kill.Text = "Kill"
Kill.TextScaled = true
Kill.TextSize = 14
Kill.TextWrapped = true

KillSurvive.Name = "KillSurvive"
KillSurvive.Parent = Tools
KillSurvive.BackgroundColor3 = Color3.new(0.854902, 0.854902, 0.854902)
KillSurvive.BorderColor3 = Color3.new(0.941177, 0.701961, 0.133333)
KillSurvive.Position = UDim2.new(0.54435122, 0, 0.261304349, 0)
KillSurvive.Size = UDim2.new(0, 140, 0, 25)
KillSurvive.Font = Enum.Font.SourceSans
KillSurvive.FontSize = Enum.FontSize.Size14
KillSurvive.Text = "Kill Survive"
KillSurvive.TextScaled = true
KillSurvive.TextSize = 14
KillSurvive.TextWrapped = true

Attach.Name = "Attach"
Attach.Parent = Tools
Attach.BackgroundColor3 = Color3.new(0.854902, 0.854902, 0.854902)
Attach.BorderColor3 = Color3.new(0.941177, 0.701961, 0.133333)
Attach.Position = UDim2.new(0.54435122, 0, 0.435507238, 0)
Attach.Size = UDim2.new(0, 140, 0, 25)
Attach.Font = Enum.Font.SourceSans
Attach.FontSize = Enum.FontSize.Size14
Attach.Text = "Attach"
Attach.TextScaled = true
Attach.TextSize = 14
Attach.TextWrapped = true

Bring.Name = "Bring"
Bring.Parent = Tools
Bring.BackgroundColor3 = Color3.new(0.854902, 0.854902, 0.854902)
Bring.BorderColor3 = Color3.new(0.941177, 0.701961, 0.133333)
Bring.Position = UDim2.new(0.0286500659, 0, 0.435507238, 0)
Bring.Size = UDim2.new(0, 140, 0, 25)
Bring.Font = Enum.Font.SourceSans
Bring.FontSize = Enum.FontSize.Size14
Bring.Text = "Bring"
Bring.TextScaled = true
Bring.TextSize = 14
Bring.TextWrapped = true

SuperSpin.Name = "SuperSpin"
SuperSpin.Parent = Tools
SuperSpin.BackgroundColor3 = Color3.new(0.854902, 0.854902, 0.854902)
SuperSpin.BorderColor3 = Color3.new(0.941177, 0.701961, 0.133333)
SuperSpin.Position = UDim2.new(0.0286500659, 0, 0.609710157, 0)
SuperSpin.Size = UDim2.new(0, 140, 0, 25)
SuperSpin.Font = Enum.Font.SourceSans
SuperSpin.FontSize = Enum.FontSize.Size14
SuperSpin.Text = "Super Spin"
SuperSpin.TextScaled = true
SuperSpin.TextSize = 14
SuperSpin.TextWrapped = true

FreeFall.Name = "FreeFall"
FreeFall.Parent = Tools
FreeFall.BackgroundColor3 = Color3.new(0.854902, 0.854902, 0.854902)
FreeFall.BorderColor3 = Color3.new(0.941177, 0.701961, 0.133333)
FreeFall.Position = UDim2.new(0.54435122, 0, 0.609710157, 0)
FreeFall.Size = UDim2.new(0, 140, 0, 25)
FreeFall.Font = Enum.Font.SourceSans
FreeFall.FontSize = Enum.FontSize.Size14
FreeFall.Text = "Free Fall"
FreeFall.TextScaled = true
FreeFall.TextSize = 14
FreeFall.TextWrapped = true

AttachExperimental.Name = "AttachExperimental"
AttachExperimental.Parent = Tools
AttachExperimental.BackgroundColor3 = Color3.new(0.854902, 0.854902, 0.854902)
AttachExperimental.BorderColor3 = Color3.new(0.941177, 0.701961, 0.133333)
AttachExperimental.Position = UDim2.new(0.54435122, 0, 0.783913076, 0)
AttachExperimental.Size = UDim2.new(0, 140, 0, 25)
AttachExperimental.Font = Enum.Font.SourceSans
AttachExperimental.FontSize = Enum.FontSize.Size14
AttachExperimental.Text = "Attach Experimental"
AttachExperimental.TextScaled = true
AttachExperimental.TextSize = 14
AttachExperimental.TextWrapped = true

GiveTool.Name = "GiveTool"
GiveTool.Parent = Tools
GiveTool.BackgroundColor3 = Color3.new(0.854902, 0.854902, 0.854902)
GiveTool.BorderColor3 = Color3.new(0.941177, 0.701961, 0.133333)
GiveTool.Position = UDim2.new(0.0286500659, 0, 0.783913076, 0)
GiveTool.Size = UDim2.new(0, 140, 0, 25)
GiveTool.Font = Enum.Font.SourceSans
GiveTool.FontSize = Enum.FontSize.Size14
GiveTool.Text = "Give Tool"
GiveTool.TextScaled = true
GiveTool.TextSize = 14
GiveTool.TextWrapped = true

Basic.Name = "Basic"
Basic.Parent = Sections
Basic.BackgroundColor3 = Color3.new(0.278431, 0.278431, 0.278431)
Basic.BorderColor3 = Color3.new(0.121569, 0.121569, 0.121569)
Basic.BorderSizePixel = 2
Basic.Size = UDim2.new(0, 350, 0, 230)
Basic.Visible = false

BASICGUIDE.Name = "BASICGUIDE"
BASICGUIDE.Parent = Basic
BASICGUIDE.BackgroundColor3 = Color3.new(1, 1, 1)
BASICGUIDE.BackgroundTransparency = 1
BASICGUIDE.Position = UDim2.new(0.0286500659, 0, 0.0435507223, 0)
BASICGUIDE.Size = UDim2.new(0, 332, 0, 35)
BASICGUIDE.Font = Enum.Font.ArialBold
BASICGUIDE.FontSize = Enum.FontSize.Size14
BASICGUIDE.Text = "Change/alter your own player."
BASICGUIDE.TextScaled = true
BASICGUIDE.TextSize = 14
BASICGUIDE.TextStrokeColor3 = Color3.new(1, 0.658824, 0.0666667)
BASICGUIDE.TextStrokeTransparency = 0
BASICGUIDE.TextWrapped = true

Speed.Name = "Speed"
Speed.Parent = Basic
Speed.BackgroundColor3 = Color3.new(0.854902, 0.854902, 0.854902)
Speed.BorderColor3 = Color3.new(0.941177, 0.701961, 0.133333)
Speed.Position = UDim2.new(0.0286500659, 0, 0.348405778, 0)
Speed.Size = UDim2.new(0, 100, 0, 25)
Speed.Font = Enum.Font.SourceSans
Speed.FontSize = Enum.FontSize.Size14
Speed.Text = "Speed"
Speed.TextScaled = true
Speed.TextSize = 14
Speed.TextWrapped = true

JumpHeight.Name = "JumpHeight"
JumpHeight.Parent = Basic
JumpHeight.BackgroundColor3 = Color3.new(0.854902, 0.854902, 0.854902)
JumpHeight.BorderColor3 = Color3.new(0.941177, 0.701961, 0.133333)
JumpHeight.Position = UDim2.new(0.343800783, 0, 0.348405778, 0)
JumpHeight.Size = UDim2.new(0, 100, 0, 25)
JumpHeight.Font = Enum.Font.SourceSans
JumpHeight.FontSize = Enum.FontSize.Size14
JumpHeight.Text = "JumpHeight"
JumpHeight.TextScaled = true
JumpHeight.TextSize = 14
JumpHeight.TextWrapped = true

Chat.Name = "Chat"
Chat.Parent = Basic
Chat.BackgroundColor3 = Color3.new(0.854902, 0.854902, 0.854902)
Chat.BorderColor3 = Color3.new(0.941177, 0.701961, 0.133333)
Chat.Position = UDim2.new(0.0286500659, 0, 0.653260887, 0)
Chat.Size = UDim2.new(0, 140, 0, 25)
Chat.Font = Enum.Font.SourceSans
Chat.FontSize = Enum.FontSize.Size14
Chat.Text = "Chat"
Chat.TextScaled = true
Chat.TextSize = 14
Chat.TextWrapped = true

Spam.Name = "Spam"
Spam.Parent = Basic
Spam.BackgroundColor3 = Color3.new(0.854902, 0.854902, 0.854902)
Spam.BorderColor3 = Color3.new(0.941177, 0.701961, 0.133333)
Spam.Position = UDim2.new(0.54435122, 0, 0.653260887, 0)
Spam.Size = UDim2.new(0, 140, 0, 25)
Spam.Font = Enum.Font.SourceSans
Spam.FontSize = Enum.FontSize.Size14
Spam.Text = "Spam"
Spam.TextScaled = true
Spam.TextSize = 14
Spam.TextWrapped = true

Fly.Name = "Fly"
Fly.Parent = Basic
Fly.BackgroundColor3 = Color3.new(0.854902, 0.854902, 0.854902)
Fly.BorderColor3 = Color3.new(0.941177, 0.701961, 0.133333)
Fly.Position = UDim2.new(0.54435122, 0, 0.827463746, 0)
Fly.Size = UDim2.new(0, 140, 0, 25)
Fly.Font = Enum.Font.SourceSans
Fly.FontSize = Enum.FontSize.Size14
Fly.Text = "Fly"
Fly.TextScaled = true
Fly.TextSize = 14
Fly.TextWrapped = true

Noclip.Name = "Noclip"
Noclip.Parent = Basic
Noclip.BackgroundColor3 = Color3.new(0.854902, 0.854902, 0.854902)
Noclip.BorderColor3 = Color3.new(0.941177, 0.701961, 0.133333)
Noclip.Position = UDim2.new(0.0286500659, 0, 0.827463746, 0)
Noclip.Size = UDim2.new(0, 140, 0, 25)
Noclip.Font = Enum.Font.SourceSans
Noclip.FontSize = Enum.FontSize.Size14
Noclip.Text = "Noclip"
Noclip.TextScaled = true
Noclip.TextSize = 14
Noclip.TextWrapped = true

HipHeight.Name = "HipHeight"
HipHeight.Parent = Basic
HipHeight.BackgroundColor3 = Color3.new(0.854902, 0.854902, 0.854902)
HipHeight.BorderColor3 = Color3.new(0.941177, 0.701961, 0.133333)
HipHeight.Position = UDim2.new(0.658951521, 0, 0.348405778, 0)
HipHeight.Size = UDim2.new(0, 100, 0, 25)
HipHeight.Font = Enum.Font.SourceSans
HipHeight.FontSize = Enum.FontSize.Size14
HipHeight.Text = "HipHeight"
HipHeight.TextScaled = true
HipHeight.TextSize = 14
HipHeight.TextWrapped = true

STATCHANGE.Name = "STATCHANGE"
STATCHANGE.Parent = Basic
STATCHANGE.BackgroundColor3 = Color3.new(1, 1, 1)
STATCHANGE.BorderColor3 = Color3.new(0.968628, 0.698039, 0.0588235)
STATCHANGE.BorderSizePixel = 2
STATCHANGE.Position = UDim2.new(0.315150708, 0, 0.217753619, 0)
STATCHANGE.Size = UDim2.new(0, 120, 0, 18)
STATCHANGE.ZIndex = 3
STATCHANGE.Font = Enum.Font.SourceSans
STATCHANGE.FontSize = Enum.FontSize.Size14
STATCHANGE.Text = ""
STATCHANGE.TextScaled = true
STATCHANGE.TextSize = 14
STATCHANGE.TextWrapped = true

CHATBOX.Name = "CHATBOX"
CHATBOX.Parent = Basic
CHATBOX.BackgroundColor3 = Color3.new(1, 1, 1)
CHATBOX.BorderColor3 = Color3.new(0.968628, 0.698039, 0.0588235)
CHATBOX.BorderSizePixel = 2
CHATBOX.Position = UDim2.new(0.143250331, 0, 0.522608697, 0)
CHATBOX.Size = UDim2.new(0, 240, 0, 18)
CHATBOX.ZIndex = 3
CHATBOX.Font = Enum.Font.SourceSans
CHATBOX.FontSize = Enum.FontSize.Size14
CHATBOX.Text = ""
CHATBOX.TextScaled = true
CHATBOX.TextSize = 14
CHATBOX.TextWrapped = true

Local_Player.Name = "Local_Player"
Local_Player.Parent = Sections
Local_Player.BackgroundColor3 = Color3.new(0.278431, 0.278431, 0.278431)
Local_Player.BorderColor3 = Color3.new(0.121569, 0.121569, 0.121569)
Local_Player.BorderSizePixel = 2
Local_Player.Size = UDim2.new(0, 350, 0, 230)
Local_Player.Visible = false

Local_PlayerGUIDE.Name = "Local_PlayerGUIDE"
Local_PlayerGUIDE.Parent = Local_Player
Local_PlayerGUIDE.BackgroundColor3 = Color3.new(1, 1, 1)
Local_PlayerGUIDE.BackgroundTransparency = 1
Local_PlayerGUIDE.Position = UDim2.new(0.0286500659, 0, 0.0435507223, 0)
Local_PlayerGUIDE.Size = UDim2.new(0, 332, 0, 35)
Local_PlayerGUIDE.Font = Enum.Font.ArialBold
Local_PlayerGUIDE.FontSize = Enum.FontSize.Size14
Local_PlayerGUIDE.Text = "Perform cool tricks on yourself."
Local_PlayerGUIDE.TextScaled = true
Local_PlayerGUIDE.TextSize = 14
Local_PlayerGUIDE.TextStrokeColor3 = Color3.new(1, 0.658824, 0.0666667)
Local_PlayerGUIDE.TextStrokeTransparency = 0
Local_PlayerGUIDE.TextWrapped = true

CrazySpin.Name = "CrazySpin"
CrazySpin.Parent = Local_Player
CrazySpin.BackgroundColor3 = Color3.new(0.854902, 0.854902, 0.854902)
CrazySpin.BorderColor3 = Color3.new(0.941177, 0.701961, 0.133333)
CrazySpin.Position = UDim2.new(0.0286500659, 0, 0.261304349, 0)
CrazySpin.Size = UDim2.new(0, 140, 0, 25)
CrazySpin.Font = Enum.Font.SourceSans
CrazySpin.FontSize = Enum.FontSize.Size14
CrazySpin.Text = "Crazy Spin"
CrazySpin.TextScaled = true
CrazySpin.TextSize = 14
CrazySpin.TextWrapped = true

CrouchRocket.Name = "CrouchRocket"
CrouchRocket.Parent = Local_Player
CrouchRocket.BackgroundColor3 = Color3.new(0.854902, 0.854902, 0.854902)
CrouchRocket.BorderColor3 = Color3.new(0.941177, 0.701961, 0.133333)
CrouchRocket.Position = UDim2.new(0.54435122, 0, 0.261304349, 0)
CrouchRocket.Size = UDim2.new(0, 140, 0, 25)
CrouchRocket.Font = Enum.Font.SourceSans
CrouchRocket.FontSize = Enum.FontSize.Size14
CrouchRocket.Text = "Crouch Rocket"
CrouchRocket.TextScaled = true
CrouchRocket.TextSize = 14
CrouchRocket.TextWrapped = true

Haunted.Name = "Haunted"
Haunted.Parent = Local_Player
Haunted.BackgroundColor3 = Color3.new(0.854902, 0.854902, 0.854902)
Haunted.BorderColor3 = Color3.new(0.941177, 0.701961, 0.133333)
Haunted.Position = UDim2.new(0.54435122, 0, 0.435507238, 0)
Haunted.Size = UDim2.new(0, 140, 0, 25)
Haunted.Font = Enum.Font.SourceSans
Haunted.FontSize = Enum.FontSize.Size14
Haunted.Text = "Haunted"
Haunted.TextScaled = true
Haunted.TextSize = 14
Haunted.TextWrapped = true

CloneIllusion.Name = "CloneIllusion"
CloneIllusion.Parent = Local_Player
CloneIllusion.BackgroundColor3 = Color3.new(0.854902, 0.854902, 0.854902)
CloneIllusion.BorderColor3 = Color3.new(0.941177, 0.701961, 0.133333)
CloneIllusion.Position = UDim2.new(0.0286500659, 0, 0.435507238, 0)
CloneIllusion.Size = UDim2.new(0, 140, 0, 25)
CloneIllusion.Font = Enum.Font.SourceSans
CloneIllusion.FontSize = Enum.FontSize.Size14
CloneIllusion.Text = "Clone Illusion"
CloneIllusion.TextScaled = true
CloneIllusion.TextSize = 14
CloneIllusion.TextWrapped = true

Levitate.Name = "Levitate"
Levitate.Parent = Local_Player
Levitate.BackgroundColor3 = Color3.new(0.854902, 0.854902, 0.854902)
Levitate.BorderColor3 = Color3.new(0.941177, 0.701961, 0.133333)
Levitate.Position = UDim2.new(0.0286500659, 0, 0.609710157, 0)
Levitate.Size = UDim2.new(0, 140, 0, 25)
Levitate.Font = Enum.Font.SourceSans
Levitate.FontSize = Enum.FontSize.Size14
Levitate.Text = "Levitate"
Levitate.TextScaled = true
Levitate.TextSize = 14
Levitate.TextWrapped = true

Dinosaur.Name = "Dinosaur"
Dinosaur.Parent = Local_Player
Dinosaur.BackgroundColor3 = Color3.new(0.854902, 0.854902, 0.854902)
Dinosaur.BorderColor3 = Color3.new(0.941177, 0.701961, 0.133333)
Dinosaur.Position = UDim2.new(0.54435122, 0, 0.609710157, 0)
Dinosaur.Size = UDim2.new(0, 140, 0, 25)
Dinosaur.Font = Enum.Font.SourceSans
Dinosaur.FontSize = Enum.FontSize.Size14
Dinosaur.Text = "Dinosaur"
Dinosaur.TextScaled = true
Dinosaur.TextSize = 14
Dinosaur.TextWrapped = true

Glitchy.Name = "Glitchy"
Glitchy.Parent = Local_Player
Glitchy.BackgroundColor3 = Color3.new(0.854902, 0.854902, 0.854902)
Glitchy.BorderColor3 = Color3.new(0.941177, 0.701961, 0.133333)
Glitchy.Position = UDim2.new(0.54435122, 0, 0.783913076, 0)
Glitchy.Size = UDim2.new(0, 140, 0, 25)
Glitchy.Font = Enum.Font.SourceSans
Glitchy.FontSize = Enum.FontSize.Size14
Glitchy.Text = "Glitchy"
Glitchy.TextScaled = true
Glitchy.TextSize = 14
Glitchy.TextWrapped = true

NoLimbs.Name = "NoLimbs"
NoLimbs.Parent = Local_Player
NoLimbs.BackgroundColor3 = Color3.new(0.854902, 0.854902, 0.854902)
NoLimbs.BorderColor3 = Color3.new(0.941177, 0.701961, 0.133333)
NoLimbs.Position = UDim2.new(0.0286500659, 0, 0.783913076, 0)
NoLimbs.Size = UDim2.new(0, 140, 0, 25)
NoLimbs.Font = Enum.Font.SourceSans
NoLimbs.FontSize = Enum.FontSize.Size14
NoLimbs.Text = "No Limbs"
NoLimbs.TextScaled = true
NoLimbs.TextSize = 14
NoLimbs.TextWrapped = true

Animations.Name = "Animations"
Animations.Parent = Sections
Animations.BackgroundColor3 = Color3.new(0.278431, 0.278431, 0.278431)
Animations.BorderColor3 = Color3.new(0.121569, 0.121569, 0.121569)
Animations.BorderSizePixel = 2
Animations.Size = UDim2.new(0, 350, 0, 230)
Animations.Visible = false

ANIMATIONSGUIDE.Name = "ANIMATIONSGUIDE"
ANIMATIONSGUIDE.Parent = Animations
ANIMATIONSGUIDE.BackgroundColor3 = Color3.new(1, 1, 1)
ANIMATIONSGUIDE.BackgroundTransparency = 1
ANIMATIONSGUIDE.Position = UDim2.new(0.0286500659, 0, 0.0435507223, 0)
ANIMATIONSGUIDE.Size = UDim2.new(0, 332, 0, 35)
ANIMATIONSGUIDE.Font = Enum.Font.ArialBold
ANIMATIONSGUIDE.FontSize = Enum.FontSize.Size14
ANIMATIONSGUIDE.Text = "Do cool commands with animations on others."
ANIMATIONSGUIDE.TextScaled = true
ANIMATIONSGUIDE.TextSize = 14
ANIMATIONSGUIDE.TextStrokeColor3 = Color3.new(1, 0.658824, 0.0666667)
ANIMATIONSGUIDE.TextStrokeTransparency = 0
ANIMATIONSGUIDE.TextWrapped = true

_18.Name = "18+"
_18.Parent = Animations
_18.BackgroundColor3 = Color3.new(0.854902, 0.854902, 0.854902)
_18.BorderColor3 = Color3.new(0.941177, 0.701961, 0.133333)
_18.Position = UDim2.new(0.0286500659, 0, 0.261304349, 0)
_18.Size = UDim2.new(0, 140, 0, 25)
_18.Font = Enum.Font.SourceSans
_18.FontSize = Enum.FontSize.Size14
_18.Text = "18+"
_18.TextScaled = true
_18.TextSize = 14
_18.TextWrapped = true

Hide.Name = "Hide"
Hide.Parent = Animations
Hide.BackgroundColor3 = Color3.new(0.854902, 0.854902, 0.854902)
Hide.BorderColor3 = Color3.new(0.941177, 0.701961, 0.133333)
Hide.Position = UDim2.new(0.54435122, 0, 0.261304349, 0)
Hide.Size = UDim2.new(0, 140, 0, 25)
Hide.Font = Enum.Font.SourceSans
Hide.FontSize = Enum.FontSize.Size14
Hide.Text = "Hide"
Hide.TextScaled = true
Hide.TextSize = 14
Hide.TextWrapped = true

PushLock.Name = "PushLock"
PushLock.Parent = Animations
PushLock.BackgroundColor3 = Color3.new(0.854902, 0.854902, 0.854902)
PushLock.BorderColor3 = Color3.new(0.941177, 0.701961, 0.133333)
PushLock.Position = UDim2.new(0.54435122, 0, 0.435507238, 0)
PushLock.Size = UDim2.new(0, 140, 0, 25)
PushLock.Font = Enum.Font.SourceSans
PushLock.FontSize = Enum.FontSize.Size14
PushLock.Text = "Push Lock"
PushLock.TextScaled = true
PushLock.TextSize = 14
PushLock.TextWrapped = true

SlamOn.Name = "SlamOn"
SlamOn.Parent = Animations
SlamOn.BackgroundColor3 = Color3.new(0.854902, 0.854902, 0.854902)
SlamOn.BorderColor3 = Color3.new(0.941177, 0.701961, 0.133333)
SlamOn.Position = UDim2.new(0.0286500659, 0, 0.435507238, 0)
SlamOn.Size = UDim2.new(0, 140, 0, 25)
SlamOn.Font = Enum.Font.SourceSans
SlamOn.FontSize = Enum.FontSize.Size14
SlamOn.Text = "Slam On"
SlamOn.TextScaled = true
SlamOn.TextSize = 14
SlamOn.TextWrapped = true

LevitateOn.Name = "LevitateOn"
LevitateOn.Parent = Animations
LevitateOn.BackgroundColor3 = Color3.new(0.854902, 0.854902, 0.854902)
LevitateOn.BorderColor3 = Color3.new(0.941177, 0.701961, 0.133333)
LevitateOn.Position = UDim2.new(0.0286500659, 0, 0.609710157, 0)
LevitateOn.Size = UDim2.new(0, 140, 0, 25)
LevitateOn.Font = Enum.Font.SourceSans
LevitateOn.FontSize = Enum.FontSize.Size14
LevitateOn.Text = "Levitate On"
LevitateOn.TextScaled = true
LevitateOn.TextSize = 14
LevitateOn.TextWrapped = true

Dance.Name = "Dance"
Dance.Parent = Animations
Dance.BackgroundColor3 = Color3.new(0.854902, 0.854902, 0.854902)
Dance.BorderColor3 = Color3.new(0.941177, 0.701961, 0.133333)
Dance.Position = UDim2.new(0.54435122, 0, 0.609710157, 0)
Dance.Size = UDim2.new(0, 140, 0, 25)
Dance.Font = Enum.Font.SourceSans
Dance.FontSize = Enum.FontSize.Size14
Dance.Text = "Dance"
Dance.TextScaled = true
Dance.TextSize = 14
Dance.TextWrapped = true

ExperimentalAnimation.Name = "ExperimentalAnimation"
ExperimentalAnimation.Parent = Animations
ExperimentalAnimation.BackgroundColor3 = Color3.new(0.854902, 0.854902, 0.854902)
ExperimentalAnimation.BorderColor3 = Color3.new(0.941177, 0.701961, 0.133333)
ExperimentalAnimation.Position = UDim2.new(0.54435122, 0, 0.783913076, 0)
ExperimentalAnimation.Size = UDim2.new(0, 140, 0, 25)
ExperimentalAnimation.Font = Enum.Font.SourceSans
ExperimentalAnimation.FontSize = Enum.FontSize.Size14
ExperimentalAnimation.Text = "Experimental Animation"
ExperimentalAnimation.TextScaled = true
ExperimentalAnimation.TextSize = 14
ExperimentalAnimation.TextWrapped = true

Carpet.Name = "Carpet"
Carpet.Parent = Animations
Carpet.BackgroundColor3 = Color3.new(0.854902, 0.854902, 0.854902)
Carpet.BorderColor3 = Color3.new(0.941177, 0.701961, 0.133333)
Carpet.Position = UDim2.new(0.0286500659, 0, 0.783913076, 0)
Carpet.Size = UDim2.new(0, 140, 0, 25)
Carpet.Font = Enum.Font.SourceSans
Carpet.FontSize = Enum.FontSize.Size14
Carpet.Text = "Carpet"
Carpet.TextScaled = true
Carpet.TextSize = 14
Carpet.TextWrapped = true

Extra.Name = "Extra"
Extra.Parent = Sections
Extra.BackgroundColor3 = Color3.new(0.278431, 0.278431, 0.278431)
Extra.BorderColor3 = Color3.new(0.121569, 0.121569, 0.121569)
Extra.BorderSizePixel = 2
Extra.Size = UDim2.new(0, 350, 0, 230)
Extra.Visible = false

EXTRAGUIDE.Name = "EXTRAGUIDE"
EXTRAGUIDE.Parent = Extra
EXTRAGUIDE.BackgroundColor3 = Color3.new(1, 1, 1)
EXTRAGUIDE.BackgroundTransparency = 1
EXTRAGUIDE.Position = UDim2.new(0.0286500659, 0, 0.0435507223, 0)
EXTRAGUIDE.Size = UDim2.new(0, 332, 0, 35)
EXTRAGUIDE.Font = Enum.Font.ArialBold
EXTRAGUIDE.FontSize = Enum.FontSize.Size14
EXTRAGUIDE.Text = "Extra commands for yourself."
EXTRAGUIDE.TextScaled = true
EXTRAGUIDE.TextSize = 14
EXTRAGUIDE.TextStrokeColor3 = Color3.new(1, 0.658824, 0.0666667)
EXTRAGUIDE.TextStrokeTransparency = 0
EXTRAGUIDE.TextWrapped = true

Sit.Name = "Sit"
Sit.Parent = Extra
Sit.BackgroundColor3 = Color3.new(0.854902, 0.854902, 0.854902)
Sit.BorderColor3 = Color3.new(0.941177, 0.701961, 0.133333)
Sit.Position = UDim2.new(0.0286500659, 0, 0.261304349, 0)
Sit.Size = UDim2.new(0, 140, 0, 25)
Sit.Font = Enum.Font.SourceSans
Sit.FontSize = Enum.FontSize.Size14
Sit.Text = "Sit"
Sit.TextScaled = true
Sit.TextSize = 14
Sit.TextWrapped = true

Jump.Name = "Jump"
Jump.Parent = Extra
Jump.BackgroundColor3 = Color3.new(0.854902, 0.854902, 0.854902)
Jump.BorderColor3 = Color3.new(0.941177, 0.701961, 0.133333)
Jump.Position = UDim2.new(0.54435122, 0, 0.261304349, 0)
Jump.Size = UDim2.new(0, 140, 0, 25)
Jump.Font = Enum.Font.SourceSans
Jump.FontSize = Enum.FontSize.Size14
Jump.Text = "Jump"
Jump.TextScaled = true
Jump.TextSize = 14
Jump.TextWrapped = true

PlatformStand.Name = "PlatformStand"
PlatformStand.Parent = Extra
PlatformStand.BackgroundColor3 = Color3.new(0.854902, 0.854902, 0.854902)
PlatformStand.BorderColor3 = Color3.new(0.941177, 0.701961, 0.133333)
PlatformStand.Position = UDim2.new(0.54435122, 0, 0.435507238, 0)
PlatformStand.Size = UDim2.new(0, 140, 0, 25)
PlatformStand.Font = Enum.Font.SourceSans
PlatformStand.FontSize = Enum.FontSize.Size14
PlatformStand.Text = "Platform Stand"
PlatformStand.TextScaled = true
PlatformStand.TextSize = 14
PlatformStand.TextWrapped = true

Freeze.Name = "Freeze"
Freeze.Parent = Extra
Freeze.BackgroundColor3 = Color3.new(0.854902, 0.854902, 0.854902)
Freeze.BorderColor3 = Color3.new(0.941177, 0.701961, 0.133333)
Freeze.Position = UDim2.new(0.0286500659, 0, 0.435507238, 0)
Freeze.Size = UDim2.new(0, 140, 0, 25)
Freeze.Font = Enum.Font.SourceSans
Freeze.FontSize = Enum.FontSize.Size14
Freeze.Text = "Freeze"
Freeze.TextScaled = true
Freeze.TextSize = 14
Freeze.TextWrapped = true

Insane.Name = "Insane"
Insane.Parent = Extra
Insane.BackgroundColor3 = Color3.new(0.854902, 0.854902, 0.854902)
Insane.BorderColor3 = Color3.new(0.941177, 0.701961, 0.133333)
Insane.Position = UDim2.new(0.0286500659, 0, 0.609710157, 0)
Insane.Size = UDim2.new(0, 140, 0, 25)
Insane.Font = Enum.Font.SourceSans
Insane.FontSize = Enum.FontSize.Size14
Insane.Text = "Insane"
Insane.TextScaled = true
Insane.TextSize = 14
Insane.TextWrapped = true

TPVoid.Name = "TPVoid"
TPVoid.Parent = Extra
TPVoid.BackgroundColor3 = Color3.new(0.854902, 0.854902, 0.854902)
TPVoid.BorderColor3 = Color3.new(0.941177, 0.701961, 0.133333)
TPVoid.Position = UDim2.new(0.54435122, 0, 0.609710157, 0)
TPVoid.Size = UDim2.new(0, 140, 0, 25)
TPVoid.Font = Enum.Font.SourceSans
TPVoid.FontSize = Enum.FontSize.Size14
TPVoid.Text = "TP Void"
TPVoid.TextScaled = true
TPVoid.TextSize = 14
TPVoid.TextWrapped = true

Unknown.Name = "Unknown"
Unknown.Parent = Extra
Unknown.BackgroundColor3 = Color3.new(0.854902, 0.854902, 0.854902)
Unknown.BorderColor3 = Color3.new(0.941177, 0.701961, 0.133333)
Unknown.Position = UDim2.new(0.54435122, 0, 0.783913076, 0)
Unknown.Size = UDim2.new(0, 140, 0, 25)
Unknown.Font = Enum.Font.SourceSans
Unknown.FontSize = Enum.FontSize.Size14
Unknown.Text = "Unknown"
Unknown.TextScaled = true
Unknown.TextSize = 14
Unknown.TextWrapped = true

Reset.Name = "Reset"
Reset.Parent = Extra
Reset.BackgroundColor3 = Color3.new(0.854902, 0.854902, 0.854902)
Reset.BorderColor3 = Color3.new(0.941177, 0.701961, 0.133333)
Reset.Position = UDim2.new(0.0286500659, 0, 0.783913076, 0)
Reset.Size = UDim2.new(0, 140, 0, 25)
Reset.Font = Enum.Font.SourceSans
Reset.FontSize = Enum.FontSize.Size14
Reset.Text = "Reset"
Reset.TextScaled = true
Reset.TextSize = 14
Reset.TextWrapped = true

SelectTabs.Name = "SelectTabs"
SelectTabs.Parent = MainFrame
SelectTabs.BackgroundColor3 = Color3.new(0.435294, 0.435294, 0.435294)
SelectTabs.BorderColor3 = Color3.new(0.121569, 0.121569, 0.121569)
SelectTabs.BorderSizePixel = 2
SelectTabs.Position = UDim2.new(-0.286500663, 0, 0.148395061, 0)
SelectTabs.Size = UDim2.new(0, 98, 0, 230)
SelectTabs.CanvasSize = UDim2.new(0, 0, 1.20000005, 0)

RocketPropulsionTAB.Name = "RocketPropulsionTAB"
RocketPropulsionTAB.Parent = SelectTabs
RocketPropulsionTAB.BackgroundColor3 = Color3.new(1, 1, 1)
RocketPropulsionTAB.BackgroundTransparency = 1
RocketPropulsionTAB.Position = UDim2.new(0, 0, 0.00999999978, 0)
RocketPropulsionTAB.Size = UDim2.new(0, 82, 0, 40)
RocketPropulsionTAB.Font = Enum.Font.SourceSansLight
RocketPropulsionTAB.FontSize = Enum.FontSize.Size18
RocketPropulsionTAB.Text = "Rocket Propulsion"
RocketPropulsionTAB.TextSize = 18
RocketPropulsionTAB.TextWrapped = true

TeleportationTAB.Name = "TeleportationTAB"
TeleportationTAB.Parent = SelectTabs
TeleportationTAB.BackgroundColor3 = Color3.new(1, 1, 1)
TeleportationTAB.BackgroundTransparency = 1
TeleportationTAB.Position = UDim2.new(0, 0, 0.150000006, 0)
TeleportationTAB.Size = UDim2.new(0, 82, 0, 40)
TeleportationTAB.Font = Enum.Font.SourceSansLight
TeleportationTAB.FontSize = Enum.FontSize.Size18
TeleportationTAB.Text = "Teleportation"
TeleportationTAB.TextSize = 17
TeleportationTAB.TextWrapped = true

ToolsTAB.Name = "ToolsTAB"
ToolsTAB.Parent = SelectTabs
ToolsTAB.BackgroundColor3 = Color3.new(1, 1, 1)
ToolsTAB.BackgroundTransparency = 1
ToolsTAB.Position = UDim2.new(0, 0, 0.289999992, 0)
ToolsTAB.Size = UDim2.new(0, 82, 0, 40)
ToolsTAB.Font = Enum.Font.SourceSansLight
ToolsTAB.FontSize = Enum.FontSize.Size24
ToolsTAB.Text = "Tools"
ToolsTAB.TextSize = 20
ToolsTAB.TextWrapped = true

AnimationsTAB.Name = "AnimationsTAB"
AnimationsTAB.Parent = SelectTabs
AnimationsTAB.BackgroundColor3 = Color3.new(1, 1, 1)
AnimationsTAB.BackgroundTransparency = 1
AnimationsTAB.Position = UDim2.new(0, 0, 0.569999993, 0)
AnimationsTAB.Size = UDim2.new(0, 82, 0, 40)
AnimationsTAB.Font = Enum.Font.SourceSansLight
AnimationsTAB.FontSize = Enum.FontSize.Size24
AnimationsTAB.Text = "Animations"
AnimationsTAB.TextSize = 20
AnimationsTAB.TextWrapped = true

BasicTAB.Name = "BasicTAB"
BasicTAB.Parent = SelectTabs
BasicTAB.BackgroundColor3 = Color3.new(1, 1, 1)
BasicTAB.BackgroundTransparency = 1
BasicTAB.Position = UDim2.new(0, 0, 0.430000007, 0)
BasicTAB.Size = UDim2.new(0, 82, 0, 40)
BasicTAB.Font = Enum.Font.SourceSansLight
BasicTAB.FontSize = Enum.FontSize.Size24
BasicTAB.Text = "Basic"
BasicTAB.TextSize = 20
BasicTAB.TextWrapped = true

Local_PlayerTAB.Name = "Local_PlayerTAB"
Local_PlayerTAB.Parent = SelectTabs
Local_PlayerTAB.BackgroundColor3 = Color3.new(1, 1, 1)
Local_PlayerTAB.BackgroundTransparency = 1
Local_PlayerTAB.Position = UDim2.new(0, 0, 0.709999979, 0)
Local_PlayerTAB.Size = UDim2.new(0, 82, 0, 40)
Local_PlayerTAB.Font = Enum.Font.SourceSansLight
Local_PlayerTAB.FontSize = Enum.FontSize.Size24
Local_PlayerTAB.Text = "Local Player"
Local_PlayerTAB.TextSize = 20
Local_PlayerTAB.TextWrapped = true

ExtraTAB.Name = "ExtraTAB"
ExtraTAB.Parent = SelectTabs
ExtraTAB.BackgroundColor3 = Color3.new(1, 1, 1)
ExtraTAB.BackgroundTransparency = 1
ExtraTAB.Position = UDim2.new(0, 0, 0.850000024, 0)
ExtraTAB.Size = UDim2.new(0, 82, 0, 40)
ExtraTAB.Font = Enum.Font.SourceSansLight
ExtraTAB.FontSize = Enum.FontSize.Size24
ExtraTAB.Text = "Extra"
ExtraTAB.TextSize = 20
ExtraTAB.TextWrapped = true

SideFrame.Name = "SideFrame"
SideFrame.Parent = HyperTotal
SideFrame.Active = true
SideFrame.BackgroundColor3 = Color3.new(1, 1, 1)
SideFrame.BackgroundTransparency = 1
SideFrame.Draggable = true
SideFrame.Position = UDim2.new(0.349, 0, 0.25, 0)
SideFrame.Size = UDim2.new(0, 350, 0, 40)
SideFrame.Visible = false

SideTopFrame.Name = "SideTopFrame"
SideTopFrame.Parent = SideFrame
SideTopFrame.BackgroundColor3 = Color3.new(0.121569, 0.121569, 0.121569)
SideTopFrame.BorderColor3 = Color3.new(0.121569, 0.121569, 0.121569)
SideTopFrame.BorderSizePixel = 2
SideTopFrame.Position = UDim2.new(-0.287, 0, 0, 0)
SideTopFrame.Size = UDim2.new(0, 450, 0, 270)
SideTopFrame.ZIndex = 9

SideTitle.Name = "SideTitle"
SideTitle.Parent = SideTopFrame
SideTitle.BackgroundColor3 = Color3.new(1, 1, 1)
SideTitle.BackgroundTransparency = 1
SideTitle.Position = UDim2.new(0.356534153, 0, 0, 0)
SideTitle.Size = UDim2.new(0, 150, 0, 40)
SideTitle.ZIndex = 10
SideTitle.Font = Enum.Font.SourceSansItalic
SideTitle.FontSize = Enum.FontSize.Size36
SideTitle.Text = "HyperTotal"
SideTitle.TextColor3 = Color3.new(0.933333, 0.670588, 0.0509804)
SideTitle.TextSize = 35
SideTitle.TextWrapped = true

OpenGUI.Name = "OpenGUI"
OpenGUI.Parent = SideTopFrame
OpenGUI.BackgroundColor3 = Color3.new(1, 1, 1)
OpenGUI.BackgroundTransparency = 1
OpenGUI.Position = UDim2.new(0.913618803, 0, 0, 0)
OpenGUI.Size = UDim2.new(0, 40, 0, 40)
OpenGUI.ZIndex = 10
OpenGUI.Font = Enum.Font.SourceSansBold
OpenGUI.FontSize = Enum.FontSize.Size60
OpenGUI.Text = "X"
OpenGUI.TextColor3 = Color3.new(1, 0.631373, 0.109804)
OpenGUI.TextSize = 50
OpenGUI.TextWrapped = true

SideCreditTXT.Name = "SideCreditTXT"
SideCreditTXT.Parent = SideTopFrame
SideCreditTXT.BackgroundColor3 = Color3.new(1, 1, 1)
SideCreditTXT.BackgroundTransparency = 1
SideCreditTXT.Position = UDim2.new(0.690784931, 0, 0.250416666, 0)
SideCreditTXT.Rotation = -17
SideCreditTXT.Size = UDim2.new(0, 90, 0, 20)
SideCreditTXT.ZIndex = 10
SideCreditTXT.Font = Enum.Font.SourceSansItalic
SideCreditTXT.FontSize = Enum.FontSize.Size24
SideCreditTXT.Text = "illremember"
SideCreditTXT.TextColor3 = Color3.new(0.933333, 0.819608, 0.737255)
SideCreditTXT.TextSize = 20
SideCreditTXT.TextWrapped = true

BrickFrame.Name = "BrickFrame"
BrickFrame.Parent = MainFrame
BrickFrame.BackgroundColor3 = Color3.new(0.121569, 0.121569, 0.121569)
BrickFrame.BorderColor3 = Color3.new(0.121569, 0.121569, 0.121569)
BrickFrame.BorderSizePixel = 0
BrickFrame.Position = UDim2.new(0, 0, 0.148395061, 0)
BrickFrame.Size = UDim2.new(0, 0, 0, 230)
BrickFrame.ZIndex = 4

-- Buttons

col = Color3.new(0.854902, 0.854902, 0.854902)
loc = Color3.new(0.65, 0.90, 0.65)

wait(1)
MainFrame:TweenPosition(UDim2.new(0.348623842, 0, 0.25, 0), "Out", "Bounce", 2)

if game.Workspace.FilteringEnabled == false then
	FE_CHECK.Text = "FE is disabled"
	FE_CHECK.TextColor3 = Color3.fromRGB(200,10,10)
else
	FE_CHECK.Text = "FE is enabled"
	FE_CHECK.TextColor3 = Color3.fromRGB(10,200,10)
end

CloseGUI.MouseButton1Click:connect(function()
CloseGUI.Visible = false
EnterUsername.Visible = false
TopFrame:TweenSize(UDim2.new(0, 450, 0, 270), "Out", "Sine", 1)
wait(1)
SideFrame.Position = MainFrame.Position
MainFrame.Visible = false
SideFrame.Visible = true
SideTopFrame:TweenSize(UDim2.new(0, 450, 0, 40), "Out", "Sine", 1)
OpenGUI.Visible = false
wait(1)
OpenGUI.Visible = true
end)

OpenGUI.MouseButton1Click:connect(function()
OpenGUI.Visible = false
SideTopFrame:TweenSize(UDim2.new(0, 450, 0, 270), "Out", "Sine", 1)
wait(1)
MainFrame.Position = SideFrame.Position
SideFrame.Visible = false
MainFrame.Visible = true
CloseGUI.Visible = false
TopFrame:TweenSize(UDim2.new(0, 450, 0, 40), "Out", "Sine", 1)
wait(1)
EnterUsername.Visible = true
CloseGUI.Visible = true
end)

AnimationsTAB.MouseButton1Click:connect(function()
	BrickFrame:TweenSize(UDim2.new(0, 350, 0, 230), "Out", "Sine", 0.5)
	wait(0.5)
	Animations.Visible = true
	Basic.Visible = false
	Extra.Visible = false
	INTRO.Visible = false
	Local_Player.Visible = false
	RocketPropulsion.Visible = false
	Teleportation.Visible = false
	Tools.Visible = false
	AnimationsTAB.Font = "SourceSansBold"
	BasicTAB.Font = "SourceSansLight"
	ExtraTAB.Font = "SourceSansLight"
	Local_PlayerTAB.Font = "SourceSansLight"
	RocketPropulsionTAB.Font = "SourceSansLight"
	TeleportationTAB.Font = "SourceSansLight"
	ToolsTAB.Font = "SourceSansLight"
	AnimationsTAB.TextSize = 17
	TeleportationTAB.TextSize = 17
	BrickFrame:TweenSize(UDim2.new(0, 0, 0, 230), "Out", "Sine", 0.5)
end)

BasicTAB.MouseButton1Click:connect(function()
	BrickFrame:TweenSize(UDim2.new(0, 350, 0, 230), "Out", "Sine", 0.5)
	wait(0.5)
	Animations.Visible = false
	Basic.Visible = true
	Extra.Visible = false
	INTRO.Visible = false
	Local_Player.Visible = false
	RocketPropulsion.Visible = false
	Teleportation.Visible = false
	Tools.Visible = false
	AnimationsTAB.Font = "SourceSansLight"
	BasicTAB.Font = "SourceSansBold"
	ExtraTAB.Font = "SourceSansLight"
	Local_PlayerTAB.Font = "SourceSansLight"
	RocketPropulsionTAB.Font = "SourceSansLight"
	TeleportationTAB.Font = "SourceSansLight"
	ToolsTAB.Font = "SourceSansLight"
	AnimationsTAB.TextSize = 20
	TeleportationTAB.TextSize = 17
	BrickFrame:TweenSize(UDim2.new(0, 0, 0, 230), "Out", "Sine", 0.5)
end)

ExtraTAB.MouseButton1Click:connect(function()
	BrickFrame:TweenSize(UDim2.new(0, 350, 0, 230), "Out", "Sine", 0.5)
	wait(0.5)
	Animations.Visible = false
	Basic.Visible = false
	Extra.Visible = true
	INTRO.Visible = false
	Local_Player.Visible = false
	RocketPropulsion.Visible = false
	Teleportation.Visible = false
	Tools.Visible = false
	AnimationsTAB.Font = "SourceSansLight"
	BasicTAB.Font = "SourceSansLight"
	ExtraTAB.Font = "SourceSansBold"
	Local_PlayerTAB.Font = "SourceSansLight"
	RocketPropulsionTAB.Font = "SourceSansLight"
	TeleportationTAB.Font = "SourceSansLight"
	ToolsTAB.Font = "SourceSansLight"
	AnimationsTAB.TextSize = 20
	TeleportationTAB.TextSize = 17
	BrickFrame:TweenSize(UDim2.new(0, 0, 0, 230), "Out", "Sine", 0.5)
end)

Local_PlayerTAB.MouseButton1Click:connect(function()
	BrickFrame:TweenSize(UDim2.new(0, 350, 0, 230), "Out", "Sine", 0.5)
	wait(0.5)
	Animations.Visible = false
	Basic.Visible = false
	Extra.Visible = false
	INTRO.Visible = false
	Local_Player.Visible = true
	RocketPropulsion.Visible = false
	Teleportation.Visible = false
	Tools.Visible = false
	AnimationsTAB.Font = "SourceSansLight"
	BasicTAB.Font = "SourceSansLight"
	ExtraTAB.Font = "SourceSansLight"
	Local_PlayerTAB.Font = "SourceSansBold"
	RocketPropulsionTAB.Font = "SourceSansLight"
	TeleportationTAB.Font = "SourceSansLight"
	ToolsTAB.Font = "SourceSansLight"
	AnimationsTAB.TextSize = 20
	TeleportationTAB.TextSize = 17
	BrickFrame:TweenSize(UDim2.new(0, 0, 0, 230), "Out", "Sine", 0.5)
end)

RocketPropulsionTAB.MouseButton1Click:connect(function()
	BrickFrame:TweenSize(UDim2.new(0, 350, 0, 230), "Out", "Sine", 0.5)
	wait(0.5)
	Animations.Visible = false
	Basic.Visible = false
	Extra.Visible = false
	INTRO.Visible = false
	Local_Player.Visible = false
	RocketPropulsion.Visible = true
	Teleportation.Visible = false
	Tools.Visible = false
	AnimationsTAB.Font = "SourceSansLight"
	BasicTAB.Font = "SourceSansLight"
	ExtraTAB.Font = "SourceSansLight"
	Local_PlayerTAB.Font = "SourceSansLight"
	RocketPropulsionTAB.Font = "SourceSansBold"
	TeleportationTAB.Font = "SourceSansLight"
	ToolsTAB.Font = "SourceSansLight"
	AnimationsTAB.TextSize = 20
	TeleportationTAB.TextSize = 17
	BrickFrame:TweenSize(UDim2.new(0, 0, 0, 230), "Out", "Sine", 0.5)
end)

TeleportationTAB.MouseButton1Click:connect(function()
	BrickFrame:TweenSize(UDim2.new(0, 350, 0, 230), "Out", "Sine", 0.5)
	wait(0.5)
	Animations.Visible = false
	Basic.Visible = false
	Extra.Visible = false
	INTRO.Visible = false
	Local_Player.Visible = false
	RocketPropulsion.Visible = false
	Teleportation.Visible = true
	Tools.Visible = false
	AnimationsTAB.Font = "SourceSansLight"
	BasicTAB.Font = "SourceSansLight"
	ExtraTAB.Font = "SourceSansLight"
	Local_PlayerTAB.Font = "SourceSansLight"
	RocketPropulsionTAB.Font = "SourceSansLight"
	TeleportationTAB.Font = "SourceSansBold"
	ToolsTAB.Font = "SourceSansLight"
	AnimationsTAB.TextSize = 20
	TeleportationTAB.TextSize = 15
	BrickFrame:TweenSize(UDim2.new(0, 0, 0, 230), "Out", "Sine", 0.5)
end)

ToolsTAB.MouseButton1Click:connect(function()
	BrickFrame:TweenSize(UDim2.new(0, 350, 0, 230), "Out", "Sine", 0.5)
	wait(0.5)
	Animations.Visible = false
	Basic.Visible = false
	Extra.Visible = false
	INTRO.Visible = false
	Local_Player.Visible = false
	RocketPropulsion.Visible = false
	Teleportation.Visible = false
	Tools.Visible = true
	AnimationsTAB.Font = "SourceSansLight"
	BasicTAB.Font = "SourceSansLight"
	ExtraTAB.Font = "SourceSansLight"
	Local_PlayerTAB.Font = "SourceSansLight"
	RocketPropulsionTAB.Font = "SourceSansLight"
	TeleportationTAB.Font = "SourceSansLight"
	ToolsTAB.Font = "SourceSansBold"
	AnimationsTAB.TextSize = 20
	TeleportationTAB.TextSize = 17
	BrickFrame:TweenSize(UDim2.new(0, 0, 0, 230), "Out", "Sine", 0.5)
end)

------ ANIMATIONS -------------------------------------------------------------------------
------ ANIMATIONS -------------------------------------------------------------------------
------ ANIMATIONS -------------------------------------------------------------------------
------ ANIMATIONS -------------------------------------------------------------------------

function GetPlayer(String) -- Credit to Timeless/xFunnieuss
    local Found = {}
    local strl = String:lower()
    if strl == "all" then
        for i,v in pairs(game.Players:GetPlayers()) do
            table.insert(Found,v)
        end
    elseif strl == "others" then
        for i,v in pairs(game.Players:GetPlayers()) do
            if v.Name ~= game.Players.LocalPlayer.Name then
                table.insert(Found,v)
            end
        end    
    else
        for i,v in pairs(game.Players:GetPlayers()) do
            if v.Name:lower():sub(1, #String) == String:lower() then
                table.insert(Found,v)
            end
        end    
    end
    return Found    
end

AnimationId = "148840371"
local Anim = Instance.new("Animation")
Anim.AnimationId = "rbxassetid://"..AnimationId
local track = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
_18active = false
game.Players.LocalPlayer.CharacterAdded:Connect(function(character)
    track = character:WaitForChild("Humanoid"):LoadAnimation(Anim)
    _18active = false
end)
_18.MouseButton1Click:connect(function()
	_18active = not _18active
	if _18active then
		_18.BackgroundColor3 = loc
		for i,v in pairs(GetPlayer(EnterUsername.Text))do
			track:Play()
			game:GetService('RunService').Stepped:connect(function()
				if _18active then
					game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players[v.Name].Character.HumanoidRootPart.CFrame
				end
			end)
		end
	else
		track:Stop()
		_18.BackgroundColor3 = col
	end
end)

AnimationId = "282574440"
local Anim = Instance.new("Animation")
Anim.AnimationId = "rbxassetid://"..AnimationId
local track = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
CarpetActive = false
game.Players.LocalPlayer.CharacterAdded:Connect(function(character)
    track = character:WaitForChild("Humanoid"):LoadAnimation(Anim)
    CarpetActive = false
end)
Carpet.MouseButton1Click:connect(function()
	CarpetActive = not CarpetActive
	if CarpetActive then
		Carpet.BackgroundColor3 = loc
		for i,v in pairs(GetPlayer(EnterUsername.Text))do
			track:Play()
			game:GetService('RunService').Stepped:connect(function()
				if CarpetActive then
					game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players[v.Name].Character.HumanoidRootPart.CFrame
				end
			end)
		end
	else
		track:Stop()
		Carpet.BackgroundColor3 = col
	end
end)

AnimationId = "215384594"
local Anim = Instance.new("Animation")
Anim.AnimationId = "rbxassetid://"..AnimationId
local track = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
ExperimentalAnimationActive = false
game.Players.LocalPlayer.CharacterAdded:Connect(function(character)
    track = character:WaitForChild("Humanoid"):LoadAnimation(Anim)
    ExperimentalAnimationActive = false
end)
ExperimentalAnimation.MouseButton1Click:connect(function()
	ExperimentalAnimationActive = not ExperimentalAnimationActive
	if ExperimentalAnimationActive then
		ExperimentalAnimation.BackgroundColor3 = loc
		for i,v in pairs(GetPlayer(EnterUsername.Text))do
			track:Play(0.1, 1, 5)
			game:GetService('RunService').Stepped:connect(function()
				if ExperimentalAnimationActive then
					game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players[v.Name].Character.HumanoidRootPart.CFrame
				end
			end)
		end
	else
		track:Stop()
		ExperimentalAnimation.BackgroundColor3 = col
	end
end)

AnimationId = "429703734"
local Anim = Instance.new("Animation")
Anim.AnimationId = "rbxassetid://"..AnimationId
local track = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
DanceActive = false
game.Players.LocalPlayer.CharacterAdded:Connect(function(character)
    track = character:WaitForChild("Humanoid"):LoadAnimation(Anim)
    DanceActive = false
end)
Dance.MouseButton1Click:connect(function()
	DanceActive = not DanceActive
	if DanceActive then
		Dance.BackgroundColor3 = loc
		for i,v in pairs(GetPlayer(EnterUsername.Text))do
			track:Play()
			game:GetService('RunService').Stepped:connect(function()
				if DanceActive then
					game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players[v.Name].Character.HumanoidRootPart.CFrame
				end
			end)
		end
	else
		track:Stop()
		Dance.BackgroundColor3 = col
	end
end)

AnimationId = "282574440"
local Anim = Instance.new("Animation")
Anim.AnimationId = "rbxassetid://"..AnimationId
local track = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
HideActive = false
game.Players.LocalPlayer.CharacterAdded:Connect(function(character)
    track = character:WaitForChild("Humanoid"):LoadAnimation(Anim)
    HideActive = false
end)
Hide.MouseButton1Click:connect(function()
	HideActive = not HideActive
	if HideActive then
		Hide.BackgroundColor3 = loc
		for i,v in pairs(GetPlayer(EnterUsername.Text))do
			track:Play()
			game:GetService('RunService').Stepped:connect(function()
				if HideActive then
					game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players[v.Name].Character.Head.CFrame
				end
			end)
		end
	else
		track:Stop()
		Hide.BackgroundColor3 = col
	end
end)

AnimationId = "313762630"
local Anim = Instance.new("Animation")
Anim.AnimationId = "rbxassetid://"..AnimationId
local track = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
LevitateOnActive = false
game.Players.LocalPlayer.CharacterAdded:Connect(function(character)
    track = character:WaitForChild("Humanoid"):LoadAnimation(Anim)
    LevitateOnActive = false
end)
LevitateOn.MouseButton1Click:connect(function()
	LevitateOnActive = not LevitateOnActive
	if LevitateOnActive then
		LevitateOn.BackgroundColor3 = loc
		for i,v in pairs(GetPlayer(EnterUsername.Text))do
			track:Play()
			game:GetService('RunService').Stepped:connect(function()
				if LevitateOnActive then
					game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players[v.Name].Character.HumanoidRootPart.CFrame
				end
			end)
		end
	else
		track:Stop()
		LevitateOn.BackgroundColor3 = col
	end
end)

AnimationId = "215384594"
local Anim = Instance.new("Animation")
Anim.AnimationId = "rbxassetid://"..AnimationId
local track = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
PushLockActive = false
game.Players.LocalPlayer.CharacterAdded:Connect(function(character)
    track = character:WaitForChild("Humanoid"):LoadAnimation(Anim)
    PushLockActive = false
end)
PushLock.MouseButton1Click:connect(function()
	PushLockActive = not PushLockActive
	if PushLockActive then
		PushLock.BackgroundColor3 = loc
		for i,v in pairs(GetPlayer(EnterUsername.Text))do
			track:Play()
			game:GetService('RunService').Stepped:connect(function()
				if PushLockActive then
					game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players[v.Name].Character.HumanoidRootPart.CFrame
				end
			end)
		end
	else
		track:Stop()
		PushLock.BackgroundColor3 = col
	end
end)

AnimationId = "184574340"
local Anim = Instance.new("Animation")
Anim.AnimationId = "rbxassetid://"..AnimationId
local track = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
SlamOnActive = false
game.Players.LocalPlayer.CharacterAdded:Connect(function(character)
    track = character:WaitForChild("Humanoid"):LoadAnimation(Anim)
    SlamOnActive = false
end)
SlamOn.MouseButton1Click:connect(function()
	SlamOnActive = not SlamOnActive
	if SlamOnActive then
		SlamOn.BackgroundColor3 = loc
		for i,v in pairs(GetPlayer(EnterUsername.Text))do
			track:Play()
			game:GetService('RunService').Stepped:connect(function()
				if SlamOnActive then
					game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players[v.Name].Character.HumanoidRootPart.CFrame
				end
			end)
		end
	else
		track:Stop()
		SlamOn.BackgroundColor3 = col
	end
end)

------ BASIC -------------------------------------------------------------------------
------ BASIC -------------------------------------------------------------------------
------ BASIC -------------------------------------------------------------------------
------ BASIC -------------------------------------------------------------------------

HipHeight.MouseButton1Click:connect(function()
	game.Players.LocalPlayer.Character.Humanoid.HipHeight = STATCHANGE.Text
end)
JumpHeight.MouseButton1Click:connect(function()
	game.Players.LocalPlayer.Character.Humanoid.JumpPower = STATCHANGE.Text
end)
Speed.MouseButton1Click:connect(function()
	game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = STATCHANGE.Text
end)
Chat.MouseButton1Click:connect(function()
	game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer(CHATBOX.Text, "All")
end)
keepspam = false
Spam.MouseButton1Click:connect(function()
	keepspam = not keepspam
	if keepspam then
		Spam.BackgroundColor3 = loc
	else
		Spam.BackgroundColor3 = col
	end
	while wait(0.5) do
		if keepspam then
			game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer(CHATBOX.Text, "All")
		end
	end
end)
clip = true
Noclip.MouseButton1Click:connect(function()
	clip = not clip
	game:GetService('RunService').Stepped:connect(function()
		if not clip then
			Noclip.BackgroundColor3 = loc
			game.Players.LocalPlayer.Character.Head.CanCollide = false
			game.Players.LocalPlayer.Character.Torso.CanCollide = false
			game.Players.LocalPlayer.Character["Left Leg"].CanCollide = false
			game.Players.LocalPlayer.Character["Right Leg"].CanCollide = false
		else
			Noclip.BackgroundColor3 = col
		end
	end)
end)
local flying = false
Fly.MouseButton1Click:connect(function()
flying = not flying
repeat wait()
until game.Players.LocalPlayer and game.Players.LocalPlayer.Character and game.Players.LocalPlayer.Character:findFirstChild("Torso") and game.Players.LocalPlayer.Character:findFirstChild("Humanoid")
local mouse = game.Players.LocalPlayer:GetMouse()
repeat wait() until mouse
local plr = game.Players.LocalPlayer
local torso = plr.Character.Torso
local deb = true
local ctrl = {f = 0, b = 0, l = 0, r = 0}
local lastctrl = {f = 0, b = 0, l = 0, r = 0}
local maxspeed = 70
local speed = 0
if flying then
	Fly.BackgroundColor3 = loc
else
	Fly.BackgroundColor3 = col
end
 
function FlyFunction()
local bg = Instance.new("BodyGyro", torso)
bg.P = 9e4
bg.maxTorque = Vector3.new(9e9, 9e9, 9e9)
bg.cframe = torso.CFrame
local bv = Instance.new("BodyVelocity", torso)
bv.velocity = Vector3.new(0,0.1,0)
bv.maxForce = Vector3.new(9e9, 9e9, 9e9)
repeat wait()
plr.Character.Humanoid.PlatformStand = true
if ctrl.l + ctrl.r ~= 0 or ctrl.f + ctrl.b ~= 0 then
speed = speed+.5+(speed/maxspeed)
if speed > maxspeed then
speed = maxspeed
end
elseif not (ctrl.l + ctrl.r ~= 0 or ctrl.f + ctrl.b ~= 0) and speed ~= 0 then
speed = speed-1
if speed < 0 then
speed = 0
end
end
if (ctrl.l + ctrl.r) ~= 0 or (ctrl.f + ctrl.b) ~= 0 then
bv.velocity = ((game.Workspace.CurrentCamera.CoordinateFrame.lookVector * (ctrl.f+ctrl.b)) + ((game.Workspace.CurrentCamera.CoordinateFrame * CFrame.new(ctrl.l+ctrl.r,(ctrl.f+ctrl.b)*.2,0).p) - game.Workspace.CurrentCamera.CoordinateFrame.p))*speed
lastctrl = {f = ctrl.f, b = ctrl.b, l = ctrl.l, r = ctrl.r}
elseif (ctrl.l + ctrl.r) == 0 and (ctrl.f + ctrl.b) == 0 and speed ~= 0 then
bv.velocity = ((game.Workspace.CurrentCamera.CoordinateFrame.lookVector * (lastctrl.f+lastctrl.b)) + ((game.Workspace.CurrentCamera.CoordinateFrame * CFrame.new(lastctrl.l+lastctrl.r,(lastctrl.f+lastctrl.b)*.2,0).p) - game.Workspace.CurrentCamera.CoordinateFrame.p))*speed
else
bv.velocity = Vector3.new(0,0.1,0)
end
bg.cframe = game.Workspace.CurrentCamera.CoordinateFrame * CFrame.Angles(-math.rad((ctrl.f+ctrl.b)*50*speed/maxspeed),0,0)
until not flying
ctrl = {f = 0, b = 0, l = 0, r = 0}
lastctrl = {f = 0, b = 0, l = 0, r = 0}
speed = 0
bg:Destroy()
bv:Destroy()
plr.Character.Humanoid.PlatformStand = false
end
mouse.KeyDown:connect(function(key)
if key:lower() == "w" then
ctrl.f = 1
elseif key:lower() == "s" then
ctrl.b = -1
elseif key:lower() == "a" then
ctrl.l = -1
elseif key:lower() == "d" then
ctrl.r = 1
end
end)
mouse.KeyUp:connect(function(key)
if key:lower() == "w" then
ctrl.f = 0
elseif key:lower() == "s" then
ctrl.b = 0
elseif key:lower() == "a" then
ctrl.l = 0
elseif key:lower() == "d" then
ctrl.r = 0
end
end)
FlyFunction()
end)

------ EXTRA -------------------------------------------------------------------------
------ EXTRA -------------------------------------------------------------------------
------ EXTRA -------------------------------------------------------------------------
------ EXTRA -------------------------------------------------------------------------

frost = false
Freeze.MouseButton1Click:connect(function()
	frost = not frost
	if frost then
		game.Players.LocalPlayer.Character.Torso.Anchored = true
		game.Players.LocalPlayer.Character.Head.Anchored = true
		game.Players.LocalPlayer.Character["Left Leg"].Anchored = true
		game.Players.LocalPlayer.Character["Left Arm"].Anchored = true
		game.Players.LocalPlayer.Character["Right Leg"].Anchored = true
		game.Players.LocalPlayer.Character["Right Arm"].Anchored = true
		Freeze.BackgroundColor3 = loc
	else
		game.Players.LocalPlayer.Character.Torso.Anchored = false
		game.Players.LocalPlayer.Character.Head.Anchored = false
		game.Players.LocalPlayer.Character["Left Leg"].Anchored = false
		game.Players.LocalPlayer.Character["Left Arm"].Anchored = false
		game.Players.LocalPlayer.Character["Right Leg"].Anchored = false
		game.Players.LocalPlayer.Character["Right Arm"].Anchored = false
		Freeze.BackgroundColor3 = col
	end
end)
insanity = false
local Anim = Instance.new("Animation")
AnimationId = "33796059"
Anim.AnimationId = "rbxassetid://"..AnimationId
local track = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
game.Players.LocalPlayer.CharacterAdded:Connect(function(character)
    track = character:WaitForChild("Humanoid"):LoadAnimation(Anim)
    insanity = false
end)
Insane.MouseButton1Down:connect(function()
	insanity = not insanity
	if insanity then
		track:Play(0.1, 1, 999)
		Insane.BackgroundColor3 = loc
	else
		track:Stop()
		Insane.BackgroundColor3 = col
	end
end)
Sit.MouseButton1Click:connect(function()
	game.Players.LocalPlayer.Character.Humanoid.Sit = true
end)
Jump.MouseButton1Click:connect(function()
	game.Players.LocalPlayer.Character.Humanoid.Jump = true
end)
platform = false
PlatformStand.MouseButton1Click:connect(function()
	platform = not platform
	if platform then
		game.Players.LocalPlayer.Character.Humanoid.PlatformStand = true
		PlatformStand.BackgroundColor3 = loc
	else
		game.Players.LocalPlayer.Character.Humanoid.PlatformStand = false
		PlatformStand.BackgroundColor3 = col
	end
end)
TPVoid.MouseButton1Click:connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(math.huge, math.huge, math.huge)
end)

local Anim = Instance.new("Animation")
Anim.AnimationId = "rbxassetid://204295235"
local track = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
question = false
game.Players.LocalPlayer.CharacterAdded:Connect(function(character)
    track = character:WaitForChild("Humanoid"):LoadAnimation(Anim)
    question = false
end)
Unknown.MouseButton1Click:connect(function()
	question = not question
	if question then
		Unknown.BackgroundColor3 = loc
		while wait do
			if track.IsPlaying == false then
				if question then
					track:Play(0.1, 1, 1e5)
				end
			end
		end
	else
		Unknown.BackgroundColor3 = col
		track:Stop()
	end
end)

Reset.MouseButton1Click:connect(function()
	game.Players.LocalPlayer.Character.Head:Destroy()
end)

------ LOCALPLAYER -------------------------------------------------------------------------
------ LOCALPLAYER -------------------------------------------------------------------------
------ LOCALPLAYER -------------------------------------------------------------------------
------ LOCALPLAYER -------------------------------------------------------------------------

local Anim = Instance.new("Animation")
Anim.AnimationId = "rbxassetid://215384594"
local track = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
local CloneIllusionACTIVE = false
game.Players.LocalPlayer.CharacterAdded:Connect(function(character)
    track = character:WaitForChild("Humanoid"):LoadAnimation(Anim)
    CloneIllusionACTIVE = false
end)
CloneIllusion.MouseButton1Click:connect(function()
	CloneIllusionACTIVE = not CloneIllusionACTIVE
	if CloneIllusionACTIVE then
		track:Play(.5, 1, 1e7)
		CloneIllusion.BackgroundColor3 = loc
	else
		track:Stop()
		CloneIllusion.BackgroundColor3 = col
	end
end)

local Anim = Instance.new("Animation")
Anim.AnimationId = "rbxassetid://204328711"
local track = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
local DinoWalkACTIVE = false
game.Players.LocalPlayer.CharacterAdded:Connect(function(character)
    track = character:WaitForChild("Humanoid"):LoadAnimation(Anim)
    DinoWalkACTIVE = false
end)
Dinosaur.MouseButton1Click:connect(function()
	DinoWalkACTIVE = not DinoWalkACTIVE
	if DinoWalkACTIVE then
		track:Play(.1, 1, 1)
		Dinosaur.BackgroundColor3 = loc
		game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 30
		game.Players.LocalPlayer.Character.Humanoid.JumpHeight = 200
	else
		track:Stop()
		Dinosaur.BackgroundColor3 = col
		game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 16
		game.Players.LocalPlayer.Character.Humanoid.JumpHeight = 50
	end
end)

local Anim = Instance.new("Animation")
Anim.AnimationId = "rbxassetid://313762630"
local track = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
local GlitchLevitateACTIVE = false
game.Players.LocalPlayer.CharacterAdded:Connect(function(character)
    track = character:WaitForChild("Humanoid"):LoadAnimation(Anim)
    GlitchLevitateACTIVE = false
end)
Glitchy.MouseButton1Click:connect(function()
	GlitchLevitateACTIVE = not GlitchLevitateACTIVE
	if GlitchLevitateACTIVE then
		track:Play(.5, 1, 1e7)
		Glitchy.BackgroundColor3 = loc
	else
		track:Stop()
		Glitchy.BackgroundColor3 = col
	end
end)

local Anim = Instance.new("Animation")
Anim.AnimationId = "rbxassetid://313762630"
local track = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
local LevitateACTIVE = false
game.Players.LocalPlayer.CharacterAdded:Connect(function(character)
    track = character:WaitForChild("Humanoid"):LoadAnimation(Anim)
    LevitateACTIVE = false
end)
Levitate.MouseButton1Click:connect(function()
	LevitateACTIVE = not LevitateACTIVE
	if LevitateACTIVE then
		track:Play(.1, 1, 1)
		Levitate.BackgroundColor3 = loc
	else
		track:Stop()
		Levitate.BackgroundColor3 = col
	end
end)

NoLimbs.MouseButton1Click:connect(function()
	game.Players.LocalPlayer.Character["Left Leg"]:Destroy()
	game.Players.LocalPlayer.Character["Left Arm"]:Destroy()
	game.Players.LocalPlayer.Character["Right Leg"]:Destroy()
	game.Players.LocalPlayer.Character["Right Arm"]:Destroy()
end)

local Anim = Instance.new("Animation")
Anim.AnimationId = "rbxassetid://180612465"
local track = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
local ScaredACTIVE = false
game.Players.LocalPlayer.CharacterAdded:Connect(function(character)
    track = character:WaitForChild("Humanoid"):LoadAnimation(Anim)
    ScaredACTIVE = false
end)
CrouchRocket.MouseButton1Click:connect(function()
	ScaredACTIVE = not ScaredACTIVE
	if ScaredACTIVE then
		local u = Instance.new("RocketPropulsion")
		u.Parent = game.Players.LocalPlayer.Character.HumanoidRootPart
		u.Name = "CrouchRocket"
		u.Target = game.Players.LocalPlayer.Character.Head
		u:Fire()
		CrouchRocket.BackgroundColor3 = loc
		while wait() do
		 if track.IsPlaying == false then
			if ScaredACTIVE then
				track:Play(.1, 1, 1)
			end
		 end
		end
	else
		track:Stop()
		CrouchRocket.BackgroundColor3 = col
		game.Players.LocalPlayer.Character.HumanoidRootPart.CrouchRocket:Destroy()
	end
end)

local Anim = Instance.new("Animation")
Anim.AnimationId = "rbxassetid://313762630"
local track = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
local Anim2 = Instance.new("Animation")
Anim2.AnimationId = "rbxassetid://35154961"
local track2 = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim2)
local Anim3 = Instance.new("Animation")
Anim3.AnimationId = "rbxassetid://33169583"
local track3 = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim3)
haunting = false
game.Players.LocalPlayer.CharacterAdded:Connect(function(character)
    track = character:WaitForChild("Humanoid"):LoadAnimation(Anim)
	track2 = character:WaitForChild("Humanoid"):LoadAnimation(Anim2)
	track3 = character:WaitForChild("Humanoid"):LoadAnimation(Anim3)
    haunting = false
end)
Haunted.MouseButton1Click:connect(function()
	haunting = not haunting
	if haunting then
		while true do
			if track3.IsPlaying == false then
				if haunting then
					track:Play()
					track2:Play(0.1,1,1000)
					track3:Play(0.1,1,1000)
				end
			end
		end
	else
		track:Stop()
		track2:Stop()
		track3:Stop()
	end
end)

spinning = false
CrazySpin.MouseButton1Click:connect(function()
	spinning = not spinning
	if spinning then
		local p = Instance.new("RocketPropulsion")
		p.Parent = game.Players.LocalPlayer.Character.HumanoidRootPart
		p.Name = "CrazySpin"
		p.Target = game.Players.LocalPlayer.Character["Left Arm"]
		p:Fire()
		CrazySpin.BackgroundColor3 = loc
	else
		game.Players.LocalPlayer.Character.HumanoidRootPart.CrazySpin:Destroy()
		CrazySpin.BackgroundColor3 = col
	end
end)

------ ROCKETPROPULSION -------------------------------------------------------------------------
------ ROCKETPROPULSION -------------------------------------------------------------------------
------ ROCKETPROPULSION -------------------------------------------------------------------------
------ ROCKETPROPULSION -------------------------------------------------------------------------

floating = false
Float.MouseButton1Click:connect(function()
	floating = not floating
	if floating then
		Float.BackgroundColor3 = loc
		local y = Instance.new("RocketPropulsion")
		y.Parent = game.Players.LocalPlayer.Character.HumanoidRootPart
		y.CartoonFactor = 1
		y.MaxThrust = 50000
		y.MaxSpeed = 1000
		y.ThrustP = 50000
		y.Name = "Float"
		for i,v in pairs(GetPlayer(EnterUsername.Text))do
			y.Target = game.Players[v.Name].Character.Head
			y:Fire()
			game:GetService('RunService').Stepped:connect(function()
				if floating then
					game.Players.LocalPlayer.Character.Head.CanCollide = false
					game.Players.LocalPlayer.Character.Torso.CanCollide = false
					game.Players.LocalPlayer.Character["Left Leg"].CanCollide = false
					game.Players.LocalPlayer.Character["Right Leg"].CanCollide = false
				end
			end)
			while wait(0.3) do
				if floating then
					game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players[v.Name].Character["Left Leg"].CFrame
				end
			end
		end
	else
		game.Players.LocalPlayer.Character.HumanoidRootPart.Float:Destroy()
		Float.BackgroundColor3 = col
	end
end)

local Anim = Instance.new("Animation")
Anim.AnimationId = "rbxassetid://282574440"
local track = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
flattening = false
Flatten.MouseButton1Click:connect(function()
	flattening = not flattening
	if flattening then
		Flatten.BackgroundColor3 = loc
		local y = Instance.new("RocketPropulsion")
		y.Parent = game.Players.LocalPlayer.Character.HumanoidRootPart
		y.CartoonFactor = 1
		y.MaxThrust = 50000
		y.MaxSpeed = 1000
		y.ThrustP = 50000
		y.Name = "Flatten"
		for i,v in pairs(GetPlayer(EnterUsername.Text))do
			y.Target = game.Players[v.name].Character["Left Leg"]
			y:Fire()
			track:Play(.1, 1, 1)
			game:GetService('RunService').Stepped:connect(function()
				if flattening then
					game.Players.LocalPlayer.Character.Head.CanCollide = false
					game.Players.LocalPlayer.Character.Torso.CanCollide = false
					game.Players.LocalPlayer.Character["Left Leg"].CanCollide = false
					game.Players.LocalPlayer.Character["Right Leg"].CanCollide = false
				end
			end)
			while wait(0.3) do
				if flattening then
					game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players[v.Name].Character.HumanoidRootPart.CFrame + Vector3.new(0,2,0)
				end
			end
		end
	else
		game.Players.LocalPlayer.Character.HumanoidRootPart.Flatten:Destroy()
		track:Stop()
		Flatten.BackgroundColor3 = col
	end
end)

pushing = false
Push.MouseButton1Click:connect(function()
	pushing = not pushing
	if pushing then
		Push.BackgroundColor3 = loc
		local b = Instance.new("RocketPropulsion")
		b.Parent = game.Players.LocalPlayer.Character.HumanoidRootPart
		b.TurnP = 2500
		b.MaxThrust = 50000
		b.MaxSpeed = 1000
		b.ThrustP = 50000
		b.CartoonFactor = 1
		b.Name = "Push"
		for i,v in pairs(GetPlayer(EnterUsername.Text))do
			b.Target = game.Players[v.Name].Character.HumanoidRootPart
			b:Fire()
			game:GetService('RunService').Stepped:connect(function()
				if pushing then
					game.Players.LocalPlayer.Character.Head.CanCollide = false
					game.Players.LocalPlayer.Character.Torso.CanCollide = false
					game.Players.LocalPlayer.Character["Left Leg"].CanCollide = false
					game.Players.LocalPlayer.Character["Right Leg"].CanCollide = false
				end
			end)
		end
	else
		game.Players.LocalPlayer.Character.HumanoidRootPart.Push:Destroy()
		Push.BackgroundColor3 = col
	end
end)

SlowAttracting = false
SlowAttract.MouseButton1Click:connect(function()
	SlowAttracting = not SlowAttracting
	if SlowAttracting then
		SlowAttract.BackgroundColor3 = loc
		local b = Instance.new("RocketPropulsion")
		b.Parent = game.Players.LocalPlayer.Character.HumanoidRootPart
		b.TurnD = 5000
		b.MaxThrust = 5000
		b.MaxSpeed = 200
		b.ThrustP = 5000
		b.CartoonFactor = 1
		b.Name = "SlowAttract"
		for i,v in pairs(GetPlayer(EnterUsername.Text))do
			b.Target = game.Players[v.Name].Character.HumanoidRootPart
			b:Fire()
			game:GetService('RunService').Stepped:connect(function()
				if SlowAttracting then
					game.Players.LocalPlayer.Character.Head.CanCollide = false
					game.Players.LocalPlayer.Character.Torso.CanCollide = false
					game.Players.LocalPlayer.Character["Left Leg"].CanCollide = false
					game.Players.LocalPlayer.Character["Right Leg"].CanCollide = false
				end
			end)
		end
	else
		game.Players.LocalPlayer.Character.HumanoidRootPart.SlowAttract:Destroy()
		SlowAttract.BackgroundColor3 = col
	end
end)

Maxing = false
Max.MouseButton1Click:connect(function()
	Maxing = not Maxing
	if Maxing then
		Max.BackgroundColor3 = loc
		local t1 = Instance.new("RocketPropulsion")
		t1.Parent = game.Players.LocalPlayer.Character.HumanoidRootPart
		t1.TurnP = 100000
		t1.MaxThrust = 100000
		t1.MaxSpeed = 5000
		t1.ThrustP = 100000
		t1.CartoonFactor = 1
		t1.Name = "one"
		local t2 = Instance.new("RocketPropulsion")
		t2.Parent = game.Players.LocalPlayer.Character.HumanoidRootPart
		t2.TurnP = 100000
		t2.MaxThrust = 100000
		t2.MaxSpeed = 5000
		t2.ThrustP = 100000
		t2.CartoonFactor = 1
		t2.Name = "two"
		local t3 = Instance.new("RocketPropulsion")
		t3.Parent = game.Players.LocalPlayer.Character.HumanoidRootPart
		t3.TurnP = 100000
		t3.MaxThrust = 100000
		t3.MaxSpeed = 5000
		t3.ThrustP = 100000
		t3.CartoonFactor = 1
		t3.Name = "three"
		local t4 = Instance.new("RocketPropulsion")
		t4.Parent = game.Players.LocalPlayer.Character.HumanoidRootPart
		t4.TurnP = 100000
		t4.MaxThrust = 100000
		t4.MaxSpeed = 5000
		t4.ThrustP = 100000
		t4.CartoonFactor = 1
		t4.Name = "four"
		local t5 = Instance.new("RocketPropulsion")
		t5.Parent = game.Players.LocalPlayer.Character.HumanoidRootPart
		t5.TurnP = 100000
		t5.MaxThrust = 100000
		t5.MaxSpeed = 5000
		t5.ThrustP = 100000
		t5.CartoonFactor = 1
		t5.Name = "five"
		local t6 = Instance.new("RocketPropulsion")
		t6.Parent = game.Players.LocalPlayer.Character.HumanoidRootPart
		t6.TurnP = 100000
		t6.MaxThrust = 100000
		t6.MaxSpeed = 5000
		t6.ThrustP = 100000
		t6.CartoonFactor = 1
		t6.Name = "six"
		for i,v in pairs(GetPlayer(EnterUsername.Text))do
			t1.Target = game.Players[v.Name].Character.Torso
			t1:Fire()
			t2.Target = game.Players[v.Name].Character["Right Leg"]
			t2:Fire()
			t3.Target = game.Players[v.Name].Character["Left Arm"]
			t3:Fire()
			t4.Target = game.Players[v.Name].Character["Left Leg"]
			t4:Fire()
			t5.Target = game.Players[v.Name].Character["Right Arm"]
			t5:Fire()
			t6.Target = game.Players[v.Name].Character.Head
			t6:Fire()
			game:GetService('RunService').Stepped:connect(function()
				if Maxing then
					game.Players.LocalPlayer.Character.Head.CanCollide = false
					game.Players.LocalPlayer.Character.Torso.CanCollide = false
					game.Players.LocalPlayer.Character["Left Leg"].CanCollide = false
					game.Players.LocalPlayer.Character["Right Leg"].CanCollide = false
				end
			end)
		end
	else
		game.Players.LocalPlayer.Character.HumanoidRootPart.one:Destroy()
		game.Players.LocalPlayer.Character.HumanoidRootPart.two:Destroy()
		game.Players.LocalPlayer.Character.HumanoidRootPart.three:Destroy()
		game.Players.LocalPlayer.Character.HumanoidRootPart.four:Destroy()
		game.Players.LocalPlayer.Character.HumanoidRootPart.five:Destroy()
		game.Players.LocalPlayer.Character.HumanoidRootPart.six:Destroy()
		Max.BackgroundColor3 = col
	end
end)

AimHeading = false
AimHead.MouseButton1Click:connect(function()
	AimHeading = not AimHeading
	if AimHeading then
		AimHead.BackgroundColor3 = loc
		local b = Instance.new("RocketPropulsion")
		b.Parent = game.Players.LocalPlayer.Character.HumanoidRootPart
		b.TurnP = 2500
		b.MaxThrust = 50000
		b.MaxSpeed = 1000
		b.ThrustP = 50000
		b.CartoonFactor = 1
		b.Name = "AimHead"
		for i,v in pairs(GetPlayer(EnterUsername.Text))do
			b.Target = game.Players[v.Name].Character.Head
			b:Fire()
			game:GetService('RunService').Stepped:connect(function()
				if AimHeading then
					game.Players.LocalPlayer.Character.Head.CanCollide = false
					game.Players.LocalPlayer.Character.Torso.CanCollide = false
					game.Players.LocalPlayer.Character["Left Leg"].CanCollide = false
					game.Players.LocalPlayer.Character["Right Leg"].CanCollide = false
				end
			end)
		end
	else
		game.Players.LocalPlayer.Character.HumanoidRootPart.AimHead:Destroy()
		AimHead.BackgroundColor3 = col
	end
end)

Experimentaling = false
Experimental.MouseButton1Click:connect(function()
	Experimentaling = not Experimentaling
	if Experimentaling then
		Experimental.BackgroundColor3 = loc
		local b = Instance.new("RocketPropulsion")
		b.Parent = game.Players.LocalPlayer.Character.HumanoidRootPart
		b.TurnP = 15000
		b.MaxThrust = 25000
		b.MaxSpeed = 15000
		b.ThrustP = 10000
		b.CartoonFactor = 1
		b.Name = "Experimental"
		for i,v in pairs(GetPlayer(EnterUsername.Text))do
			game.Workspace.CurrentCamera.CameraSubject = game.Players[v.Name].Character.Head
			b.Target = game.Players[v.Name].Character.Torso
			b:Fire()
			game:GetService('RunService').Stepped:connect(function()
				if Experimentaling then
					game.Players.LocalPlayer.Character.Head.CanCollide = false
					game.Players.LocalPlayer.Character.Torso.CanCollide = false
					game.Players.LocalPlayer.Character["Left Leg"].CanCollide = false
					game.Players.LocalPlayer.Character["Right Leg"].CanCollide = false
				end
			end)
		end
	else
		game.Players.LocalPlayer.Character.HumanoidRootPart.Experimental:Destroy()
		Experimental.BackgroundColor3 = col
		game.Workspace.CurrentCamera.CameraSubject = game.Players.LocalPlayer.Character.Head
	end
end)

Multipleing = false
Multiple.MouseButton1Click:connect(function()
	Multipleing = not Multipleing
	if Multipleing then
		Multiple.BackgroundColor3 = loc
		local t1 = Instance.new("RocketPropulsion")
		t1.Parent = game.Players.LocalPlayer.Character.HumanoidRootPart
		t1.TurnP = 30000
		t1.MaxThrust = 30000
		t1.MaxSpeed = 1000
		t1.ThrustP = 30000
		t1.CartoonFactor = 1
		t1.Name = "one"
		local t2 = Instance.new("RocketPropulsion")
		t2.Parent = game.Players.LocalPlayer.Character.HumanoidRootPart
		t2.TurnP = 30000
		t2.MaxThrust = 30000
		t2.MaxSpeed = 1000
		t2.ThrustP = 30000
		t2.CartoonFactor = 1
		t2.Name = "two"
		local t3 = Instance.new("RocketPropulsion")
		t3.Parent = game.Players.LocalPlayer.Character.HumanoidRootPart
		t3.TurnP = 30000
		t3.MaxThrust = 30000
		t3.MaxSpeed = 1000
		t3.ThrustP = 30000
		t3.CartoonFactor = 1
		t3.Name = "three"
		for i,v in pairs(GetPlayer(EnterUsername.Text))do
			t1.Target = game.Players[v.Name].Character.Torso
			t1:Fire()
			t2.Target = game.Players[v.Name].Character["Right Leg"]
			t2:Fire()
			t3.Target = game.Players[v.Name].Character["Left Arm"]
			t3:Fire()
			game:GetService('RunService').Stepped:connect(function()
				if Multipleing then
					game.Players.LocalPlayer.Character.Head.CanCollide = false
					game.Players.LocalPlayer.Character.Torso.CanCollide = false
					game.Players.LocalPlayer.Character["Left Leg"].CanCollide = false
					game.Players.LocalPlayer.Character["Right Leg"].CanCollide = false
				end
			end)
		end
	else
		game.Players.LocalPlayer.Character.HumanoidRootPart.one:Destroy()
		game.Players.LocalPlayer.Character.HumanoidRootPart.two:Destroy()
		game.Players.LocalPlayer.Character.HumanoidRootPart.three:Destroy()
		Multiple.BackgroundColor3 = col
	end
end)

------ TELEPORTATION -------------------------------------------------------------------------
------ TELEPORTATION -------------------------------------------------------------------------
------ TELEPORTATION -------------------------------------------------------------------------
------ TELEPORTATION -------------------------------------------------------------------------

LockOnACTIVE = false
LockOn.MouseButton1Click:connect(function()
	LockOnACTIVE = not LockOnACTIVE
	for i,v in pairs(GetPlayer(EnterUsername.Text))do
		game:GetService('RunService').Stepped:connect(function()
			if LockOnACTIVE then
				game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players[v.Name].Character.HumanoidRootPart.CFrame
				LockOn.BackgroundColor3 = loc
				game:GetService('RunService').Stepped:connect(function()
					if LockOnACTIVE then
						game.Players.LocalPlayer.Character.Head.CanCollide = false
						game.Players.LocalPlayer.Character.Torso.CanCollide = false
						game.Players.LocalPlayer.Character["Left Leg"].CanCollide = false
						game.Players.LocalPlayer.Character["Right Leg"].CanCollide = false
					end
				end)
			else
				LockOn.BackgroundColor3 = col
			end
		end)
	end
end)

LockLegACTIVE = false
LockLeg.MouseButton1Click:connect(function()
	LockLegACTIVE = not LockLegACTIVE
	for i,v in pairs(GetPlayer(EnterUsername.Text))do
		game:GetService('RunService').Stepped:connect(function()
			if LockLegACTIVE then
				game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players[v.Name].Character["Left Leg"].CFrame
				LockLeg.BackgroundColor3 = loc
				game:GetService('RunService').Stepped:connect(function()
					if LockLegACTIVE then
						game.Players.LocalPlayer.Character.Head.CanCollide = false
						game.Players.LocalPlayer.Character.Torso.CanCollide = false
						game.Players.LocalPlayer.Character["Left Leg"].CanCollide = false
						game.Players.LocalPlayer.Character["Right Leg"].CanCollide = false
					end
				end)
			else
				LockLeg.BackgroundColor3 = col
			end
		end)
	end
end)

LockArmACTIVE = false
LockArm.MouseButton1Click:connect(function()
	LockArmACTIVE = not LockArmACTIVE
	for i,v in pairs(GetPlayer(EnterUsername.Text))do
		game:GetService('RunService').Stepped:connect(function()
			if LockArmACTIVE then
				game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players[v.Name].Character["Right Arm"].CFrame
				LockArm.BackgroundColor3 = loc
				game:GetService('RunService').Stepped:connect(function()
					if LockArmACTIVE then
						game.Players.LocalPlayer.Character.Head.CanCollide = false
						game.Players.LocalPlayer.Character.Torso.CanCollide = false
						game.Players.LocalPlayer.Character["Left Leg"].CanCollide = false
						game.Players.LocalPlayer.Character["Right Leg"].CanCollide = false
					end
				end)
			else
				LockArm.BackgroundColor3 = col
			end
		end)
	end
end)

LockHeadACTIVE = false
LockHead.MouseButton1Click:connect(function()
	LockHeadACTIVE = not LockHeadACTIVE
	for i,v in pairs(GetPlayer(EnterUsername.Text))do
		game:GetService('RunService').Stepped:connect(function()
			if LockHeadACTIVE then
				game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players[v.Name].Character.Head.CFrame
				LockHead.BackgroundColor3 = loc
				game:GetService('RunService').Stepped:connect(function()
					if LockHeadACTIVE then
						game.Players.LocalPlayer.Character.Head.CanCollide = false
						game.Players.LocalPlayer.Character.Torso.CanCollide = false
						game.Players.LocalPlayer.Character["Left Leg"].CanCollide = false
						game.Players.LocalPlayer.Character["Right Leg"].CanCollide = false
					end
				end)
			else
				LockHead.BackgroundColor3 = col
			end
		end)
	end
end)

LockAboveACTIVE = false
LockAbove.MouseButton1Click:connect(function()
	LockAboveACTIVE = not LockAboveACTIVE
	for i,v in pairs(GetPlayer(EnterUsername.Text))do
		game:GetService('RunService').Stepped:connect(function()
			if LockAboveACTIVE then
				game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players[v.Name].Character.HumanoidRootPart.CFrame + Vector3.new(0,4,0)
				LockAbove.BackgroundColor3 = loc
				game:GetService('RunService').Stepped:connect(function()
					if LockAboveACTIVE then
						game.Players.LocalPlayer.Character.Head.CanCollide = false
						game.Players.LocalPlayer.Character.Torso.CanCollide = false
						game.Players.LocalPlayer.Character["Left Leg"].CanCollide = false
						game.Players.LocalPlayer.Character["Right Leg"].CanCollide = false
					end
				end)
			else
				LockAbove.BackgroundColor3 = col
			end
		end)
	end
end)

LockMaxACTIVE = false
LockMax.MouseButton1Click:connect(function()
	LockMaxACTIVE = not LockMaxACTIVE
	for i,v in pairs(GetPlayer(EnterUsername.Text))do
		game:GetService('RunService').Stepped:connect(function()
			if LockMaxACTIVE then
				game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players[v.Name].Character.HumanoidRootPart.CFrame
				game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players[v.Name].Character.Head.CFrame
				game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players[v.Name].Character["Left Leg"].CFrame
				game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players[v.Name].Character["Left Arm"].CFrame
				game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players[v.Name].Character["Right Leg"].CFrame
				game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players[v.Name].Character["Right Arm"].CFrame
				LockMax.BackgroundColor3 = loc
				game:GetService('RunService').Stepped:connect(function()
					if LockMaxACTIVE then
						game.Players.LocalPlayer.Character.Head.CanCollide = false
						game.Players.LocalPlayer.Character.Torso.CanCollide = false
						game.Players.LocalPlayer.Character["Left Leg"].CanCollide = false
						game.Players.LocalPlayer.Character["Right Leg"].CanCollide = false
					end
				end)
			else
				LockMax.BackgroundColor3 = col
			end
		end)
	end
end)

TrailACTIVE = false
Trail.MouseButton1Click:connect(function()
	TrailACTIVE = not TrailACTIVE
	for i,v in pairs(GetPlayer(EnterUsername.Text))do
		game:GetService('RunService').Stepped:connect(function()
			if TrailACTIVE then
				game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players[v.Name].Character.HumanoidRootPart.CFrame + Vector3.new(5,0,0)
				Trail.BackgroundColor3 = loc
				game.Players.LocalPlayer.Character.Head.CanCollide = false
				game.Players.LocalPlayer.Character.Torso.CanCollide = false
				game.Players.LocalPlayer.Character["Left Leg"].CanCollide = false
				game.Players.LocalPlayer.Character["Right Leg"].CanCollide = false
			else
				Trail.BackgroundColor3 = col
			end
		end)
	end
end)

TeleportTo.MouseButton1Click:connect(function()
	for i,v in pairs(GetPlayer(EnterUsername.Text))do
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players[v.Name].Character.HumanoidRootPart.CFrame
	end
end)

------ TOOLS -------------------------------------------------------------------------
------ TOOLS -------------------------------------------------------------------------
------ TOOLS -------------------------------------------------------------------------
------ TOOLS -------------------------------------------------------------------------

Attach.MouseButton1Click:connect(function()
	for i,v in pairs(GetPlayer(EnterUsername.Text))do
		game.Players.LocalPlayer.Character.Humanoid.Name = 1
		local l = game.Players.LocalPlayer.Character["1"]:Clone()
		l.Parent = game.Players.LocalPlayer.Character
		l.Name = "Humanoid"
		wait(0.1)
		game.Players.LocalPlayer.Character["1"]:Destroy()
		game.Workspace.CurrentCamera.CameraSubject = game.Players.LocalPlayer.Character
		game.Players.LocalPlayer.Character.Animate.Disabled = true
		wait(0.1)
		game.Players.LocalPlayer.Character.Animate.Disabled = false
		game.Players.LocalPlayer.Character.Humanoid.DisplayDistanceType = "None"
		for i,v in pairs(game:GetService'Players'.LocalPlayer.Backpack:GetChildren())do
		game.Players.LocalPlayer.Character.Humanoid:EquipTool(v)
		end
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players[v.Name].Character["Left Arm"].CFrame
	end
end)

AttachExperimental.MouseButton1Click:connect(function()
	for i,v in pairs(GetPlayer(EnterUsername.Text))do
		game.Players.LocalPlayer.Character.Humanoid.Name = 1
		local l = game.Players.LocalPlayer.Character["1"]:Clone()
		l.Parent = game.Players.LocalPlayer.Character
		l.Name = "Humanoid"
		wait(0.1)
		game.Players.LocalPlayer.Character["1"]:Destroy()
		game.Workspace.CurrentCamera.CameraSubject = game.Players.LocalPlayer.Character
		game.Players.LocalPlayer.Character.Animate.Disabled = true
		wait(0.1)
		game.Players.LocalPlayer.Character.Animate.Disabled = false
		game.Players.LocalPlayer.Character.Humanoid.DisplayDistanceType = "None"
		for i,v in pairs(game:GetService'Players'.LocalPlayer.Backpack:GetChildren())do
		game.Players.LocalPlayer.Character.Humanoid:EquipTool(v)
		end
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players[v.Name].Character["Left Arm"].CFrame
		wait(1)
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(0,100,0)
	end
end)

Bring.MouseButton1Click:connect(function()
	for i,v in pairs(GetPlayer(EnterUsername.Text))do
		local NOW = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
		game.Players.LocalPlayer.Character.Humanoid.Name = 1
		local l = game.Players.LocalPlayer.Character["1"]:Clone()
		l.Parent = game.Players.LocalPlayer.Character
		l.Name = "Humanoid"
		wait(0.1)
		game.Players.LocalPlayer.Character["1"]:Destroy()
		game.Workspace.CurrentCamera.CameraSubject = game.Players.LocalPlayer.Character
		game.Players.LocalPlayer.Character.Animate.Disabled = true
		wait(0.1)
		game.Players.LocalPlayer.Character.Animate.Disabled = false
		game.Players.LocalPlayer.Character.Humanoid.DisplayDistanceType = "None"
		for i,v in pairs(game:GetService'Players'.LocalPlayer.Backpack:GetChildren())do
		game.Players.LocalPlayer.Character.Humanoid:EquipTool(v)
		end
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players[v.Name].Character.HumanoidRootPart.CFrame
		wait(0.2)
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players[v.Name].Character.HumanoidRootPart.CFrame
		wait(0.6)
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = NOW
		wait(0.6)
		game.Players.LocalPlayer.Character:MoveTo(game.Players[v.Name].Character.Position)
	end
end)

FreeFall.MouseButton1Click:connect(function()
	for i,v in pairs(GetPlayer(EnterUsername.Text))do
		local NOW = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
		game.Players.LocalPlayer.Character.Humanoid.Name = 1
		local l = game.Players.LocalPlayer.Character["1"]:Clone()
		l.Parent = game.Players.LocalPlayer.Character
		l.Name = "Humanoid"
		wait(0.1)
		game.Players.LocalPlayer.Character["1"]:Destroy()
		game.Workspace.CurrentCamera.CameraSubject = game.Players.LocalPlayer.Character
		game.Players.LocalPlayer.Character.Animate.Disabled = true
		wait(0.1)
		game.Players.LocalPlayer.Character.Animate.Disabled = false
		game.Players.LocalPlayer.Character.Humanoid.DisplayDistanceType = "None"
		for i,v in pairs(game:GetService'Players'.LocalPlayer.Backpack:GetChildren())do
		game.Players.LocalPlayer.Character.Humanoid:EquipTool(v)
		end
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players[v.Name].Character.HumanoidRootPart.CFrame
		wait(0.2)
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players[v.Name].Character.HumanoidRootPart.CFrame
		wait(0.6)
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = NOW
		wait(0.6)
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(0,50000,0)
	end
end)

GiveTool.MouseButton1Click:connect(function()
	for i,v in pairs(GetPlayer(EnterUsername.Text))do
		game.Players.LocalPlayer.Character.Humanoid.Name = 1
		local l = game.Players.LocalPlayer.Character["1"]:Clone()
		l.Parent = game.Players.LocalPlayer.Character
		l.Name = "Humanoid"
		wait(0.1)
		game.Players.LocalPlayer.Character["1"]:Destroy()
		game.Workspace.CurrentCamera.CameraSubject = game.Players.LocalPlayer.Character
		game.Players.LocalPlayer.Character.Animate.Disabled = true
		wait(0.1)
		game.Players.LocalPlayer.Character.Animate.Disabled = false
		game.Players.LocalPlayer.Character.Humanoid.DisplayDistanceType = "None"
		for i,v in pairs(game:GetService'Players'.LocalPlayer.Backpack:GetChildren())do
		game.Players.LocalPlayer.Character.Humanoid:EquipTool(v)
		end
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players[v.Name].Character.HumanoidRootPart.CFrame
		wait(0.2)
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players[v.Name].Character.HumanoidRootPart.CFrame
		wait(0.6)
		game.Players.LocalPlayer.Character:MoveTo(game.Players[v.Name].Character.Position)
	end
end)

KillSurvive.MouseButton1Click:connect(function()
	for i,v in pairs(GetPlayer(EnterUsername.Text))do
		local NOW = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
		game.Players.LocalPlayer.Character.Humanoid.Name = 1
		local l = game.Players.LocalPlayer.Character["1"]:Clone()
		l.Parent = game.Players.LocalPlayer.Character
		l.Name = "Humanoid"
		wait(0.1)
		game.Players.LocalPlayer.Character["1"]:Destroy()
		game.Workspace.CurrentCamera.CameraSubject = game.Players.LocalPlayer.Character
		game.Players.LocalPlayer.Character.Animate.Disabled = true
		wait(0.1)
		game.Players.LocalPlayer.Character.Animate.Disabled = false
		game.Players.LocalPlayer.Character.Humanoid.DisplayDistanceType = "None"
		for i,v in pairs(game:GetService'Players'.LocalPlayer.Backpack:GetChildren())do
		game.Players.LocalPlayer.Character.Humanoid:EquipTool(v)
		end
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players[v.Name].Character.HumanoidRootPart.CFrame
		wait(0.2)
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players[v.Name].Character.HumanoidRootPart.CFrame
		wait(0.4)
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(Vector3.new(10000, 10000, 10000))
		wait(0.8)
		game.Players.LocalPlayer.Character:MoveTo(game.Players[v.Name].Character.Position)
		wait(0.8)
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = NOW
	end
end)

Kill.MouseButton1Click:connect(function()
	for i,v in pairs(GetPlayer(EnterUsername.Text))do
		game.Players.LocalPlayer.Character.Humanoid.Name = 1
		local l = game.Players.LocalPlayer.Character["1"]:Clone()
		l.Parent = game.Players.LocalPlayer.Character
		l.Name = "Humanoid"
		wait(0.1)
		game.Players.LocalPlayer.Character["1"]:Destroy()
		game.Workspace.CurrentCamera.CameraSubject = game.Players.LocalPlayer.Character
		game.Players.LocalPlayer.Character.Animate.Disabled = true
		wait(0.1)
		game.Players.LocalPlayer.Character.Animate.Disabled = false
		game.Players.LocalPlayer.Character.Humanoid.DisplayDistanceType = "None"
		for i,v in pairs(game:GetService'Players'.LocalPlayer.Backpack:GetChildren())do
		game.Players.LocalPlayer.Character.Humanoid:EquipTool(v)
		end
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players[v.Name].Character.HumanoidRootPart.CFrame
		wait(0.2)
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players[v.Name].Character.HumanoidRootPart.CFrame
		wait(0.4)
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(Vector3.new(10000, 10000, 10000))
	end
end)

superspinning = false
SuperSpin.MouseButton1Click:connect(function()
	superspinning = not superspinning
	if superspinning then
		SuperSpin.BackgroundColor3 = loc
		for i,v in pairs(GetPlayer(EnterUsername.Text))do
			game.Players.LocalPlayer.Character.Humanoid.Name = 1
			local l = game.Players.LocalPlayer.Character["1"]:Clone()
			l.Parent = game.Players.LocalPlayer.Character
			l.Name = "Humanoid"
			wait(0.1)
			game.Players.LocalPlayer.Character["1"]:Destroy()
			game.Workspace.CurrentCamera.CameraSubject = game.Players.LocalPlayer.Character
			game.Players.LocalPlayer.Character.Animate.Disabled = true
			wait(0.1)
			game.Players.LocalPlayer.Character.Animate.Disabled = false
			game.Players.LocalPlayer.Character.Humanoid.DisplayDistanceType = "None"
			for i,v in pairs(game:GetService'Players'.LocalPlayer.Backpack:GetChildren())do
			game.Players.LocalPlayer.Character.Humanoid:EquipTool(v)
			end
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players[v.Name].Character["Left Arm"].CFrame
			wait(1)
			while wait() do
				if superspinning then
					game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players[v.Name].Character.HumanoidRootPart.CFrame
				end
			end
		end
	else
		SuperSpin.BackgroundColor3 = col
	end
end)
end)


MainSection:NewButton("backflips", "oh no dont hurt your head", function()
    loadstring(game:HttpGet('https://pastebin.com/raw/yjxXnxbS'))()
end)

MainSection:NewToggle("super-human", "go fast and jump realy high", function(state)
    if state then
        game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 120
        game.Players.LocalPlayer.Character.Humanoid.JumpPower = 120
    else
        game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 16
        game.Players.LocalPlayer.Character.Humanoid.JumpPower = 50
    end
end)


--LOCAL PLAYER
local Player = Window:NewTab("Player")
local PlayerSection = Player:NewSection("Player")

PlayerSection:NewSlider("Walkspeed", "changes ur walkspeed", 500, 16, function(s) -- 500 (MaxValue) | 0 (MinValue)
    game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = s
end)

PlayerSection:NewSlider("JumpPower", "JumpPower", 500, 16, function(s) -- 500 (MaxValue) | 0 (MinValue)
    game.Players.LocalPlayer.Character.Humanoid.JumpPower = s
end)

PlayerSection:NewButton("infinite jump", "ahh dont fall", function()
    local InfiniteJumpEnabled = true
game:GetService("UserInputService").JumpRequest:connect(function()
	if InfiniteJumpEnabled then
		game:GetService"Players".LocalPlayer.Character:FindFirstChildOfClass'Humanoid':ChangeState("Jumping")
	end
end)
end)

local Animations = Window:NewTab("Animations")
local AnimationsSection = Animations:NewSection("Animations")


AnimationsSection:NewButton("rickroll", "just rickroll peoople", function()
   game:GetService("StarterGui"):SetCore("SendNotification", { 
	Title = "Melon's (FE) Scripts";
	Text = "Loading, enjoy!";
	Icon = "rbxthumb://type=Asset&id=7969699183&w=150&h=150"})
Duration = 16;
HumanDied = false
local CountSCIFIMOVIELOL = 1
function SCIFIMOVIELOL(Part0,Part1,Position,Angle)
	local AlignPos = Instance.new('AlignPosition', Part1); AlignPos.Name = "AliP_"..CountSCIFIMOVIELOL
	AlignPos.ApplyAtCenterOfMass = true;
	AlignPos.MaxForce = 5772000--67752;
	AlignPos.MaxVelocity = math.huge/9e110;
	AlignPos.ReactionForceEnabled = false;
	AlignPos.Responsiveness = 200;
	AlignPos.RigidityEnabled = false;
	local AlignOri = Instance.new('AlignOrientation', Part1); AlignOri.Name = "AliO_"..CountSCIFIMOVIELOL
	AlignOri.MaxAngularVelocity = math.huge/9e110;
	AlignOri.MaxTorque = 5772000
	AlignOri.PrimaryAxisOnly = false;
	AlignOri.ReactionTorqueEnabled = false;
	AlignOri.Responsiveness = 200;
	AlignOri.RigidityEnabled = false;
	local AttachmentA=Instance.new('Attachment',Part1); AttachmentA.Name = "Ath_"..CountSCIFIMOVIELOL
	local AttachmentB=Instance.new('Attachment',Part0); AttachmentB.Name = "Ath_"..CountSCIFIMOVIELOL
	AttachmentA.Orientation = Angle or Vector3.new(0,0,0)
	AttachmentA.Position = Position or Vector3.new(0,0,0)
	AlignPos.Attachment1 = AttachmentA;
	AlignPos.Attachment0 = AttachmentB;
	AlignOri.Attachment1 = AttachmentA;
	AlignOri.Attachment0 = AttachmentB;
	CountSCIFIMOVIELOL = CountSCIFIMOVIELOL + 1
	return {AlignPos,AlignOri,AttachmentA,AttachmentB}
end

if _G.netted ~= true then
	_G.netted = true
	coroutine.wrap(function()
		settings().Physics.PhysicsEnvironmentalThrottle = Enum.EnviromentalPhysicsThrottle.Disabled
		settings().Physics.AllowSleep = false
		game:GetService("RunService").RenderStepped:Connect(function()
			game:FindFirstChildOfClass("Players").LocalPlayer.MaximumSimulationRadius=math.pow(math.huge,math.huge)
			sethiddenproperty(game:FindFirstChildOfClass("Players").LocalPlayer,"SimulationRadius",math.huge*math.huge)
		end)
	end)()
end

game:FindFirstChildOfClass("Players").LocalPlayer["Character"].Archivable = true
local hatnameclone = {}
for _,v in next, game:FindFirstChildOfClass("Players").LocalPlayer["Character"]:GetChildren() do
	if v:IsA("Accessory") then
		if hatnameclone[v.Name] then
			if hatnameclone[v.Name] == "s" then
				hatnameclone[v.Name] = {}
			end
			table.insert(hatnameclone[v.Name],v)
		else
			hatnameclone[v.Name] = "s"
		end
	end
end
for _,v in pairs(hatnameclone) do
	if type(v) == "table" then
		local num = 1
		for _,w in pairs(v) do
			w.Name = w.Name..num
			num = num + 1
		end
	end
end
hatnameclone = nil

local DeadChar = game:FindFirstChildOfClass("Players").LocalPlayer.Character

local fldr = Instance.new("Folder",game:FindFirstChildOfClass("Players").LocalPlayer["Character"])
fldr.Name = "DMYF"
local CloneChar = DeadChar:Clone()
local ANIMATIONHERE
if CloneChar:FindFirstChild("Animate") then
	ANIMATIONHERE = CloneChar:FindFirstChild("Animate"):Clone()
	CloneChar:FindFirstChild("Animate"):Destroy()
end
if CloneChar:FindFirstChildOfClass("Folder") then CloneChar:FindFirstChildOfClass("Folder"):Destroy() end
if CloneChar.Torso:FindFirstChild("Neck") then
	local Clonessss = CloneChar.Torso:FindFirstChild("Neck"):Clone()
	Clonessss.Part0 = nil
	Clonessss.Part1 = DeadChar.Head
	Clonessss.Parent = DeadChar.Torso
end
CloneChar.Parent = fldr
CloneChar.HumanoidRootPart.CFrame = DeadChar.HumanoidRootPart.CFrame
CloneChar.Humanoid.BreakJointsOnDeath = false
CloneChar.Name = "non"
CloneChar.Humanoid.DisplayDistanceType = "None"

for _,v in next, DeadChar:GetChildren() do
	if v:IsA("Accessory") then
		local topacc = false
		if v.Handle:FindFirstChildOfClass("Weld") then v.Handle:FindFirstChildOfClass("Weld"):Destroy() end
		v.Handle.Massless = true
		v.Handle.CanCollide = false
		if v.Handle:FindFirstChildOfClass("Attachment") then
			local ath__ = v.Handle:FindFirstChildOfClass("Attachment")
			if ath__.Name == "HatAttachment" or ath__.Name == "HairAttachment" or ath__.Name == "FaceFrontAttachment" or ath__.Name == "FaceCenterAttachment" then
				topacc = ath__.Name
			end
		end
        local bv = Instance.new("BodyVelocity",v.Handle)
		bv.Velocity = Vector3.new(0,0,0)
		coroutine.wrap(function()
			if topacc then
				local allthings = SCIFIMOVIELOL(v.Handle,DeadChar.Torso,Vector3.new(0,1.5,0)+ (DeadChar.Head[topacc].Position + (v.Handle[topacc].Position*-1)),Vector3.new(0,0,0))
				local normaltop = allthings[1].Attachment1
				local alipos = allthings[1]
				local alirot = allthings[2]
				local p0 = v.Handle
				local p1 = DeadChar.Head
				alipos.Parent = CloneChar:FindFirstChild(v.Name).Handle
				alirot.Parent = CloneChar:FindFirstChild(v.Name).Handle
				while true do
					game:GetService("RunService").RenderStepped:wait()
					if HumanDied then break end
					coroutine.wrap(function()
						if alipos.Attachment1 == normaltop then
							p0.CFrame = p0.CFrame:lerp((((DeadChar.Torso.CFrame * CFrame.new(0,1.5,0)) * p1[topacc].CFrame) * p0[topacc].CFrame:inverse()),1)
						else
							v.Handle.CFrame = v.Handle.CFrame:lerp(alipos.Attachment1.Parent.CFrame * CFrame.new(alipos.Attachment1.Position) * CFrame.Angles(math.rad(alipos.Attachment1.Rotation.X),math.rad(alipos.Attachment1.Rotation.Y),math.rad(alipos.Attachment1.Rotation.Z)),1)
						end
					end)()
				end
			else
				SCIFIMOVIELOL(v.Handle,CloneChar[v.Name].Handle,Vector3.new(0,0,0),Vector3.new(0,0,0))
			end
		end)()
    end
end

local a = DeadChar.Torso
local b = DeadChar.HumanoidRootPart
local c = DeadChar.Humanoid
a.Parent = game:FindFirstChildOfClass("Workspace")
c.Parent = game:FindFirstChildOfClass("Workspace")
local told = a:Clone()
local told1 = c:Clone()
b["RootJoint"].Part0 = told
b["RootJoint"].Part1 = DeadChar.Head
a.Name = "torso"
a.Neck:Destroy()
c.Name = "Cloned Avatar"
told.Parent = DeadChar
told1.Parent = DeadChar
DeadChar.PrimaryPart = told
told1.Health = 0
b:Destroy()
a.Parent = DeadChar
c.Parent = DeadChar
told:Destroy()
told1:Destroy()
a.Name = "Torso"

if CloneChar.Head:FindFirstChildOfClass("Decal") then CloneChar.Head:FindFirstChildOfClass("Decal").Transparency = 1 end
if DeadChar:FindFirstChild("Animate") then DeadChar:FindFirstChild("Animate"):Destroy() end

local Collider
function UnCollide()
    if HumanDied then Collider:Disconnect(); return end
    --[[for _,Parts in next, CloneChar:GetChildren() do
        if Parts:IsA("BasePart") then
            Parts.CanCollide = false 
        end 
    end]]
    for _,Parts in next, DeadChar:GetChildren() do
        if Parts:IsA("BasePart") then
        Parts.CanCollide = false
        end 
    end 
end
Collider = game:GetService("RunService").Stepped:Connect(UnCollide)

local resetBindable = Instance.new("BindableEvent")
resetBindable.Event:connect(function()
    game:GetService("StarterGui"):SetCore("ResetButtonCallback", true)
	resetBindable:Destroy()
	HumanDied = true
    pcall(function()
		game:FindFirstChildOfClass("Players").LocalPlayer.Character = DeadChar
		DeadChar.Head:Destroy()
		DeadChar:FindFirstChildOfClass("Humanoid"):Destroy()
		game:FindFirstChildOfClass("Players").LocalPlayer.Character = CloneChar
		if DeadChar:FindFirstChildOfClass("Folder") then DeadChar:FindFirstChildOfClass("Folder"):Destroy() end
	end)
end)
game:GetService("StarterGui"):SetCore("ResetButtonCallback", resetBindable)

coroutine.wrap(function()
    while true do
        game:GetService("RunService").RenderStepped:wait()
        if not CloneChar or not CloneChar:FindFirstChild("Head") or not CloneChar:FindFirstChildOfClass("Humanoid") or CloneChar:FindFirstChildOfClass("Humanoid").Health <= 0 and not DeadChar or not DeadChar:FindFirstChild("Head") or not DeadChar:FindFirstChildOfClass("Humanoid") or DeadChar:FindFirstChildOfClass("Humanoid").Health <= 0 then 
            HumanDied = true
            pcall(function()
				game:FindFirstChildOfClass("Players").LocalPlayer.Character = DeadChar
				DeadChar.Head:Destroy()
				DeadChar:FindFirstChildOfClass("Humanoid"):Destroy()
				game:FindFirstChildOfClass("Players").LocalPlayer.Character = CloneChar
				if DeadChar:FindFirstChildOfClass("Folder") then DeadChar:FindFirstChildOfClass("Folder"):Destroy() end
			end)
            if resetBindable then
                game:GetService("StarterGui"):SetCore("ResetButtonCallback", true)
                resetBindable:Destroy()
            end
            break
        end		
    end
end)()


SCIFIMOVIELOL(DeadChar["Head"],CloneChar["Head"])
SCIFIMOVIELOL(DeadChar["Torso"],CloneChar["Torso"])
SCIFIMOVIELOL(DeadChar["Left Arm"],CloneChar["Left Arm"])
SCIFIMOVIELOL(DeadChar["Right Arm"],CloneChar["Right Arm"])
SCIFIMOVIELOL(DeadChar["Left Leg"],CloneChar["Left Leg"])
SCIFIMOVIELOL(DeadChar["Right Leg"],CloneChar["Right Leg"])

for _,v in pairs(DeadChar:GetChildren()) do
	if v:IsA("BasePart") and v.Name ~= "Head" then
		--[[local bv = Instance.new("BodyVelocity",v)
		bv.Velocity = Vector3.new(0,0,0)
		coroutine.wrap(function()
			while true do
				game:GetService("RunService").RenderStepped:wait()
				if HumanDied then break end
				v.CFrame = CloneChar[v.Name].CFrame
			end
		end)()]]
	elseif v:IsA("BasePart") and v.Name == "Head" then
		local bv = Instance.new("BodyVelocity",v)
		bv.Velocity = Vector3.new(0,0,0)
		coroutine.wrap(function()
			while true do
				game:GetService("RunService").RenderStepped:wait()
				if HumanDied then break end
				v.CFrame = DeadChar.Torso.CFrame * CFrame.new(0,1.5,0)
			end
		end)()
	end
end

for _,BodyParts in next, CloneChar:GetDescendants() do
if BodyParts:IsA("BasePart") or BodyParts:IsA("Part") then
BodyParts.Transparency = 1 end end
game:GetService("RunService").RenderStepped:wait()
game:FindFirstChildOfClass("Players").LocalPlayer.Character = CloneChar
game:FindFirstChildOfClass("Workspace"):FindFirstChildOfClass("Camera").CameraSubject = CloneChar.Humanoid

for _,v in next, DeadChar:GetChildren() do
	if v:IsA("Accessory") then
		if v.Handle:FindFirstChildOfClass("Weld") then v.Handle:FindFirstChildOfClass("Weld"):Destroy() end
	end
end

if ANIMATIONHERE then ANIMATIONHERE.Parent = CloneChar end



local playing = false
local rtrnv;
local c;
local tbl3;
local v;
local anim;
local count;
local hhhh;
local asdf;
local s;
local animid;
local plr;
local char;
local cframe;
local torso;
local rs;
local ls;
local rh;
local lh;
local n;
local rj;
local rsc0;
local lsc0;
local rhc0;
local lhc0;
local rjc0;
local nc0;
local gc0;
local orsc0;
local olsc0;
local orhc0;
local olhc0;
local orjc0;
local onc0;
local count2;
local maxcount2;

local function getnext(tbl,number)
	c=100
	rtrnv=0
	for i,v in pairs(tbl) do
		if i>number and i-number<c then
			c=i-number
			rtrnv=i
		end
	end
	return(rtrnv)
end
local function wait2(tim)
	if tim<0.1 then
		game:GetService("RunService").Heartbeat:Wait()
	else
		for i=1,tim*40 do
			game:GetService("RunService").Heartbeat:Wait()
		end
	end
end
local function kftotbl(kf) -- Below this is PAIN
tbl3 = {}
	for i,v in pairs(kf:GetDescendants()) do
		if v:IsA("Pose") then
			tbl3[string.sub(v.Name,1,1)..string.sub(v.Name,#v.Name,#v.Name)] = v.CFrame
		end
	end
	return(tbl3)
end
        
        if playanother == true then
				playanother = false
			end
			playing = true
			s = Instance.new("Sound", game:GetService("Players").LocalPlayer.Character.Torso)

				s.SoundId = "rbxassetid://"

			s.Looped = true
			s.Playing = true
			wait(.1) -- Do not change because changing it will break.
			animid="rbxassetid://6495653138"
			plr = game.Players.LocalPlayer
			char = game:GetService("Players").LocalPlayer.Character
			if _G.permadeath == true then
				char = workspace.non
			end
			cframe = char.HumanoidRootPart.CFrame
			torso = char.Torso
			-----------------------------------------------------------
			rs = torso["Right Shoulder"] -- Just took this from another script(Faster).
			ls = torso["Left Shoulder"]
			rh = torso["Right Hip"]
			lh = torso["Left Hip"]
			n = torso["Neck"]
			rj = char.HumanoidRootPart["RootJoint"]
			rsc0 = rs.C0
			lsc0 = ls.C0
			rhc0 = rh.C0
			lhc0 = lh.C0
			rjc0 = rj.C0
			nc0 = n.C0
			gc0 = CFrame.new()
			orsc0 = rs.C0
			olsc0 = ls.C0
			orhc0 = rh.C0
			olhc0 = lh.C0
			orjc0 = rj.C0
			onc0 = n.C0
			count2 = 100
			maxcount2=100
			-----------------------------------------------------------
			game:GetService("RunService").Heartbeat:Connect(function() -- Speed.
				if playanother == true then
					return nil
				else
					count2 = count2+1
					if count2<=maxcount2 then
						rs.Transform=rs.Transform:Lerp(rsc0,count2/maxcount2)
						ls.Transform=ls.Transform:Lerp(lsc0,count2/maxcount2)
						rh.Transform=rh.Transform:Lerp(rhc0,count2/maxcount2)
						lh.Transform=lh.Transform:Lerp(lhc0,count2/maxcount2)
						n.Transform=n.Transform:Lerp(nc0,count2/maxcount2)
						rj.Transform=rj.Transform:Lerp(rjc0,count2/maxcount2)
					end
				end
			end)
			-----------------------------------------------------------
			animid=game:GetObjects(animid)[1]
			anim={}
			for i,v in pairs(animid:GetChildren()) do
				if v:IsA("Keyframe") then
					anim[v.Time]=kftotbl(v)
				end
			end

			count = 0
			char=game:GetService("Players").LocalPlayer.Character
			if _G.permadeath == true then
				char = workspace.non
			end
						if _G.permadeath == false then
							hhhh=char.Humanoid.Animator
			hhhh.Parent = nil
			end
			hhhh=char.Humanoid.Animator
			hhhh.Parent = nil
			for _,v in pairs(char.Humanoid:GetPlayingAnimationTracks()) do
				v:Stop()
			end

			plr.CharacterRemoving:Connect(function()
				if playing == true then
					playing = false
				end
			end)

			while wait() do
				if playanother == true then
					break
				else
					for i,oasjdadlasdkadkldjkl in pairs(anim) do
						asdf=getnext(anim,count)
						v=anim[asdf]
						if v["Lg"] then
							lhc0 = v["Lg"]
						end
						if v["Rg"] then
							rhc0 = v["Rg"]
						end
						if v["Lm"] then
							lsc0 = v["Lm"]
						end
						if v["Rm"] then
							rsc0 = v["Rm"]
						end
						if v["To"] then
							rjc0 = v["To"]
						end
						if v["Hd"] then
							nc0 = v["Hd"]
						end
						count2=0
						maxcount2=asdf-count
						count=asdf
						wait(asdf-count)
						count2=maxcount2
						if v["Lg"] then
							char.Torso["Left Hip"].Transform = v["Lg"]
						end
						if v["Rg"] then
							char.Torso["Right Hip"].Transform = v["Rg"]
						end
						if v["Lm"] then
							char.Torso["Left Shoulder"].Transform = v["Lm"]
						end
						if v["Rm"] then
							char.Torso["Right Shoulder"].Transform = v["Rm"]
						end
						if v["To"] then
							char.HumanoidRootPart["RootJoint"].Transform = v["To"]
						end
						if v["Hd"] then
							char.Torso["Neck"].Transform = v["Hd"]
						end
					end
				end
			end
		--end)    
end)


AnimationsSection:NewButton("nameless animation", "ur name is gone -_-", function()
    
-- FE Nameless Animations V2 *R15* Script - 2022 (COPY THE SCRIPT!)

-- JOIN THE DISCORD! - https://discord.gg/3GJECGdCWY

--[[
    fe nameless animations v2
    made by MyWorld#4430
    discord.gg/pYVHtSJmEY
    no hats needed, r15 supported
]]

if "myworld reanimate again" then
    --reanimate by MyWorld#4430 discord.gg/pYVHtSJmEY
    local Vector3_101 = Vector3.new(1, 0, 1)
    local netless_Y = Vector3.new(0, 25.1, 0)
    local function getNetlessVelocity(realPartVelocity) --change this if you have a better method
        local mag = realPartVelocity.Magnitude
        if (mag > 1) and (mag < 100) then
            local unit = realPartVelocity.Unit
            if (unit.Y > 0.7) or (unit.Y < -0.7) then
                return realPartVelocity * (25.1 / realPartVelocity.Y)
            end
            realPartVelocity = unit * 100
        end
        return (realPartVelocity * Vector3_101) + netless_Y
    end
    local simradius = "shp" --simulation radius (net bypass) method
    --"shp" - sethiddenproperty
    --"ssr" - setsimulationradius
    --false - disable
    local noclipAllParts = false --set it to true if you want noclip
    local flingpart = "HumanoidRootPart" --the part that will be used to fling (ctrl + F "fling function")
    local antiragdoll = true --removes hingeConstraints and ballSocketConstraints from your character
    local newanimate = true --disables the animate script and enables after reanimation
    local discharscripts = true --disables all localScripts parented to your character before reanimation
    local R15toR6 = true --tries to convert your character to r6 if its r15
    local hatcollide = false --makes hats cancollide (credit to ShownApe) (works only with reanimate method 0)
    local humState16 = true --enables collisions for limbs before the humanoid dies (using hum:ChangeState)
    local addtools = false --puts all tools from backpack to character and lets you hold them after reanimation
    local hedafterneck = true --disable aligns for head and enable after neck or torso is removed
    local loadtime = game:GetService("Players").RespawnTime + 0.5 --anti respawn delay
    local method = 3 --reanimation method
    --methods:
    --0 - breakJoints (takes [loadtime] seconds to laod)
    --1 - limbs
    --2 - limbs + anti respawn
    --3 - limbs + breakJoints after [loadtime] seconds
    --4 - remove humanoid + breakJoints
    --5 - remove humanoid + limbs
    local alignmode = 2 --AlignPosition mode
    --modes:
    --1 - AlignPosition rigidity enabled true
    --2 - 2 AlignPositions rigidity enabled both true and false
    --3 - AlignPosition rigidity enabled false
    
    local lp = game:GetService("Players").LocalPlayer
    local rs = game:GetService("RunService")
    local stepped = rs.Stepped
    local heartbeat = rs.Heartbeat
    local renderstepped = rs.RenderStepped
    local sg = game:GetService("StarterGui")
    local ws = game:GetService("Workspace")
    local cf = CFrame.new
    local v3 = Vector3.new
    local v3_0 = Vector3.zero
    local inf = math.huge
    
    local c = lp.Character
    
    if not (c and c.Parent) then
    	return
    end
    
    c:GetPropertyChangedSignal("Parent"):Connect(function()
        if not (c and c.Parent) then
    	    c = nil
    	end
    end)
    
    local function gp(parent, name, className)
    	if typeof(parent) == "Instance" then
    		for i, v in pairs(parent:GetChildren()) do
    			if (v.Name == name) and v:IsA(className) then
    				return v
    			end
    		end
    	end
    	return nil
    end
    
    if type(getNetlessVelocity) ~= "function" then
        getNetlessVelocity = nil
    end
    
    local function align(Part0, Part1)
    	Part0.CustomPhysicalProperties = PhysicalProperties.new(0, 0, 0, 0, 0)
    
    	local att0 = Instance.new("Attachment")
    	att0.Orientation = v3_0
    	att0.Position = v3_0
    	att0.Name = "att0_" .. Part0.Name
    	local att1 = Instance.new("Attachment")
    	att1.Orientation = v3_0
    	att1.Position = v3_0
    	att1.Name = "att1_" .. Part1.Name
    
    	if (alignmode == 1) or (alignmode == 2) then
    		local ape = Instance.new("AlignPosition", att0)
    		ape.ApplyAtCenterOfMass = false
    		ape.MaxForce = inf
    		ape.MaxVelocity = inf
    		ape.ReactionForceEnabled = false
    		ape.Responsiveness = 200
    		ape.Attachment1 = att1
    		ape.Attachment0 = att0
    		ape.Name = "AlignPositionRtrue"
    		ape.RigidityEnabled = true
    	end
    
    	if (alignmode == 2) or (alignmode == 3) then
    		local apd = Instance.new("AlignPosition", att0)
    		apd.ApplyAtCenterOfMass = false
    		apd.MaxForce = inf
    		apd.MaxVelocity = inf
    		apd.ReactionForceEnabled = false
    		apd.Responsiveness = 200
    		apd.Attachment1 = att1
    		apd.Attachment0 = att0
    		apd.Name = "AlignPositionRfalse"
    		apd.RigidityEnabled = false
    	end
    
    	local ao = Instance.new("AlignOrientation", att0)
    	ao.MaxAngularVelocity = inf
    	ao.MaxTorque = inf
    	ao.PrimaryAxisOnly = false
    	ao.ReactionTorqueEnabled = false
    	ao.Responsiveness = 200
    	ao.Attachment1 = att1
    	ao.Attachment0 = att0
    	ao.RigidityEnabled = false
    
    	if getNetlessVelocity then
    	    local vel = Part0.Velocity
    	    local velpart = Part1
            local rsteppedcon = renderstepped:Connect(function()
                Part0.Velocity = vel
            end)
            local heartbeatcon = heartbeat:Connect(function()
                vel = Part0.Velocity
                Part0.Velocity = getNetlessVelocity(velpart.Velocity)
            end)
            local attcon = nil
            Part0:GetPropertyChangedSignal("Parent"):Connect(function()
                if not (Part0 and Part0.Parent) then
                    rsteppedcon:Disconnect()
                    heartbeatcon:Disconnect()
                    attcon:Disconnect()
                end
            end)
            attcon = att1:GetPropertyChangedSignal("Parent"):Connect(function()
    	        if not (att1 and att1.Parent) then
    	            attcon:Disconnect()
                    velpart = Part0
    	        else
    	            velpart = att1.Parent
    	            if not velpart:IsA("BasePart") then
    	                velpart = Part0
    	            end
    	        end
    	    end)
    	end
    	
    	att0.Parent = Part0
        att1.Parent = Part1
    end
    
    local function respawnrequest()
    	local ccfr = ws.CurrentCamera.CFrame
    	local c = lp.Character
    	lp.Character = nil
    	lp.Character = c
    	local con = nil
    	con = ws.CurrentCamera.Changed:Connect(function(prop)
    	    if (prop ~= "Parent") and (prop ~= "CFrame") then
    	        return
    	    end
    	    ws.CurrentCamera.CFrame = ccfr
    	    con:Disconnect()
        end)
    end
    
    local destroyhum = (method == 4) or (method == 5)
    local breakjoints = (method == 0) or (method == 4)
    local antirespawn = (method == 0) or (method == 2) or (method == 3)
    
    hatcollide = hatcollide and (method == 0)
    
    addtools = addtools and gp(lp, "Backpack", "Backpack")
    
    local fenv = getfenv()
    local shp = fenv.sethiddenproperty or fenv.set_hidden_property or fenv.set_hidden_prop or fenv.sethiddenprop
    local ssr = fenv.setsimulationradius or fenv.set_simulation_radius or fenv.set_sim_radius or fenv.setsimradius or fenv.set_simulation_rad or fenv.setsimulationrad
    
    if shp and (simradius == "shp") then
    	spawn(function()
    		while c and heartbeat:Wait() do
    			shp(lp, "SimulationRadius", inf)
    		end
    	end)
    elseif ssr and (simradius == "ssr") then
    	spawn(function()
    		while c and heartbeat:Wait() do
    			ssr(inf)
    		end
    	end)
    end
    
    antiragdoll = antiragdoll and function(v)
    	if v:IsA("HingeConstraint") or v:IsA("BallSocketConstraint") then
    		v.Parent = nil
    	end
    end
    
    if antiragdoll then
    	for i, v in pairs(c:GetDescendants()) do
    		antiragdoll(v)
    	end
    	c.DescendantAdded:Connect(antiragdoll)
    end
    
    if antirespawn then
    	respawnrequest()
    end
    
    if method == 0 then
    	wait(loadtime)
    	if not c then
    		return
    	end
    end
    
    if discharscripts then
    	for i, v in pairs(c:GetChildren()) do
    		if v:IsA("LocalScript") then
    			v.Disabled = true
    		end
    	end
    elseif newanimate then
    	local animate = gp(c, "Animate", "LocalScript")
    	if animate and (not animate.Disabled) then
    		animate.Disabled = true
    	else
    		newanimate = false
    	end
    end
    
    if addtools then
    	for i, v in pairs(addtools:GetChildren()) do
    		if v:IsA("Tool") then
    			v.Parent = c
    		end
    	end
    end
    
    pcall(function()
    	settings().Physics.AllowSleep = false
    	settings().Physics.PhysicsEnvironmentalThrottle = Enum.EnviromentalPhysicsThrottle.Disabled
    end)
    
    local OLDscripts = {}
    
    for i, v in pairs(c:GetDescendants()) do
    	if v.ClassName == "Script" then
    		table.insert(OLDscripts, v)
    	end
    end
    
    local scriptNames = {}
    
    for i, v in pairs(c:GetDescendants()) do
    	if v:IsA("BasePart") then
    		local newName = tostring(i)
    		local exists = true
    		while exists do
    			exists = false
    			for i, v in pairs(OLDscripts) do
    				if v.Name == newName then
    					exists = true
    				end
    			end
    			if exists then
    				newName = newName .. "_"    
    			end
    		end
    		table.insert(scriptNames, newName)
    		Instance.new("Script", v).Name = newName
    	end
    end
    
    c.Archivable = true
    local hum = c:FindFirstChildOfClass("Humanoid")
    if hum then
    	for i, v in pairs(hum:GetPlayingAnimationTracks()) do
    		v:Stop()
    	end
    end
    local cl = c:Clone()
    if hum and humState16 then
        hum:ChangeState(Enum.HumanoidStateType.Physics)
        if destroyhum then
            wait(1.6)
        end
    end
    if hum and hum.Parent and destroyhum then
        hum:Destroy()
    end
    
    if not c then
        return
    end
    
    local head = gp(c, "Head", "BasePart")
    local torso = gp(c, "Torso", "BasePart") or gp(c, "UpperTorso", "BasePart")
    local root = gp(c, "HumanoidRootPart", "BasePart")
    if hatcollide and c:FindFirstChildOfClass("Accessory") then
        local anything = c:FindFirstChildOfClass("BodyColors") or gp(c, "Health", "Script")
        if not (torso and root and anything) then
            return
        end
        torso:Destroy()
        root:Destroy()
        if shp then
            for i,v in pairs(c:GetChildren()) do
                if v:IsA("Accessory") then
                    shp(v, "BackendAccoutrementState", 0)
                end 
            end
        end
        anything:Destroy()
    end
    
    local model = Instance.new("Model", c)
    model.Name = model.ClassName
    
    model:GetPropertyChangedSignal("Parent"):Connect(function()
        if not (model and model.Parent) then
    	    model = nil
        end
    end)
    
    for i, v in pairs(c:GetChildren()) do
    	if v ~= model then
    		if addtools and v:IsA("Tool") then
    			for i1, v1 in pairs(v:GetDescendants()) do
    				if v1 and v1.Parent and v1:IsA("BasePart") then
    					local bv = Instance.new("BodyVelocity", v1)
    					bv.Velocity = v3_0
    					bv.MaxForce = v3(1000, 1000, 1000)
    					bv.P = 1250
    					bv.Name = "bv_" .. v.Name
    				end
    			end
    		end
    		v.Parent = model
    	end
    end
    
    if breakjoints then
    	model:BreakJoints()
    else
    	if head and torso then
    		for i, v in pairs(model:GetDescendants()) do
    			if v:IsA("Weld") or v:IsA("Snap") or v:IsA("Glue") or v:IsA("Motor") or v:IsA("Motor6D") then
    				local save = false
    				if (v.Part0 == torso) and (v.Part1 == head) then
    					save = true
    				end
    				if (v.Part0 == head) and (v.Part1 == torso) then
    					save = true
    				end
    				if save then
    					if hedafterneck then
    						hedafterneck = v
    					end
    				else
    					v:Destroy()
    				end
    			end
    		end
    	end
    	if method == 3 then
    		spawn(function()
    			wait(loadtime)
    			if model then
    				model:BreakJoints()
    			end
    		end)
    	end
    end
    
    cl.Parent = c
    for i, v in pairs(cl:GetChildren()) do
    	v.Parent = c
    end
    cl:Destroy()
    
    local noclipmodel = (noclipAllParts and c) or model
    local noclipcon = nil
    local function uncollide()
    	if noclipmodel then
    		for i, v in pairs(noclipmodel:GetDescendants()) do
    		    if v:IsA("BasePart") then
    			    v.CanCollide = false
    		    end
    		end
    	else
    		noclipcon:Disconnect()
    	end
    end
    noclipcon = stepped:Connect(uncollide)
    uncollide()
    
    for i, scr in pairs(model:GetDescendants()) do
    	if (scr.ClassName == "Script") and table.find(scriptNames, scr.Name) then
    		local Part0 = scr.Parent
    		if Part0:IsA("BasePart") then
    			for i1, scr1 in pairs(c:GetDescendants()) do
    				if (scr1.ClassName == "Script") and (scr1.Name == scr.Name) and (not scr1:IsDescendantOf(model)) then
    					local Part1 = scr1.Parent
    					if (Part1.ClassName == Part0.ClassName) and (Part1.Name == Part0.Name) then
    						align(Part0, Part1)
    						scr:Destroy()
    						scr1:Destroy()
    						break
    					end
    				end
    			end
    		end
    	end
    end
    
    for i, v in pairs(c:GetDescendants()) do
    	if v and v.Parent and (not v:IsDescendantOf(model)) then
    		if v:IsA("Decal") then
    		    v.Transparency = 1
    		elseif v:IsA("BasePart") then
    			v.Transparency = 1
    			v.Anchored = false
    		elseif v:IsA("ForceField") then
    			v.Visible = false
    		elseif v:IsA("Sound") then
    			v.Playing = false
    		elseif v:IsA("BillboardGui") or v:IsA("SurfaceGui") or v:IsA("ParticleEmitter") or v:IsA("Fire") or v:IsA("Smoke") or v:IsA("Sparkles") then
    			v.Enabled = false
    		end
    	end
    end
    
    if newanimate then
    	local animate = gp(c, "Animate", "LocalScript")
    	if animate then
    		animate.Disabled = false
    	end
    end
    
    if addtools then
    	for i, v in pairs(c:GetChildren()) do
    		if v:IsA("Tool") then
    			v.Parent = addtools
    		end
    	end
    end
    
    local hum0 = model:FindFirstChildOfClass("Humanoid")
    if hum0 then
        hum0:GetPropertyChangedSignal("Parent"):Connect(function()
            if not (hum0 and hum0.Parent) then
                hum0 = nil
            end
        end)
    end
    
    local hum1 = c:FindFirstChildOfClass("Humanoid")
    if hum1 then
        hum1:GetPropertyChangedSignal("Parent"):Connect(function()
            if not (hum1 and hum1.Parent) then
                hum1 = nil
            end
        end)
        
    	ws.CurrentCamera.CameraSubject = hum1
    	local camSubCon = nil
    	local function camSubFunc()
    		camSubCon:Disconnect()
    		if c and hum1 then
    			ws.CurrentCamera.CameraSubject = hum1
    		end
    	end
    	camSubCon = renderstepped:Connect(camSubFunc)
    	if hum0 then
    		hum0:GetPropertyChangedSignal("Jump"):Connect(function()
    			if hum1 then
    				hum1.Jump = hum0.Jump
    			end
    		end)
    	else
    		respawnrequest()
    	end
    end
    
    local rb = Instance.new("BindableEvent", c)
    rb.Event:Connect(function()
    	rb:Destroy()
    	sg:SetCore("ResetButtonCallback", true)
    	if destroyhum then
    		c:BreakJoints()
    		return
    	end
    	if hum0 and (hum0.Health > 0) then
    		model:BreakJoints()
    		hum0.Health = 0
    	end
    	if antirespawn then
    	    respawnrequest()
    	end
    end)
    sg:SetCore("ResetButtonCallback", rb)
    
    spawn(function()
    	while c do
    		if hum0 and hum1 then
    			hum1.Jump = hum0.Jump
    		end
    		wait()
    	end
    	sg:SetCore("ResetButtonCallback", true)
    end)
    
    R15toR6 = R15toR6 and hum1 and (hum1.RigType == Enum.HumanoidRigType.R15)
    if R15toR6 then
        local part = gp(c, "HumanoidRootPart", "BasePart") or gp(c, "UpperTorso", "BasePart") or gp(c, "LowerTorso", "BasePart") or gp(c, "Head", "BasePart") or c:FindFirstChildWhichIsA("BasePart")
    	if part then
    	    local cfr = part.CFrame
    		local R6parts = { 
    			head = {
    				Name = "Head",
    				Size = v3(2, 1, 1),
    				R15 = {
    					Head = 0
    				}
    			},
    			torso = {
    				Name = "Torso",
    				Size = v3(2, 2, 1),
    				R15 = {
    					UpperTorso = 0.2,
    					LowerTorso = -0.8
    				}
    			},
    			root = {
    				Name = "HumanoidRootPart",
    				Size = v3(2, 2, 1),
    				R15 = {
    					HumanoidRootPart = 0
    				}
    			},
    			leftArm = {
    				Name = "Left Arm",
    				Size = v3(1, 2, 1),
    				R15 = {
    					LeftHand = -0.85,
    					LeftLowerArm = -0.2,
    					LeftUpperArm = 0.4
    				}
    			},
    			rightArm = {
    				Name = "Right Arm",
    				Size = v3(1, 2, 1),
    				R15 = {
    					RightHand = -0.85,
    					RightLowerArm = -0.2,
    					RightUpperArm = 0.4
    				}
    			},
    			leftLeg = {
    				Name = "Left Leg",
    				Size = v3(1, 2, 1),
    				R15 = {
    					LeftFoot = -0.85,
    					LeftLowerLeg = -0.15,
    					LeftUpperLeg = 0.6
    				}
    			},
    			rightLeg = {
    				Name = "Right Leg",
    				Size = v3(1, 2, 1),
    				R15 = {
    					RightFoot = -0.85,
    					RightLowerLeg = -0.15,
    					RightUpperLeg = 0.6
    				}
    			}
    		}
    		for i, v in pairs(c:GetChildren()) do
    			if v:IsA("BasePart") then
    				for i1, v1 in pairs(v:GetChildren()) do
    					if v1:IsA("Motor6D") then
    						v1.Part0 = nil
    					end
    				end
    			end
    		end
    		part.Archivable = true
    		for i, v in pairs(R6parts) do
    			local part = part:Clone()
    			part:ClearAllChildren()
    			part.Name = v.Name
    			part.Size = v.Size
    			part.CFrame = cfr
    			part.Anchored = false
    			part.Transparency = 1
    			part.CanCollide = false
    			for i1, v1 in pairs(v.R15) do
    				local R15part = gp(c, i1, "BasePart")
    				local att = gp(R15part, "att1_" .. i1, "Attachment")
    				if R15part then
    					local weld = Instance.new("Weld", R15part)
    					weld.Name = "Weld_" .. i1
    					weld.Part0 = part
    					weld.Part1 = R15part
    					weld.C0 = cf(0, v1, 0)
    					weld.C1 = cf(0, 0, 0)
    					R15part.Massless = true
    					R15part.Name = "R15_" .. i1
    					R15part.Parent = part
    					if att then
    						att.Parent = part
    						att.Position = v3(0, v1, 0)
    					end
    				end
    			end
    			part.Parent = c
    			R6parts[i] = part
    		end
    		local R6joints = {
    			neck = {
    				Parent = R6parts.torso,
    				Name = "Neck",
    				Part0 = R6parts.torso,
    				Part1 = R6parts.head,
    				C0 = cf(0, 1, 0, -1, 0, 0, 0, 0, 1, 0, 1, -0),
    				C1 = cf(0, -0.5, 0, -1, 0, 0, 0, 0, 1, 0, 1, -0)
    			},
    			rootJoint = {
    				Parent = R6parts.root,
    				Name = "RootJoint" ,
    				Part0 = R6parts.root,
    				Part1 = R6parts.torso,
    				C0 = cf(0, 0, 0, -1, 0, 0, 0, 0, 1, 0, 1, -0),
    				C1 = cf(0, 0, 0, -1, 0, 0, 0, 0, 1, 0, 1, -0)
    			},
    			rightShoulder = {
    				Parent = R6parts.torso,
    				Name = "Right Shoulder",
    				Part0 = R6parts.torso,
    				Part1 = R6parts.rightArm,
    				C0 = cf(1, 0.5, 0, 0, 0, 1, 0, 1, -0, -1, 0, 0),
    				C1 = cf(-0.5, 0.5, 0, 0, 0, 1, 0, 1, -0, -1, 0, 0)
    			},
    			leftShoulder = {
    				Parent = R6parts.torso,
    				Name = "Left Shoulder",
    				Part0 = R6parts.torso,
    				Part1 = R6parts.leftArm,
    				C0 = cf(-1, 0.5, 0, 0, 0, -1, 0, 1, 0, 1, 0, 0),
    				C1 = cf(0.5, 0.5, 0, 0, 0, -1, 0, 1, 0, 1, 0, 0)
    			},
    			rightHip = {
    				Parent = R6parts.torso,
    				Name = "Right Hip",
    				Part0 = R6parts.torso,
    				Part1 = R6parts.rightLeg,
    				C0 = cf(1, -1, 0, 0, 0, 1, 0, 1, -0, -1, 0, 0),
    				C1 = cf(0.5, 1, 0, 0, 0, 1, 0, 1, -0, -1, 0, 0)
    			},
    			leftHip = {
    				Parent = R6parts.torso,
    				Name = "Left Hip" ,
    				Part0 = R6parts.torso,
    				Part1 = R6parts.leftLeg,
    				C0 = cf(-1, -1, 0, 0, 0, -1, 0, 1, 0, 1, 0, 0),
    				C1 = cf(-0.5, 1, 0, 0, 0, -1, 0, 1, 0, 1, 0, 0)
    			}
    		}
    		for i, v in pairs(R6joints) do
    			local joint = Instance.new("Motor6D")
    			for prop, val in pairs(v) do
    				joint[prop] = val
    			end
    			R6joints[i] = joint
    		end
    		if hum1 then
        		hum1.RigType = Enum.HumanoidRigType.R6
        		hum1.HipHeight = 0
    		end
    	end
    end
    
    local torso1 = torso
    torso = gp(c, "Torso", "BasePart") or ((not R15toR6) and gp(c, torso.Name, "BasePart"))
    if (typeof(hedafterneck) == "Instance") and head and torso and torso1 then
    	local conNeck = nil
    	local conTorso = nil
    	local contorso1 = nil
    	local aligns = {}
    	local function enableAligns()
    	    conNeck:Disconnect()
            conTorso:Disconnect()
            conTorso1:Disconnect()
    		for i, v in pairs(aligns) do
    			v.Enabled = true
    		end
    	end
    	conNeck = hedafterneck.Changed:Connect(function(prop)
    	    if table.find({"Part0", "Part1", "Parent"}, prop) then
    	        enableAligns()
    		end
    	end)
    	conTorso = torso:GetPropertyChangedSignal("Parent"):Connect(enableAligns)
    	conTorso1 = torso1:GetPropertyChangedSignal("Parent"):Connect(enableAligns)
    	for i, v in pairs(head:GetDescendants()) do
    		if v:IsA("AlignPosition") or v:IsA("AlignOrientation") then
    			i = tostring(i)
    			aligns[i] = v
    			v:GetPropertyChangedSignal("Parent"):Connect(function()
    			    aligns[i] = nil
    			end)
    			v.Enabled = false
    		end
    	end
    end
    
    --[[
        fling function
        usage: fling(target, duration, velocity)
        target can be set to: basePart, CFrame, Vector3, character model or humanoid
        duration (fling time) can be set to a number or a string containing the number (in seconds) will be set to 0.5 if not provided,
        velocity (fling part rotation velocity) can be set to a vector3 value (Vector3.new(20000, 20000, 20000) if not provided)
    ]]
    
    local flingpart0 = gp(model, flingpart, "BasePart")
    local flingpart1 = gp(c, flingpart, "BasePart")
    
    local fling = function() end
    if flingpart0 and flingpart1 then
        flingpart0:GetPropertyChangedSignal("Parent"):Connect(function()
            if not (flingpart0 and flingpart0.Parent) then
                flingpart0 = nil
                fling = function() end
            end
        end)
        flingpart0.Archivable = true
        flingpart1:GetPropertyChangedSignal("Parent"):Connect(function()
            if not (flingpart1 and flingpart1.Parent) then
                flingpart1 = nil
                fling = function() end
            end
        end)
        local att0 = gp(flingpart0, "att0_" .. flingpart0.Name, "Attachment")
        local att1 = gp(flingpart1, "att1_" .. flingpart1.Name, "Attachment")
        if att0 and att1 then
            att0:GetPropertyChangedSignal("Parent"):Connect(function()
                if not (att0 and att0.Parent) then
                    att0 = nil
                    fling = function() end
                end
            end)
            att1:GetPropertyChangedSignal("Parent"):Connect(function()
                if not (att1 and att1.Parent) then
                    att1 = nil
                    fling = function() end
                end
            end)
            local lastfling = nil
            fling = function(target, duration, rotVelocity)
                if typeof(target) == "Instance" then
                    if target:IsA("BasePart") then
                        target = target.Position
                    elseif target:IsA("Model") then
                        target = gp(target, "HumanoidRootPart", "BasePart") or gp(target, "Torso", "BasePart") or gp(target, "UpperTorso", "BasePart") or target:FindFirstChildWhichIsA("BasePart")
                        if target then
                            target = target.Position
                        else
                            return
                        end
                    elseif target:IsA("Humanoid") then
                        local parent = target.Parent
                        if not (parent and parent:IsA("Model")) then
                            return
                        end
                        target = gp(target, "HumanoidRootPart", "BasePart") or gp(target, "Torso", "BasePart") or gp(target, "UpperTorso", "BasePart") or target:FindFirstChildWhichIsA("BasePart")
                        if target then
                            target = target.Position
                        else
                            return
                        end
                    else
                        return
                    end
                elseif typeof(target) == "CFrame" then
                    target = target.Position
                elseif typeof(target) ~= "Vector3" then
                    return
                end
                lastfling = target
                if type(duration) ~= "number" then
                    duration = tonumber(duration) or 0.5
                end
                if typeof(rotVelocity) ~= "Vector3" then
                    rotVelocity = v3(20000, 20000, 20000)
                end
                if not (target and flingpart0 and flingpart1 and att0 and att1) then
                    return
                end
                local flingpart = flingpart0:Clone()
                flingpart.Transparency = 1
                flingpart.Size = v3(0.01, 0.01, 0.01)
                flingpart.CanCollide = false
                flingpart.Name = "flingpart_" .. flingpart0.Name
                flingpart.Anchored = true
                flingpart.Velocity = v3_0
                flingpart.RotVelocity = v3_0
                flingpart:GetPropertyChangedSignal("Parent"):Connect(function()
                    if not (flingpart and flingpart.Parent) then
                        flingpart = nil
                    end
                end)
                flingpart.Parent = flingpart1
                if flingpart0.Transparency > 0.5 then
                    flingpart0.Transparency = 0.5
                end
                att1.Parent = flingpart
                for i, v in pairs(att0:GetChildren()) do
                    if v:IsA("AlignOrientation") then
                        v.Enabled = false
                    end
                end
                local con = nil
                con = heartbeat:Connect(function()
                    if target and (lastfling == target) and flingpart and flingpart0 and flingpart1 and att0 and att1 then
                        flingpart0.RotVelocity = rotVelocity
                        flingpart.Position = target
                    else
                        con:Disconnect()
                    end
                end)
                local rsteppedRotVel = v3(
                    ((rotVelocity.X > 0) and -1) or 1,
                    ((rotVelocity.Y > 0) and -1) or 1,
                    ((rotVelocity.Z > 0) and -1) or 1
                )
                local con = nil
                con = renderstepped:Connect(function()
                    if target and (lastfling == target) and flingpart and flingpart0 and flingpart1 and att0 and att1 then
                        flingpart0.RotVelocity = rsteppedRotVel
                        flingpart.Position = target
                    else
                        con:Disconnect()
                    end
                end)
                wait(duration)
                if lastfling ~= target then
                    if flingpart then
                        if att1 and (att1.Parent == flingpart) then
                            att1.Parent = flingpart1
                        end
                        flingpart:Destroy()
                    end
                    return
                end
                target = nil
                if not (flingpart and flingpart0 and flingpart1 and att0 and att1) then
                    return
                end
                flingpart0.RotVelocity = v3_0
                att1.Parent = flingpart1
                for i, v in pairs(att0:GetChildren()) do
                    if v:IsA("AlignOrientation") then
                        v.Enabled = true
                    end
                end
                if flingpart then
                    flingpart:Destroy()
                end
            end
        end
    end
end

local lp = game:GetService("Players").LocalPlayer

local c = lp.Character
if not (c and c.Parent) then
	return print("character not found")
end
c:GetPropertyChangedSignal("Parent"):Connect(function()
    if not (c and c.Parent) then
        c = nil
    end
end)

--getPart function

local function gp(parent, name, className)
	local ret = nil
	pcall(function()
		for i, v in pairs(parent:GetChildren()) do
			if (v.Name == name) and v:IsA(className) then
				ret = v
				break
			end
		end
	end)
	return ret
end

--check if reanimate loaded

local model = gp(c, "Model", "Model")
if not model then return print("model not found") end

--find body parts

local head = gp(c, "Head", "BasePart")
if not head then return print("head not found") end

local torso = gp(c, "Torso", "BasePart")
if not torso then return print("torso not found") end

local humanoidRootPart = gp(c, "HumanoidRootPart", "BasePart")
if not humanoidRootPart then return print("humanoid root part not found") end

local leftArm = gp(c, "Left Arm", "BasePart")
if not leftArm then return print("left arm not found") end

local rightArm = gp(c, "Right Arm", "BasePart")
if not rightArm then return print("right arm not found") end

local leftLeg = gp(c, "Left Leg", "BasePart")
if not leftLeg then return print("left leg not found") end

local rightLeg = gp(c, "Right Leg", "BasePart")
if not rightLeg then return print("right leg not found") end

--find rig joints

local neck = gp(torso, "Neck", "Motor6D")
if not neck then return print("neck not found") end

local rootJoint = gp(humanoidRootPart, "RootJoint", "Motor6D")
if not rootJoint then return print("root joint not found") end

local leftShoulder = gp(torso, "Left Shoulder", "Motor6D")
if not leftShoulder then return print("left shoulder not found") end

local rightShoulder = gp(torso, "Right Shoulder", "Motor6D")
if not rightShoulder then return print("right shoulder not found") end

local leftHip = gp(torso, "Left Hip", "Motor6D")
if not leftHip then return print("left hip not found") end

local rightHip = gp(torso, "Right Hip", "Motor6D")
if not rightHip then return print("right hip not found") end

--humanoid

local hum = c:FindFirstChildOfClass("Humanoid")
if not hum then return print("humanoid not found") end

local animate = gp(c, "Animate", "LocalScript")
if animate then
	animate.Disabled = true
end

for i, v in pairs(hum:GetPlayingAnimationTracks()) do
	v:Stop()
end

local fps = 60
local sinechange = 40 / fps
local event = Instance.new("BindableEvent", c)
event.Name = "renderstepped"
local floor = math.floor
fps = 1 / fps
local tf = 0
local con = nil
con = game:GetService("RunService").RenderStepped:Connect(function(s)
	if not c then
		con:Disconnect()
		return
	end
	tf += s
	if tf >= fps then
		for i=1, floor(tf / fps) do
		    tf -= fps
			event:Fire(c)
		end
	end
end)
local event = event.Event

local function stopIfRemoved(instance)
    if not (instance and instance.Parent) then
        c = nil
        return
    end
    instance:GetPropertyChangedSignal("Parent"):Connect(function()
        if not (instance and instance.Parent) then
            c = nil
        end
    end)
end
stopIfRemoved(c)
stopIfRemoved(hum)
for i, v in pairs({head, torso, leftArm, rightArm, leftLeg, rightLeg, humanoidRootPart}) do
    stopIfRemoved(v)
end
for i, v in pairs({neck, rootJoint, leftShoulder, rightShoulder, leftHip, rightHip}) do
    stopIfRemoved(v)
end
if not c then
    return
end
local mode = false
uis = game:GetService("UserInputService")
local modes = {
	[Enum.KeyCode.Q] = "lay",
	[Enum.KeyCode.E] = "sit",
	[Enum.KeyCode.R] = "russia",
	[Enum.KeyCode.T] = "wave",
	[Enum.KeyCode.Y] = "dab",
	[Enum.KeyCode.U] = "dance",
	[Enum.KeyCode.L] = "L",
	[Enum.KeyCode.F] = "fly",
	[Enum.KeyCode.G] = "floss"
}
uis.InputBegan:Connect(function(keycode)
    if uis:GetFocusedTextBox() then
        return
    end
	keycode = keycode.KeyCode
	if modes[keycode] ~= nil then
		if mode == modes[keycode] then
			mode = nil
		else
			mode = modes[keycode]
		end
	end
end)

local cf, v3, euler, sin, sine = CFrame.new, Vector3.new, CFrame.fromEulerAnglesXYZ, math.sin, 0
while event:Wait() do
    sine += sinechange
    local vel = humanoidRootPart.Velocity
    if (vel*v3(1, 0, 1)).Magnitude > 2 then -- walk
        neck.C0 = neck.C0:Lerp(cf(0, 1, 0) * euler(-1.6580627893946132 + -0.17453292519943295 * sin(sine * 0.4), -0.04363323129985824 * sin(sine * 0.2), -3.1590459461097367 + -0.08726646259971647 * sin((sine + -2.5) * 0.2)), 0.2) 
        rootJoint.C0 = rootJoint.C0:Lerp(cf(0, 0.2 + 0.2 * sin(sine * 0.4), 0) * euler(-1.6580627893946132 + 0.08726646259971647 * sin((sine + -1) * 0.4), 0.08726646259971647 * sin(sine * 0.2), -3.1590459461097367 + 0.17453292519943295 * sin((sine + -2.5) * 0.2)), 0.2) 
        leftShoulder.C0 = leftShoulder.C0:Lerp(cf(-1, 0.5, 0) * euler(1.5707963267948966, -1.3962634015954636, 1.2217304763960306 + -0.6981317007977318 * sin((sine + -2.5) * 0.2)), 0.2) 
        rightShoulder.C0 = rightShoulder.C0:Lerp(cf(1, 0.5, 0) * euler(1.5707963267948966, 1.3962634015954636, -1.2217304763960306 + -0.6981317007977318 * sin((sine + -2.5) * 0.2)), 0.2) 
        leftHip.C0 = leftHip.C0:Lerp(cf(-1, -1 + -0.3 * sin((sine + 5) * 0.2), 0) * euler(1.5707963267948966 + -0.8726646259971648 * sin(sine * 0.2), -1.5707963267948966 + 0.08726646259971647 * sin(sine * 0.2), 1.5707963267948966), 0.2) 
        rightHip.C0 = rightHip.C0:Lerp(cf(1, -1 + 0.3 * sin((sine + 5) * 0.2), 0) * euler(1.5707963267948966 + 0.8726646259971648 * sin(sine * 0.2), 1.5707963267948966 + 0.08726646259971647 * sin(sine * 0.2), -1.5707963267948966), 0.2) 
    elseif vel.Y > 2 then -- jump
        neck.C0 = neck.C0:Lerp(cf(0 + 0 * sin((sine + 0) * 0.1), 1 + 0 * sin((sine + 0) * 0.1), 0 + 0 * sin((sine + 0) * 0.1)) * euler(-1.3962634015954636 + 0 * sin((sine + 0) * 0.1), 0 + 0 * sin((sine + 0) * 0.1), -3.1590459461097367 + 0 * sin((sine + 0) * 0.1)), 0.2) 
        rootJoint.C0 = rootJoint.C0:Lerp(cf(0 + 0 * sin((sine + 0) * 0.1), 0 + 0 * sin((sine + 0) * 0.1), 0 + 0 * sin((sine + 0) * 0.1)) * euler(-1.3962634015954636 + 0 * sin((sine + 0) * 0.1), 0 + 0 * sin((sine + 0) * 0.1), -3.141592653589793 + 0 * sin((sine + 0) * 0.1)), 0.2) 
        leftShoulder.C0 = leftShoulder.C0:Lerp(cf(-1 + 0 * sin((sine + 0) * 0.1), 0.5 + 0 * sin((sine + 0) * 0.1), 0 + 0 * sin((sine + 0) * 0.1)) * euler(-0 + 0 * sin((sine + 0) * 0.1), -0.7853981633974483 + 0 * sin((sine + 0) * 0.1), -2.443460952792061 + 0 * sin((sine + 0) * 0.1)), 0.2) 
        rightShoulder.C0 = rightShoulder.C0:Lerp(cf(1 + 0 * sin((sine + 0) * 0.1), 0.5 + 0 * sin((sine + 0) * 0.1), 0 + 0 * sin((sine + 0) * 0.1)) * euler(0 + 0 * sin((sine + 0) * 0.1), 0.7853981633974483 + 0 * sin((sine + 0) * 0.1), 2.443460952792061 + 0 * sin((sine + 0) * 0.1)), 0.2) 
        leftHip.C0 = leftHip.C0:Lerp(cf(-1 + 0 * sin((sine + 0) * 0.1), -1 + 0 * sin((sine + 0) * 0.1), 0 + 0 * sin((sine + 0) * 0.1)) * euler(-0.6981317007977318 + 0 * sin((sine + 0) * 0.1), -1.5882496193148399 + 0 * sin((sine + 0) * 0.1), 0 + 0 * sin((sine + 0) * 0.1)), 0.2) 
        rightHip.C0 = rightHip.C0:Lerp(cf(1 + 0 * sin((sine + 0) * 0.1), -1 + 0 * sin((sine + 0) * 0.1), 0 + 0 * sin((sine + 0) * 0.1)) * euler(0 + 0 * sin((sine + 0) * 0.1), 1.5707963267948966 + 0 * sin((sine + 0) * 0.1), -0.6981317007977318 + 0 * sin((sine + 0) * 0.1)), 0.2)
    elseif vel.Y < -2 then -- fall
        neck.C0 = neck.C0:Lerp(cf(0 + 0 * sin((sine + 0) * 0.1), 1 + 0 * sin((sine + 0) * 0.1), 0 + 0 * sin((sine + 0) * 0.1)) * euler(-1.7453292519943295 + 0 * sin((sine + 0) * 0.1), 0 + 0 * sin((sine + 0) * 0.1), -3.141592653589793 + 0 * sin((sine + 0) * 0.1)), 0.2) 
        rootJoint.C0 = rootJoint.C0:Lerp(cf(0 + 0 * sin((sine + 0) * 0.1), 0 + 0 * sin((sine + 0) * 0.1), 0 + 0 * sin((sine + 0) * 0.1)) * euler(-1.7453292519943295 + 0 * sin((sine + 0) * 0.1), 0 + 0 * sin((sine + 0) * 0.1), -3.141592653589793 + 0 * sin((sine + 0) * 0.1)), 0.2) 
        leftShoulder.C0 = leftShoulder.C0:Lerp(cf(-1 + 0 * sin((sine + 0) * 0.1), 0.5 + 0 * sin((sine + 0) * 0.1), 0 + 0 * sin((sine + 0) * 0.1)) * euler(-0 + 0 * sin((sine + 0) * 0.1), -1.2217304763960306 + 0 * sin((sine + 0) * 0.1), -0.8726646259971648 + 0 * sin((sine + 0) * 0.1)), 0.2) 
        rightShoulder.C0 = rightShoulder.C0:Lerp(cf(1 + 0 * sin((sine + 0) * 0.1), 0.5 + 0 * sin((sine + 0) * 0.1), 0 + 0 * sin((sine + 0) * 0.1)) * euler(0 + 0 * sin((sine + 0) * 0.1), 1.2217304763960306 + 0 * sin((sine + 0) * 0.1), 0.8726646259971648 + 0 * sin((sine + 0) * 0.1)), 0.2) 
        leftHip.C0 = leftHip.C0:Lerp(cf(-1 + 0 * sin((sine + 0) * 0.1), -1 + 0 * sin((sine + 0) * 0.1), 0 + 0 * sin((sine + 0) * 0.1)) * euler(0.5235987755982988 + 0 * sin((sine + 0) * 0.1), -1.5707963267948966 + 0 * sin((sine + 0) * 0.1), 0 + 0 * sin((sine + 0) * 0.1)), 0.2) 
        rightHip.C0 = rightHip.C0:Lerp(cf(1 + 0 * sin((sine + 0) * 0.1), -1 + 0 * sin((sine + 0) * 0.1), 0 + 0 * sin((sine + 0) * 0.1)) * euler(0.5235987755982988 + 0 * sin((sine + 0) * 0.1), 1.5707963267948966 + 0 * sin((sine + 0) * 0.1), 0 + 0 * sin((sine + 0) * 0.1)), 0.2)
    else -- idle
		if not mode then
            neck.C0 = neck.C0:Lerp(cf(0, 1, 0) * euler(-1.5882496193148399 + 0.08726646259971647 * sin((sine + -30) * 0.05), 0, -3.1590459461097367), 0.2) 
            rootJoint.C0 = rootJoint.C0:Lerp(cf(0, 0.1 * sin(sine * 0.05), 0) * euler(-1.5882496193148399 + 0.05235987755982989 * sin(sine * 0.05), 0, -3.1590459461097367), 0.2) 
            leftShoulder.C0 = leftShoulder.C0:Lerp(cf(-0.85, 0.65 + 0.1 * sin((sine + -15) * 0.05), 0.2 + 0.1 * sin(sine * 0.05)) * euler(1.5707963267948966 + 0.08726646259971647 * sin(sine * 0.05), -0.7853981633974483, 1.7453292519943295), 0.2) 
            rightShoulder.C0 = rightShoulder.C0:Lerp(cf(0.85, 0.65 + 0.1 * sin((sine + -15) * 0.05), 0.2 + 0.1 * sin(sine * 0.05)) * euler(1.5707963267948966 + 0.08726646259971647 * sin(sine * 0.05), 0.7853981633974483, -1.7453292519943295), 0.2) 
            leftHip.C0 = leftHip.C0:Lerp(cf(-1, -1 + -0.1 * sin(sine * 0.05), 0.05 * sin(sine * 0.05)) * euler(1.5707963267948966, -1.6580627893946132, 1.5707963267948966 + 0.05235987755982989 * sin(sine * 0.05)), 0.2) 
            rightHip.C0 = rightHip.C0:Lerp(cf(1, -1 + -0.1 * sin(sine * 0.05), 0.05 * sin(sine * 0.05)) * euler(1.5707963267948966, 1.6580627893946132, -1.5707963267948966 + -0.05235987755982989 * sin(sine * 0.05)), 0.2) 
		elseif mode == "russia" then
            neck.C0 = neck.C0:Lerp(cf(0, 1, 0) * euler(-1.6580627893946132 + 0.17453292519943295 * sin((sine + -7.5) * 0.4), 0.08726646259971647 * sin((sine + 7.5) * 0.2), -3.1590459461097367 + 0.17453292519943295 * sin((sine + -2.5) * 0.2)), 0.2) 
            rootJoint.C0 = rootJoint.C0:Lerp(cf(0, 0.1 + 0.2 * sin((sine + -2.5) * 0.4), 0) * euler(-1.4835298641951802 + 0.08726646259971647 * sin(sine * 0.4), -0.08726646259971647 * sin((sine + -5) * 0.2), -3.1590459461097367 + -0.17453292519943295 * sin((sine + -3.5) * 0.2)), 0.2) 
            leftShoulder.C0 = leftShoulder.C0:Lerp(cf(-0.5, 0.2 + 0.05 * sin((sine + 5) * 0.4), 0) * euler(3.141592653589793 + 0.08726646259971647 * sin(sine * 0.4), -0.17453292519943295 + 0.17453292519943295 * sin((sine + -5) * 0.2), 1.5707963267948966 + -0.03490658503988659 * sin((sine + -5) * 0.4)), 0.2) 
            rightShoulder.C0 = rightShoulder.C0:Lerp(cf(0.5, 0.2 + 0.05 * sin((sine + 5) * 0.4), 0) * euler(3.141592653589793 + 0.08726646259971647 * sin(sine * 0.4), 0.17453292519943295 + 0.17453292519943295 * sin((sine + -5) * 0.2), -1.5707963267948966 + 0.03490658503988659 * sin((sine + -5) * 0.4)), 0.2) 
            leftHip.C0 = leftHip.C0:Lerp(cf(-1, -1, 0) * euler(0, -1.5882496193148399, -0.3490658503988659 + 1.0471975511965976 * sin((sine + -5) * 0.2)), 0.2) 
            rightHip.C0 = rightHip.C0:Lerp(cf(1, -1, 0) * euler(0, 1.5707963267948966, 0.3490658503988659 + 1.0471975511965976 * sin((sine + -5) * 0.2)), 0.2) 
		elseif mode == "sit" then
            neck.C0 = neck.C0:Lerp(cf(0, 1.1, -0.1) * euler(-2.007128639793479 + -0.12217304763960307 * sin((sine + -25) * 0.05), 0, -3.1590459461097367), 0.2) 
            rootJoint.C0 = rootJoint.C0:Lerp(cf(0, -1.6 + 0.05 * sin(sine * 0.05), 1 + 0.01 * sin((sine + 15) * 0.05)) * euler(-1.1344640137963142 + 0.08726646259971647 * sin((sine + 15) * 0.05), 0, -3.141592653589793), 0.2) 
            leftShoulder.C0 = leftShoulder.C0:Lerp(cf(-1, 0.2 + -0.05 * sin(sine * 0.05), 0.05 * sin(sine * 0.05)) * euler(-0.6981317007977318 + -0.05235987755982989 * sin((sine + 15) * 0.05), -1.2217304763960306, 0), 0.2) 
            rightShoulder.C0 = rightShoulder.C0:Lerp(cf(1, 0.2 + -0.05 * sin(sine * 0.05), 0.05 * sin(sine * 0.05)) * euler(-0.6981317007977318 + -0.05235987755982989 * sin((sine + 15) * 0.05), 1.2217304763960306, 0), 0.2) 
            leftHip.C0 = leftHip.C0:Lerp(cf(-0.9, -1 + -0.06 * sin((sine + 5) * 0.05), 0.1 * sin(sine * 0.05)) * euler(2.705260340591211 + -0.08726646259971647 * sin((sine + 15) * 0.05), -1.7453292519943295, 1.5707963267948966), 0.2) 
            rightHip.C0 = rightHip.C0:Lerp(cf(0.9, -1 + -0.06 * sin((sine + 5) * 0.05), 0.1 * sin(sine * 0.05)) * euler(2.705260340591211 + -0.08726646259971647 * sin((sine + 15) * 0.05), 1.7453292519943295, -1.5707963267948966), 0.2) 
		elseif mode == "wave" then
            neck.C0 = neck.C0:Lerp(cf(0, 1, 0) * euler(-1.5882496193148399, -0.2617993877991494 * sin((sine + 5) * 0.1), -3.1590459461097367), 0.2) 
            rootJoint.C0 = rootJoint.C0:Lerp(cf(0.2 * sin(sine * 0.1), -0.1, 0) * euler(-1.5882496193148399, 0.17453292519943295 * sin(sine * 0.1), -3.1590459461097367), 0.2) 
            leftShoulder.C0 = leftShoulder.C0:Lerp(cf(-1, 0.5, 0) * euler(1.5707963267948966, -1.7453292519943295 + 0.17453292519943295 * sin((sine + 10) * 0.1), 1.5707963267948966), 0.2) 
            rightShoulder.C0 = rightShoulder.C0:Lerp(cf(1, 1.5, 0) * euler(1.5707963267948966, 1.2217304763960306 + -0.3490658503988659 * sin((sine + -10) * 0.1), 1.5707963267948966), 0.2) 
            leftHip.C0 = leftHip.C0:Lerp(cf(-1 + -0.1 * sin(sine * 0.1), -0.9 + -0.15 * sin(sine * 0.1), 0) * euler(1.5707963267948966, -1.7453292519943295 + 0.20943951023931956 * sin(sine * 0.1), 1.5707963267948966), 0.2) 
            rightHip.C0 = rightHip.C0:Lerp(cf(1 + -0.1 * sin(sine * 0.1), -0.9 + 0.15 * sin(sine * 0.1), 0) * euler(1.5707963267948966, 1.7453292519943295 + 0.20943951023931956 * sin(sine * 0.1), -1.5707963267948966), 0.2) 		
        elseif mode == "lay" then
            neck.C0 = neck.C0:Lerp(cf(0, 1.2, -0.2) * euler(-2.2689280275926285 + 0.08726646259971647 * sin(sine * 0.05), 0, -3.1590459461097367), 0.2) 
            rootJoint.C0 = rootJoint.C0:Lerp(cf(0, -2.4 + 0.1 * sin(sine * 0.05), 0) * euler(0, 0, -3.1590459461097367), 0.2) 
            leftShoulder.C0 = leftShoulder.C0:Lerp(cf(-0.6, 1, 0.1 + 0.1 * sin(sine * 0.05)) * euler(1.5707963267948966, -2.356194490192345 + 0.08726646259971647 * sin(sine * 0.05), -1.5707963267948966), 0.2) 
            rightShoulder.C0 = rightShoulder.C0:Lerp(cf(0.6, 1, 0.1 + 0.1 * sin(sine * 0.05)) * euler(1.5707963267948966, 2.356194490192345 + -0.08726646259971647 * sin(sine * 0.05), 1.5707963267948966), 0.2) 
            leftHip.C0 = leftHip.C0:Lerp(cf(-1, -1, 0) * euler(1.5707963267948966, -1.3089969389957472, 1.6580627893946132 + 0.08726646259971647 * sin(sine * 0.05)), 0.2) 
            rightHip.C0 = rightHip.C0:Lerp(cf(1, -1, 0) * euler(1.5707963267948966, 1.3089969389957472, -1.1344640137963142 + -0.08726646259971647 * sin(sine * 0.05)), 0.2) 
		elseif mode == "dab" then
            neck.C0 = neck.C0:Lerp(cf(0, 1 + -0.1 * sin((sine + 10) * 0.05), 0) * euler(-2.2689280275926285, -0.17453292519943295, 2.356194490192345), 0.2) 
            rootJoint.C0 = rootJoint.C0:Lerp(cf(0, 0.1 * sin(sine * 0.05), 0) * euler(-1.6580627893946132, 0.08726646259971647, -3.2288591161895095), 0.2) 
            leftShoulder.C0 = leftShoulder.C0:Lerp(cf(-1.6, 0.5 + -0.1 * sin((sine + 20) * 0.05), 0) * euler(1.5707963267948966, 2.8797932657906435, 1.5707963267948966), 0.2) 
            rightShoulder.C0 = rightShoulder.C0:Lerp(cf(1, 0.25 + -0.1 * sin((sine + 20) * 0.05), -0.5) * euler(4.1887902047863905, 0.3490658503988659, -1.7453292519943295), 0.2) 
            leftHip.C0 = leftHip.C0:Lerp(cf(-1, -1 + -0.1 * sin((sine + 10) * 0.05), 0) * euler(1.7453292519943295, -1.7453292519943295, 1.5707963267948966), 0.2) 
            rightHip.C0 = rightHip.C0:Lerp(cf(1, -0.85 + -0.1 * sin((sine + 10) * 0.05), 0) * euler(1.5707963267948966, 1.7453292519943295, -1.5707963267948966), 0.2) 
		elseif mode == "dance" then
            neck.C0 = neck.C0:Lerp(cf(0, 1, 0) * euler(-1.5882496193148399 + 0.3490658503988659 * sin((sine + 27.5) * 0.2), -0.17453292519943295 * sin((sine + 10) * 0.1), -3.1590459461097367 + 0.3490658503988659 * sin(sine * 0.1)), 0.2) 
            rootJoint.C0 = rootJoint.C0:Lerp(cf(0, 0, 0) * euler(-1.5882496193148399, 0, -3.1590459461097367 + 0.5235987755982988 * sin(sine * 0.1)), 0.2) 
            leftShoulder.C0 = leftShoulder.C0:Lerp(cf(-1, 0.5, 0) * euler(0, -1.5882496193148399 + 0.5235987755982988 * sin((sine + 5) * 0.1), -1.7453292519943295 + -0.5235987755982988 * sin((sine + 5) * 0.1)), 0.2) 
            rightShoulder.C0 = rightShoulder.C0:Lerp(cf(1, 0.5, 0) * euler(0, 1.5707963267948966 + 0.5235987755982988 * sin((sine + 5) * 0.1), 1.7453292519943295 + -0.5235987755982988 * sin((sine + 5) * 0.1)), 0.2) 
            leftHip.C0 = leftHip.C0:Lerp(cf(-1.05 + 0.05 * sin((sine + 7.5) * 0.2), -1, 0.05 * sin(sine * 0.1)) * euler(0, -1.5882496193148399 + -0.2617993877991494 * sin(sine * 0.1), -0.3490658503988659 * sin(sine * 0.1)), 0.2) 
            rightHip.C0 = rightHip.C0:Lerp(cf(1.05 + -0.05 * sin((sine + 7.5) * 0.2), -1, -0.05 * sin(sine * 0.1)) * euler(0, 1.5707963267948966 + -0.2617993877991494 * sin(sine * 0.1), -0.3490658503988659 * sin(sine * 0.1)), 0.2) 
		elseif mode == "L" then
		    neck.C0 = neck.C0:Lerp(cf(0, 1 + 0.01 * sin(sine * 0.4), 0) * euler(-1.5882496193148399 + -0.08726646259971647 * sin((sine + -10) * 0.4), -0.2617993877991494 * sin(sine * 0.2), -3.1590459461097367), 0.2) 
            rootJoint.C0 = rootJoint.C0:Lerp(cf(0.2 * sin(sine * 0.2), 0.1 + 0.3 * sin(sine * 0.4), 0) * euler(-1.4835298641951802, 0.17453292519943295 * sin(sine * 0.2), -3.141592653589793), 0.2) 
            leftShoulder.C0 = leftShoulder.C0:Lerp(cf(-0.7 + -0.2 * sin(sine * 0.2), 0.5 + -0.1 * sin(sine * 0.2), 0) * euler(1.5707963267948966 + 0.3490658503988659 * sin(sine * 0.2), -1.0471975511965976 + 0.08726646259971647 * sin(sine * 0.2), 1.2217304763960306 + 0.3490658503988659 * sin(sine * 0.2)), 0.2) 
            rightShoulder.C0 = rightShoulder.C0:Lerp(cf(0.9 + -0.1 * sin(sine * 0.2), 0.9 + 0.1 * sin(sine * 0.4), -0.5) * euler(1.2217304763960306 + 0.3490658503988659 * sin((sine + -10) * 0.2), 2.2689280275926285 + 0.08726646259971647 * sin(sine * 0.2), 1.5707963267948966 + -0.3490658503988659 * sin((sine + -10) * 0.2)), 0.2) 
            leftHip.C0 = leftHip.C0:Lerp(cf(-0.9 + 0.2 * sin(sine * 0.2), -0.9, 0) * euler(1.5707963267948966, -2.007128639793479 + 0.4363323129985824 * sin((sine + 15) * 0.2), 1.3089969389957472 + -0.6981317007977318 * sin(sine * 0.2)), 0.2) 
            rightHip.C0 = rightHip.C0:Lerp(cf(0.9 + 0.2 * sin(sine * 0.2), -0.9, 0) * euler(1.5707963267948966, 2.007128639793479 + 0.4363323129985824 * sin((sine + 15) * 0.2), -1.3089969389957472 + -0.6981317007977318 * sin(sine * 0.2)), 0.2) 
		elseif mode == "fly" then
            neck.C0 = neck.C0:Lerp(cf(0, 1, 0) * euler(-1.5882496193148399 + 0.2617993877991494 * sin((sine + -30) * 0.025), 0.17453292519943295 * sin((sine + -10) * 0.05), -3.1590459461097367 + 0.17453292519943295 * sin((sine + 30) * 0.05)), 0.2) 
            rootJoint.C0 = rootJoint.C0:Lerp(cf(1 * sin(sine * 0.05), 5 + 1 * sin(sine * 0.05), 1 * sin(sine * 0.025)) * euler(-1.5882496193148399 + 0.17453292519943295 * sin((sine + -15) * 0.025), 0.17453292519943295 * sin(sine * 0.05), -3.1590459461097367 + 0.3490658503988659 * sin((sine + 15) * 0.05)), 0.2) 
            leftShoulder.C0 = leftShoulder.C0:Lerp(cf(-1, 0.5, 0) * euler(1.5707963267948966 + -0.3490658503988659 * sin((sine + -30) * 0.025), -1.5882496193148399 + 0.3490658503988659 * sin((sine + -10) * 0.05), 1.5707963267948966), 0.2) 
            rightShoulder.C0 = rightShoulder.C0:Lerp(cf(1, 0.5, 0) * euler(1.5707963267948966 + -0.3490658503988659 * sin((sine + -30) * 0.025), 1.5707963267948966 + 0.3490658503988659 * sin((sine + -20) * 0.05), -1.5707963267948966), 0.2) 
            leftHip.C0 = leftHip.C0:Lerp(cf(-1, -1, 0) * euler(1.5707963267948966, -1.5882496193148399 + 0.2617993877991494 * sin((sine + -7) * 0.05), 1.5707963267948966 + 0.3490658503988659 * sin((sine + -10) * 0.025)), 0.2) 
            rightHip.C0 = rightHip.C0:Lerp(cf(1, -1, 0) * euler(1.5707963267948966, 1.5707963267948966 + 0.2617993877991494 * sin((sine + -10) * 0.05), -1.5707963267948966 + -0.3490658503988659 * sin((sine + -5) * 0.025)), 0.2) 
--[[MW_animator progress save: 0, 0, 0, 0.1, -91, 15, -30, 0.025, 1, 0, 0, 0.1, 0, 10, -10, 0.05, 0, 0, 0, 0.1, -181, 10, 30, 0.05, 0, 1, 30, 0.05, -91, 10, -15, 0.025, 5, 1, 0, 0.05, 0, 10, 0, 0.05, 0, 1, 0, 0.025, -181, 20, 15, 0.05, -1, 0, 0, 0.1, 90, -20, -30, 0.025, 0.5, 0, 0, 0.1, -91, 20, -10, 0.05, 0, 0, 0, 0.1, 90, 0, 30, 0, 1, 0, 0, 0.1, 90, -20, -30, 0.025, 0.5, 0, 0, 0.1, 90, 20, -20, 0.05, 0, 0, 0, 0.1, -90, 0, 0, 0.1, -1, 0, 0, 0.1, 90, 0, 0, 0.1, -1, 0, 0, 0.1, -91, 15, -7, 0.05, 0, 0, 0, 0.1, 90, 20, -10, 0.025, 1, 0, 0, 0.1, 90, 0, 0, 0.1, -1, 0, 0, 0.1, 90, 15, -10, 0.05, 0, 0, 0, 0.1, -90, -20, -5, 0.025]]
		elseif mode == "floss" then
            neck.C0 = neck.C0:Lerp(cf(0, 1, 0) * euler(-1.5882496193148399 + 0.08726646259971647 * sin((sine + 3.5) * 0.2), -0.1308996938995747 * sin((sine + 7.5) * 0.1), -3.1590459461097367 + -0.08726646259971647 * sin((sine + 7.5) * 0.1)), 0.2) 
            rootJoint.C0 = rootJoint.C0:Lerp(cf(-0.1 * sin(sine * 0.1), -0.1 * sin(sine * 0.2), 0) * euler(-1.5882496193148399, 0.17453292519943295 * sin((sine + 7.5) * 0.1), -3.1590459461097367 + 0.17453292519943295 * sin((sine + 7.5) * 0.1)), 0.2) 
            leftShoulder.C0 = leftShoulder.C0:Lerp(cf(-1, 0.5, -0.2) * euler(1.9198621771937625, -1.5707963267948966 + -0.3490658503988659 * sin((sine + 7.5) * 0.1), 1.7453292519943295 + 0.17453292519943295 * sin((sine + 15) * 0.1)), 0.2) 
            rightShoulder.C0 = rightShoulder.C0:Lerp(cf(1, 0.5, -0.2) * euler(-1.7453292519943295, 1.5707963267948966 + 0.3490658503988659 * sin((sine + 7.5) * 0.1), 1.9198621771937625 + 0.17453292519943295 * sin((sine + 15) * 0.1)), 0.2) 
            leftHip.C0 = leftHip.C0:Lerp(cf(-1, -1 + -0.2 * sin((sine + 7.5) * 0.1), 0) * euler(1.5707963267948966 + 0.08726646259971647 * sin((sine + 7.5) * 0.1), -1.7453292519943295 + 0.3490658503988659 * sin((sine + 7.5) * 0.1), 1.5707963267948966), 0.2) 
            rightHip.C0 = rightHip.C0:Lerp(cf(1, -1 + 0.2 * sin((sine + 7.5) * 0.1), 0) * euler(1.5707963267948966 + -0.08726646259971647 * sin((sine + 7.5) * 0.1), 1.7453292519943295 + 0.3490658503988659 * sin((sine + 7.5) * 0.1), -1.5707963267948966), 0.2) 
        end
    end
end
end)


AnimationsSection:NewButton("netless needed for all animations", "its needed", function()
    for i,v in next, game:GetService("Players").LocalPlayer.Character:GetDescendants() do
if v:IsA("BasePart") and v.Name ~="HumanoidRootPart" then 
game:GetService("RunService").Heartbeat:connect(function()
v.Velocity = Vector3.new(0,35,0)
wait(0.5)
end)
end
end

game:GetService("StarterGui"):SetCore("SendNotification", { 
	Title = "Notification";
	Text = "Netless activated";
	Icon = "rbxthumb://type=Asset&id=5107182114&w=150&h=150"})
Duration = 16;
end)


MainSection:NewButton("AURATUS X", "VERY OP SCRIPT HUB", function()
    _G.Toggle_GUI = "z" -- keybind to open/close gui

--[[ Credits - MrQuack#8010  Showcase - SMOKEZ SQUAD 

]]

--[[
Hello and welcome to Auratus X. Auratus X is a free scrit hub that amasses scripts from popular exploiting/script sharing areas in the exploiting community. Auratus X is a reliable source because it supports over 150+ Games and has hundreds of scripts implanted.

**The Default Keybind to open is Z , you can change it in the script, scroll down and you'll see it.**

IF IT DOESNT LOAD JUST GIVE IT 5-10 Secs because it has hundreds of scripts.



]]
while not game:IsLoaded() do
    wait(0.1)
end
loadstring(game:HttpGet("https://pastebin.com/raw/mtrRP1H1", true))()
end)


MainSection:NewButton("ghost hub script", "sub to ghost player", function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/GhostPlayer352/Test4/main/GhostHub'))()
end)


MainSection:NewButton("fe pendulum script hub", "its good -_-", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Tescalus/Pendulum-Hubs-Source/main/Pendulum%20Hub%20V5.lua"))()
end)


MainSection:NewButton("iv fe admin", "its good", function()
    -- // Iv- Admin
 loadstring(game:HttpGet("\104\116\116\112\115\58\47\47\114\97\119\46\103\105\116\104\117\98\117\115\101\114\99\111\110\116\101\110\116\46\99\111\109\47\79\109\110\105\112\111\116\101\110\99\101\68\101\118\101\108\111\112\101\114\47\78\117\109\98\101\114\47\109\97\105\110\47\49\46\108\117\97"))()

end)


MainSection:NewButton("coolkid gui", "your cool", function()
    loadstring(game:GetObjects("rbxassetid://8127297852")[1].Source)()
end)


MainSection:NewButton("ultimate trolling gui", "its good trust me", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Blukez/Scripts/main/UTG%20V3%20RAW"))()

--//✔103 Commands!!✔\\--
--\\✔Made by Blukez✔//
 --[[⏬ Commands ⏬]]--

-- sonic
-- gale
-- among us
-- killbot
-- neko main
-- smug
-- shadow blade
-- fishing rod
-- sword stand
-- neptunion
-- rb neptunion
-- wall
-- achromatic glitcher
-- flaming cube
-- spider
-- cop
-- chips
-- joy
-- ultimate meme dance
-- chill
-- wallwalk
-- grapple
-- krystal dance
-- stand
-- fling punch gui
-- server admin
-- ban hammmer
-- parkour god
-- sniper
-- ender
-- vr sword
-- caducus
-- elio blasio
-- minigun
-- car
-- carnage
-- segs doll
-- titan
-- gun
-- cat
-- lutris
-- memeus
-- pen
-- xester
-- broomstick
-- headless
-- head hold
-- goopie
-- orange justice
-- dumb
-- floss
-- distract dance
-- russian kick
-- insanity powers
-- zen
-- hell robotics
-- touch kill
-- pillow
-- rainbow king
-- pp
-- genocider
-- abyss eye
-- rolex
-- triangle chat
-- take the l
-- naruto
-- aureate
-- blackhole
-- flaming umbrella
-- rc tank
-- electro swing
-- spellcaster
-- neko
-- racer
-- pixel car
-- christmas scythe
-- christmas sniper
-- void eye
-- scout
-- plane
-- bike
-- vapor gun
-- bobs
-- noob humper
-- pumpkin lord
-- shooter fighter
-- void duel
-- john doe
-- boots
-- penguin dance
-- golem
-- chair
-- chat spy
-- rtx
-- skateboard
-- eggdog
-- stilts
-- pyramid
-- gamer
-- hacker x
-- drone
-- vr
end)


MainSection:NewButton("orca hub ", "is it good?", function()
    loadstring(game:HttpGetAsync("https://raw.githubusercontent.com/richie0866/orca/master/public/latest.lua"))()
end)


MainSection:NewButton("tigron hub v2", "tigron can be free", function()
    -- Gui to Lua
-- Version: 3.2

-- Instances:

local CMDS = Instance.new("ScreenGui")
local CMDSframe = Instance.new("Frame")
local scrollingCMDS = Instance.new("ScrollingFrame")
local minigunCMDS = Instance.new("TextLabel")
local rifleCMDS = Instance.new("TextLabel")
local bananaCMDS = Instance.new("TextLabel")
local suicideCMDS = Instance.new("TextLabel")
local shotgunCMDS = Instance.new("TextLabel")
local carCMDS = Instance.new("TextLabel")
local noobsexCMDS = Instance.new("TextLabel")
local hangCMDS = Instance.new("TextLabel")
local ppv2CMDS = Instance.new("TextLabel")
local beeCMDS = Instance.new("TextLabel")
local pistolCMDS = Instance.new("TextLabel")
local planesoon = Instance.new("TextLabel")
local furrysoon = Instance.new("TextLabel")
local something = Instance.new("TextLabel")
local title = Instance.new("TextLabel")
local close = Instance.new("TextButton")

--Properties:

CMDS.Name = "CMDS"
CMDS.Parent = game.CoreGui
CMDS.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

CMDSframe.Name = "CMDS frame"
CMDSframe.Parent = CMDS
CMDSframe.Active = true
CMDSframe.BackgroundColor3 = Color3.fromRGB(5, 5, 5)
CMDSframe.BorderColor3 = Color3.fromRGB(5, 5, 5)
CMDSframe.Position = UDim2.new(0.689784527, 0, 0.314907879, 0)
CMDSframe.Size = UDim2.new(0, 205, 0, 241)
CMDSframe.Draggable = true

scrollingCMDS.Name = "scrollingCMDS"
scrollingCMDS.Parent = CMDSframe
scrollingCMDS.Active = true
scrollingCMDS.BackgroundColor3 = Color3.fromRGB(20, 20, 20)
scrollingCMDS.BorderColor3 = Color3.fromRGB(20, 20, 20)
scrollingCMDS.Position = UDim2.new(0.115989119, 0, 0.12033195, 0)
scrollingCMDS.Size = UDim2.new(0, 157, 0, 190)
scrollingCMDS.CanvasPosition = Vector2.new(0, 484.799988)
scrollingCMDS.CanvasSize = UDim2.new(0, 0, 2.79999995, 0)

minigunCMDS.Name = "minigunCMDS"
minigunCMDS.Parent = scrollingCMDS
minigunCMDS.BackgroundColor3 = Color3.fromRGB(20, 20, 20)
minigunCMDS.BorderColor3 = Color3.fromRGB(20, 20, 20)
minigunCMDS.Size = UDim2.new(0, 157, 0, 50)
minigunCMDS.Font = Enum.Font.Gotham
minigunCMDS.Text = ".Minigun"
minigunCMDS.TextColor3 = Color3.fromRGB(255, 255, 255)
minigunCMDS.TextSize = 14.000

rifleCMDS.Name = "rifleCMDS"
rifleCMDS.Parent = scrollingCMDS
rifleCMDS.BackgroundColor3 = Color3.fromRGB(20, 20, 20)
rifleCMDS.BorderColor3 = Color3.fromRGB(20, 20, 20)
rifleCMDS.Position = UDim2.new(0, 0, 0.0638365895, 0)
rifleCMDS.Size = UDim2.new(0, 157, 0, 50)
rifleCMDS.Font = Enum.Font.Gotham
rifleCMDS.Text = ".Rifle"
rifleCMDS.TextColor3 = Color3.fromRGB(255, 255, 255)
rifleCMDS.TextSize = 14.000

bananaCMDS.Name = "bananaCMDS"
bananaCMDS.Parent = scrollingCMDS
bananaCMDS.BackgroundColor3 = Color3.fromRGB(20, 20, 20)
bananaCMDS.BorderColor3 = Color3.fromRGB(20, 20, 20)
bananaCMDS.Position = UDim2.new(0, 0, 0.137704641, 0)
bananaCMDS.Size = UDim2.new(0, 157, 0, 50)
bananaCMDS.Font = Enum.Font.Gotham
bananaCMDS.Text = ".Banana"
bananaCMDS.TextColor3 = Color3.fromRGB(255, 255, 255)
bananaCMDS.TextSize = 14.000

suicideCMDS.Name = "suicideCMDS"
suicideCMDS.Parent = scrollingCMDS
suicideCMDS.BackgroundColor3 = Color3.fromRGB(20, 20, 20)
suicideCMDS.BorderColor3 = Color3.fromRGB(20, 20, 20)
suicideCMDS.Position = UDim2.new(0, 0, 0.211572677, 0)
suicideCMDS.Size = UDim2.new(0, 157, 0, 50)
suicideCMDS.Font = Enum.Font.Gotham
suicideCMDS.Text = ".Suicide"
suicideCMDS.TextColor3 = Color3.fromRGB(255, 255, 255)
suicideCMDS.TextSize = 14.000

shotgunCMDS.Name = "shotgunCMDS"
shotgunCMDS.Parent = scrollingCMDS
shotgunCMDS.BackgroundColor3 = Color3.fromRGB(20, 20, 20)
shotgunCMDS.BorderColor3 = Color3.fromRGB(20, 20, 20)
shotgunCMDS.Position = UDim2.new(0, 0, 0.285668701, 0)
shotgunCMDS.Size = UDim2.new(0, 157, 0, 50)
shotgunCMDS.Font = Enum.Font.Gotham
shotgunCMDS.Text = ".Shotgun"
shotgunCMDS.TextColor3 = Color3.fromRGB(255, 255, 255)
shotgunCMDS.TextSize = 14.000

carCMDS.Name = "carCMDS"
carCMDS.Parent = scrollingCMDS
carCMDS.BackgroundColor3 = Color3.fromRGB(20, 20, 20)
carCMDS.BorderColor3 = Color3.fromRGB(20, 20, 20)
carCMDS.Position = UDim2.new(0, 0, 0.359764725, 0)
carCMDS.Size = UDim2.new(0, 157, 0, 50)
carCMDS.Font = Enum.Font.Gotham
carCMDS.Text = ".Car"
carCMDS.TextColor3 = Color3.fromRGB(255, 255, 255)
carCMDS.TextSize = 14.000

noobsexCMDS.Name = "noobsexCMDS"
noobsexCMDS.Parent = scrollingCMDS
noobsexCMDS.BackgroundColor3 = Color3.fromRGB(20, 20, 20)
noobsexCMDS.BorderColor3 = Color3.fromRGB(20, 20, 20)
noobsexCMDS.Position = UDim2.new(0, 0, 0.433860749, 0)
noobsexCMDS.Size = UDim2.new(0, 157, 0, 50)
noobsexCMDS.Font = Enum.Font.Gotham
noobsexCMDS.Text = ".NoobSex"
noobsexCMDS.TextColor3 = Color3.fromRGB(255, 255, 255)
noobsexCMDS.TextSize = 14.000

hangCMDS.Name = "hangCMDS"
hangCMDS.Parent = scrollingCMDS
hangCMDS.BackgroundColor3 = Color3.fromRGB(20, 20, 20)
hangCMDS.BorderColor3 = Color3.fromRGB(20, 20, 20)
hangCMDS.Position = UDim2.new(0, 0, 0.506474853, 0)
hangCMDS.Size = UDim2.new(0, 157, 0, 50)
hangCMDS.Font = Enum.Font.Gotham
hangCMDS.Text = ".Hang"
hangCMDS.TextColor3 = Color3.fromRGB(255, 255, 255)
hangCMDS.TextSize = 14.000

ppv2CMDS.Name = "ppv2CMDS"
ppv2CMDS.Parent = scrollingCMDS
ppv2CMDS.BackgroundColor3 = Color3.fromRGB(20, 20, 20)
ppv2CMDS.BorderColor3 = Color3.fromRGB(20, 20, 20)
ppv2CMDS.Position = UDim2.new(0, 0, 0.580570877, 0)
ppv2CMDS.Size = UDim2.new(0, 157, 0, 50)
ppv2CMDS.Font = Enum.Font.Gotham
ppv2CMDS.Text = ".PPv2"
ppv2CMDS.TextColor3 = Color3.fromRGB(255, 255, 255)
ppv2CMDS.TextSize = 14.000

beeCMDS.Name = "beeCMDS"
beeCMDS.Parent = scrollingCMDS
beeCMDS.BackgroundColor3 = Color3.fromRGB(20, 20, 20)
beeCMDS.BorderColor3 = Color3.fromRGB(20, 20, 20)
beeCMDS.Position = UDim2.new(0, 0, 0.654666901, 0)
beeCMDS.Size = UDim2.new(0, 157, 0, 50)
beeCMDS.Font = Enum.Font.Gotham
beeCMDS.Text = ".Bee"
beeCMDS.TextColor3 = Color3.fromRGB(255, 255, 255)
beeCMDS.TextSize = 14.000

pistolCMDS.Name = "pistolCMDS"
pistolCMDS.Parent = scrollingCMDS
pistolCMDS.BackgroundColor3 = Color3.fromRGB(20, 20, 20)
pistolCMDS.BorderColor3 = Color3.fromRGB(20, 20, 20)
pistolCMDS.Position = UDim2.new(0, 0, 0.728762925, 0)
pistolCMDS.Size = UDim2.new(0, 157, 0, 50)
pistolCMDS.Font = Enum.Font.Gotham
pistolCMDS.Text = ".Pistol"
pistolCMDS.TextColor3 = Color3.fromRGB(255, 255, 255)
pistolCMDS.TextSize = 14.000

planesoon.Name = "planesoon"
planesoon.Parent = scrollingCMDS
planesoon.BackgroundColor3 = Color3.fromRGB(20, 20, 20)
planesoon.BorderColor3 = Color3.fromRGB(20, 20, 20)
planesoon.Position = UDim2.new(0, 0, 0.802858889, 0)
planesoon.Size = UDim2.new(0, 157, 0, 50)
planesoon.Font = Enum.Font.Gotham
planesoon.Text = ".Plane"
planesoon.TextColor3 = Color3.fromRGB(255, 255, 255)
planesoon.TextSize = 14.000

furrysoon.Name = "furrysoon"
furrysoon.Parent = scrollingCMDS
furrysoon.BackgroundColor3 = Color3.fromRGB(20, 20, 20)
furrysoon.BorderColor3 = Color3.fromRGB(20, 20, 20)
furrysoon.Position = UDim2.new(0, 0, 0.875473022, 0)
furrysoon.Size = UDim2.new(0, 157, 0, 50)
furrysoon.Font = Enum.Font.Gotham
furrysoon.Text = ".Wings (soon)"
furrysoon.TextColor3 = Color3.fromRGB(255, 255, 255)
furrysoon.TextSize = 14.000

something.Name = "something"
something.Parent = scrollingCMDS
something.BackgroundColor3 = Color3.fromRGB(20, 20, 20)
something.BorderColor3 = Color3.fromRGB(20, 20, 20)
something.Position = UDim2.new(0, 0, 0.948087156, 0)
something.Size = UDim2.new(0, 157, 0, 50)
something.Font = Enum.Font.Gotham
something.Text = ".Broom"
something.TextColor3 = Color3.fromRGB(255, 255, 255)
something.TextSize = 14.000

title.Name = "title"
title.Parent = CMDSframe
title.BackgroundColor3 = Color3.fromRGB(5, 5, 5)
title.BorderColor3 = Color3.fromRGB(5, 5, 5)
title.Size = UDim2.new(0, 205, 0, 29)
title.Font = Enum.Font.SourceSans
title.Text = "CMDS"
title.TextColor3 = Color3.fromRGB(255, 255, 255)
title.TextSize = 21.000

close.Name = "close"
close.Parent = CMDSframe
close.BackgroundColor3 = Color3.fromRGB(5, 5, 5)
close.BorderColor3 = Color3.fromRGB(5, 5, 5)
close.BorderSizePixel = 0
close.Position = UDim2.new(0.814634144, 0, 0, 0)
close.Size = UDim2.new(0, 38, 0, 29)
close.Font = Enum.Font.SourceSans
close.Text = "X"
close.TextColor3 = Color3.fromRGB(255, 255, 255)
close.TextSize = 26.000
close.MouseButton1Down:connect(function()
	CMDSframe.Visible = false
end)

-- Scripts:

local function RQQQHX_fake_script() -- minigunCMDS. 
	local script = Instance.new('Script', minigunCMDS)

	
	--[[ Last synced 10/7/2020 06:14                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         ]] require(5246683085) --[[                                                                                                  ]]--
end
coroutine.wrap(RQQQHX_fake_script)()

end)


MainSection:NewButton("xxhub", "its very cool", function()
    loadstring(game:HttpGet(('https://pastebin.com/raw/YVE4njap'),true))()
end)


MainSection:NewButton("ButtonText", "ButtonInfo", function()
    
--ORPLAYZ SHOWCASED THIS SCRIPT, ANYBODY WHO SHOWCASES WITHOUT PERMISSION OR CREDIT WILL BE PRESSED CHARGES (LMT.197 Licence)
--SUBSCRIBE TO ORPLAYZ: https://www.youtube.com/channel/UC1UwUVxrjM2Sb4duUoR6zfA?sub_confirmation=1



game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("ORPLAYZ SCRIPT LOADED" ,"All")
game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("Sub To OrPlayz" ,"All")

--[[
    fe nameless animations v2
    showcased by OrPlayz
    Subscribe To OrPlayz on Youtube
    no hats needed, r15 supported
]]

if "myworld reanimate again" then
    --reanimate by MyWorld#4430 discord.gg/pYVHtSJmEY
    local Vector3_101 = Vector3.new(1, 0, 1)
    local netless_Y = Vector3.new(0, 25.1, 0)
    local function getNetlessVelocity(realPartVelocity) --change this if you have a better method
        local mag = realPartVelocity.Magnitude
        if (mag > 1) and (mag < 100) then
            local unit = realPartVelocity.Unit
            if (unit.Y > 0.7) or (unit.Y < -0.7) then
                return realPartVelocity * (25.1 / realPartVelocity.Y)
            end
            realPartVelocity = unit * 100
        end
        return (realPartVelocity * Vector3_101) + netless_Y
    end
    local simradius = "shp" --simulation radius (net bypass) method
    --"shp" - sethiddenproperty
    --"ssr" - setsimulationradius
    --false - disable
    local noclipAllParts = false --set it to true if you want noclip
    local flingpart = "HumanoidRootPart" --the part that will be used to fling (ctrl + F "fling function")
    local antiragdoll = true --removes hingeConstraints and ballSocketConstraints from your character
    local newanimate = true --disables the animate script and enables after reanimation
    local discharscripts = true --disables all localScripts parented to your character before reanimation
    local R15toR6 = true --tries to convert your character to r6 if its r15
    local hatcollide = false --makes hats cancollide (credit to ShownApe) (works only with reanimate method 0)
    local humState16 = true --enables collisions for limbs before the humanoid dies (using hum:ChangeState)
    local addtools = false --puts all tools from backpack to character and lets you hold them after reanimation
    local hedafterneck = true --disable aligns for head and enable after neck or torso is removed
    local loadtime = game:GetService("Players").RespawnTime + 0.5 --anti respawn delay
    local method = 3 --reanimation method
    --methods:
    --0 - breakJoints (takes [loadtime] seconds to laod)
    --1 - limbs
    --2 - limbs + anti respawn
    --3 - limbs + breakJoints after [loadtime] seconds
    --4 - remove humanoid + breakJoints
    --5 - remove humanoid + limbs
    local alignmode = 2 --AlignPosition mode
    --modes:
    --1 - AlignPosition rigidity enabled true
    --2 - 2 AlignPositions rigidity enabled both true and false
    --3 - AlignPosition rigidity enabled false
    
    local lp = game:GetService("Players").LocalPlayer
    local rs = game:GetService("RunService")
    local stepped = rs.Stepped
    local heartbeat = rs.Heartbeat
    local renderstepped = rs.RenderStepped
    local sg = game:GetService("StarterGui")
    local ws = game:GetService("Workspace")
    local cf = CFrame.new
    local v3 = Vector3.new
    local v3_0 = Vector3.zero
    local inf = math.huge
    
    local c = lp.Character
    
    if not (c and c.Parent) then
    	return
    end
    
    c:GetPropertyChangedSignal("Parent"):Connect(function()
        if not (c and c.Parent) then
    	    c = nil
    	end
    end)
    
    local function gp(parent, name, className)
    	if typeof(parent) == "Instance" then
    		for i, v in pairs(parent:GetChildren()) do
    			if (v.Name == name) and v:IsA(className) then
    				return v
    			end
    		end
    	end
    	return nil
    end
    
    if type(getNetlessVelocity) ~= "function" then
        getNetlessVelocity = nil
    end
    
    local function align(Part0, Part1)
    	Part0.CustomPhysicalProperties = PhysicalProperties.new(0, 0, 0, 0, 0)
    
    	local att0 = Instance.new("Attachment")
    	att0.Orientation = v3_0
    	att0.Position = v3_0
    	att0.Name = "att0_" .. Part0.Name
    	local att1 = Instance.new("Attachment")
    	att1.Orientation = v3_0
    	att1.Position = v3_0
    	att1.Name = "att1_" .. Part1.Name
    
    	if (alignmode == 1) or (alignmode == 2) then
    		local ape = Instance.new("AlignPosition", att0)
    		ape.ApplyAtCenterOfMass = false
    		ape.MaxForce = inf
    		ape.MaxVelocity = inf
    		ape.ReactionForceEnabled = false
    		ape.Responsiveness = 200
    		ape.Attachment1 = att1
    		ape.Attachment0 = att0
    		ape.Name = "AlignPositionRtrue"
    		ape.RigidityEnabled = true
    	end
    
    	if (alignmode == 2) or (alignmode == 3) then
    		local apd = Instance.new("AlignPosition", att0)
    		apd.ApplyAtCenterOfMass = false
    		apd.MaxForce = inf
    		apd.MaxVelocity = inf
    		apd.ReactionForceEnabled = false
    		apd.Responsiveness = 200
    		apd.Attachment1 = att1
    		apd.Attachment0 = att0
    		apd.Name = "AlignPositionRfalse"
    		apd.RigidityEnabled = false
    	end
    
    	local ao = Instance.new("AlignOrientation", att0)
    	ao.MaxAngularVelocity = inf
    	ao.MaxTorque = inf
    	ao.PrimaryAxisOnly = false
    	ao.ReactionTorqueEnabled = false
    	ao.Responsiveness = 200
    	ao.Attachment1 = att1
    	ao.Attachment0 = att0
    	ao.RigidityEnabled = false
    
    	if getNetlessVelocity then
    	    local vel = Part0.Velocity
    	    local velpart = Part1
            local rsteppedcon = renderstepped:Connect(function()
                Part0.Velocity = vel
            end)
            local heartbeatcon = heartbeat:Connect(function()
                vel = Part0.Velocity
                Part0.Velocity = getNetlessVelocity(velpart.Velocity)
            end)
            local attcon = nil
            Part0:GetPropertyChangedSignal("Parent"):Connect(function()
                if not (Part0 and Part0.Parent) then
                    rsteppedcon:Disconnect()
                    heartbeatcon:Disconnect()
                    attcon:Disconnect()
                end
            end)
            attcon = att1:GetPropertyChangedSignal("Parent"):Connect(function()
    	        if not (att1 and att1.Parent) then
    	            attcon:Disconnect()
                    velpart = Part0
    	        else
    	            velpart = att1.Parent
    	            if not velpart:IsA("BasePart") then
    	                velpart = Part0
    	            end
    	        end
    	    end)
    	end
    	
    	att0.Parent = Part0
        att1.Parent = Part1
    end
    
    local function respawnrequest()
    	local ccfr = ws.CurrentCamera.CFrame
    	local c = lp.Character
    	lp.Character = nil
    	lp.Character = c
    	local con = nil
    	con = ws.CurrentCamera.Changed:Connect(function(prop)
    	    if (prop ~= "Parent") and (prop ~= "CFrame") then
    	        return
    	    end
    	    ws.CurrentCamera.CFrame = ccfr
    	    con:Disconnect()
        end)
    end
    
    local destroyhum = (method == 4) or (method == 5)
    local breakjoints = (method == 0) or (method == 4)
    local antirespawn = (method == 0) or (method == 2) or (method == 3)
    
    hatcollide = hatcollide and (method == 0)
    
    addtools = addtools and gp(lp, "Backpack", "Backpack")
    
    local fenv = getfenv()
    local shp = fenv.sethiddenproperty or fenv.set_hidden_property or fenv.set_hidden_prop or fenv.sethiddenprop
    local ssr = fenv.setsimulationradius or fenv.set_simulation_radius or fenv.set_sim_radius or fenv.setsimradius or fenv.set_simulation_rad or fenv.setsimulationrad
    
    if shp and (simradius == "shp") then
    	spawn(function()
    		while c and heartbeat:Wait() do
    			shp(lp, "SimulationRadius", inf)
    		end
    	end)
    elseif ssr and (simradius == "ssr") then
    	spawn(function()
    		while c and heartbeat:Wait() do
    			ssr(inf)
    		end
    	end)
    end
    
    antiragdoll = antiragdoll and function(v)
    	if v:IsA("HingeConstraint") or v:IsA("BallSocketConstraint") then
    		v.Parent = nil
    	end
    end
    
    if antiragdoll then
    	for i, v in pairs(c:GetDescendants()) do
    		antiragdoll(v)
    	end
    	c.DescendantAdded:Connect(antiragdoll)
    end
    
    if antirespawn then
    	respawnrequest()
    end
    
    if method == 0 then
    	wait(loadtime)
    	if not c then
    		return
    	end
    end
    
    if discharscripts then
    	for i, v in pairs(c:GetChildren()) do
    		if v:IsA("LocalScript") then
    			v.Disabled = true
    		end
    	end
    elseif newanimate then
    	local animate = gp(c, "Animate", "LocalScript")
    	if animate and (not animate.Disabled) then
    		animate.Disabled = true
    	else
    		newanimate = false
    	end
    end
    
    if addtools then
    	for i, v in pairs(addtools:GetChildren()) do
    		if v:IsA("Tool") then
    			v.Parent = c
    		end
    	end
    end
    
    pcall(function()
    	settings().Physics.AllowSleep = false
    	settings().Physics.PhysicsEnvironmentalThrottle = Enum.EnviromentalPhysicsThrottle.Disabled
    end)
    
    local OLDscripts = {}
    
    for i, v in pairs(c:GetDescendants()) do
    	if v.ClassName == "Script" then
    		table.insert(OLDscripts, v)
    	end
    end
    
    local scriptNames = {}
    
    for i, v in pairs(c:GetDescendants()) do
    	if v:IsA("BasePart") then
    		local newName = tostring(i)
    		local exists = true
    		while exists do
    			exists = false
    			for i, v in pairs(OLDscripts) do
    				if v.Name == newName then
    					exists = true
    				end
    			end
    			if exists then
    				newName = newName .. "_"    
    			end
    		end
    		table.insert(scriptNames, newName)
    		Instance.new("Script", v).Name = newName
    	end
    end
    
    c.Archivable = true
    local hum = c:FindFirstChildOfClass("Humanoid")
    if hum then
    	for i, v in pairs(hum:GetPlayingAnimationTracks()) do
    		v:Stop()
    	end
    end
    local cl = c:Clone()
    if hum and humState16 then
        hum:ChangeState(Enum.HumanoidStateType.Physics)
        if destroyhum then
            wait(1.6)
        end
    end
    if hum and hum.Parent and destroyhum then
        hum:Destroy()
    end
    
    if not c then
        return
    end
    
    local head = gp(c, "Head", "BasePart")
    local torso = gp(c, "Torso", "BasePart") or gp(c, "UpperTorso", "BasePart")
    local root = gp(c, "HumanoidRootPart", "BasePart")
    if hatcollide and c:FindFirstChildOfClass("Accessory") then
        local anything = c:FindFirstChildOfClass("BodyColors") or gp(c, "Health", "Script")
        if not (torso and root and anything) then
            return
        end
        torso:Destroy()
        root:Destroy()
        if shp then
            for i,v in pairs(c:GetChildren()) do
                if v:IsA("Accessory") then
                    shp(v, "BackendAccoutrementState", 0)
                end 
            end
        end
        anything:Destroy()
    end
    
    local model = Instance.new("Model", c)
    model.Name = model.ClassName
    
    model:GetPropertyChangedSignal("Parent"):Connect(function()
        if not (model and model.Parent) then
    	    model = nil
        end
    end)
    
    for i, v in pairs(c:GetChildren()) do
    	if v ~= model then
    		if addtools and v:IsA("Tool") then
    			for i1, v1 in pairs(v:GetDescendants()) do
    				if v1 and v1.Parent and v1:IsA("BasePart") then
    					local bv = Instance.new("BodyVelocity", v1)
    					bv.Velocity = v3_0
    					bv.MaxForce = v3(1000, 1000, 1000)
    					bv.P = 1250
    					bv.Name = "bv_" .. v.Name
    				end
    			end
    		end
    		v.Parent = model
    	end
    end
    
    if breakjoints then
    	model:BreakJoints()
    else
    	if head and torso then
    		for i, v in pairs(model:GetDescendants()) do
    			if v:IsA("Weld") or v:IsA("Snap") or v:IsA("Glue") or v:IsA("Motor") or v:IsA("Motor6D") then
    				local save = false
    				if (v.Part0 == torso) and (v.Part1 == head) then
    					save = true
    				end
    				if (v.Part0 == head) and (v.Part1 == torso) then
    					save = true
    				end
    				if save then
    					if hedafterneck then
    						hedafterneck = v
    					end
    				else
    					v:Destroy()
    				end
    			end
    		end
    	end
    	if method == 3 then
    		spawn(function()
    			wait(loadtime)
    			if model then
    				model:BreakJoints()
    			end
    		end)
    	end
    end
    
    cl.Parent = c
    for i, v in pairs(cl:GetChildren()) do
    	v.Parent = c
    end
    cl:Destroy()
    
    local noclipmodel = (noclipAllParts and c) or model
    local noclipcon = nil
    local function uncollide()
    	if noclipmodel then
    		for i, v in pairs(noclipmodel:GetDescendants()) do
    		    if v:IsA("BasePart") then
    			    v.CanCollide = false
    		    end
    		end
    	else
    		noclipcon:Disconnect()
    	end
    end
    noclipcon = stepped:Connect(uncollide)
    uncollide()
    
    for i, scr in pairs(model:GetDescendants()) do
    	if (scr.ClassName == "Script") and table.find(scriptNames, scr.Name) then
    		local Part0 = scr.Parent
    		if Part0:IsA("BasePart") then
    			for i1, scr1 in pairs(c:GetDescendants()) do
    				if (scr1.ClassName == "Script") and (scr1.Name == scr.Name) and (not scr1:IsDescendantOf(model)) then
    					local Part1 = scr1.Parent
    					if (Part1.ClassName == Part0.ClassName) and (Part1.Name == Part0.Name) then
    						align(Part0, Part1)
    						scr:Destroy()
    						scr1:Destroy()
    						break
    					end
    				end
    			end
    		end
    	end
    end
    
    for i, v in pairs(c:GetDescendants()) do
    	if v and v.Parent and (not v:IsDescendantOf(model)) then
    		if v:IsA("Decal") then
    		    v.Transparency = 1
    		elseif v:IsA("BasePart") then
    			v.Transparency = 1
    			v.Anchored = false
    		elseif v:IsA("ForceField") then
    			v.Visible = false
    		elseif v:IsA("Sound") then
    			v.Playing = false
    		elseif v:IsA("BillboardGui") or v:IsA("SurfaceGui") or v:IsA("ParticleEmitter") or v:IsA("Fire") or v:IsA("Smoke") or v:IsA("Sparkles") then
    			v.Enabled = false
    		end
    	end
    end
    
    if newanimate then
    	local animate = gp(c, "Animate", "LocalScript")
    	if animate then
    		animate.Disabled = false
    	end
    end
    
    if addtools then
    	for i, v in pairs(c:GetChildren()) do
    		if v:IsA("Tool") then
    			v.Parent = addtools
    		end
    	end
    end
    
    local hum0 = model:FindFirstChildOfClass("Humanoid")
    if hum0 then
        hum0:GetPropertyChangedSignal("Parent"):Connect(function()
            if not (hum0 and hum0.Parent) then
                hum0 = nil
            end
        end)
    end
    
    local hum1 = c:FindFirstChildOfClass("Humanoid")
    if hum1 then
        hum1:GetPropertyChangedSignal("Parent"):Connect(function()
            if not (hum1 and hum1.Parent) then
                hum1 = nil
            end
        end)
        
    	ws.CurrentCamera.CameraSubject = hum1
    	local camSubCon = nil
    	local function camSubFunc()
    		camSubCon:Disconnect()
    		if c and hum1 then
    			ws.CurrentCamera.CameraSubject = hum1
    		end
    	end
    	camSubCon = renderstepped:Connect(camSubFunc)
    	if hum0 then
    		hum0:GetPropertyChangedSignal("Jump"):Connect(function()
    			if hum1 then
    				hum1.Jump = hum0.Jump
    			end
    		end)
    	else
    		respawnrequest()
    	end
    end
    
    local rb = Instance.new("BindableEvent", c)
    rb.Event:Connect(function()
    	rb:Destroy()
    	sg:SetCore("ResetButtonCallback", true)
    	if destroyhum then
    		c:BreakJoints()
    		return
    	end
    	if hum0 and (hum0.Health > 0) then
    		model:BreakJoints()
    		hum0.Health = 0
    	end
    	if antirespawn then
    	    respawnrequest()
    	end
    end)
    sg:SetCore("ResetButtonCallback", rb)
    
    spawn(function()
    	while c do
    		if hum0 and hum1 then
    			hum1.Jump = hum0.Jump
    		end
    		wait()
    	end
    	sg:SetCore("ResetButtonCallback", true)
    end)
    
    R15toR6 = R15toR6 and hum1 and (hum1.RigType == Enum.HumanoidRigType.R15)
    if R15toR6 then
        local part = gp(c, "HumanoidRootPart", "BasePart") or gp(c, "UpperTorso", "BasePart") or gp(c, "LowerTorso", "BasePart") or gp(c, "Head", "BasePart") or c:FindFirstChildWhichIsA("BasePart")
    	if part then
    	    local cfr = part.CFrame
    		local R6parts = { 
    			head = {
    				Name = "Head",
    				Size = v3(2, 1, 1),
    				R15 = {
    					Head = 0
    				}
    			},
    			torso = {
    				Name = "Torso",
    				Size = v3(2, 2, 1),
    				R15 = {
    					UpperTorso = 0.2,
    					LowerTorso = -0.8
    				}
    			},
    			root = {
    				Name = "HumanoidRootPart",
    				Size = v3(2, 2, 1),
    				R15 = {
    					HumanoidRootPart = 0
    				}
    			},
    			leftArm = {
    				Name = "Left Arm",
    				Size = v3(1, 2, 1),
    				R15 = {
    					LeftHand = -0.85,
    					LeftLowerArm = -0.2,
    					LeftUpperArm = 0.4
    				}
    			},
    			rightArm = {
    				Name = "Right Arm",
    				Size = v3(1, 2, 1),
    				R15 = {
    					RightHand = -0.85,
    					RightLowerArm = -0.2,
    					RightUpperArm = 0.4
    				}
    			},
    			leftLeg = {
    				Name = "Left Leg",
    				Size = v3(1, 2, 1),
    				R15 = {
    					LeftFoot = -0.85,
    					LeftLowerLeg = -0.15,
    					LeftUpperLeg = 0.6
    				}
    			},
    			rightLeg = {
    				Name = "Right Leg",
    				Size = v3(1, 2, 1),
    				R15 = {
    					RightFoot = -0.85,
    					RightLowerLeg = -0.15,
    					RightUpperLeg = 0.6
    				}
    			}
    		}
    		for i, v in pairs(c:GetChildren()) do
    			if v:IsA("BasePart") then
    				for i1, v1 in pairs(v:GetChildren()) do
    					if v1:IsA("Motor6D") then
    						v1.Part0 = nil
    					end
    				end
    			end
    		end
    		part.Archivable = true
    		for i, v in pairs(R6parts) do
    			local part = part:Clone()
    			part:ClearAllChildren()
    			part.Name = v.Name
    			part.Size = v.Size
    			part.CFrame = cfr
    			part.Anchored = false
    			part.Transparency = 1
    			part.CanCollide = false
    			for i1, v1 in pairs(v.R15) do
    				local R15part = gp(c, i1, "BasePart")
    				local att = gp(R15part, "att1_" .. i1, "Attachment")
    				if R15part then
    					local weld = Instance.new("Weld", R15part)
    					weld.Name = "Weld_" .. i1
    					weld.Part0 = part
    					weld.Part1 = R15part
    					weld.C0 = cf(0, v1, 0)
    					weld.C1 = cf(0, 0, 0)
    					R15part.Massless = true
    					R15part.Name = "R15_" .. i1
    					R15part.Parent = part
    					if att then
    						att.Parent = part
    						att.Position = v3(0, v1, 0)
    					end
    				end
    			end
    			part.Parent = c
    			R6parts[i] = part
    		end
    		local R6joints = {
    			neck = {
    				Parent = R6parts.torso,
    				Name = "Neck",
    				Part0 = R6parts.torso,
    				Part1 = R6parts.head,
    				C0 = cf(0, 1, 0, -1, 0, 0, 0, 0, 1, 0, 1, -0),
    				C1 = cf(0, -0.5, 0, -1, 0, 0, 0, 0, 1, 0, 1, -0)
    			},
    			rootJoint = {
    				Parent = R6parts.root,
    				Name = "RootJoint" ,
    				Part0 = R6parts.root,
    				Part1 = R6parts.torso,
    				C0 = cf(0, 0, 0, -1, 0, 0, 0, 0, 1, 0, 1, -0),
    				C1 = cf(0, 0, 0, -1, 0, 0, 0, 0, 1, 0, 1, -0)
    			},
    			rightShoulder = {
    				Parent = R6parts.torso,
    				Name = "Right Shoulder",
    				Part0 = R6parts.torso,
    				Part1 = R6parts.rightArm,
    				C0 = cf(1, 0.5, 0, 0, 0, 1, 0, 1, -0, -1, 0, 0),
    				C1 = cf(-0.5, 0.5, 0, 0, 0, 1, 0, 1, -0, -1, 0, 0)
    			},
    			leftShoulder = {
    				Parent = R6parts.torso,
    				Name = "Left Shoulder",
    				Part0 = R6parts.torso,
    				Part1 = R6parts.leftArm,
    				C0 = cf(-1, 0.5, 0, 0, 0, -1, 0, 1, 0, 1, 0, 0),
    				C1 = cf(0.5, 0.5, 0, 0, 0, -1, 0, 1, 0, 1, 0, 0)
    			},
    			rightHip = {
    				Parent = R6parts.torso,
    				Name = "Right Hip",
    				Part0 = R6parts.torso,
    				Part1 = R6parts.rightLeg,
    				C0 = cf(1, -1, 0, 0, 0, 1, 0, 1, -0, -1, 0, 0),
    				C1 = cf(0.5, 1, 0, 0, 0, 1, 0, 1, -0, -1, 0, 0)
    			},
    			leftHip = {
    				Parent = R6parts.torso,
    				Name = "Left Hip" ,
    				Part0 = R6parts.torso,
    				Part1 = R6parts.leftLeg,
    				C0 = cf(-1, -1, 0, 0, 0, -1, 0, 1, 0, 1, 0, 0),
    				C1 = cf(-0.5, 1, 0, 0, 0, -1, 0, 1, 0, 1, 0, 0)
    			}
    		}
    		for i, v in pairs(R6joints) do
    			local joint = Instance.new("Motor6D")
    			for prop, val in pairs(v) do
    				joint[prop] = val
    			end
    			R6joints[i] = joint
    		end
    		if hum1 then
        		hum1.RigType = Enum.HumanoidRigType.R6
        		hum1.HipHeight = 0
    		end
    	end
    end
    
    local torso1 = torso
    torso = gp(c, "Torso", "BasePart") or ((not R15toR6) and gp(c, torso.Name, "BasePart"))
    if (typeof(hedafterneck) == "Instance") and head and torso and torso1 then
    	local conNeck = nil
    	local conTorso = nil
    	local contorso1 = nil
    	local aligns = {}
    	local function enableAligns()
    	    conNeck:Disconnect()
            conTorso:Disconnect()
            conTorso1:Disconnect()
    		for i, v in pairs(aligns) do
    			v.Enabled = true
    		end
    	end
    	conNeck = hedafterneck.Changed:Connect(function(prop)
    	    if table.find({"Part0", "Part1", "Parent"}, prop) then
    	        enableAligns()
    		end
    	end)
    	conTorso = torso:GetPropertyChangedSignal("Parent"):Connect(enableAligns)
    	conTorso1 = torso1:GetPropertyChangedSignal("Parent"):Connect(enableAligns)
    	for i, v in pairs(head:GetDescendants()) do
    		if v:IsA("AlignPosition") or v:IsA("AlignOrientation") then
    			i = tostring(i)
    			aligns[i] = v
    			v:GetPropertyChangedSignal("Parent"):Connect(function()
    			    aligns[i] = nil
    			end)
    			v.Enabled = false
    		end
    	end
    end
    
    --[[
        fling function
        usage: fling(target, duration, velocity)
        target can be set to: basePart, CFrame, Vector3, character model or humanoid
        duration (fling time) can be set to a number or a string containing the number (in seconds) will be set to 0.5 if not provided,
        velocity (fling part rotation velocity) can be set to a vector3 value (Vector3.new(20000, 20000, 20000) if not provided)
    ]]
    
    local flingpart0 = gp(model, flingpart, "BasePart")
    local flingpart1 = gp(c, flingpart, "BasePart")
    
    local fling = function() end
    if flingpart0 and flingpart1 then
        flingpart0:GetPropertyChangedSignal("Parent"):Connect(function()
            if not (flingpart0 and flingpart0.Parent) then
                flingpart0 = nil
                fling = function() end
            end
        end)
        flingpart0.Archivable = true
        flingpart1:GetPropertyChangedSignal("Parent"):Connect(function()
            if not (flingpart1 and flingpart1.Parent) then
                flingpart1 = nil
                fling = function() end
            end
        end)
        local att0 = gp(flingpart0, "att0_" .. flingpart0.Name, "Attachment")
        local att1 = gp(flingpart1, "att1_" .. flingpart1.Name, "Attachment")
        if att0 and att1 then
            att0:GetPropertyChangedSignal("Parent"):Connect(function()
                if not (att0 and att0.Parent) then
                    att0 = nil
                    fling = function() end
                end
            end)
            att1:GetPropertyChangedSignal("Parent"):Connect(function()
                if not (att1 and att1.Parent) then
                    att1 = nil
                    fling = function() end
                end
            end)
            local lastfling = nil
            fling = function(target, duration, rotVelocity)
                if typeof(target) == "Instance" then
                    if target:IsA("BasePart") then
                        target = target.Position
                    elseif target:IsA("Model") then
                        target = gp(target, "HumanoidRootPart", "BasePart") or gp(target, "Torso", "BasePart") or gp(target, "UpperTorso", "BasePart") or target:FindFirstChildWhichIsA("BasePart")
                        if target then
                            target = target.Position
                        else
                            return
                        end
                    elseif target:IsA("Humanoid") then
                        local parent = target.Parent
                        if not (parent and parent:IsA("Model")) then
                            return
                        end
                        target = gp(target, "HumanoidRootPart", "BasePart") or gp(target, "Torso", "BasePart") or gp(target, "UpperTorso", "BasePart") or target:FindFirstChildWhichIsA("BasePart")
                        if target then
                            target = target.Position
                        else
                            return
                        end
                    else
                        return
                    end
                elseif typeof(target) == "CFrame" then
                    target = target.Position
                elseif typeof(target) ~= "Vector3" then
                    return
                end
                lastfling = target
                if type(duration) ~= "number" then
                    duration = tonumber(duration) or 0.5
                end
                if typeof(rotVelocity) ~= "Vector3" then
                    rotVelocity = v3(20000, 20000, 20000)
                end
                if not (target and flingpart0 and flingpart1 and att0 and att1) then
                    return
                end
                local flingpart = flingpart0:Clone()
                flingpart.Transparency = 1
                flingpart.Size = v3(0.01, 0.01, 0.01)
                flingpart.CanCollide = false
                flingpart.Name = "flingpart_" .. flingpart0.Name
                flingpart.Anchored = true
                flingpart.Velocity = v3_0
                flingpart.RotVelocity = v3_0
                flingpart:GetPropertyChangedSignal("Parent"):Connect(function()
                    if not (flingpart and flingpart.Parent) then
                        flingpart = nil
                    end
                end)
                flingpart.Parent = flingpart1
                if flingpart0.Transparency > 0.5 then
                    flingpart0.Transparency = 0.5
                end
                att1.Parent = flingpart
                for i, v in pairs(att0:GetChildren()) do
                    if v:IsA("AlignOrientation") then
                        v.Enabled = false
                    end
                end
                local con = nil
                con = heartbeat:Connect(function()
                    if target and (lastfling == target) and flingpart and flingpart0 and flingpart1 and att0 and att1 then
                        flingpart0.RotVelocity = rotVelocity
                        flingpart.Position = target
                    else
                        con:Disconnect()
                    end
                end)
                local rsteppedRotVel = v3(
                    ((rotVelocity.X > 0) and -1) or 1,
                    ((rotVelocity.Y > 0) and -1) or 1,
                    ((rotVelocity.Z > 0) and -1) or 1
                )
                local con = nil
                con = renderstepped:Connect(function()
                    if target and (lastfling == target) and flingpart and flingpart0 and flingpart1 and att0 and att1 then
                        flingpart0.RotVelocity = rsteppedRotVel
                        flingpart.Position = target
                    else
                        con:Disconnect()
                    end
                end)
                wait(duration)
                if lastfling ~= target then
                    if flingpart then
                        if att1 and (att1.Parent == flingpart) then
                            att1.Parent = flingpart1
                        end
                        flingpart:Destroy()
                    end
                    return
                end
                target = nil
                if not (flingpart and flingpart0 and flingpart1 and att0 and att1) then
                    return
                end
                flingpart0.RotVelocity = v3_0
                att1.Parent = flingpart1
                for i, v in pairs(att0:GetChildren()) do
                    if v:IsA("AlignOrientation") then
                        v.Enabled = true
                    end
                end
                if flingpart then
                    flingpart:Destroy()
                end
            end
        end
    end
end

local lp = game:GetService("Players").LocalPlayer

local c = lp.Character
if not (c and c.Parent) then
	return print("character not found")
end
c:GetPropertyChangedSignal("Parent"):Connect(function()
    if not (c and c.Parent) then
        c = nil
    end
end)

--getPart function

local function gp(parent, name, className)
	local ret = nil
	pcall(function()
		for i, v in pairs(parent:GetChildren()) do
			if (v.Name == name) and v:IsA(className) then
				ret = v
				break
			end
		end
	end)
	return ret
end

--check if reanimate loaded

local model = gp(c, "Model", "Model")
if not model then return print("model not found") end

--find body parts

local head = gp(c, "Head", "BasePart")
if not head then return print("head not found") end

local torso = gp(c, "Torso", "BasePart")
if not torso then return print("torso not found") end

local humanoidRootPart = gp(c, "HumanoidRootPart", "BasePart")
if not humanoidRootPart then return print("humanoid root part not found") end

local leftArm = gp(c, "Left Arm", "BasePart")
if not leftArm then return print("left arm not found") end

local rightArm = gp(c, "Right Arm", "BasePart")
if not rightArm then return print("right arm not found") end

local leftLeg = gp(c, "Left Leg", "BasePart")
if not leftLeg then return print("left leg not found") end

local rightLeg = gp(c, "Right Leg", "BasePart")
if not rightLeg then return print("right leg not found") end

--find rig joints

local neck = gp(torso, "Neck", "Motor6D")
if not neck then return print("neck not found") end

local rootJoint = gp(humanoidRootPart, "RootJoint", "Motor6D")
if not rootJoint then return print("root joint not found") end

local leftShoulder = gp(torso, "Left Shoulder", "Motor6D")
if not leftShoulder then return print("left shoulder not found") end

local rightShoulder = gp(torso, "Right Shoulder", "Motor6D")
if not rightShoulder then return print("right shoulder not found") end

local leftHip = gp(torso, "Left Hip", "Motor6D")
if not leftHip then return print("left hip not found") end

local rightHip = gp(torso, "Right Hip", "Motor6D")
if not rightHip then return print("right hip not found") end

--humanoid

local hum = c:FindFirstChildOfClass("Humanoid")
if not hum then return print("humanoid not found") end

local animate = gp(c, "Animate", "LocalScript")
if animate then
	animate.Disabled = true
end

for i, v in pairs(hum:GetPlayingAnimationTracks()) do
	v:Stop()
end

local fps = 60
local sinechange = 40 / fps
local event = Instance.new("BindableEvent", c)
event.Name = "renderstepped"
local floor = math.floor
fps = 1 / fps
local tf = 0
local con = nil
con = game:GetService("RunService").RenderStepped:Connect(function(s)
	if not c then
		con:Disconnect()
		return
	end
	tf += s
	if tf >= fps then
		for i=1, floor(tf / fps) do
		    tf -= fps
			event:Fire(c)
		end
	end
end)
local event = event.Event

local function stopIfRemoved(instance)
    if not (instance and instance.Parent) then
        c = nil
        return
    end
    instance:GetPropertyChangedSignal("Parent"):Connect(function()
        if not (instance and instance.Parent) then
            c = nil
        end
    end)
end
stopIfRemoved(c)
stopIfRemoved(hum)
for i, v in pairs({head, torso, leftArm, rightArm, leftLeg, rightLeg, humanoidRootPart}) do
    stopIfRemoved(v)
end
for i, v in pairs({neck, rootJoint, leftShoulder, rightShoulder, leftHip, rightHip}) do
    stopIfRemoved(v)
end
if not c then
    return
end
local mode = false
uis = game:GetService("UserInputService")
local modes = {
	[Enum.KeyCode.Q] = "lay",
	[Enum.KeyCode.E] = "sit",
	[Enum.KeyCode.R] = "russia",
	[Enum.KeyCode.T] = "wave",
	[Enum.KeyCode.Y] = "dab",
	[Enum.KeyCode.U] = "dance",
	[Enum.KeyCode.L] = "L",
	[Enum.KeyCode.F] = "fly",
	[Enum.KeyCode.G] = "floss"
}
uis.InputBegan:Connect(function(keycode)
    if uis:GetFocusedTextBox() then
        return
    end
	keycode = keycode.KeyCode
	if modes[keycode] ~= nil then
		if mode == modes[keycode] then
			mode = nil
		else
			mode = modes[keycode]
		end
	end
end)

local cf, v3, euler, sin, sine = CFrame.new, Vector3.new, CFrame.fromEulerAnglesXYZ, math.sin, 0
while event:Wait() do
    sine += sinechange
    local vel = humanoidRootPart.Velocity
    if (vel*v3(1, 0, 1)).Magnitude > 2 then -- walk
        neck.C0 = neck.C0:Lerp(cf(0, 1, 0) * euler(-1.6580627893946132 + -0.17453292519943295 * sin(sine * 0.4), -0.04363323129985824 * sin(sine * 0.2), -3.1590459461097367 + -0.08726646259971647 * sin((sine + -2.5) * 0.2)), 0.2) 
        rootJoint.C0 = rootJoint.C0:Lerp(cf(0, 0.2 + 0.2 * sin(sine * 0.4), 0) * euler(-1.6580627893946132 + 0.08726646259971647 * sin((sine + -1) * 0.4), 0.08726646259971647 * sin(sine * 0.2), -3.1590459461097367 + 0.17453292519943295 * sin((sine + -2.5) * 0.2)), 0.2) 
        leftShoulder.C0 = leftShoulder.C0:Lerp(cf(-1, 0.5, 0) * euler(1.5707963267948966, -1.3962634015954636, 1.2217304763960306 + -0.6981317007977318 * sin((sine + -2.5) * 0.2)), 0.2) 
        rightShoulder.C0 = rightShoulder.C0:Lerp(cf(1, 0.5, 0) * euler(1.5707963267948966, 1.3962634015954636, -1.2217304763960306 + -0.6981317007977318 * sin((sine + -2.5) * 0.2)), 0.2) 
        leftHip.C0 = leftHip.C0:Lerp(cf(-1, -1 + -0.3 * sin((sine + 5) * 0.2), 0) * euler(1.5707963267948966 + -0.8726646259971648 * sin(sine * 0.2), -1.5707963267948966 + 0.08726646259971647 * sin(sine * 0.2), 1.5707963267948966), 0.2) 
        rightHip.C0 = rightHip.C0:Lerp(cf(1, -1 + 0.3 * sin((sine + 5) * 0.2), 0) * euler(1.5707963267948966 + 0.8726646259971648 * sin(sine * 0.2), 1.5707963267948966 + 0.08726646259971647 * sin(sine * 0.2), -1.5707963267948966), 0.2) 
    elseif vel.Y > 2 then -- jump
        neck.C0 = neck.C0:Lerp(cf(0 + 0 * sin((sine + 0) * 0.1), 1 + 0 * sin((sine + 0) * 0.1), 0 + 0 * sin((sine + 0) * 0.1)) * euler(-1.3962634015954636 + 0 * sin((sine + 0) * 0.1), 0 + 0 * sin((sine + 0) * 0.1), -3.1590459461097367 + 0 * sin((sine + 0) * 0.1)), 0.2) 
        rootJoint.C0 = rootJoint.C0:Lerp(cf(0 + 0 * sin((sine + 0) * 0.1), 0 + 0 * sin((sine + 0) * 0.1), 0 + 0 * sin((sine + 0) * 0.1)) * euler(-1.3962634015954636 + 0 * sin((sine + 0) * 0.1), 0 + 0 * sin((sine + 0) * 0.1), -3.141592653589793 + 0 * sin((sine + 0) * 0.1)), 0.2) 
        leftShoulder.C0 = leftShoulder.C0:Lerp(cf(-1 + 0 * sin((sine + 0) * 0.1), 0.5 + 0 * sin((sine + 0) * 0.1), 0 + 0 * sin((sine + 0) * 0.1)) * euler(-0 + 0 * sin((sine + 0) * 0.1), -0.7853981633974483 + 0 * sin((sine + 0) * 0.1), -2.443460952792061 + 0 * sin((sine + 0) * 0.1)), 0.2) 
        rightShoulder.C0 = rightShoulder.C0:Lerp(cf(1 + 0 * sin((sine + 0) * 0.1), 0.5 + 0 * sin((sine + 0) * 0.1), 0 + 0 * sin((sine + 0) * 0.1)) * euler(0 + 0 * sin((sine + 0) * 0.1), 0.7853981633974483 + 0 * sin((sine + 0) * 0.1), 2.443460952792061 + 0 * sin((sine + 0) * 0.1)), 0.2) 
        leftHip.C0 = leftHip.C0:Lerp(cf(-1 + 0 * sin((sine + 0) * 0.1), -1 + 0 * sin((sine + 0) * 0.1), 0 + 0 * sin((sine + 0) * 0.1)) * euler(-0.6981317007977318 + 0 * sin((sine + 0) * 0.1), -1.5882496193148399 + 0 * sin((sine + 0) * 0.1), 0 + 0 * sin((sine + 0) * 0.1)), 0.2) 
        rightHip.C0 = rightHip.C0:Lerp(cf(1 + 0 * sin((sine + 0) * 0.1), -1 + 0 * sin((sine + 0) * 0.1), 0 + 0 * sin((sine + 0) * 0.1)) * euler(0 + 0 * sin((sine + 0) * 0.1), 1.5707963267948966 + 0 * sin((sine + 0) * 0.1), -0.6981317007977318 + 0 * sin((sine + 0) * 0.1)), 0.2)
    elseif vel.Y < -2 then -- fall
        neck.C0 = neck.C0:Lerp(cf(0 + 0 * sin((sine + 0) * 0.1), 1 + 0 * sin((sine + 0) * 0.1), 0 + 0 * sin((sine + 0) * 0.1)) * euler(-1.7453292519943295 + 0 * sin((sine + 0) * 0.1), 0 + 0 * sin((sine + 0) * 0.1), -3.141592653589793 + 0 * sin((sine + 0) * 0.1)), 0.2) 
        rootJoint.C0 = rootJoint.C0:Lerp(cf(0 + 0 * sin((sine + 0) * 0.1), 0 + 0 * sin((sine + 0) * 0.1), 0 + 0 * sin((sine + 0) * 0.1)) * euler(-1.7453292519943295 + 0 * sin((sine + 0) * 0.1), 0 + 0 * sin((sine + 0) * 0.1), -3.141592653589793 + 0 * sin((sine + 0) * 0.1)), 0.2) 
        leftShoulder.C0 = leftShoulder.C0:Lerp(cf(-1 + 0 * sin((sine + 0) * 0.1), 0.5 + 0 * sin((sine + 0) * 0.1), 0 + 0 * sin((sine + 0) * 0.1)) * euler(-0 + 0 * sin((sine + 0) * 0.1), -1.2217304763960306 + 0 * sin((sine + 0) * 0.1), -0.8726646259971648 + 0 * sin((sine + 0) * 0.1)), 0.2) 
        rightShoulder.C0 = rightShoulder.C0:Lerp(cf(1 + 0 * sin((sine + 0) * 0.1), 0.5 + 0 * sin((sine + 0) * 0.1), 0 + 0 * sin((sine + 0) * 0.1)) * euler(0 + 0 * sin((sine + 0) * 0.1), 1.2217304763960306 + 0 * sin((sine + 0) * 0.1), 0.8726646259971648 + 0 * sin((sine + 0) * 0.1)), 0.2) 
        leftHip.C0 = leftHip.C0:Lerp(cf(-1 + 0 * sin((sine + 0) * 0.1), -1 + 0 * sin((sine + 0) * 0.1), 0 + 0 * sin((sine + 0) * 0.1)) * euler(0.5235987755982988 + 0 * sin((sine + 0) * 0.1), -1.5707963267948966 + 0 * sin((sine + 0) * 0.1), 0 + 0 * sin((sine + 0) * 0.1)), 0.2) 
        rightHip.C0 = rightHip.C0:Lerp(cf(1 + 0 * sin((sine + 0) * 0.1), -1 + 0 * sin((sine + 0) * 0.1), 0 + 0 * sin((sine + 0) * 0.1)) * euler(0.5235987755982988 + 0 * sin((sine + 0) * 0.1), 1.5707963267948966 + 0 * sin((sine + 0) * 0.1), 0 + 0 * sin((sine + 0) * 0.1)), 0.2)
    else -- idle
		if not mode then
            neck.C0 = neck.C0:Lerp(cf(0, 1, 0) * euler(-1.5882496193148399 + 0.08726646259971647 * sin((sine + -30) * 0.05), 0, -3.1590459461097367), 0.2) 
            rootJoint.C0 = rootJoint.C0:Lerp(cf(0, 0.1 * sin(sine * 0.05), 0) * euler(-1.5882496193148399 + 0.05235987755982989 * sin(sine * 0.05), 0, -3.1590459461097367), 0.2) 
            leftShoulder.C0 = leftShoulder.C0:Lerp(cf(-0.85, 0.65 + 0.1 * sin((sine + -15) * 0.05), 0.2 + 0.1 * sin(sine * 0.05)) * euler(1.5707963267948966 + 0.08726646259971647 * sin(sine * 0.05), -0.7853981633974483, 1.7453292519943295), 0.2) 
            rightShoulder.C0 = rightShoulder.C0:Lerp(cf(0.85, 0.65 + 0.1 * sin((sine + -15) * 0.05), 0.2 + 0.1 * sin(sine * 0.05)) * euler(1.5707963267948966 + 0.08726646259971647 * sin(sine * 0.05), 0.7853981633974483, -1.7453292519943295), 0.2) 
            leftHip.C0 = leftHip.C0:Lerp(cf(-1, -1 + -0.1 * sin(sine * 0.05), 0.05 * sin(sine * 0.05)) * euler(1.5707963267948966, -1.6580627893946132, 1.5707963267948966 + 0.05235987755982989 * sin(sine * 0.05)), 0.2) 
            rightHip.C0 = rightHip.C0:Lerp(cf(1, -1 + -0.1 * sin(sine * 0.05), 0.05 * sin(sine * 0.05)) * euler(1.5707963267948966, 1.6580627893946132, -1.5707963267948966 + -0.05235987755982989 * sin(sine * 0.05)), 0.2) 
		elseif mode == "russia" then
            neck.C0 = neck.C0:Lerp(cf(0, 1, 0) * euler(-1.6580627893946132 + 0.17453292519943295 * sin((sine + -7.5) * 0.4), 0.08726646259971647 * sin((sine + 7.5) * 0.2), -3.1590459461097367 + 0.17453292519943295 * sin((sine + -2.5) * 0.2)), 0.2) 
            rootJoint.C0 = rootJoint.C0:Lerp(cf(0, 0.1 + 0.2 * sin((sine + -2.5) * 0.4), 0) * euler(-1.4835298641951802 + 0.08726646259971647 * sin(sine * 0.4), -0.08726646259971647 * sin((sine + -5) * 0.2), -3.1590459461097367 + -0.17453292519943295 * sin((sine + -3.5) * 0.2)), 0.2) 
            leftShoulder.C0 = leftShoulder.C0:Lerp(cf(-0.5, 0.2 + 0.05 * sin((sine + 5) * 0.4), 0) * euler(3.141592653589793 + 0.08726646259971647 * sin(sine * 0.4), -0.17453292519943295 + 0.17453292519943295 * sin((sine + -5) * 0.2), 1.5707963267948966 + -0.03490658503988659 * sin((sine + -5) * 0.4)), 0.2) 
            rightShoulder.C0 = rightShoulder.C0:Lerp(cf(0.5, 0.2 + 0.05 * sin((sine + 5) * 0.4), 0) * euler(3.141592653589793 + 0.08726646259971647 * sin(sine * 0.4), 0.17453292519943295 + 0.17453292519943295 * sin((sine + -5) * 0.2), -1.5707963267948966 + 0.03490658503988659 * sin((sine + -5) * 0.4)), 0.2) 
            leftHip.C0 = leftHip.C0:Lerp(cf(-1, -1, 0) * euler(0, -1.5882496193148399, -0.3490658503988659 + 1.0471975511965976 * sin((sine + -5) * 0.2)), 0.2) 
            rightHip.C0 = rightHip.C0:Lerp(cf(1, -1, 0) * euler(0, 1.5707963267948966, 0.3490658503988659 + 1.0471975511965976 * sin((sine + -5) * 0.2)), 0.2) 
		elseif mode == "sit" then
            neck.C0 = neck.C0:Lerp(cf(0, 1.1, -0.1) * euler(-2.007128639793479 + -0.12217304763960307 * sin((sine + -25) * 0.05), 0, -3.1590459461097367), 0.2) 
            rootJoint.C0 = rootJoint.C0:Lerp(cf(0, -1.6 + 0.05 * sin(sine * 0.05), 1 + 0.01 * sin((sine + 15) * 0.05)) * euler(-1.1344640137963142 + 0.08726646259971647 * sin((sine + 15) * 0.05), 0, -3.141592653589793), 0.2) 
            leftShoulder.C0 = leftShoulder.C0:Lerp(cf(-1, 0.2 + -0.05 * sin(sine * 0.05), 0.05 * sin(sine * 0.05)) * euler(-0.6981317007977318 + -0.05235987755982989 * sin((sine + 15) * 0.05), -1.2217304763960306, 0), 0.2) 
            rightShoulder.C0 = rightShoulder.C0:Lerp(cf(1, 0.2 + -0.05 * sin(sine * 0.05), 0.05 * sin(sine * 0.05)) * euler(-0.6981317007977318 + -0.05235987755982989 * sin((sine + 15) * 0.05), 1.2217304763960306, 0), 0.2) 
            leftHip.C0 = leftHip.C0:Lerp(cf(-0.9, -1 + -0.06 * sin((sine + 5) * 0.05), 0.1 * sin(sine * 0.05)) * euler(2.705260340591211 + -0.08726646259971647 * sin((sine + 15) * 0.05), -1.7453292519943295, 1.5707963267948966), 0.2) 
            rightHip.C0 = rightHip.C0:Lerp(cf(0.9, -1 + -0.06 * sin((sine + 5) * 0.05), 0.1 * sin(sine * 0.05)) * euler(2.705260340591211 + -0.08726646259971647 * sin((sine + 15) * 0.05), 1.7453292519943295, -1.5707963267948966), 0.2) 
		elseif mode == "wave" then
            neck.C0 = neck.C0:Lerp(cf(0, 1, 0) * euler(-1.5882496193148399, -0.2617993877991494 * sin((sine + 5) * 0.1), -3.1590459461097367), 0.2) 
            rootJoint.C0 = rootJoint.C0:Lerp(cf(0.2 * sin(sine * 0.1), -0.1, 0) * euler(-1.5882496193148399, 0.17453292519943295 * sin(sine * 0.1), -3.1590459461097367), 0.2) 
            leftShoulder.C0 = leftShoulder.C0:Lerp(cf(-1, 0.5, 0) * euler(1.5707963267948966, -1.7453292519943295 + 0.17453292519943295 * sin((sine + 10) * 0.1), 1.5707963267948966), 0.2) 
            rightShoulder.C0 = rightShoulder.C0:Lerp(cf(1, 1.5, 0) * euler(1.5707963267948966, 1.2217304763960306 + -0.3490658503988659 * sin((sine + -10) * 0.1), 1.5707963267948966), 0.2) 
            leftHip.C0 = leftHip.C0:Lerp(cf(-1 + -0.1 * sin(sine * 0.1), -0.9 + -0.15 * sin(sine * 0.1), 0) * euler(1.5707963267948966, -1.7453292519943295 + 0.20943951023931956 * sin(sine * 0.1), 1.5707963267948966), 0.2) 
            rightHip.C0 = rightHip.C0:Lerp(cf(1 + -0.1 * sin(sine * 0.1), -0.9 + 0.15 * sin(sine * 0.1), 0) * euler(1.5707963267948966, 1.7453292519943295 + 0.20943951023931956 * sin(sine * 0.1), -1.5707963267948966), 0.2) 		
        elseif mode == "lay" then
            neck.C0 = neck.C0:Lerp(cf(0, 1.2, -0.2) * euler(-2.2689280275926285 + 0.08726646259971647 * sin(sine * 0.05), 0, -3.1590459461097367), 0.2) 
            rootJoint.C0 = rootJoint.C0:Lerp(cf(0, -2.4 + 0.1 * sin(sine * 0.05), 0) * euler(0, 0, -3.1590459461097367), 0.2) 
            leftShoulder.C0 = leftShoulder.C0:Lerp(cf(-0.6, 1, 0.1 + 0.1 * sin(sine * 0.05)) * euler(1.5707963267948966, -2.356194490192345 + 0.08726646259971647 * sin(sine * 0.05), -1.5707963267948966), 0.2) 
            rightShoulder.C0 = rightShoulder.C0:Lerp(cf(0.6, 1, 0.1 + 0.1 * sin(sine * 0.05)) * euler(1.5707963267948966, 2.356194490192345 + -0.08726646259971647 * sin(sine * 0.05), 1.5707963267948966), 0.2) 
            leftHip.C0 = leftHip.C0:Lerp(cf(-1, -1, 0) * euler(1.5707963267948966, -1.3089969389957472, 1.6580627893946132 + 0.08726646259971647 * sin(sine * 0.05)), 0.2) 
            rightHip.C0 = rightHip.C0:Lerp(cf(1, -1, 0) * euler(1.5707963267948966, 1.3089969389957472, -1.1344640137963142 + -0.08726646259971647 * sin(sine * 0.05)), 0.2) 
		elseif mode == "dab" then
            neck.C0 = neck.C0:Lerp(cf(0, 1 + -0.1 * sin((sine + 10) * 0.05), 0) * euler(-2.2689280275926285, -0.17453292519943295, 2.356194490192345), 0.2) 
            rootJoint.C0 = rootJoint.C0:Lerp(cf(0, 0.1 * sin(sine * 0.05), 0) * euler(-1.6580627893946132, 0.08726646259971647, -3.2288591161895095), 0.2) 
            leftShoulder.C0 = leftShoulder.C0:Lerp(cf(-1.6, 0.5 + -0.1 * sin((sine + 20) * 0.05), 0) * euler(1.5707963267948966, 2.8797932657906435, 1.5707963267948966), 0.2) 
            rightShoulder.C0 = rightShoulder.C0:Lerp(cf(1, 0.25 + -0.1 * sin((sine + 20) * 0.05), -0.5) * euler(4.1887902047863905, 0.3490658503988659, -1.7453292519943295), 0.2) 
            leftHip.C0 = leftHip.C0:Lerp(cf(-1, -1 + -0.1 * sin((sine + 10) * 0.05), 0) * euler(1.7453292519943295, -1.7453292519943295, 1.5707963267948966), 0.2) 
            rightHip.C0 = rightHip.C0:Lerp(cf(1, -0.85 + -0.1 * sin((sine + 10) * 0.05), 0) * euler(1.5707963267948966, 1.7453292519943295, -1.5707963267948966), 0.2) 
		elseif mode == "dance" then
            neck.C0 = neck.C0:Lerp(cf(0, 1, 0) * euler(-1.5882496193148399 + 0.3490658503988659 * sin((sine + 27.5) * 0.2), -0.17453292519943295 * sin((sine + 10) * 0.1), -3.1590459461097367 + 0.3490658503988659 * sin(sine * 0.1)), 0.2) 
            rootJoint.C0 = rootJoint.C0:Lerp(cf(0, 0, 0) * euler(-1.5882496193148399, 0, -3.1590459461097367 + 0.5235987755982988 * sin(sine * 0.1)), 0.2) 
            leftShoulder.C0 = leftShoulder.C0:Lerp(cf(-1, 0.5, 0) * euler(0, -1.5882496193148399 + 0.5235987755982988 * sin((sine + 5) * 0.1), -1.7453292519943295 + -0.5235987755982988 * sin((sine + 5) * 0.1)), 0.2) 
            rightShoulder.C0 = rightShoulder.C0:Lerp(cf(1, 0.5, 0) * euler(0, 1.5707963267948966 + 0.5235987755982988 * sin((sine + 5) * 0.1), 1.7453292519943295 + -0.5235987755982988 * sin((sine + 5) * 0.1)), 0.2) 
            leftHip.C0 = leftHip.C0:Lerp(cf(-1.05 + 0.05 * sin((sine + 7.5) * 0.2), -1, 0.05 * sin(sine * 0.1)) * euler(0, -1.5882496193148399 + -0.2617993877991494 * sin(sine * 0.1), -0.3490658503988659 * sin(sine * 0.1)), 0.2) 
            rightHip.C0 = rightHip.C0:Lerp(cf(1.05 + -0.05 * sin((sine + 7.5) * 0.2), -1, -0.05 * sin(sine * 0.1)) * euler(0, 1.5707963267948966 + -0.2617993877991494 * sin(sine * 0.1), -0.3490658503988659 * sin(sine * 0.1)), 0.2) 
		elseif mode == "L" then
		    neck.C0 = neck.C0:Lerp(cf(0, 1 + 0.01 * sin(sine * 0.4), 0) * euler(-1.5882496193148399 + -0.08726646259971647 * sin((sine + -10) * 0.4), -0.2617993877991494 * sin(sine * 0.2), -3.1590459461097367), 0.2) 
            rootJoint.C0 = rootJoint.C0:Lerp(cf(0.2 * sin(sine * 0.2), 0.1 + 0.3 * sin(sine * 0.4), 0) * euler(-1.4835298641951802, 0.17453292519943295 * sin(sine * 0.2), -3.141592653589793), 0.2) 
            leftShoulder.C0 = leftShoulder.C0:Lerp(cf(-0.7 + -0.2 * sin(sine * 0.2), 0.5 + -0.1 * sin(sine * 0.2), 0) * euler(1.5707963267948966 + 0.3490658503988659 * sin(sine * 0.2), -1.0471975511965976 + 0.08726646259971647 * sin(sine * 0.2), 1.2217304763960306 + 0.3490658503988659 * sin(sine * 0.2)), 0.2) 
            rightShoulder.C0 = rightShoulder.C0:Lerp(cf(0.9 + -0.1 * sin(sine * 0.2), 0.9 + 0.1 * sin(sine * 0.4), -0.5) * euler(1.2217304763960306 + 0.3490658503988659 * sin((sine + -10) * 0.2), 2.2689280275926285 + 0.08726646259971647 * sin(sine * 0.2), 1.5707963267948966 + -0.3490658503988659 * sin((sine + -10) * 0.2)), 0.2) 
            leftHip.C0 = leftHip.C0:Lerp(cf(-0.9 + 0.2 * sin(sine * 0.2), -0.9, 0) * euler(1.5707963267948966, -2.007128639793479 + 0.4363323129985824 * sin((sine + 15) * 0.2), 1.3089969389957472 + -0.6981317007977318 * sin(sine * 0.2)), 0.2) 
            rightHip.C0 = rightHip.C0:Lerp(cf(0.9 + 0.2 * sin(sine * 0.2), -0.9, 0) * euler(1.5707963267948966, 2.007128639793479 + 0.4363323129985824 * sin((sine + 15) * 0.2), -1.3089969389957472 + -0.6981317007977318 * sin(sine * 0.2)), 0.2) 
		elseif mode == "fly" then
            neck.C0 = neck.C0:Lerp(cf(0, 1, 0) * euler(-1.5882496193148399 + 0.2617993877991494 * sin((sine + -30) * 0.025), 0.17453292519943295 * sin((sine + -10) * 0.05), -3.1590459461097367 + 0.17453292519943295 * sin((sine + 30) * 0.05)), 0.2) 
            rootJoint.C0 = rootJoint.C0:Lerp(cf(1 * sin(sine * 0.05), 5 + 1 * sin(sine * 0.05), 1 * sin(sine * 0.025)) * euler(-1.5882496193148399 + 0.17453292519943295 * sin((sine + -15) * 0.025), 0.17453292519943295 * sin(sine * 0.05), -3.1590459461097367 + 0.3490658503988659 * sin((sine + 15) * 0.05)), 0.2) 
            leftShoulder.C0 = leftShoulder.C0:Lerp(cf(-1, 0.5, 0) * euler(1.5707963267948966 + -0.3490658503988659 * sin((sine + -30) * 0.025), -1.5882496193148399 + 0.3490658503988659 * sin((sine + -10) * 0.05), 1.5707963267948966), 0.2) 
            rightShoulder.C0 = rightShoulder.C0:Lerp(cf(1, 0.5, 0) * euler(1.5707963267948966 + -0.3490658503988659 * sin((sine + -30) * 0.025), 1.5707963267948966 + 0.3490658503988659 * sin((sine + -20) * 0.05), -1.5707963267948966), 0.2) 
            leftHip.C0 = leftHip.C0:Lerp(cf(-1, -1, 0) * euler(1.5707963267948966, -1.5882496193148399 + 0.2617993877991494 * sin((sine + -7) * 0.05), 1.5707963267948966 + 0.3490658503988659 * sin((sine + -10) * 0.025)), 0.2) 
            rightHip.C0 = rightHip.C0:Lerp(cf(1, -1, 0) * euler(1.5707963267948966, 1.5707963267948966 + 0.2617993877991494 * sin((sine + -10) * 0.05), -1.5707963267948966 + -0.3490658503988659 * sin((sine + -5) * 0.025)), 0.2) 
--[[MW_animator progress save: 0, 0, 0, 0.1, -91, 15, -30, 0.025, 1, 0, 0, 0.1, 0, 10, -10, 0.05, 0, 0, 0, 0.1, -181, 10, 30, 0.05, 0, 1, 30, 0.05, -91, 10, -15, 0.025, 5, 1, 0, 0.05, 0, 10, 0, 0.05, 0, 1, 0, 0.025, -181, 20, 15, 0.05, -1, 0, 0, 0.1, 90, -20, -30, 0.025, 0.5, 0, 0, 0.1, -91, 20, -10, 0.05, 0, 0, 0, 0.1, 90, 0, 30, 0, 1, 0, 0, 0.1, 90, -20, -30, 0.025, 0.5, 0, 0, 0.1, 90, 20, -20, 0.05, 0, 0, 0, 0.1, -90, 0, 0, 0.1, -1, 0, 0, 0.1, 90, 0, 0, 0.1, -1, 0, 0, 0.1, -91, 15, -7, 0.05, 0, 0, 0, 0.1, 90, 20, -10, 0.025, 1, 0, 0, 0.1, 90, 0, 0, 0.1, -1, 0, 0, 0.1, 90, 15, -10, 0.05, 0, 0, 0, 0.1, -90, -20, -5, 0.025]]
		elseif mode == "floss" then
            neck.C0 = neck.C0:Lerp(cf(0, 1, 0) * euler(-1.5882496193148399 + 0.08726646259971647 * sin((sine + 3.5) * 0.2), -0.1308996938995747 * sin((sine + 7.5) * 0.1), -3.1590459461097367 + -0.08726646259971647 * sin((sine + 7.5) * 0.1)), 0.2) 
            rootJoint.C0 = rootJoint.C0:Lerp(cf(-0.1 * sin(sine * 0.1), -0.1 * sin(sine * 0.2), 0) * euler(-1.5882496193148399, 0.17453292519943295 * sin((sine + 7.5) * 0.1), -3.1590459461097367 + 0.17453292519943295 * sin((sine + 7.5) * 0.1)), 0.2) 
            leftShoulder.C0 = leftShoulder.C0:Lerp(cf(-1, 0.5, -0.2) * euler(1.9198621771937625, -1.5707963267948966 + -0.3490658503988659 * sin((sine + 7.5) * 0.1), 1.7453292519943295 + 0.17453292519943295 * sin((sine + 15) * 0.1)), 0.2) 
            rightShoulder.C0 = rightShoulder.C0:Lerp(cf(1, 0.5, -0.2) * euler(-1.7453292519943295, 1.5707963267948966 + 0.3490658503988659 * sin((sine + 7.5) * 0.1), 1.9198621771937625 + 0.17453292519943295 * sin((sine + 15) * 0.1)), 0.2) 
            leftHip.C0 = leftHip.C0:Lerp(cf(-1, -1 + -0.2 * sin((sine + 7.5) * 0.1), 0) * euler(1.5707963267948966 + 0.08726646259971647 * sin((sine + 7.5) * 0.1), -1.7453292519943295 + 0.3490658503988659 * sin((sine + 7.5) * 0.1), 1.5707963267948966), 0.2) 
            rightHip.C0 = rightHip.C0:Lerp(cf(1, -1 + 0.2 * sin((sine + 7.5) * 0.1), 0) * euler(1.5707963267948966 + -0.08726646259971647 * sin((sine + 7.5) * 0.1), 1.7453292519943295 + 0.3490658503988659 * sin((sine + 7.5) * 0.1), -1.5707963267948966), 0.2) 
        end
    end
end
print"ORPLAYZ SCRIPT LOADED"
end)


MainSection:NewButton("mizt hub V2", "is it good ...", function()  
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Sylixe/MiztHub/master/MainFolder/uqXAxyVdQpWTcRCdFXU6Yt2meuDkYcLUDN4SJRekQWZ5wp368zKHreYT4w82AH4U.lua",true))()
end)


MainSection:NewButton("dynamo script hub", "its good", function()  
loadstring(game:HttpGet("https://raw.githubusercontent.com/yt-flix/dynamo/main/nooob", true))()
end)


MainSection:NewButton("fe reality hub v2", "its good its op", function()
    --[[

~HATS NEEDED~

(These are needed for every script except "Hat Tornado", "Moon Man", And "Kitchen Gun")

1.  https://www.roblox.com/catalog/1309911 [12 ROBUXS]
2.  https://www.roblox.com/catalog/13207429 [25 ROBUXS]
3.  https://www.roblox.com/catalog/62234425 [0 ROBUXS]
4.  https://www.roblox.com/catalog/62724852 [0 ROBUXS]
5.  https://www.roblox.com/catalog/63690008 [0 ROBUXS]
6.  https://www.roblox.com/catalog/451220849 [0 ROBUXS]

~ Hat Torndado Hats ~

wear what ever hats u want it will work

~ Kitchen Gun ~

1.  https://www.roblox.com/catalog/1309911 [12 ROBUXS]
2.  https://www.roblox.com/catalog/13207429 [25 ROBUXS]
3.  https://www.roblox.com/catalog/62234425 [0 ROBUXS]
4.  https://www.roblox.com/catalog/62724852 [0 ROBUXS]
5.  https://www.roblox.com/catalog/63690008 [0 ROBUXS]
6.  https://www.roblox.com/catalog/451220849 [0 ROBUXS]
7. https://www.roblox.com/catalog/5100070995 [100 ROBUXS]

~ Moon Man ~

1.  https://www.roblox.com/catalog/5461578341 [50 ROBUXS]
2.  https://www.roblox.com/catalog/13207429 [25 ROBUXS]
3.  https://www.roblox.com/catalog/62234425 [0 ROBUXS]
4.  https://www.roblox.com/catalog/62724852 [0 ROBUXS]
5.  https://www.roblox.com/catalog/63690008 [0 ROBUXS]
6.  https://www.roblox.com/catalog/451220849 [0 ROBUXS]

]]--

loadstring(game:HttpGet("https://raw.githubusercontent.com/Plebby12/RH2/main/poop.txt", true))()
end)


MainSection:NewButton("search bar script", "its op trust me", function()
    print("Clicked")
end)
