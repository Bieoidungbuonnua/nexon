repeat wait() until game:IsLoaded()
getgenv().Configcuttay = {
    ["Rarity"] = {
        "Common",
        "Rare",
        "Epic",
        "Legendary",
        "Mythic",
        "Brainrot God",
        "Secret"
    },
    ["Settings"] = {
    ["HideUI"] = false,
    ["AutoKick"] = false,
    ["BoostFPS"] = false,
    ["Auto Rebirth"] = true,
    ["Speed"] = 50,
    ["Lock Base"] = true,
    ["Auto Buy Animals"] = true,
    ["Auto Sell"] = true,
    ["AutoBuyRebirthRequirements"] = false,
    ["Lock Priority"] = false,
    ["Collect Time"] = 30, -- set this to math.huge for no collect
    },
    ["Save Pet From Being Sell and Rebirths"] = {
        "Secret"
    },
    ["Webhook"] = {
        Enabled = true,
        WebhookURL = "",
        WebhookSettings = {
            TrackMode = "Edit", -- Send/Edit
            Interval = 20,
        },
        BuyNotificationSettings = {
            Enabled = true,
            URL = "",
            PingEveryone = true,
            Rarity = {
                "Secret",
            },
        }
    }
}
loadstring(game:HttpGet("https://api.luarmor.net/files/v3/loaders/8737d05624dbadf5102c4fa89aaa1a23.lua"))()
