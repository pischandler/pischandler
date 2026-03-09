<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&pause=1000&color=58A6FF&center=true&vCenter=true&width=600&lines=Hi%2C+I'm+Felipe+Schandler+%F0%9F%91%8B;Full+Stack+%2B+IoT+%2B+Computer+Vision;Building+things+that+matter" alt="Typing SVG" />

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/felipe-schandler/)
[![Portfolio](https://img.shields.io/badge/dotwave.com.br-111827?style=for-the-badge&logo=vercel&logoColor=white)](https://dotwave.com.br/)
[![GitHub](https://img.shields.io/badge/GitHub-pischandler-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/pischandler)

</div>

---

## About me

Computer Engineering student at **UEPG (Brazil)** — finishing my undergraduate thesis on low-cost smart agriculture with IoT and ML.

I build across the stack: **production APIs and SPAs** on the web side, **embedded firmware** on the hardware side, and **ML inference pipelines** connecting both. I also run **[dotwave](https://dotwave.com.br/)**, a freelance studio delivering institutional sites, web systems, and landing pages.

- 🔬 **Thesis:** low-cost smart garden integrating ESP32-S3 + OV2640 camera with a Flask ML API for real-time tomato leaf disease detection
- 🌐 **Web:** TypeScript, NestJS, Vue.js, Next.js — APIs and SPAs from design to deploy
- 🤖 **ML:** 188 handcrafted features (Haralick, Zernike, LBP, HSV, Hu moments), XGBoost/RF/SVM, StratifiedGroupKFold
- ⚙️ **Embedded:** ESP32-S3, PlatformIO, C/C++, sensor arrays, actuator control, OV2640 streaming

---

## 🌱 Featured project — Undergraduate Thesis

### [`uepg-garden-lowcost-iot-ml`](https://github.com/pischandler/uepg-garden-lowcost-iot-ml)

> End-to-end smart garden prototype built for a budget. The ESP32-S3 reads soil moisture, light, temperature and humidity, controls irrigation and ventilation, streams camera frames — and sends them to a Flask ML API that extracts 188 features and returns a disease prediction in < 500 ms.

```
ESP32-S3 (sensors + OV2640)  →  /capture endpoint
        ↓
Flask API  →  HSV segmentation  →  188 features  →  XGBoost  →  JSON response
(classe_predita · score · top-k · timings_ms)
```

**Stack:** C/C++ · PlatformIO · Python 3.10+ · Flask · XGBoost · OpenCV · Albumentations · Docker · GitHub Actions · Prometheus

[![Repo](https://img.shields.io/badge/View%20Repo-181717?style=flat-square&logo=github)](https://github.com/pischandler/uepg-garden-lowcost-iot-ml)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=flat-square)](https://github.com/pischandler/uepg-garden-lowcost-iot-ml/blob/main/LICENSE)
![Languages](https://img.shields.io/github/languages/count/pischandler/uepg-garden-lowcost-iot-ml?style=flat-square&color=58a6ff)

---

## 🧰 Tech stack

**Backend & APIs**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)

**Frontend**

![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

**ML / CV**

![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-189AB4?style=flat-square&logo=python&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)

**Embedded**

![ESP32](https://img.shields.io/badge/ESP32--S3-E7352C?style=flat-square&logo=espressif&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![PlatformIO](https://img.shields.io/badge/PlatformIO-FF7F00?style=flat-square&logo=platformio&logoColor=white)

**Infra & tooling**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## 📊 GitHub stats

<div align="center">

<img height="160" src="https://streak-stats.demolab.com?user=pischandler&theme=github-dark-blue&hide_border=true&date_format=j%20M%5B%20Y%5D" />
<img height="160" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=pischandler&theme=github_dark" />

</div>

---

## 🔗 Links

| | |
|---|---|
| 💼 Freelance studio | [dotwave.com.br](https://dotwave.com.br/) |
| 👔 LinkedIn | [linkedin.com/in/felipe-schandler](https://www.linkedin.com/in/felipe-schandler/) |
| 🎓 University | [UEPG — Universidade Estadual de Ponta Grossa](https://uepg.br/) |

---

<div align="center">
<sub>Open to international opportunities · Remote-friendly · Ponta Grossa, Brazil 🇧🇷</sub>
</div>
