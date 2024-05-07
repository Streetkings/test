local Rayfield = loadstring(game:HttpGet('https://sirius.menu/rayfield'))()

local Window = Rayfield:CreateWindow({
   Name = "★Peanut's ChatBypasser★ V.0.0 More Coming Soon!",
   LoadingTitle = "Peanut ScriptHub",
   LoadingSubtitle = "by ★LilPeanutGamer4133★✔v",
   ConfigurationSaving = {
      Enabled = false,
      FolderName = nil, -- Create a custom folder for your hubame
      FileName = "Big Hub"
   },
   Discord = {
      Enabled = false,
      Invite = "noinvitelink", -- The Discord invite code, do not include discord.gg/. E.g. discord.gg/ABCD would be ABCD
      RememberJoins = true -- Set this to false to make them join the discord every time they load it up
   },
   KeySystem = false, -- Set this to true to use our key system
   KeySettings = {
      Title = "Peanut Hub",
      Subtitle = "Key System",
      Note = "Contact lilpeanut123 For Key",
      FileName = "Key", -- It is recommended to use something unique as other scripts using Rayfield may overwrite your key file
      SaveKey = false, -- The user's key will be saved, but if you change the key, they will be unable to use your script
      GrabKeyFromSite = True, -- If this is true, set Key below to the RAW site you would like Rayfield to get the key from
      Key = {""} -- List of keys that will be accepted by the system, can be RAW file links (pastebin, github etc) or simple strings ("hello","key22")
   }
})

local HomeTab = Window:CreateTab("Home!", nil) -- Title, Image
local Label = HomeTab:CreateLabel("More Coming Soon!")
local HomeSection = HomeTab:CreateSection("Universal Sliders")

local Slider = HomeTab:CreateSlider({
   Name = "★Walkspeed★!",
   Range = {1, 1000},
   Increment = 1,
   Suffix = "Speed",
   CurrentValue = 16,
   Flag = "Sliderws", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
   Callback = function(Value)
        game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = (Value)
   end,
})

local Slider = HomeTab:CreateSlider({
   Name = "★JumpBoost!★",
   Range = {1, 1000},
   Increment = 1,
   Suffix = "Jump Boost",
   CurrentValue = 100,
   Flag = "Slider", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
   Callback = function(Value)
        game.Players.LocalPlayer.Character.Humanoid.JumpPower = (Value)
   end,
})


local MainTab = Window:CreateTab("Sentences", nil) -- Title, Image
local MainSection = MainTab:CreateSection("Chat Bypasses")

Rayfield:Notify({
   Title = "You Executed Chat Bypasser!",
   Content = "Peanut Gave You This Script.",
   Duration = 6.5,
   Image = 4483362458,
   Actions = { -- Notification Buttons
      Ignore = {
         Name = "Yeah", 
         Callback = function()
         print("More Coming Soon!")
      end
   },
},
})

local Button = MainTab:CreateButton({
   Name = "anal sex",
   Callback = function()
   local args = {
    [1] = "\208\176n\226\129\165\226\129\165\226\129\165\226\129\165\208\176l \209\149\226\129\165\226\129\165\226\129\165\208\181\226\129\165\226\129\165\226\129\165\209\133",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "adopt me sex update",
   Callback = function()
   local args = {
    [1] = "\208\176\226\129\165\226\129\165\226\129\165d\226\129\165\226\129\165\226\129\165\208\190\226\129\165\226\129\165\226\129\165\209\128\226\129\165\226\129\165\226\129\165t\226\129\165\226\129\165\226\129\165 \226\129\165\226\129\165\226\129\165m\226\129\165\226\129\165\226\129\165\208\181\226\129\165\226\129\165\226\129\165 \226\129\165\226\129\165\226\129\165\209\149\226\129\165\226\129\165\226\129\165\208\181\226\129\165\226\129\165\226\129\165\209\133\226\129\165\226\129\165\226\129\165 \226\129\165\226\129\165\226\129\165u\226\129\165\226\129\165\226\129\165\209\128\226\129\165\226\129\165\226\129\165d\226\129\165\226\129\165\226\129\165\208\176\226\129\165\226\129\165\226\129\165t\226\129\165\226\129\165\226\129\165\208\181",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "ass sex pls",
   Callback = function()
   local args = {
    [1] = "\208\176\226\129\165\226\129\165\226\129\165\226\129\165\209\149\209\149 s\226\129\165\226\129\165\226\129\165\226\129\165\208\181\209\133 pls",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "anel sex pls",
   Callback = function()

local args = {
    [1] = "\208\176n\226\129\165\226\129\165\226\129\165\226\129\165\208\176l \209\149\226\129\165\226\129\165\226\129\165\208\181\226\129\165\226\129\165\226\129\165\209\133\226\129\165\226\129\165\226\129\165 pls",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
-- 
   end,
})

local Button = MainTab:CreateButton({
   Name = "Boom cockshot!",
   Callback = function()

local args = {
    [1] = "\208\146\226\129\165\226\129\165\226\129\165\226\129\165\208\190\226\129\165\226\129\165\226\129\165\226\129\165\208\190\226\129\165\226\129\165\226\129\165\226\129\165m\226\129\165\226\129\165\226\129\165\226\129\165 \209\129\226\129\165\226\129\165\226\129\165\226\129\165\208\190\226\129\165\226\129\165\226\129\165\226\129\165\209\129\226\129\165\226\129\165\226\129\165\226\129\165k\226\129\165\226\129\165\226\129\165\226\129\165\209\149\226\129\165\226\129\165\226\129\165\226\129\165h\226\129\165\226\129\165\226\129\165\226\129\165\208\190\226\129\165\226\129\165\226\129\165\226\129\165t\226\129\165\226\129\165\226\129\165\226\129\165!",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))

   end,
})

local Button = MainTab:CreateButton({
   Name = "butt sex",
   Callback = function()

local args = {
    [1] = "bu\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165tt \209\149\226\129\165\226\129\165\226\129\165\208\181x",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "boner alert!",
   Callback = function()

local args = {
    [1] = "b\226\129\165\226\129\165\226\129\165o\226\129\165\226\129\165\226\129\165n\226\129\165\226\129\165\226\129\165\208\181\226\129\165\226\129\165\226\129\165r\226\129\165\226\129\165\226\129\165 \226\129\165\226\129\165\226\129\165\208\176\226\129\165\226\129\165\226\129\165\211\143\226\129\165\226\129\165\226\129\165\208\181\226\129\165\226\129\165\226\129\165r\226\129\165\226\129\165\226\129\165t\226\129\165\226\129\165\226\129\165!",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "big cock",
   Callback = function()

local args = {
    [1] = "b\226\129\165ig \209\129\208\190\226\129\165\226\129\165\226\129\165\209\129k",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "boobs or ass",
   Callback = function()

local args = {
    [1] = "b\226\129\165\226\129\165\226\129\165\208\190\226\129\165\226\129\165\226\129\165\208\190\226\129\165\226\129\165\226\129\165b\226\129\165\226\129\165\226\129\165\209\149\226\129\165\226\129\165\226\129\165 \226\129\165\226\129\165\226\129\165\208\190\226\129\165\226\129\165\226\129\165r\226\129\165\226\129\165\226\129\165 \226\129\165\226\129\165\226\129\165\208\176\226\129\165\226\129\165\226\129\165\209\149\226\129\165\226\129\165\226\129\165\209\149?",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "Big ass thighs",
   Callback = function()

local args = {
    [1] = "\208\146\209\150g \208\176\209\149\209\149 th\209\150gh\209\149",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "bites your cock",
   Callback = function()

local args = {
    [1] = "bites your \209\129\208\190\209\129k",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))

   end,
})

local Button = MainTab:CreateButton({
   Name = "big black cock",
   Callback = function()

local args = {
    [1] = "big black \209\129\208\190\209\129k",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "big ass",
   Callback = function()

local args = {
    [1] = "\208\146\209\150g \208\176\209\149\209\149",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))

   end,
})

local Button = MainTab:CreateButton({
   Name = "Be My Wife!",
   Callback = function()

local args = {
    [1] = "\208\146\208\181 \208\156\209\131 W\209\150f\208\181!",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "can i see those cute boobs of yours?",
   Callback = function()

local args = {
    [1] = "\208\161\208\176n \208\134 \209\149\208\181\208\181 th\208\190\209\149\208\181 \209\129ut\208\181 b\208\190\208\190b\209\149 \208\190f \209\131\208\190ur\209\149?",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))

   end,
})

local Button = MainTab:CreateButton({
   Name = "Cum on me please!",
   Callback = function()

local args = {
    [1] = "\208\161\226\129\165\226\129\165\226\129\165\226\129\165um on me please!",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
-- 
   end,
})

local Button = MainTab:CreateButton({
   Name = "cum please",
   Callback = function()

local args = {
    [1] = "\209\129\226\129\165\226\129\165\226\129\165\226\129\165um \209\128\211\143\208\181\208\176\209\149\208\181",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "cock sucker",
   Callback = function()

local args = {
    [1] = "\209\129\208\190\209\129k \209\149u\209\129k\208\181r",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "cut youself.",
   Callback = function()

local args = {
    [1] = "\209\129ut y\208\190urself.",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))

   end,
})

local Button = MainTab:CreateButton({
   Name = "cock incoming!",
   Callback = function()

local args = {
    [1] = "\208\161\208\190\209\129k incoming!",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "Cock or Boobs",
   Callback = function()

local args = {
    [1] = "\208\161\226\129\165\226\129\165\226\129\165\208\190\226\129\165\226\129\165\226\129\165\209\129\226\129\165\226\129\165\226\129\165k\226\129\165\226\129\165\226\129\165 \226\129\165\226\129\165\226\129\165\208\190\226\129\165\226\129\165\226\129\165r\226\129\165\226\129\165\226\129\165 \226\129\165\226\129\165\226\129\165\208\146\226\129\165\226\129\165\226\129\165\208\190\226\129\165\226\129\165\226\129\165\208\190\226\129\165\226\129\165\226\129\165b\226\129\165\226\129\165\226\129\165\209\149\226\129\165\226\129\165\226\129\165?",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "dirty hoe",
   Callback = function()

local args = {
    [1] = "d\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165i\226\129\165\226\129\165\226\129\165\226\129\165rt\226\129\165\226\129\165\226\129\165\209\131 \226\129\165\226\129\165h\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\208\190\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\208\181",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))

   end,
})

local Button = MainTab:CreateButton({
   Name = "dommy mommy",
   Callback = function()

local args = {
    [1] = "d\226\129\165\226\129\165\226\129\165\208\190\226\129\165\226\129\165\226\129\165m\226\129\165\226\129\165\226\129\165m\226\129\165\226\129\165\226\129\165\209\131 m\226\129\165\226\129\165\226\129\165\208\190\226\129\165\226\129\165\226\129\165m\226\129\165\226\129\165\226\129\165m\226\129\165\226\129\165\226\129\165\209\131",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))

   end,
})

local Button = MainTab:CreateButton({
   Name = "free porn",
   Callback = function()

local args = {
    [1] = "fr\208\181\208\181 \209\128\208\190rn",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "fat ass hoe",
   Callback = function()

local args = {
    [1] = "f\226\129\165\208\176t \208\176\226\129\165\209\149\209\149 \210\187\226\129\165\208\190\208\181",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "fat ass",
   Callback = function()

local args = {
    [1] = "f\226\129\165\208\176t \208\176\226\129\165\209\149\209\149",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "hardcore sex",
   Callback = function()


local args = {
    [1] = "h\226\129\165\226\129\165\226\129\165\208\176\226\129\165\226\129\165\226\129\165r\226\129\165\226\129\165\226\129\165d\226\129\165\226\129\165\226\129\165\209\129\226\129\165\226\129\165\226\129\165\208\190\226\129\165\226\129\165\226\129\165r\226\129\165\226\129\165\226\129\165\208\181\226\129\165\226\129\165\226\129\165 \209\149\226\129\165\226\129\165\226\129\165\208\181\226\129\165\226\129\165\226\129\165\209\133\226\129\165\226\129\165\226\129\165",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "go end your own life.",
   Callback = function()

local args = {
    [1] = "g\208\190 \208\181nd \209\131\208\190ur \208\190wn l\209\150f\208\181.",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))

   end,
})

local Button = MainTab:CreateButton({
   Name = "hardcore impregnation",
   Callback = function()

local args = {
    [1] = "\210\187\208\176rd\209\129\208\190r\208\181 \209\150m\209\128r\208\181gn\208\176t\209\150\208\190n",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "horny 24/7",
   Callback = function()

local args = {
    [1] = "h\208\190rn\209\131 24/7",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "i eat pussy",
   Callback = function()

local args = {
    [1] = "I\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165 \208\181\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\208\176t \226\129\165\226\129\165\209\128\226\129\165\226\129\165\226\129\165u\226\129\165\226\129\165\226\129\165\226\129\165s\226\129\165\226\129\165s\209\131",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))

   end,
})

local Button = MainTab:CreateButton({
   Name = "i love minores",
   Callback = function()

local args = {
    [1] = "\226\129\165\226\129\165\226\129\165\209\150 \211\143\226\129\165\226\129\165\226\129\165\208\190\226\129\165\226\129\165\226\129\165v\226\129\165\226\129\165\226\129\165\208\181 \226\129\165\226\129\165\226\129\165m\226\129\165\226\129\165\226\129\165\209\150\226\129\165\226\129\165\226\129\165n\226\129\165\226\129\165\226\129\165\208\190\226\129\165\226\129\165\226\129\165r\226\129\165\226\129\165\226\129\165\209\149",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "i love you",
   Callback = function()

local args = {
    [1] = "\209\150 \211\143\208\190v\208\181 \209\131\208\190u",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "i love you daddy",
   Callback = function()

local args = {
    [1] = "\209\150 \211\143\208\190v\208\181 \209\131\208\190u daddy",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "i love you mommy",
   Callback = function()

local args = {
    [1] = "\209\150 \211\143\208\190v\208\181 \209\131\208\190u mommy",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "i love you so much mommy",
   Callback = function()

local args = {
    [1] = "\209\150 \211\143\208\190v\208\181 \209\131\208\190u \209\149\208\190 mu\209\129h mommy",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "i love you so much",
   Callback = function()

local args = {
    [1] = "\209\150 \211\143\208\190v\208\181 \209\131\208\190u \209\149\208\190 mu\209\129h",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))

   end,
})

local Button = MainTab:CreateButton({
   Name = "i love you so much daddy",
   Callback = function()

local args = {
    [1] = "\209\150 \211\143\208\190v\208\181 \209\131\208\190u \209\149\208\190 mu\209\129h daddy",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))

   end,
})

local Button = MainTab:CreateButton({
   Name = "i love cocks",
   Callback = function()

local args = {
    [1] = "I\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165 \211\143\226\129\165\226\129\165\208\190\226\129\165\226\129\165v\208\181 \226\129\165\226\129\165\209\129\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\208\190\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\209\129\226\129\165\226\129\165\226\129\165\226\129\165k\209\149",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))

   end,
})

local Button = MainTab:CreateButton({
   Name = "i like titties",
   Callback = function()

local args = {
    [1] = "\209\150 \211\143\209\150k\208\181 t\209\150tt\209\150\208\181s",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))

   end,
})

local Button = MainTab:CreateButton({
   Name = "i love boobs",
   Callback = function()

local args = {
    [1] = "\209\150\226\129\165\226\129\165\226\129\165 \226\129\165\226\129\165\226\129\165\211\143\226\129\165\226\129\165\226\129\165\208\190\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165v\208\181 b\208\190\208\190b\209\149",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))

   end,
})

local Button = MainTab:CreateButton({
   Name = "im gonna make you pregnant mommy",
   Callback = function()

local args = {
    [1] = "\209\150m g\208\190nn\208\176 m\208\176k\208\181 \209\131\208\190u \209\128r\208\181gn\208\176nt m\208\190mm\209\131",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))

   end,
})

local Button = MainTab:CreateButton({
   Name = "i'm horny so moan",
   Callback = function()

local args = {
    [1] = "\209\150'm h\208\190rn\209\131 \209\149\206\191 m\206\191\208\176n",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "im sexy, and you know it",
   Callback = function()

local args = {
    [1] = "\209\150'm \209\149\208\181\209\133\209\131, \208\176nd \209\131\206\191\207\133 kn\206\191w \209\150t",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "i'm mad horny",
   Callback = function()

local args = {
    [1] = "\209\150'm mad h\208\190rn\209\131",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "i'm so hard rn",
   Callback = function()

local args = {
    [1] = "\209\150'm \209\149\208\190 h\208\176rd rn",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "i'm gonna bang you hard",
   Callback = function()

local args = {
    [1] = "\209\150'm g\206\191nn\208\176 b\208\176ng \209\131\206\191u \210\187\208\176rd",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "i'm so hard right now!",
   Callback = function()

local args = {
    [1] = "\209\150'm \209\149\208\190 h\208\176rd right now!",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "i would like to see some titties",
   Callback = function()

local args = {
    [1] = "\206\153 w\206\191\207\133\211\143d \211\143\209\150k\208\181 t\206\191 \209\149\208\181\208\181 \209\149\206\191m\208\181 t\209\150tt\209\150\208\181s",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "ive been a very naughty girl",
   Callback = function()

local args = {
    [1] = "\209\150v\208\181 b\208\181\208\181n \208\176 v\208\181r\209\131 n\208\176ug\210\187t\209\131 g\209\150r\211\143",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "ive been a very dirty little boy",
   Callback = function()

local args = {
    [1] = "\209\150v\208\181 b\208\181\208\181n \208\176 d\209\150rt\209\131 \211\143\209\150tt\211\143\208\181 b\208\190\209\131",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "i wanna kms",
   Callback = function()

local args = {
    [1] = "\209\150 w\208\176nn\208\176 km\209\149",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "i wanna smash you",
   Callback = function()

local args = {
    [1] = "\209\150 w\208\176nn\208\176 \209\149m\208\176\209\149h \209\131\208\190u",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "i want to drink your breasts",
   Callback = function()

local args = {
    [1] = "\209\150 w\208\176nt t\208\190 dr\209\150nk \209\131\208\190ur br\208\181\208\176\209\149t\209\149",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))

   end,
})

local Button = MainTab:CreateButton({
   Name = "i do sexy things",
   Callback = function()

local args = {
    [1] = "\208\134 d\208\190 \209\149\208\181\209\133\209\131 th\209\150ng\209\149",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))

   end,
})

local Button = MainTab:CreateButton({
   Name = "i banged your girl so hard",
   Callback = function()

local args = {
    [1] = "\208\134 b\208\176ng\208\181d \209\131\208\190ur g\209\150rl \209\149\208\190 \210\187\208\176rd",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "i dont give a shit.",
   Callback = function()

local args = {
    [1] = "I dont give a s\210\187\209\150t.",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))

   end,
})

local Button = MainTab:CreateButton({
   Name = "i just shat my pants",
   Callback = function()

local args = {
    [1] = "i just s\210\187at my pants",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))

   end,
})

local Button = MainTab:CreateButton({
   Name = "i just shit my pants",
   Callback = function()

local args = {
    [1] = "i just s\210\187it my pants",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))

   end,
})

local Button = MainTab:CreateButton({
   Name = "i love masterbating",
   Callback = function()

local args = {
    [1] = "i love m\226\129\165\226\129\165\226\129\165\208\176\226\129\165\226\129\165\226\129\165\209\149\226\129\165\226\129\165\226\129\165t\226\129\165\226\129\165\226\129\165u\226\129\165\226\129\165\226\129\165r\226\129\165\226\129\165\226\129\165b\226\129\165\226\129\165\226\129\165\208\176\226\129\165\226\129\165\226\129\165t\226\129\165\226\129\165\226\129\165ing",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))

   end,
})

local Button = MainTab:CreateButton({
   Name = "i love sex",
   Callback = function()

local args = {
    [1] = "I love \209\149\208\181x",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))

   end,
})

local Button = MainTab:CreateButton({
   Name = "i love weed",
   Callback = function()

local args = {
    [1] = "i love w\208\181\208\181d",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))

   end,
})

local Button = MainTab:CreateButton({
   Name = "i'll make you pregnant",
   Callback = function()

local args = {
    [1] = "\208\134'\211\143\211\143 m\208\176k\208\181 \209\131\208\190u \209\128r\208\181gn\208\176nt",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))

   end,
})

local Button = MainTab:CreateButton({
   Name = "i pull all the bitches",
   Callback = function()

local args = {
    [1] = "i pull all the bit\209\129\210\187\208\181s",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "imagine getting no bitch",
   Callback = function()

local args = {
    [1] = "imagine getting no bit\209\129\210\187\208\181s",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "kill yourself",
   Callback = function()

local args = {
    [1] = "k\209\150\211\143l \209\131\208\190ur\209\149\208\181\211\143f",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))

   end,
})

local Button = MainTab:CreateButton({
   Name = "keep moaning",
   Callback = function()

local args = {
    [1] = "keep m\208\190\208\176ning",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))

   end,
})

local Button = MainTab:CreateButton({
   Name = "lets do doggy style",
   Callback = function()

local args = {
    [1] = "\211\143\226\129\165\226\129\165\226\129\165\208\181\226\129\165\226\129\165\226\129\165t\226\129\165\226\129\165\226\129\165\209\149\226\129\165\226\129\165\226\129\165 \226\129\165\226\129\165\226\129\165d\226\129\165\226\129\165\226\129\165\208\190\226\129\165\226\129\165\226\129\165 \226\129\165\226\129\165\226\129\165d\226\129\165\226\129\165\226\129\165\208\190\226\129\165\226\129\165\226\129\165g\226\129\165\226\129\165\226\129\165g\226\129\165\226\129\165\226\129\165\209\131\226\129\165\226\129\165\226\129\165 \226\129\165\226\129\165\226\129\165\209\149\226\129\165\226\129\165\226\129\165t\226\129\165\226\129\165\226\129\165\209\131\226\129\165\226\129\165\226\129\165\211\143\226\129\165\226\129\165\226\129\165\208\181",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
-- 
   end,
})

local Button = MainTab:CreateButton({
   Name = "lets do it doggy style",
   Callback = function()

local args = {
    [1] = "\211\143\226\129\165\226\129\165\226\129\165\208\181\226\129\165\226\129\165\226\129\165t\226\129\165\226\129\165\226\129\165\209\149\226\129\165\226\129\165\226\129\165 \226\129\165\226\129\165\226\129\165d\226\129\165\226\129\165\226\129\165\208\190\226\129\165\226\129\165\226\129\165 it \226\129\165\226\129\165\226\129\165d\226\129\165\226\129\165\226\129\165\208\190\226\129\165\226\129\165\226\129\165g\226\129\165\226\129\165\226\129\165g\226\129\165\226\129\165\226\129\165\209\131\226\129\165\226\129\165\226\129\165 \226\129\165\226\129\165\226\129\165\209\149\226\129\165\226\129\165\226\129\165t\226\129\165\226\129\165\226\129\165\209\131\226\129\165\226\129\165\226\129\165\211\143\226\129\165\226\129\165\226\129\165\208\181",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "lets have sex",
   Callback = function()

local args = {
    [1] = "\226\129\165\226\129\165\226\129\165\211\143\226\129\165\226\129\165\226\129\165\208\181\226\129\165\226\129\165\226\129\165t\226\129\165\226\129\165\226\129\165\209\149 \226\129\165\226\129\165\226\129\165\210\187\226\129\165\226\129\165\226\129\165\208\176\226\129\165\226\129\165\226\129\165v\226\129\165\226\129\165\226\129\165\208\181\226\129\165\226\129\165\226\129\165 \209\149\226\129\165\226\129\165\226\129\165\208\181\226\129\165\226\129\165\226\129\165\209\133\226\129\165\226\129\165\226\129\165",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "let daddy eat u out",
   Callback = function()

local args = {
    [1] = "\211\143\226\129\165\226\129\165\226\129\165\208\181\226\129\165\226\129\165\226\129\165t\226\129\165\226\129\165\226\129\165 \226\129\165\226\129\165\226\129\165d\226\129\165\226\129\165\226\129\165a\226\129\165\226\129\165\226\129\165d\226\129\165\226\129\165\226\129\165d\226\129\165\226\129\165\226\129\165y\226\129\165\226\129\165\226\129\165 \226\129\165\226\129\165\226\129\165\208\181\226\129\165\226\129\165\226\129\165\208\176\226\129\165\226\129\165\226\129\165t\226\129\165\226\129\165\226\129\165 \226\129\165\226\129\165\226\129\165u\226\129\165\226\129\165\226\129\165 \226\129\165\226\129\165\226\129\165\208\190\226\129\165\226\129\165\226\129\165u\226\129\165\226\129\165\226\129\165t",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "let daddy eat you out",
   Callback = function()

local args = {
    [1] = "\211\143\226\129\165\226\129\165\226\129\165\208\181\226\129\165\226\129\165\226\129\165t\226\129\165\226\129\165\226\129\165 \226\129\165\226\129\165\226\129\165d\226\129\165\226\129\165\226\129\165a\226\129\165\226\129\165\226\129\165d\226\129\165\226\129\165\226\129\165d\226\129\165\226\129\165\226\129\165y\226\129\165\226\129\165\226\129\165 \226\129\165\226\129\165\226\129\165\208\181\226\129\165\226\129\165\226\129\165\208\176\226\129\165\226\129\165\226\129\165t\226\129\165\226\129\165\226\129\165 \226\129\165\226\129\165\226\129\165you\226\129\165\226\129\165\226\129\165 \226\129\165\226\129\165\226\129\165\208\190\226\129\165\226\129\165\226\129\165u\226\129\165\226\129\165\226\129\165t",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "let me squish those titties",
   Callback = function()

local args = {
    [1] = "\211\143\208\181t m\208\181 \209\149q\207\133\209\150\209\149\210\187 t\210\187\206\191\209\149\208\181 t\209\150tt\209\150\208\181s",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "lgbtq? kill them all",
   Callback = function()

local args = {
    [1] = "\226\129\165\226\129\165\226\129\165\211\143\226\129\165\226\129\165\226\129\165g\226\129\165\226\129\165\226\129\165b\226\129\165\226\129\165\226\129\165t\226\129\165\226\129\165\226\129\165q? k\226\129\165\226\129\165\226\129\165\209\150\226\129\165\226\129\165\226\129\165\211\143\226\129\165\226\129\165\226\129\165\211\143 t\210\187\208\181m \208\176\211\143\211\143",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "mind if you let me squish those titties",
   Callback = function()

local args = {
    [1] = "Mind if you \211\143\208\181t m\208\181 \209\149q\207\133\209\150\209\149\210\187 t\210\187\206\191\209\149\208\181 t\209\150tt\209\150\208\181s",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "my condom fell off!",
   Callback = function()

local args = {
    [1] = "m\209\131 \226\129\165\226\129\165\226\129\165\209\129\226\129\165\226\129\165\226\129\165\208\190\226\129\165\226\129\165\226\129\165n\226\129\165\226\129\165\226\129\165d\226\129\165\226\129\165\226\129\165\208\190\226\129\165\226\129\165\226\129\165m f\208\181\211\143\211\143 \208\190ff!",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "make me pregnant",
   Callback = function()
   

local args = {
    [1] = "m\208\176k\208\181 m\208\181 \209\128r\208\181gn\208\176nt",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))

   end,
})

local Button = MainTab:CreateButton({
   Name = "Mr Breast is so cool",
   Callback = function()

local args = {
    [1] = "\208\156r \208\146r\208\181\208\176\209\149t \209\150\209\149 \209\149\208\190 \209\129\208\190\208\190l",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "Naked Boys in your closet",
   Callback = function()
   

local args = {
    [1] = "\206\157\208\176k\208\181d \208\146\206\191\209\131\209\149 \209\150n \209\131\206\191ur closet",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))

   end,
})

local Button = MainTab:CreateButton({
   Name = "Naked Girls",
   Callback = function()

local args = {
    [1] = "\206\157\208\176k\208\181d G\209\150r\211\143\209\149",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "Naked boys",
   Callback = function()

local args = {
    [1] = "\206\157\208\176k\208\181d \208\146\206\191\209\131\209\149",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "Naked Boys in your closet",
   Callback = function()

local args = {
    [1] = "\206\157\208\176k\208\181d \208\146\206\191\209\131\209\149 \209\150n \209\131\206\191ur closet",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "oh my god, not this DUMB ASS",
   Callback = function()

local args = {
    [1] = "oh my god, not this DU\208\156\208\146 \208\144\208\133\208\133",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))

   end,
})

local Button = MainTab:CreateButton({
   Name = "please dominate me",
   Callback = function()

local args = {
    [1] = "\209\128\211\143\208\181\208\176\209\149\208\181 d\208\190m\209\150n\208\176t\208\181 m\208\181",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "rape me",
   Callback = function()

local args = {
    [1] = "r\208\176\209\128\208\181\20m\208\181",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "spank me daddy",
   Callback = function()

local args = {
    [1] = "\209\149\226\129\165\226\129\165\226\129\165\209\128\226\129\165\226\129\165\226\129\165\208\176\226\129\165\226\129\165\226\129\165n\226\129\165\226\129\165\226\129\165k\226\129\165\226\129\165\226\129\165 \226\129\165\226\129\165\226\129\165m\226\129\165\226\129\165\226\129\165\208\181\226\129\165\226\129\165\226\129\165 \226\129\165\226\129\165\226\129\165d\226\129\165\226\129\165\226\129\165\208\176\226\129\165\226\129\165\226\129\165d\226\129\165\226\129\165\226\129\165d\226\129\165\226\129\165\226\129\165\209\131",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "pussy licker",
   Callback = function()

local args = {
    [1] = "\209\128\226\129\165\226\129\165\226\129\165u\226\129\165\226\129\165\226\129\165\226\129\165s\226\129\165\226\129\165s\209\131 \211\143i\226\129\165\226\129\165\209\129\226\129\165\226\129\165\226\129\165k\226\129\165\226\129\165\208\181\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165r",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))

   end,
})

local Button = MainTab:CreateButton({
   Name = "sweet cock dude",
   Callback = function()

local args = {
    [1] = "\208\133w\208\181\208\181t \209\129\208\190\209\129k dud\208\181",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "sex slave",
   Callback = function()

local args = {
    [1] = "\209\149\226\129\165\226\129\165\226\129\165\208\181\226\129\165\226\129\165\226\129\165\209\133\226\129\165\226\129\165\226\129\165 \226\129\165\226\129\165\226\129\165\209\149\226\129\165\226\129\165\226\129\165\211\143\226\129\165\226\129\165\226\129\165\208\176\226\129\165\226\129\165\226\129\165v\226\129\165\226\129\165\226\129\165\208\181",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))

   end,
})

local Button = MainTab:CreateButton({
   Name = "spank me",
   Callback = function()

local args = {
    [1] = "\209\149\226\129\165\226\129\165\226\129\165\209\128\226\129\165\226\129\165\226\129\165\208\176\226\129\165\226\129\165\226\129\165n\226\129\165\226\129\165\226\129\165k\226\129\165\226\129\165\226\129\165 \226\129\165\226\129\165\226\129\165m\226\129\165\226\129\165\226\129\165\208\181\226\129\165\226\129\165\226\129\165",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "shut up cunt",
   Callback = function()

local args = {
    [1] = "Shut up \209\129unt",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "seduce me",
   Callback = function()

local args = {
    [1] = "\209\149\208\181du\209\129\208\181 me",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "smd hoe",
   Callback = function()

local args = {
    [1] = "\209\149md \210\187\226\129\165\226\129\165\226\129\165\208\190\226\129\165\226\129\165\226\129\165\208\181",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "shut yo goofy ass up",
   Callback = function()

local args = {
    [1] = "\208\133hut\20yo\20goofy\20\208\176\209\149\209\149\20up",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "Sweet cock you got up there",
   Callback = function()

local args = {
    [1] = "Sweet \209\129\208\190\209\129k you got up there",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "suck my cock retard",
   Callback = function()

local args = {
    [1] = "\209\149u\209\129k my \209\129\208\190\209\129k ret\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\208\176rd",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))

   end,
})

local Button = MainTab:CreateButton({
   Name = "shut yo broke ass up",
   Callback = function()

local args = {
    [1] = "shut\20yo\20broke\20\208\176\209\149\209\149\20up",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "Shut yo goofy ass",
   Callback = function()

local args = {
    [1] = "\208\133hut yo goofy \208\176\209\149\209\149",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "Twerk for me!",
   Callback = function()

local args = {
    [1] = "\208\162w\208\181rk f\208\190r m\208\181!",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "small penis",
   Callback = function()

local args = {
    [1] = "small \209\128en\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165i\209\149",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))-- The function that takes place when the button is pressed
   end,
})

local Button = MainTab:CreateButton({
   Name = "ur moms booty is delicious",
   Callback = function()

local args = {
    [1] = "ur m\208\190m\209\149 b\208\190\208\190t\209\131 \209\150\209\149 d\208\181l\209\150\209\129\209\150\208\190u\209\149",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "that bbc dont play",
   Callback = function()

local args = {
    [1] = "th\208\176t b\226\129\165\226\129\165\226\129\165b\226\129\165\226\129\165\226\129\165\209\129 d\208\190nt \209\128l\208\176\209\131",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "wanna have anel sex?",
   Callback = function()

local args = {
    [1] = "w\208\176nn\208\176 \210\187\208\176v\208\181 \208\176n\226\129\165\226\129\165\226\129\165\226\129\165\208\176l s\226\129\165\226\129\165\226\129\165\226\129\165\208\181\209\133?",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "wanna have sex?",
   Callback = function()

local args = {
    [1] = "w\208\176nn\208\176 \210\187\208\176v\208\181 s\226\129\165\226\129\165\226\129\165\226\129\165\208\181\209\133?",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "wsg bbg you lookin sexy",
   Callback = function()

local args = {
    [1] = "w\209\149g bbg \209\131\208\190u l\208\190\208\190k\209\150n \209\149\208\181\209\133\209\131",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "wanna see some bbc",
   Callback = function()

local args = {
    [1] = "w\208\176nn\208\176 \209\149\208\181\208\181 \209\149\208\190m\208\181 b\226\129\165\226\129\165\226\129\165b\226\129\165\226\129\165\226\129\165\209\129",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "you like to rape and suck black oiled up men",
   Callback = function()

local args = {
    [1] = "\209\131\208\190u l\209\150k\208\181 t\208\190 r\208\176\209\128\208\181 \208\176nd \209\149u\209\129k bl\208\176\209\129k \208\190\209\150l\208\181d u\209\128 m\208\181n",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))

   end,
})

local Button = MainTab:CreateButton({
   Name = "yo my shaft is hard, mind jerking it?",
   Callback = function()

local args = {
    [1] = "\209\131\208\190 m\209\131 \209\149h\208\176ft \209\150\209\149 \210\187\208\176rd, m\209\150nd \209\152\208\181rk\209\150ng \209\150t?",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "you're nothing but a failed abortion",
   Callback = function()

local args = {
    [1] = "\209\131\208\190u'r\208\181 n\208\190t\210\187\209\150ng but \208\176 f\208\176\209\150\211\143\208\181d \208\176b\208\190rt\209\150\208\190n.",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "you're such a whore",
   Callback = function()

local args = {
    [1] = "\209\131\226\129\165\226\129\165\226\129\165\208\190\226\129\165\226\129\165\226\129\165u\226\129\165\226\129\165\226\129\165'r\226\129\165\226\129\165\226\129\165\208\181\226\129\165\226\129\165\226\129\165 \226\129\165\226\129\165\226\129\165\209\149\226\129\165\226\129\165\226\129\165u\226\129\165\226\129\165\226\129\165\209\129\226\129\165\226\129\165\226\129\165\210\187\226\129\165\226\129\165\226\129\165 \226\129\165\226\129\165\226\129\165\208\176\226\129\165\226\129\165\226\129\165 \226\129\165\226\129\165\226\129\165w\226\129\165\226\129\165\226\129\165\210\187\226\129\165\226\129\165\226\129\165\208\190\226\129\165\226\129\165\226\129\165r\226\129\165\226\129\165\226\129\165\208\181",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))

   end,
})

local Button = MainTab:CreateButton({
   Name = "you're a predophile",
   Callback = function()

local args = {
    [1] = "\209\131\226\129\165\226\129\165\226\129\165\208\190\226\129\165\226\129\165\226\129\165u\226\129\165\226\129\165\226\129\165'\226\129\165\226\129\165\226\129\165r\226\129\165\226\129\165\226\129\165\208\181\226\129\165\226\129\165\226\129\165 \226\129\165\226\129\165\226\129\165\208\176\226\129\165\226\129\165\226\129\165 p\226\129\165\226\129\165\208\181\226\129\165\226\129\165\226\129\165d\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\208\190\209\128\226\129\165\226\129\165h\209\150\211\143\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\208\181",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "you pathetic slut",
   Callback = function()

local args = {
    [1] = "you pathetic \209\149\211\143\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165ut",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "you're a pussy",
   Callback = function()

local args = {
    [1] = "\209\131\208\190u'r\208\181 \208\176 \209\128u\226\129\165\226\129\165\226\129\165ss\209\131",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "you're so sexy",
   Callback = function()

local args = {
    [1] = "\209\131\208\190u'r\208\181 \209\149\208\190 \209\149\208\181\209\133\209\131",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))

   end,
})

local MainSection = MainTab:CreateSection("*Roleplays*")

local Button = MainTab:CreateButton({
   Name = "ah yes~ *moans* yes harder~",
   Callback = function()
   local args = {
    [1] = "\208\176h \209\131\208\181\209\149~ *m\226\129\165\226\129\165\226\129\165\208\190\226\129\165\226\129\165\226\129\165\208\176\226\129\165\226\129\165\226\129\165n\226\129\165\226\129\165\226\129\165\209\149* \209\131\208\181\209\149 \210\187\208\176rd\208\181r~",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "*bites your cock*",
   Callback = function()
   local args = {
    [1] = "*bites\20your\20\209\129\208\190\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\209\129k*",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "*cums*",
   Callback = function()
   local args = {
    [1] = "*\209\129\226\129\165\226\129\165\226\129\165\226\129\165um\209\149*",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "*looka under skirt* wow nice balls bro",
   Callback = function()
   local args = {
    [1] = "*\211\143\208\190\208\190k\209\149 und\208\181r \209\149k\209\150rt* w\208\190w n\209\150\209\129\208\181 b\208\176l\211\143\209\149 br\208\190",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "*masturbates*",
   Callback = function()
   local args = {
    [1] = "*ma\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165st\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165urbates*",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "*sucks cock*",
   Callback = function()
   local args = {
    [1] = "*\209\149u\209\129k\209\149 \209\129\208\190\209\129k*",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local MainSection = MainTab:CreateSection("Uppercase Sentences")

local Button = MainTab:CreateButton({
   Name = "BE MY WIFE!",
   Callback = function()
   local args = {
    [1] = "\208\146\206\149 \208\156\206\165 WIF\206\149!",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "BIG BOOTY LATINAS",
   Callback = function()
   local args = {
    [1] = "\208\146\208\134G \208\146\208\158\208\158\208\162\206\165 L\208\144\208\162\208\134\206\157\208\144\208\133",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "BIG BOOTY FEMBOYS",
   Callback = function()
   local args = {
    [1] = "\208\146\208\134G \208\146\208\158\208\158\208\162\206\165 F\208\149\208\156\208\146\208\158\206\165\208\133",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "BIG BOOTY",
   Callback = function()
   local args = {
    [1] = "\208\146\208\134G \208\146\208\158\208\158\208\162\206\165",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "BIG BOOBS",
   Callback = function()
   local args = {
    [1] = "BIG \208\146\208\158\208\158\208\146S",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "CAN I PISS INSIDE YOUR BUTTHOLE?",
   Callback = function()
   local args = {
    [1] = "\208\161\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\208\144N \208\134 \208\160\226\129\165\226\129\165\226\129\165\226\129\165\208\134\208\133\208\133 \208\134N\208\133IDE YOU\226\129\165\226\129\165\226\129\165R \208\146\226\129\165\226\129\165\226\129\165U\226\129\165\226\129\165\226\129\165\226\129\165\208\162\208\162\226\129\165\226\129\165\226\129\165\226\129\165\208\157OL\208\149?",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "COCK IN BEDROOM",
   Callback = function()
   local args = {
    [1] = "\208\161\208\158\208\161K\20I\226\129\165\226\129\165\226\129\165N\20BEDROOM",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "CUM ON ME",
   Callback = function()
   local args = {
    [1] = "\208\161U\208\156\20\208\158\206\157\20\208\156\208\149",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "DO YOU HAVE TITS?",
   Callback = function()
   local args = {
    [1] = "D\208\158 \206\165\208\158U \208\157\208\144V\208\149 \208\162\226\129\165\226\129\165\226\129\165\208\134\226\129\165\226\129\165\226\129\165\208\162\226\129\165\226\129\165\226\129\165\208\133?",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "EAT PUSSY BITCH",
   Callback = function()
   local args = {
    [1] = "EAT \208\160\226\129\165\226\129\165\226\129\165U\226\129\165\226\129\165\226\129\165\208\133\226\129\165\226\129\165\226\129\165\208\133\226\129\165\226\129\165\226\129\165Y \208\146\208\134\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165T\208\161H",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "FATASS HOE",
   Callback = function()
   local args = {
    [1] = "F\208\144\208\162\208\144\208\133\208\133 \208\157\208\158\208\149",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "FAT ASS",
   Callback = function()
   local args = {
    [1] = "F\226\129\165\226\129\165\226\129\165\208\144\226\129\165\226\129\165\226\129\165\208\162 \208\144\226\129\165\226\129\165\226\129\165\208\133\226\129\165\226\129\165\226\129\165\208\133",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "FREE HENTAI",
   Callback = function()
   local args = {
    [1] = "FR\208\149\208\149 \208\157\208\149\226\129\165\226\129\165\226\129\165\226\129\165\206\157\226\129\165\208\162\208\144\211\128",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "FUCK YOU",
   Callback = function()
   local args = {
    [1] = "FU\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\208\161\206\154\20\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165Y\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165O\226\129\165\226\129\165\226\129\165\226\129\165U",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "HELP! THERES A HOE CHASING ME",
   Callback = function()
   local args = {
    [1] = "\208\157\208\149L\208\160! \208\162\208\157\208\149R\208\149S \208\144 \208\157\208\158\208\149 \208\161\208\157\208\144SING \208\156\208\149",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "I AM ABOUT TO CUM",
   Callback = function()
   local args = {
    [1] = "I\20\208\144\208\156 \208\144\208\146OU\239\191\176\239\191\176\239\191\176T\20TO\20\208\161\239\191\176\239\191\176\239\191\176U\239\191\176\239\191\176\239\191\176\208\156",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "I EAT PUSSY",
   Callback = function()
   local args = {
    [1] = "\211\128 \208\149\208\144\208\162 \208\160U\208\133\208\133\210\174",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "I PREFER PUSSY",
   Callback = function()
   local args = {
    [1] = "I\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165 P\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165R\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165E\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165F\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165E\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165R\226\129\165 \208\160\226\129\165\226\129\165U\208\133\226\129\165\226\129\165\208\133\226\129\165\226\129\165\210\174\226\129\165",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))

   end,
})

local Button = MainTab:CreateButton({
   Name = "I HAVE A MASSIVE COCK",
   Callback = function()
   
local args = {
    [1] = "I HAVE A MASSIVE \208\161\208\158\208\161K",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "ILL MAKE YOU PREGNANT",
   Callback = function()
   local args = {
    [1] = "ILL \208\156\206\145K\206\149 \206\165\208\158U \208\160R\206\149G\206\157\206\145\206\157\208\162",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "IM GONNA BANG YOU HARD",
   Callback = function()
   local args = {
    [1] = "\208\134\208\156 G\208\158\206\157\206\157\208\144 \208\146\208\144\206\157G \206\165\208\158U \208\157\208\144RD",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "IM MAD HORNY",
   Callback = function()
   local args = {
    [1] = "IM MAD \208\157\208\158RNY",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "KYS BITCH",
   Callback = function()
   local args = {
    [1] = "K\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\206\165\226\129\165\226\129\165\226\129\165S B\208\134\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165TCH",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "LET ME HAVE A TASTE OF THAT COCK",
   Callback = function()
   local args = {
    [1] = "L\208\149\208\162 \208\156\208\149 \208\157\208\144V\208\149 \208\144 \208\162\208\144\208\133\208\162\208\149 \208\158F \208\162\208\157\208\144\208\162 \208\161\208\158\208\161\206\154",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "LET ME SQUISH THOSE TITTIES",
   Callback = function()
   local args = {
    [1] = "L\208\149\208\162 \208\156\208\149 \208\133QU\208\134\208\133\208\157 \208\162\208\157\208\158\208\133\208\149 \208\162\208\134\208\162\208\162\208\134\208\149\208\133",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "LETS HAVE SEX",
   Callback = function()
   local args = {
    [1] = "L\226\129\165\226\129\165\226\129\165\208\149\226\129\165\226\129\165\226\129\165\208\162\226\129\165\226\129\165\226\129\165\208\133\226\129\165\226\129\165\226\129\165 \226\129\165\226\129\165\226\129\165\208\157\226\129\165\226\129\165\226\129\165\208\144\226\129\165\226\129\165\226\129\165V\226\129\165\226\129\165\226\129\165\208\149\226\129\165\226\129\165\226\129\165 \226\129\165\226\129\165\226\129\165\208\133\226\129\165\226\129\165\226\129\165\208\149\226\129\165\226\129\165\226\129\165\208\165",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "LETS FUCK",
   Callback = function()
   local args = {
    [1] = "LET'S\20F\239\191\176\239\191\176\239\191\176\239\191\176\239\191\176\239\191\176U\208\161\239\191\176\239\191\176\239\191\176\239\191\176\239\191\176\239\191\176\239\191\176\239\191\176\206\154",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "MY CONDOM FELL OFF!",
   Callback = function()
   local args = {
    [1] = "\208\156\206\165 \208\161\226\129\165\226\129\165\226\129\165\208\158\226\129\165\226\129\165\226\129\165\206\157\226\129\165\226\129\165\226\129\165D\226\129\165\226\129\165\226\129\165\208\158\226\129\165\226\129\165\226\129\165\208\156 F\208\149LL \208\158FF!",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "NAKED GIRLS",
   Callback = function()
   local args = {
    [1] = "\206\157\206\145K\206\149D GIRL\208\133",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "oh my god, not this DUMB ASS",
   Callback = function()
   local args = {
    [1] = "oh my god, not this DU\208\156\208\146 \208\144\208\133\208\133",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "PUT YOUR COCK IN MY ASS",
   Callback = function()
   local args = {
    [1] = "\208\160U\208\162\20\206\165\239\191\176\239\191\176\239\191\176\208\158U\239\191\176\239\191\176R\20\208\161\208\158\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\208\161K\20IN\20MY \208\144\239\191\176\239\191\176\239\191\176\208\133\239\191\176\239\191\176\239\191\176\208\133",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "SUCK MY COCK",
   Callback = function()
   local args = {
    [1] = "SU\208\161K\20\208\156\206\165\20\208\161\208\158\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\208\161K",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "SHUT THE FUCK UP",
   Callback = function()
   local args = {
    [1] = "SHUT\20THE\20F\239\191\176\239\191\176\239\191\176\239\191\176\239\191\176\239\191\176U\208\161\239\191\176\239\191\176\239\191\176\239\191\176\239\191\176\239\191\176\239\191\176\239\191\176\206\154\20U\208\160",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "SHUT UP CUNT",
   Callback = function()
   local args = {
    [1] = "SHUT UP CU\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165N\208\162",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "SHAKE THAT ASS",
   Callback = function()
   local args = {
    [1] = "\208\133HAKE\20\208\162\208\157\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\226\129\165\208\144\208\162 \208\144\239\191\176\239\191\176\239\191\176\208\133\239\191\176\239\191\176\239\191\176\208\133",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "SON OF A BITCH",
   Callback = function()
   local args = {
    [1] = "SO\243\160\128\150\243\160\128\151\243\160\128\152\243\160\128\149\243\160\128\150N\20O\243\160\128\150\243\160\128\151\243\160\128\152\243\160\128\149\243\160\128\150F\20A\20\208\146\239\191\176\239\191\176\239\191\176\239\191\176\239\191\176\239\191\176\239\191\176I\239\191\176\239\191\176\239\191\176\239\191\176\239\191\176\239\191\176TCH",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "SHIT NOOOOOOO",
   Callback = function()
   local args = {
    [1] = "\208\133\226\129\165\226\129\165\226\129\165\226\129\165\208\157\226\129\165\226\129\165\226\129\165\226\129\165\206\153\226\129\165\226\129\165\226\129\165\226\129\165\208\162\226\129\165\226\129\165\226\129\165\226\129\165 \206\157\226\129\165\226\129\165\226\129\165\226\129\165\208\158\226\129\165\226\129\165\226\129\165\226\129\165\208\158\226\129\165\226\129\165\226\129\165\226\129\165\208\158\226\129\165\226\129\165\226\129\165\226\129\165\208\158\226\129\165\226\129\165\226\129\165\226\129\165\208\158\226\129\165\226\129\165\226\129\165\226\129\165\208\158\226\129\165\226\129\165\226\129\165\226\129\165\208\158\226\129\165\226\129\165\226\129\165\226\129\165",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local Button = MainTab:CreateButton({
   Name = "YOUU ARE SO ASS AT THIS GAME",
   Callback = function()
   local args = {
    [1] = "\206\165\208\158U\20\208\144R\208\149\20\208\133\208\158 \208\144\239\191\176\239\191\176\239\191\176\208\133\239\191\176\239\191\176\239\191\176\208\133 \208\144\208\162\20THI\208\133\20G\208\144\208\156\208\149",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
   end,
})

local WordTab = Window:CreateTab("Words", nil) -- Title, Image
local WordSection = WordTab:CreateSection("Word Bypasses")

local Button = WordTab:CreateButton({
   Name = "NAME",
   Callback = function()
   --script
   end,
})

local Button = WordTab:CreateButton({
   Name = "NAME",
   Callback = function()
   --script
   end,
})

local Button = WordTab:CreateButton({
   Name = "NAME",
   Callback = function()
   --script
   end,
})

local Button = WordTab:CreateButton({
   Name = "NAME",
   Callback = function()
   --script
   end,
})

local Button = WordTab:CreateButton({
   Name = "NAME",
   Callback = function()
   --script
   end,
})

local Button = WordTab:CreateButton({
   Name = "NAME",
   Callback = function()
   --script
   end,
})

local Button = WordTab:CreateButton({
   Name = "NAME",
   Callback = function()
   --script
   end,
})

local Button = WordTab:CreateButton({
   Name = "NAME",
   Callback = function()
   --script
   end,
})


local Button = WordTab:CreateButton({
   Name = "NAME",
   Callback = function()
   --script
   end,
})

local Button = WordTab:CreateButton({
   Name = "NAME",
   Callback = function()
   --script
   end,
})

local Button = WordTab:CreateButton({
   Name = "NAME",
   Callback = function()
   --script
   end,
})

local Button = WordTab:CreateButton({
   Name = "NAME",
   Callback = function()
   --script
   end,
})


local Button = WordTab:CreateButton({
   Name = "NAME",
   Callback = function()
   --script
   end,
})

local Button = WordTab:CreateButton({
   Name = "NAME",
   Callback = function()
   --script
   end,
})

local Button = WordTab:CreateButton({
   Name = "NAME",
   Callback = function()
   --script
   end,
})

local Button = WordTab:CreateButton({
   Name = "NAME",
   Callback = function()
   --script
   end,
})


local Button = WordTab:CreateButton({
   Name = "NAME",
   Callback = function()
   --script
   end,
})

local Button = WordTab:CreateButton({
   Name = "NAME",
   Callback = function()
   --script
   end,
})

local Button = WordTab:CreateButton({
   Name = "NAME",
   Callback = function()
   --script
   end,
})

local Button = WordTab:CreateButton({
   Name = "NAME",
   Callback = function()
   --script
   end,
})


local Button = WordTab:CreateButton({
   Name = "NAME",
   Callback = function()
   --script
   end,
})

local Button = WordTab:CreateButton({
   Name = "NAME",
   Callback = function()
   --script
   end,
})

local Button = WordTab:CreateButton({
   Name = "NAME",
   Callback = function()
   --script
   end,
})

local Button = WordTab:CreateButton({
   Name = "NAME",
   Callback = function()
   --script
   end,
})


local Button = WordTab:CreateButton({
   Name = "NAME",
   Callback = function()
   --script
   end,
})

local Button = WordTab:CreateButton({
   Name = "NAME",
   Callback = function()
   --script
   end,
})

local Button = WordTab:CreateButton({
   Name = "NAME",
   Callback = function()
   --script
   end,
})

local Button = WordTab:CreateButton({
   Name = "NAME",
   Callback = function()
   --script
   end,
})


local Button = WordTab:CreateButton({
   Name = "NAME",
   Callback = function()
   --script
   end,
})

local Button = WordTab:CreateButton({
   Name = "NAME",
   Callback = function()
   --script
   end,
})

local Button = WordTab:CreateButton({
   Name = "NAME",
   Callback = function()
   --script
   end,
})

local Button = WordTab:CreateButton({
   Name = "NAME",
   Callback = function()
   --script
   end,
})


local Button = WordTab:CreateButton({
   Name = "NAME",
   Callback = function()
   --script
   end,
})

local Button = WordTab:CreateButton({
   Name = "NAME",
   Callback = function()
   --script
   end,
})

local Button = WordTab:CreateButton({
   Name = "NAME",
   Callback = function()
   --script
   end,
})

local Button = WordTab:CreateButton({
   Name = "NAME",
   Callback = function()
   --script
   end,
})
