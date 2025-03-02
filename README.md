# Spatial Heterogeneity in Human Mobility Responses to London's ULEZ Expansion

This repository contains code and data supporting the paper **Spatial Heterogeneity in Human Mobility Responses to London's Ultra-Low Emission Zone Expansion** by [Yikang Wang](https://yikang.wang/) and [Dr Chen Zhong](https://profiles.ucl.ac.uk/46973).

## Repository Structure

The repository is organised as follows:

-   **Code**:
    -   **`Extended ITS.ipynb`**: Jupyter Notebook implementing the extended Interrupted Time Series (ITS) analysis.
-   **Input data**:
    -   **`mobility indicators/`**: Pre-calculated human mobility indicators derived from mobile phone location data, aggregated at the Middle Layer Super Output Area (MSOA) and Local Authority District (LAD) levels. 
    -   **`Census Data/`**: Socioeconomic indicators from the 2021 UK Census (aggregated at MSOA/LAD levels).
    -   **`PTAL/`**: Public Transport Accessibility Level (PTAL) and Index (PTAI) data, aggregated at MSOA and LAD levels.
    -   **`fuel price/`**: Weekly fuel price data. This dataset was excluded from final analysis due to multicollinearity.
    -   **`UK Geo Data/`**: UK MSOA boundary data.
-   **Output**:
    -   **`results/`**: Processed model outputs, including merged tables and figures referenced in the paper.

## Usage

Execute `Extended ITS.ipynb` using Jupyter Notebook. Ensure required Python dependencies are installed (full list in `requirements.txt`).
