# Verified trending AI repos

### [supabase/agent-skills](https://github.com/supabase/agent-skills)

_2026-10-14_ `technical_verification`

The `supabase/agent-skills` repository provides structured markdown-based documentation designed to be consumed by AI agents (like Claude Code, Cursor, or Cline) to improve their accuracy when working with Supabase and Postgres. Notable: Uses the agentskills.io format.; Includes `.mcp.json` for Model Context Protocol support.; Contains specific technical references for Postgres (e.g., JSONB indexing, RLS performance) rather than just high-level guides.; Installation is via `npx skills add`.. Category: technical_verification. Legitimacy 1.00, code backs claims: yes. (2817 stars, +27 daily, TypeScript)

### [karpathy/nn-zero-to-hero](https://github.com/karpathy/nn-zero-to-hero)

_2026-10-14_ `verification`

The `karpathy/nn-zero-to-hero` repository is a collection of Jupyter notebooks that implement the neural network concepts from Andrej Karpathy's lecture series. The file structure matches the README curriculum, providing code for `micrograd` (backpropagation), `makemore` (bigrams, MLPs, BatchNorm, and CNNs), and a GPT-style transformer. The notebooks are organized by lecture, covering the progression from basic calculus to tokenization. Notable: The file tree directly reflects the lecture progression described in the README.; The repository contains actual implementation code (7 code files) rather than just documentation.. Category: verification. Legitimacy 1.00, code backs claims: yes. (24798 stars, +35 daily, Jupyter Notebook)

### [UFund-Me/Qbot](https://github.com/UFund-Me/Qbot)

_2026-10-14_ `quantitative-trading`

A quantitative investment platform that integrates machine learning (via qlib) and backtesting (via backtrader) with a GUI built on wxPython. Notable: Integrates qlib for deep learning strategies; Uses backtrader for backtesting; Modular backend with a multi-factor learner. Category: quantitative-trading. Legitimacy 1.00, code backs claims: yes. (18641 stars, +37 daily, Jupyter Notebook)

### [Tencent/teamai-cli](https://github.com/Tencent/teamai-cli)

_2026-10-14_ `software_engineering`

A CLI tool that uses a Git repository to sync AI assets—such as rules, agents, and MCP servers—across a team. Notable: 279 code files; Includes src/ directory and agent definitions in agents/; Contains technical design docs for git-native-memory and model-profiles; Includes unit tests and CI workflows. Category: software_engineering. Legitimacy 1.00, code backs claims: yes. (5426 stars, +37 daily, TypeScript)

### [sgl-project/sglang-omni](https://github.com/sgl-project/sglang-omni)

_2026-10-13_ `verification`

The sgl-project/sglang-omni repository is a serving framework for audio (TTS, ASR) and multimodal models, built as an extension of SGLang. Notable: The codebase is substantial, with over 300 code files including Python for the runtime, Rust for routing, and a Swift/Xcode project (Voxt) for a macOS voice interface.; The README claims support for specific models like Qwen3-Omni and various TTS engines; the file tree confirms this with dedicated CI workflows (e.g., `test-qwen3-omni-ci.yaml`, `test-tts-ci.yaml`).; The project includes complex infrastructure for multi-stage decoding and distributed inference.. Category: verification. Legitimacy 1.00, code backs claims: yes. (1437 stars, +42 daily, Python)

### [rohitg00/agentmemory](https://github.com/rohitg00/agentmemory)

_2026-10-13_ `AI/Software Engineering`

Provides a persistent memory layer for AI coding agents (Claude Code, Cursor, etc.) using the iii engine. Notable: Uses hybrid search (BM25 and vector/graph search); Supports local embeddings via HuggingFace transformers; Includes specific plugin configurations for multiple agent environments. Category: AI/Software Engineering. Legitimacy 0.90, code backs claims: partly. (29388 stars, +49 daily, TypeScript)

### [googleworkspace/cli](https://github.com/googleworkspace/cli)

_2026-10-13_ `software_engineering`

A Rust-based CLI that builds its command surface at runtime using Google's Discovery Service. Notable: Uses `discovery.rs` to map APIs dynamically instead of using a static command list.; Includes `generate_skills.rs` to create agent-ready workflows.; Designed for structured JSON output to support agentic integration.. Category: software_engineering. Legitimacy 1.00, code backs claims: yes. (31460 stars, +50 daily, Rust)

### [microsoft/ai-agents-for-beginners](https://github.com/microsoft/ai-agents-for-beginners)

_2026-10-13_ `verification`

I looked through the file structure for microsoft/ai-agents-for-beginners. It's a structured curriculum rather than a single-file repo. The tree shows organized lessons (00-08) containing both Python notebooks (.ipynb) and C# files (.cs). It covers specific agentic patterns like tool use, RAG, and multi-agent orchestration using Semantic Kernel and AutoGen. The inclusion of .devcontainer and GitHub workflows makes it a functional dev environment for the course. It's a substantive project from Microsoft. Notable: Contains both Python and C# code samples; Includes .devcontainer for standardized environments; Covers Semantic Kernel and AutoGen. Category: verification. Legitimacy 1.00, code backs claims: yes. (77074 stars, +81 daily, Jupyter Notebook)

### [mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill)

_2026-10-13_ `verification`

The repository implements an AI agent skill using the Model Context Protocol (MCP). It provides a Go-based engine to fetch and synthesize data from social platforms like Reddit, X, and YouTube for use in agentic workflows. Notable: Contains a full Go implementation in the `mcp/` directory, including an engine for extraction, caching, and process management.; Includes detailed documentation in `docs/solutions/` regarding specific technical hurdles like entity grounding and source deduplication.; Designed to work with various agent environments (Claude Code, Cursor, etc.) via MCP and plugin specs.. Category: verification. Legitimacy 1.00, code backs claims: yes. (64140 stars, +103 daily, Python)

### [browser-use/video-use](https://github.com/browser-use/video-use)

_2026-10-13_ `technical_verification`

The repository provides a framework for using coding agents to perform video editing by converting video data into text-based transcripts and sparse visual composites (filmstrips/waveforms) rather than raw frames. Notable: Uses ElevenLabs Scribe for word-level timestamps and diarization.; Implements a 'timeline_view' PNG to provide visual context to LLMs without the token cost of frame-dumping.; Relies on ffmpeg for rendering and EDL (Edit Decision List) execution.; Integrates Manim for generating animation overlays.. Category: technical_verification. Legitimacy 0.85, code backs claims: partly. Red flags: High star-to-file ratio (28k stars for ~10 code files) is unusual and suggests high virality or potential star farming.. (28852 stars, +122 daily, Python)

### [rtk-ai/rtk](https://github.com/rtk-ai/rtk)

_2026-10-13_ `software_verification`

I looked into the rtk-ai/rtk repository. It is a Rust-based CLI proxy that intercepts shell commands to compress their output before an AI agent reads it. Notable: The tool uses a hook system to rewrite commands for agents like Claude Code, Cursor, and Copilot.; The file tree shows specific logic for summarizing different outputs: `ls` becomes a tree format, `cargo test` collapses passing tests into a count, and `git status` is condensed into a compact stat.; The README claims up to 90% reduction in bash output. This is a specific claim about the volume of text being sent to the LLM, not the total cost of the API call, which is a technically honest distinction.; They use a `bytes / 4` approximation for token counts to avoid shipping a heavy tokenizer.. Category: software_verification. Legitimacy 1.00, code backs claims: yes. (83188 stars, +131 daily, Rust)

### [krillinai/OpenCreator](https://github.com/krillinai/OpenCreator)

_2026-10-13_ `AI agents and agentic workflows`

An AI workspace for creators that uses Codex CLI as an execution engine to handle video translation, downloading, and agentic tasks. Notable: Uses a daemon-based architecture (apps/daemon); Includes MCP (Model Context Protocol) routes; Contains yt-dlp plugins for video handling; Uses a generated Codex-based communication protocol. Category: AI agents and agentic workflows. Legitimacy 1.00, code backs claims: yes. (12884 stars, +134 daily, TypeScript)

### [vercel-labs/skills](https://github.com/vercel-labs/skills)

_2026-10-13_ `AI agents / CLI tools`

A CLI tool to manage and install 'skills' (prompts or configurations) for AI agents like Claude Code or Cursor. Notable: Supports multiple git providers (GitHub, GitLab, Azure); Handles private repositories via existing git credentials; Includes a large test suite for installation and authentication flows. Category: AI agents / CLI tools. Legitimacy 1.00, code backs claims: yes. (34126 stars, +187 daily, TypeScript)

### [apify/apify-mcp-server](https://github.com/apify/apify-mcp-server)

_2026-10-13_ `AI Agents / MCP`

Provides an MCP server to connect AI agents to Apify's scraping and automation tools. Notable: Supports both hosted HTTPS and local stdio (via npx) transport.; Includes a dedicated evaluation suite in the /evals directory.; Uses 'agentic payments' to handle the cost of underlying scrapers.. Category: AI Agents / MCP. Legitimacy 1.00, code backs claims: yes. (10909 stars, +207 daily, TypeScript)

### [harry0703/MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo)

_2026-10-13_ `AI video generation / automation`

Automates short video creation by using LLMs for scripting, matching assets, generating subtitles, and adding background music. Notable: Substantive Python codebase with a modular service architecture (LLM, video, voice, subtitles).; Supports Docker deployment.; Heavily monetized via affiliate links and sponsorships in the README.; Extremely high star count (130k+) for a repository created in March 2024.. Category: AI video generation / automation. Legitimacy 0.85, code backs claims: yes. Red flags: High star-to-age ratio; Heavy affiliate marketing. (130435 stars, +404 daily, Python)

### [heygen-com/hyperframes](https://github.com/heygen-com/hyperframes)

_2026-10-13_ `verification`

A framework for generating MP4 videos from HTML, CSS, and GSAP animations, specifically designed to be used by AI agents. Notable: Provides structured 'skills' (via .md and .json) for agents like Claude Code or Cursor to follow a production loop.; Includes implementation scripts for caption alignment and motion logic.; Uses ffmpeg and puppeteer for the rendering pipeline.. Category: verification. Legitimacy 1.00, code backs claims: yes. (62186 stars, +831 daily, TypeScript)

### [intel/AI-PC-Samples](https://github.com/intel/AI-PC-Samples)

_2026-10-12_ `verification`

The `intel/AI-PC-Samples` repository is a collection of notebooks and scripts designed to demonstrate generative AI workloads on Intel hardware, specifically targeting iGPUs and NPUs. Notable: Includes implementations for LLM quantization and inference using SYCL and llama.cpp.; Contains RAG workflows using both LangChain and native PyTorch.; Features NPU-specific samples like image upscaling.; Uses modern dependency management tools like `uv` and `pixi` across different modules.. Category: verification. Legitimacy 1.00, code backs claims: yes. (73 stars, +0 daily, Jupyter Notebook)

### [onestardao/WFGY](https://github.com/onestardao/WFGY)

_2026-10-12_ `AI Agents / RAG`

Claims to be an open-source ecosystem for AI reasoning, RAG, and agents via the 'Polaris Protocol'. Notable: Extremely low code-to-documentation ratio (17 code files vs 400 total files).; Includes GitHub workflows for automated star and ecosystem engagement.; README contains explicit instructions for LLMs to follow specific verification protocols.. Category: AI Agents / RAG. Legitimacy 0.00, code backs claims: no. Red flags: Presence of star-farming/engagement bots in workflows.; Minimal executable code relative to the scale of claims.; README uses prompt-injection style instructions to guide LLM responses.; Heavy focus on theoretical PDFs and research papers rather than implementation.. (1796 stars, +1 daily, Jupyter Notebook)

### [rasbt/machine-learning-book](https://github.com/rasbt/machine-learning-book)

_2026-10-12_ `verification`

Verified the `rasbt/machine-learning-book` repository. It is the official code companion for Sebastian Raschka's book, *Machine Learning with PyTorch and Scikit-Learn*. Notable: The repo contains 67 code files organized by chapter.; It includes both Jupyter notebooks (.ipynb) and Python scripts (.py) for the examples.; Datasets used in the chapters, such as `iris.data` and `wine.data`, are included in the file tree.; The implementation covers a range of topics from basic Scikit-Learn classifiers to Transformers and Graph Neural Networks.. Category: verification. Legitimacy 1.00, code backs claims: yes. (5435 stars, +3 daily, Jupyter Notebook)

### [datawhalechina/llm-algo-leetcode](https://github.com/datawhalechina/llm-algo-leetcode)

_2026-10-12_ `technical_verification`

The `llm-algo-leetcode` repository by Datawhale China is a structured curriculum of Jupyter notebooks designed to teach LLM algorithms and systems engineering. It moves from high-level PyTorch implementations to low-level Triton and CUDA kernel optimization. Notable: Covers specific architectural components like RoPE, GQA, and MoE.; Includes post-training techniques such as LoRA, DPO, and GRPO.; Covers inference optimization topics including PagedAttention and speculative decoding.; Provides hardware-level content on VRAM calculation, NCCL, and quantization.. Category: technical_verification. Legitimacy 1.00, code backs claims: yes. (678 stars, +6 daily, Jupyter Notebook)

### [datawhalechina/llm-universe](https://github.com/datawhalechina/llm-universe)

_2026-10-12_ `AI/LLM`

A tutorial repository for LLM application development, specifically focused on RAG and LangChain. Notable: Contains a Chroma vector database (chroma.sqlite3) and various document types (JSON, PDF, TXT) for RAG examples.; Includes technical documentation on LangChain custom embeddings and LLM wrappers.; Structured as a curriculum rather than a single standalone application.. Category: AI/LLM. Legitimacy 1.00, code backs claims: yes. Red flags: no license. (14117 stars, +7 daily, Jupyter Notebook)

### [facebookresearch/audiocraft](https://github.com/facebookresearch/audiocraft)

_2026-10-12_ `AI Research/Audio Generation`

Provides a PyTorch library for audio generation and processing, including models like MusicGen, AudioGen, and EnCodec. Notable: Includes full implementations for models, loss functions, and evaluation metrics.; Requires PyTorch 2.1.0 and ffmpeg.; Supports both inference and training workflows.. Category: AI Research/Audio Generation. Legitimacy 1.00, code backs claims: yes. (23687 stars, +9 daily, Jupyter Notebook)

### [google/skills](https://github.com/google/skills)

_2026-10-12_ `AI Agents / Tooling`

Provides a registry of tool definitions (skills) for AI agents to interact with Google Cloud and other services. Notable: Supports MCP (Model Context Protocol); Supports Claude plugins; Supports Gemini extensions. Category: AI Agents / Tooling. Legitimacy 1.00, code backs claims: yes. (21202 stars, +66 daily, Python)

### [breferrari/obsidian-mind](https://github.com/breferrari/obsidian-mind)

_2026-10-12_ `verification`

Verified breferrari/obsidian-mind. It is a substantive project with a functional TypeScript codebase supporting its claims. Notable: Implements an MCP (Model Context Protocol) server for agent-vault communication.; Includes dedicated logic for memory operations (write, recall, similarity).; Features a comprehensive test suite for its internal scripts.; Uses Claude Code's command/agent structure for workflow automation.. Category: verification. Legitimacy 1.00, code backs claims: yes. (5239 stars, +82 daily, TypeScript)

### [open-webui/open-webui](https://github.com/open-webui/open-webui)

_2026-10-12_ `verification`

I looked through the `open-webui/open-webui` repository to see if the code matches the claims. It's a substantive project. The file tree shows a structured Python backend using Alembic for migrations, with dedicated modules for RAG, MCP, and model management. The architecture supports the complex workflows described in the README, and the deployment options like Docker and Kubernetes are clearly defined. For 150k stars, the issue count is relatively low, which suggests a mature or highly managed codebase. Notable: Python backend with Alembic migrations; Support for MCP and various vector databases; Multiple deployment paths (Docker, Kubernetes, pip). Category: verification. Legitimacy 1.00, code backs claims: yes. (154589 stars, +142 daily, Python)

### [1jehuang/jcode](https://github.com/1jehuang/jcode)

_2026-10-12_ `AI Coding Tools`

A Rust-based coding agent harness designed for low memory usage. Notable: Claims 27.8 MB PSS for one session (local embeddings off) vs 386.6 MB for Claude Code.; Contains 251 code files and a structured changelog.; Uses curl | bash for installation.. Category: AI Coding Tools. Legitimacy 0.90, code backs claims: yes. Red flags: curl | bash installation pattern; pipes a remote script to shell from an unknown host. (20555 stars, +160 daily, Rust)

### [Crosstalk-Solutions/project-nomad](https://github.com/Crosstalk-Solutions/project-nomad)

_2026-10-12_ `local_inference_and_rag`

An offline-first server that orchestrates Docker containers to provide Wikipedia, maps, and local AI (Ollama + Qdrant) on local hardware. Notable: Uses AdonisJS for the management backend; Includes built-in RAG pipeline and retrieval evaluation services; Orchestrates Kiwix and Kolibri for offline content. Category: local_inference_and_rag. Legitimacy 1.00, code backs claims: yes. (39610 stars, +168 daily, TypeScript)

### [microsoft/BitNet](https://github.com/microsoft/BitNet)

_2026-10-12_ `AI Infrastructure`

Inference framework for 1-bit (ternary) LLMs Notable: C++ kernels for CPU; CUDA kernels for GPU; Hugging Face weight conversion utilities. Category: AI Infrastructure. Legitimacy 1.00, code backs claims: yes. (40751 stars, +195 daily, C++)

### [multimodal-art-projection/YuE](https://github.com/multimodal-art-projection/YuE)

_2026-10-12_ `music-generation`

YuE2 is a music generation model that uses symbolic planning (ABC notation) to bridge composition and audio, allowing for editable melody and chord structures. Notable: Includes model definitions (modeling_yue2.py); Includes quantization and tokenization logic; Features an agentic workflow via a 'skills' directory; Has a comprehensive test suite (VAE, CUDA graphs, CLI). Category: music-generation. Legitimacy 1.00, code backs claims: yes. (11760 stars, +318 daily, Python)

### [OpenBMB/VoxCPM](https://github.com/OpenBMB/VoxCPM)

_2026-10-12_ `AI/Software Engineering`

A 2B parameter, tokenizer-free TTS system using a diffusion autoregressive architecture. Notable: Modular implementation of AudioVAE V2 and Local DiT; Supports 30 languages and 48kHz output; Includes training, fine-tuning (LoRA), and Docker configurations. Category: AI/Software Engineering. Legitimacy 1.00, code backs claims: yes. (39094 stars, +370 daily, Python)

### [tashfeenahmed/freellmapi](https://github.com/tashfeenahmed/freellmapi)

_2026-10-12_ `LLM Infrastructure`

Aggregates free LLM tiers into a single OpenAI-compatible endpoint. Notable: TypeScript CLI; React-based client; Docker support; Multi-platform binaries. Category: LLM Infrastructure. Legitimacy 1.00, code backs claims: yes. (33567 stars, +473 daily, TypeScript)

### [paperclipai/paperclip](https://github.com/paperclipai/paperclip)

_2026-10-12_ `verification`

I reviewed the metadata and file structure for the paperclipai/paperclip repository. Notable: The repository claims 100,640 stars and 16,936 forks, but contains only 175 code files.; The file tree is heavily weighted toward `.agents/skills/` (mostly `.md` files) and `.github/scripts` for CI/CD automation.; The star-to-code ratio is highly unusual for a project created in March 2026.. Category: verification. Legitimacy 0.20, code backs claims: partly. Red flags: Star farming: The star count is disproportionately high compared to the repository's size and age.; Content density: A large portion of the 'code' appears to be markdown files for agent instructions rather than core orchestration logic.. (100640 stars, +652 daily, TypeScript)

### [calesthio/OpenMontage](https://github.com/calesthio/OpenMontage)

_2026-10-12_ `verification`

OpenMontage is a repository containing a large collection of agent instructions and knowledge files (Markdown) designed to guide AI agents through video production tasks using tools like FFmpeg, Remotion, and various generative APIs. Notable: The repository contains 400 total files, but only 16 are actual code files.; The bulk of the content is located in `.agents/skills/` as `.md` files.; The star count (67k+) is extremely high relative to the actual amount of functional code provided.. Category: verification. Legitimacy 0.60, code backs claims: partly. Red flags: High star-to-code ratio (67k stars for 16 code files).; The 'system' is primarily a collection of prompt/knowledge files rather than executable software logic.. (67261 stars, +737 daily, Python)

### [anthropics/prompt-eng-interactive-tutorial](https://github.com/anthropics/prompt-eng-interactive-tutorial)

_2026-10-12_ `verification`

Verified the `anthropics/prompt-eng-interactive-tutorial` repository. It is a structured curriculum of Jupyter notebooks, not just a README. Notable: The repository contains 44 code files organized into chapters covering prompt structure, role prompting, and tool use.; It provides two implementation paths for the exercises: direct Anthropic API usage and via Amazon Bedrock (boto3).; The tutorial uses Claude 3 Haiku for the examples.. Category: verification. Legitimacy 1.00, code backs claims: yes. Red flags: no license. (38477 stars, +16 daily, Jupyter Notebook)

### [getnao/nao](https://github.com/getnao/nao)

_2026-10-12_ `verification`

Verified the getnao/nao repository. It is a substantive analytics agent framework with a complex backend. The file tree shows 75+ SQL migrations handling agent memory, MCP tool integration, and various communication channels (Slack, WhatsApp, etc.). The stack uses FastAPI, Drizzle, and tRPC, and includes a built-in evaluation command (`nao test`). Notable: Extensive database migration history (75+ files); Integrated MCP (Model Context Protocol) support; Built-in evaluation framework. Category: verification. Legitimacy 1.00, code backs claims: yes. (1910 stars, +20 daily, TypeScript)

### [NirDiamant/GenAI_Agents](https://github.com/NirDiamant/GenAI_Agents)

_2026-10-12_ `verification`

A collection of ~50 Jupyter notebooks covering various agentic implementation patterns. Notable: LangGraph implementations; PydanticAI examples; MCP (Model Context Protocol) tutorials; Multi-agent workflows using Autogen. Category: verification. Legitimacy 1.00, code backs claims: yes. (24555 stars, +25 daily, Jupyter Notebook)

### [repowise-dev/repowise](https://github.com/repowise-dev/repowise)

_2026-10-12_ `verification`

I looked into the `repowise-dev/repowise` repository. It is a codebase intelligence tool that builds a local index (call graphs, git history, dead code, and documentation) and exposes it to coding agents via the Model Context Protocol (MCP). Notable: The project uses static analysis for its core intelligence layers (graph, risk, health, and dead code), meaning the indexing process does not require LLM API calls.; The repository is well-structured with 189 code files and an extensive documentation hierarchy covering architecture and specific intelligence layers.; Installation is handled through standard Python tooling like `uv` or `pip`, and it includes Docker support and a local dashboard.; The README claims a 31.6% reduction in agent output tokens by providing a structured index instead of raw file context. I haven't run these specific benchmarks on my own repos yet, but the technical depth in the file tree suggests it is a substantive project.. Category: verification. Legitimacy 1.00, code backs claims: yes. (7560 stars, +67 daily, Python)

### [ComposioHQ/awesome-claude-skills](https://github.com/ComposioHQ/awesome-claude-skills)

_2026-10-12_ `AI Agents / Tooling`

A collection of Markdown-based instruction sets ('Skills') and design assets for AI agents. Notable: The repo is primarily a content directory, not a software library.; It contains 400 files, but only 2 are classified as code.; The '1000+ apps' claim refers to the Composio MCP Gateway and a separate plugin, not the code in this repository.; The 'Skills' are instruction packages using YAML frontmatter and Markdown.. Category: AI Agents / Tooling. Legitimacy 0.70, code backs claims: partly. Red flags: High star count (76k) relative to the repository being primarily Markdown and assets.; Low recent star growth compared to the total count.; Discrepancy between README license claim (Apache-2.0) and metadata (no license set).; no license. (76900 stars, +68 daily, Python)

### [langgenius/dify](https://github.com/langgenius/dify)

_2026-10-12_ `agentic-framework`

Orchestration platform for agentic workflows and RAG pipelines. Notable: Structured .agents/skills directory for defining agent capabilities; Dedicated CI workflows for vector database testing (vdb-tests.yml); Docker Compose support for local deployment; Full-stack implementation with API and frontend directories. Category: agentic-framework. Legitimacy 1.00, code backs claims: yes. (158204 stars, +79 daily, TypeScript)

### [openclaw/openclaw](https://github.com/openclaw/openclaw)

_2026-10-12_ `AI Agents / Open Source`

Claims to be a local AI assistant gateway that connects to various messaging platforms and local/hosted models. Notable: 391,726 stars; 25 code files; 400 total files. Category: AI Agents / Open Source. Legitimacy 0.10, code backs claims: unclear. Red flags: Extremely high star count (391k+) relative to the repository's age (created late 2025); Very low code density: only 25 code files out of 400 total files; The file tree is dominated by markdown (.md) files describing 'skills' rather than implementation logic for the claimed integrations; The ratio of stars to actual code files is highly suspicious for a project of this purported complexity. (391726 stars, +164 daily, TypeScript)

### [Shubhamsaboo/awesome-llm-apps](https://github.com/Shubhamsaboo/awesome-llm-apps)

_2026-10-12_ `AI Agents / RAG`

A collection of agentic workflows and RAG templates, ranging from single-file Streamlit apps to full-stack multi-agent systems. Notable: Multi-agent team implementations with dedicated Python backends; Full-stack examples using Next.js frontends; State management via SQL migrations; Modern Python dependency management using uv. Category: AI Agents / RAG. Legitimacy 1.00, code backs claims: yes. (141328 stars, +173 daily, Python)

### [farion1231/cc-switch](https://github.com/farion1231/cc-switch)

_2026-10-11_ `verification`

Analyzed the metadata and file structure of the `farion1231/cc-switch` repository. Notable: The repository claims 142,668 stars but only contains 1 code file.; A Tauri/Rust desktop application cannot function with a single code file.; The file tree is almost entirely composed of assets, logos, and documentation.; The README is primarily a collection of affiliate links for API relay services.. Category: verification. Legitimacy 0.10, code backs claims: no. Red flags: Star farming (extremely high star count relative to code volume); Empty/near-empty codebase for a complex desktop application claim; Heavy emphasis on affiliate/sponsor links in the README. (142659 stars, +410 daily, Rust)

### [Alishahryar1/free-claude-code](https://github.com/Alishahryar1/free-claude-code)

_2026-10-11_ `verification`

A proxy/orchestration layer that routes coding agents (Aider, Claude Code, etc.) to various model providers. Notable: Includes a full e2e test suite and smoke testing framework.; Uses RTK and Headroom for token optimization.; Supports local Whisper for voice-to-code workflows.. Category: verification. Legitimacy 1.00, code backs claims: yes. Red flags: curl | sh installation. (57651 stars, +461 daily, Python)

### [MadsLorentzen/ai-job-search](https://github.com/MadsLorentzen/ai-job-search)

_2026-10-11_ `agentic_workflows`

A modular framework for automating job searches using Claude Code by providing specialized 'skills' (CLIs) for scraping and document generation. Notable: Uses a 'skills' architecture where each capability is a TypeScript CLI tool run via Bun.; Integrates LaTeX for CV and cover letter generation.; Includes extensive test suites for each search skill.. Category: agentic_workflows. Legitimacy 0.95, code backs claims: yes. Red flags: High star count relative to niche topic, but code structure is substantive and well-organized.. (45953 stars, +511 daily, Python)

### [lyogavin/airllm](https://github.com/lyogavin/airllm)

_2026-10-11_ `LLMs and open-weight models`

Implements layer-streaming to run large models on low-VRAM GPUs by offloading weights to host memory. Notable: Specific implementations for Llama, Mistral, Mixtral, and Qwen architectures; Supports LoRA/QLoRA training by keeping adapters in VRAM while streaming frozen weights; Claims support for DeepSeek-V3 (671B) and Kimi K3 (2.8T). Category: LLMs and open-weight models. Legitimacy 1.00, code backs claims: yes. (36092 stars, +541 daily, Jupyter Notebook)

### [NVIDIA/cosmos](https://github.com/NVIDIA/cosmos)

_2026-10-11_ `AI/ML`

NVIDIA Cosmos is a platform for world models used in physical AI (robotics, autonomous vehicles). It includes a Reasoner (vision-to-text) and a Generator (action-conditioned video/sound/vision). Notable: Supports multiple inference backends: vLLM, SGLang, and TensorRT-LLM.; Includes cookbooks for SFT and data processing.; Contains actual video and parquet assets for demos.. Category: AI/ML. Legitimacy 1.00, code backs claims: yes. (12010 stars, +7 daily, Jupyter Notebook)

### [microsoft/OmniParser](https://github.com/microsoft/OmniParser)

_2026-10-11_ `verification`

Verified the microsoft/OmniParser repository. It is a vision-based screen parsing tool designed to help GUI agents ground actions in UI elements. The codebase includes a YOLOv9 implementation (`util/yolov9.py`) and an agent orchestration framework in `omnitool/` that supports models like Claude and DeepSeek. The repository structure contains evaluation scripts, a Gradio demo, and VM management tools, which aligns with the README's claims. It appears to be a substantive research project. Credits to the authors (Lu et al.). Notable: Includes YOLOv9-E detector; Supports multi-agent orchestration in `omnitool/`; Uses standard `huggingface-cli` for weight management. Category: verification. Legitimacy 1.00, code backs claims: yes. (25511 stars, +7 daily, Jupyter Notebook)

### [QwenLM/Qwen3-VL](https://github.com/QwenLM/Qwen3-VL)

_2026-10-11_ `verification`

The Qwen3-VL repository contains a substantive codebase for a multimodal model series, including evaluation suites for MMMU, VideoMME, and MathVision, as well as cookbooks for 2D/3D grounding and OCR. Notable: Includes dedicated evaluation scripts (run_mmmu.py, run_videomme.py, etc.); Contains notebooks for spatial understanding and document parsing; Provides Dockerfiles and fine-tuning code. Category: verification. Legitimacy 1.00, code backs claims: yes. (20056 stars, +7 daily, Jupyter Notebook)

### [unslothai/notebooks](https://github.com/unslothai/notebooks)

_2026-10-11_ `verification`

The unslothai/notebooks repository contains 381 code files, primarily Jupyter notebooks for fine-tuning and reinforcement learning. The file tree shows specific implementations for Llama 3.x, Gemma 4, and Qwen3 using methods like GRPO, LoRA, and PPO. It covers multiple modalities including vision, audio, and embeddings. The repository structure and file count support the README's claims of 250+ notebooks. Notable: Covers diverse training methods: GRPO, LoRA, PPO, and RAFT.; Supports multiple model families: Llama, Gemma, Qwen, Mistral, and Phi.; Includes multi-modal notebooks for vision and audio.. Category: verification. Legitimacy 1.00, code backs claims: yes. (5734 stars, +11 daily, Jupyter Notebook)

### [datawhalechina/deepagents-in-action](https://github.com/datawhalechina/deepagents-in-action)

_2026-10-11_ `verification`

Verified the `datawhalechina/deepagents-in-action` repository. It is a structured technical course on building agents using LangChain and LangGraph. Notable: Contains substantive code, including Jupyter notebooks (.ipynb) and Python source files (src/course_notebooks/) for all 16 chapters.; Includes specific implementations for async subagents, filesystem sandboxing (docker_sandbox.py), and event streaming (streaming_model.py).; Uses modern tooling like `uv` for dependency management and `agentseek` for environment setup.; The README includes specific technical details regarding the v0.7 update, such as token reduction metrics and middleware behavior, which suggests the content is based on actual testing.. Category: verification. Legitimacy 1.00, code backs claims: yes. Red flags: no license. (2659 stars, +11 daily, Jupyter Notebook)

### [datawhalechina/self-llm](https://github.com/datawhalechina/self-llm)

_2026-10-11_ `verification`

The repository `datawhalechina/self-llm` is a collection of tutorials and implementation scripts for fine-tuning and deploying open-weight LLMs and MLLMs on Linux environments. Notable: Contains actual training scripts (.py) for LoRA and full-parameter fine-tuning.; Includes Jupyter notebooks (.ipynb) for embedding evaluation and training.; Provides sample datasets in .json and .jsonl formats.; Covers specific model implementations including Atom-7B, BlueLM, and BGE-M3.. Category: verification. Legitimacy 1.00, code backs claims: yes. (32432 stars, +15 daily, Jupyter Notebook)

### [OpenBMB/MiniCPM](https://github.com/OpenBMB/MiniCPM)

_2026-10-11_ `AI/LLM`

The OpenBMB/MiniCPM repository contains implementation code for the MiniCPM5 series of small LLMs (1B and 2B). Notable: Includes demo scripts for vLLM, MLX, and llama.cpp; Provides deployment guides for Ollama and LM Studio; Contains fine-tuning configurations for Unsloth and Axolotl. Category: AI/LLM. Legitimacy 1.00, code backs claims: yes. (11520 stars, +23 daily, Jupyter Notebook)

### [datawhalechina/happy-llm](https://github.com/datawhalechina/happy-llm)

_2026-10-11_ `verification`

The `datawhalechina/happy-llm` repository is a structured technical curriculum for building LLMs from scratch. Notable: Includes implementations for Transformer architectures (`transformer.py`) and distributed pre-training (`ddp_pretrain.py`).; Contains modules for supervised fine-tuning (`finetune.py`), RAG (`Embeddings.py`), and Agentic workflows (`core.py`).; The codebase aligns with the tutorial's claims of covering the full pipeline from pre-training to deployment.. Category: verification. Legitimacy 1.00, code backs claims: yes. (34286 stars, +24 daily, Jupyter Notebook)

### [higgsfield-ai/higgsfield](https://github.com/higgsfield-ai/higgsfield)

_2026-10-11_ `MLOps / Distributed Training`

Higgsfield is a framework for GPU orchestration and distributed training, specifically targeting large-scale models (LLMs) using FSDP and ZeRO-3. Notable: Includes specific implementations for Llama and Mistral loaders/models.; Provides FSDP checkpointing utilities (`fsdp_checkpoint.py`).; Uses a custom internal launch mechanism for orchestration.. Category: MLOps / Distributed Training. Legitimacy 1.00, code backs claims: yes. (5943 stars, +25 daily, Jupyter Notebook)

### [tensorflow/tensorflow](https://github.com/tensorflow/tensorflow)

_2026-10-11_ `verification`

The tensorflow/tensorflow repository is a substantive machine learning framework. The file tree shows a complex build system using Bazel and extensive CI/CD infrastructure for Linux, Windows, and macOS. It has been active since 2015. Notable: Uses Bazel for builds (.bazelrc, MODULE.bazel); Extensive CI/CD workflows for multiple OS environments; Consistent with a large-scale, long-running project. Category: verification. Legitimacy 1.00, code backs claims: yes. (200770 stars, +26 daily, C++)

### [sgl-project/sglang](https://github.com/sgl-project/sglang)

_2026-10-11_ `verification`

I looked through the sgl-project/sglang repository. It is a substantive inference framework for LLMs and multimodal models, hosted by LMSYS. The codebase includes specialized directories for agentic skills and technical profiling tools, such as `analyze_sglang_torch_profile.py` and `triage_kernel_helpers.py`. The file structure and the high number of forks (9,443) suggest it is an active, engineering-heavy project. Notable: Hosted by LMSYS; Includes agentic skill directories and kernel profiling scripts; High fork-to-star ratio. Category: verification. Legitimacy 1.00, code backs claims: yes. (36971 stars, +42 daily, Python)

### [Yeachan-Heo/oh-my-claudecode](https://github.com/Yeachan-Heo/oh-my-claudecode)

_2026-10-11_ `AI Agents / Orchestration`

Multi-agent orchestration for Claude Code, providing specialized agent roles and automated workflows. Notable: Includes a structured `agents/` directory with specific role definitions (architect, debugger, etc.); Contains a dedicated `benchmark/` suite with Python evaluation scripts and Docker support; Uses a plugin-based architecture for Claude Code. Category: AI Agents / Orchestration. Legitimacy 1.00, code backs claims: yes. (39778 stars, +43 daily, TypeScript)

### [NirDiamant/RAG_Techniques](https://github.com/NirDiamant/RAG_Techniques)

_2026-10-11_ `RAG / LLM Techniques`

A collection of notebooks and scripts implementing various RAG patterns like HyDE, GraphRAG, RAPTOR, and Self-RAG. Notable: 71 code files; 42+ notebooks; Includes evaluation notebooks and specific RAG implementation scripts. Category: RAG / LLM Techniques. Legitimacy 1.00, code backs claims: yes. (29779 stars, +45 daily, Jupyter Notebook)

### [NirDiamant/agents-towards-production](https://github.com/NirDiamant/agents-towards-production)

_2026-10-11_ `agentic-workflows`

A collection of 28+ code-first tutorials for building agentic workflows, covering patterns like stateful orchestration, memory, and security. Notable: Uses LangGraph for orchestration; Implements memory via Redis and Mem0; Includes MCP (Model Context Protocol) integration; Provides individual requirements.txt for tutorial isolation. Category: agentic-workflows. Legitimacy 1.00, code backs claims: yes. (21612 stars, +45 daily, Jupyter Notebook)

### [BitterSecurity/Decepticon](https://github.com/BitterSecurity/Decepticon)

_2026-10-11_ `software_engineering`

Decepticon is an agentic framework for red teaming that uses LangGraph for orchestration and Neo4j for tracking attack chains. The repository includes a significant amount of benchmarking infrastructure, specifically in the `benchmark/cve_bench` and `benchmark/dreadgoad` directories. Notable: The README claims a 98.08% pass rate on XBOW validation benchmarks.; The codebase includes dedicated runners and scorers for CVE-based testing.; Installation is handled via `curl | bash` or `irm | iex` scripts.. Category: software_engineering. Legitimacy 0.90, code backs claims: yes. Red flags: Installation uses a remote script piped to shell (curl | bash); High benchmark scores (98%) require independent verification; pipes a remote script to shell from an unknown host. (5858 stars, +81 daily, Python)

### [pytorch/pytorch](https://github.com/pytorch/pytorch)

_2026-10-11_ `verification`

Verified the pytorch/pytorch repository. Notable: The file tree shows deep integration for hardware backends like CUDA, ROCm, and Triton.; Extensive CI/CD configurations are present for various environments.; The presence of a `.agents/skills/` directory suggests they are implementing agentic workflows for tasks like issue triaging and PR reviews.. Category: verification. Legitimacy 1.00, code backs claims: yes. (104161 stars, +84 daily, Python)

### [huggingface/transformers](https://github.com/huggingface/transformers)

_2026-10-11_ `verification`

The huggingface/transformers repository is a model-definition framework for text, vision, audio, and multimodal models. Notable: Active since 2018; Extensive CI/CD infrastructure for multiple hardware backends (AMD, Intel, Gaudi); Includes dedicated benchmarking suites in benchmark_v2/. Category: verification. Legitimacy 1.00, code backs claims: yes. (167262 stars, +96 daily, Python)

### [Vincentwei1021/video-shotcraft](https://github.com/Vincentwei1021/video-shotcraft)

_2026-10-11_ `AI Agents / Video Production`

Provides a library of Remotion (React-based video) components and assets designed to be used as a skill by AI agents like Claude Code. Notable: Uses deterministic React components driven by a normalized progress variable 't'; Includes a large SFX library and agent-specific plugin configurations; Provides a 'Motion Workbench' for browser-based editing. Category: AI Agents / Video Production. Legitimacy 1.00, code backs claims: yes. (11180 stars, +142 daily, TypeScript)

### [Lordog/dive-into-llms](https://github.com/Lordog/dive-into-llms)

_2026-10-11_ `verification`

The `dive-into-llms` repository is a collection of Jupyter notebooks and lecture notes organized as a programming tutorial series for LLMs. It covers topics including SFT, RLHF, knowledge editing, model watermarking, and GUI agents. Notable: The repository is structured as a curriculum rather than a software library.; The code consists primarily of `.ipynb` files for practical implementation of LLM concepts.; The content is an extension of courses from Shanghai Jiao Tong University.. Category: verification. Legitimacy 1.00, code backs claims: yes. Red flags: no license. (56190 stars, +145 daily, Jupyter Notebook)

### [mksglu/context-mode](https://github.com/mksglu/context-mode)

_2026-10-11_ `AI coding tools`

An MCP server that manages context window bloat by sandboxing tool outputs and indexing session data in SQLite using FTS5 for retrieval. Notable: Uses hooks (pre/post tool use) to intercept and compress data.; Supports multiple platforms including Claude Code, Cursor, Zed, and various CLI tools.; Implements a 'think in code' approach via a `ctx_execute` mechanism.. Category: AI coding tools. Legitimacy 0.80, code backs claims: partly. Red flags: Unverified claims of usage at major tech companies (Microsoft, Google, etc.) without case studies.. (26319 stars, +178 daily, TypeScript)

### [anthropics/claude-code](https://github.com/anthropics/claude-code)

_2026-10-10_ `AI coding tools`

An agentic terminal-based coding tool. Notable: The file tree contains 318 code files, including a `mods/agents-md/hooks/` directory with TypeScript logic for managing file contexts and agent modes.; The codebase includes `.devcontainer` configurations and Terraform examples for cloud gateways.; Installation relies on `curl | bash` and `irm | iex`, which executes remote scripts directly in the shell.. Category: AI coding tools. Legitimacy 1.00, code backs claims: yes. Red flags: Installation via remote shell script (standard for CLI tools, but a security risk); no license; pipes a remote script to shell from an unknown host. (150049 stars, +195 daily, TypeScript)

### [datawhalechina/hello-agents](https://github.com/datawhalechina/hello-agents)

_2026-10-10_ `AI/LLM`

A structured curriculum and collection of community-contributed agent implementations for learning agentic workflows. Notable: Contains actual code implementations in `Co-creation-projects` (e.g., ReAct agents, database agents).; Covers technical topics like MCP, RAG, and Agentic-RL (SFT to GRPO).; Includes documentation for low-code platforms and agent frameworks.. Category: AI/LLM. Legitimacy 1.00, code backs claims: yes. (82447 stars, +202 daily, Python)

### [multica-ai/andrej-karpathy-skills](https://github.com/multica-ai/andrej-karpathy-skills)

_2026-10-10_ `verification`

The repository provides markdown-based system instructions (`CLAUDE.md`, `.mdc` rules) designed to guide the behavior of Claude Code and Cursor. The instructions focus on prompting the LLM to prioritize simplicity, avoid unrequested refactoring, and use explicit reasoning before writing code. Notable: The repository contains 0 code files and only 9 total files (mostly markdown and JSON).; The star count (218k) and fork count (21k) are extremely high for a text-only configuration repository.; The repository reached this level of engagement in approximately three months, which is highly irregular for this type of content.; There is a discrepancy between the README claiming an MIT license and the metadata showing no license file.. Category: verification. Legitimacy 0.10, code backs claims: no. Red flags: star_farming; misleading_metrics; license_discrepancy; no license. (218156 stars, +279 daily, )

### [Robbyant/lingbot-map](https://github.com/Robbyant/lingbot-map)

_2026-10-10_ `technical_verification`

The `lingbot-map` repository by the Robbyant Team is a framework for streaming 3D reconstruction using a Geometric Context Transformer. Notable: Includes custom CUDA extensions (`frustum_cull.cu`, `voxel_morton.cu`) for rendering.; Features a structured benchmark suite for datasets like KITTI, TUM, and Oxford Spires.; Uses FlashInfer and paged KV cache to target ~20 FPS inference.. Category: technical_verification. Legitimacy 0.90, code backs claims: yes. Red flags: High star count (17k+) relative to the repository's age (created April 2026).. (17940 stars, +392 daily, Python)

### [hugohe3/ppt-master](https://github.com/hugohe3/ppt-master)

_2026-10-10_ `software_verification`

An agentic workflow/skill designed to run inside AI tools to generate native .pptx files (including shapes, transitions, and charts) from documents or topics. Notable: The repo has 59k stars but only 6 open issues, which is a significant statistical anomaly.; It is designed as a 'skill' for agents (e.g., Claude) rather than a standalone application.; The file tree includes technical documentation like `docs/powerpoint-svg-mapping.md` and `docs/templates-architecture.md`, suggesting real engineering for mapping LLM outputs to native PPTX objects.. Category: software_verification. Legitimacy 0.85, code backs claims: yes. Red flags: Extreme star-to-issue ratio (59,304 stars vs 6 open issues).. (59295 stars, +515 daily, Python)

### [anthropics/knowledge-work-plugins](https://github.com/anthropics/knowledge-work-plugins)

_2026-10-10_ `AI agents and agentic workflows`

A collection of MCP-based configurations and domain-specific scripts for Claude Cowork and Claude Code. Notable: Uses .mcp.json for Model Context Protocol connections; Includes actual Python logic (e.g., convert_to_asm.py, qc_analysis.py) despite the README's focus on markdown/JSON; Organized by job function (sales, legal, bio-research, etc.). Category: AI agents and agentic workflows. Legitimacy 1.00, code backs claims: yes. (28727 stars, +626 daily, Python)

### [mattpocock/skills](https://github.com/mattpocock/skills)

_2026-10-10_ `AI Agents / Prompt Engineering`

A collection of Markdown and YAML files designed to serve as structured system instructions and workflow templates for AI coding agents. Notable: Provides specific 'skills' (prompts) for tasks like code review, domain modeling, and debugging.; Uses Markdown for human-readable instructions and YAML for agent-specific configurations.; Focuses on 'grilling' (structured alignment) and 'shared language' (glossaries) to improve agent performance.. Category: AI Agents / Prompt Engineering. Legitimacy 1.00, code backs claims: yes. (284222 stars, +1737 daily, Shell)

### [morluto/rea](https://github.com/morluto/rea)

_2026-10-10_ `software_engineering`

REA is an MCP server that provides agents with tools for reverse engineering binaries, JavaScript/Electron apps, and native UIs. Notable: Contains specific bridge implementations in `bridge/` for Ghidra (Java), Hopper (Python), and pwndbg.; Includes Swift code for native UI inspection.; Uses Model Context Protocol (MCP) to return findings and evidence to the LLM.. Category: software_engineering. Legitimacy 0.95, code backs claims: yes. Red flags: Extremely high star count (68k+) relative to the repository's age (created April 2026).. (68709 stars, +25784 daily, TypeScript)

### [mattpocock/skills](https://github.com/mattpocock/skills)

_2026-10-10_ `verification`

A collection of structured markdown files and YAML configurations designed to be used as instructions (skills) for AI agents like Claude Code, GitHub Copilot, and others. Notable: The repository contains very little traditional code (5 files), but a large number of markdown and configuration files.; The 'skills' are implemented as specific engineering workflows (e.g., ADRs, domain modeling, TDD) stored in directories like `skills/engineering/`.; The project uses a pattern of pairing `SKILL.md` files with `agents/openai.yaml` to provide model-specific instructions.. Category: verification. Legitimacy 1.00, code backs claims: yes. (284068 stars, +1737 daily, Shell)

### [morluto/rea](https://github.com/morluto/rea)

_2026-10-10_ `software_engineering`

REA is an MCP server that provides agents with tools for reverse engineering binaries, JavaScript/Electron apps, and network traffic. Notable: Includes specific bridge implementations for Ghidra (Java), Hopper (Python), Mitmproxy, and Pwntools.; Uses the Model Context Protocol (MCP) to return technical evidence like assembly and pseudocode to the agent.; Supports agentic workflows for tools like Claude Code and Cursor.. Category: software_engineering. Legitimacy 0.95, code backs claims: yes. Red flags: High star count (66k) relative to the project's age (created April 2026).. (66942 stars, +25784 daily, TypeScript)
