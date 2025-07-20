ai-agents-learning/
│
├── .gitignore             # Tells Git which files to ignore
├── README.md              # Project overview and instructions
├── requirements.txt       # Lists project dependencies
├── .env                   # Stores secret API keys
├── config.py              # Stores non-secret configurations
│
├── src/                   # Main source code directory
│   ├── __init__.py
│   ├── main.py            # Main script to run the application
│   │
│   ├── core/              # Core application logic
│   │   ├── __init__.py
│   │   └── agent.py       # Logic for AI agents
│   │
│   └── utils/             # Reusable helper functions
│       ├── __init__.py
│       └── file_handler.py# Functions for reading/writing files
│
├── data/                  # For all project data
│   ├── input/             # Raw data files (e.g., CSVs)
│   └── output/            # Generated files (e.g., summaries)
│
├── notebooks/             # Jupyter notebooks for experimentation
│
└── tests/                 # For test scripts
    ├── __init__.py
    └── test_agent.py