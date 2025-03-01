-- Load Rayfield UI Library
local Rayfield = loadstring(game:HttpGet('https://sirius.menu/rayfield'))()

-- Create the UI Window
local Window = Rayfield:CreateWindow({
    Name = "Ban/Kick Hub",
    LoadingTitle = "Admin Panel",
    LoadingSubtitle = "Control Players",
    Theme = "Dark",
})

-- Create Admin Controls Tab
local AdminTab = Window:CreateTab("Admin Controls", 4483362458)

-- Variable to Store Player Name Input
local PlayerName = ""

-- Input Box for Entering Player Name
AdminTab:CreateInput({
    Name = "Enter Player Name",
    PlaceholderText = "Type name here...",
    RemoveTextAfterFocusLost = false,
    Callback = function(value)
        PlayerName = value
    end
})

-- Function to Find and Kick/Ban Player (Client-Side Exploit)
local function GetPlayerByName(name)
    for _, player in pairs(game.Players:GetPlayers()) do
        if player.Name:lower() == name:lower() then
            return player
        end
    end
    return nil
end

-- Function to Kick a Player
local function KickPlayer()
    local targetPlayer = GetPlayerByName(PlayerName)
    if targetPlayer then
        -- Forcefully disconnects the player
        targetPlayer:Destroy()
    end
end

-- Function to Ban a Player
local function BanPlayer()
    local targetPlayer = GetPlayerByName(PlayerName)
    if targetPlayer then
        -- Bans the player (removes them permanently for this session)
        targetPlayer:Kick("You have been permanently banned from this game.")
    end
end

-- Ban Button
AdminTab:CreateButton({
    Name = "Ban Player",
    Callback = function()
        BanPlayer()
    end
})

-- Kick Button
AdminTab:CreateButton({
    Name = "Kick Player",
    Callback = function()
        KickPlayer()
    end
})
