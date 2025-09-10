# Qubic LiteNode for UmbrelOS Store

Qubic LiteNode integrates into UmbrelOS as a community app.  
It provides a lightweight node that synchronizes transactions and data from the Qubic network via Tor and comes with a Blazor-based dashboard.

## 🚀 Features
- Synchronizes transactions and balances from the Qubic network
- Dashboard to monitor your node
- Integration with Umbrel's Tor service
- Persistent data storage

## 📦 Installation
1. Add this repository as a custom app store in your UmbrelOS settings.
2. Search for **Qubic LiteNode** in the Umbrel App Store.
3. Install and open the app.

## 🛠️ Development
This app consists of two services:
- **Core**: Synchronizes Qubic network data
- **UI**: Blazor-based web dashboard

Both services are defined in `umbrel-app.yml` and use Docker images from DockerHub.

## 🧾 License
As we use some parts from the 451 Package in our Wallet, the Anti-Military License also applies.  
See [451 License](https://github.com/computor-tools/qubic-crypto).  

Further, our Wallet Code is protected by the **AGPL-3.0 License**.  
You may use our source code for your business as long as you comply with the license terms.
