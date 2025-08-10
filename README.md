# WoofingJaceID NFT Minting Page

This repository contains a web-based interface for minting **WoofingJaceID** NFTs on the BNB Chain. The page allows users to connect their wallet, mint a unique NFT with a custom ID, and view their owned NFT with a preview of its SVG image. The interface is styled with a cyberpunk aesthetic, featuring a neon color scheme and the `VT323` font, inspired by the WoofingJace brand.

The minting page interacts with the **WoofingJaceID** smart contract deployed at `0xFC8E612a097E091CA8fbD5327ABf63E4E50C8005` on the BNB Chain (Chain ID: 56).

## Features

- **Wallet Connection**: Supports popular wallets like MetaMask, OKX Wallet, Trust Wallet, and more.
- **Network Validation**: Ensures users are connected to the BNB Chain, with automatic network switching or addition.
- **NFT Minting**: Allows users to mint a single NFT with a unique alphanumeric ID (e.g., `jace123`), enforcing contract rules (one NFT per address, no duplicate IDs).
- **Contract Information**: Displays contract details (name, symbol, suffix, total supply).
- **Owned NFT Display**: Shows the user's minted NFT (if any) with a "View" button to display its SVG image.
- **Responsive Design**: Optimized for both desktop and mobile devices.
- **Cyberpunk Aesthetic**: Neon colors (`#00ffcc` and `#ff007f`), glowing effects, and a futuristic layout.
- **User Feedback**: Playful "dog messages" guide users through the process (e.g., "Woof! NFT minted, pup!").

## Prerequisites

To use or develop this project, you need:
- A modern web browser (e.g., Chrome, Firefox).
- A compatible Ethereum wallet (e.g., MetaMask) installed and configured.
- Access to the BNB Chain network (Chain ID: 56).
- For development: A web server or static hosting service to serve the HTML file.

## Setup

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/woofingjaceid-minting-page.git
   cd woofingjaceid-minting-page
