# Data Cleaning Project - Nashville Housing

### Project Overview

The NashvilleHousing project involves cleaning and standardizing a housing dataset by adjusting date formats, populating missing property addresses, and splitting combined address fields into separate columns. Additionally, it includes updating categorical values, removing duplicates, and eliminating unused columns to enhance data quality and usability for analysis.

### Data Sources

The primary dataset used for this project is the "Nashville Housing Data for Data Cleaning.xlsx" file, containing detailed information about residential properties in Nashville, including property addresses, sale prices, and sale dates, which is critical for performing comprehensive data cleaning and analysis.

### Tools

- Excel - Dataset  [Download Here](https://github.com/ashtamiraj/PortfolioProjects/blob/main/DataCleaning/Nashville%20Housing%20Data%20for%20Data%20Cleaning.xlsx)
- SQL Server Management Studio - Data Cleaning and Manipulation

### Data Cleaning Processes

To prepare the Nashville Housing Data for Data Cleaning.xlsx dataset for analysis, the following data cleaning processes were carried out:

#### 1. Standardized Date Format:

Converted the SaleDate field to a consistent DATE format to ensure uniformity and facilitate accurate date-based analyses.

#### 2. Populated Missing Property Addresses:

Filled in missing property addresses by referencing available data within the dataset to ensure completeness and consistency in address information using ISNULL and Self-Join.

#### 3. Separated Address Components:

Split the combined PropertyAddress field into individual columns for Address and City, using Substring and Charindex, to enhance data granularity and ease of analysis.

#### 4. Parsed Owner Address Details:

Extracted and separated the OwnerAddress into Address, City, and State columns for improved data usability and to support detailed ownership analysis.

#### 5. Updated Categorical Values:

Standardized the SoldAsVacant field by converting 'Y' and 'N' to 'Yes' and 'No' for clearer categorical representation.

 #### 6. Removed Duplicate Records:

Identified and removed duplicate entries using CTE to ensure data accuracy and integrity.

#### 7. Deleted Unused Columns:

Dropped redundant or unnecessary columns like OwnerAddress, TaxDistrict, PropertyAddress, and SaleDate to streamline the dataset and focus on relevant information.

These processes collectively enhance the quality and usability of the dataset, making it more suitable for analysis and decision-making.

