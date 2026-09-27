# influencers-club-site-scraper
High-speed Influencers Club leads https://influencers.club/ scraper offering two distinct operational workflows: In-Depth UI Panel (DOM scraping) and Headless API Interceptor (Fast front-row leads). Engineered by Apex Automation Team.


# 🌟 Influencers Club Lead Scraper Suite (Dual Engine)

> 💡 **Community Project**: This project is open-sourced and provided for free as part of the automation initiatives by **[Apex Automation Team](https://apexautomationteam.com/)**. Visit our official portal for custom enterprise scraping pipelines, B2B lead extractors, and workflow automations!

A specialized, dual-mode browser scraper built for extracting creator profiles, public social handles, and lead lists directly from **Influencers Club** with zero external API fees.

---

## ⚡ Two Distinct Scraping Modes

This repository provides **two separate scraping engines** designed for different lead generation needs:

| Feature / Engine | 🖥️ Option 1: UI Panel Mode (`With Panel`) | ⚡ Option 2: Headless API Mode (`No Panel`) |
| :--- | :--- | :--- |
| **Primary Script** | `Influencers_Club_Panel_Scraper.js` | `Influencers_Club_No_Panel_Fast.js` |
| **Mechanism** | Deep frontend DOM scraping with full modal expansion | Backend API / Network stream interception |
| **Depth of Data** | **Deep / Complete**: Opens each creator row/card to extract deep contact details, metrics, and extended bio data. | **Front-Row Only**: Captures creator names, handles, categories, and top-level summary metrics directly from search lists. |
| **Execution Speed** | Moderate pace (respects UI animation & modal renders) | Blazing fast (captures paginated data batches instantly) |
| **Auto Load More** | Yes, automatically scrolls and navigates UI panels | Yes, triggers automated batch fetches |
| **Best For** | Exporting fully enriched creator records with maximum attributes. | Rapid bulk extraction of names and handles for multi-platform outreach or cross-referencing. |

---

## 📺 Demonstration Videos & Tutorial Assets

Video demonstrations illustrating both modes are hosted in our official release section, all videos in one zip:

* 📥 **[Download UI Panel Mode Tutorial (`With Panel`)](https://github.com/ApexAutomationTeam/influencers-club-site-scraper/releases/tag/v4.0.1)**
* 📥 **[Download Fast API Mode Tutorial (`No Panel`)](https://github.com/ApexAutomationTeam/influencers-club-site-scraper/releases/tag/v4.0.1)**
* 📦 **[View Official Release v4.0.1 Assets]([https://github.com/ApexAutomationTeam/Google-Maps-Scraper/releases/tag/v1.0.0](https://github.com/ApexAutomationTeam/influencers-club-site-scraper/releases/tag/v4.0.1))**

---

## 🛠️ Step-by-Step Usage Guide

### Option 1: Using the Full UI Panel Mode (Deep Scraper)

1. Open Google Chrome and log into your account on **Influencers Club**.
2. Apply your target search filters (niche, location, follower range).
3. Press **`F12`** (or right-click and select **Inspect**) to open the **Console** tab.
4. If prompted with browser paste warnings, type `allow pasting` and hit Enter.
5. Copy all code from `Influencers_Club_Panel_Scraper.js`, paste it into the console, and hit **Enter**.
6. The interactive panel will trigger automated scrolling, expand individual rows to extract detailed profile data, and export an organized Excel (`.xlsx`) sheet upon completion.

---

### Option 2: Using the Fast API Mode (No Panel / Front-Row Fast)

1. Log into your **Influencers Club** dashboard and navigate to your filtered search results.
2. Open Chrome DevTools Console (`F12`).
3. Copy all code from `Influencers_Club_No_Panel_Fast.js`, paste it into the console, and press **Enter**.
4. The script intercepts the underlying backend JSON stream and triggers automated "load-more" queries.
5. It compiles front-row creator records rapidly, allowing you to search and target creator names across Instagram, TikTok, or YouTube manually or via bulk lookup tools.
6. The file downloads automatically once the target batch count is satisfied.

---

## ⚠️ Maintenance & Upgrades Notice

> **Platform Change Alert**:  
> SaaS platforms frequently modify their frontend class selectors or internal API endpoints. If Influencers Club rolls out major layout adjustments:
> 
> * **Community Contributions**: Developers can inspect the updated network payloads or DOM selectors and submit a Pull Request.
> * **Direct Engineering Support**: Need custom adjustments or an immediate patch? Reach out directly to our team:  
>   📧 **contact@apexautomationteam.com**  
>   We will update the repository with a working build.

---

## 🏢 About Apex Automation Team

We build custom browser extensions, web scrapers, automated workflows, and AI solutions to scale your business operations.

* **Official Website:** [https://apexautomationteam.com/](https://apexautomationteam.com/)
* **Support & Custom Tools:** contact@apexautomationteam.com
```[cite: 14, 22, 23]
