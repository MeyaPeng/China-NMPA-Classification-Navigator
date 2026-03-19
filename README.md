# China NMPA Classification Navigator (Beta)

A tool designed for Regulatory Affairs specialists to navigate the MD/IVD Classification in China.

## 🌟 Key Features
* **Definition Filter:** Preliminary assessment of whether a product meets the NMPA definition of a medical device.
* **Intended Use Analysis:** Mapping clinical functions to the NMPA Classification Catalog.
* **Bilingual Interface:** English input support with Chinese regulatory alignment.
* **Zero-API / Privacy-First:** All logic runs locally in your browser. No data is uploaded.

## 🛠 How it Works
This tool uses a structured **Knowledge Base (JSON)** derived from official NMPA classification rules and technical guiding principles. It performs keyword matching and logical branching to suggest a potential classification (Class I, II, or III).

## ⚠️ Disclaimer
This project is for **reference only**. The final classification must be confirmed by the **NMPA Classification Improvement Center**. The developer assumes no legal responsibility for regulatory outcomes.

## 📂 Project Structure
* `/docs`: Reference to official public notices.
* `/logic`: The core decision tree script.
* `index.html`: The interactive web interface.
