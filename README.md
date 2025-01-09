
# Supply-Demand Analysis and Forecasting with Machine Learning  

This project preprocesses and analyzes transportation data, combining region, order, weather, and points of interest (POI) datasets to generate actionable insights. By leveraging machine learning models, we forecast supply-demand gaps in specific regions and time intervals.  

## **Overview**  
The project involves consolidating datasets, performing extensive preprocessing, and building machine learning models to analyze supply-demand dynamics and optimize resource allocation.  

### **Key Datasets**  
1. **Cluster Map Data**: Region mapping using region hashes and IDs.  
2. **Order Data**: Timestamped orders, drivers, and passenger information.  
3. **Weather Data**: Timestamped weather conditions and pollution levels.  
4. **POI Data**: Points of interest in different regions.  

### **Workflow**  
1. **Data Preprocessing**:  
   - Combined order and weather data based on timestamps.  
   - Merged the resulting dataset with region mapping data and POI information.  
   - Resampled data into 10-minute intervals for time-series analysis.  
   - Created two tables: one for starting regions and another for destination regions.  

2. **Exploratory Analysis**:  
   - Analyzed weather impact on supply and demand.  
   - Grouped data by regions and timestamps to calculate supply and demand metrics.  

3. **Model Training and Testing**:  
   - Divided the dataset into training (70%) and testing (30%) sets.  
   - Trained a **Linear Regression model**, achieving 72% accuracy.  
   - Optimized performance using a **Decision Tree model**, achieving 82% accuracy.  

### **Technologies Used**  
- **Programming Language**: Python  
- **Libraries**: pandas, datetime, scikit-learn  
- **Models**: Linear Regression, Decision Tree  

### **Results**  
- **Supply and Demand Forecasting**:  
  - Calculated demand (number of orders) and supply (number of active drivers) in each region and time slot.  
  - Identified gaps (demand-supply difference) for targeted improvements.  
- **Model Performance**:  
  - Linear Regression: 72% accuracy.  
  - Decision Tree: 82% accuracy.  

### **Future Work**  
- Implement additional machine learning models to improve accuracy further.  
- Incorporate external datasets, such as traffic or real-time event data.  
- Visualize supply-demand trends using interactive dashboards.  

### **Screenshots and Graphs**  
The repository includes screenshots showcasing data preprocessing, merging steps, and model performance visualizations.  
