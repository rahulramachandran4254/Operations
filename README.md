# Supply Chain and Operations Projects
---
## Amazon Lab126 Inspired Operations Project – Echo Smart Display V2  

This project simulates the **Operations Program Specialist (OPS)** role at **Amazon Lab126** (the team behind Echo, Kindle, and Fire devices).  
It demonstrates how OPS manages **BOMs, ECOs, build planning, procurement, and risk** to take a product from design → prototype → manufacturability.  

---

## Repository Contents  

**Amazon Lab126 - Operations Project.xlsx**  
This workbook contains six core sheets:  

| Sheet             | Description                                                                 |
|-------------------|-----------------------------------------------------------------------------|
| **BOM_Normalized** | Hierarchical Bill of Materials with assemblies, components, suppliers, costs, lead times |
| **ECOs**           | Engineering Change Orders with reasons, impacted parts, and build phases    |
| **Build Matrix**   | EVT, DVT, PVT prototype phases with units, ECOs applied, and build status   |
| **PO Tracker**     | Simulated purchase orders with supplier, quantity, delivery dates, and status |
| **Risk Register**  | Risks, impact, likelihood, mitigations, and responsible owners              |
| **Supplier Master**| Supplier reference with region and preference status                        |

---

🛠️ What I Did  

-  Built a **hierarchical BOM** (15+ components, 5 subassemblies) linking suppliers, costs, and lead times.  
-  Managed **4 ECOs** to log and control design changes (housing, PCB, bezel, battery).  
-  Developed a **Build Matrix** to track 270 units across EVT, DVT, and PVT builds.  
-  Created a **PO Tracker** and **Risk Register** to improve procurement visibility and risk planning.  
-  Organized a **Supplier Master** database to centralize vendor information.  

---

## Why This Matters  

These workflows are **core to hardware operations**:  
- ✅ Accurate BOMs prevent part shortages and late builds.  
- ✅ ECOs ensure design changes are tracked and approved.  
- ✅ Build Matrices align engineering, supply chain, and manufacturing.  
- ✅ PO Trackers & Risk Registers reduce supplier delays and program risk.  

---

## Key Learnings  

- The role of OPS as the **bridge** between engineering, supply chain, and manufacturing.  
- How **structured documentation** keeps teams aligned and reduces rework.  
- The importance of **risk visibility** in hitting production schedules.  

---

## Future Improvements  

- Add **pivot tables & charts** for cost and lead-time visualization.  
- Extend the BOM with **more parts and suppliers** to simulate larger programs.  
- Automate trackers with **Python or Excel macros**.  
- Build a **Notion/Markdown wiki** to mirror Confluence-style documentation.  

---
## Screenshots
Bill of Materials
<img width="1352" height="603" alt="Screenshot 2025-09-17 123125" src="https://github.com/user-attachments/assets/1f2118b2-cf4a-41d2-a6bc-5dbc344a884d" />
Build Matrix
<img width="1262" height="271" alt="Screenshot 2025-09-17 123228" src="https://github.com/user-attachments/assets/5a836dca-ba41-4030-94b1-6419aec8b757" />
Engineering Change Orders (ECOs)
<img width="1044" height="278" alt="Screenshot 2025-09-17 123258" src="https://github.com/user-attachments/assets/f15d7aa2-9c65-4092-a639-107327258759" />

## License  

This is a **learning & portfolio project**, not affiliated with Amazon or Lab126.  

