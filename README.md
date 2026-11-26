# llm-perf-benchmark
load-tests an LLM API (a local Ollama model). It measures TTFT, tokens/sec, P95 latency and cost per request at 1, 5 and 10 concurrent users, shows the results in Grafana, and runs in CI with an LLM-written pass/fail summary.
