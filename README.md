# PIA Servers
This repository contains an automatically updated list of all Private Internet Access servers

![Servers](https://img.shields.io/badge/servers-1856-brightgreen) ![Last update](https://img.shields.io/badge/last%20update-2020--09--23%2017%3A32-brightgreen) 

<a href="https://www.buymeacoffee.com/Lars-" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-orange.png" alt="Buy Me A Coffee" height="60" style="height: 60px !important;width: 217px !important;" ></a>

## Why?
Private Internet Access was unable to send a list of IPs and just said that I should "reconfigure my device", whatever that means.
On some forums I read that they don't share it, because Hulu could then block all of them. Yes, this could be true, but NordVPN also publishes their list of VPNs and they don't seem to have any problems.

## How does it work?
PIA rotates their IPs via DNS. When you open one of their provided OVPN files, you will see something like:
`remote au-melbourne.privateinternetaccess.com 1198`. When you check the A record of au-melbourne.privateinternetaccess.com, you will find one or more IPs (but never all), these are the server IPs.
You could check every 120s if there is a new IP available, or you could let me do it.

This repository is automatically updated with all the IPs that have been seen in the past 2 days. That means that if PIA disables a server, it will take approximately 2 days for it to dissapear here.
The repository is updated every hour if something has changed.

## The full list
Private Internet Access provides two types, the normal servers and the "nextgen servers" which should be faster. This repository will provide both.

Region | Normal | Nextgen | Combined
------ | ------ | ------- | --------
AU Melbourne | [10 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/AU%20Melbourne) | [17 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/AU%20Melbourne) | [17 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/AU%20Melbourne)
AU Perth | [3 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/AU%20Perth) | [16 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/AU%20Perth) | [16 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/AU%20Perth)
AU Sydney | [12 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/AU%20Sydney) | [17 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/AU%20Sydney) | [17 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/AU%20Sydney)
Albania | [1 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Albania) | [0 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Albania) | [0 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Albania)
Argentina | [1 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Argentina) | [9 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Argentina) | [9 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Argentina)
Austria | [2 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Austria) | [19 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Austria) | [19 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Austria)
Belgium | [7 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Belgium) | [17 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Belgium) | [17 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Belgium)
Bosnia and Herzegovina | [1 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Bosnia%20and%20Herzegovina) | [0 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Bosnia%20and%20Herzegovina) | [0 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Bosnia%20and%20Herzegovina)
Bulgaria | [1 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Bulgaria) | [10 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Bulgaria) | [10 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Bulgaria)
CA Montreal | [3 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/CA%20Montreal) | [26 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/CA%20Montreal) | [26 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/CA%20Montreal)
CA Ontario | [17 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/CA%20Ontario) | [0 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/CA%20Ontario) | [0 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/CA%20Ontario)
CA Toronto | [5 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/CA%20Toronto) | [26 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/CA%20Toronto) | [26 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/CA%20Toronto)
CA Vancouver | [4 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/CA%20Vancouver) | [0 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/CA%20Vancouver) | [0 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/CA%20Vancouver)
Czech Republic | [3 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Czech%20Republic) | [20 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Czech%20Republic) | [20 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Czech%20Republic)
DE Berlin | [6 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/DE%20Berlin) | [22 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/DE%20Berlin) | [22 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/DE%20Berlin)
DE Frankfurt | [6 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/DE%20Frankfurt) | [24 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/DE%20Frankfurt) | [24 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/DE%20Frankfurt)
Denmark | [1 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Denmark) | [24 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Denmark) | [24 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Denmark)
Estonia | [2 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Estonia) | [0 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Estonia) | [0 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Estonia)
Finland | [2 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Finland) | [18 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Finland) | [18 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Finland)
France | [2 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/France) | [18 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/France) | [18 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/France)
Greece | [3 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Greece) | [0 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Greece) | [0 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Greece)
Hungary | [8 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Hungary) | [15 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Hungary) | [15 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Hungary)
Iceland | [2 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Iceland) | [14 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Iceland) | [14 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Iceland)
India | [3 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/India) | [19 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/India) | [19 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/India)
Ireland | [6 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Ireland) | [16 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Ireland) | [16 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Ireland)
Israel | [4 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Israel) | [14 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Israel) | [14 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Israel)
Italy | [2 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Italy) | [22 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Italy) | [22 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Italy)
Japan | [2 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Japan) | [20 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Japan) | [20 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Japan)
Latvia | [3 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Latvia) | [0 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Latvia) | [0 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Latvia)
Lithuania | [3 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Lithuania) | [0 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Lithuania) | [0 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Lithuania)
Luxembourg | [8 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Luxembourg) | [18 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Luxembourg) | [18 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Luxembourg)
Moldova | [3 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Moldova) | [9 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Moldova) | [9 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Moldova)
Netherlands | [5 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Netherlands) | [25 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Netherlands) | [25 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Netherlands)
New Zealand | [2 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/New%20Zealand) | [10 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/New%20Zealand) | [10 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/New%20Zealand)
North Macedonia | [1 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/North%20Macedonia) | [0 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/North%20Macedonia) | [0 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/North%20Macedonia)
Norway | [2 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Norway) | [22 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Norway) | [22 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Norway)
Poland | [6 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Poland) | [16 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Poland) | [16 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Poland)
Portugal | [3 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Portugal) | [0 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Portugal) | [0 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Portugal)
Romania | [6 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Romania) | [20 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Romania) | [20 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Romania)
Serbia | [1 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Serbia) | [8 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Serbia) | [8 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Serbia)
Singapore | [4 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Singapore) | [25 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Singapore) | [25 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Singapore)
Slovakia | [1 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Slovakia) | [0 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Slovakia) | [0 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Slovakia)
South Africa | [1 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/South%20Africa) | [11 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/South%20Africa) | [11 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/South%20Africa)
Spain | [2 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Spain) | [22 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Spain) | [22 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Spain)
Sweden | [2 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Sweden) | [24 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Sweden) | [24 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Sweden)
Switzerland | [7 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Switzerland) | [24 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Switzerland) | [24 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Switzerland)
Turkey | [2 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Turkey) | [14 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Turkey) | [14 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Turkey)
UAE | [1 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/UAE) | [0 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/UAE) | [0 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/UAE)
UK London | [6 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/UK%20London) | [24 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/UK%20London) | [24 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/UK%20London)
UK Manchester | [10 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/UK%20Manchester) | [26 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/UK%20Manchester) | [26 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/UK%20Manchester)
UK Southampton | [5 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/UK%20Southampton) | [0 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/UK%20Southampton) | [0 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/UK%20Southampton)
US Atlanta | [4 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/US%20Atlanta) | [22 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/US%20Atlanta) | [22 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/US%20Atlanta)
US California | [17 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/US%20California) | [25 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/US%20California) | [25 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/US%20California)
US Chicago | [8 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/US%20Chicago) | [27 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/US%20Chicago) | [27 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/US%20Chicago)
US Dallas | [7 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/US%20Dallas) | [0 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/US%20Dallas) | [0 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/US%20Dallas)
US Denver | [26 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/US%20Denver) | [25 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/US%20Denver) | [25 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/US%20Denver)
US East | [25 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/US%20East) | [0 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/US%20East) | [0 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/US%20East)
US Florida | [13 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/US%20Florida) | [25 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/US%20Florida) | [25 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/US%20Florida)
US Houston | [13 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/US%20Houston) | [25 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/US%20Houston) | [25 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/US%20Houston)
US Las Vegas | [14 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/US%20Las%20Vegas) | [0 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/US%20Las%20Vegas) | [0 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/US%20Las%20Vegas)
US New York City | [6 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/US%20New%20York%20City) | [0 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/US%20New%20York%20City) | [0 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/US%20New%20York%20City)
US Seattle | [7 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/US%20Seattle) | [23 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/US%20Seattle) | [23 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/US%20Seattle)
US Silicon Valley | [14 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/US%20Silicon%20Valley) | [21 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/US%20Silicon%20Valley) | [21 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/US%20Silicon%20Valley)
US Washington DC | [22 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/US%20Washington%20DC) | [19 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/US%20Washington%20DC) | [19 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/US%20Washington%20DC)
US West | [4 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/US%20West) | [25 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/US%20West) | [25 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/US%20West)
Ukraine | [2 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Ukraine) | [15 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Ukraine) | [15 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Ukraine)
Algeria | [0 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Algeria) | [17 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Algeria) | [17 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Algeria)
Andorra | [0 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Andorra) | [20 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Andorra) | [20 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Andorra)
Armenia | [0 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Armenia) | [11 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Armenia) | [11 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Armenia)
Bahamas | [0 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Bahamas) | [19 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Bahamas) | [19 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Bahamas)
Bangladesh | [0 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Bangladesh) | [5 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Bangladesh) | [5 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Bangladesh)
Cambodia | [0 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Cambodia) | [14 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Cambodia) | [14 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Cambodia)
China | [0 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/China) | [5 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/China) | [5 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/China)
Cyprus | [0 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Cyprus) | [17 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Cyprus) | [17 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Cyprus)
Egypt | [0 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Egypt) | [13 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Egypt) | [13 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Egypt)
Georgia | [0 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Georgia) | [14 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Georgia) | [14 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Georgia)
Greenland | [0 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Greenland) | [13 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Greenland) | [13 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Greenland)
Iran | [0 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Iran) | [17 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Iran) | [17 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Iran)
Isle of Man | [0 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Isle%20of%20Man) | [20 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Isle%20of%20Man) | [20 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Isle%20of%20Man)
Kazakhstan | [0 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Kazakhstan) | [13 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Kazakhstan) | [13 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Kazakhstan)
Liechtenstein | [0 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Liechtenstein) | [13 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Liechtenstein) | [13 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Liechtenstein)
Macao | [0 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Macao) | [5 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Macao) | [5 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Macao)
Malta | [0 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Malta) | [16 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Malta) | [16 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Malta)
Mexico | [0 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Mexico) | [17 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Mexico) | [17 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Mexico)
Monaco | [0 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Monaco) | [12 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Monaco) | [12 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Monaco)
Mongolia | [0 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Mongolia) | [5 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Mongolia) | [5 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Mongolia)
Montenegro | [0 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Montenegro) | [16 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Montenegro) | [16 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Montenegro)
Morocco | [0 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Morocco) | [10 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Morocco) | [10 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Morocco)
Nigeria | [0 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Nigeria) | [18 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Nigeria) | [18 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Nigeria)
Panama | [0 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Panama) | [15 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Panama) | [15 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Panama)
Philippines | [0 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Philippines) | [15 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Philippines) | [15 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Philippines)
Qatar | [0 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Qatar) | [13 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Qatar) | [13 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Qatar)
Saudi Arabia | [0 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Saudi%20Arabia) | [15 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Saudi%20Arabia) | [15 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Saudi%20Arabia)
Sri Lanka | [0 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Sri%20Lanka) | [13 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Sri%20Lanka) | [13 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Sri%20Lanka)
Taiwan | [0 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Taiwan) | [11 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Taiwan) | [11 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Taiwan)
US New Jersey | [0 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/US%20New%20Jersey) | [28 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/US%20New%20Jersey) | [28 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/US%20New%20Jersey)
US New York | [0 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/US%20New%20York) | [25 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/US%20New%20York) | [25 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/US%20New%20York)
US Texas | [0 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/US%20Texas) | [24 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/US%20Texas) | [24 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/US%20Texas)
United Arab Emirates | [0 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/United%20Arab%20Emirates) | [16 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/United%20Arab%20Emirates) | [16 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/United%20Arab%20Emirates)
Venezuela | [0 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Venezuela) | [16 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Venezuela) | [16 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Venezuela)
Vietnam | [0 servers](https://github.com/Lars-/PIA-servers/tree/master/normal/Vietnam) | [17 servers](https://github.com/Lars-/PIA-servers/tree/master/nextgen/Vietnam) | [17 servers](https://github.com/Lars-/PIA-servers/tree/master/combined/Vietnam)


## Disclaimer
I am not affiliated with PIA and therefore do not include any affiliate links in this repository. 
All actions could have been done by anyone. This is in no way considered or meant as hacking. 
If servers or OVPN files don't work, it is not the fault of this repository. If you don't need anything special, just use the files provided by PIA themselves.

## Ideas or contributions
Do you have an idea for this to be better/faster/more useful, please leave me a message. Also consider buying me a coffee using the button above if it helped you.