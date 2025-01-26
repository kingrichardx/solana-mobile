# Expo Solana Wallet

A mobile cryptocurrency wallet application built with Expo for interacting with the Solana blockchain. This wallet allows users to create accounts, send and receive SOL and SPL tokens, view transaction history, and manage their digital assets securely.

## Features

- **Secure Wallet Creation**: Generate and manage Solana wallet accounts with mnemonic seed phrases
- **Balance Management**: View SOL and SPL token balances in real-time
- **Token Transfers**: Send and receive SOL and SPL tokens
- **Transaction History**: View detailed transaction history for your accounts
- **QR Code Integration**: Scan QR codes for easy address input
- **PIN Protection**: Secure your wallet with a PIN code
- **Backup & Recovery**: Securely backup and restore your wallet using seed phrases
- **Multi-Account Support**: Manage multiple accounts within a single wallet
- **Real-time Price Tracking**: View current SOL to USD conversion rates

## Technologies Used

- [Expo](https://expo.dev/) - Universal React Native development platform
- [Solana Web3.js](https://solana-labs.github.io/solana-web3.js/) - JavaScript API for Solana blockchain
- [React Native Paper](https://callstack.github.io/react-native-paper/) - Material Design components
- [Easy Peasy](https://easy-peasy.dev/) - State management solution
- [React Navigation](https://reactnavigation.org/) - Routing and navigation

## Prerequisites

Before you begin, ensure you have the following installed:

- [Node.js](https://nodejs.org/) (v14 or higher)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)
- [Expo CLI](https://docs.expo.dev/workflow/expo-cli/)
- [Git](https://git-scm.com/)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/kingrichardx/expo-solana-wallet.git
   ```

2. Navigate to the project directory:

   ```bash
   cd expo-solana-wallet
   ```

3. Install dependencies:

   ```bash
   npm install
   # or
   yarn install
   ```

4. Start the development server:
   ```bash
   expo start
   ```

## Usage

After starting the development server, you can:

- Press `a` to run on Android emulator/device
- Press `i` to run on iOS simulator
- Press `w` to run on web browser

### Creating a Wallet

1. Launch the application
2. Follow the onboarding process
3. Set a secure PIN code
4. Generate a new wallet or restore from existing seed phrase

### Sending Tokens

1. Navigate to the Dashboard
2. Tap the "Send" button
3. Enter the recipient's address or scan their QR code
4. Specify the amount of SOL or tokens to send
5. Confirm the transaction with your PIN

### Receiving Tokens

1. Navigate to the Dashboard
2. Tap the "Receive" button
3. Share your QR code or wallet address with the sender

## Project Structure

```
expo-solana-wallet/
├── api/                 # Solana blockchain integration
├── components/          # Reusable UI components
├── constants/           # Application constants
├── core/                # Core theme and configuration
├── hooks/               # Custom React hooks
├── navigation/          # App navigation setup
├── onboarding/          # Onboarding screens
├── screens/             # Application screens
├── store/               # State management (Easy Peasy)
├── utils/               # Utility functions
├── App.tsx             # Main application component
├── app.json            # Expo configuration
└── package.json        # Project dependencies
```

## Available Scripts

- `npm start` - Start the Expo development server
- `npm run android` - Run on Android
- `npm run ios` - Run on iOS
- `npm run web` - Run on Web
- `npm test` - Run tests

## Environment Variables

This project uses the Solana devnet by default. For production use, you may need to configure:

- `SOLANA_CLUSTER` - Solana cluster endpoint (devnet, testnet, mainnet-beta)

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

**Richard Ellis**

- GitHub: [@kingrichardx](https://github.com/kingrichardx)
- Email: richardellis0012@gmail.com

## Acknowledgments

- Thanks to the Solana community for their excellent documentation and tools
- Inspired by various open-source wallet implementations
- Built with ❤️ using Expo and React Native

## Disclaimer

This wallet is provided as-is for educational and demonstration purposes. Use at your own risk. Always test thoroughly before using with real funds. The developers are not responsible for any loss of funds or other damages that may occur from using this software.
