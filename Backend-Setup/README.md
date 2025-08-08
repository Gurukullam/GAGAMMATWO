# Backend-Setup

This folder contains backend deployment files and configurations for hosting and server-side functionality.

## Purpose

- **Vercel deployment files** (vercel.json, api routes, etc.)
- **Server configuration files**
- **Environment setup scripts**
- **Database migration files**
- **API endpoint definitions**
- **Backend security configurations**

## Note

The main application follows **HTML-only architecture** where all frontend code is embedded within HTML files. This folder is specifically for backend/deployment files that cannot be embedded in HTML.

## Structure

```
Backend-Setup/
├── README.md (this file)
├── vercel.json (Vercel deployment config)
├── api/ (API routes for Vercel)
├── scripts/ (Setup and deployment scripts)
└── config/ (Backend configuration files)
```

All files in this folder are for backend deployment and server-side functionality only. 