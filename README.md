-- 자동 훈련 스크립트
while true do
    local character = game.Players.LocalPlayer.Character
    if character and character:FindFirstChild("HumanoidRootPart") then
        character.HumanoidRootPart.CFrame = CFrame.new(100, 0, 100)  -- 훈련 장소로 이동
        wait(0.5)  -- 0.5초마다 훈련
    end
end
