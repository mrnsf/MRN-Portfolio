# GitHub Repository Upload Guide

## 📋 Portfolio Organization Complete! 🎉

Your portfolio has been professionally organized and is ready for upload to `https://github.com/mrnsf/MRN-Portfolio`.

## 📁 Final Repository Structure

```
MRN-Portfolio/
├── README.md                                    # ✅ Engaging animated-style README
├── R/
│   └── NBA_Performance_Analytics/
│       ├── README.md                            # ✅ Econometric analysis documentation
│       ├── MRN_731_SUB.rmarkdown               # ✅ R Markdown source
│       ├── MRN_731_SUB.html                     # ✅ Rendered analysis
│       └── ECON_880_Exploratory_Data_Analysis_Project.zip  # ✅ Additional R work
├── Python/
│   ├── Diabetes_Classification/
│   │   ├── README.md                            # ✅ Healthcare ML documentation
│   │   └── Diabetes_Classification_Model.ipynb # ✅ Jupyter notebook
│   ├── EV_Demand_Forecasting/
│   │   ├── README.md                            # ✅ Sustainability analytics docs
│   │   └── EV_Demand_Forecasting_Model.html     # ✅ Interactive analysis
│   └── Mushroom_Classification/                 # 🔗 Already exists in repo
│       └── Mushroom Classification Final Draft Report_Python.pdf
├── SQL/
│   ├── README.md                                # ✅ Database systems documentation
│   ├── ISYS_864_Database_Systems_Final_Report.pdf      # ✅ Clean filename
│   └── ISYS_864_Database_Systems_Final_Presentation.pdf # ✅ Clean filename
├── Excel/
│   ├── README.md                                # ✅ Business analytics documentation
│   ├── Five_Guys_Pricing_Analysis_Case_Study.pdf       # ✅ Clean filename
│   ├── Chapter_14_Excel_Case_Study_Analysis.pdf        # ✅ Clean filename
│   ├── Chapter_14_Case_Study_Presentation.pdf          # ✅ Clean filename
│   ├── DS_853_Case_Study_2_Data_Science_Analysis.pdf   # ✅ Clean filename
│   └── DS_853_Case_Study_3_Data_Science_Analysis.pdf   # ✅ Clean filename
└── UPLOAD_GUIDE.md                             # 📋 This guide
```

## 🚀 Upload Instructions

### Method 1: Using Git Command Line

1. **Clone your existing repository:**
   ```bash
   git clone https://github.com/mrnsf/MRN-Portfolio.git
   cd MRN-Portfolio
   ```

2. **Copy the prepared files:**
   ```bash
   # Copy the new README
   cp "/Users/marcusnogueira/Library/Mobile Documents/com~apple~CloudDocs/gh-port/README.md" .
   
   # Copy the organized project folders
   cp -r "/Users/marcusnogueira/Library/Mobile Documents/com~apple~CloudDocs/gh-port/R" .
   cp -r "/Users/marcusnogueira/Library/Mobile Documents/com~apple~CloudDocs/gh-port/Python" .
   ```

3. **Add and commit changes:**
   ```bash
   git add .
   git commit -m "feat: Enhanced portfolio with NBA Analytics, Diabetes Classification, and EV Forecasting projects
   
   - Added comprehensive README with project highlights
   - Organized projects into R/ and Python/ directories
   - Added NBA Performance Analytics (Econometric Analysis)
   - Added Diabetes Classification Model (Healthcare ML)
   - Added EV Demand Forecasting (Sustainability Analytics)
   - Included project-specific documentation
   - Updated portfolio structure for better navigation"
   
   git push origin main
   ```

### Method 2: Using GitHub Web Interface

1. **Navigate to your repository:** https://github.com/mrnsf/MRN-Portfolio
2. **Upload files using the web interface:**
   - Click "Add file" → "Upload files"
   - Drag and drop the organized folders
   - Commit with descriptive message

## ⚠️ Important Notes

### Large File Handling
The `EV_Demand_Forecasting_Model.html` file encountered a size issue. For large files:

1. **Option 1: Use Git LFS**
   ```bash
   git lfs track "*.html"
   git add .gitattributes
   ```

2. **Option 2: Host externally**
   - Upload to your website (mrnport.xyz)
   - Link to it from the README

3. **Option 3: Compress or split**
   - Create a summary version
   - Provide download link for full version

### Portfolio Website Integration
Update your website at **mrnport.xyz** to:
- Link to the GitHub repository
- Showcase the new projects
- Provide direct links to live demos

## 🔗 Key Links to Update

1. **Main README:** Links to mrnport.xyz ✅
2. **Mushroom Classification:** Link already provided ✅
3. **Video Presentation:** Diabetes project YouTube link ✅
4. **Live Demos:** Update with actual GitHub Pages URLs

## 📊 Portfolio Highlights Added

### 🏀 NBA Performance Analytics
- **Technology:** R, Econometrics, Panel Data Analysis
- **Scope:** 67 years of NBA data (1950-2017)
- **Impact:** Rule change analysis, player efficiency insights

### 🩺 Diabetes Classification
- **Technology:** Python, Machine Learning, Healthcare Analytics
- **Scope:** Predictive modeling for diabetes risk
- **Impact:** 85%+ accuracy, clinical decision support

### 🚗 EV Demand Forecasting
- **Technology:** Python, Time Series, Sustainability Analytics
- **Scope:** Market trend analysis and policy impact
- **Impact:** Evidence-based transportation planning

## 🎯 Next Steps

1. **Upload files to GitHub** using one of the methods above
2. **Enable GitHub Pages** for live project demos
3. **Update mrnport.xyz** with new project links
4. **Add LinkedIn/social media** links to README
5. **Consider adding:**
   - License file
   - Contributing guidelines
   - Code of conduct
   - Issue templates

## 📧 Contact Information to Update

Remember to replace placeholder contact information in the README:
- LinkedIn profile URL
- Email address
- Any other social media links

---

**Your portfolio is now professionally organized and ready to showcase your data science expertise!** 🚀

The enhanced structure demonstrates your skills across multiple domains:
- **Academic Research** (NBA Analytics)
- **Healthcare Applications** (Diabetes Classification) 
- **Sustainability** (EV Forecasting)
- **Technical Diversity** (R, Python, Machine Learning, Econometrics)

This comprehensive portfolio will effectively communicate your capabilities to potential employers, collaborators, and the data science community.