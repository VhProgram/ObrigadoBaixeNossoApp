# Copilot Instructions - ObrigadoBaixeNossoApp

## Project Overview
**ObrigadoBaixeNossoApp** é uma página web de agradecimento estática para usuários que preenchem um formulário. Serve como intermediária para direcionar downloads de apps móveis (Android e iOS).

## Architecture
- **Type**: Landing page estática (HTML/CSS)
- **Structure**: Single file with embedded CSS
- **Purpose**: Gratidão + Call-to-Action para download de apps

## Key Components

### [index.html.txt](../index.html.txt)
- Main page file (note: `.txt` extension - file contains HTML code)
- Responsive design (mobile-first: 480px max-width)
- Two download buttons linking to:
  - Google Play Store (Android): `https://play.google.com/store/apps/details?id=SEU_APP`
  - Apple App Store (iOS): `https://apps.apple.com/app/idSEU_APP`
- Hero image: `obrigado.png`

## Critical Details for Updates

### URL Placeholders
The app store links contain **placeholder IDs** that must be replaced:
- `SEU_APP` → Actual Android package ID
- `idSEU_APP` → Actual iOS app ID

**Always update both placeholders** when providing app store links.

### Styling Conventions
- Color scheme: Green for Android (#3ddc84), Black for iOS (#000)
- Font: Arial/Helvetica fallback
- Button styling: Block display with 15px padding
- Container max-width: 480px (mobile-optimized)

### Language
- Portuguese (Brazil) - `lang="pt-br"`
- All user-facing text in Portuguese
- Meta charset: UTF-8

## Common Tasks

### Update App Store Links
Edit the `href` attributes in the download button `<a>` tags. Replace placeholder IDs with real app store IDs.

### Modify Hero Image
Change `src="obrigado.png"` to point to the correct image file location and ensure file exists.

### Styling Changes
All CSS is embedded in `<style>` tag within the HTML file. Maintain responsive design and color scheme.

### Text Changes
Translations should maintain Portuguese tone and formatting.
