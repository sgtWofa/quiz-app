# 🎮 Quiz Game App — Optimized Prompt & Prototype

## Optimized Prompt
Build a modern, addictive quiz game app for desktop (.exe) and mobile (Play Store/App Store). The app allows users to select a subject and topic, then answer multiple-choice questions (4 alternatives, 1 correct). The app must feature:

- **Admin Tools**: Admins can set questions manually or generate bulk questions using AI. Questions should have difficulty levels (easy, medium, hard).
- **Gameplay Modes**: Play solo, with a friend, or against AI.
- **Immersive Experience**: Include sound effects, background music, and optional voice narration. Add smooth 3D animations, transitions, and gamified interactions.
- **Power-ups & Rewards**: Users earn credits, gems, points, and bonuses. These can be spent to slash two wrong answers, delay the timer, swap options, or unlock hints.
- **Tournaments & Challenges**: Admins set up tournaments with customizable entry fees, minimum subscribers, and rewards for top 3 players. Scheduled tournaments launch automatically when the date is due.
- **Addictive Game Design**: Leaderboards, streak bonuses, achievements, and daily login rewards.
- **Cross-platform**: Responsive for desktop and mobile, compiled as .exe for PC and as native builds for Play Store/App Store.

## Prototype
### 1. App Structure
- Home Screen: Play Now (Solo / Friend / AI), Tournaments & Challenges, Leaderboards & Achievements, Store, Settings & Profile
- Admin Dashboard: Add/Edit Questions, AI Bulk Question Generator, Tournament Management, Analytics

### 2. Gameplay Flow
- Player selects Subject → Topic → Difficulty.
- Timer starts (e.g., 20s per question).
- Player sees question with 4 options.
- Rewards (points, gems) based on speed + correctness.
- Power-ups: Slash Two, Delay Timer, Swap Options, Voice Hint

### 3. Visual & Audio Design
- 3D Animations: Question cards flipping, gems/points particle effects, confetti/fireworks, avatar interactions.
- Audio: Background music, voice-over, fun sound effects.

### 4. Multiplayer
- Friend Mode: Invite via code/link.
- AI Opponent: Adaptive difficulty AI.
- Tournament Mode: Pay entry fee, wait for players, scheduled start, prizes auto-assigned.

### 5. Reward System
- Daily Login Rewards
- Achievements (Perfect Round, Fastest Answer, Streak Master).
- Leaderboards: Global, Friends, Tournament-based.
- In-App Store: Buy credits/gems for power-ups.

### 6. Tech Stack
- Frontend: React Native (mobile), React + Tauri/Electron (desktop).
- Backend: Node.js / Laravel with WebSocket for real-time gameplay.
- Database: PostgreSQL / MySQL.
- AI Question Generator: GPT-based integration.
- Deployment: Desktop → .exe, Mobile → Play Store & App Store.

