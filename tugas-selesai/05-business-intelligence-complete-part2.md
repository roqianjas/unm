## BAB II LANDASAN TEORI

### 2.1 Konsep Business Intelligence

Business Intelligence (BI) adalah teknologi dan strategi yang digunakan enterprises untuk menganalisis data bisnis dan menyajikan actionable information untuk membantu executives, managers, dan workers dalam pengambilan keputusan yang informed (Turban et al., 2021).

**Komponen Utama BI:**
1. **Data Warehousing:** Central repository untuk integrated business data
2. **Data Mining:** Pattern discovery dan predictive analytics
3. **OLAP (Online Analytical Processing):** Multidimensional data analysis
4. **Reporting Tools:** Automated report generation dan distribution
5. **Dashboards:** Visual representation dari key metrics dan KPIs

### 2.2 Framework Business Intelligence

#### 2.2.1 BI Architecture Components

**Data Layer:**
- **Operational Systems:** Transactional databases (OLTP)
- **Data Staging Area:** ETL processes untuk data cleaning dan transformation
- **Data Warehouse:** Integrated, historical, subject-oriented data repository
- **Data Marts:** Departmental subsets dari data warehouse

**Analytics Layer:**
- **OLAP Cubes:** Multidimensional data structures
- **Data Mining Models:** Machine learning algorithms untuk pattern recognition
- **Statistical Analysis:** Descriptive dan inferential statistics

**Presentation Layer:**
- **Interactive Dashboards:** Real-time metrics visualization
- **Ad-hoc Reports:** Self-service query dan reporting
- **Mobile BI:** Responsive analytics untuk mobile devices

#### 2.2.2 BI Maturity Models

**Gartner's BI Maturity Model:**
- **Level 1:** Spreadsheets dan basic reporting
- **Level 2:** Standardized reporting dan basic analytics
- **Level 3:** Advanced analytics dan self-service BI
- **Level 4:** Predictive analytics dan machine learning
- **Level 5:** Prescriptive analytics dan autonomous decision-making

### 2.3 Key Performance Indicators (KPIs) untuk Educational Institutions

#### 2.3.1 Student-Centric Metrics
- **Enrollment Rate:** New student acquisitions per period
- **Completion Rate:** Percentage students completing programs
- **Student Satisfaction Score:** Net Promoter Score (NPS) analysis
- **Time-to-Completion:** Average program duration per student
- **Retention Rate:** Student continuation across program levels

#### 2.3.2 Financial Performance Metrics
- **Revenue per Student:** Average revenue generated per enrolled student
- **Cost per Acquisition (CPA):** Marketing spend divided by new enrollments
- **Lifetime Value (LTV):** Total revenue expected from student relationship
- **Profit Margin by Program:** Program-specific profitability analysis
- **Cash Flow Projections:** Monthly revenue dan expense forecasting

#### 2.3.3 Operational Excellence Metrics
- **Instructor Utilization Rate:** Teaching hours vs. available capacity
- **Resource Efficiency:** Classroom dan equipment utilization
- **Process Cycle Time:** Administrative processes speed
- **Quality Metrics:** Error rates dalam administrative processes

### 2.4 Dashboard Design Principles

#### 2.4.1 Visual Design Best Practices
- **Information Density:** Optimal data-ink ratio untuk clarity
- **Color Psychology:** Strategic use of colors untuk data interpretation
- **Layout Hierarchy:** Logical flow dari most important to supporting metrics
- **Interactive Elements:** Drill-down capabilities dan filtering options

#### 2.4.2 User Experience (UX) Considerations
- **Role-Based Access:** Customized views untuk different user types
- **Mobile Responsiveness:** Cross-device compatibility
- **Performance Optimization:** <3 second load times
- **Intuitive Navigation:** Self-explanatory interface design

---

## BAB III METODOLOGI PENELITIAN

### 3.1 Pendekatan Penelitian

Penelitian ini menggunakan **Design Science Research Methodology (DSRM)** yang dikombinasikan dengan **Agile BI development approach** untuk memastikan iterative improvement dan stakeholder validation throughout implementation process.

**Research Framework:**
1. **Problem Identification & Motivation**
2. **Define Objectives of Solution**
3. **Design & Development**
4. **Demonstration**
5. **Evaluation**
6. **Communication**

### 3.2 Metodologi Pengembangan BI

#### 3.2.1 Kimball Methodology untuk Data Warehousing

**Phase 1: Business Requirements Definition**
- Stakeholder interviews dan requirements gathering
- Business process identification dan prioritization
- KPI definition dan success metrics establishment

**Phase 2: Dimensional Modeling**
- Fact table design untuk measurable business events
- Dimension table creation untuk descriptive context
- Star schema implementation untuk optimal query performance

**Phase 3: Physical Design**
- Database schema creation dengan indexing strategy
- ETL process design untuk data integration
- Security implementation dengan role-based access control

**Phase 4: BI Application Development**
- Dashboard creation dengan interactive visualizations
- Report development untuk automated distribution
- User training dan documentation creation

#### 3.2.2 Agile BI Implementation

**Sprint Planning (2-week iterations):**
- **Sprint 1-2:** Data source analysis dan ETL development
- **Sprint 3-4:** Core dashboard development dan testing
- **Sprint 5-6:** Advanced analytics dan predictive modeling
- **Sprint 7-8:** User acceptance testing dan refinement
- **Sprint 9:** Production deployment dan training

### 3.3 Data Collection Methods

#### 3.3.1 Primary Data Sources
**Internal Systems:**
- Student Information System (SIS): Enrollment, grades, attendance
- Learning Management System (LMS): Course engagement, completion rates
- Customer Relationship Management (CRM): Lead tracking, communication history
- Financial System: Revenue, expenses, payment status
- Marketing Platforms: Campaign performance, lead generation

#### 3.3.2 Data Quality Assessment
**Data Profiling Activities:**
- Completeness analysis: Missing values identification
- Accuracy verification: Data validation against business rules
- Consistency checking: Format standardization across systems
- Timeliness evaluation: Data freshness dan update frequency

### 3.4 Technology Stack

#### 3.4.1 BI Platform Selection
**Microsoft Power BI** dipilih sebagai primary BI tool berdasarkan:
- Cost-effectiveness untuk small-medium organizations
- Integration capabilities dengan Microsoft ecosystem
- User-friendly interface untuk self-service analytics
- Scalability untuk future growth requirements

#### 3.4.2 Supporting Technologies
- **Database:** SQL Server untuk data warehouse
- **ETL Tools:** SSIS (SQL Server Integration Services)
- **Cloud Platform:** Azure untuk scalable deployment
- **Security:** Active Directory integration untuk user management

### 3.5 Evaluation Metrics

#### 3.5.1 Technical Performance
- **System Response Time:** <3 seconds untuk dashboard loads
- **Data Accuracy:** >95% accuracy rate untuk critical metrics
- **System Availability:** 99.5% uptime requirement
- **User Adoption Rate:** 80% active usage within 3 months

#### 3.5.2 Business Value Metrics
- **Decision-Making Speed:** 50% reduction dalam decision cycle time
- **Report Generation Efficiency:** 70% reduction dalam manual reporting
- **Actionable Insights:** 5+ strategic recommendations per month
- **ROI Achievement:** Positive ROI within 12 months
