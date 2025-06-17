# Script
Esse script ainda está em fase de testes,digamos que no beta
--[[  
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
🌀 CARLÃO DO GRAU V1.0 FINAL 🌀
by Daniel Flesh Benfica & GPT
Hub Completo: Auto Tudo, UI Leve, Proteções Anti-Kick/Ban, Multi idioma, Sea Events, Katakuri, V4, Bounty, Soul Guitar, etc.
--]]

repeat task.wait() until game:IsLoaded()
if game.PlaceId ~= 7449423635 and game.PlaceId ~= 2753915549 and game.PlaceId ~= 4442272183 then
    return print("⚠️ Carlão do Grau: Jogo incompatível.")
end

-- Proteção
pcall(function() setfflag("AbuseReportScreenshot", "False") end)

-- Config inicial
getgenv().Config = {
    Team = "Pirates",
    AutoFarm = true,
    AutoQuest = true,
    AutoBoss = true,
    AutoEliteBoss = true,
    AutoKatakuriV1 = true,
    AutoKatakuriV2 = true,
    AutoSoulGuitar = true,
    AutoSeaEvents = true,
    AutoTerrorShark = true,
    AutoLeviathan = true,
    AutoBlackbeard = true,
    AutoDragonDojo = true,
    AutoDragonHunter = true,
    AutoYama = true,
    AutoTushita = true,
    AutoCDK = true,
    AutoTTK = true,
    AutoBuyLegendarySwords = true,
    AutoBuyFightingStyles = true,
    AutoDracoV1 = true,
    AutoDracoV2 = true,
    AutoDracoV3 = true,
    AutoDracoV4 = true,
    AutoTrialDraco = true,
    AutoResetAfterV4 = true,
    AutoRaceV2V3 = true,
    AutoAwakenFruit = true,
    AutoStats = true,
    AutoFly = true,
    AutoClick = true,
    AutoHaki = true,
    AutoTeleportTree = true,
    AutoFarmBounty = true,
    AimbotBounty = true,
    PanicTeleport = true,
    AntiKick = true,
    AntiLag = true,
    SaveConfig = true,
    Theme = "Dark",
    Icon = "GG", -- Ícone Goku + GG
    Language = "PT", -- PT, EN, ES, RU, VI, KO, ZH, JP, TH, NL
}

-- Carregar Interface e Funcionalidades
loadstring(game:HttpGet("https://raw.githubusercontent.com/CarlHubScript/CarlScript/main/CoreHandler.lua"))()
