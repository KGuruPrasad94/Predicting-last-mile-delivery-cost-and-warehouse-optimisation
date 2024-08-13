# Last Mile Delivery Cost and Warehouse Optimization

## Project Overview
The Last Mile Delivery Cost and Warehouse Optimization project aims to predict delivery costs and optimize warehouse operations using advanced machine learning techniques. The project involved several key steps, from data collection and cleaning to model development and warehouse optimization, with a focus on improving operational efficiency and reducing delivery costs.

## Key Steps

### 1. Data Collection and Cleaning
- **Data Sources**: Collected data from multiple sources, including customer orders, warehouse locations, and delivery distances.
- **Data Cleaning**: Performed extensive data cleaning to address inconsistencies and missing values, ensuring high-quality input for the modeling process.

### 2. Distance Calculation
- **Geodesic Distance Calculation**: Developed a function to calculate the geodesic distance between customer locations and various warehouses.
- **Nearest Warehouse Determination**: Used distance calculations to identify the nearest warehouse for each customer, optimizing delivery routes.

### 3. Feature Engineering
- **Feature Selection**: Engineered important features such as order price, delivery charges, and distances to warehouses.
- **Impact on Model Performance**: Enhanced the predictive power of the models by carefully selecting and engineering relevant features.

### 4. Model Development
- **Regression Models**: Developed and fine-tuned multiple regression models, including Linear Regression, Ridge, and Lasso, to predict delivery costs.
- **Hyperparameter Tuning**: Employed GridSearchCV for hyperparameter optimization.
- **Cross-Validation**: Applied cross-validation techniques to ensure model robustness and prevent overfitting.

### 5. Warehouse Optimization
- **Anomaly Detection**: Identified and corrected anomalies in warehouse assignments, ensuring customers were assigned to the nearest warehouses.
- **Cost Minimization**: Reassigned customers to optimize delivery routes, leading to reduced delivery costs and enhanced operational efficiency.

### 6. Visualization and Reporting
- **Data Visualizations**: Created visualizations to illustrate the findings, highlighting potential cost savings and operational improvements.
- **Reporting**: Compiled results into a comprehensive report, demonstrating significant improvements in cost savings and warehouse efficiency.

## Conclusion
This project successfully applied machine learning and data analysis techniques to address real-world logistics and supply chain challenges. By optimizing warehouse assignments and accurately predicting delivery costs, the project provided actionable insights that have the potential to significantly reduce operational costs and improve efficiency.

## Technologies Used
- **Python**: Core programming language for data processing, modeling, and analysis.
- **Pandas**: Used for data manipulation and cleaning.
- **Scikit-learn**: Utilized for model development, including regression models and hyperparameter tuning.
- **Geopy**: Employed for geodesic distance calculations.
- **Matplotlib/Seaborn**: Created data visualizations to support findings and recommendations.
- **Jupyter Notebook**: Used for developing and presenting the analysis.

## Future Enhancements
- **Advanced Optimization Techniques**: Explore more sophisticated optimization algorithms for warehouse assignment.
- **Incorporate Real-Time Data**: Integrate real-time traffic data and delivery conditions to further refine cost predictions.
- **Expand Scope**: Apply the methodology to other logistics and supply chain problems, such as inventory management and route optimization.

---
