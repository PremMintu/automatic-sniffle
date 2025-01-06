# Malaysian Condominium Price Analysis

This repository contains the code, visualizations, and documentation for analyzing condominium prices in Malaysia. The project uses a data-driven approach to identify the key factors influencing property prices and builds predictive models to assist stakeholders like buyers, developers, and policymakers.

## Key Features

- **Data Cleaning and Preprocessing:**
  Scripts to clean and preprocess the dataset, ensuring consistency and removing missing values.

- **Exploratory Data Analysis (EDA):**
  Visualizations such as:

  - Correlation heatmaps to analyze relationships between numerical features.
  - Boxplots, scatter plots, and density plots to explore price distributions and trends.

- **Statistical Analysis:**

  - Multiple regression analysis and hypothesis testing to identify significant factors affecting property prices.

- **Comprehensive Documentation:**
  - Includes the project’s introduction, methodology, visualizations, and conclusions.

## Dataset Description: `houses.csv`

The `houses.csv` file is the primary dataset used for this analysis. It contains detailed information about condominium unit listings in Malaysia. Below is a description of the key columns:

- **description:** A textual description of the property listing.
- **Bedroom:** Number of bedrooms in the unit.
- **Bathroom:** Number of bathrooms in the unit.
- **Property Size:** Size of the unit in square feet.
- **Nearby School:** Information about nearby schools.
- **Nearby Mall:** Details about nearby malls.
- **Facilities:** A list of facilities available in the building (e.g., parking, gym, pool).
- **Building Name:** Name of the building where the unit is located.
- **Developer:** Name of the property developer.
- **Tenure Type:** Indicates the tenure type (e.g., leasehold, freehold).
- **Address:** Address of the property.
- **Completion Year:** Year when the building was completed or "-" if under construction.
- **# of Floors:** Total number of floors in the building.
- **Total Units:** Total number of units in the building.
- **price:** The listed price of the unit (target variable for prediction).
- **Nearby Amenities:** Includes nearby parks, bus stops, railway stations, highways, etc.

This dataset provides a comprehensive overview of factors that potentially influence condominium prices, making it suitable for exploratory and predictive analysis.

## Technologies Used

- **Language:** R
- **Libraries:**
  - `ggplot2` for visualizations.
  - `corrplot` for correlation heatmaps.
  - `dplyr` for data manipulation.
- **Tools:** GitHub for version control and collaboration.

## Getting Started

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/YourUsername/Malaysian_Condo_Price_Analysis.git
   cd Malaysian_Condo_Price_Analysis
   ```

2. **Setup the Environment:**
   Ensure R and the required libraries are installed on your system. Use the following commands in R to install necessary packages:

   ```R
   install.packages("ggplot2")
   install.packages("corrplot")
   install.packages("dplyr")
   ```

3. **Run the Scripts:**

   - Place the dataset (`houses.csv`) in the root directory.
   - Execute the R scripts in the `/scripts` folder for data preprocessing, visualization, and analysis.

4. **View Outputs:**
   - Generated visualizations and analysis results are saved in the `/outputs` folder.

## Project Structure

```
Malaysian_Condo_Price_Analysis/
├── README.md                 # Project description and usage instructions
├── houses.csv                # Dataset (to be added by the user)
├── malasian-housing-data     # R script for data analysis
├── outputs/                  # Generated visualizations and analysis results
├── documentation            # Detailed project report and references
```

## Contributions

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Submit a pull request with a detailed description of changes.
