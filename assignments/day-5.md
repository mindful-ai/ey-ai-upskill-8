### 5.1 Langraph [10]

- Ref: 23-langgraph-orchestration\langgraph-tutorial-workbook-solutions.ipynb
- Run the notebook and observe the details of the workflow

------------------------------------------------------------------------
10:50 - 11:00 Exercise 5.1
11:00 - 11:20 Tea Break
------------------------------------------------------------------------

### 5.2 Database Agent [10]

- Ref: 23-langgraph-orchestration\db-graph.py
- Ref: 23-langgraph-orchestration\db-graph-parallel.py
- Execute, Observe, Understand the graph

------------------------------------------------------------------------
12:05 - 12.15 Exercise 5.2
------------------------------------------------------------------------

### 5.3 Langsmith - Observability - Debug [15]

- Ref: 24-langsmith-observability
- Run 24-langsmith-observability\01-db-graph-buggy-code-tracing.py
- Observe in Langsmith web interface
- Correct the code by uncommenting the sections to resolve the issue
- Re-run the code again

------------------------------------------------------------------------
12:50 - 1:05 Exercise 5.3
------------------------------------------------------------------------


------------------------------------------------------------------------
1:35 - 2:30 Lunch Break
------------------------------------------------------------------------


### 5.4 Capstone Project - Multi-agent Cyber Copilot [120]

- Disucssions and case study
- Exploration of architecture
- Hands-on 
  - Setup .env:
    OPENAI_API_KEY=<your key>
    GROQ_API_KEY=<your key>
    PINECONE_API_KEY=<your key>
    PINECONE_INDEX_NAME=cyber-security
    GROQ_MODEL=llama-3.3-70b-versatile
  - Run the tests
    - python -m tests.test_namespaces
    - python -m tests.test_retrieval
  - Run the main app and test with some queries
    - python main.py
    
------------------------------------------------------------------------
4:20 - 5:00 Capstone Hands-on
------------------------------------------------------------------------