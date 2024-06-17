[![Game Networking Resources](BANNER.png)](#readme)

**Game Networking** (aka _multiplayer networking_ or _netcode_) is the synchronization of game state and events between multiple players connected over the network. It focuses on the inherent challenges of multiplayer online games such as latency, jitter and packet loss, mitigating through sophisticated algorithms and techniques, including prediction, compensation, reconciliation, interpolation and other mechanisms. It is also often deeply involved and integrated with other game systems such as physics, animation and gameplay.

## Articles

- [1500 Archers on a 28.8: Network Programming in Age of Empires and Beyond](https://www.gamedeveloper.com/programming/1500-archers-on-a-28-8-network-programming-in-age-of-empires-and-beyond) - Mark Terrano, Paul Bettner.
- [Choosing TCP or UDP: a guide for game developers](https://web.archive.org/web/20210415231950/https://heroiclabs.com/docs/expert-tcp-udp/) - Basic TCP vs UDP comparison by Heroic Labs.
- [Close Look: Halo Infinite's Online Experience](https://www.halowaypoint.com/news/closer-look-halo-infinite-online-experience) - Discussing netcode issues and mitigations by Richard Watson.
- [Don't use Lockstep in RTS games](https://blog.istrolid.com/blog/dont-use-lockstep-in-rts-games.html) - Comparing Lockstep vs Client-Server Networking Models for RTS.
- [Ethernet vs. WiFi](https://web.archive.org/web/20191231135556/https://na.leagueoflegends.com/en/page/ethernet-vs-wifi-ping-packets-playing-better) - Connection over WiFi vs Ethernet metrics comparison by Viscarious from Riot Games.
- [Explaining Delay-based and Rollback Netcode](https://arstechnica.com/gaming/2019/10/explaining-how-fighting-games-use-delay-based-and-rollback-netcode/) - Rollback netcode for fighting games by Ricky Pusch.
- [Fast-Paced Multiplayer](http://www.gabrielgambetta.com/client-server-game-architecture.html) - Prediction, reconciliation, interpolation and compensation by Gabriel Gambetta.
- [Fightin' Words, Netcode](http://ki.infil.net/w02-netcode.html) - Articles explaining how fighting games use delay-based and rollback netcode.
- [Fight The Lag! The Trick Behind GGPO's Low Latency Netcode](https://drive.google.com/file/d/1cV0fY8e_SC1hIFF5E1rT8XRVRzPjU8W9/view) - An explanation of GGPO by Tony Cannon.
- [Gaffer on Games](https://gafferongames.com/) - Glenn Fiedler's reliable-UDP protocol and game network development articles.
- [Game Networking Demystified](https://ruoyusun.com/2019/03/28/game-networking-1.html) - Basic game networking terminology and concepts by Ruoyu Sun.
- [Game Server Architecture](https://web.archive.org/web/20210419133753/https://gameserverarchitecture.com/) - Matthew Walker's multiplayer game server architecture blog.
- [High Performance Browser Networking](https://hpbn.co/) - A free online book about modern web protocols by Ilya Grigorik.
- [How a Shooter Shoots](https://kotaku.com/5869564/networking-how-a-shooter-shoots) - Armin Ronacher's analysis on Battlefield 3's shooting mechanism in multiplayer.
- [Impact Of Latency In Wireless Networks For Real-time Multiplayer Games On Mobile Devices](https://ntnuopen.ntnu.no/ntnu-xmlui/bitstream/handle/11250/2352307/11752_FULLTEXT.pdf) - A paper.
- [IT Hare on Network Programming](http://ithare.com/category/network-programming/) - Detailed network programming articles from IT Hare team.
- [Lag Compensation - Fair Play for all Pings](https://vercidium.com/blog/lag-compensation/) - An article explaining lag compensation by Mitchell Robinson.
- [NAT Punch-through for Multiplayer Games](https://keithjohnston.wordpress.com/2014/02/17/nat-punch-through-for-multiplayer-games/) - NAT and P2P connectivity by Keith Johnston.
- [Netcode at Super Bit Machine: Multiplayer First](https://medium.com/@geretti/netcode-at-super-bit-machine-multiplayer-first-7940aa0a9fa4) - Article series on ARMAJET's netcode stack by Nicola Geretti.
- [Netcode Explained](https://www.pcgamer.com/uk/netcode-explained/) - Game networking concepts with examples by Chris "Battle(non)sense" on PC Gamer.
- [Networked Physics in Virtual Reality](https://developer.oculus.com/blog/networked-physics-in-virtual-reality-networking-a-stack-of-cubes-with-unity-and-physx/) - Networking a stack of cubes with Unity and PhysX by Glenn Fiedler.
- [Networking of a turn-based game](https://longwelwind.net/blog/networking-turn-based-game/) - Deterministic state synchronization netcode by Frédéric Kaczynski.
- [Network Protocols](https://www.destroyallsoftware.com/compendium/network-protocols?share_key=97d3ba4c24d21147) - A brief overview of low-level network protocols stack from Destroy All Software.
- [Más Bandwidth](https://mas-bandwidth.com) - Glenn Fiedler's new blog at the intersection of game network programming and scalable backend engineering.
- [Peeking into Valorant's Netcode](https://technology.riotgames.com/news/peeking-valorants-netcode) - Netcode overview and peeker's advantage by Matt deWet and David Straily.
- [Quake 3 Network Model](http://fabiensanglard.net/quake3/network.php) - Fabien Sanglard's source code review about Quake 3's networking model.
- [Real Time Multiplayer in HTML5](http://buildnewgames.com/real-time-multiplayer/) - Sven Bergström's multiplayer game development on the web guide.
- [Replication in Networked Games](https://0fps.net/2014/02/10/replication-in-networked-games-overview-part-1/) - Mikola Lysenko's replication articles for JavaScript-based multiplayer.
- [Rollback Networking in INVERSUS](http://blog.hypersect.com/rollback-networking-in-inversus/) - Ryan Juckett's post on a peer-to-peer rollback system in multiplayer.
- [Source Multiplayer Networking](https://developer.valvesoftware.com/wiki/Source_Multiplayer_Networking) - Valve's Source engine wiki including advanced game networking topics.
- [Sync Host Overview](https://www.gamedevs.org/uploads/introduction-to-sync-host.pdf) - A slide deck covering Sync Host architecture by Peter Kao from Insomniac Games.
- [Tech-Stack of the Ultima Online Servers](https://www.quora.com/What-was-the-technology-stack-driving-the-original-Ultima-Online-servers) - A summary of UO tech-stack by Raph Koster and Brian Crowder.
- [The Case of the Quake Cheats](http://www.catb.org/esr/writings/quake-cheats.html) - Security lessons from client-server model from Quake 1 by id Software.
- [The DOOM III Network Architecture](http://mrelusive.com/publications/papers/The-DOOM-III-Network-Architecture.pdf) - Improvements on network architectures used in Quake III Arena.
- [The Poor Man's Netcode](http://etodd.io/2018/02/20/poor-mans-netcode/) - Project code and detailed blog post about networking challenges by Evan Todd.
- [The TRIBES Engine Networking Model](https://www.gamedevs.org/uploads/tribes-networking-model.pdf) - Tribes I & II's networking model by Mark Frohnmayer and Tim Gift.
- [Tick Based Lag Compensation in Unity](https://twotenpvp.github.io/lag-compensation-in-unity.html) - Case scenario on shooting with better accuracy by Albin Corén.
- [Unity Physics and Client-Side Prediction](http://www.codersblock.org/blog/client-side-prediction-in-unity-2018) - Demo project and how-to blog post by Joe Best-Rotheray.
- [Unity UNET HLAPI and Steam P2P Networking](https://blog.spacewavesoftware.com/gamedev/2017-10-28-unity-unet-hlapi-and-steam-p2p-networking/) - Example project and detailed blog post by Justin Rempel.
- [Unreal Engine 1 Netcode](https://docs.google.com/document/d/1KGLbEfHsWANTTgUqfK6rkpFYDGvnZYj-BN18sxq6LPY) - Historical paper on netcode in UE1 (and Unreal Tournament) by Tim Sweeney.
- [Unreal Engine 3 Networking & Replication](https://api.unrealengine.com/udk/Three/ReplicationHome.html) - Historical UE3 game networking from the old wiki.
- [Unreal Engine 4 Framework & Network](http://www.nafonso.com/home/unreal-framework-network) - A look into Unreal game networking framework by Nuno Afonso.
- [Unreal Engine 4 Network Compendium](http://cedric-neukirchen.net/Downloads/Compendium/UE4_Network_Compendium_by_Cedric_eXi_Neukirchen.pdf) - A summary of Unreal game networking by Cedric Neukirchen.
- [Unreal Engine 4 Networking and Multiplayer](https://docs.unrealengine.com/en-us/Gameplay/Networking) - Official UE4 game networking framework docs from the wiki.
- [Valorant's 128-Tick Servers](https://technology.riotgames.com/news/valorants-128-tick-servers) - Server runtime optimization techniques in-depth by Brent Randall.
- RU [Как мы писали сетевой код мобильного PvP шутера](https://habr.com/ru/company/pixonic/blog/415959/) - Pixonic о клиенте в быстром шутере.

## Talks

- Game Developers Conference
  - [2000 / Half-Life and Team Fortress Networking](https://www.gdcvault.com/play/1016642/Half-Life-and-Team-Fortress) - Talk on backend network services by Yahn Bernier.
  - [2010 / Building the Server Software for ELIMINATE](http://www.gdcvault.com/play/1012368/Building-the-Server-Software-for) - By Stephen Detwiler and James Marr.
  - [2011 / Crysis 2 Multiplayer](http://www.gdcvault.com/play/1014886/Crysis-2-Multiplayer-A-Programmer) - A Programmer's Postmortem by Peter Hall from Crytek.
  - [2011 / I Shot You First](http://www.gdcvault.com/play/1014345/I-Shot-You-First-Networking) - Gameplay networking in Halo: Reach by David Aldridge from Bungie.
  - [2012 / Writing Server and Network Code for Your Online Game](http://www.gdcvault.com/play/1015609/Writing-Server-and-Network-Code) - Talk by Patrick Wyatt from En Masse.
  - [2013 / Network Serialization and Routing in World of Warcraft](http://www.gdcvault.com/play/1017733/Network-Serialization-and-Routing-in) - Talk by Joe Rumsey from Blizzard.
  - [2015 / Game Networking for Physics Programmers](http://www.gdcvault.com/play/1022195/Physics-for-Game-Programmers-Networking) - Talk by Glenn Fiedler from Respawn.
  - [2015 / Networking Gameplay and AI in Assassin's Creed Unity](http://www.gdcvault.com/play/1022168/Networking-Gameplay-and-AI-in) - Talk by Charles Lefebvre from Ubisoft.
  - [2015 / Shared World Shooter: Destiny's Networked Mission Architecture](https://www.gdcvault.com/play/1022246/Shared-World-Shooter-Destiny-s) - By Justin Truman.
  - [2015 / Stop, Copy/Paste Networking & Innovate](https://www.gdcvault.com/play/1022787/Stop-Copy-Paste-Networking) - Design approaches by Claire Blackshaw from Sony.
  - [2016 / Fighting Latency on Call of Duty Black Ops III](https://www.gdcvault.com/play/1023220/Fighting-Latency-on-Call-of) - Talk by Benjamin Goyette from Activision.
  - [2017 / Overwatch Gameplay Architecture and Netcode](https://www.youtube.com/watch?v=zrIY0eIyqmI) - Timothy Ford on precise simulation with ECS.
  - [2017 / Replay Technology in Overwatch: Kill Cam, Gameplay, and Highlights](https://www.youtube.com/watch?v=W4oZq4tn57w) - Talk by Philip Orwig.
  - [2017 / Networking Scripted Weapons and Abilities in Overwatch](https://www.youtube.com/watch?v=ScyZjcjTlA4) - Talk by Dan Reed from Blizzard.
  - [2017 / Replicating Chaos: Vehicle Replication in Watch Dogs 2](https://www.youtube.com/watch?v=_8A2gzRrWLk) - Replicating vehicle movement in P2P.
  - [2018 / 8 Frames in 16ms](https://www.youtube.com/watch?v=7jb0FOcImdg) - Rollback Networking in Mortal Kombat and Injustice 2 by Michael Stallone.
  - [2018 / For Honor: From a Great Launch to Live Period](https://www.gdcvault.com/play/1024949/-For-Honor-From-a) - By Damien Kieken and Roman Campos Oriola.
  - [2018 / It IS Rocket Science!](https://www.gdcvault.com/play/1024972/It-IS-Rocket-Science-The) - The physics and networking of Rocket League in details by Jared Cone.
  - [2019 / Quantum Deep Dive](https://vimeo.com/335798361/2f90c04a30) - Photon Quantum Network Engine for Unity by Eric from Exit Games.
- Unreal Engine Livestream
  - [Replication Graph](https://www.youtube.com/watch?v=CDnNAAzgltw) - Epic's dev-team demonstrates UE 4.20's new Replication Graph feature.
  - [Server Optimizations](https://www.youtube.com/watch?v=mT8VUVuk-CY) - Ryan Gerleve and Dave Ratti to discuss server optimization techniques in UE4.
- Unreal Fest
  - [EU 2019 / Replication Graph For Optimizing RTS Games](https://www.youtube.com/watch?v=VusAHXoHF3Y) - Talk by Nick Prühs from Deadalic.
- Unity Unite
  - [EU 2016 / Building a PvP focused MMO](https://www.youtube.com/watch?v=x_4Y2-B-THo) - Albion MMO architecture by David Salz from Sandbox.
  - [EU 2017 / Photon vs UNet](https://www.youtube.com/watch?v=Y1my5bKhKJY) - Netcode architecture comparison by Christof Wegmann from Exit Games.
  - [LA 2018 / Deep-Dive Into Networking for Unity's FPS Sample](https://www.youtube.com/watch?v=k6JTaFE7SYI) - Talk by Peter Andreasen from Unity.
  - [EU 2019 / Intro to DOTS and Netcode](https://www.youtube.com/watch?v=P_-FoJuaYOI) - Networked future of Unity using DOTS by Tim Johansson.
- Other
  - [Between Two Servers](https://www.youtube.com/playlist?list=PLzVi6Kh_HMIWKS1aXOV4XobuymoF0P-_S) - Glenn Fiedler interviews gamedevs about multiplayer and netcode.
  - [HandmadeCon 2015 / Pat Wyatt](https://www.youtube.com/watch?v=1faaOrtHJ-A) - Chat about Guild Wars, Diablo, StarCraft netcode by Pat Wyatt.
  - [Overwatch / Let's Talk Netcode](https://www.youtube.com/watch?v=vTH2ZPgYujQ) - Overwatch netcode by Tim Ford and Philip Orwig from Blizzard.
  - [Valorant / Netcode & 128-Servers](https://www.youtube.com/watch?v=_Cu97mr7zcM) - Some basic networking concepts in Valorant from Riot Games.
  - [Warframe / Networking Architecture](https://www.youtube.com/watch?v=VVetqMgcN50) - Warframe netcode by Maciej Sinilo from Digital Extremes.

## Libraries

- C / C++
  - [ENet](http://enet.bespin.org/) - Simple and robust reliable UDP networking library.
  - [GameNetworkingSockets](https://github.com/ValveSoftware/GameNetworkingSockets) - Valve's internal (Steam) network transport layer for games.
  - [GGPO](https://github.com/pond3r/ggpo) - Good Game, Peace Out Rollback Network SDK.
  - [KCP](https://github.com/skywind3000/kcp) - A fast and reliable ARQ protocol.
  - [netcode](https://github.com/mas-bandwidth/netcode) - Secure connection-based client/server protocol built on top of UDP (C, C#, Rust, Go etc...)
  - [RakNet](https://github.com/facebookarchive/RakNet) - (Inactive) Full-featured and mature reliable UDP networking engine.
  - [Reliable](https://github.com/mas-bandwidth/reliable) - A packet acknowledgement system for UDP (C).
  - [Serialize](https://github.com/mas-bandwidth/serialize) - A simple bitpacking serializer for C++.
  - [Snapnet](https://www.snapnet.dev) - AAA netcode for real-time multiplayer games.
  - [TNL2](https://github.com/nardo/tnl2) - (Inactive) Torque Networking Library 2 which is quite similar to [TRIBES Networking Model](https://www.gamedevs.org/uploads/tribes-networking-model.pdf).
  - [yojimbo](https://github.com/mas-bandwidth/yojimbo) - Reliable UDP networking library for client/server games with dedicated servers (C++).
- C#
  - [Barebones Master Server](https://github.com/alvyxaz/barebones-masterserver) - Backend framework with auth, profile, lobby, chat features for Unity.
  - [DarkRift 2](https://github.com/DarkRiftNetworking/DarkRift) - Unity focused high-performance multi-threaded multiplayer networking solution.
  - [FishNet](https://github.com/FirstGearGames/FishNet) - Unity networking solution aimed towards reliability, ease of use, efficiency, and flexibility.
  - [Forge Networking](https://github.com/BeardedManStudios/ForgeNetworkingRemastered) - Unity focused real-time multiplayer networking solution.
  - [Lidgren.Network](https://github.com/lidgren/lidgren-network-gen3) - Reliable UDP networking library (.NET/Mono/Unity).
  - [LiteNetLib](https://github.com/RevenantX/LiteNetLib) - Lite reliable UDP networking library (.NET/Mono/Unity).
  - [MagicOnion](https://github.com/Cysharp/MagicOnion) - Unified Realtime/API framework for .NET platform and Unity.
  - [Mirror](https://github.com/vis2k/Mirror) - A community replacement for Unity's abandoned UNET Networking System.
  - [Netcode for Entities](https://docs.unity3d.com/Packages/com.unity.netcode@latest) - Unity's official netcode SDK for Entities workflows.
  - [Netcode for GameObjects](https://github.com/Unity-Technologies/com.unity.netcode.gameobjects) - Unity's official netcode SDK for GameObject workflows.
  - [Netick](https://netick.net/) - A server-authoritative networking solution for Unity.
  - [NetStack](https://github.com/nxrighthere/NetStack) - Lightweight toolset for creating concurrent networking systems for multiplayer games.
  - [Networker](https://github.com/MarkioE/Networker) - TCP and UDP networking library (.NET/Unity).
  - [Normcore](https://normcore.io/) - Seamless multiplayer game networking for Unity (Cloud/SaaS).
  - [Photon Engine](https://photonengine.com) - Hybrid multiplayer game networking platform (Cloud/SaaS).
  - [RiptideNetworking](https://github.com/tom-weiland/RiptideNetworking) - Lightweight C# networking solution for multiplayer games.
  - [SocketWeaver](https://socketweaver.com) - Multiplayer cloud services designed for the Unity engine (Cloud/SaaS).
- Go
  - [Nakama](https://github.com/heroiclabs/nakama) - Open-source backend infrastructure for multiplayer games (also with Unity/C# SDK).
  - [GoWorld](https://github.com/xiaonanln/goworld) - Scalable Distributed Game Server Engine with Hot Swapping (and Unity demo!).
- Java
  - [SmartFoxServer](http://smartfoxserver.com/) - Massive multiplayer game server with advanced built-in features.
- JavaScript
  - [Actionhero](https://actionherojs.com) - A node.js API server framework for TCP sockets, websockets and HTTP clients.
  - [Colyseus](https://github.com/colyseus/colyseus) - Authoritative multiplayer game server backend framework.
  - [Kalm](https://github.com/kalm/kalm.js) - Socket manager/optimizer library with custom congestion control for Node.js and browsers.
  - [SocketCluster](https://github.com/SocketCluster/socketcluster) - Scalable multi-process HTTP & real-time server framework.

## Tools

- [CapAnalysis](https://www.capanalysis.net/ca/) - Web visual tool to analyze captured network traffic. (Ubuntu, Debian)
- [clumsy](https://jagt.github.io/clumsy/) - Network condition simulation utility. (Windows)
- [netem](https://wiki.linuxfoundation.org/networking/netem) - Network emulation for testing protocols. (Linux)
- [matchmaker](https://github.com/mas-bandwidth/matchmaker) - Matchmaking simulator with real worldwide player data (Go).
- [mitmproxy](https://mitmproxy.org/) - Web debugging proxy server. (Windows, macOS, Linux)
- [Network Link Conditioner](https://nshipster.com/network-link-conditioner/) - Network environment simulation utility. (macOS, iOS)
- [Network Protocol Analyzer](https://www.softperfect.com/products/networksniffer/) - Tool for analysing, debugging and monitoring connections. (Windows)
- [Network Simulator (ns)](https://www.nsnam.org) - Network simulator targeting research and educational use. (macOS, Linux)
- [Postman](https://www.postman.com/) - Web API debugging and development client. (Windows, macOS, Linux)
- [websocat](https://github.com/vi/websocat) - CLI client for WebSockets like netcat or curl. (Windows, macOS, Linux)
- [Wireshark](https://www.wireshark.org/) - Network traffic analyzer tool. (Windows, macOS, Linux)

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
