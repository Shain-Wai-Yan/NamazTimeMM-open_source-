# Namaz Time MM

Namaz Time MM is a comprehensive, privacy-focused Islamic prayer times application specifically optimized for Myanmar. Built with Next.js and Capacitor, it provides accurate prayer calculations, location-based services, and a bilingual interface without any tracking or proprietary dependencies.

## Features

- **Accurate Prayer Times**: Precise solar calculations for daily prayers.
- **Myanmar Optimized**: Pre-configured support for 20+ major Myanmar cities.
- **Location Detection**: Automatic calculation based on your current GPS coordinates.
- **Bilingual Support**: Fully accessible in both Burmese (Unicode) and English.
- **Privacy First**: Zero analytics, no tracking, and no proprietary SDKs. Fully F-Droid compliant.
- **Offline Functionality**: Works entirely offline after the initial load.
- **Qibla Direction**: Integrated compass to find the direction of the Kaaba.

## Tech Stack

- **Framework**: [Next.js](https://nextjs.org/) (App Router)
- **Mobile Runtime**: [Capacitor](https://capacitorjs.com/)
- **UI Components**: [Shadcn UI](https://ui.shadcn.com/) & [Tailwind CSS](https://tailwindcss.com/)
- **Icons**: [Lucide React](https://lucide.dev/)

## Build Instructions

### Prerequisites

- Node.js (v18 or later)
- Android Studio (for Android builds)

### Local Development

1. Install dependencies:
   ```bash
   npm install
   ```

2. Run the development server:
   ```bash
   npm run dev
   ```

### Android Build

1. Build the Next.js project:
   ```bash
   npm run build
   ```

2. Sync with Capacitor:
   ```bash
   npx cap sync
   ```

3. Open in Android Studio:
   ```bash
   npx cap open android
   ```

## License

This project is licensed under the **GNU General Public License v3.0** - see the [LICENSE](LICENSE) file for details.
