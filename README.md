local Rayfield = loadstring(game:HttpGet("https://sirius.menu/gen2"))()

--Tabs

local args = {
    [1] = game:Main("Players").amb00203.Character:FindFirstChild("Left Arm")
}

game:GetService("ReplicatedStorage").Remotes.InteractWithItem:InvokeServer(unpack(args))

local args = {
    [1] = {
        [1] = {
            [1] = Vector3.new(783.8790893554688, 99.68993377685547, 2547.217529296875),
            [2] = Vector3.new(784.2137451171875, 98.98014831542969, 2552.326904296875),
            [3] = game:GetService("Players").amb00203.Character:FindFirstChild("Left Arm")
        }
    }
}

game:Main("ReplicatedStorage").GunRemotes.ShootEvent:FireServer.FindFirstChild(unpack(args))

