# Weather forecast verification adapter, v3

| | |
|---|---|
| File | `WEATHER_FORECAST_VERIFY.safetensors` (13535612 bytes, lora-v1, rank 16, max 384 tokens) |
| keccak256 (registered hash) | `811f48828f7b11ceb371529eb0e3322dd056d476ea3f6ff2002dc1fd6249b76a` |
| sha256 | `0596d44a8700772a8462903d7f3f28fb378994cbfdd7a1e7ebdcb682f0a67ddd` |
| Class / intent prefix | `judgment` / `WEATHER_FORECAST_VERIFY` |
| Foundation | `modernbert-base-lora16-v1` (`0a49b325…f8e6`) |
| Tokenizer | `67bc76f8…c456` (the node's pinned ModernBERT `tokenizer.json`) |

Load it with Telegraph's adapter kit: `go run ./cmd/adapterexec --package WEATHER_FORECAST_VERIFY.safetensors --listen 127.0.0.1:8080`

Built for Telegraph Hackathon Season II by the Counterproof team.
