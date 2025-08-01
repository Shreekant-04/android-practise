# Android Practice Repository

This repository contains Android development practice projects and experiments. Currently, it includes a React Native Expo project for cross-platform mobile app development.

## Projects

### 📱 Hello World - React Native Expo App

A starter React Native application built with Expo, featuring:

- Modern React Native 0.79.5 with Expo SDK 53
- TypeScript support
- Tab-based navigation using React Navigation
- Cross-platform support (iOS, Android, Web)
- Themed components with light/dark mode support
- File-based routing with Expo Router

## Getting Started

### Prerequisites

- Node.js (latest LTS version)
- npm or yarn
- Expo CLI
- Android Studio (for Android development)
- Xcode (for iOS development, macOS only)

### Installation & Setup

1. **Clone the repository**

   ```bash
   git clone <repository-url>
   cd android-practise
   ```

2. **Navigate to the hello-world project**

   ```bash
   cd hello-world
   ```

3. **Install dependencies**

   ```bash
   npm install
   ```

4. **Start the development server**
   ```bash
   npx expo start
   ```

### Available Scripts

In the hello-world project directory, you can run:

- `npm start` - Start the Expo development server
- `npm run android` - Run on Android device/emulator
- `npm run ios` - Run on iOS device/simulator (macOS only)
- `npm run web` - Run in web browser
- `npm run lint` - Run ESLint for code quality
- `npm run reset-project` - Reset the project to initial state

## Project Structure

```
hello-world/
├── app/                    # App screens and navigation
│   ├── (tabs)/            # Tab-based screens
│   │   ├── index.tsx      # Home screen
│   │   └── explore.tsx    # Explore screen
│   ├── _layout.tsx        # Root layout
│   └── +not-found.tsx     # 404 screen
├── assets/                # Static assets
│   ├── fonts/            # Custom fonts
│   └── images/           # Images and icons
├── components/           # Reusable React components
│   └── ui/              # UI-specific components
├── constants/           # App constants and configuration
├── hooks/              # Custom React hooks
└── scripts/           # Build and utility scripts
```

## Features

- **Cross-Platform**: Run on iOS, Android, and Web
- **Modern Navigation**: Tab-based navigation with React Navigation
- **TypeScript**: Full TypeScript support for better development experience
- **Themed Components**: Built-in support for light and dark themes
- **Expo Router**: File-based routing system
- **Hot Reloading**: Fast development with hot reloading
- **Web Support**: Run your mobile app in the browser

## Development

### Running on Different Platforms

**Android:**

```bash
npm run android
```

**iOS (macOS only):**

```bash
npm run ios
```

**Web:**

```bash
npm run web
```

### Code Quality

This project uses ESLint for code quality. Run the linter with:

```bash
npm run lint
```

## Technologies Used

- **React Native** 0.79.5
- **Expo** SDK 53
- **TypeScript** 5.8.3
- **React Navigation** 7.x
- **Expo Router** 5.x
- **ESLint** for code quality

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/new-feature`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/new-feature`)
5. Create a Pull Request

## Resources

- [Expo Documentation](https://docs.expo.dev/)
- [React Native Documentation](https://reactnative.dev/)
- [React Navigation](https://reactnavigation.org/)
- [TypeScript](https://www.typescriptlang.org/)

## License

This project is for educational and practice purposes.
