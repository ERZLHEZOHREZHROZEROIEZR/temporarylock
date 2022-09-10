   local d = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
    local k = game.Workspace.Ignored.Shop["[Surgeon Mask] - $25"]
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = k.Head.CFrame + Vector3.new(0, 3, 0)
    if (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - k.Head.Position).Magnitude <= 50 then
        wait(.2)
        fireclickdetector(k:FindFirstChild("ClickDetector"), 4)
        toolf = game.Players.LocalPlayer.Backpack:WaitForChild("Mask")
        toolf.Parent = game.Players.LocalPlayer.Character
        wait()
        game.Players.LocalPlayer.Character:WaitForChild("Mask")
        game:GetService("VirtualUser"):ClickButton1(Vector2.new())
        game.Players.LocalPlayer.Character:WaitForChild("In-gameMask")
        game.Players.LocalPlayer.Character["In-gameMask"].Handle:Destroy()
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(d)
    end
