📊 Power BI: Clinical Trial Dashboard System
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
