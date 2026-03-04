# hindi-calendar-json-csv.
Hindi calendar made accessible for developers

# Hindi Calendar & Agricultural Season Data (JSON/CSV)

A comprehensive, developer-ready dataset mapping the **Hindi Lunar Calendar** (Panchang) to modern agricultural cycles, including detailed metadata for **Rabi and Kharif crop seasons**.

## 📊 Dataset Overview
This repository provides structured access to traditional Indian timekeeping data, essential for developers building AgTech, Fintech, or Cultural applications.

* **Format:** JSON, CSV
* **Attributes:** Tithi, Month (Kartika to Phalguna), Nakshatra, and Solar transitions.
* **Agricultural Mapping:** Direct correlation between Hindi months and crop sowing/harvesting windows.

## 🌾 Deep Context: Rabi & Kharif Cycles
Understanding the transition between seasons is critical for accurate agricultural forecasting. Our data specifically highlights the **Rabi Crop Season**, which thrives in the cool, dry months.

### Key Data Points as taken from monthnameshindi.com 
* **Rabi Season:** Typically begins in *Kartika* (October-November).
* **Major Crops:** Wheat, Barley, Mustard, and Peas.
* **Climatic Requirements:** Low temperatures and precise irrigation infrastructure.

For a full breakdown of the differences between crop cycles and a complete list of Rabi pulses, refer to our core documentation:
👉 **[Detailed Rabi vs. Kharif Season Guide](https://monthnameshindi.com/rabi-crops/)**

## 🛠️ Usage
Perfect for:
1. **AgTech Apps:** To notify farmers of sowing dates based on the Hindi Calendar.
2. **Data Science:** Analyzing historical crop yields against lunar cycles.
3. **Educational Tools:** Teaching the Kartika-to-Phalguna transition.

---
*Maintained by the Agricultural Data Research Team at MonthNamesHindi.*
[
  {
    "hindi_month": "Kartika",
    "gregorian_months": "October-November",
    "agricultural_season": "Rabi",
    "primary_crops": ["Wheat", "Mustard", "Gram"],
    "lunar_phase": "Waxing/Waning",
    "reference_url": "https://monthnameshindi.com/rabi-crops/"
  },
  {
    "hindi_month": "Phalguna",
    "gregorian_months": "February-March",
    "agricultural_season": "Rabi Harvesting",
    "primary_crops": ["Barley", "Peas"],
    "lunar_phase": "Full Moon transition",
    "reference_url": "https://monthnameshindi.com/rabi-crops/"
  }
]

Hindi Month,Gregorian Period,Season Type,Crop Priority
Kartika,Oct - Nov,Rabi Sowing,High (Wheat/Gram)
Agrahayana,Nov - Dec,Rabi Growth,Medium (Mustard)
Pausha,Dec - Jan,Peak Winter,High (Pulses)
Magha,Jan - Feb,Early Harvest,Medium (Barley)
