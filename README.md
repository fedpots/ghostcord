# Ghostcord

<p align="center">
  <img src="[./browser/icon.png](https://i.ibb.co/WvnxFCvz/Chat-GPT-Image-19-fe-vr-2026-18-48-52-removebg-preview.png)" width="100" alt="Ghostcord Logo">
</p>

**Ghostcord** is an optimized fork of [Vencord](https://github.com/Vendicated/Vencord), focused on performance, stability, and new feature enhancements.

Built on top of Vencord’s powerful foundation, Ghostcord delivers a cleaner, faster, and more customizable Discord experience.

---

## ✨ About Ghostcord

Ghostcord is:

* ⚡ Optimized for performance
* 🧩 Packed with enhanced and additional plugins
* 🛠 Built on Vencord’s open-source framework
* 🔒 Focused on stability and maintainability

Ghostcord is **not affiliated with Discord Inc.**
Ghostcord is a modified fork of Vencord — full credit goes to the original Vencord developers for their foundational work.

---

## 🚀 Features

* Optimized build configuration
* Performance improvements
* Additional quality-of-life plugins
* Enhanced plugin customization
* Cleaned and refined UI elements
* Ongoing feature updates

A full list of included plugins can be found in the repository’s `/plugins` directory.

---

## 📦 Installation

### Windows

* GUI Installer *Coming Soon*
* CLI Installer *Coming Soon*

### macOS

* GUI Installer *Coming Soon*

### Linux

* GUI Installer *Coming Soon*
* CLI Installer *Coming Soon*

---

## 🛠 Building Ghostcord (Development)

### Requirements

* [Git](https://git-scm.com/download)
* [Node.js LTS](https://nodejs.org/)
* `pnpm`

Install pnpm:

```bash
npm i -g pnpm
```

⚠️ After installing pnpm, close and reopen your terminal if needed.

⚠️ Do NOT run the following steps as administrator/root. Doing so may break your Discord installation.

---

### Clone the Repository

```bash
git clone https://github.com/fedpots/ghostcord.git
cd ghostcord
```

### Install Dependencies

```bash
pnpm install --frozen-lockfile
```

### Build Ghostcord

```bash
pnpm build
```

### Inject into Discord Desktop

```bash
pnpm inject
```

---

### 🌐 Build for Web

```bash
pnpm buildWeb
```

After building, locate the generated `.zip` file inside the `dist` directory and load it as an unpacked extension in your browser (Developer Mode required).

Note: Firefox requires Firefox Developer Edition for unsigned extensions.

---

## ⚠️ Disclaimer

Discord is a trademark of Discord Inc.
Ghostcord is not affiliated with, endorsed by, or connected to Discord Inc.

Ghostcord is a modified client framework based on Vencord.

Using third-party client modifications may violate Discord’s Terms of Service.
By using Ghostcord, you acknowledge and accept any potential risks associated with client modifications.

If your Discord account is critical or irreplaceable, you should carefully consider whether using client modifications is appropriate for you.

---

## ❤️ Credits

Massive thanks to:

* [Vendicated](https://github.com/Vendicated) — Creator of **Vencord**
* The Vencord contributors — for the original framework and ecosystem
* The open-source community

Ghostcord would not exist without Vencord’s foundation.

---

## 📜 License

Ghostcord follows the same license as Vencord unless otherwise specified.
Please review the LICENSE file for details.


