# Weekly digests

### Weekly Digest

_2026-10-12_ 

What I verified in AI this week: a mix of MCP servers, agentic frameworks, and inference tools. 

1/ 🧵

I spent time digging into the Model Context Protocol (MCP) ecosystem. 

Found: morluto/rea. It’s an MCP server for reverse engineering. It uses bridges for Ghidra and Hopper to return assembly and pseudocode directly to the agent. 
https://github.com/morluto/rea

Also found: mksglu/context-mode. It manages context window bloat by sandboxing tool outputs and indexing session data in SQLite using FTS5. Useful for keeping Claude Code or Cursor from getting overwhelmed. 
https://github.com/mksglu/context-mode

Claim Check: BitterSecurity/Decepticon. The README claims a 98.08% pass rate on XBOW benchmarks. I looked into the codebase; it uses LangGraph for orchestration and includes specific benchmarking infrastructure in `benchmark/cve_bench` to back this up. 
https://github.com/BitterSecurity/Decepticon

Claim Check: NirDiamant/RAG_Techniques. Verified the implementation of various patterns like HyDE and GraphRAG. The repo contains 42+ notebooks and dedicated evaluation scripts, not just theoretical descriptions. 
https://github.com/NirDiamant/RAG_Techniques

Finally, looking at inference: sgl-project/sglang. It’s a substantive framework hosted by LMSYS. I checked the codebase for technical profiling tools; it includes scripts like `analyze_sglang_torch_profile.py` for kernel triage. 
https://github.com/sgl-project/sglang

That's it for this week. Back to the code.
