**Mobile App Market Analysis for Profitability**
Exploring the Google Play Store and Apple App Store to identify high-growth niches for free, ad-supported apps.

Project Overview
The goal of this project was to analyze over 17,000 mobile apps to provide data-driven recommendations for developers looking to build profitable free apps. I focused on identifying genres with high user engagement but lower market saturation.

Tech Stack
- **Language:** Python 3.x
- **Libraries:** Pandas (Data Manipulation), Matplotlib/Seaborn (Visualization)
- **Tools:** Google Colab / Jupyter Notebook

Key Data Cleaning Steps
To ensure high-quality insights, I performed the following:
1. **Deduplication:** Removed duplicate entries by keeping versions with the highest review counts.
2. **Data Type Correction:** Converted string-based 'Installs' and 'Price' columns into numeric formats.
3. **Market Filtering:** Isolated English-language apps and filtered for "Free" price points.
4. **Data Validation:** Corrected shifted rows in the Google Play dataset (e.g., row 10472).

Key Insights
- **The "Saturation" Trap:** While 'Games' have the most apps, the competition is too high for new developers.
- **The Hidden Gems:** The **Reference** and **Weather** categories show significantly higher average installs per app compared to common genres.
- **Recommendation:** A new developer should focus on utility-based apps (Reference/Weather) to maximize organic visibility.

