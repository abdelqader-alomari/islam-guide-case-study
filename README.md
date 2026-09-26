<div align="center">

<img src="./assets/cover.svg" alt="Islam Guide case study" width="100%"/>

[![Live](https://img.shields.io/badge/Live-islamguide.us-22c55e?style=for-the-badge&logo=googlechrome&logoColor=white)](https://islamguide.us) ![Source](https://img.shields.io/badge/Source-private-64748b?style=for-the-badge&logo=lock&logoColor=white)

</div>

> 🔒 **The source code is private** (production / client work). This repository is a case study: what the product does, how it is built, and my role. A code walkthrough is available on request: [abdelqader.pro](https://abdelqader.pro) · [LinkedIn](https://www.linkedin.com/in/abdelqader-al-omari/).

## Overview
A free, comprehensive reference that introduces the teachings of Islam through authentic sources, in widely spoken
languages, built to stay fast and discoverable at scale.

## Key features
- 🎓 **Course Builder LMS**: structured courses (Muslim 101/103/105, Fiqh of Zakat...) built with a course builder
- 📚 **Interactive book readers** in the books library
- 🎧 **Multimedia hub** bringing together YouTube and SoundCloud content
- 🕌 **Location-aware prayer-times dashboard**
- 🌍 **Multilingual** interface and content
- 🔎 **SEO & performance** optimization so the content is found and loads fast

## Architecture

```mermaid
flowchart LR
    V([🌍 Visitors]) --> CDN[⚡ CDN] --> N[▲ Next.js<br/>SSR / SSG]
    N --> API[(🗄️ Content API & DB)]
    N --> M[🎧 YouTube / SoundCloud]
    N --> PT[🕌 Prayer-times service]
    A([✍️ Editors]) --> CB[🎓 Course Builder] --> API
```

## My role
Full-stack development: architecture, the Next.js front end, the course builder, integrations, and SEO & performance work.

## Tech
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white) ![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black) ![SEO](https://img.shields.io/badge/SEO-22c55e?style=for-the-badge&logo=googlesearchconsole&logoColor=white) ![i18n](https://img.shields.io/badge/i18n-0ea5e9?style=for-the-badge&logo=googletranslate&logoColor=white)

## Screenshots

<p align="center"><img src="./assets/home.jpg" alt="Home: courses, library and multimedia in one place" width="100%"/><br/><sub>Home: courses, library and multimedia in one place</sub></p>

<p align="center"><img src="./assets/mobile.jpg" alt="Mobile-first layout" width="360"/><br/><sub>Mobile-first layout</sub></p>


---

<div align="center">

**Built by [Abdelqader Al-Omari](https://github.com/abdelqader-alomari)** · Senior Full-Stack Engineer · AI & Enterprise Solutions

[![Portfolio](https://img.shields.io/badge/abdelqader.pro-8b5cf6?style=for-the-badge&logo=googlechrome&logoColor=white)](https://abdelqader.pro) [![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abdelqader-al-omari/) [![More work](https://img.shields.io/badge/More_case_studies-111827?style=for-the-badge&logo=github&logoColor=white)](https://github.com/abdelqader-alomari)

</div>
