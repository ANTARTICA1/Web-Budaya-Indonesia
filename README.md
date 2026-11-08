# Kebudayaan Indonesia - Interactive Cultural Heritage Portal

An educational web platform dedicated to cataloging, preserving, and presenting the diversity of Indonesian cultural heritage. Engineered with modern HTML5, CSS3, and Bootstrap 5, the portal offers deep cultural documentation, multimedia galleries, informative articles, and geographical cultural mapping across the Indonesian archipelago.

## Overview

Indonesia possesses exceptional ethnic and cultural diversity spanning over 17,000 islands. This portal organizes traditional performing arts, architecture, culinary traditions, and sacred ceremonies into an accessible, responsive digital repository designed for students, researchers, and cultural enthusiasts.

## Interface Preview

[![Interface Preview Status](https://img.shields.io/badge/Interface_Preview-Documentation_in_Progress-2563eb?style=for-the-badge)](https://github.com/ANTARTICA1/Web-Budaya-Indonesia)

## Core Content and Modules

- Home Portal (`index.html`): Engaging landing page introducing Indonesian cultural identity and featured cultural traditions.
- Cultural Registry (`daftar.html`): Filterable directory of cultural assets categorized by province and domain.
- Dedicated Deep-Dive Articles:
  - Tari Kecak (`detailkecak.html`): Balinese sacred vocal dance drama narrating the Ramayana epic.
  - Ogoh-Ogoh (`detailogoh.html`): Balinese giant mythological effigies paraded during the eve of Nyepi (Tawur Agung Kesanga).
  - Rumah Adat Honai (`detailhonai.html`): Indigenous Papuan architecture engineered for Highland thermal efficiency.
  - Reog Ponorogo (`detailreog.html`): Iconic East Javanese performance art featuring the Singa Barong peacock mask.
  - Rendang Minangkabau (`detailrendang.html`): Globally recognized West Sumatran slow-cooked caramelized culinary tradition.
  - Rambu Solo (`detailrambu.html`): Elaborate Torajan funerary rites and ancestor veneration traditions.
- Interactive Map (`peta.html`): Geographical representation mapping cultural assets across western, central, and eastern Indonesia.
- Multimedia Gallery (`galeri.html`): Responsive visual showcase displaying traditional costumes, ceremonies, and artifacts.
- Editorial Articles (`artikel.html` - `artikel3.html`): Analytical writings regarding cultural preservation in the digital era.

## Technology Stack

- Markup: Semantic HTML5
- Styling: CSS3, Custom Color Palettes (Indonesian Heritage Earth Tones)
- Front-End Framework: Bootstrap 5.3.3
- Responsive Design: Flexbox and Grid layout compliant across smartphone, tablet, and desktop displays

## Project Structure

```
Web-Budaya-Indonesia/
├── css/                     # Custom stylesheet rules and theme variables
├── img/                     # Cultural photography, illustrations, and maps
├── artikel.html             # Cultural editorial index
├── artikel1.html            # Editorial article 1
├── artikel2.html            # Editorial article 2
├── artikel3.html            # Editorial article 3
├── daftar.html              # Comprehensive cultural registry
├── detailhonai.html         # Papuan Honai cultural case study
├── detailkecak.html         # Balinese Kecak cultural case study
├── detailogoh.html          # Balinese Ogoh-Ogoh case study
├── detailrambu.html         # Torajan Rambu Solo case study
├── detailrendang.html       # Minangkabau Rendang case study
├── detailreog.html          # Ponorogo Reog case study
├── galeri.html              # Cultural photo gallery
├── index.html               # Main landing portal
├── peta.html                # Interactive archipelago map
└── README.md                # Project documentation
```

## Running Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/ANTARTICA1/Web-Budaya-Indonesia.git
   cd Web-Budaya-Indonesia
   ```

2. Open `index.html` in any web browser, or launch using a local development server:
   ```bash
   python -m http.server 8080
   ```

3. Visit `http://localhost:8080` in your web browser.

## Author

Anak Agung Ngurah Krisna Artha Wibawa ([ANTARTICA1](https://github.com/ANTARTICA1))  
Institut Teknologi dan Bisnis (ITB) STIKOM Bali

## License

This project is licensed under the MIT License.