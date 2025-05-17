# 📄 Philist Test Plan

📥 **[Download this Test Plan as PDF](./Philist_Test_Plan_by_Dominique_Gonzaga.pdf)**

---

## Document Change History

| Version | Date       | Contributor        | Description                            |
|---------|------------|--------------------|----------------------------------------|
| v1.0    | 02/05/2024 | Dominique Gonzaga  | Initial test plan created              |
| v1.1    | 03/11/2024 | Dominique Gonzaga  | Added scope, out-of-scope, schedule    |
| v1.2    | 04/22/2024 | Dominique Gonzaga  | Added terms and acronyms               |

---

## 1. Introduction

### 1.1 Purpose  
To define the testing approach, deliverables, and schedule for Philist, ensuring the application functions as intended and meets the needs of students, teachers, and administrators.

### 1.2 Background  
Philist is an integrated platform designed to streamline academic workflows in educational institutions. It supports students, teachers, and administrators in managing academic tasks such as scheduling, grading, communication, and performance tracking.

## 1.3 Scope

### In Scope
- Core functionalities: user authentication, class management, enrollment, administrative workflows  
- Validation of frontend and backend components  
- Cross-browser and cross-device compatibility testing  
- Performance testing under typical load conditions

### Out of Scope
- Integration with external APIs beyond core scope  
- Advanced security/penetration testing  
- Load testing under extreme conditions  
- Testing on tablets or unsupported devices  
- Browsers other than Chrome and Safari

## 1.4 Project Identification

| Role              | Name(s)                                             |
|-------------------|-----------------------------------------------------|
| Project Name      | Philist                                             |
| Project Managers  | Sam Nam, Julie Requiso                              |
| Test Engineer     | Dominique Gonzaga                                   |
| Developers        | Ronnel Suan, Olliver Jules Morales, Mikko Dacasin, Gael Murillo, Laurence Co, Jan Solomon |
| UI/UX Designer    | Arcel Vocales                                       |

## 1.5 Quality Objectives

### Primary Objective
Ensure Philist meets all functional requirements and delivers a seamless user experience across supported platforms.

### Secondary Objective
Address security concerns and assess performance under expected loads to ensure data integrity, responsiveness, and usability.

## 1.6 Assumptions for Test Execution

- Test environments will mirror production  
- Test data will reflect real-world usage  
- QA team will collaborate actively with developers and PMs

## 1.7 Constraints

- Fixed project timelines  
- Limited QA resources  
- Dependency on infrastructure or third-party systems

---

## 2. Test Approach

### 2.1 Testing Stages

- Functional Testing  
- GUI Testing  
- Usability Testing  
- Integration Testing  
- System Testing  
- API Testing

### 2.2 Testing Types

- Functional Testing  
- Security Testing  
- Performance Testing  
- Usability Testing

### 2.3 Tasks, Estimations, and Schedule

| Task                   | Member          | Estimate        |
|------------------------|------------------|-----------------|
| Create Test Specification | Test Engineer | 170 man-hours   |
| Perform Test Execution    | Test Engineer | 80 man-hours    |
| Test Reporting            | Test Engineer | 10 man-hours    |
| Test Delivery             | Test Engineer | 20 man-hours    |
| **Total**                 |                | **280 man-hours** |

### 2.4 Bug Life Cycle

_New → Assigned → In Progress → Retest → Closed_  
(*Include diagram if needed in the repo.*)

### 2.5 Priority Levels

| Priority  | Description                                |
|-----------|--------------------------------------------|
| Highest   | Blocks testing or product usage completely |
| High      | Serious issue, impacts functionality       |
| Medium    | Noticeable, but non-blocking               |
| Low       | Minor issue or cosmetic bug                |
| Lowest    | Trivial, little or no impact               |

---

## 3. Test Deliverables

- Test Plan  
- Test Cases  
- Test Reports  
- Defect Logs  

---

## 4. Environmental Needs

### 4.1 Hardware  
- Desktops/laptops for admin testing  
- Mobile devices for student/teacher testing

### 4.2 Software

| Device   | OS       | Browser |
|----------|----------|---------|
| Desktop  | Windows  | Chrome  |
|          | macOS    | Safari  |
| Mobile   | Android  | Chrome  |
|          | iOS      | Safari  |

### 4.3 Tools

| Process            | Tool          |
|--------------------|---------------|
| Test Case Creation | Google Sheets |
| Test Tracking      | Google Sheets |
| Test Execution     | Manual        |
| Test Management    | Google Sheets |
| Defect Management  | Jira          |
| API Testing        | Postman       |

---

## 5. Roles & Responsibilities

### Test Engineer  
- Write test plans, design test cases, execute tests, and log bugs

### Developers  
- Implement features and resolve reported defects

### Project Manager  
- Manage timelines, ensure coordination, and approve deliverables

---

## 6. Dependencies & Risks

- Delayed feature delivery  
- Limited test coverage due to time constraints  
- Environment or infrastructure issues

---

## 7. Schedule & Milestones

| Phase                  | Dates                |
|------------------------|----------------------|
| Test Planning          | Jan 26 – Feb 16, 2024 |
| Test Execution         | Feb 8 – May 17, 2024  |
| Defect Resolution      | Ongoing              |
| Final Test Report      | May 17, 2024         |

---

## 8. Approvals

This test plan requires approval from the Project Manager.

---

## 9. Terms & Acronyms

- **GUI** – Graphical User Interface  
- **OS** – Operating System  
- **PM** – Project Manager  
- **TE** – Test Engineer  
- **UI/UX** – User Interface / User Experience
