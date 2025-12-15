# Food Rescue Hub

A platform designed to connect food donors with recipients to reduce food waste and combat hunger in local communities.

## Overview

Food Rescue Hub is a web application that facilitates the donation and distribution of surplus food from restaurants, grocery stores, events, and individuals to those in need. By bridging the gap between food donors and recipients, this platform helps reduce food waste while addressing food insecurity.

## Features

- **Food Donation Management**: Donors can list available food items with details like quantity, expiry date, and pickup location
- **Real-time Notifications**: Recipients receive instant alerts about available food donations in their area
- **User Profiles**: Separate profiles for donors (restaurants, stores, individuals) and recipients (NGOs, shelters, individuals)
- **Location-based Matching**: Smart matching algorithm connects donors with nearby recipients
- **Pickup Scheduling**: Coordinate convenient pickup times between donors and recipients
- **Impact Tracking**: Dashboard showing total food rescued, meals provided, and environmental impact

## Tech Stack

### Frontend
- Modern JavaScript framework for responsive UI
- Interactive maps for location-based features
- Real-time updates and notifications

### Backend
- RESTful API architecture
- Database for user management and donation tracking
- Authentication and authorization
- Geolocation services

## Project Structure

```
Food-Rescue-Hub/
├── Food-rescue-hub-frontend/    # Frontend application
├── Food-rescue-hub-backend-/    # Backend API and services
└── README.md                     # Project documentation
```

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn
- Database (MongoDB/PostgreSQL)

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd Food-Rescue-Hub
```

2. Install backend dependencies:
```bash
cd Food-rescue-hub-backend-
npm install
```

3. Install frontend dependencies:
```bash
cd ../Food-rescue-hub-frontend
npm install
```

4. Set up environment variables:
- Create `.env` files in both backend and frontend directories
- Configure database connections, API keys, and other credentials

5. Run the application:

Backend:
```bash
cd Food-rescue-hub-backend-
npm start
```

Frontend:
```bash
cd Food-rescue-hub-frontend
npm start
```

## Use Cases

### For Donors
- Restaurants with excess prepared food at closing time
- Grocery stores with near-expiry products
- Event organizers with leftover catered food
- Individuals with surplus home-cooked meals

### For Recipients
- Food banks and pantries
- Homeless shelters
- Community kitchens
- Low-income families

## Impact

Food Rescue Hub aims to:
- Reduce food waste going to landfills
- Provide nutritious meals to those facing food insecurity
- Lower greenhouse gas emissions from food decomposition
- Build stronger, more caring communities

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

For questions, suggestions, or collaboration opportunities, please open an issue or contact the project maintainers.

## Acknowledgments

- Built for hackathon to address food waste and food insecurity
- Inspired by the global movement to rescue surplus food
- Thanks to all contributors and supporters of this initiative

---

**Together, we can make a difference - one meal at a time.**
