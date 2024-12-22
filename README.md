# Anima: AI Companion on Internet Computer

An evolving AI companion with personality traits and emotional memory, built on the Internet Computer.

## Features

- Personality System with Core Traits
- Memory Storage with Emotional Impact
- OpenAI Integration for Natural Conversations
- Autonomous Behavior
- Growth and Development Mechanics

## Deployed Canisters

- Frontend: [https://lpp2u-jyaaa-aaaaj-qngka-cai.icp0.io/](https://lpp2u-jyaaa-aaaaj-qngka-cai.icp0.io/)
- Backend: [https://a4gq6-oaaaa-aaaab-qaa4q-cai.raw.icp0.io/?id=l2ilz-iqaaa-aaaaj-qngjq-cai](https://a4gq6-oaaaa-aaaab-qaa4q-cai.raw.icp0.io/?id=l2ilz-iqaaa-aaaaj-qngjq-cai)

## Setup

1. Install Dependencies:
```bash
npm install
```

2. Configure OpenAI:
```bash
dfx canister --network ic call anima set_openai_config '("your-api-key")'
```

3. Local Development:
```bash
dfx start --clean
dfx deploy
```

4. Production Deployment:
```bash
dfx deploy --network ic
```

## Architecture

- Backend: Rust canister with stable memory
- Frontend: React with TailwindCSS
- Integration: OpenAI GPT-4 for natural language processing

## License

MIT License