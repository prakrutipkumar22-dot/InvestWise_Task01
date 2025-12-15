# 💰 InvestWise

**Investment Education Platform for Gen Z (Ages 21-30)**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.9+](https://img.shields.io/badge/python-3.9+-blue.svg)](https://www.python.org/downloads/)
[![Status: In Development](https://img.shields.io/badge/status-in%20development-orange.svg)]()

---

## 🎯 Project Overview

InvestWise is an educational investment platform designed to help young adults (ages 21-30) learn about investing, understand risk management, and build confidence in financial decision-making—all without risking real money.

**Project Timeline**: December 2025 - April 2026  
**Status**: Phase 1 - Foundation & Core Features

### Key Features

- 🤖 **AI Investment Tutor**: LLM-powered chatbot that explains investing concepts in plain Gen Z language
- 📊 **Portfolio Simulator**: Test investment strategies with historical data
- 🎯 **Risk Assessment**: Interactive quiz to determine personal risk tolerance
- 💵 **Budget Planner**: Calculate realistic investment amounts based on income
- 📈 **Stock Screener**: Filter stocks with beginner-friendly criteria (Coming Soon)
- 📰 **Market Insights**: Educational market analysis and trends (Coming Soon)

---

## 🚨 Important Legal Disclaimer

**InvestWise is an educational tool only and does NOT provide financial advice.**

- ❌ We do not recommend specific stocks to buy or sell
- ❌ We do not guarantee investment returns
- ❌ We are not licensed financial advisors
- ✅ We provide educational information about investing principles
- ✅ We encourage users to do their own research
- ✅ We recommend consulting licensed financial advisors before investing

**Past performance does not guarantee future results.**

---

## 📸 Screenshots

### Home Dashboard
![InvestWise Dashboard](docs/images/dashboard.png)

### AI Investment Tutor
![AI Tutor Chat](docs/images/ai-tutor.png)

### Portfolio Simulator
![Portfolio Simulator](docs/images/simulator.png)

---

## 🛠️ Technology Stack

### Backend
- **Python 3.9+**: Core programming language
- **yfinance**: Stock market data (historical)
- **Alpha Vantage API**: Real-time stock quotes
- **Flask/FastAPI**: REST API backend
- **Anthropic Claude API**: LLM integration for AI tutor

### Frontend
- **React 18+**: UI framework
- **Tailwind CSS**: Styling
- **Recharts/Plotly**: Data visualization
- **Vite**: Build tool

### Data & Analysis
- **Pandas**: Data manipulation
- **NumPy**: Numerical computations
- **SciPy**: Statistical analysis

### Infrastructure
- **Git/GitHub**: Version control
- **pytest**: Testing framework
- **Docker**: Containerization (optional)

---

## 🚀 Quick Start

### Prerequisites

- Python 3.9 or higher
- Node.js 18+ and npm
- Git

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/investwise.git
cd investwise
```

2. **Set up Python environment**
```bash
# Create virtual environment
python -m venv venv

# Activate virtual environment
# Mac/Linux:
source venv/bin/activate
# Windows:
venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

3. **Configure environment variables**
```bash
# Copy example environment file
cp .env.example .env

# Edit .env and add your API keys:
# ALPHA_VANTAGE_API_KEY=your_key_here
# ANTHROPIC_API_KEY=your_key_here
```

4. **Set up frontend**
```bash
cd frontend
npm install
```

5. **Run the application**

Backend:
```bash
# From project root
python -m src.app
# Or use Flask:
flask run
```

Frontend:
```bash
# From frontend directory
npm run dev
```

Visit `http://localhost:5173` to see the application!

---

## 📚 Documentation

- **[Technical Documentation](TECHNICAL.md)**: Architecture, code organization, and developer guide
- **[Methodology](METHODOLOGY.md)**: Data analysis approach, LLM integration, and validation
- **[API Documentation](docs/api_documentation.md)**: REST API endpoints and usage
- **[User Guide](docs/user_guide.md)**: How to use InvestWise features

---

## 🗂️ Project Structure

```
investwise/
├── src/                    # Python source code
│   ├── data/              # Data fetching modules
│   ├── analysis/          # Portfolio analysis
│   ├── llm/               # AI tutor integration
│   └── utils/             # Helper functions
├── frontend/              # React application
│   └── src/
│       ├── components/    # React components
│       └── pages/         # Page components
├── notebooks/             # Jupyter analysis notebooks
├── tests/                 # Test suite
├── data/                  # Data storage (gitignored)
└── docs/                  # Documentation
```

---

## 🧪 Testing

Run the test suite:

```bash
# Run all tests
pytest

# Run with coverage
pytest --cov=src tests/

# Run specific test file
pytest tests/test_data/test_stock_fetcher.py
```

---

## 📊 Data Sources

### Primary Data Sources
- **yfinance**: Historical stock prices, company info, financial statements
- **Alpha Vantage**: Real-time quotes, technical indicators
- **S&P 500 Historical Data**: Market benchmarks

### Data Update Frequency
- Historical data: Cached, updated weekly
- Real-time quotes: Fetched on demand (rate-limited)
- Company fundamentals: Updated daily

### Data Privacy
- All data is publicly available market data
- No personal financial information is collected or stored
- User interactions are session-based (no persistent storage currently)

---

## 🤝 Contributing

This is currently a solo educational project, but feedback and suggestions are welcome!

### Reporting Issues
If you find bugs or have suggestions:
1. Check existing [Issues](https://github.com/yourusername/investwise/issues)
2. Create a new issue with detailed description
3. Include screenshots if relevant

---

## 📈 Roadmap

### Phase 1: Foundation (December 2025) ✅
- [x] Project structure setup
- [x] Basic prototype with core features
- [x] Documentation framework

### Phase 2: Data Integration (January 2026) 🔄
- [ ] Real stock data pipeline (yfinance)
- [ ] API caching layer
- [ ] Historical performance analysis
- [ ] Enhanced portfolio simulator

### Phase 3: Advanced Features (February 2026)
- [ ] Stock screener with filters
- [ ] Diversification analyzer
- [ ] Market sentiment analysis
- [ ] Educational content library

### Phase 4: Polish & Testing (March 2026)
- [ ] User accounts (optional)
- [ ] Comprehensive testing
- [ ] Performance optimization
- [ ] Mobile responsiveness

### Phase 5: Deployment (April 2026)
- [ ] Production deployment
- [ ] User testing
- [ ] Final documentation
- [ ] Project presentation

---

## 🎓 Educational Goals

This project demonstrates:

1. **Full-Stack Development**: Backend API + Frontend application
2. **Data Science**: Stock market analysis, statistical modeling
3. **LLM Integration**: Responsible AI chatbot with validation
4. **Financial Literacy**: Making complex topics accessible
5. **Best Practices**: Testing, documentation, code quality
6. **Real-World APIs**: Working with financial data sources

---


## 🙏 Acknowledgments

- **Syracuse University OPT Research Program**: Project framework and guidance
- **yfinance**: Excellent open-source financial data library
- **Anthropic**: Claude API for educational AI features
- **Alpha Vantage**: Free stock market data API

---



**Built with 💚 for financial literacy and education**

*Remember: Investing carries risk. Always do your own research and never invest more than you can afford to lose.*
