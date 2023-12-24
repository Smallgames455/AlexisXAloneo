local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/thanhdat4461/OrionMoblie/main/source')))()
local Window = OrionLib:MakeWindow({Name = "Alone & Alexis Universal 🧊", HidePremium = false, SaveConfig = true, IntroText = "Welcome" })


OrionLib:MakeNotification({
	Name = "Alone & Alexis Universal",
	Content = "Beta Version",
	Image = "rbxassetid://4483345998",
	Time = 5
})

local Tab = Window:MakeTab({
	Name = "Official / Main 🎄",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false})
	
	Tab:AddLabel("Universal Script Made By Aloneo And Alex")
	
	Tab:AddButton({
	Name = "Click To Join Our Discord",
	Callback = function()
    setclipboard("https://discord.com/invite/hMsQ5QC5Ah")
  	end    
})

local Section = Tab:AddSection({
	Name = "Misc Script 🎄"
})

Tab:AddButton({
	Name = "Mobile Keyboard ❄️",
	Callback = function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/advxzivhsjjdhxhsidifvsh/mobkeyboard/main/main.txt", true))()
  	end    
})

Tab:AddButton({
	Name = "Fly Script V3 ❄️",
	Callback = function()
    loadstring(game:HttpGet('https://pastebin.com/raw/YSL3xKYU'))()
  	end    
})

Tab:AddButton({
	Name = "Anti Lag ❄️",
	Callback = function()
    loadstring(game:HttpGet("https://pastebin.com/raw/t2391h1A"))()
  	end    
})

Tab:AddButton({
	Name = "Anti Afk ❄️",
	Callback = function()
    loadstring(game:HttpGet(('https://raw.githubusercontent.com/RTrade/Voidz/main/AntiAFK.lua'),true))()
  	end    
})

local Tab = Window:MakeTab({
	Name = "New Update 🎄",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false})

local Section = Tab:AddSection({
	Name = "New Update"
})

Tab:AddLabel("--------- Version 4.1 News ---------")
Tab:AddLabel("[ + ] Added Alexis Universal Script On Script Hub")
Tab:AddLabel("[ + ] Added Arm Wrestle Simulator")

local Tab = Window:MakeTab({
	Name = "Script Games 🎄",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false})
	
	local Section = Tab:AddSection({
	Name = "Blade Ball ❄️"
})

Tab:AddButton({
	Name = "Auto Parry ❄️",
	Callback = function()
      		loadstring(game:HttpGet("https://raw.githubusercontent.com/Hosvile/Refinement/main/MC%3ABlade%20Ball%20Parry",true))()
  	end    
})

Tab:AddButton({
	Name = "Auto Spam ❄️",
	Callback = function()
      		loadstring(game:HttpGet("https://pastebin.com/raw/t2391h1A"))()
  	end    
})

Tab:AddButton({
	Name = "Bedol Hub ❄️",
	Callback = function()
      		loadstring(game:HttpGet("https://raw.githubusercontent.com/3345-c-a-t-s-u-s/-beta-/main/AutoParry.lua"))()
  	end    
})

Tab:AddButton({
	Name = "EminX Hub ❄️",
	Callback = function()
      		loadstring(game:HttpGet("https://raw.githubusercontent.com/EminenceXLua/Blade-your-Balls/main/BladeBallLoaderV2.lua"))()
  	end    
})

Tab:AddButton({
	Name = "Joe Hub ❄️",
	Callback = function()
      		loadstring(game:HttpGet("https://raw.githubusercontent.com/JoeBidenhub/Script-releases-latest-download/main/main.lua",true))()
  	end    
})

Tab:AddButton({
	Name = "NovaX Hub ❄️",
	Callback = function()
      		loadstring(game:HttpGet("https://raw.githubusercontent.com/xdevslasher/novaxnewgen/main/novax.lua",true))()
  	end    
})

Tab:AddButton({
	Name = "DarkRai Hub ❄️",
	Callback = function()
      		loadstring(game:HttpGet("https://pastefy.app/scPne8wv/raw"))()
  	end    
})

Tab:AddButton({
	Name = "Baryon Hub ❄️",
	Callback = function()
      		loadstring(game:HttpGet("https://raw.githubusercontent.com/VickzinJs/Auto-Parry123/main/Untitled-2.lua"))()
  	end    
})

Tab:AddButton({
	Name = "Atreus Hub ❄️",
	Callback = function()
      		loadstring(game:HttpGet("https://raw.githubusercontent.com/DenDenZYT/DenDenZ-On-YouTube/main/Atreus%20Hub%20KEYSYSTEM"))()
  	end    
})

local Section = Tab:AddSection({
	Name = "Pet Simulator 99 🎄"
})

Tab:AddButton({
	Name = "Redz Hub ❄️",
	Callback = function()
      		loadstring(game:HttpGet("https://raw.githubusercontent.com/REDzHUB/PetSimulator99/main/redz9999.lua"))()
  	end    
})
Tab:AddButton({
	Name = "Auto StairWay ❄️",
	Callback = function()
      		loadstring(game:HttpGet('https://raw.githubusercontent.com/fissurectomy/woah/main/ps99_stairway.lua'))()
  	end    
})

Tab:AddButton({
	Name = "RiverHub / Skyhub ❄️",
	Callback = function()
      		loadstring(game:HttpGet('https://raw.githubusercontent.com/SKOIXLL/RIVERHUB-SKYHUB/main/WL.lua'))();
  	end    
})

Tab:AddButton({
	Name = "Banana Hub ❄️",
	Callback = function()
      		loadstring(game:HttpGet("https://raw.githubusercontent.com/diepedyt/bui/main/temporynewkeysystem.lua"))()
  	end    
})

Tab:AddButton({
	Name = "Syrex Hub ❄️",
	Callback = function()
      		loadstring(game:HttpGet("https://raw.githubusercontent.com/gerisxx/ps99-Script/main/syrexhub"))()
  	end    
})

Tab:AddButton({
	Name = "Auto Collect Chrismas Gift ❄️",
	Callback = function()
      		loadstring(game:HttpGet("https://pastebin.com/raw/EekcdYVL"))()
  	end    
})

Tab:AddButton({
	Name = "Stop Collect Chrismas Gift ❄️",
	Callback = function()
      		loadstring(game:HttpGet("https://pastebin.com/raw/z2M4vJuZ"))()
  	end    
})

local Section = Tab:AddSection({
	Name = "BloxFruit 🎄"
})

Tab:AddButton({
	Name = "Annie Hub ❄️",
	Callback = function()
      		loadstring(game:HttpGet("https://raw.githubusercontent.com/Anniecuti/Free-Scr/main/Annie-Hub.lua"))()
  	end    
})

Tab:AddButton({
	Name = "Halox Hub ❄️",
	Callback = function()
      		loadstring(game:HttpGet('https://raw.githubusercontent.com/HALOxHUB/ScriptLoader/main/Loader.lua')())
  	end    
})

Tab:AddButton({
	Name = "Night Hub ❄️",
	Callback = function()
      		loadstring(game:HttpGet("https://raw.githubusercontent.com/NIGHTHUBONTOP/Main/main/NightHub.lua"))()
  	end    
})

Tab:AddButton({
	Name = "Hoho Hub ❄️",
	Callback = function()
      		loadstring(game:HttpGet('https://raw.githubusercontent.com/acsu123/HOHO_H/main/Loading_UI'))()
  	end    
})

Tab:AddButton({
	Name = "Domadic Hub ❄️",
	Callback = function()
      		loadstring(game:HttpGet("https://raw.githubusercontent.com/Domadicoof/Domadicoof/main/Domadichub/NottoGay/Start.ranscript"))()
  	end    
})

Tab:AddButton({
	Name = "Dragon Hub ❄️",
	Callback = function()
      		loadstring(game:HttpGet("https://raw.githubusercontent.com/ahmadsgamer2/Dragon-Hub/main/Script-Execute.lua"))()
  	end    
})

Tab:AddButton({
	Name = "Phantom Hub ❄️",
	Callback = function()
      		loadstring(game:HttpGet("https://raw.githubusercontent.com/ao-0/Banana-Inc/main/BananaPortableLoader.rbxm"))()
  	end    
})

Tab:AddButton({
	Name = "Xero Hub ❄️",
	Callback = function()
      		loadstring(game:HttpGet("https://raw.githubusercontent.com/Xero2409/XeroHub/main/xero.lua"))()
  	end    
})

local Section = Tab:AddSection({
	Name = "Break In 2 🎄"
})
Tab:AddButton({
	Name = "Breaking Blitz ❄️",
	Callback = function()
      		loadstring(game:HttpGet("https://raw.githubusercontent.com/RScriptz/RobloxScripts/main/BreakIn2.lua"))()
  	end   
 })
  
Tab:AddButton({
	Name = "items Giver ❄️",
	Callback = function()
      		loadstring(game:HttpGet("https://freenote.biz/raw/qLlMYwbVNd",true))()
  	end    
})

Tab:AddButton({
	Name = "Harlen Hub ❄️",
	Callback = function()
      		loadstring(game:HttpGet("https://raw.githubusercontent.com/harlenscripts/HarlenHub/main/HarlenScripts"))()
  	end    
})

Tab:AddButton({
	Name = "Dark Hub ❄️",
	Callback = function()
      		loadstring(game:HttpGet("https://raw.githubusercontent.com/D8rkX/D8rk-Hub/main/Games/Break%20In%202.lua",true))()
  	end    
})

local Section = Tab:AddSection({
	Name = "Evade 🎄"
})

Tab:AddButton({
	Name = "9Strew Evade ❄️",
	Callback = function()
      		loadstring(game:HttpGet('https://raw.githubusercontent.com/9Strew/roblox/main/gamescripts/evade.lua'))()
  	end    
})

Tab:AddButton({
	Name = "Hydra Network ❄️",
	Callback = function()
      		loadstring(game:HttpGet("https://pastebin.com/raw/6BbcWQJs"))()
  	end    
})

Tab:AddButton({
	Name = "Tbao Hub ❄️",
	Callback = function()
      		loadstring(game:HttpGet("https://raw.githubusercontent.com/tbao143/thaibao/main/TbaoHubEvade"))()
  	end    
})

local Section = Tab:AddSection({
	Name = "Brookhaven 🎄"
})

Tab:AddButton({
	Name = "Ice Hub ❄️",
	Callback = function()
      		loadstring(game:HttpGet("https://raw.githubusercontent.com/IceMael7/NewIceHub/main/Brookhaven"))()
  	end    
})

Tab:AddButton({
	Name = "Redz Hub ❄️",
	Callback = function()
      		loadstring(game:HttpGet("https://scriptblox.com/raw/Brookhaven-RP-REDz-HUB-6559"))()
  	end    
})

Tab:AddButton({
	Name = "Owl Hub ❄️",
	Callback = function()
      		loadstring(game:HttpGet("https://raw.githubusercontent.com/CriShoux/OwlHub/master/OwlHub.txt"))();
  	end    
})

Tab:AddButton({
	Name = "Mateon Hub ❄️",
	Callback = function()
      		loadstring(game:HttpGet("https://raw.githubusercontent.com/Hydro4Music/MeteonHub/ad8bbba8b8e492674c382b7992f05ce7fa130e87/Brookhaven"))()
  	end    
})

Tab:AddButton({
	Name = "Antares Hub ❄️",
	Callback = function()
      		loadstring(game:HttpGet("https://raw.githubusercontent.com/BorisLua/AntaresHubSuaMaeNaMinhaCama/main/AntaresHub.lua"))()
  	end    
})

Tab:AddButton({
	Name = "SalaKitos Hub ❄️",
	Callback = function()
      		loadstring(game:HttpGet("https://raw.githubusercontent.com/SAKALITOS/Salakitoshub/main/scriptSK"))()
  	end    
})

Tab:AddButton({
	Name = "Meta Hub ❄️",
	Callback = function()
      		loadstring(game:HttpGet("https://raw.githubusercontent.com/NocturneMoDz/BROOKHAVEN-GUI-/main/METAB", true))()
  	end    
})

local Section = Tab:AddSection({
	Name = "Murder Mystery 2 🎄"
})

Tab:AddButton({
	Name = "Darkxy Hub ❄️",
	Callback = function()
      		loadstring(game:HttpGet(('https://raw.githubusercontent.com/Psxvoidyx/Murdermysvoid2/main/Darkxyz23'),true))()
  	end    
})

Tab:AddButton({
	Name = "Eclipse Hub ❄️",
	Callback = function()
      		loadstring(game:HttpGet("https://pastebin.com/raw/gZH7sjgq"))()
  	end    
})

Tab:AddButton({
	Name = "Drifter MM2 ❄️",
	Callback = function()
      		loadstring(game:HttpGet("https://raw.githubusercontent.com/Drifter0507/GUIS/main/MURDER%20MYSTERY%202"))()
  	end    
})

local Section = Tab:AddSection({
	Name = "Doors 🎄"
})

Tab:AddButton({
	Name = "Doors Script ❄️",
	Callback = function()
      		loadstring(game:HttpGet('https://pastebin.com/raw/R8QMbhzv),true'))()
  	end    
})

Tab:AddButton({
	Name = "Poop Hub Doors ❄️",
	Callback = function()
      		loadstring(game:HttpGet(("https://raw.githubusercontent.com/mstudio45/poopdoors_edited/main/poopdoors_edited.lua"),true))()
  	end    
})

Tab:AddButton({
	Name = "Vynixius ❄️",
	Callback = function()
      		loadstring(game:HttpGet("https://raw.githubusercontent.com/RegularVynixu/Vynixius/main/Doors/Script.lua"))()
  	end    
})

Tab:AddButton({
	Name = "Tablet Rooms ❄️",
	Callback = function()
      		loadstring(game:HttpGet('https://raw.githubusercontent.com/DeividComSono/Scripts/main/Scanner.lua'))()
  	end    
})

Tab:AddButton({
	Name = "King Hub ❄️",
	Callback = function()
      		loadstring(game:HttpGet(('https://pastebin.com/raw/R8QMbhzv')))()
  	end    
})

local Section = Tab:AddSection({
	Name = "Arsenal  🎄"
})

Tab:AddButton({
	Name = "Bolts Hub ( OP ) ❄️",
	Callback = function()
      		loadstring(game:HttpGet("https://raw.githubusercontent.com/fusiongreg/BoltsHubV5/main/Main"))()
  	end    
})

Tab:AddButton({
	Name = "DexHub Script Arsenal ❄️",
	Callback = function()
      		loadstring(game:HttpGet("https://raw.githubusercontent.com/HonestlyDex/DexHub/main/Arsenal"))()
  	end    
})

local Section = Tab:AddSection({
	Name = "Fishing Simulator 🎄"
})

Tab:AddButton({
	Name = "SLH Hub ❄️",
	Callback = function()
      		loadstring(game:HttpGet("https://raw.githubusercontent.com/SmellLikeHacker/MyEdit/main/Hub"))()
  	end    
})

Tab:AddButton({
	Name = "Ansit Hub ❄️",
	Callback = function()
      		loadstring(game:HttpGet("https://raw.githubusercontent.com/AnSitDz/AnSitHub/main/FishingSimulator"))()
  	end    
})

local Section = Tab:AddSection({
	Name = "Da Hood 🎄"
})

Tab:AddButton({
	Name = "OP Script ❄️",
	Callback = function()
      		loadstring(game:HttpGet('https://pastebin.com/raw/XXAWmifh'))()
  	end    
})

Tab:AddButton({
	Name = "DIAMG Script ❄️",
	Callback = function()
      		loadstring(game:HttpGet('https://raw.githubusercontent.com/Dimag16/DimagX_NEW/main/dimagx', true))()
  	end    
})

Tab:AddButton({
	Name = "Hood Aim Trailer ❄️",
	Callback = function()
      		loadstring(game:HttpGet("https://raw.githubusercontent.com/Nosssa/NossLock/main/WinterTime"))()
  	end    
})

Tab:AddButton({
	Name = "FADED Script ❄️",
	Callback = function()
      		loadstring(game:HttpGet('https://pastebin.com/raw/HdExQysw'))()
  	end    
})

Tab:AddButton({
	Name = "Seller Gui Da Hood ❄️",
	Callback = function()
      		loadstring(game:HttpGet("https://raw.githubusercontent.com/Crostide/cdhc/main/gui"))()
  	end    
})

Tab:AddButton({
	Name = "OP DAHOOD STREAMBLE LOCK ❄️",
	Callback = function()
      		loadstring(game:HttpGet"https://pastebin.com/UQVqNThV")()
  	end    
})

Tab:AddButton({
	Name = "SPACE X Da Hood ❄️",
	Callback = function()
      		loadstring(game:HttpGet("https://raw.githubusercontent.com/spacexrandom/Lua/main/DaHood", true))()
  	end    
})

local Section = Tab:AddSection({
	Name = "3008 🎄"
})

Tab:AddButton({
	Name = "Auto Get Food ❄️",
	Callback = function()
      		loadstring(game:HttpGet("https://rawscripts.net/raw/3008-2.71-OP-GET-FOOD-5538"))()
  	end    
})

Tab:AddButton({
	Name = "No Fall Damage ❄️",
	Callback = function()
      		loadstring(game:HttpGet("https://pastebin.com/raw/NDR5JTEY"))()
  	end    
})

Tab:AddButton({
	Name = "3008 Uni Hub ❄️",
	Callback = function()
      		loadstring(game:HttpGet("https://pastebin.com/raw/Xwk6sgeY"))()
  	end    
})

local Section = Tab:AddSection({
	Name = "BABFT 🎄"
})

Tab:AddButton({
	Name = "Cndy Frm ❄️",
	Callback = function()
      		loadstring(game:HttpGet("https://shz.al/PZ6M"))()
  	end    
})

Tab:AddButton({
	Name = "Ruby Hub ❄️",
	Callback = function()
      		loadstring(game:HttpGet("https://raw.githubusercontent.com/Deni210/main/main/RubyHub.lua", true))()
  	end    
})

Tab:AddButton({
	Name = "VipFirst Hub ❄️",
	Callback = function()
      		loadstring(game:HttpGet('https://raw.githubusercontent.com/VIPFirstTime/UploadFile/main/Protected_8627265294288055.lua'))()
  	end    
})

Tab:AddButton({
	Name = "NeverloseHub Key Is Beta ❄️",
	Callback = function()
      		loadstring(game:HttpGet("https://raw.githubusercontent.com/Mana42138/Neverlose-UI/main/Scripts/Build%20A%20Boat.lua"))()
  	end    
})

local Section = Tab:AddSection({
	Name = "Arm Wrestle Simulator 🎄"
})

Tab:AddButton({
	Name = "Pikachu Hub ❄️",
	Callback = function()
      		loadstring(game:HttpGet("https://api.luarmor.net/files/v3/loaders/99d16edc79729a038994f85ce7335971.lua"))()
  	end    
})

Tab:AddButton({
	Name = "Op Script ❄️",
	Callback = function()
      		loadstring(game:HttpGet("https://pastebin.com/raw/6TmL5ZXG"))()
  	end    
})

local Tab = Window:MakeTab({
	Name = "Script Hub ❄️",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false})

Tab:AddButton({
	Name = "BidoSkins Hub ❄️",
	Callback = function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/BidoSkinsYT/BidoSkinsYT/main/Bido%20Skins%20V1.8"))()
  	end    
})

Tab:AddButton({
	Name = "BT Project Hub ❄️",
	Callback = function()
    loadstring(game:HttpGet("https://scriptblox.com/raw/Universal-Script-BT-Project-8158"))()
  	end    
})

Tab:AddButton({
	Name = "Alexis Universal Script ❄️",
	Callback = function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Smallgames455/Universe-Script-V2/main/Universal%20Script%20V2"))();
  	end    
})

local Tab = Window:MakeTab({
	Name = "Executor UI 🎄",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false})
	
	Tab:AddButton({
	Name = "Arceus X V3 ❄️",
	Callback = function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/AZYsGithub/chillz-workshop/main/Arceus%20X%20V3"))()
  	end    
})

Tab:AddButton({
	Name = "Synapse X ❄️",
	Callback = function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/AZYsGithub/Chillz-s-scripts/main/Synapse-X-Remake.lua"))()
  	end    
})

Tab:AddButton({
	Name = "KRNL ❄️",
	Callback = function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/wtfplayer/redemption/main/krnlnoui.lua"))()
  	end    
})

Tab:AddButton({
	Name = "PxyPixel ❄️",
	Callback = function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/k00pz/Brandnew-ahh-ked/main/the-first-executer-from-pxypixel"))()
  	end    
})

local Tab = Window:MakeTab({
	Name = "Misc Script 🎄",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false})

local Section = Tab:AddSection({
	Name = "FE Script ❄️"
})

Tab:AddButton({
	Name = "Fe Emote UI ❄️",
	Callback = function()
    loadstring(game:HttpGet("https://pastebin.com/raw/eCpipCTH"))()
  	end    
})
local Section = Tab:AddSection({
	Name = "RTX Shaders 🎄"
})

Tab:AddButton({
	Name = "RTX ( Low ) ❄️",
	Callback = function()
    loadstring(game:HttpGet(('https://pastebin.com/raw/beJhkj3m'),true))()
  	end    
})

Tab:AddButton({
	Name = "RTX ( Medium ) ❄️",
	Callback = function()
    loadstring(game:HttpGet(('https://pastebin.com/raw/bEL98kZE'),true))()
  	end    
})

Tab:AddButton({
	Name = "RTX ( High ) ❄️",
	Callback = function()
    loadstring(game:HttpGet(('https://pastefy.app/BIr8OzrR/raw'),true))()
  	end    
})

Tab:AddButton({
	Name = "RTX ( Ultra ) ❄️",
	Callback = function()
    loadstring(game:HttpGet(('https://pastebin.com/raw/uqD7VqQU'),true))()
  	end    
})
