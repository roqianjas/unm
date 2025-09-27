# RANCANGAN TUGAS MATA KULIAH
## BUSINESS INTELLIGENCE

**Universitas:** Nusa Mandiri Jakarta  
**Program Studi:** Sistem Informasi  
**Semester:** 7  
**Objek Studi:** LeadTalkInstitute (Lembaga Pelatihan Public Speaking)

---

### INFORMASI MATA KULIAH
- **Kode:** 493
- **SKS:** 4
- **Dosen:** Ridan Nurfalah, M.Kom
- **Durasi Tugas:** 9 Minggu

### TUJUAN TUGAS
Mahasiswa mampu menerapkan konsep Business Intelligence pada LeadTalkInstitute untuk mengoptimalkan pengambilan keputusan bisnis melalui analisis data, dashboard interaktif, dan sistem pelaporan yang komprehensif.

### CAPAIAN PEMBELAJARAN MATA KULIAH
CPMK043: Mampu menerapkan konsep atas pencapaian hasil kerja kelompok dan melakukan supervisi dan evaluasi terhadap penyelesaian pekerjaan yang ditugaskan kepada pekerja yang berada dibawah tanggung jawabnya. (CPL04)

### DESKRIPSI TUGAS
Mahasiswa merancang Dashboard Interaktif pada Perusahaan skala kecil kemudian menyusun ke dalam bentuk laporan dan mempresentasikan hasil diskusi pada pertemuan ke 13-15.

### METODOLOGI PENGERJAAN TUGAS

#### TAHAP 1: BUSINESS UNDERSTANDING & DATA ASSESSMENT (Minggu 1-2)

##### 1.1 Business Context Analysis (Minggu 1)
**LeadTalkInstitute Business Overview:**
- **Core Business:** Public speaking training dan coaching
- **Revenue Streams:** 
  - Individual training sessions
  - Corporate workshop packages
  - Online course subscriptions
  - Private coaching sessions
- **Key Stakeholders:** Students, instructors, corporate clients, management
- **Business Challenges:** 
  - Student retention optimization
  - Instructor performance measurement
  - Revenue forecasting accuracy
  - Marketing ROI analysis

**Key Business Questions untuk BI Solution:**
1. Bagaimana tren enrollment dan completion rate students?
2. Instructor mana yang paling efektif dalam meningkatkan student outcomes?
3. Program pelatihan mana yang memberikan ROI tertinggi?
4. Bagaimana seasonal pattern mempengaruhi business performance?
5. Apa faktor-faktor yang mempengaruhi student satisfaction dan retention?

##### 1.2 Data Sources Identification (Minggu 1-2)
**Primary Data Sources:**
- **Student Management System:**
  - Student demographics dan enrollment data
  - Course completion rates dan progress tracking
  - Assessment scores dan performance metrics
  - Feedback dan satisfaction surveys

- **Learning Management System (LMS):**
  - Course access patterns dan engagement metrics
  - Content consumption analytics
  - Assignment submission rates
  - Discussion forum participation

- **Financial System:**
  - Revenue data per program dan time period
  - Cost structure (instructor fees, material costs)
  - Payment patterns dan customer lifetime value
  - Refund rates dan reasons

- **Marketing Systems:**
  - Lead generation sources dan conversion rates
  - Campaign performance metrics
  - Social media engagement data
  - Website analytics dan user behavior

**External Data Sources:**
- Industry benchmarks dan market trends
- Economic indicators affecting training demand
- Competitor analysis data
- Social media sentiment analysis

#### TAHAP 2: DATA MODELING & WAREHOUSE DESIGN (Minggu 3-4)

##### 2.1 Dimensional Modeling (Minggu 3)
**Star Schema Design untuk LeadTalkInstitute:**

**Fact Tables:**
1. **Fact_Enrollment**
   - StudentID, CourseID, InstructorID, DateID
   - Measures: EnrollmentCount, Revenue, CompletionRate

2. **Fact_Performance**
   - StudentID, CourseID, AssessmentID, DateID
   - Measures: Score, TimeSpent, EngagementLevel

3. **Fact_Marketing**
   - CampaignID, ChannelID, DateID
   - Measures: Leads, Conversions, Cost, ROI

**Dimension Tables:**
- **Dim_Student:** Demographics, enrollment history, preferences
- **Dim_Course:** Program details, difficulty level, duration
- **Dim_Instructor:** Experience, specialization, ratings
- **Dim_Date:** Standard date dimension dengan business calendar
- **Dim_Marketing_Channel:** Online/offline channels, campaign types

##### 2.2 ETL Process Design (Minggu 3-4)
**Extract, Transform, Load Strategy:**

**Extract Phase:**
- Automated data extraction dari operational systems
- Real-time streaming untuk critical metrics
- Batch processing untuk historical data
- Data quality checks dan validation rules

**Transform Phase:**
- Data cleansing dan standardization
- Business rule application
- Calculated metrics generation
- Data type conversions dan formatting

**Load Phase:**
- Incremental loading strategies
- Data archiving procedures
- Performance optimization
- Error handling dan recovery procedures

**Technical Implementation:**
- **ETL Tools:** Talend, Pentaho, atau SSIS
- **Data Warehouse:** MySQL atau PostgreSQL
- **Scheduling:** Apache Airflow atau cron jobs

#### TAHAP 3: DASHBOARD DEVELOPMENT (Minggu 5-7)

##### 3.1 Dashboard Architecture Design (Minggu 5)
**BI Platform Selection:**
- **Primary Choice:** Tableau atau Power BI
- **Alternative:** Open source (Apache Superset, Grafana)
- **Custom Solution:** React-based dashboard dengan D3.js

**Dashboard Categories:**
1. **Executive Dashboard** - High-level KPIs untuk management
2. **Operational Dashboard** - Day-to-day metrics untuk staff
3. **Analytical Dashboard** - Deep-dive analysis untuk analysts
4. **Student Portal** - Self-service analytics untuk students

##### 3.2 Key Performance Indicators (KPIs) Definition (Minggu 5)
**Financial KPIs:**
- Revenue growth rate (monthly/quarterly)
- Average revenue per student (ARPS)
- Customer acquisition cost (CAC)
- Customer lifetime value (CLV)
- Profit margin per program

**Operational KPIs:**
- Student enrollment rate
- Course completion rate
- Student satisfaction score
- Instructor utilization rate
- Class capacity utilization

**Marketing KPIs:**
- Lead conversion rate by channel
- Marketing ROI by campaign
- Website traffic dan engagement
- Social media reach dan engagement
- Brand awareness metrics

**Academic KPIs:**
- Average assessment scores
- Skill improvement rates
- Certification completion rates
- Student progress velocity
- Learning outcome achievement

##### 3.3 Interactive Dashboard Development (Minggu 6-7)
**Executive Dashboard Components:**
- **Revenue Overview:** Monthly/quarterly revenue trends
- **Student Analytics:** Enrollment trends, demographics breakdown
- **Program Performance:** Course popularity, completion rates
- **Instructor Metrics:** Performance ratings, student feedback
- **Market Analysis:** Lead sources, conversion funnels

**Operational Dashboard Features:**
- **Real-time Metrics:** Current enrollments, active sessions
- **Resource Management:** Instructor schedules, room utilization
- **Student Support:** Help desk tickets, response times
- **Quality Monitoring:** Course ratings, feedback analysis

**Advanced Analytics Features:**
- **Predictive Analytics:** Student churn prediction, revenue forecasting
- **Cohort Analysis:** Student retention patterns
- **A/B Testing Results:** Course format effectiveness
- **Sentiment Analysis:** Student feedback sentiment trends

#### TAHAP 4: IMPLEMENTATION & OPTIMIZATION (Minggu 8-9)

##### 4.1 Dashboard Implementation (Minggu 8)
**Technical Implementation:**
- Dashboard deployment pada production environment
- User access control dan security implementation
- Performance optimization untuk fast loading
- Mobile responsiveness testing
- Integration dengan existing systems

**User Training Program:**
- Dashboard navigation training
- Key metrics interpretation guidelines
- Best practices untuk data-driven decision making
- Troubleshooting common issues
- Advanced features utilization

##### 4.2 Testing & Validation (Minggu 8-9)
**Data Accuracy Testing:**
- Source system data reconciliation
- Calculation verification untuk all metrics
- Historical data consistency checks
- Real-time data update validation

**User Acceptance Testing:**
- Stakeholder feedback collection
- Usability testing dengan actual users
- Performance benchmarking
- Security penetration testing

**Optimization Activities:**
- Query performance tuning
- Dashboard load time optimization
- User experience improvements
- Additional feature development based on feedback

### BENTUK DAN FORMAT DELIVERABLES

#### 1. LAPORAN HASIL RANCANG DASHBOARD INTERAKTIF
**Format:** Sistematika dan format sesuai dengan penulisan yang sudah ditetapkan
**Length:** 35-40 halaman

**STRUKTUR LAPORAN:**

**EXECUTIVE SUMMARY** (2 halaman)
- Project overview dan objectives
- Key findings dan insights
- Business impact dan recommendations
- Technical achievements summary

**BAB I PENDAHULUAN**
- 1.1 Latar Belakang
- 1.2 Rumusan Masalah
- 1.3 Tujuan Penelitian
- 1.4 Manfaat Penelitian
- 1.5 Batasan Penelitian
- 1.6 Sistematika Penulisan

**BAB II LANDASAN TEORI**
- 2.1 Konsep Business Intelligence
- 2.2 Dashboard Design Principles
- 2.3 Data Warehousing Concepts
- 2.4 Key Performance Indicators (KPIs)
- 2.5 Data Visualization Best Practices

**BAB III ANALISIS DAN PERANCANGAN**
- 3.1 Business Requirements Analysis
- 3.2 Data Source Analysis
- 3.3 Dimensional Modeling
- 3.4 ETL Process Design
- 3.5 Dashboard Architecture

**BAB IV IMPLEMENTASI**
- 4.1 Data Warehouse Implementation
- 4.2 ETL Process Development
- 4.3 Dashboard Development Process
- 4.4 Testing dan Validation Results
- 4.5 Performance Optimization

**BAB V HASIL DAN PEMBAHASAN**
- 5.1 Dashboard Features Overview
- 5.2 Key Insights dari Data Analysis
- 5.3 Business Impact Analysis
- 5.4 User Feedback dan Acceptance
- 5.5 Performance Metrics Achievement

**BAB VI PENUTUP**
- 6.1 Kesimpulan
- 6.2 Saran untuk Pengembangan Selanjutnya
- 6.3 Keterbatasan dan Lessons Learned

#### 2. SLIDE PRESENTASI POWERPOINT
**Format:** Professional presentation template
**Duration:** 25 menit presentasi + 15 menit Q&A

**Presentation Outline:**
1. **Introduction & Business Context** (3 slides)
2. **Data Analysis & Insights** (4 slides)
3. **Dashboard Demo** (6 slides - interactive demonstration)
4. **Business Impact & ROI** (3 slides)
5. **Implementation Challenges & Solutions** (2 slides)
6. **Future Recommendations** (2 slides)

#### 3. LAPORAN HASIL RANCANG DASHBOARD INTERAKTIF MENGGUNAKAN TABLEAU
**Technical Deliverable:**
- **Tableau Workbook (.twbx file)** dengan complete data sources
- **Published Dashboard** pada Tableau Public atau Server
- **User Guide** untuk dashboard navigation
- **Technical Documentation** untuk maintenance

**Dashboard Components:**
- **Executive Summary Dashboard**
- **Student Analytics Dashboard**
- **Financial Performance Dashboard**
- **Marketing Analytics Dashboard**
- **Operational Metrics Dashboard**

### SPESIFIKASI TEKNIS

#### Dashboard Requirements:
- **Responsiveness:** Compatible dengan desktop, tablet, mobile
- **Performance:** Load time < 3 seconds untuk all dashboards
- **Interactivity:** Drill-down, filtering, cross-filtering capabilities
- **Real-time Updates:** Automated data refresh setiap 15 menit
- **Export Features:** PDF reports, Excel exports, image downloads

#### Data Requirements:
- **Data Volume:** Handle minimum 10,000 student records
- **Historical Data:** 3 years of historical performance data
- **Real-time Metrics:** Current enrollment, active sessions
- **Data Quality:** 99% accuracy dengan automated validation

#### Technical Specifications:
- **Font:** Arial atau Helvetica untuk optimal readability
- **Color Scheme:** Corporate colors dengan accessibility compliance
- **Charts:** Interactive dengan hover tooltips dan legends
- **Navigation:** Intuitive menu structure dengan breadcrumbs

### PENILAIAN DAN KRITERIA

#### A. KETEPATAN WAKTU PENGUMPULAN LAPORAN (20%)
- **Excellent (18-20):** Submitted 1+ days early
- **Good (14-17):** Submitted on time
- **Fair (10-13):** 1-2 days late
- **Poor (0-9):** >2 days late

#### B. LAPORAN PENELITIAN (30%)

1. **Business Analysis Quality (10%)**
   - Depth of business understanding
   - Relevance of research questions
   - Quality of requirements gathering
   - Stakeholder analysis completeness

2. **Technical Implementation (15%)**
   - Data modeling accuracy
   - ETL process efficiency
   - Dashboard functionality
   - Technical documentation quality

3. **Data Analysis & Insights (5%)**
   - Quality of data analysis
   - Actionable insights generation
   - Business impact quantification
   - Recommendation practicality

#### C. PENYUSUNAN SLIDE PRESENTASI (20%)
- **Visual Design (8%):** Professional aesthetics, consistent branding
- **Content Structure (7%):** Logical flow, clear messaging
- **Technical Accuracy (5%):** Correct information, proper terminology

#### D. PRESENTASI (30%)
- **Dashboard Demonstration (15%):** Live demo effectiveness, interactivity showcase
- **Business Storytelling (10%):** Data narrative, insight communication
- **Q&A Performance (5%):** Technical knowledge, professional responses

### JADWAL PELAKSANAAN DETAIL

#### Minggu 1-2: Foundation & Planning
**Week 1:**
- Day 1-2: Business requirements gathering
- Day 3-4: Data source identification dan assessment
- Day 5-7: KPI definition dan success metrics

**Week 2:**
- Day 1-3: Data quality assessment
- Day 4-5: Technical architecture planning
- Day 6-7: Project timeline finalization

#### Minggu 3-4: Data Architecture
**Week 3:**
- Day 1-3: Dimensional model design
- Day 4-5: ETL process specification
- Day 6-7: Data warehouse schema creation

**Week 4:**
- Day 1-3: ETL development dan testing
- Day 4-5: Data warehouse population
- Day 6-7: Data validation dan quality checks

#### Minggu 5-7: Dashboard Development
**Week 5:**
- Day 1-2: Dashboard wireframe design
- Day 3-4: Tableau workspace setup
- Day 5-7: Executive dashboard development

**Week 6:**
- Day 1-3: Operational dashboard creation
- Day 4-5: Analytics dashboard development
- Day 6-7: Interactive features implementation

**Week 7:**
- Day 1-3: Dashboard integration dan testing
- Day 4-5: Performance optimization
- Day 6-7: User acceptance testing

#### Minggu 8-9: Finalization & Presentation
**Week 8:**
- Day 1-3: Documentation completion
- Day 4-5: Final testing dan bug fixes
- Day 6-7: Presentation preparation

**Week 9:**
- Day 1-2: Final report writing
- Day 3-4: Presentation rehearsal
- Day 5-7: Final submission dan presentation delivery

### RESOURCES & TOOLS

#### Software Requirements:
- **BI Platform:** Tableau Desktop/Public (preferred) atau Power BI
- **Database:** MySQL, PostgreSQL, atau SQL Server
- **ETL Tools:** Talend Open Studio, Pentaho, or custom scripts
- **Development:** Python (pandas, numpy) untuk data processing

#### Data Sources (Simulated):
- **Student Database:** 1,000+ student records dengan demographics
- **Course Data:** 50+ courses dengan enrollment dan completion data
- **Financial Data:** 3 years of revenue dan cost information
- **Marketing Data:** Campaign performance dari multiple channels

#### Reference Materials:
1. P.Antonius, S.M.Gede, dkk. BUSINESS INTELEGENT (Pengantar Business Intelligence dalam Bisnis). Jambi: PT. Sonpedia Publishing Indonesia. 2023
2. RH. Valentinus. Buku Ajar Kecerdasan Bisnis. Surabaya: Institut Bisnis Dan Informatika Stikom.2017

#### Online Resources:
- Tableau learning resources dan tutorials
- Business Intelligence best practices guides
- Data visualization design principles
- Industry benchmarking reports

### SUCCESS TIPS & BEST PRACTICES

#### Dashboard Design Excellence:
1. **Know Your Audience** - Design for specific user needs
2. **Keep It Simple** - Avoid chart junk dan unnecessary complexity
3. **Tell a Story** - Create logical flow dari data ke insights
4. **Use Color Purposefully** - Consistent color scheme dengan meaning
5. **Enable Interaction** - Drill-down capabilities untuk deeper analysis

#### Technical Implementation:
1. **Plan Data Architecture** - Solid foundation untuk scalability
2. **Optimize Performance** - Fast loading times essential
3. **Ensure Data Quality** - Garbage in, garbage out principle
4. **Document Everything** - Future maintenance dan updates
5. **Test Thoroughly** - Multiple scenarios dan edge cases

#### Business Value Creation:
1. **Focus on Actionable Insights** - Data yang dapat ditindaklanjuti
2. **Quantify Business Impact** - ROI dan performance improvements
3. **Engage Stakeholders** - Regular feedback dan iteration
4. **Plan for Adoption** - User training dan change management
5. **Measure Success** - KPIs untuk BI system effectiveness

---
*Tugas ini dirancang untuk memberikan pengalaman komprehensif dalam Business Intelligence implementation, dari business understanding hingga dashboard deployment, menggunakan LeadTalkInstitute sebagai realistic case study.*
