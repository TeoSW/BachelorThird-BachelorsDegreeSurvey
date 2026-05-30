# 🏙️ Bucharest Urbanism Survey

> A web application for collecting Bucharest residents' opinions on urban quality of life — traffic, public transport, bike lanes, and residential neighborhoods.

---

## 📌 Description

An Angular 18 application with SSR (Server-Side Rendering) implementing an online survey structured across 5 sections, with responses submitted and stored in a MySQL database. The project was built as a data collection tool for the bachelor's thesis **"Current Urban Planning Challenges in Bucharest"**.

---

## 🗂️ Survey Sections

| Section | Content |
|---|---|
| **0 – Identification** | Age, gender, education, district, neighborhood, residence duration, main transport |
| **1 – Traffic** | Frequency of issues, daily time in traffic, parking ease, illegal parking |
| **3 – Cycling & Public Transport** | Bike lane satisfaction, cyclist safety, public transport cleanliness, metro coverage |
| **4 – Residential Neighborhoods** | Quality of life, construction legality, sidewalks, green spaces, illegal parking enforcement |
| **5 – Closing** | Additional issues, open feedback |

---

## 🛠️ Tech Stack

![Angular](https://img.shields.io/badge/Angular-18-red?logo=angular)
![TypeScript](https://img.shields.io/badge/TypeScript-5.5-blue?logo=typescript)
![Node.js](https://img.shields.io/badge/Node.js-Express-green?logo=node.js)
![MySQL](https://img.shields.io/badge/MySQL-Database-orange?logo=mysql)

| Technology | Role |
|---|---|
| Angular 18 + SSR | Frontend + Server-Side Rendering |
| Express.js | HTTP server + API endpoints |
| MySQL2 | Response storage |
| Angular Forms | Two-way binding with `ngModel` |

---

## ⚙️ Installation & Usage

```bash
npm install
npm start                            # development
npm run build                        # production build
npm run serve:ssr:ChestionarLicenta  # SSR production
```

---

## 🗂️ Project Structure

```
📁 chestionar-licenta/
├── src/
│   ├── app/
│   │   ├── app-component/         # Main component with the survey form
│   │   ├── app.config.ts          # Client configuration
│   │   ├── app.config.server.ts   # SSR configuration
│   │   └── app.routes.ts          # Routing
│   ├── main.ts                    # Client bootstrap
│   ├── main.server.ts             # SSR bootstrap
│   └── express.d.ts               # Custom Express types
├── server.ts                      # Express server
├── tsconfig.json
├── tsconfig.app.json
└── tsconfig.server.json
```

---

*Academic project | Bucharest University of Economic Studies (ASE), 2025*
