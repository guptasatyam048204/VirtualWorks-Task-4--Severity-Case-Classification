# VirtualWorks-Task-4--Severity-Case-Classification
# Task 4: Severity & Case Classification

## Overview
This repository contains the documentation and step-by-step implementation guide for **Task 4: Severity & Case Classification** as part of the Pharmacovigilance Internship Program at VirtualWorks.

This project covers the clinical evaluation of Adverse Drug Reactions (ADRs) based on seriousness, severity, and expectedness, along with the process of establishing a **Case Classification Sheet** (using NVivo methodology) to structure and manage patient safety data.

---

## 1. Seriousness & Case Classification Guidelines

### Key Criteria for Serious Adverse Events (SAEs)
An Adverse Drug Reaction (ADR) or Adverse Event (AE) is classified as **Serious** if it results in any of the following outcomes:
- **Death** or life-threatening scenario.
- **Inpatient Hospitalization** or prolongation of existing hospitalization.
- **Persistent or Significant Disability/Incapacity**.
- **Congenital Anomaly / Birth Defect**.
- **Medically Important Event** (requires medical intervention to prevent one of the outcomes above).

### Severity vs. Seriousness
- **Severity:** Describes the intensity of a specific event (e.g., Mild, Moderate, Severe pain).
- **Seriousness:** Based on patient/event outcome or action criteria that serve as a guide for defining regulatory reporting obligations.

---

## 2. Step-by-Step Guide: Creating a Case Classification Sheet

In qualitative data analysis software (e.g., NVivo) and safety database setups, structured Case Classification Sheets organize participant metadata and clinical variables.

### Step 1: Navigate to Case Classifications
1. Open your project in **NVivo**.
2. In the left-hand **Navigation View**, expand the **Cases** menu.
3. Select **Case Classifications**.

### Step 2: Create a New Classification
1. Right-click inside the blank space of the **Case Classifications** pane (or go to the top ribbon under *Create*).
2. Select **New Classification** $\rightarrow$ **New Case Classification**.
3. Name the classification sheet (e.g., `Participant Profile` or `ADR_Case_Classification`) and click **OK**.

### Step 3: Add Attributes (Demographic & Clinical Variables)
1. Right-click on the newly created classification sheet and select **New Attribute**.
2. Define the attribute properties:
   - **Name:** Enter variable name (e.g., `Age Group`, `Gender`, `ADR Severity`, `Seriousness Status`).
   - **Type:** Select appropriate data type (Text, Integer, Date, etc.).
3. Under the **Values** tab, define potential values:
   - For `ADR Severity`: *Mild*, *Moderate*, *Severe*.
   - For `Seriousness Status`: *Serious*, *Non-Serious*.
4. Click **OK** to save each attribute.

### Step 4: Populate Data & Import Options
1. **Manual Data Entry:** Double-click the Case Classification sheet to open it in grid view, then enter or select attribute values for each assigned case row.
2. **Batch Import:** Go to **Data / Import** $\rightarrow$ **Classification Sheets** to import pre-existing dataset spreadsheets (`.xlsx` / `.csv`) directly matching your case variables.

---

## Conclusion
Establishing structured Case Classification Sheets enables efficient filtering, sub-group analysis, and accurate regulatory reporting of adverse drug events according to standard severity and seriousness frameworks.
