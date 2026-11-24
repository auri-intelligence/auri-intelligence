<p align="center">
  <img src="assets/banner.svg" alt="AurI Intelligence" width="100%">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/MicroPython-2B2728?style=flat&logo=micropython&logoColor=white" alt="MicroPython">
  <img src="https://img.shields.io/badge/ESP32--S3-E7352C?style=flat&logo=espressif&logoColor=white" alt="ESP32-S3">
  <img src="https://img.shields.io/badge/Home%20Assistant-18BCF2?style=flat&logo=homeassistant&logoColor=white" alt="Home Assistant">
  <img src="https://img.shields.io/badge/KiCad-314CB0?style=flat&logo=kicad&logoColor=white" alt="KiCad">
</p>

### Hi, I'm Luigi

Software developer from Italy. I build **AurI**, a personal ecosystem of small services that run my home and my day: home automation, calendar, fitness, recipes, all talking to each other and to an AI assistant.

In my spare time I give old hardware a second life.

### Featured project

<table>
<tr>
<td width="50%">

**[auri-3310](https://github.com/auri-intelligence/auri-3310)**

A real phone from 2000 with a brand new ESP32-S3 brain. Original shell, screen and keys; new Wi-Fi, Home Assistant control and a Claude shell that asks before acting.

`MicroPython` `KiCad` `open hardware`

</td>
<td width="50%">

```text
  Phone               Raspberry Pi
  ESP32-S3 --Wi-Fi--> AurI Bridge --> Claude, Gemini
  AurI OS  <--------  (Python)   --> Home Assistant
```

Try the simulator: `cd firmware && python sim.py`

</td>
</tr>
</table>

### The AurI ecosystem

| Area | What it does |
|---|---|
| core, common | shared backend and libraries |
| domus, nest | home automation on top of Home Assistant |
| calendar, dine, fitness | everyday life: agenda, meals, training |
| control, ui-shared | web dashboard and shared UI components |
| deploy | self-hosted deployment on my home server |

Most of these are private for now: the 3310 is the first to go public.

### Get in touch

<p>
  <a href="https://www.instagram.com/auri.intelligence/"><img src="https://img.shields.io/badge/Instagram-E4405F?style=flat&logo=instagram&logoColor=white" alt="Instagram"></a>
  <a href="https://www.tiktok.com/@auri.intelligence"><img src="https://img.shields.io/badge/TikTok-000000?style=flat&logo=tiktok&logoColor=white" alt="TikTok"></a>
</p>

Follow the builds on Instagram and TikTok, or open an issue on any public repo, even just to ask something.
