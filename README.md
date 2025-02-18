# DexScreener on Steroids

A cutting-edge trading bot + dashboard for Solana memecoins featuring real-time analytics, auto-snipe capabilities, social sentiment analysis, and rug-check tools.

## Features

- Real-time token analytics and price tracking
- Automated trading bot with customizable strategies
- Social sentiment analysis for trending tokens
- Rug-check tools and risk assessment
- Interactive dashboard with TradingView integration

## Project Structure

```
/
├── backend/           # FastAPI backend
│   ├── main.py        # Main application entry
│   ├── database.py    # Database configurations
│   ├── apis.py        # External API integrations
│   └── trading.py     # Trading engine logic
│
└── frontend/          # Next.js frontend
    ├── pages/         # Application pages
    ├── components/    # Reusable components
    └── styles/        # CSS and styling
```

## Getting Started

### Prerequisites

- Python 3.9+
- Node.js 16+
- PostgreSQL

### Backend Setup

1. Navigate to the backend directory:
   ```bash
   cd backend
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Set up environment variables:
   ```bash
   cp .env.example .env
   # Edit .env with your configuration
   ```

4. Run the development server:
   ```bash
   uvicorn main:app --reload
   ```

### Frontend Setup

1. Navigate to the frontend directory:
   ```bash
   cd frontend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Run the development server:
   ```bash
   npm run dev
   ```

## License

MIT