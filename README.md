

# LULO.fi Application fork


From AI to Social, Launchpads to Wallets, and Trading — build solana mobile apps.


## Key Protocol Integrations

1. **Swaps:**  
   In-App trading via [Jupiter](https://jup.ag/) for the best prices across all DEXs, and native [Pump AMM](https://swap.pump.fun/)

2. **Launchpads:**  
   The three biggest Solana launchpads with configurable bonding curves – [Pump.fun](https://pump.fun/), [Raydium](https://raydium.io/launchpad/), and [Meteora](https://app.meteora.ag/) – along with [Token Mill](https://tokenmill.xyz/)

3. **Embedded Wallets:**  
   Top wallets like [Privy](https://www.privy.io/), [Turnkey](https://turnkey.com/), and [Dynamic](https://www.dynamic.xyz/), along with Mobile Wallet Adapter support by [Solana Mobile](https://solanamobile.com/) for external wallet connections.

4. **Token Data & Prices:**  
   Live prices and token info from [Coingecko](https://www.coingecko.com/), [Birdeye](https://birdeye.so/), and [Rugcheck](https://rugcheck.xyz/)

5. **NFTs:**  
   NFT minting via [Metaplex](https://www.metaplex.com/) and trading via [Tensor](https://www.tensor.trade/)

6. **AI Integration:**  
   [SendAI](https://sendai.fun/) for AI chat integration to take Solana actions

7. **On/Off-Ramps:**  
   Buy/sell crypto using cards or Apple Pay with [MoonPay](https://www.moonpay.com/) and [Mercuryo](https://mercuryo.io/) *(work in progress)*

8. **Miscellaneous Tools:**  
   [Jito Bundles](https://www.jito.network/) and [Helius](https://www.helius.dev/) for transaction landing

---

## 📱 App Features

| Feature                   | Description                                                                                                                                                                                                                                                                   |
| ------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 👛 **Wallet Integration** | • Multiple wallet connection methods<br>• Embedded wallet support via Privy, Dynamic, and Turnkey<br>• External wallet connections via Solana Mobile MWA<br>• Transaction signing and management<br>                                                                          |
| 👥 **Social Features**    | • User profiles and following system<br>• Social feed with posts and interactions<br>• Community engagement features<br>• NFT display and management<br>• IPFS storage for metadata                                                                                           |
| 🎨 **UI/UX**              | • Modern, responsive design<br>• Tab-based navigation<br>• Interactive charts and visualizations<br>• Elegant loading states and error handling<br>• Platform-specific optimizations                                                                                          |
| 🖥️ **Backend Features**   | • RESTful API for token operations<br>• Social data storage and retrieval<br>• Token market creation and management<br>• Token swapping via Jupiter and PumpSwap<br>• Token launching via different launchpads like Pump, Raydium, and Meteora <br>• Image upload and storage |

---

## 📦 Core Installation

```sh
npx start-solana-app
```

---

## 🛠️ Tech Stack

<div align="center">
  <table>
    <tr>
      <td align="center"><a href="https://reactnative.dev/" target="_blank" rel="noopener noreferrer"><img src="https://d33wubrfki0l68.cloudfront.net/554c3b0e09cf167f0281fda839a5433f2040b349/ecfc9/img/header_logo.svg" width="60" height="60" alt="React Native" /><br /><b>React Native</b></a></td>
      <td align="center"><a href="https://expo.dev/" target="_blank" rel="noopener noreferrer"><img src="https://www.vectorlogo.zone/logos/expoio/expoio-icon.svg" width="60" height="60" alt="Expo" /><br /><b>Expo</b></a></td>
      <td align="center"><a href="https://solana.com/docs/clients/javascript" target="_blank" rel="noopener noreferrer"><img src="https://cdn.jsdelivr.net/gh/trustwallet/assets@master/blockchains/solana/info/logo.png" width="60" height="60" alt="Solana Web3.js" /><br /><b>Solana Kit</b></a></td>
      <td align="center"><a href="https://www.typescriptlang.org/" target="_blank" rel="noopener noreferrer"><img src="https://cdn.worldvectorlogo.com/logos/typescript.svg" width="60" height="60" alt="TypeScript" /><br /><b>TypeScript</b></a></td>
      <td align="center"><a href="https://www.postgresql.org/" target="_blank" rel="noopener noreferrer"><img src="https://cdn.worldvectorlogo.com/logos/postgresql.svg" width="60" height="60" alt="PostgreSQL" /><br /><b>PostgreSQL</b></a></td>
    </tr>
  </table>
</div>

---

## ✅ Prerequisites

- Node.js >= 18
- pnpm or yarn or npm
- iOS: XCode and CocoaPods
- Android: Android Studio, Android SDK, and JDK
- [Expo CLI](https://docs.expo.dev/get-started/installation/)
- PostgreSQL database (for the server)
