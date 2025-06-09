# Lead-Generation
leadgen-app/
├── app.py
├── templates/
│   ├── index.html
│   └── dashboard.html
├── static/
│   └── style.css
├── requirements.txt
├── Procfile (Heroku)
├── runtime.txt
├── .env (add to .gitignore)
├── README.md
└── utils/
    ├── email.py
    ├── crm_integration.py
    ├── db_cosmos.py
    └── db_table_storage.py

✅ GitHub Repo: Lead Generation App – Production-Ready
🔧 Core Features:
Flask-based form handling

SQLite (default) or optional Cosmos DB / Azure Table Storage backend

Email confirmation via Flask-Mail

⚙️ Optional Features Included:
✅ Email confirmation (Flask-Mail)

✅ CRM integrations (Zapier Webhook, Google Sheets API, HubSpot API)

✅ Analytics dashboard (/dashboard route)

✅ Deployment configs:

Render, Heroku, and Azure App Service

✅ Cosmos DB + Azure Table Storage options

✅ .env support for secrets

✅ requirements.txt, Procfile, runtime.txt

World Bank Economic & Social Indicators Dataset
=================================================

This dataset was automatically generated using the World Bank API. It includes the following indicators:

  - GDP (current US$)
  - Population
  - Life Expectancy at Birth (years)
  - Unemployment Rate (%) (modeled ILO estimate)

The dataset covers the years 2010 to 2020 for all available countries and is enriched with country metadata
including region, income level, capital city, longitude, and latitude.

Data Sources:
  - World Bank Indicators API: http://api.worldbank.org
  - World Bank Country Metadata API: http://api.worldbank.org

License:
  This dataset is public domain as it is compiled from publicly available World Bank data.

Dataset File:
  world_bank_dataset.csv

Creation Date:
  2025-03-09

Usage:
  This dataset is ready for use in data analysis, visualization, or modeling projects.

=================================================
