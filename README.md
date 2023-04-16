# chess-gpt

**Demo:** https://play-chess-gpt.vercel.app/

Chess GPT is a web app where you can play chess against an LLM. It is powered by [window.ai](https://windowai.io/), which allows you to bring your own LLM model (e.g. GPT-3.5).

Chess GPT plays rather poorly 🥲 (as of 2023). There is a "Force Make Move" button to retry in case it makes illegal moves. Maybe the performance can serve as a benchmark for AGI.

### How it works

The prompt provides the game history, board position, and legal moves, and tells the LLM to return the best move, confidence, move explanation, and board analysis.

