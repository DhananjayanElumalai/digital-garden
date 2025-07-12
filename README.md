# 🔍 Data Analytics Portfolio
**Dhananjayan E** | Lead Data Analyst | Python | SQL | Power BI | GxP Compliance  
*Transforming complex data into actionable insights with 12+ years of experience*

---

## 🏆 Featured Case Studies

### 1. 📊 Power BI: Clinical Trial Dashboard System
**Tech Stack**: Power BI (DAX), SharePoint, Power Automate  
**Business Impact**:
- Reduced manual reporting time by **40%** for 50+ clinical team members
- Achieved **real-time updates** through SharePoint integration
- Mentored 2 junior analysts in dashboard development

**Key Code Snippet**:
```dax
// DAX Measure for Completed Tasks
Completed Tasks = 
CALCULATE(
    COUNTROWS(TaskList),
    TaskList[Status] = "Completed"
)
