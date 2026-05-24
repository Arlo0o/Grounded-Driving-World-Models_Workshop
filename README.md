# Grounded Driving World Models Workshop Website

Static website for the CoRL 2026 workshop proposal:

**Grounded World Models for Real-World Autonomous Driving Decision Making**

## Local Preview

```bash
cd /Users/liboom/Desktop/GroundedDrivingWorldModels
python3 -m http.server 8060
```

Open:

```text
http://localhost:8060/
```

## Structure

```text
index.html
styles.css
script.js
assets/
  uniscenev2/
  challenger/
```

## Resource Links Used By The Site

- UniSceneV2 code: https://github.com/Arlo0o/UniScene-Unified-Occupancy-centric-Driving-Scene-Generation
- Nuplan-Occ dataset and checkpoints: https://huggingface.co/datasets/Arlolo0/Nuplan-Occupancy/tree/main
- Challenger code: https://github.com/Pixtella/Challenger
- Adv-nuSc dataset: https://huggingface.co/datasets/Pixtella/Adv-nuSc

## Before Public Release

- Replace organizer placeholders.
- Replace speaker role placeholders with invited speakers and status.
- Update contact email.
- Fill workshop paper submission, notification, and camera-ready dates.
- Update final GitHub Pages URL after deployment.
