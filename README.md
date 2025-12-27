# Smileybase Donut Mini App

## Overview
Smileybase Donut Mini App is an interactive Next.js application that allows users to customize a digital donut image, overlay text, and explore wallet & transaction-oriented features. The app includes vibrant visuals, live previews, and playful interactions.

## Features
- **Donut Preview**: Animated donut background with real-time customization of overlay text and accessory colors.
- **Customization Panel**: Modify text displayed on the shirt and choose from a palette of accessory colors.
- **Download & Sharing**: Buttons for sharing the designs and downloading images locally.
- **Wallet Integration**: Displays mock balance data for assets like Donut, ETH Base, and USDC.
- **Transaction History**: Placeholder for transaction history tied to user wallets.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Skillabsc/SmileyBase-Builders-mini-app.git
   ```

2. Navigate to the project directory:
   ```bash
   cd SmileyBase-Builders-mini-app
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Start the development server:
   ```bash
   npm run dev
   ```

## Folder Structure
```
📦src
 ┣ 📂components
 ┃ ┗ 📜SmileybaseDonutApp.tsx (Main component.)
 ┣ 📂pages (Next.js routing pages.)
 ┣ 📂styles (Global and module-level CSS.)
```

## Next Steps

### For Modularization
Refactor the main `SmileybaseDonutApp` component into smaller reusable components for ease of maintenance. Suggested structure:
- **Background.tsx**: For animated donut backgrounds.
- **DonutPreview.tsx**: Handles preview card & dynamic overlay.
- **CustomizationPanel.tsx**: Includes outfit text input & accessories.
- **WalletOverview.tsx**: Renders wallet balances and mocks transaction history.

### Social Integration
Integrate with the Farcaster SDK to enable social sharing features.
- [Farcaster SDK Repository](https://github.com/farcasterxyz)

### To Implement Export/Download Functionality
Use libraries like `html2canvas` or `dom-to-image` to download the preview section as an image.

## Dependencies
- **react**, **next.js**: Core frontend libraries.
- **lucide-react**, **framer-motion**: Icon library and animations.
- **tailwindcss**: CSS framework.

## License
MIT License