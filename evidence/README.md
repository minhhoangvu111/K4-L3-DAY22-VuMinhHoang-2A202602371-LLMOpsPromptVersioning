# Evidence status

Local checkpoint 4 was run through Guardrails and passed the six PII cases and five JSON cases. The two files `04_pii_demo_log.txt` and `04_json_demo_log.txt` contain actual script output.

`02_ab_routing_log.txt` contains a real local deterministic-routing check over 50 request IDs. It does not claim to be an LLM A/B run or Prompt Hub evidence.

The three PNG files are explicitly marked status cards, not screenshots. The attempted Checkpoint 1 run built 107 chunks and stopped when the environment rejected the outbound Gemini connection. Auto-review also blocked sending knowledge-base content and prompts to Gemini/LangSmith without explicit authorization. Therefore Prompt Hub publishing, 50+ traces, and RAGAS metrics remain unverified. `03_ragas_report.json` records this status with null scores; it is not a completed evaluation report.

After authorization and successful external runs, replace the three status cards and status report with genuine dashboard screenshots and RAGAS output.
