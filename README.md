# Hi, I'm Elkan

I'm a founder and software engineer in Boulder, Colorado. I like building whole products end to end, from camera hardware on a door frame to the cloud API and the app on your phone.

## CrowdCount (2024–2026)

I founded [CrowdCount](https://github.com/Crowd-Count) and led its engineering. We made doorway people counters for small businesses, plus the software that turns those counts into live occupancy and busy-hour insights. At its peak, counters were running at about 25 businesses in Boulder and Breckenridge.

What I built:

- **Counter firmware** for a Raspberry Pi Zero 2W with a global shutter camera: video streaming, Bluetooth setup from a QR code, and a fleet managed over Tailscale ([crowdcount-counter](https://github.com/Crowd-Count/crowdcount-counter))
- **The cloud API** in Flask and SQLite, with signed requests, push alerts, Square POS sync and zero-downtime deploys (private repo)
- **The iOS app** in SwiftUI, live on the App Store as [CrowdCount App](https://apps.apple.com/us/app/crowdcount-app/id6523433094) ([crowdcount-ios](https://github.com/Crowd-Count/crowdcount-ios))
- **The websites** in Next.js: [crowdcount.tech](https://crowdcount.tech) with its live busyness map, the owner-facing Counter Manager, and an internal fleet dashboard
- **The GPU counting server**, built with Josh D'Annunzio, running YOLO models we trained ourselves ([crowdcount-counter-server](https://github.com/Crowd-Count/crowdcount-counter-server))

When we wound the company down, I moved the API to a read-only AWS Lambda snapshot so the site and apps still work today.

<!-- ## Now
- Cleared: https://clearedtoopen.com
- Upstream: add a link
-->

## Find me

[LinkedIn](https://www.linkedin.com/in/elkanbruha) · [elkanbruha.com](https://elkanbruha.com)
