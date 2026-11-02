<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1F4E79,100:2E7DBF&height=190&section=header&text=Afra%20Firdaus%20Momin&fontSize=46&fontColor=ffffff&fontAlignY=36&desc=AI%20Data%20Quality%20Specialist%20%C2%B7%20Python%20%C2%B7%20SQL&descSize=20&descAlignY=58" width="100%" alt="Afra Firdaus Momin, AI Data Quality Specialist"/>

<p align="center">
  <a href="https://afra-ozi.github.io/afra-ozi/"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=21&duration=3200&pause=900&color=2E7DBF&center=true&vCenter=true&width=700&lines=assert+data.is_clean()+%23+Better+data+for+better+AI;evaluate(llm_responses)+%7C+rate(search%2C+ads%2C+maps);annotate(text%2C+image%2C+audio)+%2B+audit(everything);10%2B+years+of+QA+%26+research+%7C+MCA+%7C+Python+%26+SQL" alt="Typing headline"/></a>
</p>

<p align="center">
  <a href="https://afra-ozi.github.io/afra-ozi/"><img src="https://img.shields.io/badge/Portfolio-View%20my%20site-1F4E79?style=for-the-badge&logo=githubpages&logoColor=white" alt="Portfolio"></a>
  <a href="https://www.linkedin.com/in/afra-firdaus-46a99b286"><img src="https://img.shields.io/badge/LinkedIn-Afra%20Momin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:afraomairgamer@gmail.com"><img src="https://img.shields.io/badge/Email-Hire%20me-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <img src="https://img.shields.io/badge/Open%20to-Remote%20roles-2ea44f?style=for-the-badge" alt="Open to remote roles"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/projects-9-1F4E79?style=flat-square" alt="9 projects"/>
  <img src="https://img.shields.io/badge/unit%20tests-36%20passing-2ea44f?style=flat-square" alt="36 unit tests passing"/>
  <img src="https://img.shields.io/badge/dependencies-zero-2ea44f?style=flat-square" alt="Zero dependencies"/>
  <img src="https://img.shields.io/badge/license-MIT-blue?style=flat-square" alt="MIT license"/>
</p>

---

## `$ whoami`

```python
# afra.py
from dataclasses import dataclass


@dataclass(frozen=True)
class Afra:
    name: str = "Afra Firdaus Momin"
    role: str = "AI Data Quality Specialist"
    based_in: str = "Malegaon, Maharashtra, India (remote)"
    years_in_data_qa: int = 10
    education: str = "MCA, Savitribai Phule Pune University"
    certifications: tuple = (
        "Generative AI: Prompt Engineering Basics (IBM, 2023)",
        "Oracle DBA & PL/SQL (2016)",
    )
    recent_work: tuple = (
        "evaluated and compared LLM responses",
        "rated search, ads, maps & social content",
        "annotated text, image & audio training data",
    )
    stack: tuple = ("Python", "SQL", "Oracle PL/SQL", "SQLite", "Git", "Excel")

    def mission(self) -> str:
        return "Better data for better AI."


if __name__ == "__main__":
    me = Afra()
    print(f"{me.name} | {me.role}")
    print(me.mission())
```

I help make AI systems more accurate by producing and checking the data they learn from. I have **10+ years** in research,
data validation and quality assurance, and most recently, at **Appen**, I rated search results and ads, evaluated **LLM chatbot responses** and
annotated training data. The tools below are the scripts I wish every labeling team had: small, tested and
easy to read.

## 🔁 My quality loop, and the tool for each step

```mermaid
flowchart LR
    A["📘 Guidelines"] --> B["🏷️ Annotate & rate"]
    B --> C["🎯 Audit a sample"]
    C --> D["🤝 Check agreement"]
    D --> E["📊 Measure quality"]
    E --> F["🧑‍🏫 Feedback & training"]
    F --> A
```

| Step | What I do | Tool in this profile |
|---|---|---|
| 📘 Guidelines | Turn a rulebook into prompts and checklists | [prompt-engineering-playbook](https://github.com/afra-ozi/prompt-engineering-playbook) |
| 🏷️ Annotate & rate | Score LLM answers against a rubric | [llm-eval-scorer](https://github.com/afra-ozi/llm-eval-scorer) |
| 🎯 Audit a sample | Pick a fair, reproducible QA sample | [qa-audit-sampler](https://github.com/afra-ozi/qa-audit-sampler) |
| 🤝 Check agreement | Cohen's & Fleiss' kappa, items to adjudicate | [annotation-agreement](https://github.com/afra-ozi/annotation-agreement) |
| 📊 Measure quality | NDCG, MRR, validation rules, SQL checks | [search-relevance-metrics](https://github.com/afra-ozi/search-relevance-metrics), [data-quality-checker](https://github.com/afra-ozi/data-quality-checker), [sql-data-validation](https://github.com/afra-ozi/sql-data-validation) |
| 🧑‍🏫 Feedback & training | Productivity reports and a guideline quiz | [annotator-productivity-report](https://github.com/afra-ozi/annotator-productivity-report), [guideline-quiz](https://github.com/afra-ozi/guideline-quiz) |

## 🚀 Projects

Every code project is **standard-library Python 3.9+ with unit tests, sample data and a README**: clone it and run it.

| Project | What it does | Tech |
|---|---|---|
| 🏷️ [**annotation-agreement**](https://github.com/afra-ozi/annotation-agreement) | Inter-annotator agreement: Cohen's & Fleiss' kappa, plus an adjudication list | Python |
| 🤖 [**llm-eval-scorer**](https://github.com/afra-ozi/llm-eval-scorer) | Weighted rubric scoring for LLM responses + side-by-side win rates | Python |
| 🔍 [**search-relevance-metrics**](https://github.com/afra-ozi/search-relevance-metrics) | NDCG@k, Precision@k & MRR from human relevance ratings | Python |
| ✅ [**data-quality-checker**](https://github.com/afra-ozi/data-quality-checker) | Rule-based CSV validation: required, unique, regex, allowed values, ranges | Python · JSON |
| 🗄️ [**sql-data-validation**](https://github.com/afra-ozi/sql-data-validation) | SQL data-quality checks with a PASS/FAIL runner | SQL · SQLite |
| 🧩 [**prompt-engineering-playbook**](https://github.com/afra-ozi/prompt-engineering-playbook) | Prompt patterns, rewrites & an LLM evaluation checklist | Markdown |
| 🎯 [**qa-audit-sampler**](https://github.com/afra-ozi/qa-audit-sampler) | Stratified, reproducible QA audit samples by annotator & label | Python CLI |
| 📊 [**annotator-productivity-report**](https://github.com/afra-ozi/annotator-productivity-report) | Tasks/hour, handling time & QA pass rate, with check-in flags | Python CLI |
| 📝 [**guideline-quiz**](https://github.com/afra-ozi/guideline-quiz) | Terminal quiz that trains raters on guideline edge cases | Python CLI · JSON |

### Try one in 10 seconds

```bash
git clone https://github.com/afra-ozi/guideline-quiz.git
cd guideline-quiz
python quiz.py questions.json --answers sample_answers.txt
```

```text
Score: 8/10 (80%), PASS (pass mark 80%)

By topic:
  llm-rating     2/3
  annotation     2/3
  relevance      3/3
  safety         1/1
```

## 🛠️ Skills & tools

**Code & data**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=sqlite&logoColor=white)
![Oracle PL/SQL](https://img.shields.io/badge/Oracle%20PL%2FSQL-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Excel](https://img.shields.io/badge/MS%20Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![Google Workspace](https://img.shields.io/badge/Google%20Workspace-4285F4?style=for-the-badge&logo=google&logoColor=white)
![Java](https://img.shields.io/badge/Java%20(basics)-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![C#](https://img.shields.io/badge/C%23%20(basics)-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)

**AI data & quality**

![LLM Evaluation](https://img.shields.io/badge/LLM%20Evaluation-1F4E79?style=for-the-badge)
![Prompt Engineering](https://img.shields.io/badge/Prompt%20Engineering-1F4E79?style=for-the-badge)
![Data Annotation](https://img.shields.io/badge/Data%20Annotation-1F4E79?style=for-the-badge)
![Search Quality Rating](https://img.shields.io/badge/Search%20Quality%20Rating-1F4E79?style=for-the-badge)
![Ads & Maps Rating](https://img.shields.io/badge/Ads%20%26%20Maps%20Rating-1F4E79?style=for-the-badge)
![QA Audits](https://img.shields.io/badge/QA%20Audits-1F4E79?style=for-the-badge)
![Data Validation](https://img.shields.io/badge/Data%20Validation-1F4E79?style=for-the-badge)
![Secondary Research](https://img.shields.io/badge/Secondary%20Research-1F4E79?style=for-the-badge)

## 💼 Experience

<details open>
<summary><b>Search Engine Evaluator & AI Data Specialist</b> · Appen (Remote) · 2024 – 2026</summary>

- Rated the relevance and quality of search results against detailed rater guidelines
- Evaluated and compared LLM chatbot responses for accuracy, helpfulness and safety; wrote prompts and feedback for model training
- Assessed ads relevance, maps/local listings and social media content for quality and policy compliance
- Annotated text, image and audio data for machine-learning training sets

</details>

<details>
<summary><b>Quality Analyst</b> · Datamatics Business Solutions Ltd · Jul 2019 – 2024</summary>

- Data annotation and labeling with a focus on accuracy and consistency
- Applied complex client guidelines to categorization, labeling and quality review

</details>

<details>
<summary><b>Senior Research Associate</b> · Datamatics Business Solutions Ltd · Apr 2015 – Jun 2017</summary>

- Analyzed incoming projects against client requirements to estimate effort and turnaround time
- Maintained project tracking and resource utilization reports for management

</details>

<details>
<summary><b>Research Associate</b> · Datamatics Business Solutions Ltd · Apr 2012 – Apr 2015</summary>

- Researched and validated entity data from search engines and secondary sources
- Ran quality checks on other researchers' work, allocated work across the team and trained new researchers
- Formatted and cleaned data in MS Excel; managed backups, updates and data retrieval

</details>

## 🎓 Education & certifications

| | |
|---|---|
| 🎓 **MCA**, Master of Computer Applications (2020) | Dr. B.V. Hiray College of Management & Research Center, Savitribai Phule Pune University |
| 🎓 **B.Sc. Information Technology** | Akbar Peerbhoy College |
| 📜 **Generative AI: Prompt Engineering Basics** (Feb 2023) | IBM via Coursera |
| 📜 **Oracle DBA & PL/SQL** (2016) | Karrox Technology |

## 📫 Let's connect

Open to **remote roles in AI training data, LLM evaluation, search/ads quality rating and data QA**.

- 📧 [afraomairgamer@gmail.com](mailto:afraomairgamer@gmail.com)
- 💼 [LinkedIn](https://www.linkedin.com/in/afra-firdaus-46a99b286)
- 🌐 [afra-ozi.github.io/afra-ozi](https://afra-ozi.github.io/afra-ozi/)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2E7DBF,100:1F4E79&height=110&section=footer" width="100%" alt=""/>
