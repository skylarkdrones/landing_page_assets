# DroneMissionOps Landing Page Assets

This repository serves as the centralized asset delivery source for [dronemissionops.com](https://dronemissionops.com). It hosts all production media, organized to match the landing page's modular architecture.

## 🚀 Base URL

All assets are served via the GitHub raw content CDN. When referencing assets in the frontend constant file, use the following base:

`export const BASE_URL = "https://raw.githubusercontent.com/skylarkdrones/landing_page_assets/main";`

## 📂 Directory Structure

The repository is structured into the following directories, mapped to the `IMAGES` constant in the frontend codebase:

*   **`/hero`**  
    Primary header visuals, including the main hero image and strategic partner/support logos.

*   **`/features`**  
    Visuals detailing platform capabilities such as mission planning, data QC, pixel-perfect imaging, and video grid interfaces.

*   **`/tabs`**  
    Assets for interactive components, including category-specific icons (mapping, surveillance, inspection) and their corresponding platform screenshots.

*   **`/detailed`**  
    High-resolution illustrations for industry-specific use cases like disaster response, crowd management, and security surveillance.

*   **`/testimonials`**  
    Identity assets for social proof, including client headshots and verified operator profile images.

*   **`/social-preview`**  
    Contains the branding assets used for Open Graph (OG) metadata and social media link previews.

*   **`/go-live`**  
    Dedicated visual assets for the "Go-Live" section, featuring specific hero imagery and supporting feature highlights.

*   **`/platforms`**  
    Dedicated visual assets for the "Platforms" page, featuring specific hero imagery and highlighting desktop and android platforms.

## 🛠 Asset Standards (2026)

1.  **Naming Convention**: All new files must use `kebab-case.ext` to maintain compatibility with existing image constants.
2.  **Performance**: Prioritize **SVG** for icons to maximize Core Web Vitals scores.

**Should the website load slower:**

3.  **Optimization**: Assets must be compressed using [TinyPNG](https://tinypng.com) or [Squoosh](https://squoosh.app) before being committed to the repository.

---
*© 2026 DroneMissionOps. All assets are proprietary and intended for use on official company web properties.*
