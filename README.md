# Employee Attrition Data Analysis Project

## Project Overview and Use Cases

This project focuses on analyzing employee attrition patterns using machine learning techniques to help organizations understand and predict employee turnover. The analysis provides valuable insights into factors that contribute to employee attrition, enabling HR departments and management teams to make data-driven decisions.

### Key Use Cases:
- **HR Analytics**: Identify key factors contributing to employee turnover
- **Predictive Modeling**: Predict which employees are likely to leave the organization
- **Strategic Planning**: Enable proactive retention strategies based on data insights
- **Cost Reduction**: Reduce recruitment and training costs by improving employee retention
- **Organizational Health**: Monitor and improve workplace satisfaction and engagement

## Tech Stack

### Data Analysis & Machine Learning:
- **Python 3.x** - Primary programming language
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computing
- **Scikit-learn** - Machine learning algorithms and tools
- **Matplotlib** - Data visualization
- **Seaborn** - Statistical data visualization
- **Plotly Express** - Interactive visualizations
- **Imbalanced-learn (SMOTE)** - Handling imbalanced datasets

### Development Environment:
- **Jupyter Notebook** - Interactive development and analysis
- **Git** - Version control

### Web Interface:
- **Vercel** - Deployment platform for web interface
- Custom GUI for model interaction

## Dataset

The project uses the **IBM HR Analytics Employee Attrition & Performance** dataset (WA_Fn-UseC_-HR-Employee-Attrition.csv), which contains comprehensive employee information including:

### Key Features:
- **Demographic Information**: Age, Gender, Marital Status
- **Job-Related Factors**: Job Role, Department, Job Level, Job Satisfaction
- **Compensation**: Monthly Income, Stock Option Level, Percent Salary Hike
- **Work Experience**: Total Working Years, Years at Company, Years in Current Role
- **Work-Life Balance**: Distance from Home, Work-Life Balance Rating
- **Performance Metrics**: Performance Rating, Training Times Last Year
- **Target Variable**: Attrition (Yes/No)

### Data Characteristics:
- No missing values in the dataset
- Removed constant value columns (EmployeeCount, Over18, StandardHours)
- Binary target variable converted to numerical format (Yes=1, No=0)

## Progress So Far

### ✅ Completed:
- **Data Exploration & Profiling**: Comprehensive analysis of dataset characteristics
- **Data Preprocessing**: 
  - Handled categorical variables with encoding
  - Applied SMOTE for addressing class imbalance
  - Feature selection using SelectKBest
  - Data standardization with StandardScaler
- **Exploratory Data Analysis**:
  - Correlation heatmaps
  - Pair plots for numerical features
  - Statistical insights and patterns identification
- **Machine Learning Models**:
  - Implemented multiple algorithms (RandomForest, Logistic Regression, SVM, etc.)
  - Hyperparameter tuning using GridSearchCV and RandomizedSearchCV
  - Model evaluation with comprehensive metrics (Accuracy, Precision, Recall, F1-Score, ROC-AUC)
- **Model Selection**: RandomForest identified as the best performing model
- **Visualization**: ROC curves and performance metrics visualization
- **Web Interface**: Deployed GUI for model interaction

### 🔄 In Progress:
- Model optimization and fine-tuning
- Advanced feature engineering
- Cross-validation improvements

## View Link

**Live Demo**: [Employee Attrition Analysis GUI](https://v0-simple-gui-design.vercel.app/)

The web interface provides an interactive way to:
- Input employee data
- Get attrition predictions
- Visualize model insights
- Explore data patterns

## Contribution

We welcome contributions to improve this project! Here's how you can contribute:

### Getting Started:
1. Fork the repository
2. Clone your fork: `git clone https://github.com/YOUR_USERNAME/DEPI_Project.git`
3. Install required dependencies: `pip install pandas numpy scikit-learn matplotlib seaborn plotly imbalanced-learn`
4. Open the Jupyter notebook: `jupyter notebook EmployeeAttritionDataAnalysis.ipynb`

### Areas for Contribution:
- **Model Improvements**: Implement new algorithms or improve existing ones
- **Feature Engineering**: Create new features or improve feature selection
- **Visualization**: Add new charts or improve existing visualizations
- **Documentation**: Improve code documentation and comments
- **Testing**: Add unit tests for model functions
- **UI/UX**: Enhance the web interface design and functionality

### Contribution Process:
1. Create a new branch for your feature: `git checkout -b feature/your-feature-name`
2. Make your changes and commit them: `git commit -m "Add your feature"`
3. Push to your branch: `git push origin feature/your-feature-name`
4. Create a Pull Request with a clear description of your changes

## License

This project is open source and available under the [MIT License](LICENSE).

---

**Note**: This project was developed as part of the DEPI (Digital Egypt Pioneers Initiative) program, focusing on practical applications of data science and machine learning in HR analytics.

For questions or support, please open an issue in the repository or contact the project maintainers.
