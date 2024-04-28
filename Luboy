-- Ссылка на Библиотеку
local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/Robojini/Tuturial_UI_Library/main/UI_Template_1"))()
--[[ 
В данный момент стоит тема "RJTheme3" ,
вы можете использовать другую тему приведённую ниже -
"RJTheme1"
"RJTheme2"
"RJTheme3"
"RJTheme4"
"RJTheme5"
"RJTheme6"
"RJTheme7"
"RJTheme8"
//////////////////////////////////////////////////////////////////

Что бы сделать свою тему , уберите часть скрипта из "комминтариев" ,
который находится чуть ниже , и вместо "RJTheme3" в переменной "Windows" - 
напишите переменную которая используется в скрипте чуть ниже .
]]
--[[
local colors = {
	-- Цвет фона у Секций
    SchemeColor = Color3.fromRGB(150, 72, 148),
	-- Цвет фона в правой части UI
	Background = Color3.fromRGB(15,15,15),
	-- Цвет фона в левой части UI
    Header = Color3.fromRGB(15,15,15),
	-- Цвет текста
    TextColor = Color3.fromRGB(255,255,255),
	-- Цвет фона у кнопок
    ElementColor = Color3.fromRGB(20, 20, 20)
}
]]
-- Создать окно UI
local Window = Library.CreateLib("создатель robanik", "RJTheme3")

-- Секция
local Tab = Window:NewTab("основной меню")

-- Подсекция
local Section = Tab:NewSection("подпишись на канал плз❤️❤️❤️")

-- Слайдер
Section:NewSlider("WALKSPEED", "SliderInfo", 100, 0, function(s) -- 100 (Макс. значение) | 0 (Мин. значение)
    game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = s
end)

-- Создать окно UI
local Window = Library.CreateLib("создатель robanik", "RJTheme3")

-- Секция
local Tab = Window:NewTab("основной меню 2")

-- Подсекция
local Section = Tab:NewSection("подпишись на канал плз❤️❤️❤️")

-- Слайдер
Section:NewSlider("JUMPPOWER", "SliderInfo", 400, 0, function(s) -- 400 (Макс. значение) | 0 (Мин. значение)
    game.Players.LocalPlayer.Character.Humanoid.JumpPower = s
end)
