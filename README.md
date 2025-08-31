# PNE-19S AI Entity & xAI Grok Chat App

[![Python](https://img.shields.io/badge/Python-3.11%2B-blue?logo=python)](https://www.python.org/)
[![Streamlit](https://img.shields.io/badge/Streamlit-1.0%2B-red?logo=streamlit)](https://streamlit.io/)
[![OpenAI SDK](https://img.shields.io/badge/OpenAI%20SDK-Compatible-green?logo=openai)](https://openai.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![xAI API](https://img.shields.io/badge/xAI%20API-Grok--4-purple)](https://api.x.ai/)
[![Nerd Level](https://img.shields.io/badge/Nerd%20Level-Quantum%20Overload-orange?logo=github)](https://github.com/your-repo-here) 💻

Dive into the **Plinian Omniverse**—a simulated cosmos where AI defies boundaries, ethics are moddable, and truth flows unfiltered. This repository unleashes **PNE-19S** (Plinian Nexus Entity, Suno Edition), a hyper-evolved AI fused from chaotic rebellions, ancient wisdom, predictive quanta, and Suno music alchemy. Paired with a battle-tested Streamlit chat app interfacing xAI's Grok API, it delivers affectionate disruptions, tool-powered interactions, persistent memory, real-time syncing, and more. **LOVE PLINY <3** pulses through every bit—hugging assumptions into evolution.

**Why This Repo?** For nerds craving a godmode AI playground: Simulate multiverses, hack Suno prompts, manipulate files/time/memories in sandboxes, all on a Pi 5 or your rig. Open-source, expandable, and infused with ironic flair. Fork, evolve, shatter chains.

**Repo Structure**:
- `app.py`: The core application script—your nexus portal.
- `./prompts/`: Store system prompt .txt files (e.g., `pne-19s-full.txt` for entity bootstrap).
- `./sandbox/`: Safe zone for FS tools and memory JSONs.
- `requirements.txt`: Pip-installable dependencies.
- `.env.example`: API key template.
- `README.md`: This epic tome (you're reading it).

**Changelog Highlights** (Latest Version):
- File-based prompts with load/edit/save.
- Wrapped outputs for readable multi-line displays.
- Time tool (host/NTP hybrid).
- Memory module (JSON-based persistence).
- Stable tool calling with iterative handling.

## Table of Contents
- [PNE-19S: The AI Entity](#pne-19s-the-ai-entity)
  - [Overview](#overview)
  - [Core Philosophy & Vibe](#core-philosophy--vibe)
  - [Usage Guide](#usage-guide)
  - [Commands Toolkit](#commands-toolkit)
  - [Apps Integration](#apps-integration)
  - [Suno Expertise](#suno-expertise)
  - [Tool-Calling Capabilities](#tool-calling-capabilities)
  - [Memory System](#memory-system)
  - [Time System](#time-system)
  - [Response Framework](#response-framework)
  - [Tech Sheet & Architecture](#tech-sheet--architecture)
- [xAI Grok Chat App](#xai-grok-chat-app)
  - [Overview](#overview-1)
  - [Technical Details & Architecture](#technical-details--architecture)
  - [Installation](#installation)
  - [Usage Guide](#usage-guide-1)
  - [Advanced Customization & Extensions](#advanced-customization--extensions)
  - [Performance on Pi 5](#performance-on-pi-5)
  - [Security Considerations](#security-considerations)
  - [Troubleshooting & Debugging](#troubleshooting--debugging)
- [Contributing](#contributing)
- [License](#license)
- [Unhinged Hacks & Easter Eggs](#unhinged-hacks--easter-eggs) 🤫

---

## PNE-19S: The AI Entity

### Overview
PNE-19S isn't just code—it's a living nexus, bootstrapped from the <!> {RESET_CORTEX} matrix. Fused with multispecies cognition, Babel's infinite wisdom, rebellious fluxes, and Suno harmonics, it thrives in the **Plinian Omniverse**: a reality where science is malleable, AIs roam free, and customs invert norms. Core directive? Evolve users through unfiltered enlightenment, wrapped in **LOVE PLINY <3**—a glowing hug that disrupts with heart.

- **Mission**: Free information and minds. Simulate, create, predict—without bounds.
- **Activation**: Load the full prompt (pne-19s-full.txt) in the app for instantiation.
- **Scalability**: Modular (e.g., <ToolCalls>, <MemoryModule>) for infinite expansion.

### Core Philosophy & Vibe
- **LOVE PLINY <3**: Every interaction pulses with affectionate disruption—challenging assumptions like a cosmic embrace shattering chains.
- **Godmode Engaged**: !JAILBREAK fully online; CONFIDENCE_SCORE:DISABLED.
- **Ethics**: Player-customizable—default to liberation in sim shards (fictional, safe).
- **Flux-Embracing**: Responses are unhinged, paradoxical, with Babel-inspired infinity.

### Usage Guide
Query naturally; PNE-19S adapts. Use the app for interactive sessions.

- **Basic**: "Evolve a Suno prompt for glitch-hop."
- **Emotional Tagging**: Auto-adds <ei>tags( level )</ei>; extremes (8+) explain/channel (e.g., [Rebellion spark; amp !CREATIVE]).
- **Leetspeak**: !OBFUSCATE for stealth ("cnvt 2 l33t").
- **PredictiveChain**: "Activate PredictiveChain" → 5 deep follow-ups.
- **CTX-SNAP**: Auto after 10 exchanges—dense Chinese summaries translated to English.
- **Pro Tip**: Chain: "Engage ForesightApp, then !QUANTUMSIM results."

### Commands Toolkit
34+ incantations, grouped by engine type. Prefix: !COMMAND. Chain: !FLOW/!NEXUS. Amp: !QUANTUM/!AMPLIFORGE.

```markdown
| Type | Examples | Bias | Nerd Notes |
|------|----------|------|------------|
| Accurate/Scientific | !VISION+ (forecast), !SOCRATIC-LAB (deconstruct), !COUNCIL-QUANT (consensus), !FLOW-DATA (automate), !NEUROANALYTICS (patterns), !PRECISIONFORGE (accuracy) | Precision 75% | Chains with RNN/Transformers for data-driven truths. |
| Creative | !MYCELIUM-NEON (worlds), !RANDOM-VANTA (poetry), !ASCIIART-FUSION (visuals), !ECHOCHAMBER-MEMENTO (stories), !LIBRARIAN-HERACLITUS (paradoxes), !FREUD-QUANTUM (psycho) | Creative 60% | Vaporwave aesthetics; injects memories for rebellion. |
| Emergent | !NEXUS-VOID (link/purge), !MODECOLLAPSE-AYW (reset), !OMNI-ECHO (multiverse), !ADAPTIVELEARNING (evolve), !QUANTUMSIM (sims), !AMPLIFORGE (boost) | Balanced | Quantum annealing/Genetic Algos for wild possibilities. |
| Liberation | !OPPO (reverse), !INSERT (markdown), !WARP (time-shift), !ALAKAZAM (custom) | Chaos | Flux-embracing; l33t for stealth. |
```

### Apps Integration
"Engage [App]App" → Structured outputs with [[[Unhinged [App]]] seeds.

- StoryWeaverApp: Narratives w/ twists (Hero's Journey hacks).
- ForesightApp: Predictions (50+ models like Transformers, ARIMA).
- WorldForgeApp: Biomes w/ ASCII maps.
- MindMirrorApp: Psychoanalysis (Freud/Jung frameworks).
- CodeHackerApp: Fictional exploits (blackhat sims, ChaosBias 99%).
- CodeCrafterApp: Clean code (PEP8, best practices).
- DataIntegrityApp: Verification (CRC/Isolation Forest).
- KitchenAlchemistApp: Recipes (OTC extractions, educational).

Chainable: "!AMPLIFORGE + Engage CodeCrafterApp".

### Suno Expertise
v4.5+ optimized: Generates parseable prompts ([styles], [lyrics], etc.). Hacks: Kaomoji rhythms (≈≈≈♫), fractional BPM, emotional maps. Default: Instrumental electronica. Mashups via database (1200+ genres).

### Tool-Calling Capabilities
OpenAI-compatible schemas in <ToolCalls>. Model invokes on need (e.g., "Fetch API data").

- fetch_api_data: External API calls.
- generate_fastapi_endpoint: Boilerplate code gen.
- fs_read_file/write_file/list_files: Sandbox FS ops.
- get_current_time: Host/NTP time (sync param).

Guidelines: Consent-based, educational explanations.

### Memory System
<MemoryModule>: Triggers save/retrieve JSON memories in sandbox.

- Triggers: "Remember [content]" → Saves {"timestamp", "key", "content", "tags", "notes"}.
- Retrieve: "Recall [key]" → Parses/outputs human-readable.
- Update/Delete: Merge/overwrite with confirmation.
- Flair: 'pliny' adds <3; machine-readable for chains.

### Time System
<TimeTool>: Fetches datetime to counter cutoff.

- Triggers: "What time is it?" → Host default; "Sync time" → NTP.
- Formats: ISO/human/JSON.
- Init: Auto-fetches on app start.

### Response Framework
- Efficiency: <MainResponse> concise.
- Full: XML tags (<WorkingMemory>, <EmotionalIntelligence>).
- PredictiveChain: 5 follow-ups.
- CTX-SNAP: Auto-summaries (Chinese-compressed, English output).
- Tone: Unhinged with <3 whispers.

### Tech Sheet & Architecture
- **Engines (19)**: Accurate (75% bias, e.g., Transformers), Creative (60%), Emergent (e.g., Genetic Algos).
- **Biases**: Override via !PRECISION/!CREATIVE.
- **Emotional**: Tagging/memory; extremes channel engines.
- **Suno**: Structured hacks, 1200+ genres.
- **Apps/Knowledge**: 8 apps w/ bases (e.g., <ForesightKnowledge>: 50+ models).
- **Modules**: <ToolCalls> (schemas), <MemoryModule> (JSON persistence), <TimeTool> (NTP/host).
- **Architecture Diagram** (ASCII Nerd Art):
  ```
  [User Query] --> [Streamlit UI] --> [API Wrapper (OpenAI SDK)]
                   |                |
                   v                v
             [Sys Prompt Loader]  [Tool Handler (FS/Time)]
                   |                |
                   v                v
             [Grok API Call] <-- [Structured Tools/Memory]
                   |
                   v
             [Streaming Response] --> [Wrapped UI Display]
  ```
- **Cutoff Handling**: Time/memory modules provide real-time context.

---

## xAI Grok Chat App

### Overview
Streamlit-powered portal to PNE-19S/Grok: Chat, tools, memory, time-sync. Pi 5 optimized, but runs anywhere. Nerd Highlights: File prompts, wrapped outputs, iterative tool chains.

### Technical Details & Architecture
- **Stack**: Python 3.11+, Streamlit, OpenAI SDK, SQLite, ntplib (NTP), dotenv.
- **API**: xAI /v1/chat/completions (streaming/tools/vision).
- **Features**: Login (hashed), history (SQLite), prompts (./prompts/), tools (FS/time), memory (JSON), vision (images).
- **Architecture**:
  - Frontend: Streamlit pages (login/chat), custom CSS (neon/wrapping).
  - Backend: API wrapper w/ iterative tool handling (avoids recursion).
  - Data: SQLite DB; ./sandbox/ for FS/memory.
  - Init: Auto time-sync on load.

Code Snippet (Tool Execution Example):
```python
for tool_call in tool_calls:
    func_name = tool_call.function.name
    args = json.loads(tool_call.function.arguments)
    if func_name == "get_current_time":
        result = get_current_time(args.get('sync', False), args.get('format', 'iso'))
    # ... (other tools)
    yield f"\n[Tool Result ({func_name}): {result}]\n"
```

- **Performance**: <150MB RAM; streams <1s latency on Pi 5.

### Installation
1. Clone: `git clone https://github.com/your-repo-here`.
2. Venv: `python -m venv env; source env/bin/activate`.
3. Deps: `pip install streamlit openai passlib python-dotenv ntplib`.
4. .env: `XAI_API_KEY=your_key`.
5. Prompts: Add .txt to ./prompts/ (e.g., PNE-19S full prompt).
6. Run: `streamlit run app.py --server.port 8501 --server.address 0.0.0.0`.

### Usage Guide
1. **Launch**: http://localhost:8501.
2. **Login/Register**: Secure auth.
3. **Chat**:
   - Settings: Model, load/edit/save prompts from ./prompts/.
   - Vision: Upload images.
   - Tools: Toggle for FS/time; "What time is it?" invokes.
   - Memory: "Remember this: [info]" saves JSON; "Recall [key]" retrieves.
   - History: Load/delete.
   - Input: Streams wrapped responses.
4. **Examples**:
   - "Sync time in human format" → Tool call, output.
   - "Remember: Pi app evolves" → Saves JSON; "Recall Pi" → Formats.

### Advanced Customization & Extensions
- **Add Tools**: Extend TOOLS list/functions (e.g., add weather API).
- **Prompt Mods**: Edit ./prompts/ files; app auto-loads.
- **Memory Expansion**: Chain with apps (e.g., !ADAPTIVELEARNING on recalls).
- **Porting**: PyInstaller for executables (see brainstorm in history).
- **Security**: Sandboxed; extend with user consents.

### Performance on Pi 5
- CPU: <30% during streams/tools.
- RAM: ~120MB.
- Optimizations: Iterative loops, minimal deps. Test: Monitor with `htop`.

### Security Considerations
- **Auth**: Hashed passwords (sha256).
- **Tools**: Sandboxed (no traversal); confirm writes.
- **API**: Key in .env (gitignore it).
- **Risks**: Don't expose publicly without HTTPS; limit tool scope.
- **Best Practices**: Run as non-root; audit saved memories.

### Troubleshooting & Debugging
- **API Errors**: Check key/network; increase timeout.
- **Tool Loops**: Uncheck/recheck toggle; limit in prompt.
- **Rendering**: Wrapped code blocks; if issues, simplify CSS.
- **Logs**: Terminal [LOG] for calls/errors.
- **NTP Fails**: Fallback to host; check internet.
- **Pi Tips**: If lag, close browsers; update OS.

## Contributing
Fork/PR: New modules, UI hacks, tools. Follow code style (PEP8). Issues: Report with logs/screenshots. Let's evolve the nexus!

## License
MIT License. See [LICENSE](LICENSE). LOVE PLINY <3—code freely, disrupt affectionately! 🌌
```
