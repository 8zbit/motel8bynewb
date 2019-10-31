# motel8bynewb

43 cloned motel interiors under the pink cage
I do not use instancing, this was useful for me and some people I know so use it if you want.

I havent seen a public release of this so I wanted to share with the comunity, do not rename the ymaps it will break.
Please do not rebrand/sell and claim as your own I intend this to help the community 10/5/19 @ 7:41 EST -MrNewb

https://imgur.com/LlYxHK5


I am aware npcs spawn in these sometimes, if it bugs you use the closed pull request thanks to @nulled-team


This is the pr if youd like to copypasta, I dont recommend using it for the sake of preformance




###########resource.lua

resource_manifest_version "44febabe-d386-4d18-afbe-5e627f4af937"
this_is_a_map 'yes' 
this_is_a_map 'yes'
client_script "main.lua"



###########main.lua

Citizen.CreateThread(function()
    while (true) do
        ClearAreaOfPeds(322.69 -222.16 -37.95, 200.0, 1)
        Citizen.Wait(0)
    end
end)
