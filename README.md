# StudyChain

A decentralized educational study session tracking and reward system for incentivizing consistent learning on Stacks blockchain.

## Features

- Study session tracking with duration-based rewards
- Scholar level progression system with bonus multipliers
- Study point accumulation and redemption
- Curriculum plan optimization with time-based penalties
- Comprehensive educational program statistics

## Smart Contract Functions

### Public Functions
- `start-study-session` - Begin educational study session
- `complete-study-session` - Complete study and earn rewards
- `claim-study-rewards` - Claim accumulated study points
- `optimize-curriculum-plan` - Optimize curriculum with point investment
- `complete-curriculum-optimization` - Complete optimization process

### Read-Only Functions
- `get-study-session-count` - Get user's total study sessions
- `get-study-point-balance` - Get user's study point balance
- `get-scholar-level` - Get user's scholar level
- `get-study-program-stats` - Get overall program statistics

## Reward System
- Base reward: 20 points per study session
- Scholar bonus: 7 points per level (max level 10)
- Optimization multiplier: 3x for curriculum plans

## Usage

Deploy the contract to create an educational incentive system where students can track study sessions, earn rewards, and optimize their learning curriculum.

## License

MIT