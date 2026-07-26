<div align="center">
  <h2>Hi, I'm Lili 👋</h2>
  <p>
    <a href="mailto:tothlilikornelia@gmail.com"><img src="https://img.shields.io/badge/-Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
    <a href="https://www.linkedin.com/in/lili-kornelia-toth-a83228268/"><img src="https://img.shields.io/badge/-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  </p>
</div>

---

## 👩🏻‍💻 About me

```python
from dataclasses import dataclass, field

@dataclass
class LiliToth:
    expertise: str = "Business Analytics"
    experience_years: int = 3
    domain: str = "HR Data Analytics (Matrix Organization)"
    
    education: dict[str, str] = field(default_factory=lambda: {
        "BA": "Linguistics",
        "BSc": "Computer Science (ongoing)"
    })
    
    tech_stack: set[str] = field(default_factory=lambda:  {
        "Data pipelines", "SQL", "Python", "Advanced Excel", "ML"
    })
    
    motivations: list[str] = field(default_factory=lambda: [
        "Versitality of data analytics",
        "Creating order in chaos and learning its secrets"
    ])
    
    origin_story: str = (
        "Learned to code out of spite to avoid manually analysing large research datasets during my BA "
        "fell in love "
        "never looked back. "
    )

    @property
    def hobbies(self) -> dict[str, str | dict]::
        return {
            "outdoor": "Thru-hiking",
            "indoor": "Cooking",
            "languages": {
                "types": ["Human", "Computer"],
                "philosophy": "Syntax is syntax."
            }
        }

if __name__ == "__main__":
    me = LiliToth()
```
## 🏢 Featured projects for Business Analytics
### 1. HRIS database modeling in PostgreSQL (<a href="https://github.com/tothlilikornelia/creating-hris-database-in-sql/">Link to repository</a>  )
* **The Build:** Engineered a realistic HR dataset and transformed complex organizational hierarchies into a BI-ready reporting layer.
* **Tech Stack:** PostgreSQL (CTEs, Window functions, Row & Column level security).
* **Impact:** Demonstrates advanced database designing, including real-life-like domain rules and data governance for a fictional organisation with 3000 employee, including key performance metrics and full reporting lines.
  
### 2. KPI audit modeling
* **The Build:** Built an automated pipeline taking mock HRIS SQL output and pushing it into Excel to evaluate missing KPIs and trigger tiered leadership reminders.
* **Tech Stack:** PostgreSQL, Microsoft Excel.
* **Impact:** Streamlines audit compliance and removes manual follow-up overhead across reporting lines.

### 🚧 Coming soon

* **Financial risk analysis:** Modelling and predicting financial risk indicators using time-series data to optimize portfolio allocation.
* **The pragmatics of job adverts:** Building an NLP/ML model to evaluate what the pragmatics of a job ad reveal about a company's underlying organisational culture.

## 🛠️ I am familiar with:

| Category | Skills & Tools |
| :--- | :--- |
| **BI & Analytics** | <img src="https://img.shields.io/badge/Power_BI-F2C811?style=flat&logo=powerbi&logoColor=black" alt="Power BI" /> <img src="https://img.shields.io/badge/Excel-217346?style=flat&logo=microsoft-excel&logoColor=white" alt="Excel" /> |
| **Databases** | <img src="https://img.shields.io/badge/Oracle_SQL-F80000?style=flat&logo=oracle&logoColor=white" alt="SQL" /> |
| **Scripting** | <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" /> <img src="https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white" /> <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black" /> <img src="https://img.shields.io/badge/Apps_Script-4285F4?style=flat&logo=google&logoColor=white" /> |
| **Version control & Tools** | <img src="https://img.shields.io/badge/VS_Code-0078D4?style=flat&logo=visual-studio-code&logoColor=white" /> <img src="https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white" /> <img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white" /> |
| **People Analytics** | <img src="https://img.shields.io/badge/Workday-005CB9?style=flat&logo=workday&logoColor=white" /> <img src="https://img.shields.io/badge/Dayforce-000000?style=flat&logo=ceridian&logoColor=white" /> |
---
