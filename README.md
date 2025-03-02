# awesome-meshtastic
[![](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

**A curated list of amazingly awesome Meshtastic resources**

Note: Meshtastic® is a registered trademark of [Meshtastic LLC](https://meshtastic.org/docs/legal/licensing-and-trademark/). Use in this repository is for reference only and does not imply sponsorship or endorsement by Meshtastic LLC.

## How to Contribute? 
* Option #1 - [File a PR](https://github.com/ShakataGaNai/awesome-meshtastic/pulls). 
* Option #2 - [Create an issue](https://github.com/ShakataGaNai/awesome-meshtastic/issues)
* Option #3 - Join the offical [Meshtastic Discord](https://discord.com/invite/ktMAKGBnBs) and post in the [Awesome Meshtastic project](https://discord.com/channels/867578229534359593/1246235089281749053)

--------------------

## Table of contents

- [Official Resources](#official-resources)
- [Guides & Getting Started](#guides--getting-started)
- [Maps and Diagnostics](#maps-and-diagnostics)
- [Server Software](#server-software)
- [Local Software](#local-software)
- [Hacks and Projects](#hacks-and-projects)
- [Hardware Stores](#hardware-stores)
- [Communities](#communities)
  - [Virtual](#virtual)
  - [Australia](#australia)
  - [Canada](#canada)
    - [Alberta](#alberta)
    - [British Columbia](#british-columbia)
    - [Manitoba](#manitoba)
    - [New Brunswick](#new-brunswick)
    - [Newfoundland](#newfoundland)
    - [Northwest Territories](#northwest-territories)
    - [Nova Scotia](#nova-scotia)
    - [Ontario](#ontario)
    - [Prince Edward Island](#prince-edward-island)
    - [Quebec](#quebec)
    - [Saskatchewan](#saskatchewan)
  - [Finland](#finland)
  - [Germany](#germany)
  - [India](#india)
  - [Italy](#italy)
  - [Lithuania](#lithuania)
  - [The Netherlands](#the-netherlands)
  - [Poland](#poland)
  - [Taiwan](#taiwan)
  - [Türkiye](#türkiye)
  - [Ukraine](#ukraine)
  - [United Kingdom](#united-kingdom)
  - [USA](#usa)
    - [Arkansas](#arkansas)
    - [California](#california)
    - [Colorado](#colorado)
    - [Florida](#florida)
    - [Hawaii](#hawaii)
    - [Illinois](#illinois)
    - [Massachusetts](#massachusetts)
    - [Michigan](#michigan)
    - [New Mexico](#new-mexico)
    - [Oklahoma](#oklahoma)
    - [Tennessee](#tennessee)
    - [Texas](#texas)
    - [Virginia](#virginia)
    - [Washington](#washington)


--------------------
## Official Resources

**[`^        back to top        ^`](#awesome-meshtastic)**

Everything from the offical Meshtastic project

- [Meshtastic.org](https://meshtastic.org/) - The homepage & official documentation
- [Donate to Meshtastic](https://opencollective.com/meshtastic) - Support the Meshtastic project and development on OpenCollective
- [Firmware on Github](https://github.com/meshtastic/firmware)
- [All Downloads](https://meshtastic.org/downloads/)
  - [Web Flasher](https://flasher.meshtastic.org/)
  - [iOS App](https://itunes.apple.com/WebObjects/MZStore.woa/wa/viewSoftware?id=1586432531)
  - [Android App](https://play.google.com/store/apps/details?id=com.geeksville.mesh)
  - [Web App](https://client.meshtastic.org/)
- [r/Meshtastic](https://www.reddit.com/r/meshtastic/) on reddit

## Guides & Getting Started

**[`^        back to top        ^`](#awesome-meshtastic)**

A collection of useful guides and getting started information for the new Meshtastic users.

- ["How does it Work" by AustinMesh](https://austinmesh.org/#how-does-it-work) - Some suggested settings are AustinMesh specific, but in general it's useful for anyone
- ["Getting Started with Meshtastic" by The Comms Channel (YouTube)](https://www.youtube.com/playlist?list=PLshzThxhw4O5JTOACGHzYSSd3soDhoXKK)
- [Antenna Reports](https://github.com/meshtastic/antenna-reports) - Official Meshtastic community antenna reports
- [Meshtastic RF Connector Types](https://pole1.co.uk/blog/5/) - Visual dictionary of RF connector types commonly found on Meshtastic radios and antennas. Many detailed macro photos.

## Maps and Diagnostics

**[`^        back to top        ^`](#awesome-meshtastic)**

Tools for the every-user to see whats going on in general.

- [Meshtastic Map](https://meshtastic.liamcottle.net/) by Liam Cottle - [Source code](https://github.com/liamcottle/meshtastic-map)
- [Meshmap.net](https://meshmap.net/) - [Source code](https://github.com/brianshea2/meshmap.net)

## Server Software

**[`^        back to top        ^`](#awesome-meshtastic)**

For software tools developed specifically for meshtastic but probably require running for yourself or your local mesh. Typically hosted on a server. You probably don't need to know how to run it, to use it.

- [Meshview by Armoo](https://github.com/armooo/meshview) - A project watches a MQTT topic for meshtastic messages, imports them to a database and has a web UI to view them. [Example on BayMesh](https://meshview.bayme.sh/)
- [Meshinfo by kevinelliott](https://github.com/kevinelliott/meshinfo) - A project written in Python and connects to an MQTT server that is receiving Meshtastic messages for the purpose of visualizing and inspecting traffic. [Example on SacValleyMesh](https://svm.meshinfo.network/mqtt_log.html)
- [bayme.sh-bot by ppicazo](https://github.com/ppicazo/bayme.sh-bot) - An MQTT to Discord logger bot for local meshes. 
- [meshtastic-ha-entity-builder](https://github.com/pdxlocations/meshtastic-ha-entity-builder) - Builds entities from stored nodes using the [Meshtastic Home Assistant Integration](https://meshtastic.org/docs/software/integrations/mqtt/home-assistant/)
- [meshtastic-new-node-processing by StevoKeano](https://github.com/StevoKeano/meshtastic-new-node-processing/) - Created by the AustinMesh team to welcome new users to the public mesh and direct them to help/resources.
- [TC2-BBS-mesh by TheCommsChannel](https://github.com/TheCommsChannel/TC2-BBS-mesh) - Do you miss the good old days of dial up BBS? Now you can have one via mesh!
- [Frozen BBS](https://github.com/kstrauser/frozenbbs) - Another BBS Implementation (written in Rust)
- [Meshtastic-Matrix-Relay](https://github.com/geoffwhittington/meshtastic-matrix-relay) - Meshtastic to Matrix Relay

## Local Software

**[`^        back to top        ^`](#awesome-meshtastic)**

Is it software, but not for a server? For you, your phone or your computer? You probably need some knowledge on how to run/use these things.

- [Meshtastic-MQTT-Connect by pdxlocations](https://github.com/pdxlocations/Meshtastic-MQTT-Connect) - A python (TK/TCL) based MQTT/Meshtastic UI for your local machine.
- [MultiMesh](https://github.com/paulocode/multimesh) - A cross-platform Meshtastic client based on Flutter
- [Meshtastic-SDR](https://gitlab.com/crankylinuxuser/meshtastic_sdr) - A GnuRadio and Python based replacement for Meshtastic radio hardware. Can receive multiple presets at the same time. Currently working on TX.
- [Meshtastic-SAME-EAS-Alerter by RCGV1](https://github.com/RCGV1/Meshtastic-SAME-EAS-Alerter) - A tool to recieve alerts from the National Weather Service and broadcast them on Meshtastic
- [meshtastic-go by lmatte7](https://github.com/lmatte7/meshtastic-go) - A meshtastic CLI written in GoLang
- [Meshtastic python scripts by N7IW](https://github.com/N7IW/Meshtastic) - Various Meshtastic python scripts for experimentation
- [Meshlink](https://github.com/Murturtle/MeshLink) - Send messages and packet info to and from Discord
- [MeshTenna](https://github.com/OE3JGW/MeshTenna) - Windows/Android app for comparing the performance of different antennas and locations
- [MeshSense](https://affirmatech.com/meshsense) - Windows/Mac/Linux app for using a node over Wi-Fi or Bluetooth
- [Meshtastic Visualizer](https://github.com/antlas0/meshtastic_visualizer) - Python PyQT desktop app to interface with local nodes, or subscribing to MQTT servers
- [Meshtastic Plugin for Pidgin](https://github.com/dadecoza/pidgin-meshtastic) - A plugin to enable you to use Meshtastic with Pidgin (a multiplatform chat client)

## Hacks and Projects

**[`^        back to top        ^`](#awesome-meshtastic)**

- [Harbor Breeze Meshtastic Hack](https://hackaday.io/project/194509-harbor-breeze-meshtastic-hack) - Use the $15 Harbor Breeze Solar Light as a self contained waterproof enclosure for a WisBlock based Meshtastic Node.
- [Meshtastic-Experiments by HarukiToreda](https://github.com/HarukiToreda/Meshtastic-Experiments) - A low level collection & comparison of various Meshtastic hardware.
- [Meshpipe by Armooo](https://github.com/armooo/meshpipe) - An attempt to slurp packets out of one radio and chuck them out another (POC for a conceptual meshtastic backhaul)

## Hardware Stores

**[`^        back to top        ^`](#awesome-meshtastic)**

Reputable stores that provide quality hardware only.

- [Rokland](https://store.rokland.com/pages/meshtastic-hardware-rak-lilygo)
- [YetiWurks](https://www.yetiwurks.com/product-category/communication/)
- [Neil Hao on Tindie](https://www.tindie.com/stores/neilhao/) - For the G1 & G2 series of devices
- [LILYGO Offical Site](https://www.lilygo.cc/collections/lora-or-gps)
- [LILYGO on AliExpress](https://lilygo.aliexpress.com/store/1101195566)
- [Spec5](https://specfive.com)
- [AT Labs](https://at-labs.tech)
  
## Communities

**[`^        back to top        ^`](#awesome-meshtastic)**

All the local meshtastic communities. See also: [Local Groups on Meshtastic.org](https://meshtastic.org/docs/community/local-groups/)

### Virtual
**[`^        back to top        ^`](#virtual)**

For online communities, forums and gathering places, that are not nessisarily geographically specific.

- [Meshtastic User Group on LinkedIn](https://www.linkedin.com/groups/14499139/)

### Australia
**[`^        back to top        ^`](#awesome-meshtastic)**

- [Canberra Meshtastic Community (Discord)](https://discord.gg/4QgFsuaC3Z)
- [Meshtastic User Group Tasmania (Facebook)](https://www.facebook.com/groups/1556630645195649)
- [Meshtastic Sydney (Facebook)](https://www.facebook.com/groups/1041534027106861)
- [Meshtastic Australia (Facebook)](https://www.facebook.com/groups/1169993994163108)
- [Meshtastic Victoria (Facebook - Private)](https://www.facebook.com/groups/meshtasticvictoria)

### Canada
**[`^        back to top        ^`](#awesome-meshtastic)**

- [Canada Mesh Wiki](https://wiki.mt.gt/)
- [Mesh Canada (Telegram)](https://t.me/meshtastic_canada)

#### Alberta
- [YYC Mesh](https://yycmesh.com/)
- [Mesht Calgary (Telegram)](https://t.me/meshtcalgary)
- [Mesht Alberta (Telegram)](https://t.me/meshtAlta)

#### British Columbia
- [Meshtastic BC users group (Telegram)](https://t.me/Mesh_BC)
- [Meshtastic Dawson Creek BC users group (Telegram)](https://t.me/Mesh_BC_Dawson_Creek)

#### Manitoba
- [Mesht Manitoba (Telegram)](https://t.me/MeshtManitoba)

#### New Brunswick
- [Mesht New Brunswick (Telegram)](https://t.me/MeshtNB)

#### Newfoundland
- [Mesht Newfoundland (Telegram)](https://t.me/MeshtNewfoundland)

#### Northwest Territories
- [Mesht Northwest Territories (Telegram)](https://t.me/MeshtNWT)

#### Nova Scotia
- [Mesht Nova Scotia (Telegram)](https://t.me/MeshtNovaScotia)

#### Ontario
- [Mesht Ontario (Telegram)](https://t.me/meshtOnt)

#### Prince Edward Island
- [Mesht PEI (Telegram)](https://t.me/MeshtPEI)

#### Quebec
- [Mesht Quebec (Telegram)](https://t.me/meshtQuebec)

#### Saskatchewan
- [Mesht Saskatchewan (Telegram)](https://t.me/MeshtSaska)

### Finland
**[`^        back to top        ^`](#awesome-meshtastic)**
- [Mesh-Finland](https://mesh-finland.github.io) - [Discord](https://discord.com/invite/GHnaVAjqed)

### Germany
**[`^        back to top        ^`](#awesome-meshtastic)**
- [Meshtastic Users Germany (D-A-CH) (Telegram)](https://t.me/meshtasticgermany) - for technical chat

### India
**[`^        back to top        ^`](#awesome-meshtastic)**
- [India Bir Paragliding](https://bircom.in)

### Italy
**[`^        back to top        ^`](#awesome-meshtastic)**
- [Meshtastic Italia (Telegram)](https://t.me/meshtastic_italia)
- [Mesh ITA Club (Discord)](https://discord.gg/ETFmtyzbFT)

### Lithuania
**[`^        back to top        ^`](#awesome-meshtastic)**
- [Meshtastic Lietuva (Facebook)](https://www.facebook.com/groups/1122509422249414)

### The Netherlands
**[`^        back to top        ^`](#awesome-meshtastic)**
- [Meshtastic Netherlands (Telegram)](https://t.me/meshtastic_nl)
- [MeshNet Meshtastic Netherlands Community](https://www.meshnet.nl)

### Poland
**[`^        back to top        ^`](#awesome-meshtastic)**
- [Meshtastic Poland (Matrix)](https://matrix.to/#/#meshtasticpl:matrix.org)

### Taiwan
**[`^        back to top        ^`](#awesome-meshtastic)**
- [Meshtastic Taiwan Community 臺灣鏈網 (Facebook)](https://www.facebook.com/groups/413628121046386) - [Discord](https://discord.gg/2vZkuckp8E)

### Türkiye
**[`^        back to top        ^`](#awesome-meshtastic)**
- [TRMesh](https://trmesh.org)

### Ukraine
**[`^        back to top        ^`](#awesome-meshtastic)**
- [Meshtastic Ukraine (Telegram)](https://t.me/meshtastic_ua)

### United Kingdom
**[`^        back to top        ^`](#awesome-meshtastic)**
- [UK Meshtastic Kent / South East (Facebook)](https://www.facebook.com/groups/ukmeshtastickent/)
- [UK Meshtastic Brighton (Facebook)](https://www.facebook.com/groups/3696312513946679/)
- [UK Meshtastic North East England (Facebook)](https://www.facebook.com/groups/meshtasticnortheastengland/)
- [Swansea Meshtastic Group](https://swansea.localmesh.org/) - Wales
- [UK Meshtastic Berkshire (Facebook)](https://www.facebook.com/groups/1083395923209693)
- [UK - Berkshire (Meshtastic Offical Discord)](https://discordapp.com/channels/867578229534359593/1201610993462153376)

### USA
**[`^        back to top        ^`](#awesome-meshtastic)**

#### Arkansas
- [Fab Lab Fort Smit (Discord)](https://discord.com/invite/nwsvcXeqMX) - Fort Smith

#### California
- [BayMesh](https://bayme.sh/) - San Francisco Bay Area
- [Sac Valley Mesh](https://www.sacvalleymesh.com/) - Sacramento Valley
- [Central Valley Mesh](https://centralvalleymesh.net)
- [SoCal Mesh](https://socalmesh.org/) - Formerly Laguna Mesh
- [Mission Viejo Mesh](https://missionviejomesh.org/)
- [San Diego Mesh (Discord)](https://discord.gg/k8RputgWgD)
- [Antelope Valley Mesh](https://www.avmesh.org/)
- [AltaMesh](https://altamesh.net/) - Altadena, CA
- [Meshtastic Santa Cruz County (Groups.IO)](https://groups.io/g/Meshtastic-Santa-Cruz)
- [MontereyBayMesh](https://mrymesh.net/)

#### Colorado
- [Denver Mesh](https://denvermesh.org/)
- [Longmont Mesh](https://longmont.localmesh.org/)

#### Florida
- [Florida Meshtastic](https://discord.gg/WRcfFH4sGz)

#### Hawaii
- [Hawaii Meshnet](https://www.hawaiimesh.net/)

#### Illinois
- [Chicagoland Meshtastic](https://chicagolandmesh.org/)
- [Clark County Illinois Meshtastic Network](https://clarkcountyill.localmesh.org/doku.php?id=start)

#### Massachusetts
- [Boston Meshnet (Facebook)](https://www.facebook.com/groups/376287875353461/)

#### Michigan
- [Michigan Meshtastic Network (Discord)](https://discord.gg/3A5RREcBcc)

#### New Mexico
- [Albuquerque Mesh](https://www.abqm.net)

#### North Carolina
- [North Carolina Mesh](https://ncmesh.net)

#### Oklahoma
- [Oklahoma Meshtastic (Facebook)](https://www.facebook.com/groups/942404880478488)

#### Tennessee
- [Meshville](https://meshville.org/) - Nashville

#### Texas
- [Austin Mesh](https://austinmesh.org/)

#### Virginia
- [Northern Virginia Meshtastic](https://groups.io/g/NoVa-Meshtastic)
- [Shenandoah Valley Meshtastic](https://svmeshtastic.org)

#### Washington
- [Tacoma.localmesh](https://tacoma.localmesh.org/doku.php?id=start)
