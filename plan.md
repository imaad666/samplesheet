dummy-pipeline/
├── clients/
│   ├── jira_client.py      # fetch bugs/stories
│   └── qtest_client.py     # fetch test runs
├── mappers/
│   ├── jira_mapper.py      # reshape Jira data
│   └── qtest_mapper.py     # reshape qTest data
├── loader/
│   └── smartsheet_loader.py # write to Smartsheet
├── chatbot/
│   └── chat.py             # AI chatbot that reads Smartsheet
├── run.py                  # runs the whole pipeline
├── .env                    # your tokens (git-ignored)
└── requirements.txt