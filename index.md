---
layout: home
title: Jalal Khalil
subtitle: Department of Computing, Informatics, and Data Science, St. Cloud State University
---
I am a tenure-track assistant professor of Computer Science at [St. Cloud State University](https://www.stcloudstate.edu/csit/default.aspx). I hold a Ph.D. in Computer Science from the University of Alabama at Birmingham (2023) and bring eight years of industry experience in cloud-based systems and software development.
My research focuses on geospatial data management, graph mining, and transportation simulation. I'm actively engaged in the academic community through conference reviews and program committees at top-tier venues including AAAI, ICDM, VLDB, WWW, ECIR and CIKM.

### **News**
<ul class="news-list">
{% assign news_items = site.data.news | sort: "date" | reverse %}
{% for item in news_items %}
  <li>
    {% if item.image %}
    <a href="{{ item.link | default: item.image }}" target="_blank">
      <img class="news-image" src="{{ item.image | relative_url }}" alt="{{ item.text }}">
    </a>
    {% endif %}
    <span class="news-date">{{ item.date | date: "%b %Y" }}</span>
    <span class="news-text">
      {% if item.link %}<a href="{{ item.link }}" target="_blank">{{ item.text }}</a>{% else %}{{ item.text }}{% endif %}
    </span>
  </li>
{% endfor %}
</ul>

### **Grants and Awards**
- St. Cloud State University Faculty Improvement Research Grant [Link](https://www.stcloudstate.edu/rsp/grants/internal/faculty-improvement.aspx){:target="_blank"}
- ICDE 2024 Best Demo Runner-Up Award
- SIGSPATIAL 2022 Best Paper Candidate
- ACM SIGSPATIAL GIS 2022 Travel Grant
- Innovation Bowl 2022-2023 Winner ($25,000) [Link](https://www.linkedin.com/posts/radiance-technologies_winning-team-selected-for-inaugural-radiance-activity-7062151574743089152-ykGI?utm_source=share&utm_medium=member_desktop){:target="_blank"}

### **Conference Review:**
- AAAI 2024, 2025, 2026
- ICDM 2025, 2026
- SIGSpatial 2026
- WWW 2026
- ECIR 2026
- TKDE 2025
- CIKM 2022, 2023-2026
- ACM SIGMOD ARI 2023
- IEEE BIGDATA 2024, 2025
- BIOKDD 2024
- LSGDA 2024
- AIGC 2023
- National Conference on Undergraduate Research (NCUR)

### **Journal Review:**
- VLDB Journal 2025, 2026
- The Journal of Supercomputing
- Data Mining and Knowledge Discovery

### **Internships**
- **Engineering Intern** (June 2022 - Aug. 2022)\
    [Shipt](https://www.shipt.com){:target="_blank"}\
    Search and Recommendation Team
    - Worked on a spelling correction project using Python.
    - Worked on a query understanding project using Go language.
    - Read papers about E-commerce product search and recommendations.
    - Hands-on tools and technologies such as Kafka, Docker, Snowflake, and others.

### **Experience**
- **Cloud Engineer** (2013 - 2017)\
[Logitude](https://logitudeworld.com){:target="_blank"}\
    Responsible for cloud infrastructure and deployments
    - Deploy the weekly hotfixes and monthly releases
    - Manage pre-production and test versions
    - Manage and monitor SQL database backups, alerts, indexes, and performance
    - Manage the releases workflow with quality assurance and customer care teams
    - Backup tools for Azure storage and databases
    - Create tools to automate repetitive tasks, evaluate implementations, and provide feedback for tool improvements
    - Troubleshoot and identify performance, connectivity and other issues for the applications hosted on the Azure platform

- **Software Engineer** (2009 - 2013)\
[Logitude](https://logitudeworld.com){:target="_blank"}\
    As a startup, I have worked on the first prototypes to create Logitude Platform using C#, Silverlight, SQL, .Net, Microsoft Azure and more\
    Some solo projects using C#:
    - XML to Silverlight conversion tool
    - SQL Azure database backup
    - Azure storage backup

