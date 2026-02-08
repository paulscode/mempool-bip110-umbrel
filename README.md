# BIP-110 Umbrel Community App Store

A community app store for [Umbrel](https://umbrel.com) providing tools to visualize and monitor [BIP-110 (Reduced Data Temporary Softfork)](https://github.com/dathonohm/bips/blob/reduced-data/bip-0110.mediawiki) activation progress on the Bitcoin network.

## Apps

### Mempool BIP-110
A specialized fork of the [Mempool](https://mempool.space) block explorer with BIP-110 visualization:
- 🟢 **Miner signaling detection** — blocks from miners signaling BIP-110 support glow green/gold
- 🟠 **Violation highlighting** — transactions that would be invalid under BIP-110 rules glow neon orange
- 📊 **Full Mempool functionality** — all standard explorer features (mempool, blocks, transactions, mining dashboard)

## How to Install

1. Open your Umbrel dashboard
2. Go to **App Store** → **Community App Stores** (or Settings → App Stores)
3. Add this repository URL:
   ```
   https://github.com/paulscode/mempool-bip110-umbrel
   ```
4. The **BIP-110 Apps** store will appear — find **Mempool BIP-110** and click **Install**

## Requirements

- **Umbrel** (umbrelOS 1.x or later)
- **Bitcoin Node** — must be installed and fully synced on your Umbrel
- **Electrs** — recommended for best performance (Electrum server for Umbrel)

## Links

- [BIP-110 Specification](https://github.com/dathonohm/bips/blob/reduced-data/bip-0110.mediawiki)
- [Mempool BIP-110 Source](https://github.com/paulscode/mempool-bip110)
- [Issues & Support](https://github.com/paulscode/mempool-bip110-umbrel/issues)

## License

The Mempool BIP-110 fork is licensed under the GNU Affero General Public License v3.0.
