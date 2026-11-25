# RelayAPI — Web-Based REST API Client and Collection Runner

Web-Based REST API Client and Collection Runner featuring a request builder, response viewer, smart request validator, API error explainer, SSRF security guard, collections, runner, history, and environments.

This project keeps the original **RelayAPI React + TypeScript frontend** and includes the **API Nova Express + PostgreSQL backend** plus RelayAPI-compatible API endpoints.

## Project Contents

- `src/` — RelayAPI frontend (React, TypeScript, Vite)
- `backend/` — Express API, API Nova authentication/share/collection routes, RelayAPI compatibility routes, request execution proxy, and PostgreSQL schema
- `docker-compose.yml` — PostgreSQL 16 service
- `.env.example` and `backend/.env.example` — Environment configuration templates

## Requirements

- Node.js 20 or newer (Node 22 LTS recommended)
- npm
- PostgreSQL (via Docker Desktop or a cloud provider such as Neon)

## Getting Started

### 1. Clone the Repository

```bash
git clone <YOUR_REPOSITORY_URL>
cd <YOUR_REPOSITORY_FOLDER>
