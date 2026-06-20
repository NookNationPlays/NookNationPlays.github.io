<div align="center">

<img width="300" src="docs/nnp-logo.png#gh-dark-mode-only" alt="EmulatorJS Dark Mode Logo">
<img width="300" src="docs/nnp-logo.png#gh-light-mode-only" alt="EmulatorJS Light Mode Logo">

<br>

Self-hosted **JavaScript** emulation for various systems.

[![License: GPLv3][Badge License]][Link License]
[![Website][Badge Website]][Link Website]
[![Usage Docs][Badge Usage]][Link Usage]
[![Configurator][Badge Configurator]][Link Configurator]
[![Live Demo][Badge Demo]][Link Demo]
[![Contributors][Badge Contributors]][Link Contributors]

Join our Discord server:

[![Discord Badge](https://invidget.switchblade.xyz/6akryGkETU)](https://discord.gg/6akryGkETU)

</div>

---

## Getting Started

### Supported Systems
EmulatorJS+ supports a wide variety of legacy consoles and arcade machines including minigames like minecraft 1.8.8, cookie clicker, block blast, and TwiliRealm's Dusklight. For the complete list of supported cores, please visit our [Cores Documentation](https://emulatorjs.org/docs4devs/cores).

### Versioning Guide
We use a specific versioning system to help you choose the right build for your needs:

1.  **this one** - The only version available. This is the default version.

### CDN Integration
EmulatorJS+ provides a public CDN at `https://cdn.emulatorjs.org/`. You can access any other version by setting the data path and loader.js accordingly.

```javascript
// Example Configuration
const EJS_pathToData = 'https://cdn.emulatorjs.org/<version>/data/';
// Replace <version> with: stable, latest, nightly, etc.
```

### Development
To run EmulatorJS+ locally for development:

1.  Open a terminal in the root directory.
2.  Install dependencies:
    ```sh
    npm i
    ```
3.  Start the server/minification:
    ```sh
    npm run start
    ```
4.  Open `http://localhost:8080/` to view the demo.

> **Note:** Minify your script files before deploying to a production server to optimize load times and bandwidth. See [Minification Docs](minify/README.md).

---

## Community & Support

### 3rd Party Integrations
EmulatorJS+ is built as a fork to the library/plugin EmulatorJS, not a standalone website (therefore, no Docker container). For projects that utilize EmulatorJS+, check out the official [3rd Party Integration List](https://emulatorjs.org/docs/3rd-party).

### Issues & Reporting
If you encounter an issue, please open an [Issue](https://github.com/EmulatorJS/EmulatorJS/issues) on GitHub. Include as many details as possible, including your browser console logs. Same here with my version, If you encounter an issue with the UI or minigames, Please open an [Issue](https://github.com/NookNationPlays/NookNationPlays.github.io/issues) or email/DM me If I know You.

> **When reporting bugs, please specify the version you are using (OG/My Fork/Your Fork Of My Fork/Your Fork Of OG).**

### Support the Project
This project is free and ad-free. normally there could be ads on the normal version but like I say, I don't pay a dime for this site so IDK really loll.

---

## Star History

<a href="https://star-history.com/#EmulatorJS/EmulatorJS&Date">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=EmulatorJS/EmulatorJS&type=Date&theme=dark" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=EmulatorJS/EmulatorJS&type=Date" />
   <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=EmulatorJS/EmulatorJS&type=Date" />
 </picture>
</a>

<!-- Link Definitions -->
[Badge License]: https://img.shields.io/badge/License-GPLv3-blue.svg?style=for-the-badge&logo=opensourceinitiative
[Badge Website]: https://img.shields.io/badge/Website-736e9b?style=for-the-badge
[Badge Usage]: https://img.shields.io/badge/Usage-2478b5?style=for-the-badge
[Badge Configurator]: https://img.shields.io/badge/Config-992cb3?style=for-the-badge
[Badge Demo]: https://img.shields.io/badge/Demo-528116?style=for-the-badge
[Badge Contributors]: https://img.shields.io/badge/Contributors-54b7dd?style=for-the-badge
[Discord Badge]: https://invidget.switchblade.xyz/6akryGkETU

[Link License]: LICENSE
[Link Website]: https://youtube.com/@NookNation
[Link Usage]: https://youtube.com/@NookNation
[Link Configurator]: https://youtube.com/@NookNation
[Link Demo]: https://nooknationplays.github.io
[Link Contributors]: docs/contributors.md
[Link Issue]: https://github.com/NookNationPlays/nooknationplays.github.io/issues
