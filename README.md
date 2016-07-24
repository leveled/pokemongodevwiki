As the community has grown over the last few weeks it is clear that some centralization of effort will be useful. There are several different projects with roughly similar aims that may benefit from cross-pollination. I intend for this post to be an up-to-date archive of projects and development resources. This will allow new developers to be able to find projects which match their interests, learn the requisite knowledge necessary to contribute, and reduce redundancy across several projects. I am not the author of any of these resources, but given that most are publicly accessible repos or websites, I assume that it is fine if I post them here. If you are the author of one of these resources and would like me to remove it, feel free to send me a PM. 


If you have a Pokémon Go resource which other developers may find useful send me a PM with a **concise description**, and I will update the list. If you want to 


#READ [THIS ](https://www.reddit.com/r/pokemongodev/comments/4td499/a_note_about_security/)BEFORE USING ANY OF THESE TOOLS!

###PLEASE DO NOT SEND ME ANY PMS ASKING QUESTIONS ABOUT PROJECTS OR HOW TO USE THEM!

###Update 7/21/16: Check out the [github page](https://github.com/leveled/pokemongodevwiki). This will allow you to see any updates that were made chronologically. If you want to change any of the content feel free to do a pull request and I will evaluate it.

###The reddit thread is [here](https://www.reddit.com/r/pokemongodev/comments/4trjum/pok%C3%A9mon_go_development_archive_works_in_progress/)


#Content
- I. Works in Progress
    - Maps
    - APIs / Libraries 
    - Mods / Other
    - Bots
- II. Game Mechanics / Resources
    - Network Communications
    - Reverse Engineering
    - Pokémon 
- III. Open Research Questions / Topics


#I. Works in Progress
#Maps 
____
####Pokémon Go Map Visualization [[Github]](https://github.com/AHAAAAAAA/PokemonGo-Map) [[Github-Android]] (https://github.com/omkarmoghe/Pokemap) [[Website]](https://jz6.github.io/PoGoMap/)
From github: 
> Live visualization of all pokemon (with option to show gyms and pokestops) in your area. This is a proof of concept that we can load all nearby pokemon given a location. Currently runs on a Flask server displaying a Google Map with markers on it.

>Using this software is against the ToS and can get you banned. Use at your own risk.

>Building off Mila432's PokemonGo API, tejado's additions, leegao's additions and Flask-GoogleMaps.

There is a guide for installation [here](https://www.reddit.com/r/pokemongodev/comments/4t80df/wip_pokemon_go_map_visualization_google_maps_view/d5feu2f).

[Discussion thread] (https://www.reddit.com/r/pokemongodev/comments/4t80df/wip_pokemon_go_map_visualization_google_maps_view/)
[Discussion thread v 2.0](https://www.reddit.com/r/pokemongodev/comments/4u6lwe/pokemap_v20_like_the_original_but_waaaaay_better/)
___
####Pokémon Go Map w/ Merged Features [[Github]](https://github.com/TheZ3ro/pkmngo-map) 

From github:
>This is a Work-In-Progress attempt to merge all Pokemon-Go-API Python project.

>Feature will be developed on base of the Project maintainer's view, so Pull-Request that don't follow his views will be rejected.

[Discussion thread] (https://www.reddit.com/r/pokemongodev/comments/4tkt8y/wip_pkmngo_map_merge_all_pythonproject_feature/) 
___

####PokéGPS [[Website]] (https://www.reddit.com/r/pokemongodev/comments/4tc33k/wip_pokegps_locate_nearby_pokemon_in_phone_browser/)

From discussion thread:
> Basically if you have your location services enabled and to GO servers are not on fire, this app queries for nearby pokemon and displays them on a map. The Pokeball = your current location returned by google apis.
The intention is for this site to work on your mobile device. So make sure that you have gone into the Privacy settings and enabled to ask for location services in your app settings if for some reason you have disabled them.
This is intended to be a extremely developmental thing at present, but is receiving tons of development time.

[Discussion thread]
(https://www.reddit.com/r/pokemongodev/comments/4tc33k/wip_pokegps_locate_nearby_pokemon_in_phone_browser/)
___

####Pokémon Go Desktop App [[Github]](https://github.com/mchristopher/PokemonGo-DesktopMap/releases)

From github:
> I just finished putting together an Electron wrapper around the wonderful PokemonGo-Map project.
My next step is 1-click tunnel support so you can pull it up on your iPhone/Android while you're out and about.

[Discussion thread] ( https://www.reddit.com/r/pokemongodev/comments/4tojmo/pokemon_go_map_desktop_app/)
___

####Pokémon Go iOS App [[Github]] (https://github.com/ruffnecktsk/pokemap_live_ios)

From github: 
> iOS application with live pokemon go map

____

####Pokémon Go Map for Telegram [[Github]] (https://github.com/robbcocco/PokemonGo-Map-forTelegram)

From github:
> Live visualization of all the pokemon in your area. To use with a Telegram Bot. Request one here.

>Bot using API from nickoala's telepot.


___
####Pokémon Go Scanner (Mobile) [[Github]] (https://github.com/emeth-/pokelocater)

[Discussion thread] (https://www.reddit.com/r/pokemongodev/comments/4t995i/pokemongo_scanner_google_map_view_based_on_your/)

___

####Pokérevs Map UI [[Map]] (http://pokerev.r3v3rs3.net/mapui/#1/-0/0) [[Website]] (http://pokerev.r3v3rs3.net/) (Github repos in discussion thread)

[Discussion thread] ( https://www.reddit.com/r/pokemongodev/comments/4tj4m9/pokerevs_mapui_now_load_balanced_and_fast/)

___

####Poképosition [[Website]] (http://pokeposition.com/) 

From discussion thread
> PokePosition brings LIVE pokemon locations, gym details, lured pokestops and more, straight to your browser.

[Discussion thread] (https://www.reddit.com/r/pokemongodev/comments/4tw6x5/real_time_pokemon_go_map_straight_to_your_mobile/)

____

####Auto Updating Pokémon Go Map Scanner [[Github]](https://github.com/memelyfe/pokemongo-api-demo/tree/maps)

[Discussion thread] (https://www.reddit.com/r/pokemongodev/comments/4t8ohw/autoupdating_pokemon_go_map_scanner/) 

____

#### Live Map of Wild Pokémon [[Website]] (https://skiplagged.com/pokemon)
[Discussion thread] (https://www.reddit.com/r/pokemongodev/comments/4tm8tm/hey_guys_lets_work_together_on_a_live_map_of_wild/)

___

#APIs / Libraries 
####pgoapi - Pokémon Go API lib [[Github]] (https://github.com/tejado/pgoapi)

From github:
>pgoapi is a client/api/demo for Pokemon Go by https://github.com/tejado.
It allows automatic parsing of requests/responses by finding the correct protobuf objects over a naming convention and will return the response in a parsed python dictionary format.

[Discussion thread] (https://www.reddit.com/r/pokemongodev/comments/4tmdkt/pgoapi_rewrite_of_pokemonapidemo/) 

___

####Pokémon Go Proto Files [[Github]] (https://github.com/AeonLucid/POGOProtos)

From github: 
> This repository contains the ProtoBuf .proto files needed to decode the PokémonGo RPC.

____

#### Pokémon Go C# Library [[Github]](https://github.com/AeonLucid/POGOLib) 

From github:
> POGOLib is written in C# and aims to be a community-driven PokémonGo API. Feel free to submit pull requests.

____

####Client API Library in C# [[Github]] (https://github.com/FeroxRev/Pokemon-Go-Rocket-API)

[Discussion thread] (https://www.reddit.com/r/pokemongodev/comments/4thw89/client_api_library_for_pokemon_go_in_c/)

___
####Opensource C# API [[Github]](https://github.com/ernilos/PokemonGoApi)

From github:
> An API developed in C# with the premise to interact with Pokémon GO server.

[Discussion thread] (https://www.reddit.com/r/pokemongodev/comments/4tfszb/net_opensource_c_api/)
___
#### Java API [[Github]] ( https://github.com/Grover-c13/PokeGOAPI-Java/)

[Discussion thread] (https://www.reddit.com/r/pokemongodev/comments/4t65mh/pokemongo_api_java_01/)

___

####Node API [[Github]] ( https://github.com/Armax/Pokemon-GO-node-api) 

From github:
> Pokemon GO api node.js library, still WIP
Check main.js for examples
___

####Swift API [[Github]] (https://github.com/lsapan/pgoapi-swift)

From github:
> This API is very much a work in progress, but it allows you to authenticate to the servers, as well as request information about the player, inventory, etc.

____

#Mods / Other

####Pokémon Go Notification System [[Github]] (https://github.com/jxmorris12/PokemonGo-Finder) 

From github:
> This is a fork of the popular PokemonGo-Map repository with the purpose of allowing users to search for specific Pokemon without having to constantly monitor the map of nearby Pokemon. This allows users to set a list of sought-after Pokemon and receive notifications through Pushbullet. All API and map functionality was left untouched.

[Discussion thread] (https://www.reddit.com/r/pokemongodev/comments/4tp9jh/receive_notifications_when_rare_pokemon_pop_up/)
___

####Pokémon Go MITM Node [[Github]] (https://github.com/rastapasta/pokemon-go-mitm-node)

From github:
> Pokemon Go MITM Proxy - Intercepts the traffic between your Pokemon Go App and their servers, decodes the protocol and gives you a handy tool to enrich your own game experience by altering the data on the fly.


[Discussion thread] (https://www.reddit.com/r/pokemongodev/comments/4tp5t3/mod_ingame_radar_created_an_opensource_software/)

___

####Pokémon Go MITM .Net Proxy [[Github]] (https://github.com/cstrachan88/PoGo-Proxy.NET)

From github: 
> This project is a .net MITM proxy designed to read all the API messages sent between the Pokemon Go device and the Pokemon Go servers. By reading this data, you can make informed decisions about which Pokemon to keep, and so on.


___


####Pokémon Go Optimizer [[Github]] (https://github.com/justinleewells/pogo-optimizer)

From github:
> This tool shows you the IVs and information necessary to determine which Pokemon get ground into candy. Perfect for any trainer aspiring to be the very best.


___


####Pokémon Go Plus [[Github]] (https://github.com/rubenvereecken/PokemonGo-Enhanced)

From github:
>While this repository does not come with a lot of content, it does come with a dream.

>It's simple in essence. Make Pokemon Go more awesome by giving an edge over others (face it, that's why most are here) but still making it fun to play by actually going out there.

>This repository will contain a single-deploy suite of nifty little things that together will make up Pokemon Go Enhanced. What follows is a little overview of dreams (or as devs like to call it, a TODO list).

___
####Pokémon Go Web Spoof [[Github]] (https://github.com/iam4x/pokemongo-webspoof)

From github:
>Spoof your iOS device GPS location for Pokémon Go

[Discussion thread] (https://www.reddit.com/r/pokemongodev/comments/4tca4k/v101_pokemongowebspoofapp_play_pok%C3%A9mon_go_from/) 

___

####Pokémon Go IV Miner [[Website]] (http://www.pokemongonexus.com/


From website:
>Pokémon Go Nexus provides you with an easy way to see all of your pokémons' IVs! Just walk through the following steps so we can securely grab your Pokémon GO data.

___


####MITMDump Decoder [[Github]] (https://github.com/bettse/mitmdump_decoder)

From github:
>A helper script for mitmproxy to decode protobuf serialized requests and responses. It is primarily intended to help in validating the IDLs for the protocol. As a intereting diversion, it also parses the GetMapObjects responses into a geojson format file that can be viewed using the 'ui'. The ui is completely clientside, so it should be hostable with any static file server (I use 'http-server').

___

####SFIDA [[Github]] (https://github.com/numinit/porygon/wiki/protocol)

From github:
>The Pokémon Go Plus (codenamed "Sfida") is a battery-powered Bluetooth LE bracelet.

From discussion thread: 
> My aim with porygon is to make the wristband more useful. For what it's worth, I don't think it straddles the "cheating" line, so it should be usable without fearing the banhammer.
At present, it's still in progress, mainly because Go doesn't have wristband support wired up yet.

___
#Bots 

####Python Pokémon Go Bot [[Github]] (https://github.com/TomTheBotter/Pokemon-Go-Bot-Working-Hack-API)

From github:
> This is one of the fastest bot that farms for Pokestops and Pokemon and super easy to level up. Incubate and hatch eggs by walking or catch rare pokemon fast! No bans with correct use as of now. Use with caution as with all bots. 


[Discussion thread] (https://www.reddit.com/r/pokemongodev/comments/4ubwh0/open_source_pokemon_go_bot_very_fast120_in_56_hrs/)
___
####Python Pokémon Go Bot [[Github]](https://github.com/PokemonGoF/PokemonGo-Bot)

From github:
>Features:

>Search Fort(Spin Pokestop)
Catch Pokemon
Release low cp pokemon
Walking as you

___

####Python Pokémon Go Bot [[Github]](https://github.com/eggins/Pokemon-Go-Automation)

From github:
> A Pokemon Go Bot (work in progress) This will contain all of my updates and slow build progress on a fully automated Pokemon Go bot. More than happy to take on someone with me to build something awesome

____

####Python Pokémon Go Bot [[Github]](https://github.com/j-e-k/pgoapi)

From Discussion: 
> Based on tejado/pgoapi (thanks). It does catching/movement/fort spinning/transferring bad pokemon. Caveat emptor, it's poorly documented and I haven't tested it on anyone else's machine...

___

####Java Pokémon Go Bot [[Github]](https://github.com/jabbink/PokemonGoBot/releases/)


___


#II. Game Mechanics / Resources
##Network Communications:
[Guide to Pokémon Go Server Responses](https://www.reddit.com/r/pokemongodev/comments/4svl1o/guide_to_pokemon_go_server_responses/)

[What we know so far](https://www.reddit.com/r/pokemongodev/comments/4scf8p/what_we_know_so_far/)

##Reverse Engineering:
[Unbundling Pokémon Go](https://applidium.com/en/news/unbundling_pokemon_go/)

##Pokémon:
Decoded GAME_MASTER protobuf file v0.1 [[protobuf]](https://gist.github.com/anonymous/077d6dea82d58b8febde54ae9729b1bf) [[.tsv]] (https://gist.github.com/anonymous/540700108cf0f051e11f70273e9e2590) [[Discussion Thread]] (https://www.reddit.com/r/pokemongodev/comments/4t59t1/decoded_game_master_protobuf_file_v01_all_pokemon/)

[Information from protobuf data-dump visualized] (http://squarecat.io/pokemongo-data/) [[Discussion thread]] ( https://www.reddit.com/r/pokemongodev/comments/4tc8ao/wip_webapp_exploiting_the_data_dumps/) 

[Max CP/HP per Pokémon (sortable)](https://www.reddit.com/r/pokemongodev/comments/4t7zt4/max_cphp_per_pokemon_in_a_sortable_chart/)

[Pokémon CP/HP Ranges](https://docs.google.com/spreadsheets/d/19iql4aABmZ5oZ6YDE3LmZ8qcth3UoH52954WhjuiJow/edit#gid=1488557536)

[Guide to figuring out Pokémon level from CP/HP](https://www.reddit.com/r/pokemongodev/comments/4takbp/guide_to_figuring_out_your_pokemons_level_from_cp/)

[Exact CP Formula] (https://www.reddit.com/r/pokemongodev/comments/4t7xb4/exact_cp_formula_from_stats_and_cpm_and_an_update/)

[How HP/Max Stamina is Calculated] (https://www.reddit.com/r/pokemongodev/comments/4t0xd1/how_hpmaxstamina_is_calculated/)

From [here](https://www.reddit.com/r/TheSilphRoad/comments/4tm8io/pokemon_go_link_dump/d5imx7t):

[Evolution Calculator](https://3edgy6u.com/misc/pogoevo.html)  
[Evolution Calculator 2](http://pidgeycalc.com/)   
[Evolution Calculator for Android](https://play.google.com/store/apps/details?id=com.pokefam.evolution.calculator.pokego)   
[Best Moveset](https://www.reddit.com/r/TheSilphRoad/comments/4teoe2/best_move_sets_and_matchups_v2/)  
[Evolution CP Calculator](http://pogotoolkit.com/)  
[Max CP](http://pokemongo.gamepress.gg/pokemon-list)  
[How Battling Works](https://www.youtube.com/watch?v=Df-5-1D4ZrI)  
[Pokemon Stats](https://thesilphroad.com/research)  
[Automatic IV Calculator](https://docs.google.com/spreadsheets/d/1wbtIc33K45iU1ScUnkB0PlslJ-eLaJlSZY47sPME2Uk/copy)  
[Weakness Chart](https://i.redd.it/oy7lrixl8r9x.png)  
[CP per level up](http://i.imgur.com/uoIJjdz.png)  
[Pokemon Go Database](http://pokemongo.gamepress.gg/)  





___

#III. Open Research Questions / Topics 


[Collecting all spawns to eliminate API calls] (https://www.reddit.com/r/pokemongodev/comments/4t7zt4/max_cphp_per_pokemon_in_a_sortable_chart/) 

[Collecting spawn data via location/time] (https://www.reddit.com/r/pokemongodev/comments/4tl8qq/we_dont_need_apis_for_spawns_if_we_track/)

[Spawn location research] (https://www.reddit.com/r/pokemongodev/comments/4tu584/some_spawn_location_research/)
