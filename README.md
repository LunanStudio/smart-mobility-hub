
# Smart Mobility Hub
The smart mobility hub is an improvement on the YOVOY app which addresses the slow start up time, slow bus location updates, and unintuitive route selection. This app also aims to add more features for users to benefit from such as:
- Add funds
- Pay with apple pay/google wallet
- Show near by busses
- Show the routes to take to reach a wanted destination
- Display estimated time of arrival for the bus
- Display estimated time of arrival to destination
and features on the administration side such as:
- Download statistics
- Bus monitoring
- Keep payment inventory
- Report delays

# Tech Stack
The tech stack used to create this application are the following:
- Turborepo: To create a monorepo to be able to run both frontend and backend
- Expo: A react-native tool used to compile to both ios and android
- NestJS: Backend framework
- WebSocket: A continuous and simultaneous communication between client and server for real-time updates
- Redis: Database used to cache location data
- PostgreSQL: Database that allows to store longer lasting data such as routes and user info

# Screenshots

# How to contribute
To start contributing to the project first it is necessary to install some tools
1. Install pnpm using `npm install -g pnpm@latest-10`
2. install Turborepo using `npm install turbo --global`

Thanks to Turborepo the set up is easy.
1. Make sure you're in the root directory "smart-mobility-hub"
2. Install the packages with `pnpm i`
3. Once the packages have installed run the project with `turbo run dev`