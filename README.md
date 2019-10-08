[<img src="BANNER.svg" width="100%">](#readme)

[![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

Game networking is a subset of computer networking that commonly covers data replication, state synchronization, snapshot interpolation, client-side prediction, lag compensation, anti cheating, load balancing, bandwidth optimization\
&mdash; and many more techniques involved in multiplayer online game programming.

**Please feel free to contribute your _awesome_ resource after reading [contribution guidelines](CONTRIBUTING.md), thank you!**

## Contents
- [Articles](#articles)
- [Talks](#talks)
- [Tutorials](#tutorials)
- [Libraries](#libraries)
- [Projects](#projects)
- [Tools](#tools)

## Articles

- [Ethernet vs. WiFi](https://na.leagueoflegends.com/en/page/ethernet-vs-wifi-ping-packets-playing-better) - Internet connection over WiFi vs Ethernet metrics comparison by Viscarious from Riot Games.
- [Fast-Paced Multiplayer](http://www.gabrielgambetta.com/client-server-game-architecture.html) - Gabriel Gambetta's client-side prediction, entity interpolation, lag compensation articles.
- [Gaffer on Games](https://web.archive.org/web/https://gafferongames.com/) - Glenn Fiedler's reliable-UDP protocol and game network development articles.
- [Game Server Architecture](https://web.archive.org/web/https://gameserverarchitecture.com/) - Matthew Walker's multiplayer game server architecture blog.
- [High Performance Browser Networking](https://hpbn.co/) - A fantastic free online book about modern web protocols by Ilya Grigorik.
- [How a Shooter Shoots](https://kotaku.com/5869564/networking-how-a-shooter-shoots) - Armin Ronacher's analysis on Battlefield 3's shooting mechanism in multiplayer.
- [Impact Of Latency In Wireless Networks For Real-time Multiplayer Games On Mobile Devices](https://ntnuopen.ntnu.no/ntnu-xmlui/bitstream/handle/11250/2352307/11752_FULLTEXT.pdf) - An academic paper.
- [IT Hare on Network Programming](http://ithare.com/category/network-programming/) - Detailed network programming articles from IT Hare team.
- [NAT Punch-through for Multiplayer Games](https://keithjohnston.wordpress.com/2014/02/17/nat-punch-through-for-multiplayer-games/) - Brief summary of NAT and P2P connectivity by Keith Johnston.
- [Netcode Explained](https://www.pcgamer.com/uk/netcode-explained/) - Basic game networking concepts with examples by Chris "Battle(non)sense" on PC Gamer.
- [Networked Physics in Virtual Reality](https://developer.oculus.com/blog/networked-physics-in-virtual-reality-networking-a-stack-of-cubes-with-unity-and-physx/) - Networking a stack of cubes with Unity and PhysX by Glenn Fiedler at Oculus.
- [Network Protocols](https://www.destroyallsoftware.com/compendium/network-protocols?share_key=97d3ba4c24d21147) - A brief yet detailed overview of low-level network protocols stack from Destroy All Software.
- [Photon Unity Networking](https://doc.photonengine.com/en-us/pun/current/getting-started/pun-intro) - Official PUN multiplayer online game networking framework documentation wiki.
- [Quake 3 Network Model](http://fabiensanglard.net/quake3/network.php) - Fabien Sanglard's source code review about Quake 3's networking model.
- [Real Time Multiplayer in HTML5](http://buildnewgames.com/real-time-multiplayer/) - Sven Bergström's multiplayer game development guide using web technologies.
- [Replication in Networked Games](https://0fps.net/2014/02/10/replication-in-networked-games-overview-part-1/) - Mikola Lysenko's replication articles for JavaScript-based multiplayer games.
- [Source Multiplayer Networking](https://developer.valvesoftware.com/wiki/Source_Multiplayer_Networking) - Valve's Source engine wiki that includes advanced game networking topics.
- [Tech-Stack of the Ultima Online Servers](https://www.quora.com/What-was-the-technology-stack-driving-the-original-Ultima-Online-servers) - A brief summary about UO tech-stack by Raph Koster and Brian Crowder.
- [The Case of the Quake Cheats](http://www.catb.org/esr/writings/quake-cheats.html) - Security lessons learned about client-server model from Quake 1 by id Software.
- [The DOOM III Network Architecture](http://mrelusive.com/publications/papers/The-DOOM-III-Network-Architecture.pdf) - Improvements upon previous network architectures used in Quake III Arena.
- [The Poor Man's Netcode](http://etodd.io/2018/02/20/poor-mans-netcode/) - Project code and detailed blog post about networking challenges by Evan Todd.
- [The TRIBES Engine Networking Model](https://www.gamedevs.org/uploads/tribes-networking-model.pdf) - Tribes II's networking model paper by Mark Frohnmayer and Tim Gift.
- [Tick Based Lag Compensation in Unity](https://twotenpvp.github.io/lag-compensation-in-unity.html) - Case scenario on shooting with better accuracy by Albin Corén.
- [Unity Physics and Client-Side Prediction](http://www.codersblock.org/blog/client-side-prediction-in-unity-2018) - Demo project and detailed how-to blog post by Joe Best-Rotheray.
- [Unity UNET HLAPI and Steam P2P Networking](https://blog.spacewavesoftware.com/gamedev/2017-10-28-unity-unet-hlapi-and-steam-p2p-networking/) - Example project and detailed blog post by Justin Rempel.
- [Unreal Engine 1 Netcode](https://docs.google.com/document/d/1KGLbEfHsWANTTgUqfK6rkpFYDGvnZYj-BN18sxq6LPY) - Historical paper on netcode in UE1 (Unreal, Unreal Tournament), by Tim Sweeney.
- [Unreal Engine 3 Networking & Replication](https://api.unrealengine.com/udk/Three/ReplicationHome.html) - Historical but still valuable UE3 game networking documentation wiki.
- [Unreal Engine 4 Framework & Network](http://www.nafonso.com/home/unreal-framework-network) - Brief look into Unreal's gameplay networking framework by Nuno Afonso.
- [Unreal Engine 4 Network Compendium](http://cedric-neukirchen.net/Downloads/Compendium/UE4_Network_Compendium_by_Cedric_eXi_Neukirchen.pdf) - Detailed summary of UE4 networking with examples by Cedric Neukirchen.
- [Unreal Engine 4 Networking and Multiplayer](https://docs.unrealengine.com/en-us/Gameplay/Networking) - Official UE4 gameplay networking framework documentation wiki.
- RU [Как мы писали сетевой код мобильного PvP шутера](https://habr.com/ru/company/pixonic/blog/415959/) - Pixonic о клиенте в быстром шутере.

## Talks

- Game Developers Conference
  - [2000 / Half-Life and Team Fortress Networking](https://www.gdcvault.com/play/1016642/Half-Life-and-Team-Fortress) - Game networking in details by Yahn Bernier from Valve.
  - [2010 / Building the Server Software for ELIMINATE](http://www.gdcvault.com/play/1012368/Building-the-Server-Software-for) - Talk by Stephen Detwiler and James Marr from ngmoco:).
  - [2011 / Crysis 2 Multiplayer](http://www.gdcvault.com/play/1014886/Crysis-2-Multiplayer-A-Programmer) - A Programmer's Postmortem by Peter Hall from Crytek.
  - [2011 / I Shot You First](http://www.gdcvault.com/play/1014345/I-Shot-You-First-Networking) - Gameplay networking in Halo: Reach by David Aldridge from Bungie.
  - [2012 / Writing Server and Network Code for Your Online Game](http://www.gdcvault.com/play/1015609/Writing-Server-and-Network-Code) - Talk by Patrick Wyatt from En Masse Ent.
  - [2013 / Network Serialization and Routing in World of Warcraft](http://www.gdcvault.com/play/1017733/Network-Serialization-and-Routing-in) - Talk by Joe Rumsey from Blizzard.
  - [2015 / Game Networking for Physics Programmers](http://www.gdcvault.com/play/1022195/Physics-for-Game-Programmers-Networking) - Talk by Glenn Fiedler from Respawn Entertainment.
  - [2015 / Networking Gameplay and AI in Assassin's Creed Unity](http://www.gdcvault.com/play/1022168/Networking-Gameplay-and-AI-in) - Talk by Charles Lefebvre from Ubisoft.
  - [2015 / Stop, Copy/Paste Networking & Innovate](https://www.gdcvault.com/play/1022787/Stop-Copy-Paste-Networking) - High level design approaches by Claire Blackshaw from Sony.
  - [2016 / Fighting Latency on Call of Duty Black Ops III](https://www.gdcvault.com/play/1023220/Fighting-Latency-on-Call-of) - Detailed techniques by Benjamin Goyette from Activision.
  - [2017 / Overwatch Gameplay Architecture and Netcode](https://www.gdcvault.com/play/1024001/-Overwatch-Gameplay-Architecture-and) - Simulation, determinism, responsiveness and precision.
  - [2018 / 8 Frames in 16ms](https://www.youtube.com/watch?v=7jb0FOcImdg) - Rollback Networking in Mortal Kombat and Injustice 2 by Michael Stallone.
  - [2018 / It IS Rocket Science!](https://www.gdcvault.com/play/1024972/It-IS-Rocket-Science-The) - The physics and networking of Rocket League in details by Jared Cone.
  - [2019 / Quantum Deep Dive](https://vimeo.com/335798361/2f90c04a30) - Photon Quantum Deterministic Network Engine for Unity by Eric from Exit Games.
- Unreal Engine Livestream
  - [Replication Graph](https://www.youtube.com/watch?v=CDnNAAzgltw) - Epic's dev-team demonstrates UE 4.20's new Replication Graph feature.
  - [Server Optimizations](https://www.youtube.com/watch?v=mT8VUVuk-CY) - Ryan Gerleve and Dave Ratti to discuss server optimization techniques in UE4.
- Unreal Fest
  - [EU 2019 / Replication Graph For Optimizing RTS Games](https://www.youtube.com/watch?v=VusAHXoHF3Y) - Talk by Nick Prühs from Deadalic Entertainment.
- Unity Unite
  - [EU 2016 / Building a PvP focused MMO](https://www.youtube.com/watch?v=x_4Y2-B-THo) - Albion MMO architecture by David Salz from Sandbox Interactive.
  - [EU 2017 / Photon vs UNet](https://www.youtube.com/watch?v=Y1my5bKhKJY) - Multiplayer architecture comparison by Christof Wegmann from Exit Games.
  - [LA 2018 / Deep-Dive Into Networking for Unity's FPS Sample](https://www.youtube.com/watch?v=k6JTaFE7SYI) - Netcode talk by Peter Andreasen from Unity.
- Other
  - [HandmadeCon 2015 / Pat Wyatt](https://www.youtube.com/watch?v=1faaOrtHJ-A) - Chat about networking of Guild Wars, Diablo, StarCraft by Pat Wyatt.
  - [Overwatch / Let's Talk Netcode](https://www.youtube.com/watch?v=vTH2ZPgYujQ) - Tim Ford and Philip Orwig from Blizzard on Overwatch's netcode.

## Tutorials

- Unreal Engine
  - [Authoritative Networked Character Movement](https://wiki.unrealengine.com/Authoritative_Networked_Character_Movement) - Introduction to implementing networked movement features.
  - [Blueprint Multiplayer](https://www.youtube.com/playlist?list=PLZlv_N0_O1gYqSlbGQVKsRg6fpxWndZqZ) - Blueprint multiplayer game development tutorial series by Wes Bunn from Epic Games.
  - [Create Multiplayer Games](https://www.udemy.com/unrealengine-cpp/) - (Paid) C++ multiplayer game development tutorial series by Tom Looman.
  - [Online Game Development](https://www.udemy.com/unrealmultiplayer/) - (Paid) C++ online game development tutorial series by Sam Pattuzzi.
  - [Steam Multiplayer](https://www.youtube.com/watch?v=TPakLkxc6f0) - Steam-backed blueprint multiplayer tutorial by Maik Hilfer.
- Unity
  - [Bouncy Ball Networking](https://materiagame.com/complete-darkrift2-tutorials-for-unity3d-network-games) - Making of a simple networked bouncy ball using DarkRift2 from MateriaGame.
  - [Making a Multiplayer FPS](https://www.youtube.com/playlist?list=PLPV2KyIb3jR5PhGqsO7G4PsbEC_Al-kPZ) - UNET-based multiplayer FPS game development tutorials by Asbjørn Thirslund.
  - [Multiplayer Networking](https://unity3d.com/learn/tutorials/s/multiplayer-networking) - Official UNET-based multiplayer game networking tutorials by Unity.

## Libraries

- C / C++
  - [ENet](http://enet.bespin.org/) - Simple and robust reliable UDP networking library.
  - [GameNetworkingSockets](https://github.com/ValveSoftware/GameNetworkingSockets) - Valve's internal (Steam) network transport layer for games.
  - [RakNet](https://github.com/facebookarchive/RakNet) - Full-featured and mature reliable UDP networking engine.
  - [yojimbo](https://github.com/networkprotocol/yojimbo) - Reliable UDP networking library for client/server games with dedicated servers.
- C#
  - [Barebones Master Server](https://github.com/alvyxaz/barebones-masterserver) - Backend framework with auth, profile, lobby, chat features for Unity.
  - [DarkRift Networking](https://www.darkriftnetworking.com/) - Unity focused multi-threaded multiplayer networking solution.
  - [Forge Networking](https://github.com/BeardedManStudios/ForgeNetworkingRemastered) - Unity focused real-time multiplayer networking solution.
  - [Lidgren.Network](https://github.com/lidgren/lidgren-network-gen3) - Reliable UDP networking library (.NET).
  - [LiteNetLib](https://github.com/RevenantX/LiteNetLib) - Lite reliable UDP networking library (.NET/Mono).
  - [MLAPI](https://mlapi.network) - Mix and match networking library with lots of built-in features for Unity.
  - [Photon Engine](https://photonengine.com) - Hybrid multiplayer game networking platform (SaaS, Cloud).
  - [SocketWeaver](https://socketweaver.com) - Multiplayer cloud services designed for the Unity engine (SaaS).
- Java
  - [SmartFoxServer](http://smartfoxserver.com/) - Massive multiplayer game server with advanced built-in features.

## Projects

- Unreal Engine
  - [CharacterMovementReplication](https://github.com/error454/CharacterMovementReplication-UE4) - Project that adds sprint ability to the CharacterMovementComponent.
  - [CoopHordeShooter](https://github.com/tomlooman/CoopHordeShooter) - 3rd-person co-op multiplayer horde shooter game tutorial project.
  - [EpicSurvivalGame](https://github.com/tomlooman/EpicSurvivalGameSeries) - 3rd-person multiplayer zombie survival game tutorial project.
- Unity
  - [AuthoritativeMovementExample](https://github.com/Relic/AuthoritativeMovementExample) - Server authoritative movement project using Forge Networking for Unity.
  - [Angry Bots Multiplayer](https://assetstore.unity.com/packages/templates/photon-angry-bots-multiplayer-showcase-1917) - Photon PUN-based multiplayer top-down shooter project.
  - [ArenaGame](https://github.com/NFMynster/ArenaGame) - Forge Networking-based multiplayer FPS game as an example project.
  - [Entitas Sync Framework](https://github.com/RomanZhu/Entitas-Sync-Framework) - Network framework for Entitas ECS targeting turn-based or slow-paced games.
  - [FPSSample](https://github.com/Unity-Technologies/FPSSample) - An official Multiplayer FPS project sample from Unity using new networking package and ECS.
  - [Gambetta Networked Demo](https://github.com/RamiAhmed/Gambetta_NetworkedDemo) - Gabriel Gambetta's network architecture implementation in Unity using Lidgren.
  - [MultiplayerFPS](https://github.com/Brackeys/MultiplayerFPS-Tutorial) - UNET-based simple multiplayer 1st-person shooter tutorial project.
  - [SmartFoxServer2X Multiplayer](https://assetstore.unity.com/packages/tools/network/smartfoxserver2x-multiplayer-sdk-17261) - SFS2X-based multiplayer project examples.
  - [TANKS! Networking](https://assetstore.unity.com/packages/essentials/tutorial-projects/tanks-networking-demo-46213) - UNET-based multiplayer tank shooter project.
  - [UNet-Controller](https://github.com/Heep042/UNet-Controller) - UNET-based networked 1st-person and 3rd-person player controller with advanced features.

## Tools

- [CapAnalysis](https://www.capanalysis.net/ca/) - Web visual tool to analyze captured network traffic. (Ubuntu, Debian)
- [clumsy](https://jagt.github.io/clumsy/) - Network condition simulation utility. (Windows)
- [Fiddler](https://www.telerik.com/fiddler) - Web debugging proxy server. (Windows, macOS, Linux)
- [netem](https://wiki.linuxfoundation.org/networking/netem) - Network emulation for testing protocols. (Linux)
- [Network Link Conditioner](https://nshipster.com/network-link-conditioner/) - Network environment simulation utility. (macOS, iOS)
- [Network Protocol Analyzer](https://www.softperfect.com/products/networksniffer/) - Tool for analysing, debugging, maintaining and monitoring connections. (Windows)
- [Network Simulator (ns)](https://www.nsnam.org) - Network simulator targeting research and educational use. (macOS, Linux)
- [Postman](https://www.getpostman.com/) - Web API debugging client. (Windows, macOS, Linux)
- [Wireshark](https://www.wireshark.org/) - Network traffic analyzer tool. (Windows, macOS, Linux)

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [M. Fatih MAR](https://github.com/mfatihmar) has waived all copyright and related or neighboring rights to this work.
