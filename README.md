# PIA Servers
This repository contains an automatically updated list of all Private Internet Access servers.

![Servers](https://img.shields.io/badge/servers-6278-brightgreen) ![Last update](https://img.shields.io/badge/last%20update-2023--04--12%2017%3A00%20CET-brightgreen)

<a href="https://www.buymeacoffee.com/Lars-" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-orange.png" alt="Buy Me A Coffee" height="60" style="height: 60px !important;width: 217px !important;" ></a>

## Check if you are connected
A little thing PIA doesn't provide is a way to check if you are connected to their network without going to their website.
Thanks to [@lucasrangit](https://github.com/lucasrangit), this can now be checked by executing the following command:
```bash
curl -s https://lars-.github.io/PIA-servers/$(curl -s https://ipinfo.io/ip)
```

When you are connected, you will see: `You are connected to PIA`.

When you are not connected, you will see: `You are not connected to PIA`.

## Why?
Private Internet Access was unable to send a list of IPs and just said that I should "reconfigure my device", whatever that means.
On some forums I read that they don't share it, because Hulu could then block all of them. Yes, this could be true, but NordVPN also publishes their list of IPs and they don't seem to have any problems.

## How does it work?
PIA rotates their IPs via DNS. When you open one of their provided OVPN files, you will see something like:
`remote au-melbourne.privateinternetaccess.com 1198`. When you check the A record of au-melbourne.privateinternetaccess.com, you will find one or more IPs (but never all), these are the server IPs.
You could check every 120s if there is a new IP available, or you could let me do it.

This repository is automatically updated with all the IPs that have been seen in the past 14 days. That means that if PIA disables a server, it will take approximately 14 days for it to dissapear here.
The repository is automatically updated four times per day.

## The full list
Private Internet Access provides two types, the normal servers and the "nextgen servers" which should be faster. This repository will provide both.

Region | Servers
------ |--------
Albania | [34](https://github.com/Lars-/PIA-servers/tree/master/regions/Albania)
Algeria | [35](https://github.com/Lars-/PIA-servers/tree/master/regions/Algeria)
Andorra | [36](https://github.com/Lars-/PIA-servers/tree/master/regions/Andorra)
Argentina | [61](https://github.com/Lars-/PIA-servers/tree/master/regions/Argentina)
Armenia | [12](https://github.com/Lars-/PIA-servers/tree/master/regions/Armenia)
AU Melbourne | [118](https://github.com/Lars-/PIA-servers/tree/master/regions/AU%20Melbourne)
AU Perth | [96](https://github.com/Lars-/PIA-servers/tree/master/regions/AU%20Perth)
AU Sydney | [111](https://github.com/Lars-/PIA-servers/tree/master/regions/AU%20Sydney)
Austria | [56](https://github.com/Lars-/PIA-servers/tree/master/regions/Austria)
Bahamas | [60](https://github.com/Lars-/PIA-servers/tree/master/regions/Bahamas)
Bangladesh | [13](https://github.com/Lars-/PIA-servers/tree/master/regions/Bangladesh)
Belgium | [44](https://github.com/Lars-/PIA-servers/tree/master/regions/Belgium)
Brazil | [61](https://github.com/Lars-/PIA-servers/tree/master/regions/Brazil)
Bulgaria | [28](https://github.com/Lars-/PIA-servers/tree/master/regions/Bulgaria)
CA Montreal | [125](https://github.com/Lars-/PIA-servers/tree/master/regions/CA%20Montreal)
CA Ontario | [122](https://github.com/Lars-/PIA-servers/tree/master/regions/CA%20Ontario)
CA Toronto | [126](https://github.com/Lars-/PIA-servers/tree/master/regions/CA%20Toronto)
CA Vancouver | [130](https://github.com/Lars-/PIA-servers/tree/master/regions/CA%20Vancouver)
Cambodia | [24](https://github.com/Lars-/PIA-servers/tree/master/regions/Cambodia)
China | [37](https://github.com/Lars-/PIA-servers/tree/master/regions/China)
Cyprus | [24](https://github.com/Lars-/PIA-servers/tree/master/regions/Cyprus)
Czech Republic | [73](https://github.com/Lars-/PIA-servers/tree/master/regions/Czech%20Republic)
DE Berlin | [106](https://github.com/Lars-/PIA-servers/tree/master/regions/DE%20Berlin)
DE Frankfurt | [114](https://github.com/Lars-/PIA-servers/tree/master/regions/DE%20Frankfurt)
Denmark | [78](https://github.com/Lars-/PIA-servers/tree/master/regions/Denmark)
Egypt | [24](https://github.com/Lars-/PIA-servers/tree/master/regions/Egypt)
Estonia | [55](https://github.com/Lars-/PIA-servers/tree/master/regions/Estonia)
Finland | [68](https://github.com/Lars-/PIA-servers/tree/master/regions/Finland)
France | [69](https://github.com/Lars-/PIA-servers/tree/master/regions/France)
Georgia | [22](https://github.com/Lars-/PIA-servers/tree/master/regions/Georgia)
Greece | [41](https://github.com/Lars-/PIA-servers/tree/master/regions/Greece)
Greenland | [52](https://github.com/Lars-/PIA-servers/tree/master/regions/Greenland)
Hong Kong | [20](https://github.com/Lars-/PIA-servers/tree/master/regions/Hong%20Kong)
Hungary | [29](https://github.com/Lars-/PIA-servers/tree/master/regions/Hungary)
Iceland | [24](https://github.com/Lars-/PIA-servers/tree/master/regions/Iceland)
India | [30](https://github.com/Lars-/PIA-servers/tree/master/regions/India)
Ireland | [85](https://github.com/Lars-/PIA-servers/tree/master/regions/Ireland)
Isle Of Man | [29](https://github.com/Lars-/PIA-servers/tree/master/regions/Isle%20Of%20Man)
Israel | [46](https://github.com/Lars-/PIA-servers/tree/master/regions/Israel)
Italy | [67](https://github.com/Lars-/PIA-servers/tree/master/regions/Italy)
Japan | [94](https://github.com/Lars-/PIA-servers/tree/master/regions/Japan)
Kazakhstan | [23](https://github.com/Lars-/PIA-servers/tree/master/regions/Kazakhstan)
Latvia | [56](https://github.com/Lars-/PIA-servers/tree/master/regions/Latvia)
Liechtenstein | [29](https://github.com/Lars-/PIA-servers/tree/master/regions/Liechtenstein)
Lithuania | [49](https://github.com/Lars-/PIA-servers/tree/master/regions/Lithuania)
Luxembourg | [56](https://github.com/Lars-/PIA-servers/tree/master/regions/Luxembourg)
Macao | [26](https://github.com/Lars-/PIA-servers/tree/master/regions/Macao)
Macedonia | [23](https://github.com/Lars-/PIA-servers/tree/master/regions/Macedonia)
Malta | [36](https://github.com/Lars-/PIA-servers/tree/master/regions/Malta)
Mexico | [84](https://github.com/Lars-/PIA-servers/tree/master/regions/Mexico)
Moldova | [24](https://github.com/Lars-/PIA-servers/tree/master/regions/Moldova)
Monaco | [22](https://github.com/Lars-/PIA-servers/tree/master/regions/Monaco)
Mongolia | [12](https://github.com/Lars-/PIA-servers/tree/master/regions/Mongolia)
Montenegro | [26](https://github.com/Lars-/PIA-servers/tree/master/regions/Montenegro)
Morocco | [24](https://github.com/Lars-/PIA-servers/tree/master/regions/Morocco)
Netherlands | [126](https://github.com/Lars-/PIA-servers/tree/master/regions/Netherlands)
New Zealand | [99](https://github.com/Lars-/PIA-servers/tree/master/regions/New%20Zealand)
Nigeria | [24](https://github.com/Lars-/PIA-servers/tree/master/regions/Nigeria)
Norway | [76](https://github.com/Lars-/PIA-servers/tree/master/regions/Norway)
Panama | [53](https://github.com/Lars-/PIA-servers/tree/master/regions/Panama)
Philippines | [36](https://github.com/Lars-/PIA-servers/tree/master/regions/Philippines)
Poland | [29](https://github.com/Lars-/PIA-servers/tree/master/regions/Poland)
Portugal | [43](https://github.com/Lars-/PIA-servers/tree/master/regions/Portugal)
Qatar | [33](https://github.com/Lars-/PIA-servers/tree/master/regions/Qatar)
Romania | [53](https://github.com/Lars-/PIA-servers/tree/master/regions/Romania)
Saudi Arabia | [27](https://github.com/Lars-/PIA-servers/tree/master/regions/Saudi%20Arabia)
Serbia | [15](https://github.com/Lars-/PIA-servers/tree/master/regions/Serbia)
Singapore | [83](https://github.com/Lars-/PIA-servers/tree/master/regions/Singapore)
Slovakia | [24](https://github.com/Lars-/PIA-servers/tree/master/regions/Slovakia)
South Africa | [52](https://github.com/Lars-/PIA-servers/tree/master/regions/South%20Africa)
Spain | [78](https://github.com/Lars-/PIA-servers/tree/master/regions/Spain)
Sri Lanka | [11](https://github.com/Lars-/PIA-servers/tree/master/regions/Sri%20Lanka)
Sweden | [90](https://github.com/Lars-/PIA-servers/tree/master/regions/Sweden)
Switzerland | [93](https://github.com/Lars-/PIA-servers/tree/master/regions/Switzerland)
Taiwan | [45](https://github.com/Lars-/PIA-servers/tree/master/regions/Taiwan)
Turkey | [37](https://github.com/Lars-/PIA-servers/tree/master/regions/Turkey)
UK London | [122](https://github.com/Lars-/PIA-servers/tree/master/regions/UK%20London)
UK Manchester | [101](https://github.com/Lars-/PIA-servers/tree/master/regions/UK%20Manchester)
UK Southampton | [102](https://github.com/Lars-/PIA-servers/tree/master/regions/UK%20Southampton)
Ukraine | [50](https://github.com/Lars-/PIA-servers/tree/master/regions/Ukraine)
United Arab Emirates | [36](https://github.com/Lars-/PIA-servers/tree/master/regions/United%20Arab%20Emirates)
US Atlanta | [124](https://github.com/Lars-/PIA-servers/tree/master/regions/US%20Atlanta)
US California | [120](https://github.com/Lars-/PIA-servers/tree/master/regions/US%20California)
US Chicago | [129](https://github.com/Lars-/PIA-servers/tree/master/regions/US%20Chicago)
US Denver | [100](https://github.com/Lars-/PIA-servers/tree/master/regions/US%20Denver)
US East | [123](https://github.com/Lars-/PIA-servers/tree/master/regions/US%20East)
US Florida | [125](https://github.com/Lars-/PIA-servers/tree/master/regions/US%20Florida)
US Houston | [99](https://github.com/Lars-/PIA-servers/tree/master/regions/US%20Houston)
US Las Vegas | [121](https://github.com/Lars-/PIA-servers/tree/master/regions/US%20Las%20Vegas)
US New York | [125](https://github.com/Lars-/PIA-servers/tree/master/regions/US%20New%20York)
US Seattle | [116](https://github.com/Lars-/PIA-servers/tree/master/regions/US%20Seattle)
US Silicon Valley | [126](https://github.com/Lars-/PIA-servers/tree/master/regions/US%20Silicon%20Valley)
US Texas | [126](https://github.com/Lars-/PIA-servers/tree/master/regions/US%20Texas)
US Washington Dc | [125](https://github.com/Lars-/PIA-servers/tree/master/regions/US%20Washington%20Dc)
US West | [126](https://github.com/Lars-/PIA-servers/tree/master/regions/US%20West)
Venezuela | [42](https://github.com/Lars-/PIA-servers/tree/master/regions/Venezuela)
Vietnam | [44](https://github.com/Lars-/PIA-servers/tree/master/regions/Vietnam)


## Disclaimer
I am not affiliated with PIA and therefore do not include any affiliate links in this repository.
All actions could have been done by anyone. This is in no way considered or meant as hacking.
If servers or OVPN files don't work, it is not the fault of this repository. If you don't need anything special, just use the files provided by PIA themselves.

## Ideas or contributions
Do you have an idea for this to be better/faster/more useful, please leave me a message. Also consider buying me a coffee using the button above if it helped you.
