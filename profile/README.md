# PetalBot: Smart Plant Care Assistant
[![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=white)](https://reactjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/TailwindCSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)
[![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)](https://firebase.google.com/)
[![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)](https://vitejs.dev/)

PetalBot is a responsive web application designed to assist users in managing their plants more effectively using smart tools, intuitive interfaces, and an AI-based assistant. Developed as a diploma project by students at the Faculty of Electrical Engineering and Computer Science (FERI), University of Maribor.

![SplashImage](https://images.pexels.com/photos/1208377/pexels-photo-1208377.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2)

## Table of Contents
- [Introduction](#introduction)
- [Project Objectives](#project-objectives)
- [Technical Overview](#technical-overview)
    - [Modules](#modules)
        * [Plant Tracker](#plant-tracker)
        * [Smart Assistant](#smart-assistant)
        * [Task Scheduler](#task-scheduler)
        * [Area & Image Manager](#area--image-manager)

---

## Introduction
PetalBot provides a complete digital companion for plant owners. Whether you're a hobbyist, student, or researcher, the platform helps you stay organized with plant care, track health metrics, and get AI-based suggestions. It’s accessible via web and optimized for both desktop and mobile use.

---

## Project Objectives
- **Simplified Plant Management**: Enable users to manage multiple plants across defined spaces.
- **Personalized AI Assistant**: Offer tailored advice using a conversational interface.
- **Task Automation**: Support scheduling of care routines like watering, feeding, or replanting.
- **Visual Documentation**: Allow users to log notes and photos as part of long-term growth tracking.

---

## Technical Overview
PetalBot is built as a full-stack client-side application integrated with Firebase for authentication and real-time data storage. The interface is built using modern UI and routing libraries to maintain a seamless user experience.

### Modules

#### Plant Tracker
- **Description**: Lets users add, label, and categorize individual plants with care instructions and notes.
- **Technology**: Form-managed components, Firebase storage, and custom plant tags.

#### Smart Assistant
- **Description**: A built-in chatbot interface that helps users solve issues like pest control, watering frequency, and soil selection.
- **Technology**: Integrated using prompt-based logic (or optional LLM API connection).

#### Task Scheduler
- **Description**: Users can schedule watering, pruning, or fertilizing tasks and mark them as complete.
- **Technology**: Firebase Firestore + UI calendar components.

#### Area & Image Manager
- **Description**: Allows users to define plant spaces and upload growth photos for each plant or zone.
- **Technology**: Drag-and-drop interface for areas, image uploads stored in Firebase Storage.

---

## Deployment & Development

Clone the repo and start the dev server:

```bash
git clone https://github.com/your-org/petalbot.git
cd petalbot
npm install
npm run dev
```
