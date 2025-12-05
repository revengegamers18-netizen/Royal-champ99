# Royal-champ99
# Node.js dependencies
/node_modules/
npm-debug.log*
yarn-debug.log*
yarn-error.log*

# Environment variables
.env
.env.local
.env.*.local

# Logs
logs/
*.log

# OS files
.DS_Store
Thumbs.db

# Docker files
docker-compose.override.yml
*.pid
*.sock

# Build outputs
dist/
build/
frontend/dist/

# IDE/editor settings
.vscode/
.idea/
*.sublime-workspace
*.sublime-project

# Temporary files
tmp/
temp/
.npm/
.yarn/

MIT License

Copyright (c) 2025 Royal champ99

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

# Royal champ99

Royal champ99 is a web-based betting app with wallet, deposit, and premium features. This repository includes:

- Backend (Node.js + Express)
- Frontend deposit demo (Stripe & Razorpay)
- Docker + Docker Compose setup
- CI/CD workflow for building and pushing Docker images
- Multi-platform Docker Buildx support

## Features

- Wallet management
- Deposit via Stripe or Razorpay
- Transaction history
- Premium subscription management
- Support ticket system

## Setup

### Prerequisites

- Docker & Docker Compose
- Node.js & npm (optional for local backend)
- Stripe & Razorpay accounts

### Running Locally

```bash
docker compose up --build

STRIPE_SECRET_KEY=
STRIPE_WEBHOOK_SECRET=
RAZORPAY_KEY_ID=
RAZORPAY_KEY_SECRET=
RAZORPAY_WEBHOOK_SECRET=
PORT=3000
APP_NAME=Royal champ99

---

### ✅ What This Edit Does

1. Adds **`.gitignore`** to exclude sensitive files & build artifacts.  
2. Adds **MIT LICENSE** for legal clarity.  
3. Updates **README** with:  
   - Project description  
   - Features  
   - Setup instructions  
   - Environment variables  
   - License reference  

---

I can also **commit all of these changes automatically into your repo** and provide a **ready-to-use zip** including `.gitignore`, `LICENSE`, and updated `README.md`.  

Do you want me to do that next?
