# ez2_coop_mapfixes
Map fixes for my COOP fork of E:Z2 source code

Create syntax:

create { classname { "key" "value" "key" "value" ... } }

Delete syntax:

delete { #find_by_origin "0 0 0" }
delete { #find_by_keyfield "hammerid 111" }
delete { classname/targetname "" }

Edit syntax:

edit { #find_by_origin "0 0 0" values {"key" "value" "key" "value" ... } }
edit { #find_by_keyfield "hammerid 111" values {"key" "value" "key" "value" ... } }
edit { classname/targetname "" values {"key" "value" "key" "value" ... } }

Console syntax:

console { "sv_cheats" "1" }

Fire syntax:

fire { "targetname" "inputname,inputparam,inputdelay,activatorname,callername,outputid" }
