# Multi-Select Lookup Component ✅🔍  

A Salesforce **Lightning Web Component (LWC)** that extends the functionality of a standard lookup to support **multiple record selection**. Selected records are displayed as **pills**, with built-in validation and dynamic search powered by Apex.  

---

## 🚀 Features  

- 🔄 **Dynamic Lookup Search**  
  - Uses `@wire` with Apex for real-time record search.  

- 🏷️ **Multi-Select Support**  
  - Displays selected records as **pills** using `lightning-pill-container`.  
  - Supports **remove pill** action for deselection.  

- 🚫 **Duplicate Validation**  
  - Prevents duplicate records with **ShowToastEvent** error messages.  

- ⚡ **Reactive Array Updates**  
  - Managed selected records array using `splice()` with reactive state handling.  

- 🛠️ **Lightning App Builder Support**  
  - Configurable via `@api` properties defined in the `meta.xml` file.  

---

## 🛠️ Tech Stack  

- **Apex** (dynamic search queries)  
- **Lightning Web Components (LWC)**  
- **ShowToastEvent for validation feedback**  
- **SLDS (Salesforce Lightning Design System)**  

---
