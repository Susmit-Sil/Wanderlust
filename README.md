# WanderLust

WanderLust is a web application designed to simplify the process of finding and hosting unique accommodations around the world. With a user-friendly interface and robust features, it connects travelers with hosts offering a variety of stays, from cozy apartments to exotic getaways.

---

## Features

### For Guests:
- **Search Listings**: Discover stays by location, date, price, and other filters.
- **Interactive Map**: Visualize available accommodations on an interactive map.
- **Booking System**: Book stays seamlessly and manage your reservations.
- **Reviews and Ratings**: View feedback from previous guests to make informed decisions.

### For Hosts:
- **List Your Space**: Add detailed listings with photos, descriptions, and pricing.
- **Availability Management**: Set and update the availability of your property.
- **Guest Communication**: Chat with potential guests to answer queries.
- **Earnings Dashboard**: Track your income from bookings.

---

## Tech Stack

### Frontend:
- **React.js**: For building dynamic user interfaces.
- **Redux**: For state management.
- **Tailwind CSS**: For styling the application.

### Backend:
- **Node.js**: For server-side logic.
- **Express.js**: For handling API requests.
- **MongoDB**: As the database for storing user and booking information.

### Other Tools:
- **JWT**: For secure user authentication.
- **Stripe**: For payment processing.
- **Mapbox**: For rendering interactive maps.

---

## Setup and Installation

### Prerequisites:
- **Node.js** and **npm** installed on your system.
- **MongoDB** database set up locally or using a cloud provider.

### Steps:
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/WanderLust.git
   cd WanderLust
   ```

2. Install dependencies:
   ```bash
   npm install
   cd client && npm install
   ```

3. Set up environment variables:
   - Create a `.env` file in the root directory.
   - Add the following:
     ```env
     PORT=5000
     MONGO_URI=your_mongodb_connection_string
     JWT_SECRET=your_secret_key
     STRIPE_SECRET=your_stripe_secret_key
     MAPBOX_TOKEN=your_mapbox_access_token
     ```

4. Start the development servers:
   - Backend:
     ```bash
     npm run dev
     ```
   - Frontend:
     ```bash
     cd client && npm start
     ```

5. Access the application at `http://localhost:3000`.

---

## Contribution Guidelines

We welcome contributions to improve WanderLust! To contribute:
1. Fork the repository.
2. Create a new branch for your feature/fix:
   ```bash
   git checkout -b feature-name
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m "Description of changes"
   ```
4. Push your branch and submit a pull request.

---

## License

This project is licensed under the MIT License. 

---

## Acknowledgments

- Special thanks to all contributors who helped bring WanderLust to life.
- Inspired by platforms that connect travelers and hosts globally.
