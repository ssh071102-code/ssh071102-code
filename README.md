# Laurin Lin

Student developer in Melbourne. I build LLM applications and automation pipelines in Python and TypeScript, and I'm looking for an internship or graduate role in AI or software engineering.

- **Study:** VCE Year 12 at Glen Waverley Secondary College (exams finish 12 November 2026), then studying AI and IT from February 2027.
- **Availability:** weekends now; full-time from 13 November 2026 to 15 January 2027; up to 24 hours a week from late February 2027 (student visa).

## Projects

| Project | What it does | Built with | Evidence |
|---|---|---|---|
| [grounded-chat](https://github.com/ssh071102-code/grounded-chat) | Answers questions from a set of documents with inline citations, then checks each sentence of the answer against the retrieved passages and flags the ones they don't support. | Next.js, TypeScript, local embeddings, Postgres/pgvector, Anthropic API | recall@5 of 0.867 on the bundled eval set; 133 tests |
| [script2video](https://github.com/ssh071102-code/script2video) | Turns a markdown script into a narrated video with word-timed captions. | Python, edge-tts, ffmpeg | 100 tests; sample video in the README |
| [claude-screen-mcp](https://github.com/ssh071102-code/claude-screen-mcp) | MCP server that gives a model read-only access to the screen: screenshots, OCR and change detection. | TypeScript, MCP SDK | unit tests plus a Windows end-to-end suite; published on npm |
| [continuity-showrunner](https://github.com/ssh071102-code/continuity-showrunner) | Turns one premise into a short film and keeps characters and places consistent across shots. Built for the Qwen Cloud Global AI Hackathon, Track 2. | Python, Qwen image and video models, ffmpeg | 22-second film attached to the release |
| [gig-radar](https://github.com/ssh071102-code/gig-radar) | Collects postings from several sources, scores them against a profile with a cheap model and drafts replies for the best matches under a spending cap. | Python, Anthropic API, SQLite, Telegram | 69 tests; offline demo that needs no API keys |
| [prompt-forge](https://github.com/ssh071102-code/prompt-forge) | Improves a prompt by hill-climbing on labeled examples and reports its score on a held-out validation set. | Python, Anthropic API | 61 tests; type-checked with mypy strict |

Every repo has CI, and its README states what it doesn't do yet.

## Tools

Python (pytest, asyncio, Typer), TypeScript and Node, Next.js, SQL, ffmpeg, GitHub Actions. LLM and generative APIs from Anthropic and Qwen, and the Model Context Protocol.

## AI assistance

I use Claude Code as a pair programmer. Commits it co-authored carry a `Co-Authored-By` trailer.
