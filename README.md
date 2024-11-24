<p align="center">
  <img src="hstu_logo_.png" alt="hstu_logo_.png" width="250" height="300">
</p>
<h1 align="center">
  <b>Business Analysis System</b>
</h1>
<h3 align="center">
  <br>
  <b>Level-3 Semester-I Project Report</b>  
</h3>
<h3 align="center">
  Course Code: CSE 305 
</h3>

<h3 align="center">
  Course Title: Software Engineering
</h3>
<br>
<h3 align="center">
  Submitted by 
</h3>
<h3 align="center">
<b>Md. Sabbir Ahamed Shovon (ID: 2102034) </b> </h3>
<br>

<h3 align="center">
  Submitted To 
</h3>

<h3 align="center"><b>Pankaj Bhowmik  </b></h3>
<h3 align="center"><b>Lecturer, Department of CSE</b></h3>
<br>
<h3 align="center"> <b>Department of Computer Science and Engineering </b></h3>
<h3 align="center"><b>Hajee Mohammad Danesh Science and Technology University  
Dinajpur-5200</b></h3>

  ---

## Table of Contents  
1. [Introduction](#1-introduction)  
2. [SDLC Phases](#2-sdlc-phases)  
   - [Planning Phase](#21-planning-phase)  
   - [Requirements Analysis Phase](#22-requirements-analysis-phase)  
   - [System Design Phase](#23-system-design-phase)  
   - [Implementation Phase](#24-implementation-phase)  
   - [Testing Phase](#25-testing-phase)  
   - [Deployment Phase](#26-deployment-phase)  
   - [Maintenance Phase](#27-maintenance-phase)  
3. [Challenges and Solutions](#3-challenges-and-solutions)  
   - [Challenges](#31-challenges)  
   - [Solutions](#32-solutions)  
4. [Conclusion](#4-conclusion)  
5. [References](#5-references)  

---

## 1. Introduction  
The **Business Analysis System** is a software application designed to help businesses perform financial analysis. The system focuses on key financial metrics such as the **break-even point (BEP)**, the **number of units required to achieve target profit**, the **margin of safety**, and the **price per product required to meet a target profit**. The system is developed following the **Software Development Life Cycle (SDLC)** methodology, ensuring structured and efficient development from requirements gathering to deployment.  

---

## 2. SDLC Phases  

### 2.1 Planning Phase  
**Objective**: Define the scope and objectives of the Business Analysis System. This phase involved discussions with business owners and financial analysts to understand their needs and determine the key metrics to be calculated.  

**Key Deliverables**:  
- Project scope document  
- High-level requirements for the Business Analysis System  
- Timeline and resource allocation for development  

**Outcome**:  
- Clear definition of functional and non-functional requirements.  
- Agreement on the project timeline and milestones.  

---

### 2.2 Requirements Analysis Phase  
**Objective**: Analyze the requirements in detail to understand the business and technical needs.  

**Core Functional Requirements**:  
- **Break-even Point Calculation**: Calculate BEP based on fixed costs, variable costs per unit, and selling price per unit.  
- **Target Profit Calculation**: Determine how many units need to be sold to achieve a specified target profit.  
- **Margin of Safety Calculation**: Calculate the margin of safety to understand the risk of the business’s financial position.  
- **Price per Product Calculation**: Calculate the price required per product to reach a target profit.  

**Non-Functional Requirements**:  
- User-friendly interface (UI) built with JavaFX.  
- Scalability for handling large datasets in the future.  
- Secure system to protect financial data.  

**Outcome**:  
- A detailed requirements document outlining functional and non-functional requirements.  
- Clear understanding of the business needs and goals.  

---

### 2.3 System Design Phase  
**Objective**: Design the system architecture and components to fulfill the requirements outlined in the analysis phase.  

**High-Level Design (HLD)**:  
- **Architecture**: Modular client-server architecture.  
  - **Client Side**: Built with JavaFX for the GUI.  
  - **Business Logic**: Implemented in Java.  
- **Modules**:  
  - **Break-even Point Calculation Module**  
  - **Target Profit Calculation Module**  
  - **Margin of Safety Calculation Module**  
  - **Price per Product Calculation Module**  

**Low-Level Design (LLD)**:  
- **Class Diagrams**: Key classes include `BusinessAnalyzer`, `FinancialMetrics`, and `UserInterface`.  
- **Sequence Diagrams**: Describes interactions between modules for user input and system output.  

**Outcome**:  
- Detailed architectural design and defined system components.  

---

### 2.4 Implementation Phase  
**Objective**: Develop the system as per the design specifications.  

**Tools and Technologies**:  
- Programming Language: Java  
- GUI Framework: JavaFX  
- IDE: IntelliJ IDEA  
- Storage: In-memory (local file system for input data storage)  

**Outcome**:  
- Successfully implemented core functionalities.  
- Developed a user-friendly GUI using JavaFX.  

---

### 2.5 Testing Phase  
**Objective**: Ensure the system functions correctly and meets all requirements.  

**Testing Types**:  
- **Unit Testing**: Validated individual modules.  
- **Integration Testing**: Ensured smooth module interaction.  
- **System Testing**: Tested complete system functionality.  
- **User Acceptance Testing (UAT)**: Feedback from business users.  

**Outcome**:  
- All core functionalities passed testing.  
- Minor UI issues resolved to enhance user experience.  

---

### 2.6 Deployment Phase  
**Objective**: Deploy the system and make it available for end-users.  

**Steps**:  
1. Packaged the application as an executable JAR file.  
2. Ensured easy installation with necessary dependencies (e.g., Java Runtime Environment).  
3. Provided user manual and installation guide.  

**Outcome**:  
- Successful deployment as a standalone application.  

---

### 2.7 Maintenance Phase  
**Objective**: Ensure system reliability and future scalability.  

**Tasks**:  
- Feature Enhancements: Adding advanced reporting and forecasting tools.  
- Bug Fixes: Address user-reported issues.  
- Performance Optimization: Improve system scalability.  

**Outcome**:  
- System ready for future updates and enhancements.  

---

## 3. Challenges and Solutions  

### 3.1 Challenges  
- **Accurate Data Entry**: Ensuring users input accurate data for calculations.  
- **Scalability**: Handling large data volumes as the business grows.  

### 3.2 Solutions  
- **Data Validation**: Robust mechanisms to minimize input errors.  
- **Modular Design**: Enables easy scalability and feature addition.  

---

## 4. Conclusion  

The **Business Analysis System** successfully followed the SDLC methodology, delivering a software tool that helps businesses calculate financial metrics like break-even points, target profits, margin of safety, and pricing strategies. The project was completed efficiently, with minimal issues, meeting all business objectives.

---

## 5. References  
- "Financial Management" by Prasanna Chandra  
- JavaFX Official Documentation  
- SDLC Methodology Tutorials  

---

## [Code Repository](#)  
The complete code for the **Business Analysis System** can be accessed [here](#).  
