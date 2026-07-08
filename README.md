<div align="center">

![header](https://capsule-render.vercel.app/api?type=waving&color=0:1e3a8a,50:2563eb,100:06b6d4&height=200&section=header&text=김정웅%20·%20Full-stack%20Developer&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=웹%20화면부터%20공장%20설비까지,%20데이터가%20흐르는%20길을%20만듭니다&descSize=16&descAlignY=58)

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1000&color=2563EB&center=true&vCenter=true&width=520&lines=SaaS+MES+%2B+Industrial+IoT;Django+%C2%B7+React+%C2%B7+ESP32;%ED%99%94%EB%A9%B4+%EB%92%A4%EC%9D%98+%EC%84%9C%EB%B2%84%2C+%EC%84%9C%EB%B2%84+%EB%92%A4%EC%9D%98+%EC%84%BC%EC%84%9C%EA%B9%8C%EC%A7%80+%F0%9F%8D%9E)](https://git.io/typing-svg)

[![Portfolio](https://img.shields.io/badge/Portfolio-woong4252.vercel.app-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://woong4252.vercel.app)
[![Email](https://img.shields.io/badge/Email-woong4252%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:woong4252@gmail.com)

</div>

## 🛠 지금 하는 일

**서울소프트**에서 제조 현장을 위한 **SaaS MES**와 **산업용 IoT 게이트웨이**를 만들고 있습니다.

- 🏭 생산 · 재고 · 설비 · KPI를 아우르는 멀티테넌트 MES (Django + PostgreSQL + Docker)
- 📡 현장 설비(금속검출기, 전류센서 등)를 **RS485 / Modbus RTU → ESP32 → WiFi**로 MES에 연결하는 게이트웨이 펌웨어
- ⚙️ PLC 데이터 수집, Celery 기반 KPI 집계 파이프라인

> 이전에는 **굿스트림**에서 React · Ext JS 기반 엔터프라이즈 시스템을 개발했습니다.

## 🔩 소프트웨어만으로 안 끝나는 문제를 좋아합니다

MES를 만들다 보면 결국 데이터의 출발점인 **기계 앞에 서게 됩니다.**
납땜하고, 시리얼 모니터를 들여다보고, 현장에 직접 가서 배선을 확인하는 것까지가 제 개발 범위입니다.

```mermaid
flowchart LR
    A[🔍 금속검출기] -->|RS485 / Modbus RTU| B[📟 ESP32]
    B -->|WiFi / HTTP| C[🖥 MES]
    C --> D[📊 대시보드]
    style A fill:#dc2626,color:#fff,stroke:none
    style B fill:#ea580c,color:#fff,stroke:none
    style C fill:#2563eb,color:#fff,stroke:none
    style D fill:#059669,color:#fff,stroke:none
```

## 📌 Projects

| 프로젝트 | 설명 | 스택 |
|---|---|---|
| 🏭 **SaaS MES** | 제조 현장용 멀티테넌트 MES — 생산 · 재고 · 구매 · KPI · AI 공정 최적화 | ![Django](https://img.shields.io/badge/-Django-092E20?style=flat-square&logo=django) ![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white) |
| 📡 **IoT Gateway 펌웨어** | 산업 설비 → MES 실시간 연동 게이트웨이. 단계별 테스트 스케치로 검증하며 개발 | ![ESP32](https://img.shields.io/badge/-ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white) ![MQTT](https://img.shields.io/badge/-MQTT-660066?style=flat-square&logo=mqtt&logoColor=white) ![Modbus](https://img.shields.io/badge/-Modbus_RTU-555555?style=flat-square) |
| 🌐 **[Portfolio](https://woong4252.vercel.app)** | 포트폴리오 & 기술 블로그 (Modbus RTU 입문기 등) | ![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Tailwind](https://img.shields.io/badge/-Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white) |

## ⚡ Tech Stack

<table>
<tr>
<td valign="top" width="50%">

### 🎨 Frontend

![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Ext JS](https://img.shields.io/badge/Ext_JS-86BC40?style=for-the-badge&logo=sencha&logoColor=white)

</td>
<td valign="top" width="50%">

### 🧩 Backend

![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=celery&logoColor=white)

</td>
</tr>
<tr>
<td valign="top" width="50%">

### 🔌 IoT / Embedded

![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00878F?style=for-the-badge&logo=arduino&logoColor=white)
![MQTT](https://img.shields.io/badge/MQTT-660066?style=for-the-badge&logo=mqtt&logoColor=white)
![Modbus RTU](https://img.shields.io/badge/Modbus_RTU_%2F_RS485-555555?style=for-the-badge)

</td>
<td valign="top" width="50%">

### 🚀 DevOps

![AWS](https://img.shields.io/badge/AWS_EC2-FF9900?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![nginx](https://img.shields.io/badge/nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)

</td>
</tr>
</table>

## 📊 GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=BreadEatBread&show_icons=true&theme=github_dark_dimmed&hide_border=true&locale=kr)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=BreadEatBread&layout=compact&theme=github_dark_dimmed&hide_border=true&langs_count=8)

![GitHub Streak](https://streak-stats.demolab.com?user=BreadEatBread&theme=github-dark-dimmed&hide_border=true&locale=ko)

</div>

<div align="center">

*화면 뒤의 서버, 서버 뒤의 센서까지.* 🍞

![footer](https://capsule-render.vercel.app/api?type=waving&color=0:06b6d4,50:2563eb,100:1e3a8a&height=120&section=footer)

</div>
