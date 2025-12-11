# Quotation-Generator: The Offline SME Solution

A powerful, single-file application designed to generate professional quotations for Small and Medium Enterprises (SMEs). This lightweight tool runs completely offline, ensuring speed and reliability, and uses browser Local Storage for saving drafts and history.

## Key Features

### 1. Modern UI/UX and Print Layout

The application has been upgraded with a clean, modern, and fully responsive interface using Tailwind CSS.

**Modern Aesthetics:** Features the Inter font, rounded elements, and a clean, accessible layout.

**Mobile Responsive:** Seamlessly adapts to mobile, tablet, and desktop screens, ensuring usability on the go.

**Print Optimization:** Specialized CSS ensures clean, professional printouts by hiding UI elements and controls.

### 2. Smart Data Persistence and Auto-Save

The tool provides robust client-side storage to prevent data loss and improve workflow efficiency.

***Draft Auto-Save:** Automatically saves the current quotation data to browser storage as you type. Work-in-progress is instantly restored upon reopening the file.

**Clear All:** Resets the entire form and clears the saved draft.

### 3. Auto-Suggestion & Intelligent History

Accelerate the quotation process by reusing frequent data entries.

**Client History:** The Customer Details input suggests entire client entries from past quotations.

**Item History:** The Description of Item input suggests previously entered item descriptions.

**Intelligent Auto-Fill:** When an item description is selected from the suggestion list, the application automatically populates the corresponding Rate (₹) and GST (%) fields.

**Save & Update Suggestions:** A dedicated button ensures the data from the current quotation is added to the permanent suggestion history for future use.

### 4. Dynamic Calculation Engine

All financial calculations are performed instantly on the client side with high accuracy.

**Real-time Totals:** Calculates line item amounts, GST/CGST/SGST splits, and totals instantly upon input changes.

**Rounding Logic:** Automatically calculates and applies rounding adjustments to ensure the Grand Total (Payable) is a clean, whole rupee amount (integer).

## Interactive Project Showcase

This project also includes a separate, single-page showcase (quotation-app-showcase.html) to demonstrate the value proposition and core technical capabilities interactively.

**Efficiency Chart:** Compares manual workflow time against the application's optimized workflow.

**Live Calculation Demo:** Allows users to interactively test the GST and rounding logic.

**Persistence Simulator:** Visually explains how data auto-saves to LocalStorage.

<img width="1272" height="1280" alt="image" src="https://github.com/user-attachments/assets/bd383b25-6365-4225-948c-1c37c1f618d9" />