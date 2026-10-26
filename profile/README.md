# Sigilint

**Industrial sensing, at the speed of signal.** Sigilint is building a low-latency, high-reliability mesh that moves alerts from sensors, cameras, drones and people into the control room. It targets pipelines, refineries, ports, desalination plants and perimeters, and our first vertical is oil & gas. We are based in Fort Worth, Texas, and work in the US and the GCC.

🌐 [sigilint.com](https://sigilint.com) · 🛠 [Hacks](https://sigilint.com/hacks) · 🏁 [Hackathons](https://sigilint.com/hackathons)

## HackFW

We build in the open at [HackFW](https://hack.fwtx.city/), Fort Worth's hackathon.

- **Spring 2026: Well Monitor.** A field of wells on a topographic map, each reporting methane, H₂S and VOCs, with alert states when a well starts to leak. We presented it on May 2, 2026. [Live demo](https://wellmonitor.sigilint.com) · [Devpost](https://devpost.com/software/sigilint-well-monitor)
- **October 2026 ("Hacktober"), the MADE Challenge.** Our build is a fenceline air watch for the oil well next door. Solar-powered ESP32 nodes around a well pad wake, sample methane, H₂S and VOCs, and send their readings over ESP-NOW to a Raspberry Pi gateway, which puts them on a live site map. The toolkit's [well-pad example](https://toolkit.sigilint.com/well-pad/) shows the site. Demo Day is October 30.

All demos run on simulated or public data. None of them is a live customer site.

## Repositories

| Repo | What it is | Live |
|---|---|---|
| [**well-monitor**](https://github.com/Sigilint/well-monitor) | Our HackFW spring entry: a field of wells on a topographic map with CH₄, H₂S and VOC readings and leak alerts. It is a no-build React app. | [wellmonitor.sigilint.com](https://wellmonitor.sigilint.com) |
| [**well-site-monitor**](https://github.com/Sigilint/well-site-monitor) | One producing Barnett Shale gas well in Tarrant County, zoomed in: a live cutaway of the pad and the ground beneath it, with 54 sensors across production, safety, environment, integrity, security and weather. The well is a real public RRC record, and the sensors and readings are simulated. | [wellsite.sigilint.com](https://wellsite.sigilint.com) |
| [**offshore-platform-monitor**](https://github.com/Sigilint/offshore-platform-monitor) | A fictional fixed-jacket platform in the Gulf of Mexico (KESTREL-A) shown as a side-elevation schematic, with 84 sensors in six categories, scripted incidents, alerts and a raw data feed. Everything is simulated. | [platform.sigilint.com](https://platform.sigilint.com) |
| [**tarrant-map**](https://github.com/Sigilint/tarrant-map) | Tarrant Well Explorer: a searchable map of the roughly 7,300 wells the Texas Railroad Commission lists in Tarrant County, with status filters and well-ID and address lookup. It is built from a public RRC snapshot. | [wells.sigilint.com](https://wells.sigilint.com) |
| [**dashboard-toolkit**](https://github.com/Sigilint/dashboard-toolkit) | The React + TypeScript framework drawn out of our monitors. It provides data sources (simulator, REST, SSE, WebSocket, webhook relay), filters, saved views, alerts and components. Its examples include the well pad with ESP32 fenceline nodes. | [toolkit.sigilint.com](https://toolkit.sigilint.com) |
| [**texas-rrc-wells**](https://github.com/Sigilint/texas-rrc-wells) | Research and an access guide for the RRC's public well data, which needs no API key. It includes single-well and bulk county download examples and a well-deduplication analysis. | — |
| [**sigilint-web**](https://github.com/Sigilint/sigilint-web) | The sigilint.com website: static HTML and CSS, hosted on Netlify. [DEPLOYMENT.md](https://github.com/Sigilint/sigilint-web/blob/main/DEPLOYMENT.md) describes how every site above is hosted. | [sigilint.com](https://sigilint.com) |

## Come build with us

We recruit in the open. Come find the Sigilint table if you want to solder a node, fly a drone or help us stand up a mesh in a parking lot. We'll have dragon stickers, snacks and Raspberry Pis. See the [schedule](https://sigilint.com/careers#hackathons) or [get in touch](https://sigilint.com/contact).
