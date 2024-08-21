repeat task.wait(0.25) until game:GetService("Players") and game:GetService("Players").LocalPlayer
if not game:IsLoaded() then game.Loaded:Wait() task.wait(3) end

for _, code in ipairs(RD.Redeem) do
    game:GetService('ReplicatedStorage').MainEvent:FireServer('EnterPromoCode', code)
    task.wait(2)
end
