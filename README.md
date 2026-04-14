👨‍👩‍👧‍👦 Parenting Advice Bot

![Python](https://img.shields.io/badge/Python-3.11+-3776ab?style=for-the-badge&logo=python)
![MIT License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
![Gemma 3](https://img.shields.io/badge/Gemma%203-FF6B6B?style=for-the-badge)
![Privacy-First](https://img.shields.io/badge/Privacy-First-blue?style=for-the-badge)
![Ollama](https://img.shields.io/badge/Ollama-Powered-FF6B6B?style=for-the-badge)

> **Supportive parenting guidance using Gemma 3 AI with privacy-first recommendations and developmental insights**

## Architecture

\\\
┌─────────────────────────────────────────────────┐
│         User Interface / Client Layer            │
├─────────────────────────────────────────────────┤
│                                                   │
│     FastAPI Server (REST API Endpoints)          │
│     ↓        ↓        ↓        ↓                 │
├─────────────────────────────────────────────────┤
│   Service Layer (Business Logic & Processing)   │
│   - Data Processing                             │
│   - Analytics Engine                            │
│   - Recommendation Engine                       │
├─────────────────────────────────────────────────┤
│   Gemma 3 LLM via Ollama (Local Processing)     │
│   - Privacy-First AI                            │
│   - On-Device Inference                         │
├─────────────────────────────────────────────────┤
│   Data Layer (Local/Encrypted Storage)          │
│   - SQLite / PostgreSQL                         │
│   - User Preferences                            │
│   - Historical Data                             │
└─────────────────────────────────────────────────┘
\\\

## ✨ Key Features

- Age-appropriate parenting advice
- Child development milestone tracking
- Behavioral challenge solutions
- Emotion management techniques
- Educational activity recommendations
- Safety and health guidelines
- Privacy-first conversation processing
- Personalized parenting strategies
- Multi-child management support
- Expert-backed behavioral insights


## 🚀 Quick Start

### Prerequisites

- Python 3.11 or higher
- Ollama installed and running ([Download Ollama](https://ollama.ai))
- Git

### Installation

1. Clone the repository:
\\\ash
git clone https://github.com/kennedyraju55/parenting-advice-bot.git
cd parenting-advice-bot
\\\

2. Create a virtual environment:
\\\ash
python -m venv venv
source venv/bin/activate  # On Windows: venv\\Scripts\\activate
\\\

3. Install dependencies:
\\\ash
pip install -r requirements.txt
\\\

### Running

1. Start Ollama:
\\\ash
ollama serve
\\\

2. In another terminal, run the application:
\\\ash
python -m src.main
\\\

3. Access the API at \http://localhost:8000\

## 🛠️ Tech Stack

| Component | Technology | Purpose |
|-----------|-----------|---------|
| **Language** | Python 3.11+ | Core development language |
| **API Framework** | FastAPI | High-performance REST API |
| **LLM** | Gemma 3 | Advanced AI capabilities |
| **LLM Runtime** | Ollama | Local, privacy-first inference |
| **Data Storage** | SQLite/PostgreSQL | Persistent data management |
| **Async** | AsyncIO | Non-blocking operations |
| **Validation** | Pydantic | Data validation & serialization |
| **Testing** | Pytest | Comprehensive test suite |

## 📂 Project Structure

\\\
parenting_bot/
├── src/
│   ├── advice_engine/
│   ├── tracking/
│   ├── recommendations/
│   └── api/
├── tests/
├── resources/
└── docs/
\\\

## 👨‍💻 Author

**Raju Guthikonda**

Connect with me:
- **GitHub**: [@kennedyraju55](https://github.com/kennedyraju55)
- **Dev.to**: [@kennedyraju55](https://dev.to/kennedyraju55)
- **LinkedIn**: [Raju Guthikonda](https://linkedin.com/in/nrk-raju-guthikonda-504066a8)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

---

**Built with ❤️ for privacy-first AI applications**