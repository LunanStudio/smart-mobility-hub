# Smart Mobility Hub

The **Smart Mobility Hub** is an enhanced version of the YOVOY app, designed to overcome its limitations, such as slow startup times, sluggish bus location updates, and unintuitive route selection. Our goal is to provide a faster, more reliable, and feature-rich transportation experience for users and administrators alike.

## Features

### For Users

- Add funds to your account
- Pay seamlessly with Apple Pay/Google Wallet
- Locate nearby buses in real-time
- Find the best routes to reach your destination
- See estimated arrival times for buses
- Track your ETA to your destination

### For Administrators

- Download usage statistics
- Monitor bus activity in real-time
- Manage payment inventory
- Report and track delays

## Tech Stack

We use cutting-edge technology to ensure a smooth and efficient experience:

- **Turborepo** \'96 Manages the monorepo structure for both frontend and backend.
- **Expo** \'96 A React Native tool for compiling iOS and Android apps.
- **NestJS** \'96 A scalable backend framework.
- **WebSockets** \'96 Enables real-time updates between the client and server.
- **Redis** \'96 Caches location data for faster retrieval.
- **PostgreSQL** \'96 Stores persistent data like routes and user information.

## Screenshots

<img src="https://i.imgur.com/dAsNUds.png" width="200" alt="Splash screen">\
<img src="https://i.imgur.com/lFIifhr.png" width="200" alt="Screenshot 1">\
<img src="https://i.imgur.com/IXIhXZF.png" width="200" alt="Screenshot 2">\
<img src="https://i.imgur.com/yQKa3Am.png" width="200" alt="Screenshot 3">\
<img src="https://i.imgur.com/XVPICYu.png" width="200" alt="Screenshot 4">\
<img src="https://i.imgur.com/O9Xxnow.png" width="200" alt="Screenshot 5">\
<img src="https://i.imgur.com/jFkoMM2.png" width="200" alt="Screenshot 6">\
<img src="https://i.imgur.com/kY3U3rZ.png" width="200" alt="Screenshot 7">\
<img src="https://i.imgur.com/lfPETWv.png" width="200" alt="Screenshot 8">\

## How to Contribute

We welcome contributions! Follow these steps to get started:

### Prerequisites

1. Install **pnpm**:  

   ```sh\
   npm install -g pnpm@latest-10
   ```

2. Install **Turborepo**:

   ```sh\
   npm install turbo --global
   ```

### Setup

1. Navigate to the root directory:

   ```sh\
   cd smart-mobility-hub
   ```

2. Install dependencies:

   ```sh\
   pnpm i
   ```

3. Start the project:

   ```sh
   turbo run dev
   ```

Enjoy coding!
