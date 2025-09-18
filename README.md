# 🎮 Mystic Mantle Quest

<div align="center">
  <img src="https://github.com/Miny320/Mystic-Mantle-Quest/assets/95926324/3a912970-f5fa-437b-83fa-cf8281e62597" alt="Mystic Mantle Quest Logo" width="200"/>
  
  **A Revolutionary Quest-Based Unity Game on Mantle Blockchain** 🌟
  
  [![Live Demo](https://img.shields.io/badge/Live%20Demo-Vercel-blue?style=for-the-badge&logo=vercel)](https://minymystic-mantle-quest.vercel.app)
  [![Unity](https://img.shields.io/badge/Unity-2022.3+-black?style=for-the-badge&logo=unity)](https://unity.com/)
  [![Mantle](https://img.shields.io/badge/Mantle-Blockchain-blue?style=for-the-badge)](https://mantle.xyz/)
  [![Thirdweb](https://img.shields.io/badge/Thirdweb-Web3-orange?style=for-the-badge&logo=ethereum)](https://thirdweb.com/)
</div>

---

## 🌟 Overview

**Mystic Mantle Quest** is an innovative 2D RPG game that seamlessly integrates blockchain technology with traditional gaming mechanics. Built on Unity and powered by the Mantle blockchain, this game offers players a unique opportunity to earn real cryptocurrency rewards while embarking on epic quests and collecting valuable NFT weapons.

### 🎯 Game Flow

<div align="center">
  <img src="https://github.com/Miny320/Mystic-Mantle-Quest/assets/95926324/1ec31c73-c86a-40fb-abeb-7212c579127e" alt="Game Flow Diagram" width="600"/>
</div>

---

## 🚀 Live Demo & Presentation

- **🌐 Live Game**: [minymystic-mantle-quest.vercel.app](https://minymystic-mantle-quest.vercel.app)
- **📊 Project Presentation**: [View Presentation](https://docs.google.com/presentation/d/1VsS5hMEE52MiOXsyNMQdlMrJm35sPjGIy4qMG5wmV9g/edit?usp=sharing)

---

## 💰 Blockchain Integration

### 🪙 MMQ COIN (ERC-20 Token)

Earn valuable ERC-20 tokens by completing quests and achieving milestones in the game.

**Contract Address**: [`0x0B844d398F3a19f41209006D1D735FF379d99BDD`](https://explorer.testnet.mantle.xyz/address/0x0B844d398F3a19f41209006D1D735FF379d99BDD)

- Complete quests to earn MMQ coins
- Trade and utilize tokens within the game ecosystem
- Transparent and secure transactions on Mantle blockchain

### ⚔️ Weapon NFTs (ERC-721)

Collect unique and powerful weapon NFTs that enhance your gameplay experience.

**Contract Address**: [`0x73c4b4E214270C340546517A13A20CB10F7f1438`](https://explorer.testnet.mantle.xyz/address/0x73c4b4E214270C340546517A13A20CB10F7f1438)

- Discover rare weapon NFTs
- Each NFT is a unique digital asset
- Trade and showcase your collection

### 🏪 MMQ Marketplace

A vibrant marketplace where players can buy, sell, and trade Weapon NFTs using MMQ coins.

**Contract Address**: [`0x424832c400e69230E3553Aed59e0eF9A605Ea195`](https://explorer.testnet.mantle.xyz/address/0x424832c400e69230E3553Aed59e0eF9A605Ea195)

- Buy and sell Weapon NFTs
- Dynamic in-game economy
- Connect with other players

---

## 🛠️ Technical Stack

### Core Technologies
- **🎮 Game Engine**: Unity 2022.3+ with Universal Render Pipeline (URP)
- **🌐 Web3 Integration**: Thirdweb SDK for Unity
- **⛓️ Blockchain**: Mantle Network (Layer 2)
- **🚀 Deployment**: Vercel for WebGL builds

### Key Features
- **Quest System**: Dynamic quest management with rewards
- **Inventory System**: Collectible items and weapons
- **NFT Integration**: ERC-721 and ERC-1155 support
- **Token Economics**: ERC-20 token rewards
- **Marketplace**: In-game trading system
- **Web3 Wallet**: MetaMask, Coinbase Wallet, WalletConnect support

### Project Structure
```
MysticMantleQuest/
├── Assets/
│   ├── Creator Kit - RPG/     # Core RPG game assets
│   │   ├── Scripts/          # Game logic and mechanics
│   │   ├── Art/              # Sprites, animations, tiles
│   │   ├── Audio/            # Sound effects and music
│   │   └── Prefabs/          # Game objects and UI
│   ├── Thirdweb/             # Web3 blockchain integration
│   │   ├── Scripts/          # Thirdweb SDK implementation
│   │   └── Demo/             # Demo scripts and examples
│   └── WebGLTemplates/       # Custom WebGL deployment templates
├── webglbuild/               # Unity WebGL build output
├── vercel.json              # Vercel deployment configuration
└── package.json             # Project metadata
```

---

## 🎮 Game Features

### Core Gameplay
- **🗺️ 2D RPG Adventure**: Explore immersive game worlds
- **⚔️ Quest System**: Complete challenging quests for rewards
- **🎒 Inventory Management**: Collect and manage items
- **💬 NPC Interactions**: Rich dialogue and conversation systems
- **🎵 Audio System**: Dynamic music and sound effects

### Blockchain Features
- **🔗 Wallet Integration**: Connect with popular Web3 wallets
- **💰 Token Rewards**: Earn MMQ coins for quest completion
- **🛡️ NFT Weapons**: Collect and trade unique weapon NFTs
- **🏪 Marketplace**: Buy/sell items with other players
- **📊 Transparent Economy**: All transactions recorded on blockchain

---

## 🚀 Getting Started

### Prerequisites
- Unity 2022.3 or later
- Web3 wallet (MetaMask, Coinbase Wallet, etc.)
- Mantle testnet tokens for gas fees

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Miny320/Mystic-Mantle-Quest.git
   ```

2. Open the project in Unity
3. Install required packages through Package Manager
4. Configure Thirdweb settings for Mantle network
5. Build for WebGL platform

### Deployment
The game is configured for automatic deployment to Vercel:
- Push changes to the `master` branch
- Vercel will automatically build and deploy the WebGL version
- Access the live game at the provided URL

---

## 🔧 Development

### Key Scripts
- **`Quest.cs`**: Quest management and reward system
- **`InventoryItem.cs`**: Item collection mechanics
- **`ThirdwebSDKDemos.cs`**: Web3 integration examples
- **`GameController.cs`**: Main game state management

### Web3 Integration
The game uses Thirdweb SDK for seamless blockchain integration:
- Wallet connection and authentication
- Smart contract interactions
- NFT minting and trading
- Token transfers and balances

---

## 🌐 Network Information

- **Network**: Mantle Testnet
- **Chain ID**: 5001
- **RPC URL**: https://rpc.testnet.mantle.xyz
- **Block Explorer**: https://explorer.testnet.mantle.xyz

---

## 📈 Roadmap

- [ ] **Phase 1**: Core game mechanics and quest system ✅
- [ ] **Phase 2**: Blockchain integration and token rewards ✅
- [ ] **Phase 3**: NFT marketplace and trading system ✅
- [ ] **Phase 4**: Enhanced graphics and animations
- [ ] **Phase 5**: Multiplayer features and guild system
- [ ] **Phase 6**: Mobile app development

---

## 🤝 Contributing

We welcome contributions from the community! Please feel free to:
- Report bugs and issues
- Suggest new features
- Submit pull requests
- Improve documentation

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

- **Unity Creator Kit - RPG**: Base game framework
- **Thirdweb**: Web3 SDK and infrastructure
- **Mantle Network**: Layer 2 blockchain platform
- **Vercel**: Deployment and hosting platform

---

## 📞 Contact & Support

- **GitHub Repository**: [Mystic-Mantle-Quest](https://github.com/Miny320/Mystic-Mantle-Quest)
- **Live Demo**: [minymystic-mantle-quest.vercel.app](https://minymystic-mantle-quest.vercel.app)
- **Presentation**: [Project Overview](https://docs.google.com/presentation/d/1VsS5hMEE52MiOXsyNMQdlMrJm35sPjGIy4qMG5wmV9g/edit?usp=sharing)

---

<div align="center">
  <p><strong>Ready to embark on your blockchain gaming adventure?</strong></p>
  <p>🎮 <a href="https://minymystic-mantle-quest.vercel.app">Play Now</a> | ⚔️ <a href="https://explorer.testnet.mantle.xyz/address/0x73c4b4E214270C340546517A13A20CB10F7f1438">View NFTs</a> | 💰 <a href="https://explorer.testnet.mantle.xyz/address/0x0B844d398F3a19f41209006D1D735FF379d99BDD">Check Tokens</a></p>
</div>
