shared.Settings = {
   Autoplay = true, -- is the autoplayer is enabled
   ReleaseDelay = 7, -- time to wait before releasing the note (in ms)
 
   Percentages = { -- accuracy percentages
       ["Sick"] = 100,
       ["Good"] = 0,
       ["Ok"] = 0,
       ["Bad"] = 0
   }
}
 
loadstring(game:HttpGet("https://raw.githubusercontent.com/Introvert1337/Releases/master/Funky%20Friday.lua"))()
