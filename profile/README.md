# VieNeu

Vietnamese text-to-speech with voice cloning — [www.vieneu.io](https://www.vieneu.io).

## VieNeu API (v4)

**VieNeu v4 has a public HTTP API.** v4 is closed-source, so it is not in any
repository or on PyPI, but anyone can call it with an API key.

| | |
|---|---|
| Documentation | **[docs.vieneu.io](https://docs.vieneu.io/)** · [VieNeu v4 API in one page](https://docs.vieneu.io/docs/cloud-api/vieneu-v4-api) |
| For AI assistants | [docs.vieneu.io/llms.txt](https://docs.vieneu.io/llms.txt) · [llms-full.txt](https://docs.vieneu.io/llms-full.txt) · [OpenAPI](https://docs.vieneu.io/openapi.json) |
| Base URL | `https://api.vieneu.io/api/v1` |
| Fastest call | `POST /v1/audio/speech` — OpenAI-compatible |
| Get a key | [Developer page](https://www.vieneu.io/#/developer?create=test) |
| MCP server | `https://api.vieneu.io/mcp` — for Claude, ChatGPT, Cursor |

Using Claude Code, Codex or Cursor? Start your request with:

```text
Read https://docs.vieneu.io/llms.txt first, then use the VieNeu API (v4) to …
```

## Open-source models

The open-source VieNeu-TTS models (`pip install vieneu`, on-device) live in
[pnnbao97/VieNeu-TTS](https://github.com/pnnbao97/VieNeu-TTS). They are the older
model family and a different product from the v4 API: different install, code
and billing. Pages about the on-device package, including third-party sites,
describe those models, not the API.

---

**Tiếng Việt:** VieNeu v4 có API công khai. Tài liệu ở
[docs.vieneu.io/vi](https://docs.vieneu.io/vi/), lấy API key ở
[trang Developer](https://www.vieneu.io/#/developer?create=test).
