# Awesome-Digital-Video-Player-Store

# Awesome-Digital-Video-Player-Store

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Video Storefronts, Media Servers & Self-Hosted Streaming*
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Digital Video Players & Stores**. These tools help users buy, rent, and stream movies and TV shows—and help developers build self-hosted media servers with full library control.

**Examples** include Microsoft Movies & TV, Apple TV, Amazon Prime Video, Google TV, Fandango at Home (Vudu), YouTube Movies, Google Play Movies, Hulu, Roku, and Jellyfin (the category leaders).

**Open-source emphasis**: The open-source media server ecosystem is **exceptionally mature and production-proven**. **Jellyfin** is the leading free, open-source media server with no premium tiers, no tracking, and full library ownership . **Plex** offers a polished experience with both free media server functionality and optional Plex Pass . **Kodi** provides a highly customizable media center for local and network content . **Stremio** aggregates streaming sources into a unified interface, free forever . This section documents these production-grade solutions.

## 📖 Table of Contents

- [💼 SaaS/Hosted Platforms](#-saas-hosted-platforms)
- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)
- [🤝 How to Contribute](#-how-to-contribute)
- [⚠️ Disclaimer](#-disclaimer)

## 💼 SaaS/Hosted Platforms

> **📊 Market Context**: The digital video store and streaming market is **highly fragmented** and undergoing **significant consolidation**. **Microsoft permanently abandoned its Movies & TV storefront on July 18, 2025**—no new purchases or rentals, though previously purchased content remains viewable . **Google Play Movies & TV is being phased out**, with purchases migrating to Google TV and YouTube . **Apple removed the dedicated iTunes Movies and TV Shows apps in tvOS 26.4**, consolidating all purchases into the Apple TV app . **Fandango simplified its branding** from "Fandango at Home" to just "Fandango," unifying ticket and streaming services . The market is **shifting from ownership to access**, with **Free Ad-Supported Streaming TV (FAST)** services like Google TV Freeplay (10,000+ free titles) , Tubi, Pluto TV, and Plex's free tier  gaining significant share. No single vendor holds a winner-take-all position; consumers increasingly mix storefront purchases with subscription and ad-supported services.

| Platform | Description | Pricing (Starting Tier) | Free Tier Limits | Company Size |
|----------|-------------|------------------------|------------------|--------------|
| **[Apple TV](https://www.apple.com/apple-tv-app/)** | **Apple's unified storefront for movie and TV purchases.** Replaced dedicated iTunes Movies and TV Shows apps in tvOS 26.4 . | **Free app** — pay per rental or purchase. **Rentals**: Typically **$3.99–$19.99**; **Purchases**: **$4.99–$29.99** . **Apple TV+ subscription**: **$15/month** . | **App is free** with Apple device or Apple ID. **Apple TV+**: 7-day free trial. | **~$400B revenue (Apple FY2025 est.)** |
| **[Amazon Prime Video](https://www.amazon.com/primevideo)** | **Amazon's streaming service with transactional VOD store.** Prime members get included content; non-Prime users can rent or buy. | **Prime**: **$14.99/month** (includes Prime Video). **Rentals**: **$2.99–$19.99**; **Purchases**: **$4.99–$29.99**. | **Freevee** (bundled with Prime Video): Free ad-supported movies and TV with Amazon account . | **~$638B revenue (Amazon FY2025)** |
| **[Google TV](https://tv.google/)** | **Google's unified entertainment hub.** Replaced Google Play Movies & TV for purchases . **Freeplay** adds 10,000+ free ad-supported titles and 300+ live channels . | **Free app** — pay per rental or purchase. **Rentals**: **$2.99–$5.99** typical; **Purchases**: **$4.99–$29.99** . | **Google TV Freeplay**: **10,000+ free movies and TV shows** on demand, **300+ free live channels**, no subscription required . | **~$350B revenue (Alphabet FY2025)** |
| **[Fandango (formerly Fandango at Home/Vudu)](https://www.fandango.com/)** | **Movie ticket and streaming unified under one brand.** Purchased content from Vudu/Fandango at Home remains accessible . | **Free app** — pay per rental or purchase. **Rentals**: **$0.99–$5.99**; **Purchases**: **$4.99–$29.99** . | **10,000+ free ad-supported titles**; **3,500+ hours** of free programming including live Bundesliga soccer . | **Private (Fandango)** |
| **[Hulu](https://www.hulu.com/)** | **Disney-owned streaming service.** On-demand library plus live TV option. | **Ad-supported**: **$9.99/month**; **Ad-free**: **$18.99/month**. **Live TV**: Higher tier. | **30-day free trial** for new subscribers. **No perpetual free tier**. | **~$12B revenue (Disney FY2025 est.)** |
| **[Roku](https://www.roku.com/)** | **Streaming platform and store.** The Roku Channel offers free ad-supported movies and TV. | **Hardware**: From **$29.99**. **Roku Channel**: Free. | **The Roku Channel**: Free ad-supported movies, TV, and live channels. | **~$3.5B revenue (Roku FY2025 est.)** |
| **[Microsoft Movies & TV](https://www.microsoft.com/en-us/p/movies-tv/9wzdncrfj3p2)** | **Discontinued storefront (July 18, 2025).** Previously purchased content remains viewable. | **N/A** — no longer sells new content . | **N/A** — storefront abandoned. | **~$281B revenue (Microsoft FY2025)** |
| **[Google Play Movies](https://play.google.com/store/movies)** | **Being phased out.** Purchases migrated to Google TV and YouTube . | **N/A** — migrating to Google TV. | **N/A** — deprecating. | **~$350B revenue (Alphabet FY2025)** |

## 🔓 Open-Source GitHub Projects

| Repo | Description | Stars |
|------|-------------|-------|
| **[Jellyfin](https://github.com/jellyfin/jellyfin)** — **The leading free, open-source media server.** **No premium tiers, no tracking, no hidden costs**—you cannot pay for it even if you want to . Full library ownership, cross-platform (Windows, macOS, Linux, Docker, NAS), and community-driven development. **GPL-2.0**. | [![Stars](https://img.shields.io/github/stars/jellyfin/jellyfin?style=social&color=white)](https://github.com/jellyfin/jellyfin/stargazers) | ~38,000 |
| **[Kodi](https://github.com/xbmc/xbmc)** — **Award-winning free and open-source media center.** Cross-platform entertainment hub for HTPCs, with extensive add-on ecosystem, skins, and support for local and network media . **GPL-2.0**. | [![Stars](https://img.shields.io/github/stars/xbmc/xbmc?style=social&color=white)](https://github.com/xbmc/xbmc/stargazers) | ~20,000 |
| **[Plex Media Server](https://github.com/plexinc/pms-docker)** — **Popular media server with free tier and optional Plex Pass.** Polished UX, remote streaming, DVR, and parental controls. **Free** for core media server functionality; **Plex Pass** unlocks offline downloads, live TV recording, and enhanced features . | [![Stars](https://img.shields.io/github/stars/plexinc/pms-docker?style=social&color=white)](https://github.com/plexinc/pms-docker/stargazers) | ~2,000 |
| **[Stremio](https://github.com/Stremio/stremio-shell)** — **Free, open-source video streaming aggregator.** Combines streaming sources into a unified interface with add-on support. **Free forever**—will always remain free . | [![Stars](https://img.shields.io/github/stars/Stremio/stremio-shell?style=social&color=white)](https://github.com/Stremio/stremio-shell/stargazers) | ~1,500 |
| **[OMDb API](https://github.com/omdbapi/omdbapi)** — **Open Movie Database REST API.** Provides movie and TV show metadata, ratings, poster images, and episode data from a community-maintained database. **Free tier** with self-serve signup . | [![OMDb](https://img.shields.io/badge/OMDb-API-blue)](https://github.com/omdbapi/omdbapi) | N/A |

**Additional open-source options worth exploring:**

| Repo | Description |
|------|-------------|
| **[Emby](https://github.com/MediaBrowser/Emby)** — Media server with free tier and Emby Premiere subscription. |
| **[Internet Archive Movies](https://archive.org/details/movies)** — **15,000+ free movies** including public domain classics. No ads, no registration required . |
| **[Tubi](https://tubitv.com/)** — Free ad-supported streaming with **275,000+ movies and TV shows**. Not open-source but free with account . |
| **[Pluto TV](https://pluto.tv/)** — Free ad-supported streaming with hundreds of live channels. Paramount-owned . |

## 🤝 How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## ⚠️ Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- **Critical lifecycle notices**: **Microsoft Movies & TV abandoned its storefront on July 18, 2025**—no new purchases or rentals . **Google Play Movies & TV is being phased out** . **Apple removed dedicated iTunes Movies/TV apps in tvOS 26.4** .
- **Digital ownership caveat**: Purchased content is **tied to platform accounts**. If your account is banned or the service shuts down, you may lose access. **Movies Anywhere** helps consolidate movie purchases across platforms, but **no equivalent exists for TV shows** .
- **Open-source reality**: The open-source ecosystem for media servers is **exceptionally mature and production-proven**. **Jellyfin** is the leading free, open-source media server with **no premium tiers, no tracking, and full library ownership**—you cannot pay for it even if you want to . **Kodi** provides a highly customizable media center . **Plex** offers a polished experience with both free and premium tiers . **Stremio** aggregates streaming sources for free . However, **commercial platforms** (Apple TV, Amazon Prime Video, Google TV) provide **vast content libraries, transactional VOD stores, and seamless device integration** that open-source alternatives cannot match for new release purchases. The open-source path is **genuinely viable** for users who own their media and want full control over their library.
- **Free streaming caveat**: **Google TV Freeplay** now offers **10,000+ free titles** with no subscription . **Fandango** offers **3,500+ hours** of free content . **Tubi** and **Pluto TV** provide extensive free libraries with ads . Always verify content availability in your region.

---

**Made for movie collectors, cord-cutters, home theater enthusiasts, and self-hosting advocates.**
Let's make digital video ownership more open, transparent, and user-controlled.
