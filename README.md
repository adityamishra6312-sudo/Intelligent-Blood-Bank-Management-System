# Intelligent Blood Bank Management System

**SDG Alignment:** SDG 3 — Good Health and Well-being

**Course:** Data Structure and Algorithms - II (CCSE0301)
**Program:** B.Tech CSE-A
**Faculty:** Mr. Shamshad Ali
**Student:** Aditya Mishra (ERP ID: 2501330100036)
**Assignment Type:** Individual Assignment

---

## 📌 Project Overview

This project studies how blood-bank data from multiple sources — donor registrations, blood collection drives, blood unit storage, and hospital requests — can be organized, processed, and monitored using suitable Data Structures and Algorithms (DSA).

The goal is to combine efficient data organization with basic prioritization logic so that:
- Blood availability can be tracked
- Blood-group compatibility can be checked
- Urgent hospital requirements can be attended to first

## 🩸 Problem Context

Blood banks generate continuous data from donor registrations, collection camps, lab testing, storage, and hospital requests. As records grow, manually checking every blood unit for group, collection date, and expiry becomes impractical. Blood-related entities are also interconnected — a blood bank stores units from many donors, a hospital may request from several blood banks, and blood groups relate to one another through compatibility rules.

This project explores how **tree-based** and **graph-based** data structures can address these challenges.

## 🎯 Objectives

- Understand the problem of managing and monitoring blood donor and inventory data across blood banks
- Identify limitations of manual blood-stock tracking and fragmented donor records
- Study DSA-II Unit 1 (Trees) and Unit 2 (Graphs) as the conceptual foundation
- Explore tree-based structures for organizing/searching blood units by group or expiry date
- Explore graph-based structures for representing donor–blood bank–hospital–blood group relationships
- Explore heap-based prioritization for urgent hospital requests and near-expiry alerts
- Build the conceptual foundation for design and implementation in later reviews

## 👥 Target Users / Stakeholders

| Stakeholder | Use Case |
|---|---|
| Blood Banks / Administrators | Monitor stock, expiry status, and donor records |
| Hospitals / Doctors | Search compatible blood units and raise urgent requests |
| Donors | Register details and receive eligibility/donation notifications |
| System Administrators | Monitor data quality and request-handling performance |

## 🧠 DSA Concepts Applied (Unit 1: Trees, Unit 2: Graphs)

| Concept | Applied? | Purpose |
|---|---|---|
| Binary Tree / Tree Terminology | ✅ | Hierarchy of blood-group / expiry categories |
| Binary Search Tree (BST) | ✅ | Conceptual search of blood units by expiry/ID |
| AVL Tree | ✅ | Balanced searching as inventory changes frequently |
| Complete Binary Tree / Binary Heap | ✅ | Priority structure for urgent requests & near-expiry alerts |
| Tree Traversals (In/Pre/Post-order) | ✅ | Systematic processing of sorted blood-unit records |
| Graph Terminology & Adjacency List | ✅ | Modeling donors, blood banks, hospitals, blood-group compatibility |
| Adjacency Matrix, B-Tree, Heap Sort, Threaded Binary Tree, etc. | ❌ | Considered but not selected for current design |

*(Full complexity analysis and justification available in the Progress Report PDF.)*

## 📚 Literature Reviewed

- Sarode, Ghanekar, Krishnadas, Patil & Parmar (2019) — *Intelligent Blood Management System*, IEEE IBSSC
- Sandaruwan et al. (2020) — *Towards an Efficient and Secure Blood Bank Management System*, IEEE
- IEEE (2022) — *A Web-based Blood Bank System for Managing Records of Donors and Receipts*
- MDPI IoT Journal (2022) — *The Use of Web Technology and IoT to Contribute to the Management of Blood Banks in Developing Countries*

## 📈 Project Status

**Overall Progress: 25%** *(as of Month 1 / Review 1)*

Completed so far:
- Problem statement finalized and context studied
- Objectives and stakeholders defined
- DSA-II Unit 1 (Trees) and Unit 2 (Graphs) studied and mapped to the problem
- Initial conceptual idea of donor/blood-unit/hospital-request representation

> No implementation has been built yet — this stage reflects problem understanding and conceptual planning only.

## 🗺️ Plan for Next Review

- Refine requirements based on further study of blood-bank management needs
- Finalize the data structures to be used for donor and blood-unit information
- Design the donor–blood bank–hospital graph and apply identified tree/graph concepts
- Begin initial implementation of a small part of the monitoring system
- Collect evidence: diagrams, sample data, and code snippets

## 📄 Reports

Progress reports for this project are maintained in this repository, with detailed write-ups following the PBL Progress Report format required by the course.

## 🔗 Repository

[https://github.com/adityamishra6312-sudo/Intelligent-Blood-Bank-Management-System](https://github.com/adityamishra6312-sudo/Intelligent-Blood-Bank-Management-System)

---

### Student Declaration

This work is the original work of Aditya Mishra, submitted as an individual assignment for DSA-II (CCSE0301) at NIET Greater Noida.
