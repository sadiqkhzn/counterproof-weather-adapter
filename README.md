# Weather forecast verification adapter

A Telegraph evaluation adapter for the `WEATHER_FORECAST_VERIFY` intent family. It scores how well a miner's answer
reports the observed weather for the place and date it was asked about, and whether it checks a stated forecast against it correctly.

## Package

| | |
|---|---|
| File | `WEATHER_FORECAST_VERIFY.safetensors` (6,776,916 bytes, lora-v1) |
| keccak256 (registered hash) | `561288834ca52179518ca3ebbcf0fd0165d58e21ef647298779701302c0f26da` |
| sha256 | `b2a0fdb8d55376b32943ded08e9c18a9e90c4708304afedb9b701209f022cce7` |
| Class / intent prefix | `judgment` / `WEATHER_FORECAST_VERIFY` |
| Foundation | `modernbert-base-lora16-v1` (`0a49b325…f8e6`) |
| Tokenizer | `67bc76f8…c456` (the node's pinned ModernBERT `tokenizer.json`) |

## Verify it

Check the file against the registered hash, then load it with Telegraph's adapter kit (`telegraph-wasm-baseline`):

```
go run ./cmd/adapterexec --package WEATHER_FORECAST_VERIFY.safetensors --listen 127.0.0.1:8080
```

Evaluation details and known limits have been provided to the Telegraph Hackathon Season II judges.

Built for Telegraph Hackathon Season II by the Counterproof team.
