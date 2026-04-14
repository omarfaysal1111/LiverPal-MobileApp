# LiverPal — Flutter Mobile Client

A liver health companion app integrating LLM-powered diagnosis assistance
and patient support. This is the Flutter mobile client.

> Backend API: [liverpal-api](https://github.com/omarfaysal1111/liver_api)

## What It Does

- Guides patients through liver health self-assessment workflows
- Connects to an LLM-powered backend for intelligent diagnosis assistance
- Provides medication reminders, health tracking, and doctor communication
- Built with a clean Flutter architecture for iOS and Android

## Tech Stack

- **Mobile:** Flutter · Dart
- **Native Integration:** C++ modules via Flutter Method Channels (for
  performance-critical processing)
- **Backend:** REST API integration with the LiverPal Python/FastAPI backend
- **AI:** LLM integration for contextual health guidance

## Note on C++ Module

This repo contains a C++ native module used for performance-sensitive
medical data processing, integrated into the Flutter app via Platform
Channels. It is not a standalone C++ application.

## Related

- [liverpal-api](https://github.com/omarfaysal1111/liver_api) — Python
  backend with LLM integration
