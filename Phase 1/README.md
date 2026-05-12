## Phase 1: Data Collection and Preprocessing

In this phase, the air quality dataset containing pollutant concentration and meteorological data was collected and prepared for analysis and model training.

### Data Collection
- Selected an air quality dataset containing:
  - PM2.5
  - PM10
  - NO₂
  - SO₂
  - CO
  - O₃
  - AQI values
  - City and Date information

### Data Preprocessing
- Handled missing values using mean imputation
- Removed records with missing AQI category and date values
- Converted date column into datetime format
- Removed unnecessary columns
- Checked dataset shape and null values

### Data Transformation
- Performed feature extraction from date column
- Applied one-hot encoding for categorical city feature
- Applied label encoding for AQI category labels
- Saved cleaned dataset for further processing

### Tools and Libraries Used
- Pandas
- NumPy
- Scikit-learn
