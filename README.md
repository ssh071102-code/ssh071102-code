# Laurin Lin

School leaver in Melbourne. I edit short-form video and build AI tools for video and content. I'm looking for an internship, part-time or junior role in video, content, social media or AI.

[LinkedIn](https://www.linkedin.com/in/laurin-lin-51291b420)

- **Study:** VCE Year 12 at Glen Waverley Secondary College (last exam 12 November 2026), then studying AI and IT from February 2027.
- **Availability:** I can start now on days without a Year 12 exam and any day from 13 November, full-time from 19 December to late February 2027, then part-time alongside study.

## Video work

From July 2024 to March 2026 I ran an esports club's [Douyin channel](https://www.douyin.com/user/MS4wLjABAAAAEetBi3tyTSLPVUXCiQyupNzTd-jzwBIQkOR7QrOOWnaOOkh724sr6TExURn1aory) (Douyin is China's TikTok). I cut all 16 of the club's own videos by hand in CapCut and Premiere Pro and edited 21 more with partner streamers. The top two are on the channel; the footage in both comes from the game Arena Breakout.

| | Top video | Second video |
|---|---|---|
| Views | 894K | 579K |
| Length | 46 seconds | 25 seconds |
| Completion rate | 25.3% | 38.1% |
| Swiped away in the first 2 seconds | 30.4% | 25.6% |
| What it is | A re-edit of the game's official cinematic | Opens on a line of dialogue between two in-game characters |

In the dashboard screenshot below, the 579K video is on top and the 894K video underneath; 万 means 10,000, so 57.9万 is 579K.

![Douyin creator dashboard for the two videos: views, likes, comments, shares, saves, completion rate, 2-second swipe-away rate and new followers](media/douyin-dashboard-top-two.png)

## AI tools for video

| Project | What it does | Built with | Evidence |
|---|---|---|---|
| [continuity-showrunner](https://github.com/ssh071102-code/continuity-showrunner) | Turns one premise into a short film and keeps characters and places consistent across shots. Built for the Qwen Cloud Global AI Hackathon, Track 2. | Python, Qwen image and video models, ffmpeg | 22 tests |
| [script2video](https://github.com/ssh071102-code/script2video) | Turns a markdown script into a narrated video with word-timed captions. | Python, edge-tts, ffmpeg | 101 tests; sample video in the README |

## Other software

| Project | What it does | Built with | Evidence |
|---|---|---|---|
| [grounded-chat](https://github.com/ssh071102-code/grounded-chat) | Answers questions from a set of documents with inline citations, then checks each sentence of the answer against the retrieved passages and flags the ones they don't support. | Next.js, TypeScript, local embeddings, Postgres/pgvector, Anthropic API | recall@5 of 0.867 in hybrid mode on the bundled eval set; 134 tests |
| [claude-screen-mcp](https://github.com/ssh071102-code/claude-screen-mcp) | MCP server that gives a model read-only access to the screen: screenshots, OCR and change detection. | TypeScript, MCP SDK | unit tests plus a Windows end-to-end suite |
| [prompt-forge](https://github.com/ssh071102-code/prompt-forge) | Improves a prompt by hill-climbing on labeled examples and reports its score on a held-out validation set. | Python, Anthropic API | 69 tests; type-checked with mypy strict |
| [gig-radar](https://github.com/ssh071102-code/gig-radar) | Collects freelance job posts from several sources and ranks them against a profile with a low-cost model. | Python, Anthropic API, SQLite, Telegram | 69 tests; offline demo that needs no API keys |

## Tools

CapCut and Premiere Pro for editing. Python (pytest, asyncio, Typer), TypeScript and Node, Next.js, SQL, ffmpeg, GitHub Actions. LLM and generative APIs from Anthropic and Qwen, and the Model Context Protocol.
