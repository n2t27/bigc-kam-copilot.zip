# Big C KAM copilot

Sample project from my newsletter *Commercial AI & Intelligence Insight*:
A Key Account Management copilot built on the Claude API. All data is sample data.

Download `bigc-kam-copilot.zip`, unzip it, then:

    pip install -r requirements.txt
    python selftest.py
    python kam_copilot.py review --offline

What's inside:

- `kam_copilot.py`: weekly review + Q&A with tools
- `bigc_mcp_server.py`: the same data as an MCP server
- `selftest.py`: 18 checks, no API key needed
- `data/`: sample sell-out CSV (4 weeks, 4 stores, 5 SKUs) and a sample TTA
