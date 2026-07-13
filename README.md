# Dmitriy Motorin

Senior iOS engineer building mobile and FinTech products since 2014.

I work across native Swift/SwiftUI/UIKit, real-time and offline systems, Rust shared cores through UniFFI/CoreFFI, on-device ML, OCR/document intelligence, and retrieval/agent automation. I care about correctness at system boundaries, measurable failure handling, and shipping the whole product rather than stopping at a demo.

Open to remote Senior/Lead iOS and hands-on mobile platform roles, especially in FinTech, trading, AI-enabled products, and risk-sensitive systems.

## Selected engineering work

| Project | What it demonstrates | Stack |
|---|---|---|
| [FinStreamKit](https://github.com/jimbokl/FinStreamKit) | Public-safe real-time finance patterns: actor-owned quote state, stale-event handling, integer money, deterministic order-risk policy, cancellation, snapshots, tests and CI | Swift 6, Swift Package Manager, XCTest |
| [EvidencePipelineKit](https://github.com/jimbokl/EvidencePipelineKit) | Local-first PDFKit/Vision OCR with confidence, provenance, contradiction gates and grounded context for downstream RAG | Swift 6, PDFKit, Vision, XCTest |
| [Cortex](https://github.com/jimbokl/LLMCORTEX) | Local-first pre-reasoning memory and automation for coding agents, with deterministic rules, TF-IDF fallback, audit logs, benchmarks and human-approved learning | Python, SQLite, RAG/agent workflows |
| [SOLBOT](https://github.com/jimbokl/SOLBOT) | Financial ML research pipeline with microstructure features, RF/BiGRU ensemble, ONNX inference and explicit trading-risk disclaimers | Python, scikit-learn, ONNX Runtime |
| [MetaCAD benchmarks](https://github.com/metacadio/benchmarks) | Reproducible engineering validation cases and deterministic technical calculations | Rust/WASM, numerical validation |
| [GoldGRU](https://github.com/jimbokl/GoldGRU) | Time-series research and honest model-validation constraints for XAU/USD | Python, PyTorch, BiGRU/attention |

## Private work I can discuss in an interview

- Native SwiftUI energy product backed by a 40-module Rust core, typed CoreFFI boundary, Core ML/ONNX delivery, and 223 core unit/integration tests.
- Swift PDFKit/Vision OCR pipeline with text-layer fast path, scan fallback, confidence/provenance output, deterministic extraction, caching, retries, human review, and downstream RAG guardrails.
- AVFoundation camera PPG pipeline with real-time DSP, quality gates, stabilization/hysteresis, SwiftData evidence, and physical-device validation.

Private code, credentials, customer data, and proprietary screenshots are intentionally excluded. I can walk through architecture, trade-offs, failure modes, and selected sanitized code in a controlled interview.

## Engineering themes

- Swift concurrency, actors, `AsyncStream`, cancellation, deterministic tests
- SwiftUI/UIKit interoperability, AVFoundation, Vision, PDFKit, SwiftData, Keychain
- Rust-to-Swift ownership, DTO boundaries, error mapping, XCFramework packaging
- Core ML/ONNX, OCR confidence, evidence provenance, RAG guardrails
- FinTech state correctness, stale data, integer money, idempotency, release safety

[LinkedIn](https://www.linkedin.com/in/dmotorin) · [MetaCAD](https://metacad.io) · [Email](mailto:mmotorin@gmail.com)
