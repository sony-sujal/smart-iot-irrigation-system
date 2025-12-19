# Smart Hybrid IoT-Based Irrigation & Crop Advisory System

An ongoing IoT project focused on intelligent irrigation automation using sensor data and real-time weather information.

## Project Status
🚧 In active development

## Overview
This system combines on-field soil moisture sensing with external weather data to optimize irrigation schedules. A mobile application is used for configuration, monitoring, and automation control.

## Key Features
- Soil moisture-based irrigation control
- Weather-aware decision logic (ET₀ × Kc approach)
- Android mobile app (Kotlin + Jetpack Compose)
- Firebase OTP authentication
- Supabase backend for data storage and automation logic
- Modular design supporting mock data during development

## Architecture
- Mobile App → Firebase Authentication
- Backend → Supabase (PostgreSQL + business logic)
- Sensors → ESP32 + soil moisture sensors (planned)

## Tech Stack
- Android: Kotlin, Jetpack Compose
- Backend: Supabase, PostgreSQL
- Authentication: Firebase OTP
- IoT: ESP32, soil moisture sensors (planned)

## Future Work
- Live sensor integration
- Pump automation with safety rules
- Notifications and analytics dashboard
