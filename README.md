<div align="center">
  <h2>Hi, I'm Lili 👋</h2>
  <p>
    <a href="mailto:tothlilikornelia@gmail.com"><img src="https://img.shields.io/badge/-Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
    <a href="https://www.linkedin.com/in/lili-kornelia-toth-a83228268/"><img src="https://img.shields.io/badge/-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  </p>
</div>

---

## 👩🏻‍💻 About Me

```python
from dataclasses import dataclass, field

@dataclass
class LiliToth:
    expertise: str = "Business Analytics"
    experience_years: int = 3
    domain: str = "HR Data Analytics (Matrix Organization)"
    
    education: dict[str, str] = field(default_factory=lambda:
    {
        "BA": "Linguistics",
        "BSc": "Computer Science (ongoing)"
    })
    
    tech_stack: set[str] = field(default_factory=lambda:
    {
        "Data pipelines", "SQL", "Python", "Advanced Excel", "ML"
    })
    
    motivations: list[str] = field(default_factory=lambda:
  [
        "Versitality of data analytics",
        "Creating order in chaos and learning what its secrets"
    ])
    
    origin_story: str =
    (
        "Learned to code out of spite to avoid manually analysing large research datasets during my BA "
        "fell in love "
        "never looked back. "
    )

    @property
    def hobbies(self) -> dict[str, list[str] | str]:
        return {
            "outdoor": "Thru-hiking",
            "indoor": "Cooking",
            "languages": {
                "types": ["Human", "Computer"],
                "philosophy": "Syntax is syntax."
            }
        }

if _name__ == "__main__":
    me = LiliToth()
```
## 🏢 Featured projects for Business Analytics
### 1. HRIS Database Modeling in PostgreSQL
* **The Build:** Engineered a realistic HR dataset and transformed complex organizational hierarchies into a BI-ready reporting layer.
* **Tech Stack:** PostgreSQL (CTEs, Window functions, Row & Column level security).
* **Impact:** Demonstrates advanced database design and secure multi-tenant structure for enterprise reporting.

### 2. Automated KPI Audit Modeling
* **The Build:** Built an automated pipeline taking mock HRIS SQL output and pushing it into Excel to evaluate missing KPIs and trigger tiered leadership reminders.
* **Tech Stack:** PostgreSQL, Microsoft Excel.
* **Impact:** Streamlines audit compliance and removes manual follow-up overhead across reporting lines.

### 🚧 Coming Soon

* **Financial Risk Analysis:** Model and predict financial risk indicators using time-series data to optimize portfolio allocation.
* **The Pragmatics of Job Adverts:** Build an NLP/ML model to evaluate what the pragmatics of a job ad reveal about a company's underlying organizational culture.

## 🛠️ I am familiar with:

| Category | Skills & Tools |
| :--- | :--- |
| **BI & Analytics** | <img src="https://img.shields.io/badge/Power_BI-F2C811?style=flat&logo=powerbi&logoColor=black" alt="Power BI" /> <img src="https://img.shields.io/badge/Excel-217346?style=flat&logo=microsoft-excel&logoColor=white" alt="Excel" /> |
| **Databases** | <img src="https://img.shields.io/badge/Oracle_SQL-F80000?style=flat&logo=oracle&logoColor=white" alt="SQL" /> |
| **Scripting** | <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" /> <img src="https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white" /> <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black" /> <img src="https://img.shields.io/badge/Apps_Script-4285F4?style=flat&logo=google&logoColor=white" /> |
| **Version control & Tools** | <img src="https://img.shields.io/badge/VS_Code-0078D4?style=flat&logo=visual-studio-code&logoColor=white" /> <img src="https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white" /> <img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white" /> |
| **People Analytics** | <img src="https://img.shields.io/badge/Workday-005CB9?style=flat&logo=workday&logoColor=white" /> <img src="https://img.shields.io/badge/Dayforce-000000?style=flat&logo=ceridian&logoColor=white" /> |
---
