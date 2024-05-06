    -- Script para dinheiro infinito no Car Dealership Tycoon
local player = game.Players.LocalPlayer
local moneyAmount = 1000000000 -- Defina o valor desejado

    --Verifica se o jogador está no jogo
if player then
    local leaderstats = player:WaitForChild("leaderstats")
    local money = leaderstats:WaitForChild("Money")

    -- Define o dinheiro do jogador para o valor desejado
  money.Value = moneyAmount
    print("Dinheiro definido para $" .. moneyAmount)
else
    warn("brunno0732")
end
