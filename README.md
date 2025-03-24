local UserInputService = game:GetService("UserInputService")

local Sensitivity = 0.5 -- Define a sensibilidade da mira

UserInputService.InputBegan:Connect(function(input)
  if input.UserInputType == Enum.UserInputType.MouseMovement then
    local DeltaX = input.Delta.X * Sensitivity
    local DeltaY = input.Delta.Y * Sensitivity
    
    -- Adicione o código para mover a mira aqui
    -- Por exemplo, você pode usar a função "SetPrimaryPartCFrame" para mover a mira
  end
end)
