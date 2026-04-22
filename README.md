# My VPS Journey

Catatan belajar mengelola VPS untuk menjalankan node airdrop.

## 🚀 Current Focus (Early Stage Projects)



- **Target Nodes:** Umi Network (MoveVM), Nava Labs, & Icarus Finance.
- **Infrastructure:** Contabo VPS (4 vCPU / 8GB RAM / Ubuntu 24.04).
- **Security Goal:** SSH Key authentication, UFW configuration, & Wallet  Isolation.

- **Infrastructure:** Preparing Contabo VPS (4 vCPU / 8GB RAM).
- **Security Goal:** SSH Key authentication & UFW configuration.

## 📅 Activity Log

### 17 April 2026 - Setup & Initial Running
•Server Preparation: Melakukan update sistem (apt update) dan instalasi alat   pendukung (wget, curl, screen).

•Binary Installation: Berhasil mengunduh binary node DAC versi Linux AMD64 dari    repositori resmi.

•Account Creation: * Membuat wallet baru di dalam direktori node.
•Berhasil mengamankan Public Address: 0x0805930f9cde3140c330c7bb8e9e696955df7f73.
 Security & Backup:
•Berhasil melakukan backup Keystore File (format JSON) secara manual.
•Mencatat password enkripsi wallet secara luring (offline).
•Node Execution: * Menjalankan node menggunakan perintah ./dacnode --testnet di •dalam sesi screen agar tetap berjalan 24/7 di background.
 Status saat ini: Sedang mengunduh header blok (Imported new chain segment).

### April 16, 2026 - Umi Network Deployment Success
- [x] Installed Aptos CLI v9.1.0 on Ubuntu 24.04.
- [x] Created dedicated node wallet: 0x548aba46...
- [x] Successfully compiled and published 'my_first_contract' to Umi Devnet.
- [x] Transaction Hash: 0x8eb119e3a28826101cbd7f8fbf935a37c1fc6c5d17d2aba318e9f89e6387?network=devnet

### April 16, 2026 - Initial Server Setup
[x] Login Success: Accessed Contabo VPS via Termius.
[x] System Maintenance: Performed apt update & upgrade.
[x] Environment: Installed basic tools (screen, git, curl).
[ ] Next: Configuring Umi Network Node components.
### April 16, 2026 - VPS Procurement Update
- [x] Selected VPS Specs: 4 vCPU, 8 GB RAM, 75 GB NVMe (Optimized for node speed).
- [!] Issue: Encountered "a.trim is not a function" system error on Contabo during Bank Jago payment integration.
- [ ] Action Plan: Switch to PayPal as a payment gateway to bypass direct card processing errors.

### April 15, 2026 - Umi Network Research (AI Layer 2)
- ✅ Analyzed Umi Network docs: A MoveVM-based Layer 2 focused on AI agent payments.
- ✅ Configured Rabby Wallet for **Umi Devnet** (Chain ID: 42069).
- ✅ Exploring the "Umi Stack" for future node operator opportunities.
- *Status:* Participating in Devnet phase; monitoring for public node/testnet announcement.

### April 15, 2026 - Nava Labs Technical Deep Dive
- ✅ Followed **navalabs-dev** organization and starred active repositories (SDK & Take-home tests).
- ✅ Analyzed Nava's product stack: Understanding the **Arbiter Verification** layer and **Execution Escrow SDK**.
- ✅ Monitoring for the release of "Nava Chain" network layer and decentralized Arbiter node specs.
### April 15, 2026 - Icarus Finance Engagement
- Completed on-chain tasks: Swapping tokens and understanding the Locking & Voting mechanism.
- Obtained veIRS NFT via locking to participate in governance.
- *Status:* High-level user interaction completed; waiting for Node/Validator technical release.
### April 15, 2026 - Icarus Finance Testnet Activity
- ✅ Applied for Founding Ascenders program.
- ✅ Executed on-chain interactions: Swaps and Liquidity Provision on Icarus Testnet.
- [ ] Monitoring for Node/Validator technical documentation
### April 15, 2026 - Early Access Scouting
- ✅ **Nava Labs:** Successfully joined the waitlist for the Autonomous Agents infrastructure. Monitoring for "Agent Node" requirements. (Backers: Polychain, Polychain Capital, Hack VC).
- ✅ **Icarus Finance:** Application complete for early access. Linked wallet address and monitoring for the "Founding Ascenders" program.

### April 10, 2026 - Strategy Pivot
- Decided to pivot from Nubit/Titan due to late-stage cycle. 
- Researching **Mina Protocol** and **Tempo Network** as early-stage opportunities.
- Finalizing payment gateway troubleshooting (Bank Jago/PayPal).

---

## 🔬 Research & Observation (Archived)
*Bagian ini berisi proyek yang dipantau namun tidak menjadi prioritas utama saat ini.*

- **Nubit (Light Node):** Late-stage incentivized testnet. Resource observed.
- **Titan Network:** DePIN sharing node. Monitoring for future seasons.

---

## 🛠 Perintah Penting:
- `sudo apt update`: Memperbarui daftar paket.
- `screen -S node`: Membuat sesi terminal baru agar node tetap jalan.
- `df -h`: Mengecek sisa penyimpanan disk.

---

"Hi there! I am a tech enthusiast from Indonesia. Currently focused on: 🖥️ Learning Linux VPS Management. 🌐 Exploring Early-Stage Decentralized Networks. 🛠️ Documenting node deployment journey."
