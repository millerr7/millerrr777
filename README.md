local Fluent = loadstring(game:HttpGet("https://github.com/dawid-scripts/Fluent/releases/latest/download/main.lua"))()

local Window = Fluent:CreateWindow({
    Title = "Meepcity Hub" .. Fluent.Version,
    TabWidth = 160, Size = UDim2.fromOffset(500, 360), Theme = "Dark"
})

local Tabs = {
    Main = Window:AddTab({ Title = "Meepcity", Icon = "gamepad-2" }),
    Main2 = Window:AddTab({ Title = "Outros", Icon = "chevrons-left-right" }),
    Settings = Window:AddTab({ Title = "Settings", Icon = "settings" })
}

Fluent:Notify({ Title = "MADE BY MILLER", Content = "dc: .brandt7" })
Duration = 8

Tabs.Main:AddParagraph({ Title = "Scripts do meepcity" })
Tabs.Main2:AddParagraph({ Title = "Outros scripts" })

Tabs.Main:AddButton({ Title = "Atomic X Hub", Callback = function() loadstring(game:HttpGet('https://raw.githubusercontent.com/yLegendzz/Scripts/main/Meepcity'))() end })
Tabs.Main:AddButton({ Title = "LAG SERVER", Callback = function() game:GetService("RunService").Stepped:Connect(function()
    game:GetService("ReplicatedStorage").Connection:InvokeServer(9)
end) end})
Tabs.Main:AddButton({ Title = "Synolope", Callback = function() loadstring(game:HttpGet("https://rawscripts.net/raw/MeepCity-MeepCity-OP-GUI-(TONS-OF-OP-FEATURES)-1629"))() end })
Tabs.Main:AddButton({ Title = "Meepcity Cracked", Callback = function() loadstring(game:HttpGet("https://rawscripts.net/raw/MeepCity-Meepcity-cracked-6349"))() end })
Tabs.Main:AddButton({ Title = "Spam balão", Callback = function() while task.wait() do
local args = {
    [1] = 201,
    [2] = 1311,
    [3] = {}
}

local args2 = {
    [1] = 202
}

game:GetService("ReplicatedStorage").Connection:InvokeServer(unpack(args))
game:GetService("ReplicatedStorage").Connection:InvokeServer(unpack(args2))
local args = {
    [1] = 201,
    [2] = 1312,
    [3] = {}
}

local args2 = {
    [1] = 202
}

game:GetService("ReplicatedStorage").Connection:InvokeServer(unpack(args))
game:GetService("ReplicatedStorage").Connection:InvokeServer(unpack(args2))
local args = {
    [1] = 201,
    [2] = 1313,
    [3] = {}
}

local args2 = {
    [1] = 202
}

game:GetService("ReplicatedStorage").Connection:InvokeServer(unpack(args))
game:GetService("ReplicatedStorage").Connection:InvokeServer(unpack(args2))
local args = {
    [1] = 201,
    [2] = 1314,
    [3] = {}
}

local args2 = {
    [1] = 202
}

game:GetService("ReplicatedStorage").Connection:InvokeServer(unpack(args))
game:GetService("ReplicatedStorage").Connection:InvokeServer(unpack(args2))
local args = {
    [1] = 201,
    [2] = 1315,
    [3] = {}
}

local args2 = {
    [1] = 202
}

game:GetService("ReplicatedStorage").Connection:InvokeServer(unpack(args))
game:GetService("ReplicatedStorage").Connection:InvokeServer(unpack(args2))

end end })

Tabs.Main2:AddButton({ Title = "Infinite Yield", Callback = function() loadstring(game:HttpGet("https://rawscripts.net/raw/Infinite-Yield_500"))() end })
Tabs.Main2:AddButton({ Title = "Nameless Admin FE", Callback = function() loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-Nameless-Admin-FE-11243"))() end })
Tabs.Main2:AddButton({ Title = "Chat Bypass", Callback = function() loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-Chat-bypass-idkw-24726"))() end })
Tabs.Main2:AddButton({ Title = "Chat Bypass V2", Callback = function() loadstring(game:HttpGet("https://raw.githubusercontent.com/AlgariBot/lua/refs/heads/Lua-Script-Executor/LocalNeverPatchedBypass.txt"))() end })
Tabs.Main2:AddButton({ Title = "Clone FE", Callback = function() loadstring(game:HttpGet("https://raw.githubusercontent.com/0Ben1/fe/main/obf_11l7Y131YqJjZ31QmV5L8pI23V02b3191sEg26E75472Wl78Vi8870jRv5txZyL1.lua.txt"))() end })
Tabs.Main2:AddButton({ Title = "Rochips Universal", Callback = function() loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-rochips-usefull-24163"))() end })
Tabs.Main2:AddButton({ Title = "Haxker 666", Callback = function() loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-Haxker666-Script-hub-9666"))() end })
