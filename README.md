# Pet Platform 🐾
UK-first Rover-style platform connecting pet owners with verified local sitters for boarding, house sitting, dog walking, doggy day care, and drop-in visits. Built with Flutter (iOS &amp; Android) and a cloud-native backend.



This platform connecting **pet owners** with verified local **sitters** who provide:

- **Boarding** – pets stay overnight in the sitter’s home.
- **House Sitting** – sitter cares for pets in the owner’s home.
- **Dog Walking** – scheduled local walks.
- **Doggy Day Care** – daytime care with drop-off and pick-up.
- **Drop-In Visits** – short home visits for play, feeding, and care.

---

## Tech stack

- **Mobile:** Flutter (iOS + Android)
- **Backend API:** Fastify (TypeScript, Node.js)
- **Database:** Postgres + Redis
- **Search:** (future) OpenSearch/Vector search
- **Infra:** Docker, GitHub Actions, Terraform (planned)

---

## Features

- 📱 Mobile app for iOS & Android (Flutter)
- 🔐 Secure identity & sitter verification
- 📍 Location-based search & availability
- 💳 Stripe payments & sitter payouts
- 💬 Messaging & photo updates
- 🛡 RoverProtect-style guarantee & claims workflow
- ☁️ Cloud-native, scalable microservice architecture

---

## Local development

### Prerequisites
- [Node.js 20+](https://nodejs.org/)
- [pnpm](https://pnpm.io/)
- [Docker Desktop](https://www.docker.com/products/docker-desktop/)
- [Flutter SDK](https://docs.flutter.dev/get-started/install)

### Clone & run
```bash
git clone https://github.com/<your-username>/pet-platform.git
cd pet-platform

# API
cd apps/api && npm install && npm run dev

# Mobile app
cd apps/mobile && flutter run

