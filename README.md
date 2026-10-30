# 🔐 LegacyVault

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)](https://reactjs.org/)

> **Secure Digital Legacy Vault** - Protect your important information, documents, messages, and digital assets for the future.

## Overview

**LegacyVault** is a production-grade, full-stack cloud application that empowers users to securely store important documents, define trusted beneficiaries, and set release conditions for their digital legacy.

## Key Features

### Security

- End-to-End Encryption
- MFA / OTP Authentication
- Role-Based Access Control
- Complete Audit Trail

### Smart Features

- Digital Will Builder
- Dead-Man Switch
- Time-Locked Messages
- Conditional Release

## Quick Start

### Prerequisites

- Node.js >= 18.0.0
- pnpm >= 8.0.0
- Docker & Docker Compose

### Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/legacyvault.git
cd legacyvault

# Install dependencies
pnpm install

# Copy environment variables
cp .env.example .env

# Start development environment
pnpm docker:dev

# Access the application
# Frontend: http://localhost:3000
# Backend API: http://localhost:3001
