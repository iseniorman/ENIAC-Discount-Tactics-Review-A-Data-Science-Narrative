# ENIAC Discount Tactics Review — A Data Science Narrative
This Document Presents An Overview Of The Second Collaborative Project Completed In The Data Science & Ai Course At Wbs Coding School. In This Group Project, We Want To Analyze The Discount Strategy Eniac Used From 2017-2018 And Develop Data-Driven Recommendations To Improve Revenue To Work In Concert With Maintaining Brand Positioning.
# Summary 🔖 
This Project Involved Something Beyond Python Scripts And Seaborn Plots − Rather, It Was About Coming To Grips With A Story That Was Hidden In A Messy Set Of Real-World Data.

We Started With Four Separate Csv Files Of Information On Orders, Products, Brands, And Transaction Data Collected During Eniac’S 437-Day Operational Timeframe. This Data Was Messy In All Of Its Glory, As It Contained Inconsistent Types And Formats, Repetitions, Missing Values, And Mismatched Records That Conveyed All The Complication That Can Accompany A Business’ Data Systems.

From There, We Painstakingly Cleaned And Explored The Data To Find Evidence Of Customer Patterns, Seasonal Patterns, And An Understanding Of The Correlation Between Discounts And Revenue Generation.

We Found Evidence That Eniac Was Already Doing Well Using Discounts - €7.82m In Revenue Supported By €1.39m Invested In Its Strategy Of Using Discounts - But Still Had An Opportunity To Improve Performance.

Our Recommendation: Eniac Should Think About Using The Following Three-Legged Stool Strategy-In The Form Of The Sweet Spot Of 11-20% Discount Levels During Major Holiday Periods, With Keeping The Brand Premium Strategies Intact.
# Technologies and Tools Utilized 🔭 
* Pandas and  Python → Manipulation & Data cleaning 
* Matplotlib and Seaborn  → Data visualization &  pattern discovery
* Google Colab → Shared workspace for joint analysis
* Jupyter Notebooks → Dynamic data discovery
* Google Slides → Group presentation and narrative crafting
* Apple Keynote → Animated concluding presentation
# Explore data analysis techniques ⏳
* 437 days of transaction data (January 2017 - March 2018)
* 40,985 completed orders across 5,098 products from 177 brands
* €7.82M total revenue generated with €1.39M discount investment
* Storage products were the dominant contributor generating 36.0% of revenue (€2.81M)
* Our highest seasonal peak occurred in Q4 2017 generating €3.04M in revenue alone
  
We found that a discount of between 11% to 20% during key timeframes struck a good balance between attracting customers and making money. Larger discounts (30% and greater) generated more orders, but the overall revenue fell sharply.

# Sample Visualizations 📊
The visualizations in this project comprehensively illustrate the business narrative:
- Seasonal Trends in Revenue
- Analysis of Discount Effectiveness
- Charts on Business Performance Impacts
# Key Insights 📝 
Everything Relies On Data Quality 
The Biggest Takeaway Was That Data Preparation Took Over 60% Of Our Project Time. Real Data Isn'T Clean It Has Inconsistent Formats, Duplicate Records, Missing Values, And Inconsistencies That Wouldn'T Occur In Examples From A Textbook.

Visual Exploration Promotes Insight
Generating Plots Early In The Work Encouraged Us To Ask Better Questions And Recognize Patterns That We May Have Overlooked Had We Been Working Through The Numbers Exclusively. Graphs Became Our Guide To Follow And Take A Deeper Dive Into.

Business Context Informs Technical Decisions 
Knowing Eniac Was A Quality Tech Retailer Drove All The Technical Decisions We Made — From How We Treated Outliers In The Data To Which Discount Ranges We Wanted To Focus On In Our Recommendations.

Analytical Team Play Enhances Results 
Working With A Team Helps Provide Multiple Lenses On The Same Data, Correct Mistakes, And Reach Conclusions That Are More And Robust Than Any Analysis An Individual Could Achieve Working Alone.
# Obstacles Addressed 🔍 
-  Data Challenge Expectations
- Data inconsistency across four CSV files
- Missing product information, requiring strategic imputation decision-making
- Duplicate records with slight variations, needing careful deduplication
The date in different formats breaking analysis attempts
Balancing Depth with Clarity Getting to the point of explaining what we learned through an analysis of data to a business audience meant focusing on the actionable insights, rather than on the technical methodology itself. The "CEO presentation" compelled us to translate what is learned through data science into business strategy.

Team Coordination In Data Science Our Previous Sql Project Was Much Less Collaborative, But In This Python Analysis, We Had To Coordinate On Jupyter Notebooks, Data Processing Decisions And Merged Conclusions Of The Analysis Across Each Team Member.

# Strategic Suggestions Provided :globe_with_meridians:
1. Optimal Timing for Major Events  Offer 11-20% discounts solely during Black Friday, Christmas, and key holidays when customers anticipate larger savings.

2. Experiment and Adapt Conduct controlled tests with annual evaluations to adjust to evolving customer trends.

3. Safeguard Premium Brand  Limit discounts on Apple premium products to 0-10% to uphold ENIAC's reputation as a trusted premium tech reseller.

# Repository :alembic:  
```
eniac-discount-strategy-analysis/
├── README.md                          # This story
├── data/
│   ├── raw/                          # Original messy CSV files
│   │   ├── brands.csv
│   │   ├── orders_qu.csv
│   │   ├── products_cl.csv
│   │   └── orderlines_qu.csv
│   └── cleaned/                      # Processed and joined data
│       └── orderlines_qu.csv
|       └── orders_qu.csv
|       └── products_qu.csv
|       └── revenue_per_orders.csv
|       └── orders_avg_diff_paid_no_outliers.csv 
├── notebooks/                        # Our analytical journey
│   ├── 01_data_cleaning_with_pandas_solutions.ipynb
│   ├── 02_quality_assessment_solution.ipynb
│   └── 03_category_creation_solution.ipynb
|   └── 4_joinning_products_orders_orderlines.ipynb
|   └── 5_main_analysis.ipynb
|   └── Vennel_exploration.ipynb 
├── visualizations/ exploratory plots    # The charts that told the story
│   ├── discount_revenue_orders.png
│   ├── revenue_per_category.png
│   └── discount_revenue_time.png
├── presentation/                     # Final business presentation
│   └── ENIAC_Discount_Strategy_Analysis.pdf
└── requirements.txt                  # Python dependencies
```
