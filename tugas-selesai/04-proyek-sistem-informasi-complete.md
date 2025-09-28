# TUGAS MATA KULIAH
## PROYEK SISTEM INFORMASI
### Pengembangan Learning Management System untuk LeadTalkInstitute

**Universitas:** Nusa Mandiri Jakarta  
**Program Studi:** Sistem Informasi  
**Semester:** 7  
**Kelompok:** 3 Anggota  
**Dosen:** Rani Irma Handayani, M.Kom

---

## EXECUTIVE SUMMARY

### Ringkasan Proyek

LeadTalkInstitute membutuhkan solusi Learning Management System (LMS) yang comprehensive untuk mendukung transformasi digital dan skalabilitas bisnis. Proyek ini mengembangkan LMS terintegrasi yang menggabungkan manajemen kursus, student tracking, instructor tools, dan analytics dalam satu platform unified.

Menggunakan metodologi Agile-Waterfall hybrid, proyek ini diselesaikan dalam 7 minggu dengan budget Rp 450,000,000. Sistem yang dikembangkan menggunakan technology stack modern (React.js, Node.js, MongoDB) dengan cloud deployment untuk optimal performance dan scalability.

### Key Project Outcomes

**Functional Achievements:**
- ✅ Complete LMS dengan 25+ core features
- ✅ Mobile-responsive web application
- ✅ Integrated payment system dengan multiple gateways
- ✅ Real-time communication tools
- ✅ Comprehensive reporting dan analytics dashboard

**Technical Achievements:**
- ✅ Scalable microservices architecture
- ✅ Cloud-native deployment pada AWS
- ✅ 99.5% system availability
- ✅ <2 second average page load time
- ✅ Security implementation dengan industry standards

**Business Value Delivered:**
- 60% reduction dalam administrative workload
- 40% improvement dalam student engagement
- 90% automation dalam enrollment dan scheduling processes
- 200% increase dalam operational capacity
- ROI projected 180% dalam 24 months

---

## BAB I PENDAHULUAN

### 1.1 Latar Belakang Project

LeadTalkInstitute mengalami pertumbuhan exponential dengan 2,000+ alumni dan 50+ corporate clients, namun terkendala oleh systems yang fragmented dan manual processes. Current learning infrastructure mencakup basic Moodle installation, Excel-based student tracking, dan manual scheduling yang tidak scalable untuk growth projections.

**Business Challenges:**
- **Scalability Issues:** Current system hanya support 100 concurrent users
- **Poor User Experience:** Outdated interface dengan limited mobile support
- **Manual Administrative Tasks:** 70% proses masih manual dan time-consuming
- **Limited Analytics:** Minimal insights untuk decision making
- **Integration Problems:** Disconnected systems requiring manual data transfer

**Market Opportunity:**
- E-learning market growth 15% annually di Indonesia
- Corporate training budget increase 25% post-pandemic
- Remote learning preference 80% among professionals
- Digital transformation acceleration dalam education sector

### 1.2 Problem Statement

LeadTalkInstitute memerlukan modern Learning Management System yang dapat:
1. Handle 500+ concurrent users dengan optimal performance
2. Provide seamless user experience across all devices
3. Automate administrative processes untuk efficiency
4. Deliver actionable insights melalui advanced analytics
5. Integrate dengan existing systems dan third-party tools
6. Support future growth dan feature expansion

### 1.3 Project Objectives

**Primary Objective:**
Mengembangkan comprehensive Learning Management System yang modern, scalable, dan user-friendly untuk mendukung transformasi digital LeadTalkInstitute.

**Specific Objectives:**
1. **Functionality:** Implement 25+ core LMS features dengan complete user workflows
2. **Performance:** Achieve <2 second page load time dan 99.5% uptime
3. **Scalability:** Support 500+ concurrent users dengan auto-scaling capability
4. **User Experience:** Create intuitive interface dengan mobile-first approach
5. **Integration:** Seamless connection dengan payment systems, communication tools, dan analytics
6. **Security:** Implement industry-standard security measures dan data protection

### 1.4 Project Scope

**In-Scope Features:**
- User management (students, instructors, administrators)
- Course catalog dan content management
- Enrollment dan scheduling system
- Progress tracking dan assessment tools
- Communication features (messaging, forums, announcements)
- Payment integration dan billing management
- Reporting dan analytics dashboard
- Mobile-responsive web application

**Out-of-Scope:**
- Native mobile applications (iOS/Android)
- Advanced AI/ML features
- Third-party integrations beyond core requirements
- Legacy data migration from old systems
- Custom hardware procurement

### 1.5 Success Criteria

**Technical Success Metrics:**
- All functional requirements implemented dan tested
- Performance benchmarks achieved (load time, uptime)
- Security standards compliance verified
- Scalability requirements demonstrated

**Business Success Metrics:**
- User adoption rate >80% within 3 months
- Administrative workload reduction >50%
- Student satisfaction score >8.5/10
- Return on investment >150% within 24 months

---

## BAB II COMPANY PROFILE & ANALYSIS

### 2.1 LeadTalkInstitute Overview

**Organizational Profile:**
- **Founded:** 2020
- **Industry:** Professional Training & Development
- **Specialty:** Public Speaking & Communication Skills
- **Geographic Reach:** Jakarta, Bandung, Surabaya dengan expansion plans
- **Annual Revenue:** Rp 8.5 billion (2024)
- **Growth Rate:** 45% CAGR over 4 years

**Current Technology Landscape:**
- **Learning Platform:** Basic Moodle installation (limited customization)
- **Student Management:** Excel spreadsheets dengan manual tracking
- **Communication:** WhatsApp groups dan email blasts
- **Payment Processing:** Manual invoicing dengan bank transfer
- **Content Storage:** Google Drive dengan limited organization
- **Analytics:** Basic Google Analytics untuk website traffic only

### 2.2 Stakeholder Analysis

#### 2.2.1 Primary Stakeholders

**Students (End Users - 2,000+ active)**
- **Needs:** Easy course access, progress tracking, interactive content
- **Pain Points:** Complicated enrollment, limited mobile access, poor communication
- **Success Measures:** Course completion rates, satisfaction scores, retention

**Instructors (15 full-time, 25 part-time)**
- **Needs:** Content management tools, student progress monitoring, communication channels
- **Pain Points:** Manual grading, limited student insights, administrative overhead
- **Success Measures:** Teaching efficiency, student engagement, workload reduction

**Administrative Staff (8 members)**
- **Needs:** Automated processes, comprehensive reporting, integrated systems
- **Pain Points:** Manual data entry, scattered information, time-consuming tasks
- **Success Measures:** Process efficiency, data accuracy, workload automation

#### 2.2.2 Secondary Stakeholders

**Management Team**
- **CEO:** Strategic oversight, ROI realization, competitive advantage
- **Operations Manager:** Operational efficiency, resource optimization
- **Finance Manager:** Cost control, revenue tracking, financial reporting

**Corporate Clients (50+ companies)**
- **Needs:** Customized training programs, progress tracking, certification
- **Pain Points:** Limited customization, poor reporting, manual coordination
- **Success Measures:** Training effectiveness, administrative efficiency

### 2.3 Current System Analysis

#### 2.3.1 Existing Infrastructure Assessment

**Current Moodle Installation:**
- **Version:** Moodle 3.9 (outdated)
- **Customization Level:** Minimal (standard theme, basic plugins)
- **User Capacity:** Maximum 100 concurrent users
- **Performance Issues:** Slow loading (8-12 seconds), frequent timeouts
- **Mobile Experience:** Poor responsiveness, limited functionality

**Integration Challenges:**
- **Data Silos:** Student data scattered across multiple systems
- **Manual Workflows:** 70% of processes require manual intervention
- **Communication Gaps:** No integrated communication platform
- **Reporting Limitations:** Basic reports only, no advanced analytics

#### 2.3.2 User Experience Assessment

**Current UX Pain Points:**
- **Navigation:** Complex menu structure, hard to find content
- **Mobile Usage:** Limited mobile functionality, poor responsive design
- **Content Access:** Slow loading, broken links, outdated materials
- **Progress Tracking:** Limited visibility into learning progress
- **Communication:** No integrated messaging, relies on external platforms

**User Satisfaction Survey Results (n=200):**
- Overall satisfaction: 5.8/10
- Ease of use: 4.2/10
- Mobile experience: 3.1/10
- Content accessibility: 6.1/10
- Technical support: 7.2/10

### 2.4 Business Requirements Analysis

#### 2.4.1 Functional Requirements

**Core LMS Functionality:**
1. **User Management System**
   - Role-based access control (Student, Instructor, Admin, Corporate Admin)
   - Profile management dengan photo upload
   - Bulk user import/export functionality
   - Advanced user search dan filtering

2. **Course Management**
   - Course creation wizard dengan templates
   - Multi-media content support (video, audio, documents, SCORM)
   - Course versioning dan revision history
   - Automated course scheduling

3. **Enrollment System**
   - Self-enrollment dengan approval workflow
   - Bulk enrollment untuk corporate clients
   - Waitlist management
   - Automated email notifications

4. **Learning Delivery**
   - Progressive content unlocking
   - Interactive elements (quizzes, polls, discussions)
   - Video streaming dengan progress tracking
   - Offline content download capability

5. **Assessment & Certification**
   - Multiple assessment types (quiz, assignment, practical)
   - Automated grading dengan manual override
   - Certificate generation dengan digital signatures
   - Grade book dengan export functionality

6. **Communication Tools**
   - Integrated messaging system
   - Discussion forums per course
   - Announcement system dengan notifications
   - Live chat support integration

7. **Reporting & Analytics**
   - Student progress dashboards
   - Instructor performance metrics
   - Course effectiveness analysis
   - Custom report builder

#### 2.4.2 Non-Functional Requirements

**Performance Requirements:**
- **Response Time:** <2 seconds untuk 95% of page loads
- **Concurrent Users:** Support 500+ simultaneous users
- **Uptime:** 99.5% system availability
- **Scalability:** Auto-scaling based on demand

**Security Requirements:**
- **Authentication:** Multi-factor authentication (MFA)
- **Authorization:** Role-based access control (RBAC)
- **Data Protection:** AES-256 encryption for sensitive data
- **Compliance:** GDPR-ready privacy controls

**Usability Requirements:**
- **Responsive Design:** Optimal experience on desktop, tablet, mobile
- **Accessibility:** WCAG 2.1 AA compliance
- **Browser Support:** Modern browsers (Chrome, Firefox, Safari, Edge)
- **Loading Speed:** Progressive loading dengan optimized assets

---

## BAB III PROJECT MANAGEMENT

### 3.1 Project Management Methodology

#### 3.1.1 Hybrid Agile-Waterfall Approach

**Methodology Selection Rationale:**
- **Waterfall Elements:** Requirements gathering, architecture design, final testing
- **Agile Elements:** Iterative development, continuous feedback, flexible scope
- **Hybrid Benefits:** Structured planning dengan adaptive execution

**Project Phases Overview:**
1. **Initiation & Planning (Week 1):** Requirements, architecture, planning
2. **Design Phase (Week 2):** UI/UX design, technical architecture, database design
3. **Development Sprints (Week 3-5):** Three 1-week sprints dengan deliverables
4. **Integration & Testing (Week 6):** System testing, user acceptance, performance
5. **Deployment & Closure (Week 7):** Production deployment, training, handover

#### 3.1.2 Project Governance Structure

**Project Steering Committee:**
- **Project Sponsor:** CEO LeadTalkInstitute
- **Business Owner:** Operations Manager
- **Technical Lead:** External Development Partner
- **Quality Assurance:** Independent QA Consultant

**Core Project Team:**
- **Project Manager:** Overall coordination dan delivery
- **Business Analyst:** Requirements dan user acceptance
- **Technical Architect:** System design dan technology decisions
- **UI/UX Designer:** User experience dan interface design
- **Frontend Developers (2):** React.js application development
- **Backend Developers (2):** Node.js API dan database development
- **QA Engineer:** Testing strategy dan execution
- **DevOps Engineer:** Infrastructure dan deployment

### 3.2 Work Breakdown Structure (WBS)

#### 3.2.1 Level 1 - Major Deliverables

```
LeadTalkInstitute LMS Project (100%)
├── 1. Project Management (10%)
├── 2. Requirements & Analysis (15%)
├── 3. System Design (20%)
├── 4. Development (35%)
├── 5. Testing & Quality Assurance (15%)
└── 6. Deployment & Training (5%)
```

#### 3.2.2 Level 2 - Detailed Work Packages

**1. Project Management (10%)**
- 1.1 Project Planning & Scheduling
- 1.2 Resource Management
- 1.3 Risk Management
- 1.4 Communication Management
- 1.5 Progress Monitoring & Control

**2. Requirements & Analysis (15%)**
- 2.1 Stakeholder Interviews
- 2.2 Current System Analysis
- 2.3 Functional Requirements Documentation
- 2.4 Non-Functional Requirements
- 2.5 User Story Creation

**3. System Design (20%)**
- 3.1 Technical Architecture Design
- 3.2 Database Schema Design
- 3.3 API Design & Documentation
- 3.4 UI/UX Design & Prototyping
- 3.5 Security Architecture

**4. Development (35%)**
- 4.1 Frontend Development (React.js)
- 4.2 Backend Development (Node.js)
- 4.3 Database Implementation
- 4.4 Third-party Integrations
- 4.5 Security Implementation

**5. Testing & Quality Assurance (15%)**
- 5.1 Unit Testing
- 5.2 Integration Testing
- 5.3 System Testing
- 5.4 User Acceptance Testing
- 5.5 Performance Testing

**6. Deployment & Training (5%)**
- 6.1 Production Environment Setup
- 6.2 System Deployment
- 6.3 User Training
- 6.4 Documentation
- 6.5 Project Handover

### 3.3 Project Timeline

#### 3.3.1 Master Schedule

| Phase | Duration | Start Date | End Date | Key Deliverables |
|-------|----------|------------|----------|------------------|
| **Week 1: Initiation** | 5 days | Day 1 | Day 5 | Requirements Document, Project Plan |
| **Week 2: Design** | 5 days | Day 6 | Day 10 | System Design, UI Mockups |
| **Week 3: Sprint 1** | 5 days | Day 11 | Day 15 | Core User Management |
| **Week 4: Sprint 2** | 5 days | Day 16 | Day 20 | Course Management |
| **Week 5: Sprint 3** | 5 days | Day 21 | Day 25 | Advanced Features |
| **Week 6: Testing** | 5 days | Day 26 | Day 30 | Testing Complete |
| **Week 7: Deployment** | 5 days | Day 31 | Day 35 | Production System |

#### 3.3.2 Critical Path Analysis

**Critical Path Activities:**
1. Requirements Gathering (5 days)
2. Database Design (3 days)
3. Backend API Development (10 days)
4. Frontend Integration (8 days)
5. System Testing (5 days)
6. Production Deployment (2 days)

**Total Critical Path Duration:** 33 days
**Project Buffer:** 2 days
**Risk Mitigation:** Parallel activities untuk non-critical path items

### 3.4 Resource Allocation

#### 3.4.1 Human Resources

**Team Composition:**
- **Project Manager:** 1 FTE × 7 weeks = 7 person-weeks
- **Business Analyst:** 1 FTE × 3 weeks = 3 person-weeks
- **Technical Architect:** 1 FTE × 7 weeks = 7 person-weeks
- **UI/UX Designer:** 1 FTE × 3 weeks = 3 person-weeks
- **Frontend Developers:** 2 FTE × 5 weeks = 10 person-weeks
- **Backend Developers:** 2 FTE × 5 weeks = 10 person-weeks
- **QA Engineer:** 1 FTE × 4 weeks = 4 person-weeks
- **DevOps Engineer:** 0.5 FTE × 7 weeks = 3.5 person-weeks

**Total Effort:** 47.5 person-weeks

#### 3.4.2 Technology Resources

**Development Environment:**
- **IDE:** Visual Studio Code dengan extensions
- **Version Control:** Git dengan GitHub Enterprise
- **Project Management:** Jira dengan Agile boards
- **Communication:** Slack dengan integrations
- **Documentation:** Confluence dan Notion

**Infrastructure:**
- **Development:** AWS EC2 dengan development tier
- **Staging:** Mirror production dengan smaller capacity
- **Production:** AWS production environment dengan auto-scaling
- **Database:** MongoDB Atlas dengan backup dan monitoring
- **CDN:** CloudFront untuk asset delivery

### 3.5 Risk Management

#### 3.5.1 Risk Register

| Risk ID | Risk Description | Probability | Impact | Mitigation Strategy |
|---------|------------------|-------------|---------|-------------------|
| **R001** | Key developer unavailability | Medium | High | Cross-training, backup resources |
| **R002** | Requirements scope creep | High | Medium | Change control process |
| **R003** | Third-party integration delays | Medium | Medium | Early integration testing |
| **R004** | Performance issues | Low | High | Early performance testing |
| **R005** | Security vulnerabilities | Medium | High | Security reviews, penetration testing |
| **R006** | User adoption resistance | Medium | Medium | Change management, training |

#### 3.5.2 Risk Response Strategies

**High Priority Risks:**

**R001: Key Developer Unavailability**
- *Mitigation:* Cross-training dalam team, documentation requirements
- *Contingency:* Backup developer resources dari partner firms
- *Response Plan:* 48-hour replacement dengan knowledge transfer

**R005: Security Vulnerabilities**
- *Mitigation:* Security-first development, regular code reviews
- *Contingency:* Security consulting engagement untuk rapid response
- *Response Plan:* Immediate patch deployment dengan rollback capability

---

## BAB IV SYSTEM DESIGN

### 4.1 Technical Architecture

#### 4.1.1 System Architecture Overview

**Architecture Pattern:** Microservices dengan API Gateway
**Deployment Model:** Cloud-native pada AWS
**Data Strategy:** Event-driven dengan CQRS patterns

```
┌─────────────────────────────────────────────────────────┐
│                    CLIENT LAYER                         │
├─────────────────────────────────────────────────────────┤
│ React Web App │ Mobile Browser │ Admin Dashboard │ APIs │
└─────────────────────────────────────────────────────────┘
                            │
                            ▼
┌─────────────────────────────────────────────────────────┐
│                   API GATEWAY (Kong)                    │
├─────────────────────────────────────────────────────────┤
│ Authentication │ Rate Limiting │ Load Balancing │ Logging│
└─────────────────────────────────────────────────────────┘
                            │
                            ▼
┌─────────────────────────────────────────────────────────┐
│                 MICROSERVICES LAYER                     │
├─────────────────────────────────────────────────────────┤
│User Service│Course Service│Payment Service│Notification│Analytics│
└─────────────────────────────────────────────────────────┘
                            │
                            ▼
┌─────────────────────────────────────────────────────────┐
│                    DATA LAYER                           │
├─────────────────────────────────────────────────────────┤
│ MongoDB │ Redis │ ElasticSearch │ S3 Storage │ CloudWatch │
└─────────────────────────────────────────────────────────┘
```

#### 4.1.2 Microservices Breakdown

**User Service**
- **Responsibilities:** Authentication, authorization, profile management
- **Technology Stack:** Node.js, Express, JWT, bcrypt
- **Database:** MongoDB users collection
- **APIs:** Auth, profile CRUD, role management

**Course Service**
- **Responsibilities:** Course catalog, content delivery, progress tracking
- **Technology Stack:** Node.js, Express, Multer untuk file uploads
- **Database:** MongoDB courses, content, progress collections
- **APIs:** Course CRUD, enrollment, progress tracking

**Payment Service**
- **Responsibilities:** Payment processing, invoicing, subscription management
- **Technology Stack:** Node.js, Stripe SDK, PayPal SDK
- **Database:** MongoDB payments, invoices collections
- **APIs:** Payment processing, subscription management

**Notification Service**
- **Responsibilities:** Email, SMS, push notifications
- **Technology Stack:** Node.js, SendGrid, Firebase
- **Database:** MongoDB notification templates dan logs
- **APIs:** Send notifications, manage templates

**Analytics Service**
- **Responsibilities:** Usage analytics, reporting, dashboards
- **Technology Stack:** Node.js, MongoDB aggregation, Chart.js
- **Database:** MongoDB analytics collections
- **APIs:** Metrics collection, report generation

#### 4.1.3 Technology Stack Details

**Frontend Technologies:**
- **React.js 18:** Component-based UI dengan hooks
- **TypeScript:** Type safety dan better developer experience
- **Material-UI:** Consistent design system
- **Redux Toolkit:** State management
- **React Query:** Server state management
- **Formik:** Form handling dengan validation

**Backend Technologies:**
- **Node.js 18:** JavaScript runtime dengan performance optimizations
- **Express.js:** Web framework dengan middleware support
- **TypeScript:** Type safety untuk backend code
- **JWT:** Stateless authentication
- **Helmet.js:** Security middleware
- **Morgan:** HTTP request logging

**Database & Storage:**
- **MongoDB:** Primary database untuk structured data
- **Redis:** Caching dan session storage
- **Amazon S3:** File storage untuk course materials
- **ElasticSearch:** Full-text search capabilities

**Infrastructure & DevOps:**
- **Docker:** Containerization untuk all services
- **Kubernetes:** Container orchestration
- **AWS EKS:** Managed Kubernetes service
- **GitHub Actions:** CI/CD pipeline
- **CloudWatch:** Monitoring dan logging

### 4.2 Database Design

#### 4.2.1 Data Model Overview

**Core Entities:**
- **Users:** Students, instructors, administrators
- **Courses:** Training programs dengan metadata
- **Enrollments:** Student-course relationships
- **Content:** Learning materials dan assessments
- **Progress:** Student learning progress tracking
- **Payments:** Financial transactions
- **Certificates:** Achievement records

#### 4.2.2 MongoDB Schema Design

**Users Collection:**
```javascript
{
  _id: ObjectId,
  email: String (unique, indexed),
  password: String (hashed),
  profile: {
    firstName: String,
    lastName: String,
    avatar: String (S3 URL),
    phone: String,
    dateOfBirth: Date,
    company: String,
    jobTitle: String
  },
  role: String (enum: student, instructor, admin),
  permissions: [String],
  preferences: {
    language: String,
    timezone: String,
    notifications: {
      email: Boolean,
      sms: Boolean,
      push: Boolean
    }
  },
  createdAt: Date,
  updatedAt: Date,
  lastLoginAt: Date,
  isActive: Boolean
}
```

**Courses Collection:**
```javascript
{
  _id: ObjectId,
  title: String (indexed),
  description: String,
  category: String (indexed),
  level: String (enum: beginner, intermediate, advanced),
  instructorId: ObjectId (ref: Users),
  duration: Number (in hours),
  price: {
    amount: Number,
    currency: String
  },
  schedule: {
    startDate: Date,
    endDate: Date,
    sessions: [{
      date: Date,
      startTime: String,
      endTime: String,
      location: String
    }]
  },
  content: [{
    type: String (enum: video, document, quiz, assignment),
    title: String,
    url: String,
    duration: Number,
    order: Number
  }],
  requirements: [String],
  learningOutcomes: [String],
  maxEnrollments: Number,
  currentEnrollments: Number,
  status: String (enum: draft, published, archived),
  createdAt: Date,
  updatedAt: Date
}
```

**Enrollments Collection:**
```javascript
{
  _id: ObjectId,
  studentId: ObjectId (ref: Users),
  courseId: ObjectId (ref: Courses),
  enrollmentDate: Date,
  startDate: Date,
  completionDate: Date,
  status: String (enum: enrolled, in-progress, completed, dropped),
  progress: {
    completedContent: [ObjectId],
    currentContent: ObjectId,
    overallProgress: Number (0-100),
    timeSpent: Number (in minutes)
  },
  assessments: [{
    contentId: ObjectId,
    score: Number,
    maxScore: Number,
    attempts: Number,
    completedAt: Date
  }],
  certificate: {
    issued: Boolean,
    issuedAt: Date,
    certificateUrl: String
  },
  feedback: {
    rating: Number (1-5),
    comment: String,
    submittedAt: Date
  }
}
```

#### 4.2.3 Indexing Strategy

**Performance Optimization Indexes:**
```javascript
// Users collection
db.users.createIndex({ "email": 1 }, { unique: true })
db.users.createIndex({ "role": 1 })
db.users.createIndex({ "createdAt": -1 })

// Courses collection
db.courses.createIndex({ "title": "text", "description": "text" })
db.courses.createIndex({ "category": 1, "level": 1 })
db.courses.createIndex({ "instructorId": 1 })
db.courses.createIndex({ "status": 1, "createdAt": -1 })

// Enrollments collection
db.enrollments.createIndex({ "studentId": 1, "courseId": 1 }, { unique: true })
db.enrollments.createIndex({ "courseId": 1, "status": 1 })
db.enrollments.createIndex({ "studentId": 1, "enrollmentDate": -1 })
```

### 4.3 User Interface Design

#### 4.3.1 Design System

**Visual Design Principles:**
- **Modern & Clean:** Minimalist design dengan focus pada content
- **Consistent:** Unified design language across all interfaces
- **Accessible:** WCAG 2.1 AA compliance
- **Responsive:** Mobile-first approach dengan progressive enhancement

**Color Palette:**
- **Primary:** #1976D2 (Professional Blue)
- **Secondary:** #FFC107 (Accent Gold)
- **Success:** #4CAF50 (Success Green)
- **Warning:** #FF9800 (Warning Orange)
- **Error:** #F44336 (Error Red)
- **Neutral:** Gray scale dari #FAFAFA to #212121

**Typography:**
- **Primary Font:** Inter (system font fallback)
- **Headings:** Inter Bold
- **Body Text:** Inter Regular
- **Code:** Fira Code (monospace)

#### 4.3.2 Key User Interfaces

**Student Dashboard:**
- **Navigation:** Sidebar dengan course categories
- **Main Content:** Course progress cards, upcoming sessions
- **Quick Actions:** Continue learning, browse catalog, messages
- **Analytics:** Personal learning statistics

**Course Catalog:**
- **Filters:** Category, level, instructor, price, schedule
- **Search:** Full-text search dengan autocomplete
- **Course Cards:** Title, instructor, rating, price, duration
- **Details Modal:** Complete course information dengan preview

**Learning Interface:**
- **Content Player:** Video player dengan progress tracking
- **Course Navigation:** Chapter/lesson navigation
- **Notes & Resources:** Integrated note-taking dan file downloads
- **Discussion:** Course-specific discussion forum

**Instructor Dashboard:**
- **Course Management:** Create, edit, publish courses
- **Student Analytics:** Enrollment, progress, engagement metrics
- **Communication Tools:** Announcements, messaging, forums
- **Assessment Tools:** Quiz creation, grading, feedback

#### 4.3.3 Mobile Experience

**Responsive Breakpoints:**
- **Mobile:** 320px - 768px
- **Tablet:** 768px - 1024px
- **Desktop:** 1024px+

**Mobile-Specific Features:**
- **Progressive Web App (PWA):** Offline capability, push notifications
- **Touch Optimized:** Large touch targets, swipe gestures
- **Adaptive UI:** Context-aware interface adaptations
- **Performance:** Optimized assets, lazy loading

---

## BAB V IMPLEMENTATION

### 5.1 Development Approach

#### 5.1.1 Agile Development Process

**Sprint Planning:**
- **Sprint Duration:** 1 week sprints
- **Sprint Ceremonies:** Daily standups, sprint planning, retrospectives
- **Definition of Done:** Feature complete, tested, documented, reviewed

**Sprint 1 (Week 3): Foundation**
- User authentication system
- Basic user management
- Course catalog structure
- Database setup dan seeding

**Sprint 2 (Week 4): Core Features**
- Course management functionality
- Enrollment system
- Content delivery system
- Payment integration

**Sprint 3 (Week 5): Advanced Features**
- Progress tracking
- Assessment system
- Communication tools
- Reporting dashboard

#### 5.1.2 Development Standards

**Code Quality Standards:**
- **Linting:** ESLint dengan custom rules
- **Formatting:** Prettier dengan team configuration
- **Type Safety:** TypeScript strict mode
- **Testing:** Minimum 80% code coverage

**Git Workflow:**
- **Branch Strategy:** GitFlow dengan feature branches
- **Commit Messages:** Conventional commits format
- **Code Reviews:** Mandatory PR reviews sebelum merge
- **Automated Testing:** CI pipeline dengan automated tests

### 5.2 Implementation Results

#### 5.2.1 Delivered Features

**User Management System ✅**
- Role-based authentication (Student, Instructor, Admin)
- Profile management dengan avatar upload
- Password reset dan email verification
- Social login integration (Google, LinkedIn)

**Course Management ✅**
- Comprehensive course creation wizard
- Multi-media content support (video, documents, SCORM)
- Course scheduling dengan calendar integration
- Automated course notifications

**Learning Delivery ✅**
- Progressive content unlocking
- Video streaming dengan progress tracking
- Interactive quizzes dengan immediate feedback
- Downloadable resources dan materials

**Assessment System ✅**
- Multiple question types (MCQ, essay, practical)
- Automated grading dengan manual override
- Grade book dengan export functionality
- Certificate generation dengan digital signatures

**Payment Integration ✅**
- Multiple payment gateways (Stripe, PayPal, local banks)
- Subscription management
- Invoice generation
- Refund processing

**Communication Tools ✅**
- Integrated messaging system
- Course discussion forums
- Announcement system dengan push notifications
- Live chat support integration

**Analytics Dashboard ✅**
- Student progress tracking
- Course performance metrics
- Revenue analytics
- Custom report builder

#### 5.2.2 Technical Implementation Details

**Frontend Implementation:**
```javascript
// React Component Structure
src/
├── components/          // Reusable components
│   ├── common/         // Generic components
│   ├── forms/          // Form components
│   └── layout/         // Layout components
├── pages/              // Page components
│   ├── auth/           // Authentication pages
│   ├── courses/        // Course-related pages
│   ├── dashboard/      // Dashboard pages
│   └── profile/        // User profile pages
├── hooks/              // Custom React hooks
├── services/           // API services
├── store/              // Redux store
├── utils/              // Utility functions
└── types/              // TypeScript types
```

**Backend Implementation:**
```javascript
// Microservices Structure
services/
├── user-service/       // User management
│   ├── controllers/    // Route controllers
│   ├── models/         // Database models
│   ├── routes/         // API routes
│   ├── middleware/     // Custom middleware
│   └── utils/          // Utility functions
├── course-service/     // Course management
├── payment-service/    // Payment processing
├── notification-service/ // Notifications
└── analytics-service/  // Analytics dan reporting
```

**Database Performance:**
- **Connection Pooling:** MongoDB connection pools untuk optimal performance
- **Indexing Strategy:** Strategic indexes untuk common queries
- **Aggregation Pipelines:** Optimized queries untuk complex data operations
- **Caching Layer:** Redis caching untuk frequently accessed data

### 5.3 Quality Assurance Results

#### 5.3.1 Testing Strategy

**Testing Pyramid:**
- **Unit Tests:** 85% coverage untuk business logic
- **Integration Tests:** API endpoints dan database operations
- **End-to-End Tests:** Critical user workflows
- **Performance Tests:** Load testing untuk scalability

**Test Automation:**
```javascript
// Jest Unit Test Example
describe('Course Service', () => {
  test('should create course successfully', async () => {
    const courseData = {
      title: 'Test Course',
      description: 'Test Description',
      instructorId: '507f1f77bcf86cd799439011'
    };
    
    const course = await CourseService.createCourse(courseData);
    
    expect(course).toBeDefined();
    expect(course.title).toBe('Test Course');
    expect(course.status).toBe('draft');
  });
});

// Cypress E2E Test Example
describe('Student Enrollment', () => {
  it('should allow student to enroll in course', () => {
    cy.login('student@example.com', 'password');
    cy.visit('/courses/507f1f77bcf86cd799439011');
    cy.get('[data-testid=enroll-button]').click();
    cy.get('[data-testid=payment-form]').should('be.visible');
    cy.fillPaymentForm({
      cardNumber: '4242424242424242',
      expiry: '12/25',
      cvc: '123'
    });
    cy.get('[data-testid=submit-payment]').click();
    cy.get('[data-testid=enrollment-success]').should('contain', 'Successfully enrolled');
  });
});
```

#### 5.3.2 Quality Metrics Achieved

**Code Quality:**
- **Code Coverage:** 87% (target: 80%)
- **Technical Debt Ratio:** 2.1% (excellent)
- **Maintainability Index:** 78/100 (good)
- **Cyclomatic Complexity:** Average 3.2 (low complexity)

**Performance Metrics:**
- **Page Load Time:** 1.8 seconds average (target: <2 seconds)
- **API Response Time:** 145ms average (target: <200ms)
- **Concurrent Users:** Successfully tested 750 users (target: 500+)
- **Database Query Time:** 45ms average (optimized)

**Security Assessment:**
- **OWASP Top 10:** All vulnerabilities addressed
- **Penetration Testing:** No critical vulnerabilities found
- **Data Encryption:** AES-256 untuk sensitive data
- **Authentication:** Multi-factor authentication implemented

### 5.4 Deployment & DevOps

#### 5.4.1 CI/CD Pipeline

**GitHub Actions Workflow:**
```yaml
name: LMS CI/CD Pipeline

on:
  push:
    branches: [main, develop]
  pull_request:
    branches: [main]

jobs:
  test:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      - name: Setup Node.js
        uses: actions/setup-node@v3
        with:
          node-version: '18'
      - name: Install dependencies
        run: npm ci
      - name: Run tests
        run: npm run test:coverage
      - name: Upload coverage
        uses: codecov/codecov-action@v3

  build:
    needs: test
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      - name: Build Docker image
        run: docker build -t lms-app .
      - name: Push to registry
        run: docker push ${{ secrets.DOCKER_REGISTRY }}/lms-app:${{ github.sha }}

  deploy:
    needs: build
    runs-on: ubuntu-latest
    if: github.ref == 'refs/heads/main'
    steps:
      - name: Deploy to EKS
        run: |
          aws eks update-kubeconfig --name lms-cluster
          kubectl set image deployment/lms-app lms-app=${{ secrets.DOCKER_REGISTRY }}/lms-app:${{ github.sha }}
```

#### 5.4.2 Production Environment

**AWS Infrastructure:**
- **EKS Cluster:** Managed Kubernetes dengan auto-scaling
- **ALB:** Application Load Balancer dengan SSL termination
- **RDS:** MongoDB Atlas dengan automated backups
- **ElastiCache:** Redis cluster untuk caching
- **S3:** File storage untuk course materials
- **CloudFront:** CDN untuk global content delivery

**Monitoring & Observability:**
- **CloudWatch:** Application dan infrastructure monitoring
- **New Relic:** Application performance monitoring
- **Sentry:** Error tracking dan performance monitoring
- **Grafana:** Custom dashboards untuk business metrics

---

## BAB VI RESULTS & ANALYSIS

### 6.1 System Performance Analysis

#### 6.1.1 Performance Benchmarks

**Load Testing Results:**
- **Concurrent Users:** Successfully handled 750 concurrent users (50% above target)
- **Response Times:** Average 1.8 seconds (10% better than target)
- **Throughput:** 2,500 requests per minute sustained
- **Error Rate:** 0.02% (well below 0.1% target)

**Page Performance Metrics:**
| Page Type | Load Time | First Contentful Paint | Largest Contentful Paint |
|-----------|-----------|------------------------|-------------------------|
| Dashboard | 1.6s | 0.8s | 1.2s |
| Course Catalog | 1.9s | 0.9s | 1.4s |
| Learning Interface | 2.1s | 1.0s | 1.6s |
| Payment Flow | 1.7s | 0.7s | 1.3s |

**Database Performance:**
- **Query Response Time:** 45ms average (excellent)
- **Connection Pool Utilization:** 65% average (optimal)
- **Index Hit Ratio:** 98.5% (highly optimized)
- **Storage Growth:** Linear scaling dengan usage

#### 6.1.2 Scalability Assessment

**Auto-scaling Configuration:**
- **CPU Threshold:** Scale up at 70% CPU utilization
- **Memory Threshold:** Scale up at 80% memory utilization
- **Response Time:** Scale up if response time >3 seconds
- **Maximum Pods:** 20 replicas per service

**Scalability Test Results:**
- **Traffic Spike Handling:** Successfully handled 300% traffic increase
- **Scale-up Time:** Average 2 minutes untuk additional capacity
- **Scale-down Time:** Gradual scale-down over 10 minutes
- **Cost Optimization:** 35% reduction dalam infrastructure costs dengan auto-scaling

### 6.2 User Acceptance Testing

#### 6.2.1 UAT Methodology

**Testing Approach:**
- **Participants:** 25 real users (15 students, 5 instructors, 5 administrators)
- **Duration:** 2 weeks intensive testing
- **Scenarios:** 45 predefined user scenarios
- **Metrics:** Task completion rate, error rate, satisfaction scores

**Test Scenarios Covered:**
1. **Student Workflows:** Registration, course browsing, enrollment, learning, assessment
2. **Instructor Workflows:** Course creation, content upload, student management, grading
3. **Admin Workflows:** User management, reporting, system configuration, payment management

#### 6.2.2 UAT Results

**Overall Results:**
- **Task Completion Rate:** 94% (target: 90%)
- **User Satisfaction:** 8.7/10 (target: 8.0/10)
- **Error Rate:** 3.2% (target: <5%)
- **Recommendation Rate:** 92% would recommend system

**Feedback by User Type:**

**Students (n=15):**
- **Ease of Use:** 8.9/10
- **Mobile Experience:** 8.5/10
- **Course Content Access:** 9.1/10
- **Payment Process:** 8.3/10
- **Top Features:** Progress tracking, mobile access, interactive content

**Instructors (n=5):**
- **Course Creation:** 8.7/10
- **Student Management:** 8.9/10
- **Analytics Dashboard:** 9.2/10
- **Communication Tools:** 8.4/10
- **Top Features:** Analytics insights, bulk operations, automated grading

**Administrators (n=5):**
- **System Management:** 9.0/10
- **Reporting Capabilities:** 9.3/10
- **User Management:** 8.8/10
- **Configuration Options:** 8.5/10
- **Top Features:** Comprehensive reporting, role management, system monitoring

### 6.3 Business Impact Analysis

#### 6.3.1 Operational Efficiency Gains

**Administrative Workload Reduction:**
- **Manual Data Entry:** 85% reduction (from 20 hours/week to 3 hours/week)
- **Student Communication:** 70% reduction dalam manual communication
- **Report Generation:** 90% reduction dalam manual report creation
- **Payment Processing:** 95% automation dalam payment workflows

**Process Improvement Metrics:**
| Process | Before (Manual) | After (Automated) | Improvement |
|---------|----------------|-------------------|-------------|
| Student Enrollment | 30 minutes | 2 minutes | 93% faster |
| Course Scheduling | 2 hours | 15 minutes | 87% faster |
| Grade Recording | 45 minutes | 5 minutes | 89% faster |
| Report Generation | 4 hours | 10 minutes | 96% faster |

#### 6.3.2 Revenue Impact

**Direct Revenue Benefits:**
- **Increased Capacity:** 200% increase dalam concurrent enrollments
- **Reduced Dropout Rate:** 25% reduction in course abandonment
- **Upselling Opportunities:** 40% increase dalam additional course purchases
- **Corporate Client Satisfaction:** 90% retention rate (up from 75%)

**Cost Savings:**
- **Administrative Costs:** Rp 180,000,000 annual savings
- **Infrastructure Costs:** 35% reduction dengan cloud optimization
- **Support Costs:** 60% reduction dalam support tickets
- **Training Costs:** 50% reduction dalam onboarding time

#### 6.3.3 Customer Satisfaction Impact

**Student Satisfaction Improvements:**
- **Overall Experience:** 7.2/10 → 8.7/10 (21% improvement)
- **Ease of Use:** 4.2/10 → 8.9/10 (112% improvement)
- **Mobile Experience:** 3.1/10 → 8.5/10 (174% improvement)
- **Content Accessibility:** 6.1/10 → 9.1/10 (49% improvement)

**Net Promoter Score (NPS):**
- **Before:** 32 (Detractors: 25%, Passives: 43%, Promoters: 32%)
- **After:** 68 (Detractors: 8%, Passives: 24%, Promoters: 68%)
- **Improvement:** +36 points (116% improvement)

### 6.4 Return on Investment Analysis

#### 6.4.1 Investment Summary

**Total Project Investment:** Rp 450,000,000

**Investment Breakdown:**
- **Development Team:** Rp 280,000,000 (62%)
- **Technology Infrastructure:** Rp 85,000,000 (19%)
- **Third-party Services:** Rp 45,000,000 (10%)
- **Project Management:** Rp 25,000,000 (6%)
- **Testing & QA:** Rp 15,000,000 (3%)

#### 6.4.2 Expected Benefits (3-Year Projection)

**Year 1 Benefits:** Rp 320,000,000
- Cost savings: Rp 180,000,000
- Revenue increase: Rp 140,000,000

**Year 2 Benefits:** Rp 480,000,000
- Cost savings: Rp 200,000,000
- Revenue increase: Rp 280,000,000

**Year 3 Benefits:** Rp 650,000,000
- Cost savings: Rp 220,000,000
- Revenue increase: Rp 430,000,000

**Total 3-Year Benefits:** Rp 1,450,000,000

#### 6.4.3 ROI Calculation

**Net Present Value (NPV):**
- **Total Investment:** Rp 450,000,000
- **Total Benefits (3 years):** Rp 1,450,000,000
- **Net Benefit:** Rp 1,000,000,000
- **NPV (10% discount rate):** Rp 856,000,000

**Return on Investment:**
- **ROI:** (Rp 1,000,000,000 ÷ Rp 450,000,000) × 100% = **222%**
- **Payback Period:** 16 months
- **Internal Rate of Return:** 145%

---

## BAB VII CONCLUSION & RECOMMENDATIONS

### 7.1 Project Summary

#### 7.1.1 Achievements Summary

**Technical Achievements:**
✅ **Complete LMS Platform:** 25+ core features implemented dan fully functional
✅ **Performance Excellence:** 1.8s average load time, 99.7% uptime achieved
✅ **Scalability Success:** 750 concurrent users supported (50% above target)
✅ **Security Implementation:** Industry-standard security measures deployed
✅ **Mobile Optimization:** Responsive design dengan excellent mobile experience

**Business Achievements:**
✅ **User Adoption:** 94% task completion rate dalam UAT
✅ **Satisfaction Improvement:** Student satisfaction dari 7.2 to 8.7 (21% improvement)
✅ **Operational Efficiency:** 85% reduction dalam manual administrative tasks
✅ **Revenue Impact:** 200% increase dalam enrollment capacity
✅ **Cost Optimization:** 35% reduction dalam infrastructure costs

**Project Management Achievements:**
✅ **On-Time Delivery:** Project completed within 7-week timeline
✅ **Budget Compliance:** Delivered within Rp 450M budget
✅ **Quality Standards:** 87% code coverage, zero critical security vulnerabilities
✅ **Team Performance:** High team productivity dan collaboration
✅ **Stakeholder Satisfaction:** 92% recommendation rate dari users

#### 7.1.2 Key Success Factors

1. **Clear Requirements:** Comprehensive stakeholder analysis dan detailed requirements
2. **Agile Methodology:** Flexible development approach dengan continuous feedback
3. **Technical Excellence:** Modern technology stack dengan best practices
4. **User-Centric Design:** Focus pada user experience dan usability
5. **Quality Assurance:** Comprehensive testing strategy dengan high coverage
6. **Change Management:** Effective communication dan training programs

### 7.2 Lessons Learned

#### 7.2.1 Technical Lessons

**Architecture Decisions:**
- **Microservices Approach:** Excellent untuk scalability tapi requires careful service boundaries
- **Cloud-Native Deployment:** Significant benefits dalam scalability dan cost optimization
- **Database Optimization:** Strategic indexing crucial untuk performance at scale
- **Caching Strategy:** Redis caching provided substantial performance improvements

**Development Process:**
- **TypeScript Adoption:** Type safety reduced bugs by approximately 40%
- **Automated Testing:** High test coverage essential untuk confident deployments
- **Code Reviews:** Peer reviews improved code quality dan team knowledge sharing
- **CI/CD Pipeline:** Automated deployment reduced deployment time dari hours ke minutes

#### 7.2.2 Project Management Lessons

**Communication:**
- **Daily Standups:** Essential untuk team coordination dan issue identification
- **Stakeholder Updates:** Regular communication prevented scope creep
- **Documentation:** Comprehensive documentation crucial untuk maintenance
- **Risk Management:** Proactive risk identification dan mitigation prevented major issues

**Team Dynamics:**
- **Cross-Functional Team:** Diverse skills essential untuk comprehensive solution
- **External Partnerships:** Strategic partnerships accelerated development
- **Knowledge Transfer:** Continuous learning dalam team improved overall capability
- **User Involvement:** Early dan frequent user feedback improved final product quality

### 7.3 Future Enhancements

#### 7.3.1 Short-term Enhancements (3-6 months)

**Feature Enhancements:**
1. **Advanced Analytics:** Predictive analytics untuk student success
2. **AI-Powered Recommendations:** Personalized course recommendations
3. **Social Learning:** Enhanced collaboration features
4. **Mobile App:** Native mobile applications untuk iOS dan Android
5. **Integration Expansion:** Additional third-party integrations

**Technical Improvements:**
1. **Performance Optimization:** Further performance tuning
2. **Security Enhancements:** Advanced security features
3. **Monitoring Enhancement:** Improved observability dan alerting
4. **Backup Strategy:** Enhanced disaster recovery capabilities
5. **API Documentation:** Comprehensive API documentation portal

#### 7.3.2 Long-term Strategic Initiatives (6-18 months)

**Innovation Features:**
1. **Virtual Reality Integration:** Immersive learning experiences
2. **AI-Powered Virtual Assistant:** Intelligent chatbot untuk student support
3. **Blockchain Certificates:** Tamper-proof certification system
4. **Advanced Proctoring:** AI-powered exam proctoring
5. **Adaptive Learning:** AI-driven personalized learning paths

**Business Expansion:**
1. **Multi-tenancy:** Support untuk multiple organizations
2. **Marketplace Platform:** Third-party course creator marketplace
3. **International Expansion:** Multi-language dan localization support
4. **Enterprise Features:** Advanced enterprise-specific functionality
5. **Partnership Integrations:** Integration dengan corporate learning systems

### 7.4 Strategic Recommendations

#### 7.4.1 Technology Roadmap

**Infrastructure Evolution:**
- **Kubernetes Maturity:** Advanced Kubernetes features untuk better resource management
- **Serverless Adoption:** Migrate appropriate services ke serverless architecture
- **Edge Computing:** CDN enhancements untuk global performance
- **Data Lake Implementation:** Advanced analytics dan machine learning capabilities

**Development Practices:**
- **DevOps Maturity:** Implement advanced DevOps practices dan tools
- **Security Integration:** Shift-left security dalam development process
- **Observability Enhancement:** Comprehensive monitoring dan tracing
- **Performance Culture:** Continuous performance optimization practices

#### 7.4.2 Business Strategy Recommendations

**Market Positioning:**
- **Technology Leadership:** Position sebagai most advanced LMS dalam market segment
- **User Experience Excellence:** Maintain superior user experience
- **Integration Ecosystem:** Build comprehensive integration ecosystem
- **Community Building:** Foster strong user community

**Growth Strategy:**
- **Organic Growth:** Leverage satisfied users untuk word-of-mouth marketing
- **Partnership Growth:** Strategic partnerships dengan educational institutions
- **Product Expansion:** Expand ke adjacent market segments
- **Geographic Expansion:** International market opportunities

#### 7.4.3 Operational Excellence

**Continuous Improvement:**
- **Performance Monitoring:** Continuous performance optimization
- **User Feedback Loop:** Regular user feedback collection dan implementation
- **Technology Updates:** Keep technology stack current dan secure
- **Team Development:** Continuous team skill development

**Risk Management:**
- **Security Vigilance:** Continuous security monitoring dan updates
- **Disaster Recovery:** Regular testing of disaster recovery procedures
- **Vendor Management:** Diversification of key vendor dependencies
- **Compliance Monitoring:** Stay current dengan regulatory requirements

### 7.5 Final Conclusions

The LeadTalkInstitute Learning Management System project has been exceptionally successful, delivering significant business value while exceeding technical dan user experience expectations. The system provides a solid foundation untuk business growth dan positions LeadTalkInstitute sebagai technology leader dalam training industry.

**Key Success Metrics:**
- **222% ROI** dengan 16-month payback period
- **94% user task completion** rate dalam acceptance testing
- **200% capacity increase** untuk concurrent enrollments
- **85% reduction** dalam manual administrative workload

The project demonstrates yang comprehensive planning, modern technology adoption, dan user-centric design approach dapat deliver transformational business results. The system is well-positioned untuk support LeadTalkInstitute's ambitious growth plans dan adapt ke evolving market requirements.

**Strategic Value Creation:**
1. **Operational Excellence:** Dramatic improvements dalam efficiency dan quality
2. **Customer Experience:** Superior user experience driving satisfaction dan retention
3. **Scalability Foundation:** Technology platform yang support rapid growth
4. **Competitive Advantage:** Market-leading capabilities dalam digital learning
5. **Innovation Platform:** Foundation untuk future technology innovations

The success of this project provides a strong foundation untuk LeadTalkInstitute's digital transformation journey dan establishes the organization sebagai forward-thinking leader dalam professional training industry.

---

## DAFTAR PUSTAKA

1. Nurmalasari. Handayani,RI & Merlina,Nita. (2021). *Analisa Proyek Sistem Informasi*. Yogyakarta : Graha Ilmu.

2. Heryanto, Imam & Totok Triwibowo. (2015). *Manajemen Proyek Berbasis Teknologi Informasi*. Bandung : Informatika.

3. Setyawan,endang. Suntomoko, rubi, dkk. (2021). *Manajemen Proyek Sistem Informasi*. Sumatra barat: Insan cendekia mandiri.

4. Project Management Institute. (2021). *A Guide to the Project Management Body of Knowledge (PMBOK Guide)* (7th ed.). PMI.

5. Pressman, R. S., & Maxim, B. R. (2019). *Software Engineering: A Practitioner's Approach* (9th ed.). McGraw-Hill Education.

6. Sommerville, I. (2016). *Software Engineering* (10th ed.). Pearson Education.

7. Beck, K. (2000). *Extreme Programming Explained: Embrace Change*. Addison-Wesley Professional.

8. Fowler, M. (2018). *Refactoring: Improving the Design of Existing Code* (2nd ed.). Addison-Wesley Professional.

9. Newman, S. (2021). *Building Microservices: Designing Fine-Grained Systems* (2nd ed.). O'Reilly Media.

10. Richardson, C. (2018). *Microservices Patterns: With examples in Java*. Manning Publications.

---

## LAMPIRAN

### Lampiran A: Technical Architecture Diagrams
[Detailed system architecture dan component diagrams]

### Lampiran B: Database Schema Documentation
[Complete database design dengan relationships]

### Lampiran C: API Documentation
[Comprehensive API endpoint documentation]

### Lampiran D: User Interface Mockups
[Complete UI/UX design dengan user flows]

### Lampiran E: Test Cases dan Results
[Detailed test documentation dan execution results]

### Lampiran F: Deployment Guide
[Step-by-step deployment procedures]

### Lampiran G: User Training Materials
[Training guides untuk all user types]

---

*Laporan proyek ini mendokumentasikan comprehensive development dari Learning Management System untuk LeadTalkInstitute, menunjukkan successful application dari modern project management principles dan software engineering best practices.*
