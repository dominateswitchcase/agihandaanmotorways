DALOY

A real-time public transportation management game — Para sa Street

Built in Unity for [Jam Name Here] · 2D with a possible 3D background


About

Daloy (Filipino: "flow") puts you in charge of a city's public transportation network — tricycles, jeepneys, and waiting sheds — as you try to keep commuters moving despite floods, rush hours, road closures, and everything else Filipino urban life throws at a daily commute.

The city, roads, and neighborhoods already exist. Your job is to build and manage the network that connects them, so students, workers, patients, and shoppers can actually get where they're going.


A city's most valuable resource isn't its vehicles — it's its people's time.




Gameplay Loop

Commuter spawns
  → walks or rides a tricycle to a waiting shed
  → boards a jeepney
  → transfers once (optional)
  → rides a jeepney
  → walks or rides a tricycle to their destination
  → arrives, or gives up and becomes stranded

You never control commuters directly — you shape the network they travel through.


Core Features


🚶 Walking — commuters' default option, with a walking radius affected by weather/city conditions
🛺 Tricycles — last-mile transport, and the critical fallback during floods, rain, or road closures
🚐 Jeepneys — the network backbone; draw routes, connect waiting sheds, assign vehicles
🚏 Waiting Sheds — pickup/drop-off points with visible queues
🔄 Transfers — commuters can switch jeepney routes once per trip via transfer hubs
🌦 Dynamic Events — Heatwave, Heavy Rain, Flood, Road Construction, Festival, School Dismissal, Rush Hour
⚠️ Congestion Spread — unresolved problems worsen and spread to neighboring roads/sheds over time
📊 End-of-Day Report — daily summary of commuters served, delayed, and stranded



How to Play


Place waiting sheds near neighborhoods and destinations.
Draw jeepney routes connecting sheds, and assign jeepneys to run them.
Deploy tricycles to cover last-mile gaps.
Respond to events as they hit — reroute or reinforce before a problem spreads.
Watch your queues — overcrowded sheds are an early warning sign.
Review your End-of-Day Report and adjust for the next day.
Keep as many commuters reaching their destinations as possible, for as many days as possible.



Tech Stack


Engine: Unity (2D)
Language: C#
Platform: PC



Team

NameRoleDomDocumentation, Game MechanicsJMGame Developer, Artist SupportJuliusGame DeveloperKairaArtist — Icons, Assets, EnvironmentDaphneArtist — Assets, EnvironmentJordanSenior DeveloperBenedictArtist — Assets, EnvironmentJensAudio/Video — Trailer, Sound FX


Status

🚧 In development for the game jam — see the Master Tracker for current progress and milestones.


MVP Scope


 Road/grid layer with walking, tricycle, and jeepney movement
 Waiting shed placement + jeepney route drawing
 One commuter type, one destination type
 2–3 event types (Rain, Flood, Rush Hour)
 Congestion Spread on at least one event type
 Queue overcrowding → stranded commuter → performance decline loop
 Basic End-of-Day Report


Stretch Goals


 Multiple commuter types with distinct behavior
 Transfer hub system (multi-leg trips)
 Full event roster
 Congestion Spread across all event types
 Visual severity indicators
 Performance-based difficulty/expansion
