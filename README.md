# SPOTPOS - Modern Point of Sale System

SPOTPOS is a comprehensive Point of Sale (POS) system designed for modern restaurants and retail businesses. It offers a complete solution for order management, inventory control, reporting, and more.

## Features

- 📊 Comprehensive Reporting System
- 📦 Smart Inventory Control
- 🛒 Seamless Order Management
- 🔄 Real-time Tracking
- 📝 Transaction History
- 🍽️ Table Service Operations
- 🖨️ Order Printing
- 🚚 Delivery and Pickup Management
- ☁️ Cloud Integration
- 📱 Offline Mode Support
- 🎨 Image-driven UI
- 👥 Employee Access Management

## Project Structure

```
spotpos/
├── packages/
│   ├── client/         # React frontend application
│   └── server/         # Node.js backend application
├── package.json        # Root package configuration
└── README.md           # Project documentation
```

## Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm (v9 or higher)
- PostgreSQL
- Redis

### Installation

1. Clone the repository:
```bash
git clone https://github.com/your-username/spotpos.git
cd spotpos
```

2. Install dependencies:
```bash
npm install
```

3. Set up environment variables:
```bash
cp packages/server/.env.example packages/server/.env
cp packages/client/.env.example packages/client/.env
```

4. Start the development servers:
```bash
npm start
```

## Development

- Frontend runs on: http://localhost:3000
- Backend runs on: http://localhost:5000

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct and the process for submitting pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details. 