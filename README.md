# Class Check-In (Web-only MVP)

Privacy-safe class check-in:
- Teacher creates a session code + join link + QR
- Students join from phone browser
- Consent required before joining
- Live roster updates (socket.io)
- Students self-report activity + focus toggle
- Export CSV
- End session

## Local setup (dev)

### 1) Server
```bash
cd server
npm install
npm run dev
