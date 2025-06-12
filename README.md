# HardEco

**HardEco** is a lightweight Fabric mod for **Minecraft 1.21.5** that adds a simple, hardcore-friendly economy system to singleplayer or private worlds. Players start with **$0** and can earn money through activities like mining valuable ores. The mod tracks player balances via a local JSON file and adds basic economy commands.

---

## 📦 Features

- 💰 Players start with **$0**
- ⛏️ Earn money by mining valuable ores (configurable payout rates)
- 📊 `/balance` command to check your current money
- 💾 Balance stored in a simple JSON file under `config/`
- 📈 Fully local — no server required, perfect for hardcore worlds or singleplayer hosted on platforms like E4MC

---

## 📜 Planned Features

- `/pay <player> <amount>` command
- Economy item (custom coin or note)
- Shop/trading system via custom GUI or block
- Configurable payout values via JSON or config file
- Server version (multiworld economy)

---

## 🖥️ Server Version (COMING SOON)

A multiplayer-compatible version of **HardEco** is in development and will allow for:
- Server-wide economy balances
- Persistent money system with server-side storage
- New admin commands to manage player balances
- Integration with other server-side mods and shops

Planned for a future release after the singleplayer edition is complete.

---

## 🛠️ Development Info

**Target Minecraft Version:** `1.21.5`  
**Mod Loader:** [Fabric Loader](https://fabricmc.net/) `0.16.10+`  
**Fabric API Version:** `0.126.0+1.21.5`  
**Build System:** Gradle `8.12` with Loom `1.10`  

---

## 💻 Development Workflow (GitHub Codespaces)

1. Open this project in **GitHub Codespaces**  
2. Run `./gradlew build` to build the mod  
3. Copy the resulting `.jar` from `build/libs/` to your laptop's `.minecraft/mods/` folder  
4. Launch Minecraft 1.21.5 with Fabric Loader  
5. Enjoy your hardcore economy world!

---

## 📖 License and Contributions

- Player balances are stored in a publicly viewable `balances.json` file.  
- **Do not submit pull requests modifying `balances.json`. Such PRs will be rejected immediately.**  
- Changes to player balances must be made via in-game actions or approved mod updates.  
- Contributions to the mod’s codebase and features are welcome via GitHub Pull Requests and will be reviewed for inclusion.

See the full license in the [LICENSE](LICENSE) file.

---

**Made by Jake (stetupdev)** 🚀
