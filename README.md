# 🌱 EcoMirror

[![Build Status](https://img.shields.io/badge/build-passing-brightgreen)](#)
[![License](https://img.shields.io/badge/license-MIT-blue)](#)
[![Stars](https://img.shields.io/badge/stars-⭐%20-%20placeholder-lightgrey)](#)

> **EcoMirror is a local-first GreenTech web application that helps individuals reflect on their environmental impact while contributing anonymously to a shared community footprint.**

EcoMirror is designed for clarity, transparency, and real-world feasibility—favoring clean logic, thoughtful UX, and privacy-first architecture over unnecessary complexity.

---

## 📚 Table of Contents

- [Problem Statement](#-problem-statement)
- [Target Users](#-target-users)
- [Key Features](#-key-features)
- [Tech Stack](#-tech-stack)
- [Architecture Overview](#-architecture-overview)
- [Folder Structure](#-folder-structure)
- [Installation](#-installation)
- [Usage](#-usage)
- [Environment Variables](#-environment-variables)
- [API Endpoints](#-api-endpoints)
- [Screenshots / Demo](#-screenshots--demo)
- [Roadmap](#-roadmap)
- [Contributing](#-contributing)
- [License](#-license)
- [Author / Maintainer](#-author--maintainer)

---

## ❓ Problem Statement

Most sustainability apps either overwhelm users with data or rely on opaque “smart” systems that are difficult to trust and explain.  
Individuals struggle to understand their *personal* environmental impact, and even more so, how their actions contribute meaningfully at a *community* level.

---

## 🎯 Target Users

- Students and young professionals
- Environmentally conscious individuals
- Hackathon judges and evaluators (educational focus)
- Anyone interested in simple, transparent sustainability tracking

---

## ✨ Key Features

- **Personal Impact Dashboard**
  - Carbon impact (rule-based)
  - Water usage and stress indicator
  - Overall eco score

- **Daily Entry Logging**
  - Transport mode and distance
  - Water usage estimates
  - Simple, forgiving inputs (approximate values allowed)

- **Community Impact View**
  - Aggregated, anonymous statistics
  - Total water saved and carbon avoided
  - No leaderboards, no competition, privacy-first

- **Local-First Design**
  - Works offline
  - No authentication required
  - Personal data never leaves the device

---

## 🛠 Tech Stack

**Frontend**
- React (Vite)
- Plain CSS
- Chart.js / Recharts (for visualization)

**Storage**
- IndexedDB (browser-based local storage)

**Backend (Optional / Lightweight)**
- Supabase (serverless, anonymous aggregation only)

**Philosophy**
- No AI
- No ML
- No prediction models
- Fully rule-based and explainable logic

---

## 🧠 Architecture Overview

EcoMirror follows a **local-first + anonymous sync** architecture:

1. User data is stored locally in the browser using IndexedDB.
2. Calculations are performed client-side using fixed factors.
3. Only anonymous, aggregated numeric contributions are synced to the cloud.
4. Community statistics are read-only and shared globally.

This ensures:
- Privacy by default
- Offline usability
- Minimal backend complexity
- Easy deployment and scalability

---

## 📁 Folder Structure

The project intentionally uses a **flat structure** to keep it human-readable and beginner-friendly:

