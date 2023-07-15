while true do wait()
local args = {
    [1] = workspace:WaitForChild("NPC"):WaitForChild("TURTLEBOSS"):WaitForChild("Humanoid")
}

game:GetService("ReplicatedStorage"):WaitForChild("DamageEvent"):FireServer(unpack(args))
end
