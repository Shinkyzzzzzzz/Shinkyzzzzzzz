-- skate if you cracked this lego script ur infos are leaked on doxbin

local Library = loadstring(game:HttpGet("https://github.com/dawid-scripts/Fluent/releases/latest/download/main.lua"))()
local SaveManager = loadstring(game:HttpGet("https://raw.githubusercontent.com/dawid-scripts/Fluent/master/Addons/SaveManager.lua"))()
local InterfaceManager = loadstring(game:HttpGet("https://raw.githubusercontent.com/dawid-scripts/Fluent/master/Addons/InterfaceManager.lua"))()

local Window = Library:CreateWindow({
  Title = "Shinky hub",
  TabWidth = 160,
  Size = UDim2.fromOffset(580, 460),
  Acrylic = false, -- The blur may be detectable, setting this to false disables blur entirely
  Theme = "White",
  MinimizeKey = Enum.KeyCode.LeftControl -- Used when theres no MinimizeKeybind
})

local Tabs = {
  Important = Window:AddTab({ Title = "Important", Icon = "shield-check" }),
  Reach = Window:AddTab({ Title = "Reach", Icon = "dice-1" }),
  ImprovedReact = Window:AddTab({ Title = "Improved React", Icon = "focus" }),
  Gamepasses = Window:AddTab({ Title = "Gamepasses", Icon = "tag" }),
  Other = Window:AddTab({ Title = "Other", Icon = "at-sign" }),
  More = Window:AddTab({ Title = "More", Icon = "bell-ring" }),
  Misc = Window:AddTab({ Title = "Misc", Icon = "gamepad-2" }),
  Skys = Window:AddTab({ Title = "Skys", Icon = "umbrella" }),
  AutoStuff = Window:AddTab({ Title = "Auto Stuff", Icon = "sword" }),
  Scripts = Window:AddTab({ Title = "Scripts", Icon = "banana" }),
  Settings = Window:AddTab({ Title = "Settings", Icon = "settings" }),
}

Window:SelectTab(1)
local Options = Library.Options


Tabs.Important:AddParagraph({
  Title = "Read!!",
  Content = "Q"
})

    
    
Tabs.Important:AddParagraph({
  Title = "Credits",
  Content = "Shinky Hub Is Best???"
})


Tabs.Important:AddParagraph({
  Title = "Shink",
  Content = "Shinky 49 Hours for Finaly Script"
})


Tabs.Important:AddParagraph({
  Title = "Script",
  Content = "did you know that this script took 400 hours just to be directly designed for Tps Street Soccer."
})

Tabs.Important:AddParagraph({
  Title = "Bugs",
  Content = "Bugs Can Be Reported Via Discord Server."
})

Tabs.Important:AddParagraph({
  Title = "Fixes And Updates",
  Content = "Fixes and Updates can Be viewed via discord aswell, join up!"
})

    
    

Tabs.Important:AddButton({
  Title = "Copy Discord Server Link",
  Callback = function()
      Library:Notify({
          Title = "Copied",
          Content = "Copied the discord server link!",
          Duration = 5 
      })
  
      setclipboard("https://discord.gg/mSmeUQnT")
  end
})


-- Bu alttaki kisim
Tabs.Reach:AddButton({
  Title = "Reach GUI",
  Callback = function()
            getgenv().Kitten = 5
loadstring(game:HttpGet("https://pastebin.com/raw/EdDK6iWA",true))()
    end    
})

Tabs.Reach:AddButton({
  Title = "best reach use it GUI",
  Callback = function()
            getgenv().Kitten = 5
loadstring(game:HttpGet("https://raw.githubusercontent.com/Zkkekjdjosjdodsjwoekdkskdksksuxisjeufu/Cuaaguaokchafhoochepxiyggu933yg9du9gd9gu399uudx/main/Kekekkdjepsjxodjodidodi",true))()
    end    
})

Tabs.Reach:AddButton({
  Title = "Tps Infinite Soccer GUI",
  Callback = function()
            getgenv().Kitten = 5
loadstring(game:HttpGet("https://pastebin.com/raw/NnSYvFAa",true))()
    end    
})
    
Tabs.Reach:AddButton({
Title = "Revamped TPS UI (by strandedlukas)",
Callback = function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/strandedlukas/Revamped-Ui-Tps/main/Strandedlukas"))();
  end
})

Tabs.Reach:AddButton({
  Title = "Tps Ultimate GUI (wont work without whitelist)",
  Callback = function()
      Library:Notify({
          Title = "Executed",
          Content = "Executed! enjoy",
          Duration = 5 
      })
      loadstring(game:HttpGet("https://raw.githubusercontent.com/strandedlukas/TPS-ultimate-GUI/main/Protected_6075143873069690.lua.txt"))();
  end
})

Tabs.Reach:AddButton({
  Title = "Mps Gui",
  Callback = function()
      Library:Notify({
          Title = "Executed",
          Content = "executed!",
          Duration = 5 
      })
      loadstring(game:HttpGet("https://raw.githubusercontent.com/strandedlukas/Mpsgui/main/77_YD7RX2EYFRRQDA.lua"))();
  end
})


Tabs.ImprovedReact:AddButton({
  Title = "Best React",
  Callback = function()
            getgenv().Kitten = 5
RunStepped = game:GetService("RunService").RenderStepped:Connect(function()
              if game.Players.LocalPlayer.Character.Humanoid.RigType == Enum.HumanoidRigType.R6 then
                  if (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - game.Workspace.TPSSystem.TPS.Position).Magnitude <= DistanceReach then
                      if game.Lighting[game.Players.LocalPlayer.Name].PreferredFoot.Value == 1 then
                          firetouchinterest(game.Players.LocalPlayer.Character["Right Leg"], game.Workspace.TPSSystem.TPS, 0)
                          firetouchinterest(game.Players.LocalPlayer.Character["Right Leg"], game.Workspace.TPSSystem.TPS, 1)
                      elseif game.Lighting[game.Players.LocalPlayer.Name].PreferredFoot.Value == 2 then
                          firetouchinterest(game.Players.LocalPlayer.Character["Left Leg"], game.Workspace.TPSSystem.TPS, 0)
                          firetouchinterest(game.Players.LocalPlayer.Character["Left Leg"], game.Workspace.TPSSystem.TPS, 1)
                      end
                  end
              end
              if game.Players.LocalPlayer.Character.Humanoid.RigType == Enum.HumanoidRigType.R15 then
                  if (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - game.Workspace.TPSSystem.TPS.Position).Magnitude <= DistanceReach then
                      if game.Lighting[game.Players.LocalPlayer.Name].PreferredFoot.Value == 1 then
                          firetouchinterest(game.Players.LocalPlayer.Character["RightLowerLeg"], game.Workspace.TPSSystem.TPS, 0)
                          firetouchinterest(game.Players.LocalPlayer.Character["RightLowerLeg"], game.Workspace.TPSSystem.TPS, 1)
                      elseif game.Lighting[game.Players.LocalPlayer.Name].PreferredFoot.Value == 2 then
                          firetouchinterest(game.Players.LocalPlayer.Character["LeftLowerLeg"], game.Workspace.TPSSystem.TPS, 0)
                          firetouchinterest(game.Players.LocalPlayer.Character["LeftLowerLeg"], game.Workspace.TPSSystem.TPS, 1)
                      end
                  end
              end
          end)
    
          RunStepped:Disconnect()
      end
})

Tabs.ImprovedReact:AddButton({
Title = "Right Foot",
Callback = function()

                    _G.BallName = "TPS"
_G.Magnitude = 3.8
_G.Enabled = true


-- DONT TOUCH ANYTHING BELOW THIS

_G.Path = nil

local player = game.Players.LocalPlayer
local mouse = player:GetMouse()

local leg = game.Players.LocalPlayer.Character["Right Leg"]
local left = game.Players.LocalPlayer.Character["Left Arm"]
local arm = game.Players.LocalPlayer.Character["Right Arm"]
local torso = game.Players.LocalPlayer.Character.Torso


local player = game.Players.LocalPlayer
local mouse = player:GetMouse()
mouse.KeyDown:connect(function()
                           if _G.Path == nil then
  if _G.Enabled == true then
for i, balls in pairs(game.Workspace:GetDescendants()) do
                      if balls.Name == _G.BallName then
                              _G.Path = balls.Parent
                      if (balls.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude <= _G.Magnitude then
firetouchinterest(arm, balls, 0)
firetouchinterest(torso, balls, 0)
firetouchinterest(left, balls, 0)
firetouchinterest(leg, balls, 0)
firetouchinterest(head, balls, 0)
wait()
firetouchinterest(arm, balls, 1)
firetouchinterest(torso, balls, 1)
firetouchinterest(left, balls, 1)
firetouchinterest(leg, balls, 1)
end
end
end
end
elseif _G.Path ~= nil then
      if _G.Enabled == true then
  for i, balls2 in pairs(_G.Path:GetChildren()) do
                        if balls2.Name == _G.BallName then
                                            if (balls2.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude <= _G.Magnitude then
firetouchinterest(arm, balls2, 0)
firetouchinterest(torso, balls2, 0)
firetouchinterest(left, balls2, 0)
firetouchinterest(leg, balls2, 0)
wait()
firetouchinterest(arm, balls2, 1)
firetouchinterest(torso, balls2, 1)
firetouchinterest(left, balls2, 1)
firetouchinterest(leg, balls2, 1)
             end
          end
      end
      end
end
end)

local player = game.Players.LocalPlayer
local mouse = player:GetMouse()
          mouse.Button1Down:Connect(function()
                           if _G.Path == nil then
  if _G.Enabled == true then
for i, balls in pairs(game.Workspace:GetDescendants()) do
                      if balls.Name == _G.BallName then
                              _G.Path = balls.Parent
                      if (balls.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude <= _G.Magnitude then
firetouchinterest(arm, balls, 0)
firetouchinterest(torso, balls, 0)
firetouchinterest(left, balls, 0)
firetouchinterest(leg, balls, 0)
wait()
firetouchinterest(arm, balls, 1)
firetouchinterest(torso, balls, 1)
firetouchinterest(left, balls, 1)
firetouchinterest(leg, balls, 1)
end
end
end
end
elseif _G.Path ~= nil then
      if _G.Enabled == true then
  for i, balls2 in pairs(_G.Path:GetChildren()) do
                        if balls2.Name == _G.BallName then
                                            if (balls2.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude <= _G.Magnitude then
firetouchinterest(arm, balls2, 0)
firetouchinterest(torso, balls2, 0)
firetouchinterest(left, balls2, 0)
firetouchinterest(leg, balls2, 0)
wait()
firetouchinterest(arm, balls2, 1)
firetouchinterest(torso, balls2, 1)
firetouchinterest(left, balls2, 1)
firetouchinterest(leg, balls2, 1)
             end
          end
      end
      end
end
end)	
  end    
})

Tabs.ImprovedReact:AddButton({
Title = "Left Foot",
Callback = function()

                      _G.BallName = "TPS"
_G.Magnitude = 4
_G.Enabled = true


-- DONT TOUCH ANYTHING BELOW THIS

_G.Path = nil

local player = game.Players.LocalPlayer
local mouse = player:GetMouse()

local leg = game.Players.LocalPlayer.Character["Left Leg"]
local left = game.Players.LocalPlayer.Character["Left Arm"]
local arm = game.Players.LocalPlayer.Character["Right Arm"]
local torso = game.Players.LocalPlayer.Character.Torso


local player = game.Players.LocalPlayer
local mouse = player:GetMouse()
mouse.KeyDown:connect(function()
                           if _G.Path == nil then
  if _G.Enabled == true then
for i, balls in pairs(game.Workspace:GetDescendants()) do
                      if balls.Name == _G.BallName then
                              _G.Path = balls.Parent
                      if (balls.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude <= _G.Magnitude then
firetouchinterest(arm, balls, 0)
firetouchinterest(torso, balls, 0)
firetouchinterest(left, balls, 0)
firetouchinterest(leg, balls, 0)
firetouchinterest(head, balls, 0)
wait()
firetouchinterest(arm, balls, 1)
firetouchinterest(torso, balls, 1)
firetouchinterest(left, balls, 1)
firetouchinterest(leg, balls, 1)
end
end
end
end
elseif _G.Path ~= nil then
      if _G.Enabled == true then
  for i, balls2 in pairs(_G.Path:GetChildren()) do
                        if balls2.Name == _G.BallName then
                                            if (balls2.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude <= _G.Magnitude then
firetouchinterest(arm, balls2, 0)
firetouchinterest(torso, balls2, 0)
firetouchinterest(left, balls2, 0)
firetouchinterest(leg, balls2, 0)
wait()
firetouchinterest(arm, balls2, 1)
firetouchinterest(torso, balls2, 1)
firetouchinterest(left, balls2, 1)
firetouchinterest(leg, balls2, 1)
             end
          end
      end
      end
end
end)

local player = game.Players.LocalPlayer
local mouse = player:GetMouse()
          mouse.Button1Down:Connect(function()
                           if _G.Path == nil then
  if _G.Enabled == true then
for i, balls in pairs(game.Workspace:GetDescendants()) do
                      if balls.Name == _G.BallName then
                              _G.Path = balls.Parent
                      if (balls.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude <= _G.Magnitude then
firetouchinterest(arm, balls, 0)
firetouchinterest(torso, balls, 0)
firetouchinterest(left, balls, 0)
firetouchinterest(leg, balls, 0)
wait()
firetouchinterest(arm, balls, 1)
firetouchinterest(torso, balls, 1)
firetouchinterest(left, balls, 1)
firetouchinterest(leg, balls, 1)
end
end
end
end
elseif _G.Path ~= nil then
      if _G.Enabled == true then
  for i, balls2 in pairs(_G.Path:GetChildren()) do
                        if balls2.Name == _G.BallName then
                                            if (balls2.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude <= _G.Magnitude then
firetouchinterest(arm, balls2, 0)
firetouchinterest(torso, balls2, 0)
firetouchinterest(left, balls2, 0)
firetouchinterest(leg, balls2, 0)
wait()
firetouchinterest(arm, balls2, 1)
firetouchinterest(torso, balls2, 1)
firetouchinterest(left, balls2, 1)
firetouchinterest(leg, balls2, 1)
             end
          end
      end
      end
end
end)
  end    
})


Tabs.Gamepasses:AddButton({
Title = "Unlock All Celebrations",
Callback = function()
  game:GetService("Players").LocalPlayer.PlayerGui.Start.GamePassMenu.Items.CelebrationPack1.Tick.Visible = true
  game:GetService("Players").LocalPlayer.PlayerGui.Start.GamePassMenu.Items.CelebrationPack1.CelebrationPack1.Style = "RobloxRoundButton"
      game:GetService("Players").LocalPlayer.PlayerGui.Start.GamePassMenu.Items.CelebrationPack2.Tick.Visible = true
  game:GetService("Players").LocalPlayer.PlayerGui.Start.GamePassMenu.Items.CelebrationPack2.CelebrationPack2.Style = "RobloxRoundButton"
      game:GetService("Players").LocalPlayer.PlayerGui.Start.GamePassMenu.Items.CelebrationPack3.Tick.Visible = true
  game:GetService("Players").LocalPlayer.PlayerGui.Start.GamePassMenu.Items.CelebrationPack3.CelebrationPack3.Style = "RobloxRoundButton"
      game:GetService("Players").LocalPlayer.PlayerGui.Start.GamePassMenu.Items.CelebrationPack4.Tick.Visible = true
  game:GetService("Players").LocalPlayer.PlayerGui.Start.GamePassMenu.Items.CelebrationPack4.CelebrationPack4.Style = "RobloxRoundButton"
      game:GetService("Players").LocalPlayer.PlayerGui.Start.GamePassMenu.Items.CelebrationPack5.Tick.Visible = true
  game:GetService("Players").LocalPlayer.PlayerGui.Start.GamePassMenu.Items.CelebrationPack5.CelebrationPack5.Style = "RobloxRoundButton"
              game:GetService("Players").LocalPlayer.PlayerGui.Start.GamePassMenu.Items.CelebrationPack6.Tick.Visible = true
  game:GetService("Players").LocalPlayer.PlayerGui.Start.GamePassMenu.Items.CelebrationPack6.CelebrationPack6.Style = "RobloxRoundButton"

  game:GetService("Players").LocalPlayer.PlayerGui.Start.GamePassMenu.Items.CelebrationPack7.Tick.Visible = true
  game:GetService("Players").LocalPlayer.PlayerGui.Start.GamePassMenu.Items.CelebrationPack7.CelebrationPack7.Style = "RobloxRoundButton"
  
  game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.Package1.Button.Visible = false
game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.Package2.Button.Visible = false
game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.Package3.Button.Visible = false
game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.Package4.Button.Visible = false
game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.Package5.Button.Visible = false
game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.Package6.Button.Visible = false
game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.Package7.Button.Visible = false

  game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF04.Active = true
 game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF04.Selectable = true
  game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF04.Script.Disabled = false
  game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF05.Active = true
  game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF05.Selectable = true
  game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF05.Script.Disabled = false
 game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF06.Active = true
  game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF06.Selectable = true
  game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF06.Script.Disabled = false
  game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF05.Script.Disabled = false
 game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF06.Active = true

game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF07.Active = true
 game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF07.Selectable = true
  game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF07.Script.Disabled = false
  game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF08.Active = true
  game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF08.Selectable = true
  game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF08.Script.Disabled = false
 game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF09.Active = true
  game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF09.Selectable = true
  game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF09.Script.Disabled = false

game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF10.Active = true
 game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF10.Selectable = true
  game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF10.Script.Disabled = false
  game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF11.Active = true
  game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF11.Selectable = true
  game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF11.Script.Disabled = false
 game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF12.Active = true
  game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF12.Selectable = true
  game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF12.Script.Disabled = false

game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF13.Active = true
 game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF13.Selectable = true
  game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF13.Script.Disabled = false
  game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF14.Active = true
  game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF14.Selectable = true
  game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF14.Script.Disabled = false
 game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF15.Active = true
  game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF15.Selectable = true
  game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF15.Script.Disabled = false

game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF16.Active = true
 game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF16.Selectable = true
  game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF16.Script.Disabled = false
  game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF17.Active = true
  game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF17.Selectable = true
  game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF17.Script.Disabled = false
 game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF18.Active = true
  game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF18.Selectable = true
  game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF18.Script.Disabled = false
  game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF19.Active = true
  game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF19.Selectable = true
  game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF19.Script.Disabled = false
  game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF20.Active = true
  game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF20.Selectable = true
  game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF20.Script.Disabled = false
  game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF21.Active = true
  game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF21.Selectable = true
  game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF21.Script.Disabled = false
  game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF22.Active = true
  game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF22.Selectable = true
  game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF22.Script.Disabled = false
  game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF23.Active = true
  game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF23.Selectable = true
  game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF23.Script.Disabled = false
  game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF24.Active = true
  game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF24.Selectable = true
  game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF24.Script.Disabled = false
  
  
  game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF04.MouseButton1Click:Connect(function()
  require(game.Players.LocalPlayer.Backpack.CelebrationsModule).Celebration4()
end)

game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF05.MouseButton1Click:Connect(function()
  require(game.Players.LocalPlayer.Backpack.CelebrationsModule).Celebration5()
end)

game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF06.MouseButton1Click:Connect(function()
  require(game.Players.LocalPlayer.Backpack.CelebrationsModule).Celebration6()
end)


game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF07.MouseButton1Click:Connect(function()
  require(game.Players.LocalPlayer.Backpack.CelebrationsModule).Celebration7()
end)


game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF08.MouseButton1Click:Connect(function()
  require(game.Players.LocalPlayer.Backpack.CelebrationsModule).Celebration8()
end)


game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF09.MouseButton1Click:Connect(function()
  require(game.Players.LocalPlayer.Backpack.CelebrationsModule).Celebration9()
end)


game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF10.MouseButton1Click:Connect(function()
  require(game.Players.LocalPlayer.Backpack.CelebrationsModule).Celebration10()
end)


game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF11.MouseButton1Click:Connect(function()
  require(game.Players.LocalPlayer.Backpack.CelebrationsModule).Celebration11()
end)


game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF12.MouseButton1Click:Connect(function()
  require(game.Players.LocalPlayer.Backpack.CelebrationsModule).Celebration12()
end)


game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF13.MouseButton1Click:Connect(function()
  require(game.Players.LocalPlayer.Backpack.CelebrationsModule).Celebration13()
end)


game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF14.MouseButton1Click:Connect(function()
  require(game.Players.LocalPlayer.Backpack.CelebrationsModule).Celebration14()
end)


game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF15.MouseButton1Click:Connect(function()
  require(game.Players.LocalPlayer.Backpack.CelebrationsModule).Celebration15()
end)


game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF16.MouseButton1Click:Connect(function()
  require(game.Players.LocalPlayer.Backpack.CelebrationsModule).Celebration16()
end)


game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF17.MouseButton1Click:Connect(function()
  require(game.Players.LocalPlayer.Backpack.CelebrationsModule).Celebration17()
end)


game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF18.MouseButton1Click:Connect(function()
  require(game.Players.LocalPlayer.Backpack.CelebrationsModule).Celebration18()
end)
game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF19.MouseButton1Click:Connect(function()
  require(game.Players.LocalPlayer.Backpack.CelebrationsModule).Celebration19()
end)

game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF20.MouseButton1Click:Connect(function()
  require(game.Players.LocalPlayer.Backpack.CelebrationsModule).Celebration20()
end)

game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF21.MouseButton1Click:Connect(function()
  require(game.Players.LocalPlayer.Backpack.CelebrationsModule).Celebration21()
end)

game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF22.MouseButton1Click:Connect(function()
  require(game.Players.LocalPlayer.Backpack.CelebrationsModule).Celebration22()
end)

game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF23.MouseButton1Click:Connect(function()
  require(game.Players.LocalPlayer.Backpack.CelebrationsModule).Celebration23()
end)

game:GetService("Players").LocalPlayer.PlayerGui.Start.Celebrations.CelebrationsSelect.SF24.MouseButton1Click:Connect(function()
  require(game.Players.LocalPlayer.Backpack.CelebrationsModule).Celebration24()
end)
    end
})

local MoreCurve = Tabs.Gamepasses:AddToggle("MoreCurve", {Title = "More Curve", Default = false })

MoreCurve:OnChanged(function()
  local Value = Options.MoreCurve.Value
  if Value then
      game:GetService("Players").LocalPlayer.PlayerGui.Start.GamePassMenu.Items.WoodenFloor.Tick.Visible = true
      game:GetService("Players").LocalPlayer.PlayerGui.Start.GamePassMenu.Items.WoodenFloor.WoodenFloor.Style = "RobloxRoundButton"

      local Humanoid = game.Players.LocalPlayer.Character.Humanoid

      local AnimationCurveLoop
      AnimationCurveLoop = Humanoid.AnimationPlayed:Connect(function(AnimationTrack)
          local trackNames = {
              "OldMKickL", "OldMKick", "OldLKickL", "OldLKick", "MKickL",
              "MKick", "LKickL", "LKick", "OldDribbleL", "OldDribble",
              "DribbleL", "Dribble"
          }
          if table.find(trackNames, AnimationTrack.Name) then
              if (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - game.Workspace.TPSSystem.TPS.Position).Magnitude < 3.45 then
                  if game.Players.LocalPlayer.Backpack.Curving.Value == 2 then
                      wait(0.1)
                      local A_1T = game:GetService("Workspace").TPSSystem.TPS
                      local A_2T = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart
                      local EventT = game:GetService("Workspace").FE.Actions.KickC1
                      EventT:FireServer(A_1T, A_2T)
                      wait(0.2)
                      EventT:FireServer(A_1T, A_2T)
                  elseif game.Players.LocalPlayer.Backpack.Curving.Value == 1 then
                      wait(0.1)
                      local A_1 = game:GetService("Workspace").TPSSystem.TPS
                      local A_2 = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart
                      local Event = game:GetService("Workspace").FE.Actions.KickC2
                      Event:FireServer(A_1, A_2)
                      wait(0.2)
                      Event:FireServer(A_1, A_2)
                  end
              end
          end
      end)
  else

  end
end)


local FasterCooldown = Tabs.Gamepasses:AddToggle("FasterCooldown", {Title = "Faster Cooldown", Default = false })

FasterCooldown:OnChanged(function()
  local Value = Options.FasterCooldown.Value
  if Value then
      game:GetService("Players").LocalPlayer.PlayerGui.Start.GamePassMenu.Items.Cooldown.Tick.Visible = true
      game:GetService("Players").LocalPlayer.PlayerGui.Start.GamePassMenu.Items.Cooldown.Cooldown.Style = "RobloxRoundButton"
      game:GetService("Players").LocalPlayer.PlayerGui.Start.PowerShot.PowerValue.Value = 30
  else
      game:GetService("Players").LocalPlayer.PlayerGui.Start.GamePassMenu.Items.Cooldown.Cooldown.Style = "RobloxRoundDefaultButton"
      game:GetService("Players").LocalPlayer.PlayerGui.Start.GamePassMenu.Items.Cooldown.Tick.Visible = false
      game:GetService("Players").LocalPlayer.PlayerGui.Start.PowerShot.PowerValue.Value = 60
  end
end)


local PowerfulTackle = Tabs.Gamepasses:AddToggle("PowerfulTackle", {Title = "Powerful Tackle", Default = false })

PowerfulTackle:OnChanged(function()
  local Value = Options.PowerfulTackle.Value
  if Value then
      game:GetService("Players").LocalPlayer.PlayerGui.Start.GamePassMenu.Items.RandomWeather.Tick.Visible = true
          game:GetService("Players").LocalPlayer.PlayerGui.Start.GamePassMenu.Items.RandomWeather.RandomWeather.Style = "RobloxRoundButton"
              game:GetService("Players").LocalPlayer.Backpack.TackleGamePass.Value = true
              
              local Humanoid = game.Players.LocalPlayer.Character.Humanoid
      
      AnimationTackleLoop = Humanoid.AnimationPlayed:Connect(function(AnimationTrack)
          if AnimationTrack.Name == "TackleL" or AnimationTrack.Name == "Tackle" or AnimationTrack.Name == "OldTackleL" or AnimationTrack.Name == "OldTackle" then
          if (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - game.Workspace.TPSSystem.TPS.Position).Magnitude < 4.87 then
              wait(0.8)
                      local A_1 = game:GetService("Workspace").TPSSystem.TPS
      local A_2 = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart
      local A_3 = 30
      local A_4 = Vector3.new(4000000, 700, 4000000)
      local Event = game:GetService("Workspace").FE.Actions.KickG1
      Event:FireServer(A_1, A_2, A_3, A_4)
      
              end
          end
      end)
         
            game:GetService("Players").LocalPlayer.PlayerGui.Start.GamePassMenu.Items.RandomWeather.Tick.Visible = false
          game:GetService("Players").LocalPlayer.PlayerGui.Start.GamePassMenu.Items.RandomWeather.RandomWeather.Style = "RobloxRoundDefaultButton"
          game:GetService("Players").LocalPlayer.Backpack.TackleGamePass.Value = false
          AnimationTackleLoop:Disconnect()
          end
end)


local BlueFlame = Tabs.Gamepasses:AddToggle("BlueFlame", {Title = "Blue Flame", Default = false })

BlueFlame:OnChanged(function()
  local Value = Options.BlueFlame.Value
  if Value then
      game:GetService("Players").LocalPlayer.PlayerGui.Start.GamePassMenu.Items.BlueFlame.Tick.Visible = true
      game:GetService("Players").LocalPlayer.PlayerGui.Start.GamePassMenu.Items.BlueFlame.BlueFlame.Style = "RobloxRoundButton"
      game:GetService("Players").LocalPlayer.PlayerGui.Start.PowerShot.Image = "rbxassetid://5366457711"
      game:GetService("Players").LocalPlayer.Backpack.FValue.Value = 2
  else
      game:GetService("Players").LocalPlayer.PlayerGui.Start.GamePassMenu.Items.BlueFlame.Tick.Visible = false
      game:GetService("Players").LocalPlayer.PlayerGui.Start.GamePassMenu.Items.BlueFlame.BlueFlame.Style = "RobloxRoundDefaultButton"
      game:GetService("Players").LocalPlayer.PlayerGui.Start.PowerShot.Image = "rbxassetid://1595877615"
      game:GetService("Players").LocalPlayer.Backpack.FValue.Value = 1
  end
end)



local FrozenBall = Tabs.Gamepasses:AddToggle("FrozenBall", {Title = "Frozen Ball", Default = false })

FrozenBall:OnChanged(function()
  local Value = Options.FrozenBall.Value
  if Value then
      game:GetService("Players").LocalPlayer.PlayerGui.Start.GamePassMenu.Items.Frozen.Tick.Visible = true
          game:GetService("Players").LocalPlayer.PlayerGui.Start.GamePassMenu.Items.Frozen.Frozen.Style = "RobloxRoundButton"
          
      _G.FROZEN = true
          while _G.FROZEN do
          wait()
              game:GetService("Players").LocalPlayer.Backpack.FrozenGamePass.Value = true
              for i,v in pairs(game.Workspace:GetDescendants()) do
          if v.Name == "TPS" and v:IsA("Part") then
          if (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - v.Position).Magnitude <= 5 then
          if v.Fire.Enabled == true or v.FireB.Enabled == true then
             v.BrickColor = BrickColor.new("Cyan")
             local A_1 = game:GetService("Workspace").TPSSystem.TPS
      local A_2 = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart
      local A_3 = 0
      local A_4 = Vector3.new(4000000, 300, 4000000)
      local Event = game:GetService("Workspace").FE.Actions.KickG1
      Event:FireServer(A_1, A_2, A_3, A_4)
      wait(.1)
      local A_1 = game:GetService("Workspace").TPSSystem.TPS
      local A_2 = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart
      local A_3 = 0
      local A_4 = Vector3.new(4000000, 300, 4000000)
      local Event = game:GetService("Workspace").FE.Actions.KickG1
      Event:FireServer(A_1, A_2, A_3, A_4)
      wait(2.4)
      v.BrickColor = BrickColor.new("Institutional white")
          end
          end
          end
          end
          end
          game:GetService("Players").LocalPlayer.Backpack.FrozenGamePass.Value = false
          _G.FROZEN = false
           game:GetService("Players").LocalPlayer.PlayerGui.Start.GamePassMenu.Items.Frozen.Tick.Visible = false
          game:GetService("Players").LocalPlayer.PlayerGui.Start.GamePassMenu.Items.Frozen.Frozen.Style = "RobloxRoundDefaultButton"
      end
end)


Tabs.Other:AddParagraph({
  Title = "Ball Functions",
  Content = "Functions for the ball"
})



local BallType = Tabs.Other:AddDropdown("Dropdown", {
  Title = "Ball Type",
  Values = {"Default", "Neon"},
  Multi = false,
  Default = 1,
})

BallType:OnChanged(function(Value)
  local tps = game.Workspace.TPSSystem:FindFirstChild("TPS")
  if tps then
      if Value == "Default" then
          tps.Material = Enum.Material.Plastic
      elseif Value == "Neon" then
          tps.Material = Enum.Material.Neon
      end
  else
      warn("TPS object not found in Workspace.TPSSystem")
  end
end)



local BallTexture = Tabs.Other:AddDropdown("Dropdown", {
  Title = "Ball Texture",
  Values = {"Default", "Adidas Brazuca", "Adidas Jabulani"},
  Multi = false,
  Default = 1,
})

BallTexture:OnChanged(function(Value)
  local ball = game.Workspace.TPSSystem.TPS
  if Value == "Default" then
      ball.Decal1.Texture = "rbxassetid://1731401359"
      ball.Decal2.Texture = "rbxassetid://1731401359"
      ball.Decal3.Texture = "rbxassetid://1731401811"
      ball.Decal4.Texture = "rbxassetid://1731401811"
      ball.Decal5.Texture = "rbxassetid://1731401359"
      ball.Decal6.Texture = "rbxassetid://1731401359"
  elseif Value == "Adidas Brazuca" then
      ball.Decal1.Texture = "http://www.roblox.com/asset/?id=137668136"
      ball.Decal2.Texture = "http://www.roblox.com/asset/?id=137668129"
      ball.Decal3.Texture = "http://www.roblox.com/asset/?id=137668136"
      ball.Decal4.Texture = "http://www.roblox.com/asset/?id=137668136"
      ball.Decal5.Texture = "http://www.roblox.com/asset/?id=137668136"
      ball.Decal6.Texture = "http://www.roblox.com/asset/?id=137668136"
  elseif Value == "Adidas Jabulani" then
      ball.Decal1.Texture = "http://www.roblox.com/asset/?id=76614961"
      ball.Decal2.Texture = "http://www.roblox.com/asset/?id=76614961"
      ball.Decal3.Texture = "http://www.roblox.com/asset/?id=76614961"
      ball.Decal4.Texture = "http://www.roblox.com/asset/?id=76614961"
      ball.Decal5.Texture = "http://www.roblox.com/asset/?id=76614961"
      ball.Decal6.Texture = "http://www.roblox.com/asset/?id=76614961"
  end
end)



local BallVoice = Tabs.Other:AddDropdown("Dropdown", {
  Title = "Ball Voice",
  Values = {"Default", "OOF!", "Neverlose", "Rust", "Bruh", "TF2"},
  Multi = false,
  Default = 1,
})

BallVoice:OnChanged(function(Value)
  local ballSound = game.Workspace.TPSSystem.TPS.Sound
  if Value == "Default" then
      ballSound.SoundId = "rbxassetid://2516069845"
      ballSound.PlaybackSpeed = 0.7
      ballSound.Volume = 0.7
  elseif Value == "OOF!" then
      ballSound.SoundId = "rbxassetid://5143383166"
      ballSound.PlaybackSpeed = 1
      ballSound.Volume = 2
  elseif Value == "Neverlose" then
      ballSound.SoundId = "rbxassetid://6607204501"
      ballSound.PlaybackSpeed = 0.7
      ballSound.Volume = 0.7
  elseif Value == "Rust" then
      ballSound.SoundId = "rbxassetid://1255040462"
      ballSound.PlaybackSpeed = 0.7
      ballSound.Volume = 0.7
  elseif Value == "Bruh" then
      ballSound.SoundId = "rbxassetid://4275842574"
      ballSound.PlaybackSpeed = 0.7
      ballSound.Volume = 0.7
  elseif Value == "TF2" then
      ballSound.SoundId = "rbxassetid://2868331684"
      ballSound.PlaybackSpeed = 0.7
      ballSound.Volume = 0.7
      elseif Value == "UwU" then
      ballSound.SoundId = "rbxassetid://8679659744"
      ballSound.PlaybackSpeed = 0.7
      ballSound.Volume = 0.7
  end
end)




local BallColor = Tabs.Other:AddColorpicker("Colorpicker", {
  Title = "Ball Color",
  Default = Color3.fromRGB(255, 255, 255)
})

BallColor:OnChanged(function()
  local function changeBallColor(color)
      game.Workspace.TPSSystem.TPS.Color = color
  end

  changeBallColor(BallColor.Value)
end)

local StopBall = Tabs.Other:AddToggle("StopBall", {Title = "Stop Ball", Default = false })

StopBall:OnChanged(function()
  local Value = Options.StopBall.Value

  if Value then
      getgenv().Kitten = 5
      _G.StopBall = not _G.StopBall 
      while _G.StopBall do
          wait()
          for i = 1, 10 do
              local A_1 = game:GetService("Workspace").TPSSystem.TPS
              local A_2 = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart
              local A_3 = 0
              local A_4 = Vector3.new(4000000, 0, 4000000)
              local Event = game:GetService("Workspace").FE.Actions.KickG1
              Event:FireServer(A_1, A_2, A_3, A_4)
          end
      end
      _G.StopBall = false
  else
      _G.StopBall = false
  end
end)

local defaultColorSequence = game.Workspace.TPSSystem.TPS.Trail.Color

local TrailColor = Tabs.Other:AddColorpicker("TrailColor", {
  Title = "Trail Color",
  Default = defaultColorSequence.Keypoints[1].Value  -- Get the color from the first keyframe of the default sequence
})

TrailColor:OnChanged(function(color)
  local newColorSequence = ColorSequence.new(color)
  game.Workspace.TPSSystem.TPS.Trail.Color = newColorSequence
end)

local RainbowTrail = Tabs.Other:AddToggle("RainbowTrail", {Title = "Rainbow Trail", Default = false })

RainbowTrail:OnChanged(function()
  local arg = Options.RainbowTrail.Value

  if arg then
      local speed = 15 -- Change to speed you want
      _G.RANB = true
      while _G.RANB do
          for i = 0, 1, 0.001 * speed do
              local startColor = Color3.fromHSV(i, 1, 1)
              local endColor = Color3.fromHSV(i, 1, 1)
              local sequence = ColorSequence.new(startColor, endColor)
              game.Workspace.TPSSystem.TPS.Trail.Color = sequence
              wait()
          end
      end
  else
      _G.RANB = false
      wait(3.3)
      local startColor = Color3.fromRGB(255, 255, 255)
      local endColor = Color3.fromRGB(255, 255, 255)
      local sequence = ColorSequence.new(startColor, endColor)
      game.Workspace.TPSSystem.TPS.Trail.Color = sequence
  end
end)

local RainbowBall = Tabs.Other:AddToggle("RainbowBall", {Title = "Rainbow Ball", Default = false })

RainbowBall:OnChanged(function()
  local arg = Options.RainbowBall.Value

  local Brick = workspace.TPSSystem.TPS
        
        if arg == true then
            _G.RAIN = true
            while _G.RAIN do
                for i = 0, 1, 0.001 * 10 do
                    Brick.Color = Color3.fromHSV(i, 1, 1)
                    wait()
                    if not _G.RAIN then break end  -- Exit the loop if toggle is turned off
                end
            end
        else
            _G.RAIN = false
            Brick.Color = Color3.fromRGB(248, 248, 248)  -- Set color to white when toggle is turned off
        end
end)





Tabs.Other:AddParagraph({
  Title = "React",
  Content = "Player React"
})



Tabs.Other:AddButton({
    Title = "Alz React",
    Callback = function()
              getgenv().Kitten = 5
RunStepped = game:GetService("RunService").RenderStepped:Connect(function()
                if game.Players.LocalPlayer.Character.Humanoid.RigType == Enum.HumanoidRigType.R6 then
                    if (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - game.Workspace.TPSSystem.TPS.Position).Magnitude <= DistanceReach then
                        if game.Lighting[game.Players.LocalPlayer.Name].PreferredFoot.Value == 1 then
                            firetouchinterest(game.Players.LocalPlayer.Character["Right Leg"], game.Workspace.TPSSystem.TPS, 0)
                            firetouchinterest(game.Players.LocalPlayer.Character["Right Leg"], game.Workspace.TPSSystem.TPS, 1)
                        elseif game.Lighting[game.Players.LocalPlayer.Name].PreferredFoot.Value == 2 then
                            firetouchinterest(game.Players.LocalPlayer.Character["Left Leg"], game.Workspace.TPSSystem.TPS, 0)
                            firetouchinterest(game.Players.LocalPlayer.Character["Left Leg"], game.Workspace.TPSSystem.TPS, 1)
                        end
                    end
                end
                if game.Players.LocalPlayer.Character.Humanoid.RigType == Enum.HumanoidRigType.R15 then
                    if (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - game.Workspace.TPSSystem.TPS.Position).Magnitude <= DistanceReach then
                        if game.Lighting[game.Players.LocalPlayer.Name].PreferredFoot.Value == 1 then
                            firetouchinterest(game.Players.LocalPlayer.Character["RightLowerLeg"], game.Workspace.TPSSystem.TPS, 0)
                            firetouchinterest(game.Players.LocalPlayer.Character["RightLowerLeg"], game.Workspace.TPSSystem.TPS, 1)
                        elseif game.Lighting[game.Players.LocalPlayer.Name].PreferredFoot.Value == 2 then
                            firetouchinterest(game.Players.LocalPlayer.Character["LeftLowerLeg"], game.Workspace.TPSSystem.TPS, 0)
                            firetouchinterest(game.Players.LocalPlayer.Character["LeftLowerLeg"], game.Workspace.TPSSystem.TPS, 1)
                        end
                    end
                end
            end)
       
            RunStepped:Disconnect()
        end
})

Tabs.Other:AddButton({
    Title = "W React",
    Callback = function()
              getgenv().Kitten = 5
loadstring(game:HttpGet("https://pastebin.com/raw/GrePU9TQ",true))()
      end    
})


Tabs.Other:AddButton({
    Title = "Dribble React",
    Callback = function()
        local player = game:GetService("Players").LocalPlayer

        local mt = getrawmetatable(game);
        local old = mt.namecall
        setreadonly(mt,false)
        mt.namecall = newcclosure(function(remote,...)
           args = {...}
           method = tostring(getnamecallmethod())
           if method == "FireServer" and tostring(remote) == "Dribble" then
        
        
               args[2] = player.Character.Humanoid.LLCL
        
               return old(remote,unpack(args))
        end
           return old(remote,...)
        end)
        setreadonly(mt,true)
    end    
})

Tabs.Other:AddButton({
    Title = "Kick React",
    Callback = function()
        _G.Vector = Vector3.new(math.huge, math.huge, math.huge)

        local mt = getrawmetatable(game);
        local old = mt.namecall
        setreadonly(mt,false)
        mt.namecall = newcclosure(function(remote,...)
           args = {...}
           method = tostring(getnamecallmethod())
           if method == "FireServer" and tostring(remote) == "Kick" then
               args[6] = _G.Vector
               return old(remote,unpack(args))
           end
           return old(remote,...)
        end)
        setreadonly(mt,true)
      end    
})

Tabs.Other:AddButton({
    Title = "Shooting React",
    Callback = function()
        _G.Vector = Vector3.new(math.huge, math.huge, math.huge)

        local mt = getrawmetatable(game);
        local old = mt.namecall
        setreadonly(mt,false)
        mt.namecall = newcclosure(function(remote,...)
           args = {...}
           method = tostring(getnamecallmethod())
           if method == "FireServer" and tostring(remote) == "Shoot" then
               args[6] = _G.Vector
               return old(remote,unpack(args))
           end
           return old(remote,...)
        end)
        setreadonly(mt,true)
      end    
})

Tabs.Other:AddButton({
    Title = "Great React (goated in Low ping)",
    Callback = function()
              getgenv().Kitten = 10
loadstring(game:HttpGet('https://paste.ee/r/LjTpR'))()
      end    
})

Tabs.Other:AddButton({
    Title = "React (any position)",
    Callback = function()
              getgenv().Kitten = 10
loadstring(game:HttpGet('https://paste.ee/r/V3Wfr'))()
      end    
})


Tabs.Other:AddParagraph({
  Title = "Game Quality",
  Content = "Player Game Quality"
})


Tabs.Other:AddButton({
    Title = "Purple RTX (best with night)",
    Callback = function()
              getgenv().Kitten = 5
-- Get Lighting service
local Lighting = game:GetService("Lighting")


Lighting.Ambient = Color3.fromRGB(128, 0, 128)


Lighting.GlobalShadows = true
Lighting.Brightness = 2
Lighting.OutdoorAmbient = Color3.fromRGB(128, 0, 128)

-- Create a purple PointLight
local pointLight = Instance.new("PointLight")
pointLight.Parent = game.Workspace
pointLight.Color = Color3.fromRGB(128, 0, 128)
pointLight.Range = 50
pointLight.Brightness = 3


local starEffect = Instance.new("ParticleEmitter")
starEffect.Parent = game.Workspace
starEffect.Color = ColorSequence.new(Color3.fromRGB(255, 255, 255))
starEffect.Texture = "rbxassetid://111326512"
starEffect.Size = NumberSequence.new(0.1)
starEffect.Lifetime = NumberRange.new(1, 2)
starEffect.Speed = NumberRange.new(5, 10)
starEffect.Rate = 200
starEffect.Enabled = true


local parts = game.Workspace:GetDescendants()
for _, part in pairs(parts) do
    if part:IsA("BasePart") then
        part.BrickColor = BrickColor.new("Bright violet")
    end
end
      end    
})


Tabs.Other:AddButton({
    Title = "Normal RTX",
    Callback = function()
              getgenv().Kitten = 10
-- Roblox Graphics Enhancher
local light = game.Lighting
for i, v in pairs(light:GetChildren()) do
    v:Destroy()
end

local ter = workspace.Terrain
local color = Instance.new("ColorCorrectionEffect")
local bloom = Instance.new("BloomEffect")
local sun = Instance.new("SunRaysEffect")
local blur = Instance.new("BlurEffect")

color.Parent = light
bloom.Parent = light
sun.Parent = light
blur.Parent = light

-- enable or disable shit

local config = {

    Terrain = true;
    ColorCorrection = true;
    Sun = true;
    Lighting = true;
    BloomEffect = true;
    
}

-- settings {

color.Enabled = false
color.Contrast = 0.15
color.Brightness = 0.1
color.Saturation = 0.25
color.TintColor = Color3.fromRGB(255, 222, 211)

bloom.Enabled = false
bloom.Intensity = 0.1

sun.Enabled = false
sun.Intensity = 0.2
sun.Spread = 1

bloom.Enabled = false
bloom.Intensity = 0.05
bloom.Size = 32
bloom.Threshold = 1

blur.Enabled = false
blur.Size = 6

-- settings }


if config.ColorCorrection then
    color.Enabled = true
end


if config.Sun then
    sun.Enabled = true
end


if config.Terrain then
    -- settings {
    ter.WaterColor = Color3.fromRGB(10, 10, 24)
    ter.WaterWaveSize = 0.1
    ter.WaterWaveSpeed = 22
    ter.WaterTransparency = 0.9
    ter.WaterReflectance = 0.05
    -- settings }
end


if config.Lighting then
    -- settings {
    light.Ambient = Color3.fromRGB(0, 0, 0)
    light.Brightness = 4
    light.ColorShift_Bottom = Color3.fromRGB(0, 0, 0)
    light.ColorShift_Top = Color3.fromRGB(0, 0, 0)
    light.ExposureCompensation = 0
    light.FogColor = Color3.fromRGB(132, 132, 132)
    light.GlobalShadows = true
    light.OutdoorAmbient = Color3.fromRGB(112, 117, 128)
    light.Outlines = false
    -- settings }
end
      end    
})

Tabs.Other:AddButton({
    Title = "HD Rtx",
    Callback = function()
              getgenv().Kitten = 5
-- Put this script into a part that you want to have 4K RTX Graphics
-- This should always work, but if it doesn't then tell me and I will try and fix it.
function makeRTX()
  -- top
  part = script.Parent
  RTXPart = Instance.new("Part")
  RTXPart.Parent = part
  RTXPart.Size.X = part.Size.X
  RTXPart.Size.Y = 0.01
  RTXPart.Size.Z = part.Size.Z
  RTXPart.Material = "Glass"
  RTXPart.Transparency = 1
  RTXPart.Reflectance = 1
  RTXPart.Position.X = part.Position.X
  RTXPart.Position.Z = part.Position.Z
  addon = part.Size.Y / 2
  RTXPart.Position.Y = part.Position.Y + addon + 0.01
  -- bottom
  RTX2 = Instance.new("Part")
  RTX2.Parent = part
  RTX2.Material = "Glass"
  RTX2.Size.X = part.Size.X
  RTX2.Size.Z = part.Size.Z
  RTX2.Size.Y = 0.01
  RTX2.Transparency = 1
  RTX2.Reflectance = 1
  minus = part.Size.Y / 2
  RTX2.Position.X = part.Position.X
  RTX2.Position.Z = part.Position.Z
  RTX2.Position.Y = part.Position.Y - minus - 0.01
  -- front
  RTXF = Instance.new("Part")
  RTXF.Parent = part
  RTXF.Material = "Glass"
  RTXF.Size.Y = part.Size.Y
  RTXF.Size.X = part.Size.X
  RTXF.Size.Z = 0.01
  RTXF.Transparency = 1
  RTXF.Reflectance = 1
  plusy = part.Size.Z / 2
  RTXF.Position.X = part.Position.X
  RTXF.Position.Y = part.Position.Y
  RTXF.Position.Z = part.Position.Z - plusy - 0.01
  -- back
  RTXT = Instance.new("Part")
  RTXT.Parent = part
  RTXT.Material = "Glass"
  RTXT.Size.Y = part.Size.Y
  RTXT.Size.X = part.Size.X
  RTXT.Size.Z = 0.01
  RTXT.Transparency = 1
  RTXT.Reflectance = 1
  plusy = part.Size.Z / 2
  RTXT.Position.X = part.Position.X
  RTXT.Position.Y = part.Position.Y
  RTXT.Position.Z = part.Position.Z + plusy + 0.01
  -- left
  RTXL = Instance.new("Part")
  RTXL.Parent = part
  RTXL.Material = "Glass"
  RTXL.Transparency = 1
  RTXL.Reflectance = 1
  RTXL.Size.X = 0.01
  RTXL.Size.Y = part.Size.Y
  RTXL.Size.Z = part.Size.Z
  extra = part.Size.X / 2
  RTXL.Position.X = part.Position.X - extra - 0.01
  RTXL.Position.Y = part.Position.Y
  RTXL.Position.Z = part.Position.Z
  -- right
  RTXR = Instance.new("Part")
  RTXR.Parent = part
  RTXR.Material = "Glass"
  RTXR.Transparency = 1
  RTXR.Reflectance = 1
  RTXR.Size.X = 0.01
  RTXR.Size.Y = part.Size.Y
  RTXR.Size.Z = part.Size.Z
  extra = part.Size.X / 2
  RTXR.Position.X = part.Position.X + extra + 0.01
  RTXR.Position.Y = part.Position.Y
  RTXR.Position.Z = part.Position.Z
  -- Your part should look like it has 4K RTX Graphics once this script has run itself.
end
makeRTX()
      end    
})


Tabs.Other:AddButton({
    Title = "High Quality RTX (DAY)",
    Callback = function()
              getgenv().Kitten = 5
-- Access the Lighting service
local lighting = game:GetService("Lighting")

-- Set high-quality shader brightness
lighting.Brightness = 100 -- Increase brightness for a high-quality effect
      end    
})


Tabs.Other:AddButton({
    Title = "real life rtx",
    Callback = function()
              getgenv().Kitten = 5
game.Lighting.FogEnd = 17000
game.Lighting.FogStart = 0
game.Lighting.FogColor = Color3.fromRGB(132, 196, 245)

local a = game.Lighting
a.GlobalShadows = true
a.Ambient = Color3.fromRGB(130, 170, 200)
a.Brightness = 2
a.ColorShift_Bottom = Color3.fromRGB(160, 211, 250) 
a.ColorShift_Top = Color3.fromRGB(255, 247, 237)
a.EnvironmentDiffuseScale = 0.105
a.EnvironmentSpecularScale = 0.522
a.OutdoorAmbient = Color3.fromRGB(51, 54, 67)
a.ShadowSoftness = 0.1
      end    
})


Tabs.Other:AddButton({
    Title = "High Quality RTX ( WITH NIGHT SKY)",
    Callback = function()
              getgenv().Kitten = 5

local lighting = game.Lighting
for _, child in pairs(lighting:GetChildren()) do
child:Remove()
end

local Terra = game.Workspace.Terrain
for _, child in pairs(Terra:GetChildren()) do
child:Remove()
end

-- SKY --
local bettersky = Instance.new("Sky")
bettersky.MoonTextureId = "rbxassetid://6444320592"
bettersky.SkyboxBk = "rbxassetid://6444884337"
bettersky.SkyboxDn = "rbxassetid://6444884785"
bettersky.SkyboxFt = "rbxassetid://6444884337"
bettersky.SkyboxLf = "rbxassetid://6444884337"
bettersky.SkyboxRt = "rbxassetid://6444884337"
bettersky.SkyboxUp = "rbxassetid://6412503613"
bettersky.StarCount = 3000
bettersky.SunAngularSize = 11
bettersky.SunTextureId = "rbxassetid://6196665106"
bettersky.Parent = lighting
bettersky.Name = "RTX SKY"
-- End --

-- Clouds --
local betterclouds = Instance.new("Clouds")
betterclouds.Cover = 0.607
betterclouds.Density = 1
betterclouds.Parent = game.Workspace.Terrain
-- End --

-- SunRays --
local bettersunrays = Instance.new("SunRaysEffect")
bettersunrays.Intensity = 0.188
bettersunrays.Enabled = true
bettersunrays.Spread = 0.47
bettersunrays.Parent = lighting
-- End --

-- Water --
local Terrain = game.Workspace.Terrain
Terrain.WaterReflectance = 0.35
Terrain.WaterTransparency = 1
Terrain.WaterColor = Color3.new(0.137255, 0.447059, 0.462745)
-- End --



print("Realistic Grapchics Enabled")
script:Destroy()
      end    
})



Tabs.Other:AddButton({
    Title = "W RTX",
    Callback = function()
              getgenv().Kitten = 5
game.Lighting.FogEnd = 17000
game.Lighting.FogStart = 0
game.Lighting.FogColor = Color3.fromRGB(132, 196, 245)

local a = game.Lighting
a.GlobalShadows = true
a.Ambient = Color3.fromRGB(130, 170, 200)
a.Brightness = 2
a.ColorShift_Bottom = Color3.fromRGB(160, 211, 250) 
a.ColorShift_Top = Color3.fromRGB(255, 247, 237)
a.EnvironmentDiffuseScale = 0.105
a.EnvironmentSpecularScale = 0.522
a.OutdoorAmbient = Color3.fromRGB(51, 54, 67)
a.ShadowSoftness = 0.1
      end    
})

Tabs.Other:AddButton({
    Title = "High Quality RTX (NIGHT)",
    Callback = function()
              getgenv().Kitten = 5
-- Access the Lighting service
local lighting = game:GetService("Lighting")

-- Set high-quality shader brightness
lighting.Brightness = 1000 -- Increase brightness for a high-quality effect
      end    
})
Tabs.Other:AddButton({
    Title = "Blue RTX",
    Callback = function()
        getgenv().Kitten = 5
        -- Access required services
        local Players = game:GetService("Players")
        local Lighting = game:GetService("Lighting")

        -- Function to change the color of the ground to blue
        local function changeGroundColorToBlue()
            local ground = workspace:FindFirstChildOfClass("Terrain")
            if ground then
                ground.Material = Enum.Material.SmoothPlastic
                ground.Color = Color3.new(0, 0, 1) -- Blue color
            else
                print("No terrain found in this game.")
            end
        end

        -- Function to enable fog with blue color
        local function enableBlueFog()
            Lighting.FogEnd = 1000 -- Adjust the fog distance as needed
            Lighting.FogColor = Color3.fromRGB(0, 0, 255) -- Blue fog color
            Lighting.FogStart = 0
            Lighting.Brightness = 2 -- Increase overall brightness
            Lighting.Ambient = Color3.fromRGB(100, 100, 100) -- Adjust ambient lighting
        end

        -- Call the functions to apply changes
        changeGroundColorToBlue()
        enableBlueFog()
    end
})



Tabs.Other:AddParagraph({
  Title = "Pings",
  Content = "Player Pings"
})


Tabs.Other:AddButton({
    Title = "Fake Ping + More",
    Callback = function()
              getgenv().Kitten = 5
loadstring(game:HttpGet("https://pastebin.com/raw/61ghJPZq",true))()
      end    
})


local Clumsy = Tabs.Other:AddInput("Input", {
  Title = "Clumsy",
  Default = "0",
  TextDisappear = false,
  Numeric = true,
  Finished = true,
  Callback = function(Value)
      settings():GetService("NetworkSettings").IncomingReplicationLag = tonumber(Value)
  end	  
})


Tabs.Other:AddParagraph({
  Title = "FPS Boosters",
  Content = "Boosts your FPS!"
})




Tabs.Other:AddButton({
    Title = "FPS Unlocker",
    Callback = function()
        local UserInputService = game:GetService("UserInputService")
        local RunService = game:GetService("RunService")

        local WindowFocusReleasedFunction = function()
            RunService:Set3dRenderingEnabled(false)
            setfpscap(10)

            for _, v in pairs(workspace:GetDescendants()) do
                if v.ClassName == "Part"
                    or v.ClassName == "SpawnLocation"
                    or v.ClassName == "WedgePart"
                    or v.ClassName == "Terrain"
                    or v.ClassName == "MeshPart" then
                    v.Material = Enum.Material.SmoothPlastic
                end
            end

            local ToDisable = {
                Textures = true,
                VisualEffects = true,
                Parts = true,
                Particles = true,
                Sky = true
            }

            local ToEnable = {
                FullBright = false
            }

            local Stuff = {}

            for _, v in next, game:GetDescendants() do
                if ToDisable.Parts then
                    if v:IsA("Part") or v:IsA("Union") or v:IsA("BasePart") then
                        v.Material = Enum.Material.SmoothPlastic
                        table.insert(Stuff, 1, v)
                    end
                end

                if ToDisable.Particles then
                    if v:IsA("ParticleEmitter") or v:IsA("Smoke") or v:IsA("Explosion") or v:IsA("Sparkles") or v:IsA("Fire") then
                        v.Enabled = false
                        table.insert(Stuff, 1, v)
                    end
                end

                if ToDisable.VisualEffects then
                    if v:IsA("BloomEffect") or v:IsA("BlurEffect") or v:IsA("DepthOfFieldEffect") or v:IsA("SunRaysEffect") then
                        v.Enabled = false
                        table.insert(Stuff, 1, v)
                    end
                end

                if ToDisable.Textures then
                    if v:IsA("Decal") or v:IsA("Texture") then
                        v.Texture = ""
                        table.insert(Stuff, 1, v)
                    end
                end

                if ToDisable.Sky then
                    if v:IsA("Sky") then
                        v.Parent = nil
                        table.insert(Stuff, 1, v)
                    end
                end
            end

            game:GetService("TestService"):Message("Effects Disabler Script : Successfully disabled " .. #Stuff .. " assets / effects. Settings :")

            for i, v in next, ToDisable do
                print(tostring(i) .. ": " .. tostring(v))
            end

            if ToEnable.FullBright then
                local Lighting = game:GetService("Lighting")

                Lighting.FogColor = Color3.fromRGB(255, 255, 255)
                Lighting.FogEnd = math.huge
                Lighting.FogStart = math.huge
                Lighting.Ambient = Color3.fromRGB(255, 255, 255)
                Lighting.Brightness = 5
                Lighting.ColorShift_Bottom = Color3.fromRGB(255, 255, 255)
                Lighting.ColorShift_Top = Color3.fromRGB(255, 255, 255)
                Lighting.OutdoorAmbient = Color3.fromRGB(255, 255, 255)
                Lighting.Outlines = true
            end
        end

        local WindowFocusedFunction = function()
            RunService:Set3dRenderingEnabled(true)
            setfpscap(360)
        end

        local Initialize = function()
            UserInputService.WindowFocusReleased:Connect(WindowFocusReleasedFunction)
            UserInputService.WindowFocused:Connect(WindowFocusedFunction)
        end

        Initialize()
    end
})

Tabs.Other:AddButton({
    Title = "FPS Tracker",
    Callback = function()
        local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local TextLabel = Instance.new("TextLabel")
local TextLabel_2 = Instance.new("TextLabel")

--Properties:

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(68, 68, 68)
Frame.ClipsDescendants = true
Frame.Position = UDim2.new(0.022813689, 0, 0.0541082174, 0)
Frame.Size = UDim2.new(0, 79, 0, 56)

UICorner.Parent = Frame

TextLabel.Parent = Frame
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.Position = UDim2.new(0.129077807, 0, 0.400000036, 0)
TextLabel.Size = UDim2.new(0, 31, 0, 30)
TextLabel.Font = Enum.Font.SourceSansBold
TextLabel.Text = "50"
TextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.TextSize = 34.000
TextLabel.TextWrapped = true

TextLabel_2.Parent = Frame
TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.BackgroundTransparency = 1.000
TextLabel_2.Position = UDim2.new(0.127986133, 0, 0.132142887, 0)
TextLabel_2.Size = UDim2.new(0, 29, 0, 15)
TextLabel_2.Font = Enum.Font.SourceSansBold
TextLabel_2.Text = "FPS"
TextLabel_2.TextColor3 = Color3.fromRGB(255, 0, 0)
TextLabel_2.TextScaled = true
TextLabel_2.TextSize = 34.000
TextLabel_2.TextWrapped = true

-- Scripts:

local function GZAQCE_fake_script() -- TextLabel.LocalScript 
local script = Instance.new('LocalScript', TextLabel)

local textLabel = script.Parent

local runService = game:GetService("RunService")

local goodFPS = 30
local okFPS = 15

runService.RenderStepped:Connect(function()

  local currentFPS = workspace:GetRealPhysicsFPS()
  textLabel.Text = math.floor(currentFPS)..""

  if currentFPS >= goodFPS then

    textLabel.TextColor3 = Color3.new(0,1,0)

  elseif currentFPS >= okFPS then

    textLabel.TextColor3 = Color3.new(1, 0.333333, 0)

  else

    textLabel.TextColor3 = Color3.new(1,0,0)

  end

end)
end
coroutine.wrap(GZAQCE_fake_script)()
local function JMWW_fake_script() -- Frame.LocalScript 
local script = Instance.new('LocalScript', Frame)

script.Parent.Draggable = true
script.Parent.Active = true

coroutine.wrap(JMWW_fake_script)()
end
    end
}) 

Tabs.Other:AddButton({
    Title = "FPS Booster 2",
    Callback = function()
              getgenv().Kitten = 5
local function applyOptimizations()
    local workspace = game.Workspace
    local lighting = game.Lighting
    local terrain = workspace.Terrain
    local starterGui = game:GetService("StarterGui")

    terrain.WaterWaveSize = 0
    terrain.WaterWaveSpeed = 0
    terrain.WaterReflectance = 0
    terrain.WaterTransparency = 0

    lighting.GlobalShadows = false
    lighting.FogEnd = 9e9
    lighting.Brightness = 0

    settings().Rendering.QualityLevel = "Level01"

    for _, descendant in pairs(game:GetDescendants()) do
        if descendant:IsA("BasePart") or descendant:IsA("MeshPart") then
            descendant.Material = "SmoothPlastic"
            descendant.Reflectance = 0
            descendant.CastShadow = false
        elseif descendant:IsA("Decal") then
            descendant.Transparency = 1
        elseif descendant:IsA("ParticleEmitter") or descendant:IsA("Trail") then
            descendant.Lifetime = NumberRange.new(0)
        elseif descendant:IsA("Explosion") then
            descendant.BlastPressure = 1
            descendant.BlastRadius = 1
        elseif descendant:IsA("Fire") or descendant:IsA("SpotLight") or descendant:IsA("Smoke") then
            descendant.Enabled = false
        end
    end

    for _, effect in pairs(lighting:GetChildren()) do
        if effect:IsA("PostEffect") or effect:IsA("DepthOfFieldEffect") then
            effect.Enabled = false
        end
    end

    setclipboard("https://discord.gg/vYD98D4nsq")

    starterGui:SetCore("SendNotification", {
        Title = "FPS Boost",
        Text = "The FPS Boost has applied!\nDiscord link copied to clipboard!",
        Duration = 7,
        Style = {
            Title = {
                Font = Enum.Font.SourceSansBold,
                TextSize = 20,
                TextStrokeTransparency = 0,
                TextColor = Color3.new(1, 1, 1),
            },
            Background = {
                Transparency = 0.1,
                BackgroundColor3 = Color3.new(0, 0.7, 1),
                BorderSizePixel = 0,
            },
        },
    })

    print("The FPS Boost has applied!")
    print("Discord link copied to clipboard!")
    print("Made by ludaz. Enjoy the script!")
end

applyOptimizations()
      end    
})



Tabs.Other:AddParagraph({
  Title = "Interface",
  Content = "Customize your interface!"
})


local FOV = Tabs.Other:AddInput("Input", {
  Title = "FOV",
  Default = "0",
  Numeric = true,
  Finished = false,
  TextDisappear = false,
  Callback = function(Value)
      local FOV = tonumber(Value)
      if FOV then
          game.Workspace.Camera.FieldOfView = FOV
      end
  end	  
}) 



Tabs.Other:AddButton({
    Title = "Old UI",
    Callback = function()
        spawn(function()
            while true do
                local player = game.Players.LocalPlayer
                local playerGui = player:WaitForChild("PlayerGui")
                local startScreen = playerGui:WaitForChild("Start")
                local scores = startScreen:WaitForChild("Scores")
                local levelLabel = scores:WaitForChild("Level")
                levelLabel.Font = Enum.Font.Cartoon

                -- Wait for 1 minute before repeating
                wait(60)  -- 60 seconds is 1 minute
            end
        end)
    end
})

Tabs.Other:AddButton({
    Title = "Resolution",
    Callback = function()
              getgenv().Kitten = 10
getgenv().Resolution = {
    [".gg/scripters"] = 0.65
}

local Camera = workspace.CurrentCamera
if getgenv().gg_scripters == nil then
    game:GetService("RunService").RenderStepped:Connect(
        function()
            Camera.CFrame = Camera.CFrame * CFrame.new(0, 0, 0, 1, 0, 0, 0, getgenv().Resolution[".gg/scripters"], 0, 0, 0, 1)
        end
    )
end
getgenv().gg_scripters = "Aori0001"
      end    
})


local Brightness = Tabs.Other:AddInput("Input", {
  Title = "Brightness",
  Default = "",
  Numeric = true,
  Finished = false,
  Callback = function(Value)
      local lighting = game:GetService("Lighting")
      lighting.Brightness = Value
  end
})



Tabs.Other:AddParagraph({
  Title = "Player",
  Content = "Player Functions"
})

Tabs.Other:AddButton({
  Title = "Chat Log Spy",
  Callback = function()
      
print("-- Chat Spy Executed --")
print("Type \"spy\" to enable or disable the chat spy.")

-- Config
Config = {
enabled = true,
spyOnMyself = true,
public = false,
publicItalics = true
}

-- Customizing Log Output
PrivateProperties = {
Color = Color3.fromRGB(0,255,255); 
Font = Enum.Font.SourceSansBold;
TextSize = 18;
}

local StarterGui = game:GetService("StarterGui")
local Players = game:GetService("Players")
local player = Players.LocalPlayer
local saymsg = game:GetService("ReplicatedStorage"):WaitForChild("DefaultChatSystemChatEvents"):WaitForChild("SayMessageRequest")
local getmsg = game:GetService("ReplicatedStorage"):WaitForChild("DefaultChatSystemChatEvents"):WaitForChild("OnMessageDoneFiltering")
local instance = (_G.chatSpyInstance or 0) + 1
_G.chatSpyInstance = instance

local function onChatted(p,msg)
  if _G.chatSpyInstance == instance then
    if p==player and msg:lower():sub(1,4)=="/spy" then
      Config.enabled = not Config.enabled
      wait(0.3)
      PrivateProperties.Text = "{SPY "..(Config.enabled and "EN" or "DIS").."ABLED}"
      StarterGui:SetCore("ChatMakeSystemMessage", PrivateProperties)
    elseif Config.enabled and (Config.spyOnMyself==true or p~=player) then
      msg = msg:gsub("[\n\r]",''):gsub("\t",' '):gsub("[ ]+",' ')
      local hidden = true
      local conn = getmsg.OnClientEvent:Connect(function(packet,channel)
        if packet.SpeakerUserId==p.UserId and packet.Message==msg:sub(#msg-#packet.Message+1) and (channel=="All" or (channel=="Team" and Config.public==false and Players[packet.FromSpeaker].Team==player.Team)) then
          hidden = false
        end
      end)
      wait(1)
      conn:Disconnect()
      if hidden and Config.enabled then
        if Config.public then
          saymsg:FireServer((Config.publicItalics and "/me " or '').."{SPY} [".. p.Name .."]: "..msg,"All")
        else
          PrivateProperties.Text = "{SPY} [".. p.Name .."]: "..msg
          StarterGui:SetCore("ChatMakeSystemMessage", PrivateProperties)
        end
      end
    end
  end
end

for _,p in ipairs(Players:GetPlayers()) do
  p.Chatted:Connect(function(msg) onChatted(p,msg) end)
end

Players.PlayerAdded:Connect(function(p)
  p.Chatted:Connect(function(msg) onChatted(p,msg) end)
end)

PrivateProperties.Text = "{SPY "..(Config.enabled and "EN" or "DIS").."ABLED}"
StarterGui:SetCore("ChatMakeSystemMessage", PrivateProperties)
local chatFrame = player.PlayerGui.Chat.Frame
chatFrame.ChatChannelParentFrame.Visible = true
chatFrame.ChatBarParentFrame.Position = chatFrame.ChatChannelParentFrame.Position+UDim2.new(UDim.new(),chatFrame.ChatChannelParentFrame.Size.Y)
  end
})

Tabs.Other:AddButton({
    Title = "Square Box",
    Callback = function()
local Players = game:GetService("Players")
local RunService = game:GetService("RunService")
local Camera = game:GetService("Workspace").CurrentCamera


local function createESP(player)
    local espBox = Instance.new("BoxHandleAdornment")
    espBox.Adornee = player.Character.HumanoidRootPart
    espBox.Size = player.Character:GetExtentsSize() + Vector3.new(0.1, 0.1, 0.1) -- Add a small margin around the player
    espBox.Color3 = Color3.new(1, 1, 1) -- White color
    espBox.Transparency = 0.5 -- Semi-transparent
    espBox.ZIndex = 5 -- Render above other parts
    espBox.Parent = player.Character
end


local function updateESP(player)
    local espBox = player.Character:FindFirstChild("ESP_Box")
    if espBox and player.Character:FindFirstChild("HumanoidRootPart") then
        local playerPosition, onScreen = Camera:WorldToViewportPoint(player.Character.HumanoidRootPart.Position)
        if onScreen then
            espBox.Visible = true
            espBox.Size = player.Character:GetExtentsSize() + Vector3.new(0.1, 0.1, 0.1)
            espBox.CFrame = CFrame.new(Vector3.new(playerPosition.X, playerPosition.Y, 0))
        else
            espBox.Visible = false
        end
    end
end

-- Create ESP for existing players
for _, player in ipairs(Players:GetPlayers()) do
    createESP(player)
end

-- Connect ESP creation function to player added event
Players.PlayerAdded:Connect(createESP)

-- Update ESP positions every frame
RunService.RenderStepped:Connect(function()
    for _, player in ipairs(Players:GetPlayers()) do
        updateESP(player)
    end
end)
      end    
})

Tabs.Other:AddButton({
    Title = "Anti Fling",
    Callback = function()
              getgenv().Kitten = 10
local speaker = game.Players.LocalPlayer
            local RunService = game:GetService("RunService")
            Clip = false
                wait(0.1)
                local function NoclipLoop()
                    if Clip == false and speaker.Character ~= nil then
                        for _, child in pairs(speaker.Character:GetDescendants()) do
                            if child:IsA("BasePart") and child.CanCollide == false and child.Name == "Right Leg" or child.Name == "Right Arm" or child.Name == "Left Arm" or child.Name == "Right Arm" or child.Name == "Torso" then
                                child.CanCollide = false
                            end
                        end
                    end
                end
                Noclipping = RunService.Stepped:Connect(NoclipLoop)

      end
  
  
})

Tabs.Other:AddButton({
    Title = "Ball TP",
    Callback = function()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game:GetService("Workspace").TPSSystem.TPS.CFrame
    end    
})



local Level = Tabs.Other:AddInput("Input", {
  Title = "Level",
  Default = "0",
  Numeric = true, -- Only allows numbers
  Finished = true, -- Only calls callback when you press enter
  Callback = function(Value)
      local Targets = tonumber(Value)
      wait(0.1)
      local mt = getrawmetatable(game)
      setreadonly(mt, false)
      local old_index = mt.__index
      mt.__index = function(a, b)
          if tostring(a) == "PPLevel" or tostring(a) == "Level" then
              if tostring(b) == "Value" then
                  return Targets
              end
          end
          return old_index(a, b)
      end
  end
})

Tabs.Other:AddButton({
    Title = "Fly no banned",
    Callback = function()
              getgenv().Kitten = 5
loadstring(game:HttpGet("https://raw.githubusercontent.com/xXxUnKnowGuyxXx/123/main/Butterfly"))()
      end    
})


Tabs.Other:AddButton({
    Title = "Speed no banned",
    Callback = function()
              getgenv().Kitten = 5
loadstring(game:HttpGet("https://raw.githubusercontent.com/LETGO061/Roblox/main/7w7"))()
      end    
})


Tabs.Other:AddButton({
    Title = "Fly On Ball",
    Callback = function()
              getgenv().Kitten = 5
while true do
    game.Players.LocalPlayer.Character:MoveTo(game.Workspace.TPSSystem.TPS.Position)
    wait()
end

      end    
})

Tabs.Other:AddButton({
    Title = "Fake Switch [BLUE TEAM]",
    Callback = function()
              getgenv().Kitten = 5
_G.FB = true
    while _G.FB do
    wait()
    game.Workspace.FE.PlayerTeam.RemoteEventB:FireServer()  
    end
    
    _G.FB = false
end
})

Tabs.Other:AddButton({
    Title = "Fake Switch [RED TEAM]",
    Callback = function()
              getgenv().Kitten = 5
_G.FR = true
    while _G.FR do
    wait()
    game.Workspace.FE.PlayerTeam.RemoteEventR:FireServer()  
    end
    
    _G.FR = false
end
})


Tabs.Other:AddButton({
    Title = "Fling",
    Callback = function()
              getgenv().Kitten = 5
loadstring(game:HttpGet("https://raw.githubusercontent.com/0Ben1/fe./main/Fling%20GUI"))()
      end    
})


Tabs.Other:AddParagraph({
  Title = "Effects",
  Content = "Game Effects"
})



Tabs.Other:AddButton({
    Title = "Goal Effect",
    Callback = function()
              getgenv().Kitten = 10
local Goal = game:GetObjects("rbxassetid://14967407622")[1]

game.Workspace.RedScore:GetPropertyChangedSignal("Value"):Connect(function()
Goal.Parent = game.Workspace.BlueGoal.Part
wait(12)
Goal.Parent = nil
end)

game.Workspace.BlueScore:GetPropertyChangedSignal("Value"):Connect(function()
Goal.Parent = game.Workspace.RedGoal.Part

wait(12)
Goal.Parent = nil

end)

      end    
})

Tabs.Other:AddParagraph({
  Title = "Other",
  Content = "Other Features"
})



Tabs.Other:AddButton({
    Title = "Drag (Sometimes Works)",
    Callback = function()
              getgenv().Kitten = 10
_G.SavedSettings = {

LeftCurve = true,
RightCurve = true,
EnabledKeyBind = "l",
CurveSwitchKeyBind = "p",
SaveSettingsKeyBind = "k"

}

_G.Executed = false
_G.Enabled = true

local StarterGui = game:GetService("StarterGui")


function loadSettings()
local HttpService = game:GetService("HttpService")
if (readfile and isfile and isfile("StreetSoccerSettings.txt")) then
    _G.SettingsToSave = HttpService:JSONDecode(readfile("StreetSoccerSettings.txt"))
    else 
        
        _G.SavedSettings.LeftCurve = false
        _G.SavedSettings.RightCurve = true
        _G.SavedSettings.EnabledKeyBind = "l"
        _G.SavedSettings.CurveSwitchKeyBind = "p"
        _G.SavedSettings.SaveSettingsKeyBind = "k"
        
        json = HttpService:JSONEncode(_G.SavedSettings)
        writefile("StreetSoccerSettings.txt", json)
   end
end







function saveSettings()
    local json
    local HttpService = game:GetService("HttpService")
    if (writefile) then
        json = HttpService:JSONEncode(_G.SettingsToSave)
        writefile("StreetSoccerSettings.txt", json)
        else
        StarterGui:SetCore("ChatMakeSystemMessage",  { Text = "[AVEXCITAL SCRIPTS] Unfortunately we cannot save the settings. This is likely due to your executor.", Color = Color3.fromRGB(0, 100, 188), Font = Enum.Font.Gotham})
    end
end

    


loadSettings()


            local Player = game.Players.LocalPlayer
            local Mouse = Player:GetMouse()

                Mouse.KeyDown:Connect(function(activate)
                activate:lower()
                if activate == tostring(_G.SavedSettings.EnabledKeyBind) then
                    _G.Enabled = not _G.Enabled
                    
                        wait(0.1)
                        if _G.Enabled then
                        StarterGui:SetCore("ChatMakeSystemMessage",  { Text = "[AVEXCITAL SCRIPTS] The script is now enabled!", Color = Color3.fromRGB(11, 9, 36), Font = Enum.Font.Gotham})
                        elseif not _G.Enabled then
                        StarterGui:SetCore("ChatMakeSystemMessage",  { Text = "[AVEXCITAL SCRIPTS] The script is now unenabled!", Color = Color3.fromRGB(11, 9, 36), Font = Enum.Font.Gotham})
                            
                            end
        end
                end)
        
        
                Mouse.KeyDown:Connect(function(activate)
                activate:lower()
                if activate == tostring(_G.SavedSettings.CurveSwitchKeyBind) then
                    _G.LeftCurve = not _G.LeftCurve
                    _G.RightCurve = not _G.RightCurve
                    
                        wait(0.1)
                        if _G.LeftCurve then
                        StarterGui:SetCore("ChatMakeSystemMessage",  { Text = "[AVEXCITAL SCRIPTS] The curve is now to the left!", Color = Color3.fromRGB(11, 9, 36), Font = Enum.Font.Gotham})
                        elseif _G.RightCurve then
                        StarterGui:SetCore("ChatMakeSystemMessage",  { Text = "[AVEXCITAL SCRIPTS] The script is now to the right!", Color = Color3.fromRGB(11, 9, 36), Font = Enum.Font.Gotham})
                            
                            end
        end
                end)
        
        
        
                Mouse.KeyDown:Connect(function(activate)
                activate:lower()
                if activate == tostring(_G.SavedSettings.SaveSettingsKeyBind) then
                   saveSettings()
        end
            end)

local args = {
    [1] = workspace.TPSSystem.TPS,
    [2] = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart
}

game:GetService("RunService").RenderStepped:Connect(function()
if _G.Enabled == false then return end

if _G.SavedSettings.RightCurve then

workspace.FE.Actions.KickC1:FireServer(unpack(args))

elseif _G.SavedSettings.LeftCurve then
    
workspace.FE.Actions.KickC2:FireServer(unpack(args))
end
end)




if _G.Executed == false then
    if _G.SavedSettings.RightCurve then
StarterGui:SetCore("ChatMakeSystemMessage",  { Text = "[AVEXCITAL SCRIPTS] The script has been executed successfully! The keybind for enabling or disabling the script is ".. _G.SavedSettings.EnabledKeyBind.. ". The keybind for switching your curve settings is ".._G.SavedSettings.CurveSwitchKeyBind.. ", and the keybind for saving your settings is ".._G.SavedSettings.SaveSettingsKeyBind.. ". Also, the ball is curving to the right. I almost forgot as well, say :EnabledKey then your desired keybind for enabling or disabling the script and it'll change it. For example :EnabledKeyJ makes the keybind 'J'. The same goes for :CurveSwitchKey (changes your curve keybind) and :SaveSwitchKey (changes your save keybind).", Color = Color3.fromRGB(0, 100, 188), Font = Enum.Font.Gotham})

elseif _G.SavedSettings.LeftCurve then

StarterGui:SetCore("ChatMakeSystemMessage",  { Text = "[AVEXCITAL SCRIPTS] The script has been executed successfully! The keybind for enabling or disabling the script is ".. _G.SavedSettings.EnabledKeyBind.. ". The keybind for switching your curve settings is ".._G.SavedSettings.CurveSwitchKeyBind.. ", and the keybind for saving your settings is ".._G.SavedSettings.SaveSettingsKeyBind.. ". Also, the ball is curving to the left. I almost forgot as well, say :EnabledKey then your desired keybind for enabling or disabling the script and it'll change it. For example :EnabledKeyJ makes the keybind 'J'. The same goes for :CurveSwitchKey (changes your curve keybind) and :SaveSwitchKey (changes your save keybind).", Color = Color3.fromRGB(0, 100, 188), Font = Enum.Font.Gotham})

end
_G.Executed = true
end
      end    
})


Tabs.Other:AddButton({
    Title = "Stop ball loop",
    Callback = function()
              getgenv().Kitten = 10
_G.StopBall = true
while _G.StopBall do
  wait()
  for i = 1, 10 do
      local A_1 = game:GetService("Workspace").TPSSystem.TPS
      local A_2 = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart
      local A_3 = 0
      local A_4 = Vector3.new(4000000, 0, 4000000)
      local Event = game:GetService("Workspace").FE.Actions.KickG1
      Event:FireServer(A_1, A_2, A_3, A_4)
  end
end

_G.StopBall = false
      end    
})

Tabs.Other:AddButton({
    Title = "Ball changer and spee",
    Callback = function()
              getgenv().Kitten = 5
local mt = getrawmetatable(game)
local ncallsa = mt.__namecall
  setreadonly(mt, false)
  mt.__namecall = newcclosure(function(...)
      local args = {...}
      if not checkcaller() and getnamecallmethod() == "Kick" then
          return nil
      end
      return ncallsa(...)
  end)
  setreadonly(mt, true)

  local mmt = getrawmetatable(game)

local oldnamecall = mmt.__namecall

setreadonly(mmt, false)

mmt.__namecall = newcclosure(function(self, ...)
 local method = tostring(getnamecallmethod())
 local Args = {...}
 if not checkcaller() and method == "FireServer" and tostring(self) == "Banned" then
     return nil
 end
 
 return oldnamecall(self, ...)
end)

setreadonly(mmt, true)
  
  local gmt = getrawmetatable(game);
setreadonly(gmt, false);
local old_index = gmt.__index;
gmt.__index = function(a, b)
  if tostring(a) == "BannedA" or tostring(a) == "BannedB" or tostring(a) == "BannedC" or tostring(a) == "BannedD" then
      if tostring(b) == "Value" then
          return false;
      end
  end
  return old_index(a, b);
end

local bgmt = getrawmetatable(game);
setreadonly(bgmt, false);
local bold_index = bgmt.__index;
bgmt.__index = function(a, b)
  if tostring(a) == "BCount" then
      if tostring(b) == "Value" then
          return 0;
      end
  end
  return bold_index(a, b);
end

for i,BN in pairs(game:GetService("Workspace").FE.Settings:GetChildren()) do
  if BN.Name == "BName" then
  BN:Destroy()
end
end

for i,b in pairs(game.Players.LocalPlayer.Character:GetChildren()) do
  if b.Name == " " then
  b:Destroy()
end
end

for i,lc2 in pairs(game.Players.LocalPlayer.Character:GetChildren()) do
  if lc2:IsA("LocalScript") and string.match(lc2.Name, "1") or string.match(lc2.Name, "2") or string.match(lc2.Name, "3") or string.match(lc2.Name, "4") or string.match(lc2.Name, "5") or string.match(lc2.Name, "6") or string.match(lc2.Name, "7") or string.match(lc2.Name, "8") or string.match(lc2.Name, "9") then
     lc2:Destroy()
  end
end

for i,lc in pairs(game.Players.LocalPlayer.PlayerGui.Start:GetChildren()) do
  if lc:IsA("LocalScript") and string.match(lc.Name, "1") or string.match(lc.Name, "2") or string.match(lc.Name, "3") or string.match(lc.Name, "4") or string.match(lc.Name, "5") or string.match(lc.Name, "6") or string.match(lc.Name, "7") or string.match(lc.Name, "8") or string.match(lc.Name, "9") then
     lc:Destroy()
  end
end

for i,c in pairs(game.Players.LocalPlayer.PlayerGui.Start:GetChildren()) do
  if c.Name == "CheckPlayerW" then
  c:Destroy()
end
end

for i,z in pairs(game.StarterGui.Start:GetChildren()) do
  if z.Name == "CheckPlayerW" then
  z:Destroy()
end
end

for _, v in pairs(game.StarterPlayer.StarterCharacterScripts:GetDescendants()) do
if v.Name == " " then
v:Destroy()
end
end

game.Players.LocalPlayer.CharacterAdded:Connect(function()
wait(0.5)
for i,char in pairs(game.Players.LocalPlayer.Character:GetChildren()) do
  if char.Name == " " then
     char:Destroy()
  end
  end
end)



for i,nolag in pairs(game.StarterGui.Start:GetChildren()) do
if nolag.Name == "Gradient" then
nolag:Destroy()
end
end
for i,nolaglp in pairs(game.Players.LocalPlayer.PlayerGui.Start:GetChildren()) do
if nolaglp.Name == "Gradient" then
nolaglp:Destroy()
end
end


local DiscordLib =
  loadstring(game:HttpGet "https://raw.githubusercontent.com/bloodball/-back-ups-for-libs/main/discord")()

local win = DiscordLib:Window("LocalPlayer Tab")

local pcserv = win:Server("Ball size and speed", "")

local pctextbs = pcserv:Channel("Textboxes")

pctextbs:Textbox(
  "Ball Size changer",
  "Type here!",
  true,
  function(arg)         
game.Workspace.TPSSystem.TPS.Size =Vector3.new(arg, arg, arg)
  end
)

pctextbs:Button(
  "Speed (click if you want more speed)",
  function()
      local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoid = character:WaitForChild("Humanoid")

-- Define the speed multiplier
local speedMultiplier = 2

-- Set the WalkSpeed property of the humanoid to increase speed
humanoid.WalkSpeed = humanoid.WalkSpeed * speedMultiplier
  end
)
end
})

Tabs.Other:AddButton({
    Title = "Shift Lock",
    Callback = function()
              getgenv().Kitten = 10
local NotificationHolder = loadstring(game:HttpGet("https://raw.githubusercontent.com/BocusLuke/UI/main/STX/Module.Lua"))()
local Notification = loadstring(game:HttpGet("https://raw.githubusercontent.com/BocusLuke/UI/main/STX/Client.Lua"))()

Notification:Notify(
    {Title = "Noba gui", Description = "by ludaz"},
    {OutlineColor = Color3.fromRGB(80, 80, 80),Time = 5, Type = "option"},
    {Image = "http://www.roblox.com/asset/?id=6023426923", ImageColor = Color3.fromRGB(255, 84, 84), Callback = function(State) print(tostring(State)) end}
)


local Library = loadstring(game:HttpGet("https://pastebin.com/raw/vff1bQ9F"))()
local Window = Library.CreateLib("Coded By ludaz", "DarkTheme")
local Tab = Window:NewTab("PermShiftlock")
local Section = Tab:NewSection("Idk")
local Section = Tab:NewSection("Right Shiftlock")
Section:NewButton("Permanent Shift lock (Mobile) ", "Mobile Version", function()
loadstring(game:HttpGet('https://raw.githubusercontent.com/Unknownproootest/Permanent-Shift-Lock-Script/main/PermShiftlock'))()
    print("ggs")
end)

Section:NewButton("Permanent Shift lock (Tablet/iPad) ", "Tablet Version", function()
loadstring(game:HttpGet('https://raw.githubusercontent.com/Unknownproootest/Permanent-Shift-Lock-Beta/main/PermShiftlockV2'))()
    print("ggs")
end)

local Section = Tab:NewSection("Left Shiftlock")
Section:NewButton("Permanent Shift lock (Left) ", "Both Device", function()

loadstring(game:HttpGet('https://raw.githubusercontent.com/Unknownproootest/Permanent-Shift-Lock-Beta/main/PermShiftlockLeftMain'))()
    print("ggs")
end)

local Section = Tab:NewSection("Status works: ÃƒÆ’Ã†â€™Ãƒâ€šÃ‚Â°ÃƒÆ’Ã¢â‚¬Â¦Ãƒâ€šÃ‚Â¸ÃƒÆ’Ã¢â‚¬Â¦Ãƒâ€šÃ‚Â¸ÃƒÆ’Ã¢â‚¬Å¡Ãƒâ€šÃ‚Â¢")

local Section = Tab:NewSection("Alpha Version")
Section:NewButton("Smooth Shiftlock (Toggle)", "idk coding yet again if is work every device", function()

loadstring(game:HttpGet('https://raw.githubusercontent.com/Unknownproootest/Permanent-Shift-Lock-Beta/main/SmoothShiftLock-Notify'))()
    print("ggs")
end)
local Tab = Window:NewTab("   ")
local Section = Tab:NewSection("u found it ;-; this is a test ")
local Section = Tab:NewSection("Crosshair_Lock Test ")
Section:NewButton("   ", "ambatakum", function()

loadstring(game:HttpGet('https://raw.githubusercontent.com/Unknownproootest/Scriptblox/main/TestingV2'))()
    print("ggs")
end)
      end    
})



Tabs.Other:AddButton({
    Title = "Air Dribble Helper",
    Callback = function()
              getgenv().Kitten = 5
loadstring(game:HttpGet("https://raw.githubusercontent.com/fanlolZzz/tester/main/gay"))()
      end    
})


Tabs.More:AddParagraph({
  Title = "Grass",
  Content = "Customize your grass"
})


local defaultColor = game.Workspace.SoccerFieldParts.SoccerField.Color

local GrassColor = Tabs.More:AddColorpicker("GrassColor", {
  Title = "Grass Color",
  Default = defaultColor
})

GrassColor:OnChanged(function()
  local color = Options.GrassColor.Value
  local soccerField = game.Workspace.SoccerFieldParts.SoccerField

  if soccerField then
      soccerField.Color = color
  end
end)


Tabs.More:AddButton({
    Title = "Old Grass",
    Callback = function()
        spawn(function()
            local soccerField = workspace.SoccerFieldParts.SoccerField
            while true do
                local dirt = soccerField:FindFirstChild("Dirt")
                if dirt then
                    dirt:Destroy()
                end

                soccerField.Material = Enum.Material.Granite
                soccerField.Color = Color3.new(41/255, 99/255, 27/255)
                wait(60)  -- Wait for 60 seconds before looping again
            end
        end)
    end
})




Tabs.More:AddParagraph({
  Title = "Dribble",
  Content = "Dribbling Features"
})




local InfDribble = Tabs.More:AddToggle("InfDribble", {Title = "Inf Dribble Faster", Default = false })

InfDribble:OnChanged(function()
  local arg = Options.InfDribble.Value
  if arg == true then
      game:GetService("Players").LocalPlayer.Backpack.Ground.Value = true
  else
      game:GetService("Players").LocalPlayer.Backpack.Ground.Value = false
  end
end)



Tabs.More:AddParagraph({
  Title = "Collision",
  Content = "Customize your collision"
})

Tabs.More:AddButton({
    Title = "Collision",
    Callback = function()
game.Workspace.TPSSystem.TPS.CanCollide = true

game.Workspace.TPSSystem.TPS.CanCollide = False
            end
})

Tabs.More:AddParagraph({
  Title = "Defense",
  Content = "Defending Features"
})

local AutoDefend = Tabs.More:AddToggle("AutoDefend", {Title = "Auto Defend", Default = false })

AutoDefend:OnChanged(function()
  local arg = Options.AutoDefend.Value
  _G.AUTODEFENCE = arg
  if arg then
      while _G.AUTODEFENCE do
          wait()
          if game.Players.LocalPlayer.TeamColor == BrickColor.new("Bright blue") then
              game.Players.LocalPlayer.Character.Humanoid.WalkToPoint = Vector3.new(0.6464786529541016, 13.299994468688965, 92.49656677246094)
          else
              game.Players.LocalPlayer.Character.Humanoid.WalkToPoint = Vector3.new(0.11751431971788406, 13.299994468688965, -91.30338287353516)
          end
          
          if game.Players.LocalPlayer.TeamColor == BrickColor.new("Bright blue") then
              if (game.Workspace.TPSSystem.TPS.Position - game.Workspace.TPSSystem.Part2.Position).Magnitude <= 125 then
                  game.Players.LocalPlayer.PlayerGui.LockScript.SetLock.Value = true
                  game.Workspace.CurrentCamera.CFrame = CFrame.lookAt(game.Workspace.CurrentCamera.CFrame.Position + Vector3.new(0, 45, 0), game.Workspace.RedGoal.Part.Position)
                  game.Players.LocalPlayer.Character.Humanoid:MoveTo(game.Workspace.TPSSystem.TPS.Position)
                  for i,v in pairs(game.Workspace:GetDescendants()) do
                      if v.Name == "TPS" and v:IsA("Part") then
                          if (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - v.Position).Magnitude <= 16 then
                              local ModuleKick = require(game:GetService("Players").LocalPlayer.Backpack.Module)
                              ModuleKick.Tackle()
                              local A_1 = game:GetService("Workspace").TPSSystem.TPS
                              local A_2 = game:GetService("Players").LocalPlayer.Character.Head
                              local Event = game:GetService("Workspace").FE.Actions.Tackle
                              Event:FireServer(A_1, A_2)
                          end
                      end
                  end
              end
          elseif game.Players.LocalPlayer.TeamColor == BrickColor.new("Bright red") then
              if (game.Workspace.TPSSystem.TPS.Position - game.Workspace.TPSSystem.Part1.Position).Magnitude <= 125 then
                  game.Players.LocalPlayer.PlayerGui.LockScript.SetLock.Value = true
                  game.Workspace.CurrentCamera.CFrame = CFrame.lookAt(game.Workspace.CurrentCamera.CFrame.Position + Vector3.new(0, 45, 0), game.Workspace.BlueGoal.Part.Position)
                  game.Players.LocalPlayer.Character.Humanoid:MoveTo(game.Workspace.TPSSystem.TPS.Position)
                  for i,v in pairs(game.Workspace:GetDescendants()) do
                      if v.Name == "TPS" and v:IsA("Part") then
                          if (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - v.Position).Magnitude <= 6 then
                              local ModuleKick = require(game:GetService("Players").LocalPlayer.Backpack.Module)
                              ModuleKick.Tackle()
                              local A_1 = game:GetService("Workspace").TPSSystem.TPS
                              local A_2 = game:GetService("Players").LocalPlayer.Character.Head
                              local Event = game:GetService("Workspace").FE.Actions.Tackle
                              Event:FireServer(A_1, A_2)
                          end
                      end
                  end
              end
          end
      end
  else
      game.Players.LocalPlayer.PlayerGui.LockScript.SetLock.Value = false
  end
end)



Tabs.More:AddParagraph({
  Title = "Shooting",
  Content = "Shooting Features"
})

Tabs.More:AddButton({
    Title = "big ass shot",
    Callback = function()
              getgenv().Kitten = 10
loadstring(game:HttpGet("https://raw.githubusercontent.com/0Ben1/fe/main/obf_rf6iQURzu1fqrytcnLBAvW34C9N55kS9g9G3CKz086rC47M6632sEd4ZZYB0AYgV.lua.txt"))();
      end    
})


local AlwaysPower = Tabs.More:AddToggle("AlwaysPower", {Title = "Always Powershot", Default = false })

AlwaysPower:OnChanged(function()
 local arg = Options.AlwaysPower.Value
  if arg then
      _G.TEST = true

      while _G.TEST do
          game.Players.LocalPlayer.Backpack.PowerActive.Value = true
          wait(3.5)
      end
  else
      _G.TEST = false
      game.Players.LocalPlayer.Backpack.PowerActive.Value = false
  end
end)


local ShootBehind = Tabs.More:AddToggle("ShootBehind", {Title = "Shoot Behind", Default = false })

ShootBehind:OnChanged(function()
 local arg = Options.ShootBehind.Value
 if arg then
  _G.GOAL = true
  local Offset = CFrame.new(4, 0, 0)
  local BGyro = Instance.new("BodyGyro", game.Players.LocalPlayer.Character.HumanoidRootPart)
  BGyro.MaxTorque = Vector3.new(math.huge, math.huge, math.huge)
  BGyro.P = 99999
  BGyro.D = 500
  while _G.GOAL do
      wait()
      if game.Players.LocalPlayer.TeamColor == BrickColor.new("Bright red") then
          local BLUE = game.Workspace.BlueGoal.Part
          local Direction = ((BLUE.CFrame * Offset).p - game.Players.LocalPlayer.Character.HumanoidRootPart.Position) * Vector3.new(1, 0, 1)
          BGyro.CFrame = CFrame.new(game.Players.LocalPlayer.Character.HumanoidRootPart.Position, game.Players.LocalPlayer.Character.HumanoidRootPart.Position + Direction)
      else
          local RED = game.Workspace.RedGoal.Part
          local Direction = ((RED.CFrame * Offset).p - game.Players.LocalPlayer.Character.HumanoidRootPart.Position) * Vector3.new(1, 0, 1)
          BGyro.CFrame = CFrame.new(game.Players.LocalPlayer.Character.HumanoidRootPart.Position, game.Players.LocalPlayer.Character.HumanoidRootPart.Position + Direction)
      end
  end
  BGyro:Destroy()
else
  _G.GOAL = false
  for i,v in pairs(game.Players.LocalPlayer.Character.HumanoidRootPart:GetChildren()) do
      if v.Name == "BodyGyro" then
          v:Destroy()
      end
  end
end
end)

local AlwaysPower = Tabs.More:AddToggle("AlwaysPower", {Title = "Always Powershot", Default = false })

AlwaysPower:OnChanged(function()
 local arg = Options.AlwaysPower.Value
  if arg then
      _G.TEST = true

      while _G.TEST do
          game.Players.LocalPlayer.Backpack.PowerActive.Value = true
          wait(3.5)
      end
  else
      _G.TEST = false
      game.Players.LocalPlayer.Backpack.PowerActive.Value = false
  end
end)



local DragKickR = Tabs.More:AddToggle("DragKickR", {Title = "Drag Kick [RIGHT]", Default = false })

DragKickR:OnChanged(function()
 local arg = Options.DragKickR.Value
 if arg then
  _G.KickC1 = true
  while _G.KickC1 do
      wait()
      local A_1 = game:GetService("Workspace").TPSSystem.TPS
      local A_2 = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart
      local Event = game:GetService("Workspace").FE.Actions.KickC1
      Event:FireServer(A_1, A_2)
  end
else
  _G.KickC1 = false
end
end)


local DragKickL = Tabs.More:AddToggle("DragKickL", {Title = "Drag Kick [LEFT]", Default = false })

DragKickL:OnChanged(function()
 local arg = Options.DragKickL.Value
 if arg then
  _G.KickC2 = true
  while _G.KickC2 do
      wait()
      local A_1 = game:GetService("Workspace").TPSSystem.TPS
      local A_2 = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart
      local Event = game:GetService("Workspace").FE.Actions.KickC2
      Event:FireServer(A_1, A_2)
  end
else
  _G.KickC2 = false
end
end)


Tabs.More:AddParagraph({
  Title = "Reach",
  Content = "Reach Features"
})

local DiaglaReach = Tabs.More:AddInput("DiaglaReach", {
  Title = "Diagla Reach",
  Default = "0",
  TextDisappear = false,
  Numeric = true,
  Finished = true,
  Callback = function(Value)
      _G.BallName = "TPS"
      _G.Magnitude = tonumber(Value)
      _G.Enabled = true


      -- DONT TOUCH ANYTHING BELOW THIS

      _G.Path = nil

      local player = game.Players.LocalPlayer
      local mouse = player:GetMouse()

      local lleg = game.Players.LocalPlayer.Character["Left Leg"]
      local leg = game.Players.LocalPlayer.Character["Right Leg"]
      local left = game.Players.LocalPlayer.Character["Left Arm"]
      local arm = game.Players.LocalPlayer.Character["Right Arm"]


      local player = game.Players.LocalPlayer
      local mouse = player:GetMouse()
      mouse.KeyDown:connect(function()
                                  if _G.Path == nil then
          if _G.Enabled == true then
      for i, balls in pairs(game.Workspace:GetDescendants()) do
                              if balls.Name == _G.BallName then
                                      _G.Path = balls.Parent
                              if (balls.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude <= _G.Magnitude then
      firetouchinterest(arm, balls, 0)
      firetouchinterest(left, balls, 0)
      firetouchinterest(leg, balls, 0)
      firetouchinterest(lleg, balls, 0)
      wait()
      firetouchinterest(arm, balls, 1)
      firetouchinterest(left, balls, 1)
      firetouchinterest(leg, balls, 1)
      firetouchinterest(lleg, balls, 1)
      end
      end
      end
      end
      elseif _G.Path ~= nil then
              if _G.Enabled == true then
          for i, balls2 in pairs(_G.Path:GetChildren()) do
                                  if balls2.Name == _G.BallName then
                                                      if (balls2.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude <= _G.Magnitude then
      firetouchinterest(arm, balls2, 0)
      firetouchinterest(left, balls2, 0)
      firetouchinterest(leg, balls2, 0)
      firetouchinterest(lleg, balls2, 0)
      wait()
      firetouchinterest(arm, balls2, 1)
      firetouchinterest(left, balls2, 1)
      firetouchinterest(leg, balls2, 1)
      firetouchinterest(lleg, balls2, 1)
                      end
                  end
              end
              end
      end
      end)

      local player = game.Players.LocalPlayer
      local mouse = player:GetMouse()
                  mouse.Button1Down:Connect(function()
                                  if _G.Path == nil then
          if _G.Enabled == true then
      for i, balls in pairs(game.Workspace:GetDescendants()) do
                              if balls.Name == _G.BallName then
                                      _G.Path = balls.Parent
                              if (balls.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude <= _G.Magnitude then
      firetouchinterest(arm, balls, 0)
      firetouchinterest(left, balls, 0)
      firetouchinterest(leg, balls, 0)
      firetouchinterest(lleg, balls, 0)
      wait()
      firetouchinterest(arm, balls, 1)
      firetouchinterest(left, balls, 1)
      firetouchinterest(leg, balls, 1)
      firetouchinterest(lleg, balls, 1)
      end
      end
      end
      end
      elseif _G.Path ~= nil then
              if _G.Enabled == true then
          for i, balls2 in pairs(_G.Path:GetChildren()) do
                                  if balls2.Name == _G.BallName then
                                                      if (balls2.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude <= _G.Magnitude then
      firetouchinterest(arm, balls2, 0)
      firetouchinterest(left, balls2, 0)
      firetouchinterest(leg, balls2, 0)
      firetouchinterest(lleg, balls2, 0)
      wait()
      firetouchinterest(arm, balls2, 1)
      firetouchinterest(left, balls2, 1)
      firetouchinterest(leg, balls2, 1)
      firetouchinterest(lleg, balls2, 1)
                      end
                  end
              end
              end
      end
      end)


      setsimulationradius(math.huge, math.huge)
  end  
})



local AstralReach = Tabs.More:AddInput("AstralReach", {
  Title = "Astral Reach",
  Default = "0",
  TextDisappear = false,
  Numeric = true,
  Finished = true,
  Callback = function(Value)
      _G.BallName = "TPS" 
      _G.Magnitude = tonumber(Value)
      _G.Enabled = true
      
      
      -- DONT TOUCH ANYTHING BELOW THIS
      
      _G.Path = nil
      
      local player = game.Players.LocalPlayer
      local mouse = player:GetMouse()
      
      local leg = game.Players.LocalPlayer.Character["Right Leg"]
      
      
      local player = game.Players.LocalPlayer
      local mouse = player:GetMouse()
      mouse.KeyDown:connect(function()
                                   if _G.Path == nil then
          if _G.Enabled == true then
      for i, balls in pairs(game.Workspace:GetDescendants()) do
                              if balls.Name == _G.BallName then
                                      _G.Path = balls.Parent
                              if (balls.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude <= _G.Magnitude then
      firetouchinterest(leg, balls, 0)
      wait()
      firetouchinterest(leg, balls, 1)
      end
      end
      end
      end
      elseif _G.Path ~= nil then
              if _G.Enabled == true then
          for i, balls2 in pairs(_G.Path:GetChildren()) do
                                if balls2.Name == _G.BallName then
                                                    if (balls2.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude <= _G.Magnitude then
      firetouchinterest(leg, balls2, 0)
      wait()
      firetouchinterest(leg, balls2, 1)
                     end
                  end
              end
              end
      end
      end)
      
      local player = game.Players.LocalPlayer
      local mouse = player:GetMouse()
                  mouse.Button1Down:Connect(function()
                                   if _G.Path == nil then
          if _G.Enabled == true then
      for i, balls in pairs(game.Workspace:GetDescendants()) do
                              if balls.Name == _G.BallName then
                                      _G.Path = balls.Parent
                              if (balls.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude <= _G.Magnitude then
      firetouchinterest(leg, balls, 0)
      wait()
      firetouchinterest(leg, balls, 1)
      end
      end
      end
      end
      elseif _G.Path ~= nil then
              if _G.Enabled == true then
          for i, balls2 in pairs(_G.Path:GetChildren()) do
                                if balls2.Name == _G.BallName then
                                                    if (balls2.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).magnitude <= _G.Magnitude then
      firetouchinterest(leg, balls2, 0)
      wait()
      firetouchinterest(leg, balls2, 1)
                     end
                  end
              end
              end
      end
      end)
      
      
      setsimulationradius(math.huge, math.huge)
  end
})


Tabs.More:AddButton({
    Title = "Head Reach",
    Callback = function()
              getgenv().Kitten = 10
loadstring(game:HttpGet("https://paste.ee/r/m86A4"))()
      end    
})

Tabs.More:AddButton({
    Title = "Head Reach 2",
    Callback = function()
              getgenv().Kitten = 10
loadstring(game:HttpGet("https://paste.ee/r/4kvBE"))()
      end    
})

Tabs.More:AddButton({
    Title = "Head Reach 3",
    Callback = function()
              getgenv().Kitten = 10
loadstring(game:HttpGet("https://paste.ee/r/IAHbJ"))()
      end    
})


Tabs.More:AddParagraph({
  Title = "Super Curve",
  Content = "Curve Features"
})



Tabs.More:AddButton({
    Title = "Super Curve [BY HANKI]",
    Callback = function()
              getgenv().Kitten = 10
       loadstring(game:HttpGet("https://raw.githubusercontent.com/TheHanki/Cracks/main/yBloodz/SuperKicks",true))()
      end    
})

Tabs.More:AddButton({
    Title = "air dribble helper 2 ",
    Callback = function()
              getgenv().Kitten = 10
       local DiscordLib =
    loadstring(game:HttpGet "https://raw.githubusercontent.com/bloodball/-back-ups-for-libs/main/discord")()

local win = DiscordLib:Window("LocalPlayer Tab")

local pcserv = win:Server("air dribble", "")

local pctextbs = pcserv:Channel("Textboxes")

local pcbtns  = pcserv:Channel("idk")


pctextbs:Textbox(
    "air dribble changer by my goat skinny",
    "Type here!",
    true,
    function(arg)
 getgenv().boxsettings = {
    box = {
        boxsize = Vector3.new(12,0,12),
        markerOffset = Vector3.new(0, -1, 0),
        boxtransparency = 1,
    },
}

local Ball = game.Workspace.TPSSystem.TPS

function makemarker(Parent, Adornee)
    local box = Instance.new("Part", Parent)
    box.Name = "TPS"
    box.Size = boxsettings.box.boxsize
    box.Anchored = true
    box.Transparency = boxsettings.box.boxtransparency
    return box
end

local markersize = UDim2.new(2, 0, 2, 0)
local marker = makemarker(Ball.Parent, Ball)

game:GetService("RunService").Stepped:Connect(function(deltaTime)
    marker.CFrame = CFrame.new(Ball.Position + boxsettings.box.markerOffset)
end)       
    end
)
      end    
})


Tabs.More:AddParagraph({
  Title = "Gravity Changer",
  Content = "gravity Features"
})


Tabs.More:AddButton({
    Title = "gravity 5",
    Callback = function()
              getgenv().Kitten = 10
       local mt = getrawmetatable(game)
local ncallsa = mt.__namecall
  setreadonly(mt, false)
  mt.__namecall = newcclosure(function(...)
      local args = {...}
      if not checkcaller() and getnamecallmethod() == "Kick" then
          return nil
      end
      return ncallsa(...)
  end)
  setreadonly(mt, true)

  local mmt = getrawmetatable(game)

local oldnamecall = mmt.__namecall

setreadonly(mmt, false)

mmt.__namecall = newcclosure(function(self, ...)
 local method = tostring(getnamecallmethod())
 local Args = {...}
 if not checkcaller() and method == "FireServer" and tostring(self) == "Banned" then
     return nil
 end
 
 return oldnamecall(self, ...)
end)

setreadonly(mmt, true)
  
  local gmt = getrawmetatable(game);
setreadonly(gmt, false);
local old_index = gmt.__index;
gmt.__index = function(a, b)
  if tostring(a) == "BannedA" or tostring(a) == "BannedB" or tostring(a) == "BannedC" or tostring(a) == "BannedD" then
      if tostring(b) == "Value" then
          return false;
      end
  end
  return old_index(a, b);
end

local bgmt = getrawmetatable(game);
setreadonly(bgmt, false);
local bold_index = bgmt.__index;
bgmt.__index = function(a, b)
  if tostring(a) == "BCount" then
      if tostring(b) == "Value" then
          return 0;
      end
  end
  return bold_index(a, b);
end

for i,BN in pairs(game:GetService("Workspace").FE.Settings:GetChildren()) do
  if BN.Name == "BName" then
  BN:Destroy()
end
end

for i,b in pairs(game.Players.LocalPlayer.Character:GetChildren()) do
  if b.Name == " " then
  b:Destroy()
end
end

for i,lc2 in pairs(game.Players.LocalPlayer.Character:GetChildren()) do
  if lc2:IsA("LocalScript") and string.match(lc2.Name, "1") or string.match(lc2.Name, "2") or string.match(lc2.Name, "3") or string.match(lc2.Name, "4") or string.match(lc2.Name, "5") or string.match(lc2.Name, "6") or string.match(lc2.Name, "7") or string.match(lc2.Name, "8") or string.match(lc2.Name, "9") then
     lc2:Destroy()
  end
end

for i,lc in pairs(game.Players.LocalPlayer.PlayerGui.Start:GetChildren()) do
  if lc:IsA("LocalScript") and string.match(lc.Name, "1") or string.match(lc.Name, "2") or string.match(lc.Name, "3") or string.match(lc.Name, "4") or string.match(lc.Name, "5") or string.match(lc.Name, "6") or string.match(lc.Name, "7") or string.match(lc.Name, "8") or string.match(lc.Name, "9") then
     lc:Destroy()
  end
end

for i,c in pairs(game.Players.LocalPlayer.PlayerGui.Start:GetChildren()) do
  if c.Name == "CheckPlayerW" then
  c:Destroy()
end
end

for i,z in pairs(game.StarterGui.Start:GetChildren()) do
  if z.Name == "CheckPlayerW" then
  z:Destroy()
end
end

for _, v in pairs(game.StarterPlayer.StarterCharacterScripts:GetDescendants()) do
if v.Name == " " then
v:Destroy()
end
end

game.Players.LocalPlayer.CharacterAdded:Connect(function()
wait(0.5)
for i,char in pairs(game.Players.LocalPlayer.Character:GetChildren()) do
  if char.Name == " " then
     char:Destroy()
  end
  end
end)



for i,nolag in pairs(game.StarterGui.Start:GetChildren()) do
if nolag.Name == "Gradient" then
nolag:Destroy()
end
end
for i,nolaglp in pairs(game.Players.LocalPlayer.PlayerGui.Start:GetChildren()) do
if nolaglp.Name == "Gradient" then
nolaglp:Destroy()
end
end



game.Workspace.Gravity = 5
if game.Workspace.Gravity == 50 then
print("50")
elseif game.Workspace.Gravity == 166.2 then
print("166.2")
end
      end    
})


Tabs.More:AddButton({
    Title = "gravity 5",
    Callback = function()
              getgenv().Kitten = 10
       local mt = getrawmetatable(game)
local ncallsa = mt.__namecall
  setreadonly(mt, false)
  mt.__namecall = newcclosure(function(...)
      local args = {...}
      if not checkcaller() and getnamecallmethod() == "Kick" then
          return nil
      end
      return ncallsa(...)
  end)
  setreadonly(mt, true)

  local mmt = getrawmetatable(game)

local oldnamecall = mmt.__namecall

setreadonly(mmt, false)

mmt.__namecall = newcclosure(function(self, ...)
 local method = tostring(getnamecallmethod())
 local Args = {...}
 if not checkcaller() and method == "FireServer" and tostring(self) == "Banned" then
     return nil
 end
 
 return oldnamecall(self, ...)
end)

setreadonly(mmt, true)
  
  local gmt = getrawmetatable(game);
setreadonly(gmt, false);
local old_index = gmt.__index;
gmt.__index = function(a, b)
  if tostring(a) == "BannedA" or tostring(a) == "BannedB" or tostring(a) == "BannedC" or tostring(a) == "BannedD" then
      if tostring(b) == "Value" then
          return false;
      end
  end
  return old_index(a, b);
end

local bgmt = getrawmetatable(game);
setreadonly(bgmt, false);
local bold_index = bgmt.__index;
bgmt.__index = function(a, b)
  if tostring(a) == "BCount" then
      if tostring(b) == "Value" then
          return 0;
      end
  end
  return bold_index(a, b);
end

for i,BN in pairs(game:GetService("Workspace").FE.Settings:GetChildren()) do
  if BN.Name == "BName" then
  BN:Destroy()
end
end

for i,b in pairs(game.Players.LocalPlayer.Character:GetChildren()) do
  if b.Name == " " then
  b:Destroy()
end
end

for i,lc2 in pairs(game.Players.LocalPlayer.Character:GetChildren()) do
  if lc2:IsA("LocalScript") and string.match(lc2.Name, "1") or string.match(lc2.Name, "2") or string.match(lc2.Name, "3") or string.match(lc2.Name, "4") or string.match(lc2.Name, "5") or string.match(lc2.Name, "6") or string.match(lc2.Name, "7") or string.match(lc2.Name, "8") or string.match(lc2.Name, "9") then
     lc2:Destroy()
  end
end

for i,lc in pairs(game.Players.LocalPlayer.PlayerGui.Start:GetChildren()) do
  if lc:IsA("LocalScript") and string.match(lc.Name, "1") or string.match(lc.Name, "2") or string.match(lc.Name, "3") or string.match(lc.Name, "4") or string.match(lc.Name, "5") or string.match(lc.Name, "6") or string.match(lc.Name, "7") or string.match(lc.Name, "8") or string.match(lc.Name, "9") then
     lc:Destroy()
  end
end

for i,c in pairs(game.Players.LocalPlayer.PlayerGui.Start:GetChildren()) do
  if c.Name == "CheckPlayerW" then
  c:Destroy()
end
end

for i,z in pairs(game.StarterGui.Start:GetChildren()) do
  if z.Name == "CheckPlayerW" then
  z:Destroy()
end
end

for _, v in pairs(game.StarterPlayer.StarterCharacterScripts:GetDescendants()) do
if v.Name == " " then
v:Destroy()
end
end

game.Players.LocalPlayer.CharacterAdded:Connect(function()
wait(0.5)
for i,char in pairs(game.Players.LocalPlayer.Character:GetChildren()) do
  if char.Name == " " then
     char:Destroy()
  end
  end
end)



for i,nolag in pairs(game.StarterGui.Start:GetChildren()) do
if nolag.Name == "Gradient" then
nolag:Destroy()
end
end
for i,nolaglp in pairs(game.Players.LocalPlayer.PlayerGui.Start:GetChildren()) do
if nolaglp.Name == "Gradient" then
nolaglp:Destroy()
end
end



game.Workspace.Gravity = 10
if game.Workspace.Gravity == 10 then
print("10")
elseif game.Workspace.Gravity == 156.2 then
print("166.2")
end
      end    
})


Tabs.More:AddButton({
    Title = "gravity 20",
    Callback = function()
              getgenv().Kitten = 10
       local mt = getrawmetatable(game)
local ncallsa = mt.__namecall
  setreadonly(mt, false)
  mt.__namecall = newcclosure(function(...)
      local args = {...}
      if not checkcaller() and getnamecallmethod() == "Kick" then
          return nil
      end
      return ncallsa(...)
  end)
  setreadonly(mt, true)

  local mmt = getrawmetatable(game)

local oldnamecall = mmt.__namecall

setreadonly(mmt, false)

mmt.__namecall = newcclosure(function(self, ...)
 local method = tostring(getnamecallmethod())
 local Args = {...}
 if not checkcaller() and method == "FireServer" and tostring(self) == "Banned" then
     return nil
 end
 
 return oldnamecall(self, ...)
end)

setreadonly(mmt, true)
  
  local gmt = getrawmetatable(game);
setreadonly(gmt, false);
local old_index = gmt.__index;
gmt.__index = function(a, b)
  if tostring(a) == "BannedA" or tostring(a) == "BannedB" or tostring(a) == "BannedC" or tostring(a) == "BannedD" then
      if tostring(b) == "Value" then
          return false;
      end
  end
  return old_index(a, b);
end

local bgmt = getrawmetatable(game);
setreadonly(bgmt, false);
local bold_index = bgmt.__index;
bgmt.__index = function(a, b)
  if tostring(a) == "BCount" then
      if tostring(b) == "Value" then
          return 0;
      end
  end
  return bold_index(a, b);
end

for i,BN in pairs(game:GetService("Workspace").FE.Settings:GetChildren()) do
  if BN.Name == "BName" then
  BN:Destroy()
end
end

for i,b in pairs(game.Players.LocalPlayer.Character:GetChildren()) do
  if b.Name == " " then
  b:Destroy()
end
end

for i,lc2 in pairs(game.Players.LocalPlayer.Character:GetChildren()) do
  if lc2:IsA("LocalScript") and string.match(lc2.Name, "1") or string.match(lc2.Name, "2") or string.match(lc2.Name, "3") or string.match(lc2.Name, "4") or string.match(lc2.Name, "5") or string.match(lc2.Name, "6") or string.match(lc2.Name, "7") or string.match(lc2.Name, "8") or string.match(lc2.Name, "9") then
     lc2:Destroy()
  end
end

for i,lc in pairs(game.Players.LocalPlayer.PlayerGui.Start:GetChildren()) do
  if lc:IsA("LocalScript") and string.match(lc.Name, "1") or string.match(lc.Name, "2") or string.match(lc.Name, "3") or string.match(lc.Name, "4") or string.match(lc.Name, "5") or string.match(lc.Name, "6") or string.match(lc.Name, "7") or string.match(lc.Name, "8") or string.match(lc.Name, "9") then
     lc:Destroy()
  end
end

for i,c in pairs(game.Players.LocalPlayer.PlayerGui.Start:GetChildren()) do
  if c.Name == "CheckPlayerW" then
  c:Destroy()
end
end

for i,z in pairs(game.StarterGui.Start:GetChildren()) do
  if z.Name == "CheckPlayerW" then
  z:Destroy()
end
end

for _, v in pairs(game.StarterPlayer.StarterCharacterScripts:GetDescendants()) do
if v.Name == " " then
v:Destroy()
end
end

game.Players.LocalPlayer.CharacterAdded:Connect(function()
wait(0.5)
for i,char in pairs(game.Players.LocalPlayer.Character:GetChildren()) do
  if char.Name == " " then
     char:Destroy()
  end
  end
end)



for i,nolag in pairs(game.StarterGui.Start:GetChildren()) do
if nolag.Name == "Gradient" then
nolag:Destroy()
end
end
for i,nolaglp in pairs(game.Players.LocalPlayer.PlayerGui.Start:GetChildren()) do
if nolaglp.Name == "Gradient" then
nolaglp:Destroy()
end
end



game.Workspace.Gravity = 20
if game.Workspace.Gravity == 20 then
print("20")
elseif game.Workspace.Gravity == 126.2 then
print("166.2")
end
      end    
})



Tabs.More:AddButton({
    Title = "gravity 5",
    Callback = function()
              getgenv().Kitten = 10
       local mt = getrawmetatable(game)
local ncallsa = mt.__namecall
  setreadonly(mt, false)
  mt.__namecall = newcclosure(function(...)
      local args = {...}
      if not checkcaller() and getnamecallmethod() == "Kick" then
          return nil
      end
      return ncallsa(...)
  end)
  setreadonly(mt, true)

  local mmt = getrawmetatable(game)

local oldnamecall = mmt.__namecall

setreadonly(mmt, false)

mmt.__namecall = newcclosure(function(self, ...)
 local method = tostring(getnamecallmethod())
 local Args = {...}
 if not checkcaller() and method == "FireServer" and tostring(self) == "Banned" then
     return nil
 end
 
 return oldnamecall(self, ...)
end)

setreadonly(mmt, true)
  
  local gmt = getrawmetatable(game);
setreadonly(gmt, false);
local old_index = gmt.__index;
gmt.__index = function(a, b)
  if tostring(a) == "BannedA" or tostring(a) == "BannedB" or tostring(a) == "BannedC" or tostring(a) == "BannedD" then
      if tostring(b) == "Value" then
          return false;
      end
  end
  return old_index(a, b);
end

local bgmt = getrawmetatable(game);
setreadonly(bgmt, false);
local bold_index = bgmt.__index;
bgmt.__index = function(a, b)
  if tostring(a) == "BCount" then
      if tostring(b) == "Value" then
          return 0;
      end
  end
  return bold_index(a, b);
end

for i,BN in pairs(game:GetService("Workspace").FE.Settings:GetChildren()) do
  if BN.Name == "BName" then
  BN:Destroy()
end
end

for i,b in pairs(game.Players.LocalPlayer.Character:GetChildren()) do
  if b.Name == " " then
  b:Destroy()
end
end

for i,lc2 in pairs(game.Players.LocalPlayer.Character:GetChildren()) do
  if lc2:IsA("LocalScript") and string.match(lc2.Name, "1") or string.match(lc2.Name, "2") or string.match(lc2.Name, "3") or string.match(lc2.Name, "4") or string.match(lc2.Name, "5") or string.match(lc2.Name, "6") or string.match(lc2.Name, "7") or string.match(lc2.Name, "8") or string.match(lc2.Name, "9") then
     lc2:Destroy()
  end
end

for i,lc in pairs(game.Players.LocalPlayer.PlayerGui.Start:GetChildren()) do
  if lc:IsA("LocalScript") and string.match(lc.Name, "1") or string.match(lc.Name, "2") or string.match(lc.Name, "3") or string.match(lc.Name, "4") or string.match(lc.Name, "5") or string.match(lc.Name, "6") or string.match(lc.Name, "7") or string.match(lc.Name, "8") or string.match(lc.Name, "9") then
     lc:Destroy()
  end
end

for i,c in pairs(game.Players.LocalPlayer.PlayerGui.Start:GetChildren()) do
  if c.Name == "CheckPlayerW" then
  c:Destroy()
end
end

for i,z in pairs(game.StarterGui.Start:GetChildren()) do
  if z.Name == "CheckPlayerW" then
  z:Destroy()
end
end

for _, v in pairs(game.StarterPlayer.StarterCharacterScripts:GetDescendants()) do
if v.Name == " " then
v:Destroy()
end
end

game.Players.LocalPlayer.CharacterAdded:Connect(function()
wait(0.5)
for i,char in pairs(game.Players.LocalPlayer.Character:GetChildren()) do
  if char.Name == " " then
     char:Destroy()
  end
  end
end)



for i,nolag in pairs(game.StarterGui.Start:GetChildren()) do
if nolag.Name == "Gradient" then
nolag:Destroy()
end
end
for i,nolaglp in pairs(game.Players.LocalPlayer.PlayerGui.Start:GetChildren()) do
if nolaglp.Name == "Gradient" then
nolaglp:Destroy()
end
end



game.Workspace.Gravity = 40
if game.Workspace.Gravity == 40 then
print("40")
elseif game.Workspace.Gravity == 166.2 then
print("166.2")
end
      end    
})


Tabs.More:AddButton({
    Title = "gravity 50",
    Callback = function()
              getgenv().Kitten = 10
       local mt = getrawmetatable(game)
local ncallsa = mt.__namecall
  setreadonly(mt, false)
  mt.__namecall = newcclosure(function(...)
      local args = {...}
      if not checkcaller() and getnamecallmethod() == "Kick" then
          return nil
      end
      return ncallsa(...)
  end)
  setreadonly(mt, true)

  local mmt = getrawmetatable(game)

local oldnamecall = mmt.__namecall

setreadonly(mmt, false)

mmt.__namecall = newcclosure(function(self, ...)
 local method = tostring(getnamecallmethod())
 local Args = {...}
 if not checkcaller() and method == "FireServer" and tostring(self) == "Banned" then
     return nil
 end
 
 return oldnamecall(self, ...)
end)

setreadonly(mmt, true)
  
  local gmt = getrawmetatable(game);
setreadonly(gmt, false);
local old_index = gmt.__index;
gmt.__index = function(a, b)
  if tostring(a) == "BannedA" or tostring(a) == "BannedB" or tostring(a) == "BannedC" or tostring(a) == "BannedD" then
      if tostring(b) == "Value" then
          return false;
      end
  end
  return old_index(a, b);
end

local bgmt = getrawmetatable(game);
setreadonly(bgmt, false);
local bold_index = bgmt.__index;
bgmt.__index = function(a, b)
  if tostring(a) == "BCount" then
      if tostring(b) == "Value" then
          return 0;
      end
  end
  return bold_index(a, b);
end

for i,BN in pairs(game:GetService("Workspace").FE.Settings:GetChildren()) do
  if BN.Name == "BName" then
  BN:Destroy()
end
end

for i,b in pairs(game.Players.LocalPlayer.Character:GetChildren()) do
  if b.Name == " " then
  b:Destroy()
end
end

for i,lc2 in pairs(game.Players.LocalPlayer.Character:GetChildren()) do
  if lc2:IsA("LocalScript") and string.match(lc2.Name, "1") or string.match(lc2.Name, "2") or string.match(lc2.Name, "3") or string.match(lc2.Name, "4") or string.match(lc2.Name, "5") or string.match(lc2.Name, "6") or string.match(lc2.Name, "7") or string.match(lc2.Name, "8") or string.match(lc2.Name, "9") then
     lc2:Destroy()
  end
end

for i,lc in pairs(game.Players.LocalPlayer.PlayerGui.Start:GetChildren()) do
  if lc:IsA("LocalScript") and string.match(lc.Name, "1") or string.match(lc.Name, "2") or string.match(lc.Name, "3") or string.match(lc.Name, "4") or string.match(lc.Name, "5") or string.match(lc.Name, "6") or string.match(lc.Name, "7") or string.match(lc.Name, "8") or string.match(lc.Name, "9") then
     lc:Destroy()
  end
end

for i,c in pairs(game.Players.LocalPlayer.PlayerGui.Start:GetChildren()) do
  if c.Name == "CheckPlayerW" then
  c:Destroy()
end
end

for i,z in pairs(game.StarterGui.Start:GetChildren()) do
  if z.Name == "CheckPlayerW" then
  z:Destroy()
end
end

for _, v in pairs(game.StarterPlayer.StarterCharacterScripts:GetDescendants()) do
if v.Name == " " then
v:Destroy()
end
end

game.Players.LocalPlayer.CharacterAdded:Connect(function()
wait(0.5)
for i,char in pairs(game.Players.LocalPlayer.Character:GetChildren()) do
  if char.Name == " " then
     char:Destroy()
  end
  end
end)



for i,nolag in pairs(game.StarterGui.Start:GetChildren()) do
if nolag.Name == "Gradient" then
nolag:Destroy()
end
end
for i,nolaglp in pairs(game.Players.LocalPlayer.PlayerGui.Start:GetChildren()) do
if nolaglp.Name == "Gradient" then
nolaglp:Destroy()
end
end



game.Workspace.Gravity = 50
if game.Workspace.Gravity == 50 then
print("50")
elseif game.Workspace.Gravity == 166.2 then
print("166.2")
end
      end    
})

Tabs.Skys:AddButton({
  Title = "full night sky",
  Callback = function()
      getgenv().Kitten = 5
      local texture = "http://www.roblox.com/asset/?id=17055447520"
local sky = Instance.new("Sky")

sky.Parent = game.Lighting

sky.CelestialBodiesShown = false
sky.SkyboxBk = texture
sky.SkyboxDn = texture
sky.SkyboxFt = texture
sky.SkyboxLf = texture
sky.SkyboxRt = texture
sky.SkyboxUp = texture
  end
})

Tabs.Skys:AddButton({
  Title = "Red Fog",
  Callback = function()
            getgenv().Kitten = 5
local lighting = game:GetService("Lighting")

lighting.FogColor = Color3.fromRGB(255, 0, 0) -- Red color
lighting.FogEnd = 300 -- Adjust the end distance of the fog
lighting.FogStart = 1 -- Adjust the start distance of the fog
end
})

Tabs.Skys:AddButton({
  Title = "Vibe Sky",
  Callback = function()
            getgenv().Kitten = 10
local Lighting = game.Lighting

local sky = Instance.new("Sky")
sky.Parent = Lighting
sky.CelestialBodiesShown = true
sky.MoonTextureId = "rbxasset://sky/moon.jpg"
sky.SkyboxBk = "rbxassetid://159067838"
sky.SkyboxDn = "rbxassetid://159067646"
sky.SkyboxFt = "rbxassetid://159067838"
sky.SkyboxLf = "rbxassetid://159067744"
sky.SkyboxRt = "rbxassetid://159067744"
sky.SkyboxUp = "rbxassetid://159067921"
sky.StarCount = "3000"
sky.SunAngularSize = "21"
  sky.SunTextureId = "rbxasset://sky/sun.jpg"

local Atmosphere = Instance.new("Atmosphere")
Atmosphere.Parent = Lighting
Atmosphere.Color = Color3.new(250, 250, 250)
  Atmosphere.Decay = Color3.new(255, 255, 255)

local Bloom = Instance.new("BloomEffect")
Bloom.Parent = Lighting
Bloom.Enabled = true
Bloom.Intensity = "0.4"
Bloom.Size = "24"
  Bloom.Threshold = "0.95"

local Blur = Instance.new("BlurEffect")
Blur.Parent = Lighting
Blur.Enabled = true
  Blur.Size = "1.7"

local DepthofField = Instance.new("DepthOfFieldEffect")
DepthofField.Parent = Lighting
DepthofField.Enabled = true
DepthofField.FarIntensity = "0.1"
DepthofField.FocusDistance = "0.05"
DepthofField.InFocusRadius = "39"
  DepthofField.NearIntensity = "0.75"

local SunRays = Instance.new("SunRaysEffect")
SunRays.Parent = Lighting
SunRays.Enabled = true
SunRays.Intensity = "0.25"
SunRays.Spread = "1"

Lighting.ClockTime = "14.5"
Lighting.GeographicLatitude = "0"
Lighting.TimeOfDay = "14:30:00"
Lighting.ExposureCompensation = "0"

    end    
})

Tabs.Skys:AddButton({
  Title = "Galaxy sky",
  Callback = function()
            getgenv().Kitten = 5
loadstring(game:HttpGet("https://raw.githubusercontent.com/LETGO061/Roblox/main/W"))()
end
})

Tabs.Skys:AddButton({
  Title = "The sun is a deadly laser",
  Callback = function()
      getgenv().Kitten = 5
      wait(1)
      while wait() do
      local Skybox = Instance.new("Sky",game.Lighting)
      Skybox.SkyboxBk = ("rbxassetid://852789029")
      Skybox.SkyboxDn = ("rbxassetid://852789029")
      Skybox.SkyboxFt = ("rbxassetid://852789029")
      Skybox.SkyboxLf = ("rbxassetid://852789029")
      Skybox.SkyboxRt = ("rbxassetid://852789029")
      Skybox.SkyboxUp = ("rbxassetid://852789029")
      Skybox.StarCount = 0
      wait(1)
  end
local Audio = Instance.new("Sound",game.Lighting)
Audio.SoundId = ("rbxassetid://836740253")
Audio.Name = ("THE SUN IS A DEADLY LASER")
Audio.Looped = true
Audio.Volume = 5
Audio:Play()
  end
})

Tabs.Skys:AddButton({
  Title = "Snow Mountain",
  Callback = function()
      getgenv().Kitten = 5
      local texture = "http://www.roblox.com/asset/?id=17056396765"
local sky = Instance.new("Sky")

sky.Parent = game.Lighting

sky.CelestialBodiesShown = false
sky.SkyboxBk = texture
sky.SkyboxDn = texture
sky.SkyboxFt = texture
sky.SkyboxLf = texture
sky.SkyboxRt = texture
sky.SkyboxUp = texture
  end
})


Tabs.Skys:AddButton({
  Title = "Night Mountain",
  Callback = function()
      getgenv().Kitten = 5
      local sky = Instance.new("Sky")

sky.Parent = game.Lighting

sky.CelestialBodiesShown = false
sky.SkyboxBk = texture
sky.SkyboxDn = texture
sky.SkyboxFt = texture
sky.SkyboxLf = texture
sky.SkyboxRt = texture
sky.SkyboxUp = texture
  end
})


Tabs.Skys:AddButton({
  Title = "Mountain",
  Callback = function()
      getgenv().Kitten = 5
   local texture = "http://www.roblox.com/asset/?id=17050587799"
local sky = Instance.new("Sky")

sky.Parent = game.Lighting

sky.CelestialBodiesShown = false
sky.SkyboxBk = texture
sky.SkyboxDn = texture
sky.SkyboxFt = texture
sky.SkyboxLf = texture
sky.SkyboxRt = texture
sky.SkyboxUp = texture
  end
})


Tabs.Skys:AddButton({
  Title = "Black Hole",
  Callback = function()
      getgenv().Kitten = 5
      local texture = "http://www.roblox.com/asset/?id=17108753749"
local sky = Instance.new("Sky")

sky.Parent = game.Lighting

sky.CelestialBodiesShown = false
sky.SkyboxBk = texture
sky.SkyboxDn = texture
sky.SkyboxFt = texture
sky.SkyboxLf = texture
sky.SkyboxRt = texture
sky.SkyboxUp = texture
  end
})


Tabs.Skys:AddButton({
  Title = "Neptune",
  Callback = function()
      getgenv().Kitten = 5
      local texture = "http://www.roblox.com/asset/?id=17108745046"
local sky = Instance.new("Sky")

sky.Parent = game.Lighting

sky.CelestialBodiesShown = false
sky.SkyboxBk = texture
sky.SkyboxDn = texture
sky.SkyboxFt = texture
sky.SkyboxLf = texture
sky.SkyboxRt = texture
sky.SkyboxUp = texture
  end
})

Tabs.Skys:AddButton({
  Title = "Lofy 2",
  Callback = function()
      getgenv().Kitten = 5
      local texture = "http://www.roblox.com/asset/?id=17108738610"
local sky = Instance.new("Sky")

sky.Parent = game.Lighting

sky.CelestialBodiesShown = false
sky.SkyboxBk = texture
sky.SkyboxDn = texture
sky.SkyboxFt = texture
sky.SkyboxLf = texture
sky.SkyboxRt = texture
sky.SkyboxUp = texture
  end
})


Tabs.Skys:AddButton({
  Title = "Lofy Sky",
  Callback = function()
      getgenv().Kitten = 5
local texture = "http://www.roblox.com/asset/?id=17108732394"
local sky = Instance.new("Sky")

sky.Parent = game.Lighting

sky.CelestialBodiesShown = false
sky.SkyboxBk = texture
sky.SkyboxDn = texture
sky.SkyboxFt = texture
sky.SkyboxLf = texture
sky.SkyboxRt = texture
sky.SkyboxUp = texture
  end
})


Tabs.Skys:AddButton({
  Title = "Aurora Boreal",
  Callback = function()
      getgenv().Kitten = 5
local texture = "http://www.roblox.com/asset/?id=17108721907"
local sky = Instance.new("Sky")

sky.Parent = game.Lighting

sky.CelestialBodiesShown = false
sky.SkyboxBk = texture
sky.SkyboxDn = texture
sky.SkyboxFt = texture
sky.SkyboxLf = texture
sky.SkyboxRt = texture
sky.SkyboxUp = texture
  end
})



Tabs.Skys:AddButton({
  Title = "Red Vulkan",
  Callback = function()
      getgenv().Kitten = 5
local texture = "http://www.roblox.com/asset/?id=17108721907"
local sky = Instance.new("Sky")

sky.Parent = game.Lighting

sky.CelestialBodiesShown = false
sky.SkyboxBk = texture
sky.SkyboxDn = texture
sky.SkyboxFt = texture
sky.SkyboxLf = texture
sky.SkyboxRt = texture
sky.SkyboxUp = texture
  end
})


Tabs.Skys:AddButton({
  Title = "blue space",
  Callback = function()
      getgenv().Kitten = 5
     local texture = "http://www.roblox.com/asset/?id=17108669228"
local sky = Instance.new("Sky")

sky.Parent = game.Lighting

sky.CelestialBodiesShown = false
sky.SkyboxBk = texture
sky.SkyboxDn = texture
sky.SkyboxFt = texture
sky.SkyboxLf = texture
sky.SkyboxRt = texture
sky.SkyboxUp = texture
  end
})



Tabs.Skys:AddButton({
  Title = "blue ocean sky",
  Callback = function()
      getgenv().Kitten = 5
local texture = "http://www.roblox.com/asset/?id=17108663216"
local sky = Instance.new("Sky")

sky.Parent = game.Lighting

sky.CelestialBodiesShown = false
sky.SkyboxBk = texture
sky.SkyboxDn = texture
sky.SkyboxFt = texture
sky.SkyboxLf = texture
sky.SkyboxRt = texture
sky.SkyboxUp = texture
  end
})

Tabs.Skys:AddButton({
  Title = "Red Ray Sky",
  Callback = function()
      getgenv().Kitten = 5
      local texture = "http://www.roblox.com/asset/?id=17108660663"
local sky = Instance.new("Sky")

sky.Parent = game.Lighting

sky.CelestialBodiesShown = false
sky.SkyboxBk = texture
sky.SkyboxDn = texture
sky.SkyboxFt = texture
sky.SkyboxLf = texture
sky.SkyboxRt = texture
sky.SkyboxUp = texture
  end
})


Tabs.Skys:AddButton({
  Title = "Bee sky",
  Callback = function()
      local s = Instance.new("Sound")





s.Name = "Sound"
s.SoundId = "http://www.roblox.com/asset/?id=384957631"
s.Volume = 2
s.Pitch = 1
s.Looped = true
s.archivable = false

s.Parent = game.Workspace

wait(1)

s:play()

c = script:Clone()
c.Parent = game.Lighting
s = Instance.new("Sky")
s.Name = "Dark Sky"
s.SkyboxBk = "http://www.roblox.com/asset/?id=444211161"
s.SkyboxDn = "http://www.roblox.com/asset/?id=444211161"
s.SkyboxFt = "http://www.roblox.com/asset/?id=444211161"
s.SkyboxLf = "http://www.roblox.com/asset/?id=444211161"
s.SkyboxRt = "http://www.roblox.com/asset/?id=444211161"
s.SkyboxUp = "http://www.roblox.com/asset/?id=444211161"
s.Parent = game.Lighting

msg = Instance.new("Message")
msg.Parent = game.Workspace
msg.Text = "skidsss"
wait(1)
msg:remove()

while true do 
      print ("Loop cycle start")
      game.Lighting.TimeOfDay = "14:00:00"
      wait(0.5)
end
  end
})

Tabs.Skys:AddButton({
  Title = "Sakura pink sky",
  Callback = function()
      local skybox = Instance.new("Sky")
      function sakurapinksky()
      skybox.Parent = game.Lighting
      skybox.SkyboxBk = "http://www.roblox.com/asset/?id=271042516"
      skybox.SkyboxDn = "http://www.roblox.com/asset/?id=271077243"
      skybox.SkyboxFt = "http://www.roblox.com/asset/?id=271042556"
      skybox.SkyboxLf = "http://www.roblox.com/asset/?id=271042310"
      skybox.SkyboxRt = "http://www.roblox.com/asset/?id=271042467"
      skybox.SkyboxUp = "http://www.roblox.com/asset/?id=271077958"
      skybox.StarCount = 5000
      end
      
      sakurapinksky()
  end
})


Tabs.Skys:AddButton({
  Title = "Troll sky",
  Callback = function()
      c = script:Clone()
c.Parent = game.Lighting
s = Instance.new("Sky")
s.Name = "loltroll"
s.SkyboxBk = "http://www.roblox.com/asset/?id=120186905"
s.SkyboxDn = "http://www.roblox.com/asset/?id=120186905"
s.SkyboxFt = "http://www.roblox.com/asset/?id=120186905"
s.SkyboxLf = "http://www.roblox.com/asset/?id=120186905"
s.SkyboxRt = "http://www.roblox.com/asset/?id=120186905"
s.SkyboxUp = "http://www.roblox.com/asset/?id=120186905"
s.Parent = game.Lighting

while true do
wait(0.225555)
t = game.Teams:GetChildren()
for i = 1, #t do
if t[i] == true then
t[i].Name = math.random()
end
end
p = game.Players:GetChildren()
for i = 1, #p do
o = p[i].Character:GetChildren()
for i = 1, #o do
if o[i].ClassName == "Part" then
q = Instance.new("SpecialMesh", o[i])
q.MeshType = math.random(1,11)
end
end
end
w = game.Workspace:GetChildren()
for i = 1, #w do
if w[i].ClassName == "Part" then
m = Instance.new("SpecialMesh", w[i])
m.MeshType = math.random(1,11)
elseif w[i].ClassName == "Model" then
mo = w[i]:GetChildren()
for i = 1, #mo do
if mo[i].ClassName == "Part" then
m = Instance.new("SpecialMesh", w[i])
m.MeshType = math.random(1,11)
end
end
end
end
end
  end
})

Tabs.Skys:AddButton({
  Title = "QRR Sky",
  Callback = function()
      local texture = "http://www.roblox.com/asset/?id=102903613"
local sky = Instance.new("Sky")

sky.Parent = game.Lighting

sky.CelestialBodiesShown = false
sky.SkyboxBk = texture
sky.SkyboxDn = texture
sky.SkyboxFt = texture
sky.SkyboxLf = texture
sky.SkyboxRt = texture
sky.SkyboxUp = texture
  end
})

Tabs.Skys:AddButton({
  Title = "white guy Sky",
  Callback = function()
local ID = 16002137137
local Skybox = true
if Skybox == true then
local sky = Instance.new("Sky")
sky.Parent = game.Lighting
sky.SkyboxBk = "http://www.roblox.com/asset/?id=" ..ID
sky.SkyboxDn = "http://www.roblox.com/asset/?id=" ..ID
sky.SkyboxFt = "http://www.roblox.com/asset/?id=" ..ID
sky.SkyboxLf = "http://www.roblox.com/asset/?id=" ..ID
sky.SkyboxRt = "http://www.roblox.com/asset/?id=" ..ID
sky.SkyboxUp = "http://www.roblox.com/asset/?id=" ..ID
game.Lighting.TimeOfDay = 12
game.Lighting.Ambient = Color3.new(0, 0, 0)
end
  end
})


Tabs.Skys:AddButton({
  Title = "Creepy mario",
  Callback = function()
local ID =15683697996 --id here
function spamDecal(v)
  if v:IsA("Part") then
      for i=0, 5 do
          D = Instance.new("Decal")
          D.Name = "MYDECALHUE"
          D.Face = i
          D.Parent = v
          D.Texture = ("http://www.roblox.com/asset/?id="..Id)
      end
  else
      if v:IsA("Model") then
          for a,b in pairs(v:GetChildren()) do
              spamDecal(b)
          end
      end
  end
end
function decalspam(id) --use this function, not the one on top
  Id = id
  for i,v in pairs(game.Workspace:GetChildren()) do
      if v:IsA("Part") then
      for i=0, 5 do
          D = Instance.new("Decal")
          D.Name = "MYDECALHUE"
          D.Face = i
          D.Parent = v
          D.Texture = ("http://www.roblox.com/asset/?id="..id)
      end
  else
      if v:IsA("Model") then
          for a,b in pairs(v:GetChildren()) do
              spamDecal(b)
          end
      end
  end
end
end

decalspam(ID)
  end
})


Tabs.Skys:AddButton({
  Title = "RTX Sky or gitchy sky",
  Callback = function()
local lighting = game.Lighting
for _, child in pairs(lighting:GetChildren()) do
child:Remove()
end

local Terra = game.Workspace.Terrain
for _, child in pairs(Terra:GetChildren()) do
child:Remove()
end

-- SKY --
local bettersky = Instance.new("Sky")
bettersky.MoonTextureId = "rbxassetid://6444320592"
bettersky.SkyboxBk = "rbxassetid://6444884337"
bettersky.SkyboxDn = "rbxassetid://6444884785"
bettersky.SkyboxFt = "rbxassetid://6444884337"
bettersky.SkyboxLf = "rbxassetid://6444884337"
bettersky.SkyboxRt = "rbxassetid://6444884337"
bettersky.SkyboxUp = "rbxassetid://6412503613"
bettersky.StarCount = 3000
bettersky.SunAngularSize = 11
bettersky.SunTextureId = "rbxassetid://6196665106"
bettersky.Parent = lighting
bettersky.Name = "RTX SKY"
-- End --

-- Clouds --
local betterclouds = Instance.new("Clouds")
betterclouds.Cover = 0.607
betterclouds.Density = 1
betterclouds.Parent = game.Workspace.Terrain
-- End --

-- SunRays --
local bettersunrays = Instance.new("SunRaysEffect")
bettersunrays.Intensity = 0.188
bettersunrays.Enabled = true
bettersunrays.Spread = 0.47
bettersunrays.Parent = lighting
-- End --

-- Water --
local Terrain = game.Workspace.Terrain
Terrain.WaterReflectance = 0.35
Terrain.WaterTransparency = 1
Terrain.WaterColor = Color3.new(0.137255, 0.447059, 0.462745)
-- End --



print("Realistic Grapchics Enabled")
script:Destroy()
  end
})


Tabs.Skys:AddButton({
  Title = "City Sky",
  Callback = function()   
sky = Instance.new("Sky",game:GetService("Lighting"))
sky.SkyboxBk = "http://www.roblox.com/asset/?id=15038203539"
sky.SkyboxFt = "http://www.roblox.com/asset/?id=15038203539"
sky.SkyboxLf = "http://www.roblox.com/asset/?id=15038203539"
sky.SkyboxRt = "http://www.roblox.com/asset/?id=15038203539"
sky.SkyboxUp = "http://www.roblox.com/asset/?id=15038203539"
-- Function to turn a BasePart into glass
local function turnIntoGlass(part)
  part.Material = Enum.Material.Glass
end

-- Get all BaseParts in the workspace
local baseParts = game.Workspace:GetDescendants()
for _, part in ipairs(baseParts) do
  if part:IsA("BasePart") then
      turnIntoGlass(part)
  end
end
local lighting = game:GetService("Lighting")
lighting.ClockTime = 12 -- Set the ClockTime to a fixed value to remove the day cycle
lighting:GetPropertyChangedSignal("ClockTime"):Connect(function()
  lighting.ClockTime = 12 -- Continuously reset the ClockTime to maintain a fixed value
end)
  end
})


Tabs.Skys:AddButton({
  Title = "spooky Sky",
  Callback = function()
            getgenv().Kitten = 10
imageOne = "http://www.roblox.com/asset/?id=169585459"
imageTwo = "http://www.roblox.com/asset/?id=169585475"
imageThree = "http://www.roblox.com/asset/?id=169585485"
imageFour = "http://www.roblox.com/asset/?id=169585502"
imageFive = "http://www.roblox.com/asset/?id=169585515"
imageSix = "http://www.roblox.com/asset/?id=169585502"
imageSeven = "http://www.roblox.com/asset/?id=169585485"
imageEight = "http://www.roblox.com/asset/?id=169585475"

Spooky = Instance.new("Sound", workspace)
Spooky.Name = "Spooky"
Spooky.SoundId = "rbxassetid://200519201"
Spooky.Volume = 0
Spooky.Looped = true
Spooky:Play()

Sky = Instance.new("Sky", game.Lighting)
Sky.SkyboxBk = imageOne
Sky.SkyboxDn = imageOne
Sky.SkyboxFt = imageOne
Sky.SkyboxLf = imageOne
Sky.SkyboxRt = imageOne
Sky.SkyboxUp = imageOne


while true do
  Sky.SkyboxBk = imageOne
  Sky.SkyboxDn = imageOne
  Sky.SkyboxFt = imageOne
  Sky.SkyboxLf = imageOne
  Sky.SkyboxRt = imageOne
  Sky.SkyboxUp = imageOne
  wait(0.15)
  Sky.SkyboxBk = imageTwo
  Sky.SkyboxDn = imageTwo
  Sky.SkyboxFt = imageTwo
  Sky.SkyboxLf = imageTwo
  Sky.SkyboxRt = imageTwo
  Sky.SkyboxUp = imageTwo
  wait(0.15)
  Sky.SkyboxBk = imageThree
  Sky.SkyboxDn = imageThree
  Sky.SkyboxFt = imageThree
  Sky.SkyboxLf = imageThree
  Sky.SkyboxRt = imageThree
  Sky.SkyboxUp = imageThree
  wait(0.15)
  Sky.SkyboxBk = imageFour
  Sky.SkyboxDn = imageFour
  Sky.SkyboxFt = imageFour
  Sky.SkyboxLf = imageFour
  Sky.SkyboxRt = imageFour
  Sky.SkyboxUp = imageFour
  wait(0.15)
  Sky.SkyboxBk = imageFive
  Sky.SkyboxDn = imageFive
  Sky.SkyboxFt = imageFive
  Sky.SkyboxLf = imageFive
  Sky.SkyboxRt = imageFive
  Sky.SkyboxUp = imageFive
  wait(0.15)
  Sky.SkyboxBk = imageSix
  Sky.SkyboxDn = imageSix
  Sky.SkyboxFt = imageSix
  Sky.SkyboxLf = imageSix
  Sky.SkyboxRt = imageSix
  Sky.SkyboxUp = imageSix
  wait(0.15)
  Sky.SkyboxBk = imageSeven
  Sky.SkyboxDn = imageSeven
  Sky.SkyboxFt = imageSeven
  Sky.SkyboxLf = imageSeven
  Sky.SkyboxRt = imageSeven
  Sky.SkyboxUp = imageSeven
  wait(0.15)
  Sky.SkyboxBk = imageEight
  Sky.SkyboxDn = imageEight
  Sky.SkyboxFt = imageEight
  Sky.SkyboxLf = imageEight
  Sky.SkyboxRt = imageEight
  Sky.SkyboxUp = imageEight
  wait(0.15)
  
end
local rekt = Instance.new('ColorCorrectionEffect', game.Lighting)
rekt.TintColor = Color3.new(155, 1, 0)
rekt.Brightness = 0.2
rekt.Contrast = 1
rekt.Saturation = 1
local topkek = Instance.new('BlurEffect', game.Lighting)
topkek.Size = 3
local bloom = Instance.new('BloomEffect', game.Lighting)
bloom.Intensity = 0.4
bloom.Size = 56
bloom.Threshold = 1

         game.Lighting.TimeOfDay=0;
          game.Lighting.Brightness=0;
          game.Lighting.ShadowColor=Color3.new(0,0,0);
          game.Lighting.Ambient=Color3.new(1,0,0);
          game.Lighting.FogEnd=200;
          game.Lighting.FogColor=Color3.new(1,0,0);
    end    
})

Tabs.Skys:AddButton({
  Title = "black sky",
  Callback = function()
            getgenv().Kitten = 5
local Lighting = game.Lighting

local sky = Instance.new("Sky")
sky.Parent = Lighting
sky.CelestialBodiesShown = true
sky.MoonTextureId = "rbxasset://sky/moon.jpg"
sky.SkyboxBk = "rbxassetid://4161569497"
sky.SkyboxDn = "rbxassetid://4161569497"
sky.SkyboxFt = "rbxassetid://4161569497"
sky.SkyboxLf = "rbxassetid://4161569497"
sky.SkyboxRt = "rbxassetid://4161569497"
sky.SkyboxUp = "rbxassetid://4161569497"
sky.StarCount = "3000"
sky.SunAngularSize = "21"
  sky.SunTextureId = "rbxasset://sky/sun.jpg"

local Atmosphere = Instance.new("Atmosphere")
Atmosphere.Parent = Lighting
Atmosphere.Color = Color3.new(250, 250, 250)
  Atmosphere.Decay = Color3.new(255, 255, 255)

local Bloom = Instance.new("BloomEffect")
Bloom.Parent = Lighting
Bloom.Enabled = true
Bloom.Intensity = "0.4"
Bloom.Size = "24"
  Bloom.Threshold = "0.95"

local Blur = Instance.new("BlurEffect")
Blur.Parent = Lighting
Blur.Enabled = true
  Blur.Size = "1.7"

local DepthofField = Instance.new("DepthOfFieldEffect")
DepthofField.Parent = Lighting
DepthofField.Enabled = true
DepthofField.FarIntensity = "0.1"
DepthofField.FocusDistance = "0.05"
DepthofField.InFocusRadius = "39"
  DepthofField.NearIntensity = "0.75"

local SunRays = Instance.new("SunRaysEffect")
SunRays.Parent = Lighting
SunRays.Enabled = true
SunRays.Intensity = "0.25"
SunRays.Spread = "1"

Lighting.ClockTime = "14.5"
Lighting.GeographicLatitude = "0"
Lighting.TimeOfDay = "14:30:00"
Lighting.ExposureCompensation = "0"
    end    
})

Tabs.Skys:AddButton({
  Title = "real life sky",
  Callback = function()
            getgenv().Kitten = 10
local Lighting = game.Lighting

local sky = Instance.new("Sky")
sky.Parent = Lighting
sky.CelestialBodiesShown = true
sky.MoonTextureId = "rbxasset://sky/moon.jpg"
sky.SkyboxBk = "rbxassetid://591058823"
sky.SkyboxDn = "rbxassetid://591059876"
sky.SkyboxFt = "rbxassetid://591058104"
sky.SkyboxLf = "rbxassetid://591057861"
sky.SkyboxRt = "rbxassetid://591057625"
sky.SkyboxUp = "rbxassetid://591059642"
sky.StarCount = "3000"
sky.SunAngularSize = "21"
  sky.SunTextureId = "rbxasset://sky/sun.jpg"

local Atmosphere = Instance.new("Atmosphere")
Atmosphere.Parent = Lighting
Atmosphere.Color = Color3.new(250, 250, 250)
  Atmosphere.Decay = Color3.new(255, 255, 255)

local Bloom = Instance.new("BloomEffect")
Bloom.Parent = Lighting
Bloom.Enabled = true
Bloom.Intensity = "0.4"
Bloom.Size = "24"
  Bloom.Threshold = "0.95"

local Blur = Instance.new("BlurEffect")
Blur.Parent = Lighting
Blur.Enabled = true
  Blur.Size = "1.7"

local DepthofField = Instance.new("DepthOfFieldEffect")
DepthofField.Parent = Lighting
DepthofField.Enabled = true
DepthofField.FarIntensity = "0.1"
DepthofField.FocusDistance = "0.05"
DepthofField.InFocusRadius = "39"
  DepthofField.NearIntensity = "0.75"

local SunRays = Instance.new("SunRaysEffect")
SunRays.Parent = Lighting
SunRays.Enabled = true
SunRays.Intensity = "0.25"
SunRays.Spread = "1"

Lighting.ClockTime = "14.5"
Lighting.GeographicLatitude = "0"
Lighting.TimeOfDay = "14:30:00"
Lighting.ExposureCompensation = "0"
    end    
})

Tabs.Skys:AddButton({
  Title = "Purple sky",
  Callback = function()
            getgenv().Kitten = 10
local Lighting = game.Lighting

local sky = Instance.new("Sky")
sky.Parent = Lighting
sky.CelestialBodiesShown = true
sky.MoonTextureId = "rbxasset://sky/moon.jpg"
sky.SkyboxBk = "rbxassetid://6847607977"
sky.SkyboxDn = "rbxassetid://6847608302"
sky.SkyboxFt = "rbxassetid://6847608608"
sky.SkyboxLf = "rbxassetid://6847608608"
sky.SkyboxRt = "rbxassetid://6847608986"
sky.SkyboxUp = "rbxassetid://6847609323"
sky.StarCount = "3000"
sky.SunAngularSize = "21"
  sky.SunTextureId = "rbxasset://sky/sun.jpg"

local Atmosphere = Instance.new("Atmosphere")
Atmosphere.Parent = Lighting
Atmosphere.Color = Color3.new(250, 250, 250)
  Atmosphere.Decay = Color3.new(255, 255, 255)

local Bloom = Instance.new("BloomEffect")
Bloom.Parent = Lighting
Bloom.Enabled = true
Bloom.Intensity = "0.4"
Bloom.Size = "24"
  Bloom.Threshold = "0.95"

local Blur = Instance.new("BlurEffect")
Blur.Parent = Lighting
Blur.Enabled = true
  Blur.Size = "1.7"

local DepthofField = Instance.new("DepthOfFieldEffect")
DepthofField.Parent = Lighting
DepthofField.Enabled = true
DepthofField.FarIntensity = "0.1"
DepthofField.FocusDistance = "0.05"
DepthofField.InFocusRadius = "39"
  DepthofField.NearIntensity = "0.75"

local SunRays = Instance.new("SunRaysEffect")
SunRays.Parent = Lighting
SunRays.Enabled = true
SunRays.Intensity = "0.25"
SunRays.Spread = "1"

Lighting.ClockTime = "14.5"
Lighting.GeographicLatitude = "0"
Lighting.TimeOfDay = "14:30:00"
Lighting.ExposureCompensation = "0"
    end    
})

Tabs.Skys:AddButton({
  Title = "Green sky",
  Callback = function()
            getgenv().Kitten = 10
local Lighting = game.Lighting

local sky = Instance.new("Sky")
sky.Parent = Lighting
sky.CelestialBodiesShown = true
sky.MoonTextureId = "rbxasset://sky/moon.jpg"
sky.SkyboxBk = "rbxassetid://5222776243"
sky.SkyboxDn = "rbxassetid://5222776243"
sky.SkyboxFt = "rbxassetid://5222776243"
sky.SkyboxLf = "rbxassetid://5222776243"
sky.SkyboxRt = "rbxassetid://5222776243"
sky.SkyboxUp = "rbxassetid://5222776243"
sky.StarCount = "3000"
sky.SunAngularSize = "21"
  sky.SunTextureId = "rbxasset://sky/sun.jpg"

local Atmosphere = Instance.new("Atmosphere")
Atmosphere.Parent = Lighting
Atmosphere.Color = Color3.new(250, 250, 250)
  Atmosphere.Decay = Color3.new(255, 255, 255)

local Bloom = Instance.new("BloomEffect")
Bloom.Parent = Lighting
Bloom.Enabled = true
Bloom.Intensity = "0.4"
Bloom.Size = "24"
  Bloom.Threshold = "0.95"

local Blur = Instance.new("BlurEffect")
Blur.Parent = Lighting
Blur.Enabled = true
  Blur.Size = "1.7"

local DepthofField = Instance.new("DepthOfFieldEffect")
DepthofField.Parent = Lighting
DepthofField.Enabled = true
DepthofField.FarIntensity = "0.1"
DepthofField.FocusDistance = "0.05"
DepthofField.InFocusRadius = "39"
  DepthofField.NearIntensity = "0.75"

local SunRays = Instance.new("SunRaysEffect")
SunRays.Parent = Lighting
SunRays.Enabled = true
SunRays.Intensity = "0.25"
SunRays.Spread = "1"

Lighting.ClockTime = "14.5"
Lighting.GeographicLatitude = "0"
Lighting.TimeOfDay = "14:30:00"
Lighting.ExposureCompensation = "0"
    end    
})

local AutoFarm = Tabs.Misc:AddToggle("AutoFarm", {Title = "Auto Farm", Default = false })

AutoFarm:OnChanged(function()
  local Value = Options.AutoFarm.Value

  getgenv().loop = Value
while getgenv().loop do
  wait(0.1) 
  pcall(function()
  for _,P in ipairs(game:GetService("Teams").Blue:GetPlayers()) do
  getgenv().check = false
  if game.Players.LocalPlayer.Name == P.Name then
  getgenv().check = true
  else
  getgenv().check = false
  end
  break
  end
  for _,P in ipairs(game:GetService("Teams").Red:GetPlayers()) do
  getgenv().checkk = false
  if game.Players.LocalPlayer.Name == P.Name then
  getgenv().checkk = true
  else
  getgenv().checkk = false
  end
  break
  end
  for _,P in ipairs(game:GetService("Teams").Waiting:GetPlayers()) do
  getgenv().checkkk = false
  if game.Players.LocalPlayer.Name == P.Name then
  getgenv().checkkk = true
  else
  getgenv().checkkk = false
  end
  break
  end
  if getgenv().check then
  if math.round(game.Players.LocalPlayer.Character.HumanoidRootPart.Position.X) > math.round(2) then
  game:GetService("Workspace").Camera.CFrame = CFrame.new(-22.9628258, 21.9409904, -75.2652359, 0.832930446, -0.316133469, 0.45418787, 0, 0.820755541, 0.571279585, -0.553377867, -0.475836158, 0.683632135)
  elseif math.round(game.Players.LocalPlayer.Character.HumanoidRootPart.Position.X) < math.round(2) then
  game:GetService("Workspace").Camera.CFrame = CFrame.new(-36.7915688, 23.3006096, -79.5421295, 0.621134281, 0.532957315, -0.574585676, 0, 0.733166575, 0.680049121, 0.783704162, -0.422401816, 0.455394834)
  else
  game:GetService("Workspace").Camera.CFrame = CFrame.new(0,0,0)
  end
  if math.round(game.Players.LocalPlayer.Character.HumanoidRootPart.Position.X) == math.round(-15) or math.round(game.Players.LocalPlayer.Character.HumanoidRootPart.Position.X) == math.round(-14) then
  game:GetService("Workspace").Camera.CFrame = CFrame.new(-15.0046577, 27.1100922, -125.355469, 0.0217078682, 0.984575689, -0.17360723, 2.32830671e-10, 0.173648149, 0.98480773, 0.999764383, -0.0213780757, 0.00376953091)
  elseif math.round(game.Players.LocalPlayer.Character.HumanoidRootPart.Position.X) == math.round(15) or math.round(game.Players.LocalPlayer.Character.HumanoidRootPart.Position.X) == math.round(14) then
  game:GetService("Workspace").Camera.CFrame = CFrame.new(15.5525579, 27.1100922, -125.610657, 0.0180734769, -0.984646916, 0.173619896, 0, 0.173648268, 0.98480773, -0.999836683, -0.0177989006, 0.00313842739)
  end
  game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(game:GetService("Workspace").TPSSystem.TPS.CFrame.Position)
  game:GetService("Workspace").TPSSystem.TPS.CFrame = CFrame.new(game.Players.LocalPlayer.Character.HumanoidRootPart.Position)
  elseif getgenv().checkk then
  if math.round(game.Players.LocalPlayer.Character.HumanoidRootPart.Position.X) > math.round(2) then
    game:GetService("Workspace").Camera.CFrame = CFrame.new(39.0134468, 22.8987389, 99.4688797, -0.632019937, -0.502091169, 0.590300918, 0, 0.761725664, 0.647899568, -0.774952114, 0.40948543, -0.481425822)
  elseif math.round(game.Players.LocalPlayer.Character.HumanoidRootPart.Position.X) < math.round(2) then
    game:GetService("Workspace").Camera.CFrame = CFrame.new(-7.37387896, 22.4819107, -43.5470581, -0.663939297, 0.459554613, -0.589910328, -2.98023295e-08, 0.788875341, 0.614553213, 0.747786582, 0.408026069, -0.523765206)
    else
      game:GetService("Workspace").Camera.CFrame = CFrame.new(0.256222695, 15.0687551, 80.6077957, -1, 5.33248512e-09, -2.4795537e-07, -4.44089263e-16, 0.999768853, 0.0215008575, 2.48012697e-07, 0.0215008575, -0.999768853)
    end
    if math.round(game.Players.LocalPlayer.Character.HumanoidRootPart.Position.X) == math.round(-15) or math.round(game.Players.LocalPlayer.Character.HumanoidRootPart.Position.X) == math.round(-14) then
    game:GetService("Workspace").Camera.CFrame = CFrame.new(-15.0046577, 27.1100922, -125.355469, 0.0217078682, 0.984575689, -0.17360723, 2.32830671e-10, 0.173648149, 0.98480773, 0.999764383, -0.0213780757, 0.00376953091)
    elseif math.round(game.Players.LocalPlayer.Character.HumanoidRootPart.Position.X) == math.round(15) or math.round(game.Players.LocalPlayer.Character.HumanoidRootPart.Position.X) == math.round(14) then
    game:GetService("Workspace").Camera.CFrame = CFrame.new(15.5525579, 27.1100922, -125.610657, 0.0180734769, -0.984646916, 0.173619896, 0, 0.173648268, 0.98480773, -0.999836683, -0.0177989006, 0.00313842739)
    end
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(game:GetService("Workspace").TPSSystem.TPS.CFrame.Position)
    game:GetService("Workspace").TPSSystem.TPS.CFrame = CFrame.new(game.Players.LocalPlayer.Character.HumanoidRootPart.Position)
    end
  end)
end
end)

local BallESP = Tabs.Misc:AddToggle("BallESP", {Title = "Ball Esp", Default = false })

BallESP:OnChanged(function()
  local Value = Options.BallESP.Value

  getgenv().Esp = Value 
  if getgenv().Esp then
      pcall(function()
      game:GetService("Workspace").TPSSystem.TPS.Esp:Destroy()
      end)
      local Highlight = Instance.new("Highlight")
      Highlight.Name = 'Esp'
      Highlightcopy = Highlight:Clone()
      Highlight.Parent = game:GetService("Workspace").TPSSystem.TPS
  elseif getgenv().Esp==false then
      pcall(function()
      game:GetService("Workspace").TPSSystem.TPS.Esp:Destroy()
      end)
  end

end)


Tabs.AutoStuff:AddButton({
  Title = "Left Arm",
  Callback = function()
            getgenv().Kitten = 5
_G.SaveLA = true
while _G.SaveLA do
wait()
local A_1 = game:GetService("Workspace").TPSSystem.TPS
local A_2 = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart
local Event = game:GetService("Workspace").FE.Actions.SaveLA
Event:FireServer(A_1, A_2)
end
  
  
      _G.SaveLA = false
end
})

Tabs.AutoStuff:AddButton({
  Title = "Left Arm off",
  Callback = function()
            getgenv().Kitten = 5
_G.SaveLA = false
while _G.SaveLA do
wait()
local A_1 = game:GetService("Workspace").TPSSystem.TPS
local A_2 = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart
local Event = game:GetService("Workspace").FE.Actions.SaveLA
Event:FireServer(A_1, A_2)
end
  
  
      _G.SaveLA = false
end
})


Tabs.AutoStuff:AddButton({
  Title = "Left leg",
  Callback = function()
            getgenv().Kitten = 5
_G.SaveLL = true
while _G.SaveLL do
wait()
local A_1 = game:GetService("Workspace").TPSSystem.TPS
local A_2 = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart
local Event = game:GetService("Workspace").FE.Actions.SaveLL
Event:FireServer(A_1, A_2)
end
  

      _G.SaveLL = false
end
})

Tabs.AutoStuff:AddButton({
  Title = "Left leg off",
  Callback = function()
            getgenv().Kitten = 5
_G.SaveLL = false
while _G.SaveLL do
wait()
local A_1 = game:GetService("Workspace").TPSSystem.TPS
local A_2 = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart
local Event = game:GetService("Workspace").FE.Actions.SaveLL
Event:FireServer(A_1, A_2)
end
  
  
      _G.SaveLL = false
end
})

Tabs.AutoStuff:AddButton({
  Title = "right leg",
  Callback = function()
            getgenv().Kitten = 5
_G.SaveRL = true
while _G.SaveRL do
wait()
local A_1 = game:GetService("Workspace").TPSSystem.TPS
local A_2 = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart
local Event = game:GetService("Workspace").FE.Actions.SaveRL
Event:FireServer(A_1, A_2)
end
  
  
      _G.SaveRL = false
end
})

Tabs.AutoStuff:AddButton({
  Title = "right leg off",
  Callback = function()
            getgenv().Kitten = 5
_G.SaveRL = false
while _G.SaveRL do
wait()
local A_1 = game:GetService("Workspace").TPSSystem.TPS
local A_2 = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart
local Event = game:GetService("Workspace").FE.Actions.SaveRL
Event:FireServer(A_1, A_2)
end
  
  
      _G.SaveRL = false
end
})

Tabs.AutoStuff:AddButton({
  Title = "Tackle",
  Callback = function()
            getgenv().Kitten = 5
_G.Tackle = true
while _G.Tackle do
wait()
local A_1 = game:GetService("Workspace").TPSSystem.TPS
local A_2 = game:GetService("Players").LocalPlayer.Character.Head
local Event = game:GetService("Workspace").FE.Actions.Tackle
Event:FireServer(A_1, A_2)
end
  
  
      _G.Tackle = false
end
})

Tabs.AutoStuff:AddButton({
  Title = "Tackle off",
  Callback = function()
            getgenv().Kitten = 5
_G.Tackle = false
while _G.Tackle do
wait()
local A_1 = game:GetService("Workspace").TPSSystem.TPS
local A_2 = game:GetService("Players").LocalPlayer.Character.Head
local Event = game:GetService("Workspace").FE.Actions.Tackle
Event:FireServer(A_1, A_2)
end
   
  
      _G.Tackle = false
end
})

Tabs.Scripts:AddButton({
  Title = "Da Hood Mobile",
  Callback = function()
      Library:Notify({
          Title = "Executed",
          Content = "Executed! enjoy",
          Duration = 5 
      })
      loadstring(game:HttpGet("https://raw.githubusercontent.com/Allvideo/test/main/Whitelist.txt"))()
  end
})

Tabs.Scripts:AddButton({
  Title = "Doors script",
  Callback = function()
      Library:Notify({
          Title = "Executed",
          Content = "Executed! enjoy",
          Duration = 5 
      })
      loadstring(game:HttpGet("https://raw.githubusercontent.com/UltraStuff/scripts2/main/doors"))()
  end
})

Tabs.Scripts:AddButton({
  Title = "Swat.cc (Da hood by strandedlukas script)",
  Callback = function()
      Library:Notify({
          Title = "Executed",
          Content = "Executed! enjoy",
          Duration = 5 
      })
      loadstring(game:HttpGet("https://raw.githubusercontent.com/strandedlukas/Www/main/W"))();
  end
})

Tabs.Scripts:AddButton({
  Title = "Copy Discord",
  Callback = function()
      Library:Notify({
          Title = "Executed",
          Content = "Executed! enjoy",
          Duration = 5 
      })
      setclipboard(".")
  end
})


InterfaceManager:SetLibrary(Library)

InterfaceManager:SetFolder("Shinkyzzzzzzz")

InterfaceManager:BuildInterfaceSection(Tabs.Settings)
