<div align="center">
# Krishna Kanth Pathi
### Full-Stack & AI Systems Engineer
[![LeetCode Knight](https://img.shields.io/badge/LeetCode-Knight-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/krishnakanthpathi/)
[![Codeforces](https://img.shields.io/badge/Codeforces-krishnakanthpathi-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white)](https://codeforces.com/profile/krishnakanthpathi)
[![PyPI](https://img.shields.io/badge/PyPI-lmem-3775A9?style=for-the-badge&logo=pypi&logoColor=white)](https://pypi.org/project/lmem/)
[![Email](https://img.shields.io/badge/Email-krishnakanthpathi%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:krishnakanthpathi@gmail.com)
<p align="center">
  <b>Building low-latency AI runtimes, operating system primitives, and zero-overhead developer tooling.</b><br>
  Focused on kernel abstractions, local vector engines, and high-performance distributed systems.
</p>
---
</div>
## ❖ Featured Architectures
### 1. [LightMem (`lmem`)](https://github.com/krishnakanthpathi/lightmem)
> **Ultra-fast pure-Rust local AI agent persistent memory engine & CLI.**
- **Core Engine**: Pure-Rust architecture with SQLite WAL + FTS5 BM25 hybrid search, fastembed ONNX vector embeddings, and Native Needle precision reranking.
- **Intelligence Layer**: Sub-10ms startup, local ONNX SQuAD-2.0 Extractive QA (`minilm-squad2`), nearest-neighbor duplicate resolution, and bidirectional SQLite graph indexing (`[[wikilinks]]`).
- **Distribution**: Published on PyPI (`pip install lmem`), Cargo, and multi-platform one-line shell installers.
### 2. [MacSystem-MCP](https://github.com/krishnakanthpathi/native-assistant-mcp)
> **Cross-platform workstation automation MCP server for AI agents.**
- Exposes 70+ native OS capabilities via the Model Context Protocol (MCP).
- Low-latency window management, process supervision, native AppleScript / SkyLight hooks, system audio control, and hardware event simulation.
### 3. [LocalShare 2.0](https://github.com/krishnakanthpathi/localshare)
> **High-throughput AES-256-GCM encrypted peer-to-peer file transfer engine.**
- Direct socket pipeline and chunked streaming with zero cloud intermediaries.
