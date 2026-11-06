# Databricks Bootcamp 2026

[![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@datawithbaraa) [![Website](https://img.shields.io/badge/datawithbaraa.com-111111?style=for-the-badge&logo=googlechrome&logoColor=white)](https://www.datawithbaraa.com) [![License](https://img.shields.io/github/license/DataWithBaraa/databricks_bootcamp_2026?style=for-the-badge&color=2EA043)](LICENSE) [![Stars](https://img.shields.io/github/stars/DataWithBaraa/databricks_bootcamp_2026?style=for-the-badge&color=F5B301)](https://github.com/DataWithBaraa/databricks_bootcamp_2026)

The materials of the Databricks bootcamp project: the source files and every notebook of the data lakehouse, from bronze to gold.

⭐ If this project helps you, star the repository so other learners can find it too.

**Build it on your own first.** Follow the [Notion roadmap](https://candle-gosling-511.notion.site/Project-Building-the-Bike-Data-Lakehouse-2e734b251f1280ab8dadc269e033cc38?source=copy_link) step by step, and open the notebooks here only when you get stuck. The [bootcamp on YouTube](https://www.youtube.com/playlist?list=PLNcg_FV9n7qZoxVkw-KPhcmgLWjHWVUc9) explains the architecture and every decision.

```
databricks_bootcamp_2026/
├── datasets/
│   ├── analysts/              the sales and HR data of Day 1
│   └── engineering/           the CRM and ERP source files of Day 2
└── script/                    the notebooks, in the order of the bootcamp
    ├── init_lakehouse.ipynb   creates the bronze, silver and gold schemas and the volume for the raw files: run it first
    ├── bronze/                loads the raw files
    ├── silver/                cleans the CRM and ERP tables
    └── gold/                  builds the dimensions and the fact table
```

You need basic SQL and Python, and a little PySpark. No Databricks experience is needed. Finished? Share it on [LinkedIn](https://www.linkedin.com/in/baraa-khatib-salkini/) and let's celebrate.

---

## 🏗️ Architecture

The project follows the medallion architecture:

1. **Bronze layer:** the raw files, stored as Delta tables as they arrive.
2. **Silver layer:** the data cleaned, standardized and typed.
3. **Gold layer:** a dimensional model, ready for BI and analysis.

Tools: Databricks, Apache Spark, PySpark, Spark SQL, Delta Lake and Unity Catalog.

---

## 🎓 Learn with me

Watch on YouTube, or take the guided version with a certificate on my Academy or Udemy.

| Course | YouTube | My Academy | Udemy |
|:--|:--|:--|:--|
| **SQL** | [Full course](https://youtu.be/SSKVgrwhzus) · [Playlist](https://www.youtube.com/playlist?list=PLNcg_FV9n7qZY_2eAtUzEUulNjTJREhQe) | [Full Package](https://www.datawithbaraa.com/course/sql-full-course-for-beginners) · [Handbook](https://academy.datawithbaraa.com/l/digital_download/1087406/the-sql-handbook) | [SQL Bootcamp](https://www.udemy.com/course/the-complete-sql-bootcamp-30-hours-go-from-zero-to-hero/?referralCode=D20781228C2EB8B98339) · [SQL for Analytics](https://www.udemy.com/course/sql-mastery-for-data-analytics-and-business-intelligence/) |
| **Python** | [Full course](https://youtu.be/Rq5gJVxz55Q) · [Playlist](https://www.youtube.com/playlist?list=PLNcg_FV9n7qZGfFl2ANI_zISzNp257Lwn) | [Full Package](https://www.datawithbaraa.com/course/the-ultimate-python-mastery) · [Handbook](https://academy.datawithbaraa.com/l/digital_download/998313/the-python-handbook) | [Python Bootcamp](https://www.udemy.com/course/the-complete-python-bootcamp-13hours-go-from-zero-to-hero/?referralCode=776491A4119FF8AF41CA) |
| **Tableau** | [Full course](https://youtu.be/K3pXnbniUcM) · [Playlist](https://www.youtube.com/playlist?list=PLNcg_FV9n7qZJqrKcUUCWCWPYCrlcVm9v) | [Full Package](https://www.datawithbaraa.com/course/tableau-ultimate-full-course-for-beginners) | [Tableau Course](https://www.udemy.com/course/the-tableau-ultimate-course-from-zero-to-hero/?referralCode=6544726FDC491A6B25EC) · [Chart Masterclass](https://www.udemy.com/course/the-tableau-ultimate-chart-masterclass-63-tableau-charts/) |
| **Power BI** | [Full course](https://www.youtube.com/playlist?list=PLNcg_FV9n7qZge4KDGqGtqgiuVuhVZWzu) | | |
| **Databricks** | [Full course](https://www.youtube.com/playlist?list=PLNcg_FV9n7qZWchr-GE5iPPBmOjiffK6O) | | |

Materials on my website: [SQL](https://www.datawithbaraa.com/wiki/sql) · [Python](https://www.datawithbaraa.com/wiki/python) · [Tableau](https://www.datawithbaraa.com/wiki/tableau) · [Power BI](https://www.datawithbaraa.com/wiki/power-bi)

### The Databricks bootcamp

| Day | YouTube | Materials |
|:--|:--|:--|
| **Day 1: Introduction and Data Analytics** | [Watch](https://youtu.be/sxYcjDrMyNc) | `datasets/analysts` |
| **Day 2: Data Engineering** | [Watch](https://youtu.be/ldBLOasG23w) | `datasets/engineering` and `script` |
| **Free resources** | [The playlist](https://www.youtube.com/playlist?list=PLNcg_FV9n7qZoxVkw-KPhcmgLWjHWVUc9) | [Bootcamp Free Resources](https://academy.datawithbaraa.com/l/pdp/databricks-live-bootcamp-free1) |

More on YouTube: [Data projects](https://www.youtube.com/playlist?list=PLNcg_FV9n7qZ4Ym8ZriYT6WF8TaC2e_R7) · [Data careers](https://www.youtube.com/playlist?list=PLNcg_FV9n7qah95jp-aPtysu7kFCbg7hd)

## 🤝 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge)](https://www.linkedin.com/in/baraa-khatib-salkini/) [![Discord](https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/gsVJbMxKcA) [![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/datawithbaraa/) [![TikTok](https://img.shields.io/badge/TikTok-000000?style=for-the-badge&logo=tiktok&logoColor=white)](https://www.tiktok.com/@datawithbaraa) [![Newsletter](https://img.shields.io/badge/Newsletter-FF6719?style=for-the-badge&logo=substack&logoColor=white)](https://www.blog.datawithbaraa.com) [![Notion Roadmaps](https://img.shields.io/badge/Notion_Roadmaps-000000?style=for-the-badge&logo=notion&logoColor=white)](https://www.notion.com/@datawithbaraa)

## 🛡️ License

[MIT](LICENSE). Use it, change it, share it, with attribution.

## 🌟 About me

Hi, I'm **Baraa Khatib Salkini**. I spent years in enterprise data engineering and built one of the largest lakehouses at Mercedes-Benz. Today I teach data full-time at **Data With Baraa**: visually, step by step, from zero to hero.
