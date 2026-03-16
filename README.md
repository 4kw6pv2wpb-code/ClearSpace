# ClearSpace

> **"We don't steal your data. Find what you need, organized."**

A privacy-first social and organizational platform built to compete with Meta. No data harvesting. No algorithmic manipulation. Just clean, organized spaces for real human connection.

---

## The Problem with Meta

- Facebook/Instagram harvest your personal data and sell it to advertisers
- Algorithmic feeds are designed to keep you addicted, not informed
- Content is buried in noise — you can't find what you actually need
- Your data is the product, not the service

## ClearSpace is Different

| Meta | ClearSpace |
|------|------------|
| Sells your data | Zero data harvesting |
| Algorithmic addiction | User-controlled feeds |
| Cluttered, noisy | Clean, organized spaces |
| You are the product | You are the user |
| Hidden content | Everything findable |

---

## Core Features (MVP)

### 1. Organized Spaces
Create and join topic-based spaces (Health, Tech, Community, Education, etc.). No algorithmic feed — content is categorized and searchable.

### 2. Privacy Vault
- End-to-end encryption on all messages
- No tracking pixels, no cookies, no ad profiles
- User data stays on-device where possible
- Transparent privacy dashboard showing exactly what data exists

### 3. Smart Discovery
Find people, content, and resources through organized categories — not manipulative algorithms. Search works like it should.

### 4. Community Boards
Structured discussion boards for neighborhoods, organizations, interest groups. Think Reddit's organization + Facebook's social layer — minus the data theft.

### 5. Direct Connect
Private messaging with zero data collection. Your conversations are yours.

---

## Tech Stack

- **Frontend (Mobile):** React Native (iOS + Android)
- **Frontend (Web):** React.js
- **Backend:** Node.js + Express
- **Database:** PostgreSQL (encrypted at rest)
- **Auth:** JWT + OAuth (no third-party data sharing)
- **Real-time:** Socket.io
- **Storage:** Self-hosted / encrypted cloud
- **Privacy:** Zero-knowledge architecture

---

## Project Structure

```
ClearSpace/
|-- mobile/                 # React Native mobile app
|   |-- src/
|   |   |-- screens/        # App screens
|   |   |-- components/     # Reusable UI components
|   |   |-- navigation/     # React Navigation setup
|   |   |-- services/       # API calls
|   |   |-- utils/          # Helper functions
|   |   |-- context/        # App state management
|-- server/                 # Node.js backend
|   |-- routes/             # API endpoints
|   |-- models/             # Database models
|   |-- middleware/          # Auth, privacy middleware
|   |-- config/             # Environment config
|-- web/                    # React.js web app
|-- docs/                   # Documentation
|-- README.md
```

---

## Motto & Brand

**Tagline:** "We don't steal your data."

**Mission:** Build the social platform people deserve — organized, private, and human-first.

**Values:**
1. Privacy is a right, not a feature
2. Your attention is yours — no manipulation
3. Content should be findable, not buried
4. Transparency over profit

---

## Getting Started

```bash
# Clone the repo
git clone https://github.com/4kw6pv2wpb-code/ClearSpace.git
cd ClearSpace

# Install mobile app dependencies
cd mobile
npm install

# Start the app
npx react-native start
```

---

## Roadmap

- [x] Project setup & architecture
- [ ] Mobile app scaffolding (React Native)
- [ ] User authentication (privacy-first)
- [ ] Organized Spaces feature
- [ ] Smart Discovery search
- [ ] Community Boards
- [ ] Direct Connect messaging
- [ ] Privacy Vault dashboard
- [ ] Web app version
- [ ] Beta launch

---

## Contributing

This is an open-source project. If you believe social media should respect users, contribute.

---

## License

MIT License

---

*Built by Eyob — because the internet deserves better than Meta.*
