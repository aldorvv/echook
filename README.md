# Echook

![Go Version](https://img.shields.io/badge/Go-1.25-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Status](https://img.shields.io/badge/status-WIP-orange)

🪝 Webhook debugging proxy made easy.

## Features (planned)
- [x] Capture webhooks
- [ ] Real-time dashboard
- [ ] Replay functionality
- [ ] WebSocket updates

## Quick Start
```bash
# Clone the repo
git clone https://github.com/aldorvv/echook
cd echook

# Run
go run main.go
# Server running on :2407

# Send a test webhook
curl -X POST http://localhost:2407/w/test \
  -d '{"message": "hello world"}'

# View captured webhooks
curl http://localhost:2407/webhooks
```
