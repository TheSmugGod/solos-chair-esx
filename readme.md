# in ox_inventory
--> add png from /assets to ox_inventory/web/images

--> add the following to /data/items.lua
["portablechair"] = {
    label = 'Portable Chair',
    weight = 1,
    stack = false,
    close = true,
    description = ""
},


--> add the following to /modules/items/client.lua
Item('portablechair', function(data, slot)

		exports.portablechair:portablechairToggle()

end)



# View more FIVEM scripts and assets

https://forum.cfx.re/u/OKCRP/activity/topics <<<<
