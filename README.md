# AgroClimate AI 🌾🌡️

Climate-Smart Agriculture Platform using NASA-IBM Weather Model for Precision Farming

## Overview

AgroClimate AI is an innovative platform that leverages NASA and IBM's weather prediction model to help farmers make informed decisions about their agricultural practices. By combining real-time climate data with advanced machine learning models, we provide actionable insights for sustainable and efficient farming.

## Project Structure

```
agroclimate-ai/
├── src/                    # Source code
│   ├── frontend/          # Frontend application (Next.js)
│   ├── backend/           # Backend API services (FastAPI)
│   ├── ml_model/          # Machine learning models
│   └── data_pipeline/     # Data processing pipelines
├── docs/                  # Documentation
├── tests/                 # Test suites
├── scripts/              # Utility scripts
└── config/               # Configuration files
```

## Features

- 🛰️ NASA-IBM Weather Model Integration
- 📊 Real-time Climate Data Analysis
- 🤖 Machine Learning-based Predictions
- 🌱 Crop Recommendation System
- ⚡ Real-time Alerts and Notifications
- 📱 Farmer-friendly Dashboard
- 📈 Historical Data Analysis
- 🎯 Precision Agriculture Support

## Getting Started

### Prerequisites

- Python 3.8+
- Node.js 16+
- Docker (optional)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Roxonn-FutureTech/agroclimate-ai.git
   cd agroclimate-ai
   ```

2. Install dependencies:
   ```bash
   # Backend dependencies
   cd src/backend
   pip install -r requirements.txt

   # Frontend dependencies
   cd ../frontend
   npm install
   ```

3. Set up environment variables:
   ```bash
   cp config/.env.example config/.env
   ```

4. Start the development servers:
   ```bash
   # Backend
   cd src/backend
   uvicorn main:app --reload

   # Frontend
   cd ../frontend
   npm run dev
   ```

## Contributing

We welcome contributions! Please see our [Contributing Guide](docs/CONTRIBUTING.md) for details.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

- Website: [roxonn.com](https://roxonn.com)
- GitHub: [@Roxonn-FutureTech](https://github.com/Roxonn-FutureTech) 
