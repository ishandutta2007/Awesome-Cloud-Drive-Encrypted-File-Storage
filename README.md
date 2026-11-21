# Awesome-Cloud-Drive-Encrypted-File-Storage

## Top Cloud Drive & Encrypted File Storage Ecosystem



**Curated List of SaaS/Hosted Platforms & Open-Source GitHub Projects**  

*Focused on Self-Hosted Cloud Drives, Zero-Knowledge End-to-End Encrypted Storage, Client-Side File Encryption & P2P File Sync*  

**Last updated: November 2026**



This repository tracks notable **SaaS/hosted platforms** and **open-source projects** for **Cloud Drive & Encrypted File Storage**. These tools store, synchronize, encrypt, mount, share, and back up files across desktop, mobile, and web platforms using zero-knowledge end-to-end encryption (E2EE), self-hosted cloud storage servers, client-side cryptographic vaults, and peer-to-peer sync protocols.



**Examples** include Google Drive, Microsoft OneDrive, Dropbox, Box, pCloud, MEGA, Sync.com, Icedrive, Proton Drive, Tresorit, and zenhosta/9drive (the category leaders and notable community entries). 



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosted cloud drives (`Nextcloud`, `ownCloud Infinite Scale`, `Seafile`, `zenhosta/9drive`), client-side zero-knowledge encryption tools (`Cryptomator`, `rclone`, `gocryptfs`), and decentralized/P2P sync engines (`Syncthing`, `Peergos`) — ideal for privacy-conscious users, sysadmins, homelab operators, and organizations seeking full data sovereignty.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Support & Share](#support--share)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global cloud storage and file synchronization market is valued at approximately **$150B–$190B** (projected to surpass $500B by the early 2030s at an ~18–23% CAGR driven by data growth and AI workloads). The sector is **moderately concentrated** at the top—where hyperscale tech giants (Google, Microsoft, AWS) capture over 60% of mainstream workspace storage—while maintaining a highly fragmented landscape of specialized challengers competing aggressively on zero-knowledge encryption, sovereignty compliance, and predictable egress-free pricing.

## SaaS/Hosted Platforms

| Platform | Company Size (Revenue / Valuation) | Pricing (Starting Tier) | Free Tier Limits | Description |
| :--- | :--- | :--- | :--- | :--- |
| **[Microsoft OneDrive](https://microsoft.com)** | Valuation: ~$3.1T+ / Rev: ~$245B+ (Microsoft) | $1.99/mo ($19.99/yr) for Microsoft 365 Basic (100 GB) | 5 GB permanent free storage across OneDrive (with 15 GB Outlook mailbox) | Deeply integrated Windows and Microsoft 365 cloud file synchronization service featuring Personal Vault 2FA-protected storage and ransomware recovery. |
| **[Google Drive (Google One)](https://google.com)** | Valuation: ~$2.1T+ / Rev: ~$350B+ (Alphabet) | $1.99/mo ($19.99/yr) for Basic plan (100 GB) | 15 GB permanent free shared storage across Google Drive, Gmail, and Google Photos | Ubiquitous cloud file storage, real-time document collaboration, and AI-indexed workspace platform with optional Client-Side Encryption (CSE) for enterprise tiers. |
| **[Dropbox](https://dropbox.com)** | Valuation: ~$7.2B Market Cap / Rev: ~$2.52B | $9.99/mo (billed annually at $119.88/yr) or $11.99/mo for Plus (2 TB) | 2 GB permanent free storage with 3 connected device limit and 30-day version history | Cross-platform cloud file sync, block-level delta transfer, and team content collaboration platform with smart workspace organization. |
| **[Box](https://box.com)** | Valuation: ~$4.8B Market Cap / Rev: ~$1.09B | $10.00/mo (billed annually) or $14.00/mo for Personal Pro (100 GB) | 10 GB permanent free storage (with 250 MB single-file upload limit) | Enterprise cloud content management and workflow platform offering granular governance, e-signatures, and customer-managed encryption keys (Box KeySafe). |
| **[Proton Drive](https://proton.me)** | Valuation: Non-profit Proton Foundation (Unsold / Rev: ~$97M ARR) | $3.99/mo (billed annually at $47.88/yr) or $4.99/mo for Drive Plus (200 GB) | 5 GB permanent free storage (starts at 2 GB, unlock up to 5 GB via onboarding checklist) | Swiss-based, open-source-client end-to-end encrypted cloud storage and collaborative document platform backed by strict Swiss privacy laws and zero-access cryptography. |
| **[MEGA](https://mega.io)** | Valuation: Private / Rev: ~$15M–$60M estimated | €3.33/mo (~$3.66/mo billed annually) for Essential plan (200 GB) | 20 GB permanent free zero-knowledge encrypted base storage (expandable via bonus tasks) | User-controlled end-to-end encrypted cloud drive, backup, and secure chat/file-transfer platform with zero-knowledge cryptographic key management. |
| **[Tresorit](https://tresorit.com)** | Valuation: Acquired by Swiss Post (~$51M prev. val / Rev: ~€8.2M ARR) | $11.99/mo (billed annually at $143.88/yr) for Personal Essential (1 TB) | 3 GB permanent free storage on Tresorit Basic (max 500 MB file size, 2 connected devices); or 14-day free trial on paid plans | Enterprise-grade zero-knowledge end-to-end encrypted cloud storage and secure file-sharing suite engineered for regulated industries and confidential team collaboration. |
| **[Sync.com](https://sync.com)** | Valuation: Private Bootstrapped / Rev: ~$5M–$10M ARR | $8.00/mo (billed annually at $96.00/yr) for Solo Basic (2 TB) | 5 GB permanent free end-to-end encrypted storage (3 active shared links and folders) | Privacy-focused cloud storage and document collaboration platform providing default client-side end-to-end encryption, granular link permissions, and compliance auditing. |
| **[pCloud](https://pcloud.com)** | Valuation: Private ($3M raised / Rev: ~$4M–$10M ARR) | $4.99/mo (or $49.99/yr) for Premium (500 GB); $199 one-time Lifetime | 10 GB permanent free storage (starts at 2 GB, unlock up to 10 GB via verification tasks) | Cloud storage platform offering virtual drive mounting (`pCloud Drive`), lifetime storage plans, and optional client-side zero-knowledge encryption (`pCloud Crypto`). |
| **[Icedrive](https://icedrive.net)** | Valuation: Private Bootstrapped (ID Cloud Services Ltd / Rev: Undisclosed) | $2.99/mo (or $19.99/yr) for Lite (100 GB) | 10 GB permanent free cloud storage (no credit card required) | Modern cloud storage service featuring Twofish client-side encryption, virtual drive integration, and a fast web/mobile file browser. |





## Open-Source GitHub Projects



- **[zenhosta/9drive](https://github.com)**  

  Open-source lightweight cloud drive and file storage project designed for clean self-hosted file management, sharing, and streamlined personal cloud access.



- **[Nextcloud (`nextcloud/server`)](https://github.com)**  

  Flagship self-hosted open-source content collaboration and cloud drive platform offering desktop/mobile sync clients, optional end-to-end encryption, and an extensive app ecosystem.



- **[ownCloud Infinite Scale — oCIS (`owncloud/ocis`)](https://github.com)**  

  Modern, cloud-native open-source file sync and share platform rewritten in Go as a single binary with zero database dependencies and high-performance S3/POSIX storage backends.



- **[Seafile (`haiwen/seafile`)](https://github.com)**  

  High-performance open-source enterprise file sync and share system written in C/Python featuring Git-like block-level delta syncing, virtual drive mounting, and client-side encrypted libraries.



- **[Cryptomator (`cryptomator/cryptomator`)](https://github.com)**  

  Leading open-source, transparent client-side encryption tool that creates virtual encrypted drives inside Google Drive, Dropbox, OneDrive, or any local/cloud storage folder.



- **[rclone (`rclone/rclone`)](https://github.com)**  

  Essential open-source command-line program ("rsync for cloud storage") supporting 70+ cloud providers, transparent `crypt` client-side encryption, and FUSE virtual drive mounting.



- **[Syncthing (`syncthing/syncthing`)](https://github.com)**  

  Continuous, decentralized open-source peer-to-peer file synchronization utility written in Go that syncs folders directly across devices with TLS encryption and zero central servers.



- **[OpenCloud (`opencloud-eu/opencloud`)](https://github.com)**  

  Community-driven open-source file management and collaboration platform forked from oCIS, focused on digital sovereignty, fast Go microservices, and open standards.



- **[FileBrowser (`filebrowser/filebrowser`)](https://github.com)**  

  Lightweight, single-binary open-source web file manager written in Go providing an intuitive Google Drive-style interface over any local server directory.



- **[SFTPGo (`drakkan/sftpgo`)](https://github.com)**  

  Full-featured open-source event-driven file transfer and cloud storage server supporting SFTP, HTTP/S WebClient, WebDAV, and S3/GCS/Azure backends with encryption at rest.



- **[Peergos (`Peergos/Peergos`)](https://github.com)**  

  Open-source, peer-to-peer, post-quantum end-to-end encrypted storage and social file-sharing protocol built on IPFS with metadata privacy.



### Additional Strong Open-Source Options



- **[gocryptfs (`rfjakob/gocryptfs`)](https://github.com)** and **[CryFS (`cryfs/cryfs`)](https://github.com)** for fast, FUSE-based encrypted overlay filesystems engineered specifically for cloud folder synchronization.

- **[MinIO (`minio/minio`)](https://github.com)** and **[Garage (`deuxfleurs-org/garage`)](https://deuxfleurs.fr)** for self-hosted, S3-compatible object storage backends with server-side encryption (SSE-KMS/SSE-C).

- **[Duplicati (`duplicati/duplicati`)](https://github.com)** and **[Restic (`restic/restic`)](https://github.com)** for open-source, deduplicated, AES-256 encrypted incremental backups to any cloud drive or S3 bucket.

- **[Copyparty (`9001/copyparty`)](https://github.com)** for a portable single-file Python file server turning almost any device into a resumable-upload WebDAV/HTTP cloud drive.

- **[Pydio Cells (`pydio/cells`)](https://github.com)** for a modern open-source Go-based enterprise document sharing and collaboration platform with microservice architecture.



**Frameworks for building custom systems**: Combine **Nextcloud** or **ownCloud Infinite Scale (oCIS)** for full collaborative cloud drives, **Cryptomator** or **rclone (`crypt`)** for zero-knowledge client-side encryption over any cloud provider, and **Syncthing** for serverless P2P device sync.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS/hosted or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Support & Share



If you find this curated list helpful, consider supporting the project:



- ⭐ **Star this repository** to help others discover it.

- 🍴 **Fork & Share** it with your team, friends, or community on X/Twitter, LinkedIn, and Reddit.

- ☕ **Buy me a coffee / Sponsor** my open-source work on [GitHub Sponsors](https://github.com) — featuring tiers for profile badges, README shoutouts, logo placements, and prioritized bug fixes/features!



[![Sponsor @ishandutta2007](https://shields.io)](https://github.com)



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- With zero-knowledge client-side encryption tools (such as `Cryptomator`, `rclone crypt`, `Proton Drive`, or `Tresorit`), losing your master password or recovery key permanently renders your data unrecoverable; store recovery keys securely offline.

- Self-hosted cloud drives exposed to the internet must enforce HTTPS/TLS, strong MFA, automated database/storage backups, and regular security patching.



---



**Made for privacy advocates, homelab builders, sysadmins, developers, and open-source contributors.**  

Let's make cloud storage and file synchronization more open, private, and user-controlled.
