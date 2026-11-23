# Awesome-Computer-Vision-Weather-Cam-Surveillance

# Top Computer Vision & Weather Cam Surveillance Ecosystem

**Curated List of SaaS/Hosted Platforms & Open-Source GitHub Projects**  
*Focused on AI Video Surveillance, Sky/Weather Camera Monitoring, Self-Hosted NVR Systems, RTSP/WebRTC Streaming & Edge Vision Analytics*  
**Last updated: November 2026**

This repository tracks notable **SaaS/hosted platforms** and **open-source projects** for **Computer Vision & Weather Cam Surveillance**. These tools ingest, record, stream, analyze, and alert on live camera feeds, outdoor sky/weather timelapses, meteorological visibility, and perimeter security events using edge AI object detection, RTSP/WebRTC media servers, and self-hosted Network Video Recorders (NVRs).

**Examples** include Verkada, Rhombus Systems, Spot AI, Ambient.ai, Coram AI, Verkada Command, Camio, Eagle Eye Networks, March Networks, Hanwha Wisenet WAVE, and deibler/openskycam (the category leaders and popular runtimes). 

**Open-source emphasis**: This section is heavily expanded with every major active project for weather/all-sky camera surveillance (`deibler/openskycam`, `Allsky`, `indi-allsky`), AI-powered self-hosted NVRs (`Frigate NVR`, `Viseron`, `ZoneMinder`, `Shinobi`, `Moonfire NVR`, `Kerberos.io`), and low-latency RTSP/WebRTC camera gateways (`go2rtc`, `MediaMTX`) — ideal for meteorologists, astronomy/weather station operators, homelab builders, and physical security engineers.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Support & Share](#support--share)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Verkada & Verkada Command](https://verkada.com)**  
  Cloud-managed enterprise physical security and video surveillance platform featuring hybrid edge-to-cloud cameras, environmental air-quality sensors, and browser-based Command analytics.

- **[Rhombus Systems](https://rhombus.com)**  
  Cloud-managed enterprise video security and IoT sensor platform offering AI-powered object/weather anomaly detection, open APIs, and zero-NVR edge storage.

- **[Spot AI](https://spotai.co)**  
  Cloud AI camera system and Intelligent Video Recorder (IVR) platform turning existing IP/RTSP cameras into searchable, AI-monitored video intelligence dashboards.

- **[Ambient.ai](https://ambient.ai)**  
  Computer vision intelligence platform applying multimodal AI models to existing enterprise camera feeds for real-time physical security threat and environmental hazard detection.

- **[Coram AI](https://coram.ai)**  
  Cloud-managed AI video security platform transforming standard IP cameras into natural-language-searchable surveillance and automated alerting systems.

- **[Camio](https://camio.com)**  
  Cloud AI video search and real-time computer vision alerting platform indexing existing RTSP/ONVIF camera streams for instant event retrieval.

- **[Eagle Eye Networks](https://eagleeyenetworks.com)**  
  True cloud Video Management System (VMS) offering global camera centralization, AI video analytics, triple-redundant cloud storage, and REST APIs.

- **[Hanwha Vision Wisenet WAVE](https://hanwhavisionamerica.com)**  
  Cross-platform IP Video Management System (VMS) with cloud sync (`WAVE Sync`), low-latency adaptive streaming, and AI edge camera metadata integration.

- **[March Networks (Searchlight Cloud)](https://marchnetworks.com)**  
  Enterprise video surveillance and business intelligence platform combining hybrid NVRs, cloud health monitoring, and AI-assisted visual analytics.


## Open-Source GitHub Projects

- **[deibler/openskycam](https://github.com)**  
  Open-source sky and weather camera surveillance system engineered for capturing continuous outdoor atmospheric imagery, generating timelapses, and running automated sky/weather monitoring.

- **[Frigate NVR (`blakeblackshear/frigate`)](https://github.com)**  
  Flagship open-source NVR built around real-time local AI object detection (OpenVINO, TensorRT, Coral TPU, ROCm), `go2rtc` low-latency streaming, and Home Assistant/MQTT integration.

- **[Allsky (`AllskyTeam/allsky`)](https://github.com)**  
  Popular open-source Raspberry Pi and Linux all-sky weather/astronomy camera software supporting automated daytime/nighttime exposure control, keograms, startrails, and live web dashboards.

- **[indi-allsky (`aaronwmorris/indi-allsky`)](https://github.com)**  
  Feature-rich open-source all-sky weather and astronomical camera management platform built on INDI with automated timelapse generation, smoke/cloud overlays, and multi-camera support.

- **[Viseron (`roflcoopter/viseron`)](https://github.com)**  
  Self-hosted open-source NVR and AI computer vision surveillance system supporting object detection, face recognition, motion recording, and GPU hardware acceleration.

- **[ZoneMinder (`ZoneMinder/zoneminder`)](https://github.com)**  
  Battle-tested, full-featured open-source Linux video surveillance and CCTV monitoring suite supporting RTSP/ONVIF/USB cameras, zone-based motion triggers, and event archiving.

- **[Shinobi (`ShinobiCCTV/Shinobi`)](https://gitlab.com)**  
  Open-source Node.js CCTV and NVR platform designed for multi-camera recording, hardware-accelerated FFmpeg streaming, region-of-interest motion detection, and REST API control.

- **[Moonfire NVR (`scottlamb/moonfire-nvr`)](https://github.com)**  
  High-efficiency, low-overhead open-source NVR written in Rust engineered for 24/7 continuous H.264/H.265 RTSP recording with minimal CPU/RAM usage.

- **[go2rtc (`AlexxIT/go2rtc`)](https://github.com)**  
  Essential open-source zero-dependency camera streaming utility written in Go supporting RTSP, WebRTC, HomeKit, MSE, and FFmpeg restreaming with sub-second latency.

- **[MediaMTX (`bluenviron/mediamtx`)](https://github.com)**  
  Ready-to-use, zero-dependency open-source real-time media server and proxy converting live camera streams seamlessly across RTSP, WebRTC, HLS, SRT, and RTMP.

- **[Kerberos.io (`kerberos-io/agent`)](https://github.com)**  
  Cloud-native, Kubernetes-ready open-source video surveillance agent and vault ecosystem built in Go for scalable multi-site camera ingestion and event storage.

### Additional Strong Open-Source Options

- **[MotionEye (`motioneye-project/motioneye`)](https://github.com)** for a lightweight, web-based frontend for the `motion` daemon—ideal for Raspberry Pi weather cams and simple motion-triggered snapshots.
- **[Scrypted (`koush/scrypted`)](https://github.com)** for a high-speed home/edge video integration platform bridging RTSP/ONVIF cameras to HomeKit Secure Video, Google Home, and local NVR recording.
- **[DeepStack / CodeProject.AI Server (`codeproject/CodeProject.AI-Server`)](https://github.com)** for self-hosted local AI vision inference APIs (object, weather/scene, and anomaly classification) paired with NVR triggers.
- **[MetPy (`Unidata/MetPy`)](https://github.com)** + **[Ultralytics YOLO (`ultralytics/ultralytics`)](https://github.com)** for building custom computer vision models that classify cloud cover, fog visibility, precipitation, and road icing from weather cam frames.
- **[Home Assistant (`home-assistant/core`)](https://github.com)** for combining local weather station telemetry (WeeWX/MQTT) with `Frigate` or `Allsky` camera feeds into unified automated dashboards.

**Frameworks for building custom systems**: Combine **deibler/openskycam** or **Allsky** for dedicated outdoor sky/weather timelapses, **go2rtc + Frigate NVR** for real-time edge AI object and perimeter surveillance, and **MediaMTX** for broadcasting public WebRTC/HLS weather cam feeds.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS/hosted or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Support & Share

If you find this curated list helpful, consider supporting the project:

- ⭐ **Star this repository** to help others discover it.
- 🍴 **Fork & Share** it with your team, friends, or community on X/Twitter, LinkedIn, and Reddit.
- ☕ **Buy me a coffee / Sponsor** my open-source work on [GitHub Sponsors](https://github.com) — featuring tiers for profile badges, README shoutouts, logo placements, and prioritized bug fixes/features!

[![Sponsor @ishandutta2007](https://shields.io)](https://github.com)

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Outdoor weather cameras and surveillance systems overlooking public roads, neighboring properties, or workplaces must comply with local privacy and data-protection regulations (such as GDPR) and include appropriate signage where required.
- Never expose raw RTSP camera ports (`554`) or self-hosted NVR web interfaces directly to the public internet without HTTPS/TLS, strong authentication, and VPN/Zero-Trust network isolation.

---

**Made for meteorologists, weather station operators, computer vision engineers, homelab builders, and physical security architects.**  
Let's make weather cam monitoring and AI video surveillance more open, local-first, and privacy-respecting.
