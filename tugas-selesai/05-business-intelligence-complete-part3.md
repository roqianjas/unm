## BAB IV ANALISIS CURRENT STATE

### 4.1 Business Process Analysis

#### 4.1.1 Core Business Processes LeadTalkInstitute

**1. Student Enrollment Process**
- Lead generation melalui digital marketing dan referrals
- Initial consultation dan needs assessment
- Program recommendation dan pricing presentation
- Contract signing dan payment processing
- Orientation dan program commencement

**Current Challenges:**
- Manual lead tracking dengan 30% lead loss rate
- Inconsistent follow-up processes
- Limited conversion analytics
- No predictive modeling untuk enrollment forecasting

**2. Learning Delivery Process**
- Class scheduling dan instructor assignment
- Material preparation dan distribution
- Session delivery dan student engagement tracking
- Progress assessment dan feedback collection
- Completion certification dan alumni management

**Current Challenges:**
- Limited student engagement metrics
- Manual attendance tracking
- No correlation analysis between teaching methods dan outcomes
- Insufficient instructor performance measurement

### 4.2 Data Architecture Assessment

#### 4.2.1 Current Data Landscape

**System Inventory:**
1. **Student Information System (Custom-built)**
   - Technology: PHP/MySQL
   - Data Volume: 15,000+ student records
   - Update Frequency: Real-time
   - Data Quality: 85% completeness

2. **Learning Management System (Moodle)**
   - Technology: Open-source LMS
   - Data Volume: 500+ courses, 50,000+ activities
   - Update Frequency: Real-time
   - Data Quality: 90% completeness

3. **Financial System (QuickBooks)**
   - Technology: Cloud-based accounting
   - Data Volume: 5+ years historical data
   - Update Frequency: Daily
   - Data Quality: 95% completeness

4. **Marketing Platform (Google Analytics + Facebook Ads)**
   - Technology: Third-party APIs
   - Data Volume: 2+ years campaign data
   - Update Frequency: Hourly
   - Data Quality: 80% completeness

#### 4.2.2 Data Integration Challenges

**Technical Issues:**
- No unified data model across systems
- Inconsistent customer identifiers
- Limited API connectivity
- Manual data exports untuk cross-system analysis

**Data Quality Issues:**
- 15% missing values dalam critical fields
- Inconsistent date formats across systems
- Duplicate records dengan different formatting
- Outdated contact information (25% of records)

### 4.3 Current Reporting Capabilities

#### 4.3.1 Existing Reports Analysis

**Monthly Management Reports:**
- Student enrollment summary (basic counts)
- Revenue breakdown by program
- Instructor utilization rates
- Basic marketing campaign results

**Limitations:**
- Static reports dengan no interactivity
- 2-week delay dalam report generation
- Limited drill-down capabilities
- No predictive atau trend analysis

#### 4.3.2 Decision-Making Gaps

**Strategic Planning Challenges:**
- No forecasting models untuk enrollment planning
- Limited competitor analysis integration
- Insufficient market trend correlation
- Manual scenario planning processes

**Operational Inefficiencies:**
- Reactive rather than proactive management
- Limited real-time performance monitoring
- No automated alerts untuk critical metrics
- Inconsistent KPI definitions across departments

### 4.4 Stakeholder Requirements Analysis

#### 4.4.1 Executive Management Needs

**CEO Requirements:**
- Real-time business performance dashboard
- Revenue forecasting dan growth projections
- Market opportunity identification
- Competitive positioning analysis

**CFO Requirements:**
- Financial performance monitoring
- Cost center analysis dan optimization
- Cash flow forecasting
- Profitability analysis by program/instructor

#### 4.4.2 Operational Management Needs

**Academic Director Requirements:**
- Student success metrics dan intervention triggers
- Instructor performance analytics
- Curriculum effectiveness measurement
- Resource utilization optimization

**Marketing Manager Requirements:**
- Campaign ROI analysis dan optimization
- Lead generation performance tracking
- Customer acquisition cost analysis
- Market segmentation insights

---

## BAB V PERANCANGAN SISTEM BUSINESS INTELLIGENCE

### 5.1 BI Architecture Design

#### 5.1.1 Overall System Architecture

**Data Sources Layer:**
- Student Information System (MySQL)
- Learning Management System (Moodle Database)
- Financial System (QuickBooks API)
- Marketing Platforms (Google Analytics, Facebook Ads API)
- External Data (Industry benchmarks, Economic indicators)

**Data Integration Layer:**
- **ETL Processes:** SSIS packages untuk data extraction, cleaning, transformation
- **Data Staging Area:** Temporary storage untuk data processing
- **Data Quality Rules:** Validation, standardization, deduplication procedures
- **Error Handling:** Logging, notification, dan recovery mechanisms

**Data Storage Layer:**
- **Data Warehouse:** Star schema design dengan fact dan dimension tables
- **Data Marts:** Department-specific subsets (Academic, Financial, Marketing)
- **Metadata Repository:** Data lineage, business definitions, quality metrics
- **Archive Storage:** Historical data untuk long-term trend analysis

**Analytics Layer:**
- **OLAP Cubes:** Multidimensional analysis capabilities
- **Data Mining Models:** Predictive analytics untuk student success dan churn
- **Statistical Models:** Regression analysis, correlation studies
- **Machine Learning:** Recommendation engines, forecasting algorithms

**Presentation Layer:**
- **Executive Dashboards:** High-level KPIs dan strategic metrics
- **Operational Dashboards:** Real-time monitoring untuk daily operations
- **Self-Service Analytics:** Ad-hoc reporting capabilities
- **Mobile Applications:** Responsive design untuk mobile access

#### 5.1.2 Data Model Design

**Fact Tables:**
1. **Fact_Enrollment:** Student enrollment transactions
   - Dimensions: Student, Program, Date, Instructor, Marketing_Source
   - Measures: Enrollment_Count, Revenue, Discount_Amount

2. **Fact_Learning_Activity:** Student learning interactions
   - Dimensions: Student, Course, Activity, Date, Instructor
   - Measures: Time_Spent, Completion_Status, Score, Engagement_Score

3. **Fact_Financial:** Financial transactions
   - Dimensions: Date, Account, Program, Payment_Method
   - Measures: Amount, Tax, Discount, Net_Revenue

**Dimension Tables:**
1. **Dim_Student:** Student master data
2. **Dim_Program:** Course dan program information
3. **Dim_Instructor:** Instructor profiles dan qualifications
4. **Dim_Date:** Time dimension dengan calendar attributes
5. **Dim_Geography:** Location-based analysis support

### 5.2 Dashboard Design Specifications

#### 5.2.1 Executive Dashboard

**Layout Design:**
- Header: Company logo, current date/time, refresh status
- Top Row: Key performance indicators (4 primary metrics)
- Middle Section: Trend charts dan comparative analysis
- Bottom Section: Detailed breakdowns dan drill-down options

**Key Metrics Display:**
1. **Total Revenue YTD vs. Target**
   - Visualization: Gauge chart dengan color coding
   - Drill-down: Monthly breakdown, program contribution

2. **Student Enrollment Trends**
   - Visualization: Line chart dengan 12-month rolling average
   - Filters: Program type, student segment, marketing source

3. **Customer Satisfaction Score**
   - Visualization: KPI card dengan trend indicator
   - Supporting data: Survey response rates, feedback themes

4. **Operational Efficiency Index**
   - Visualization: Composite score dengan contributing factors
   - Components: Instructor utilization, resource efficiency, process cycle times

#### 5.2.2 Academic Performance Dashboard

**Student Success Metrics:**
- Completion rates by program dan cohort
- Time-to-completion distributions
- Student satisfaction trends
- Learning outcome achievements

**Instructor Performance Analytics:**
- Student evaluation scores
- Completion rates by instructor
- Engagement metrics comparison
- Professional development tracking

**Curriculum Effectiveness Analysis:**
- Course popularity trends
- Learning objective achievement rates
- Content engagement patterns
- Resource utilization statistics

#### 5.2.3 Financial Performance Dashboard

**Revenue Analytics:**
- Monthly recurring revenue (MRR) trends
- Revenue by program/service breakdown
- Customer lifetime value analysis
- Pricing optimization insights

**Cost Management:**
- Cost per student acquisition
- Operational expense tracking
- Profitability by program
- Budget vs. actual variance analysis

**Forecasting Models:**
- Revenue projections (3, 6, 12 months)
- Cash flow forecasting
- Scenario planning capabilities
- Risk assessment indicators

### 5.3 Predictive Analytics Models

#### 5.3.1 Student Success Prediction

**Model Objective:** Identify students at risk of dropping out
**Input Variables:**
- Demographics (age, education, location)
- Engagement patterns (login frequency, assignment completion)
- Performance metrics (quiz scores, participation rates)
- External factors (economic conditions, seasonality)

**Algorithm:** Random Forest Classifier
**Expected Accuracy:** 85%+ for early intervention triggers

#### 5.3.2 Revenue Forecasting

**Model Objective:** Predict monthly revenue dengan seasonal adjustments
**Input Variables:**
- Historical enrollment patterns
- Marketing campaign effectiveness
- Economic indicators
- Competitive landscape changes

**Algorithm:** ARIMA dengan seasonal decomposition
**Expected Accuracy:** 90%+ for 3-month forecasts

#### 5.3.3 Marketing ROI Optimization

**Model Objective:** Optimize marketing spend allocation across channels
**Input Variables:**
- Channel performance history
- Customer acquisition costs
- Lifetime value by acquisition source
- Market saturation indicators

**Algorithm:** Linear programming optimization
**Expected Improvement:** 25%+ increase dalam marketing efficiency
