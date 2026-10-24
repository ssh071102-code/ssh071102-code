# Laurin Lin

School leaver in Melbourne. I make short-form video and build AI tools for content: script-to-video, short AI films with consistent characters, and assistants that cite their sources. I'm looking for an internship, part-time or junior role in content, social media or AI.

- **Study:** VCE Year 12 at Glen Waverley Secondary College (last exam 12 November 2026), then studying AI and IT from February 2027.
- **Availability:** I can start now on days without an exam and any day from 13 November, up to 48 hours a fortnight until the school year ends on 18 December; full-time over the summer; up to 48 hours a fortnight from late February 2027 (student visa).

## Projects

| Project | What it does | Built with | Evidence |
|---|---|---|---|
| [grounded-chat](https://github.com/ssh071102-code/grounded-chat) | Answers questions from a set of documents with inline citations, then checks each sentence of the answer against the retrieved passages and flags the ones they don't support. | Next.js, TypeScript, local embeddings, Postgres/pgvector, Anthropic API | recall@5 of 0.867 on the bundled eval set; 134 tests |
| [script2video](https://github.com/ssh071102-code/script2video) | Turns a markdown script into a narrated video with word-timed captions. | Python, edge-tts, ffmpeg | 101 tests; sample video in the README |
| [claude-screen-mcp](https://github.com/ssh071102-code/claude-screen-mcp) | MCP server that gives a model read-only access to the screen: screenshots, OCR and change detection. | TypeScript, MCP SDK | unit tests plus a Windows end-to-end suite |
| [continuity-showrunner](https://github.com/ssh071102-code/continuity-showrunner) | Turns one premise into a short film and keeps characters and places consistent across shots. Built for the Qwen Cloud Global AI Hackathon, Track 2. | Python, Qwen image and video models, ffmpeg | 22-second film attached to the release |
| [gig-radar](https://github.com/ssh071102-code/gig-radar) | Collects freelance job posts from several sources and ranks them against a profile with a low-cost model. | Python, Anthropic API, SQLite, Telegram | 69 tests; offline demo that needs no API keys |
| [prompt-forge](https://github.com/ssh071102-code/prompt-forge) | Improves a prompt by hill-climbing on labeled examples and reports its score on a held-out validation set. | Python, Anthropic API | 69 tests; type-checked with mypy strict |

## Tools

Python (pytest, asyncio, Typer), TypeScript and Node, Next.js, SQL, ffmpeg, GitHub Actions. LLM and generative APIs from Anthropic and Qwen, and the Model Context Protocol.
