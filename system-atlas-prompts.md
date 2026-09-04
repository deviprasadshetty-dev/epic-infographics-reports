# System Atlas — Complete Prompts Catalog
Total Prompts: 20

---
### 1. Hermes Agent Runtime
- **ID**: `hermes-agent-runtime`
- **Category**: AI & Autonomous Agents
- **Description**: Autonomous multi-channel ReAct tool execution runtime. Integrates sandboxed terminal execution, headless CDP browser instances, isolated subagent spawning, and SQLite WAL memory persistence.

**Natural Language Trigger Prompt**:
```text
Build a comprehensive System Atlas for the Hermes Agent runtime, mapping the User Gateway (U), Auth Guard (ATH), Orchestrator Brain (B), Context Assembler (CTX), Tool Executor (T), CDP Browser Harness (C), AXTree Parser (AXT), Subagent Dispatcher (D), SQLite Session DB (M), FTS5 Index (FTS), and Cron Scheduler (S).
```

---
### 2. SIMD Distributed Vector RAG Engine
- **ID**: `distributed-vector-rag`
- **Category**: Database & Search
- **Description**: High-throughput hybrid lexical-vector retrieval engine combining SIMD AVX-512 HNSW graph search with Tantivy BM25 inverted indexes, Reciprocal Rank Fusion, and GPU cross-encoders.

**Natural Language Trigger Prompt**:
```text
Build a System Atlas for a SIMD-accelerated distributed RAG engine: Ingestion Gateway (API), Document Parser (PAR), Semantic Chunker (CHK), Dense Embedder (EMB), HNSW SIMD Index (HNSW), Scalar Quantizer (SQ8), BM25 Lexical Index (BM25), RRF Fusion (RRF), Cross-Encoder Re-Ranker (RR), Vector Lakehouse (LAK), and Query Cache (CCH).
```

---
### 3. Real-Time Fraud Detection Stream Pipeline
- **ID**: `kafka-realtime-analytics`
- **Category**: Fintech & Streams
- **Description**: Sub-10ms payment transaction stream processing pipeline with Flink stateful Complex Event Processing (CEP), Redis feature stores, and XGBoost ML scoring.

**Natural Language Trigger Prompt**:
```text
Create a System Atlas for a sub-10ms financial fraud streaming architecture: Payment Gateway (GW), Kafka Event Log (KAF), Apache Flink CEP Engine (FLK), Redis Online Feature Store (RDS), XGBoost ML Scoring (ML), and Webhook Bus (ALT).
```

---
### 4. Kubernetes Control Plane & Worker Mesh
- **ID**: `kubernetes-control-plane`
- **Category**: Cloud & Infrastructure
- **Description**: Distributed container orchestration control plane showing apiserver, etcd Raft consensus, controller reconciliation, scheduler bin-packing, and Kubelet node agents.

**Natural Language Trigger Prompt**:
```text
Map the Kubernetes core architecture: kube-apiserver (API), etcd Raft cluster (ETCD), kube-controller-manager (KCM), kube-scheduler (SCH), Kubelet node agent (KUB), Containerd CRI (CR), and kube-proxy eBPF mesh (PRX).
```

---
### 5. 16,384-GPU Slurm 3D Parallelism LLM Cluster
- **ID**: `llm-training-gpu-cluster`
- **Category**: AI & Autonomous Agents
- **Description**: Megatron-DeepSpeed 3D parallelism architecture (Tensor, Pipeline, ZeRO-3 Data Parallel) with InfiniBand RDMA rail-optimized network fabric and NVMe checkpoint arrays.

**Natural Language Trigger Prompt**:
```text
Create a System Atlas for a 16k GPU LLM training cluster: Slurm Job Controller (SLM), Lustre Checkpoint Storage (LUS), Tensor Parallel Ranks (TP1, TP2), Pipeline Parallel Stages (PP1, PP2), ZeRO-3 Shard (ZRO), InfiniBand Spine (IB), SHARP Engine (SHP), DCGM Telemetry (DCG), Evaluation Benchmark (VAL), and S3 Snapshot (CKP).
```

---
### 6. Ethereum Layer-2 Optimistic Rollup
- **ID**: `ethereum-l2-optimistic-rollup`
- **Category**: Fintech & Web3
- **Description**: High-throughput Ethereum L2 rollup execution environment showing Sequencer batching, canonical bridge contracts, EIP-4844 data blobs, and interactive fraud proof games.

**Natural Language Trigger Prompt**:
```text
Build a System Atlas for an Ethereum L2 Optimistic Rollup: User Mempool (TXP), Rollup Sequencer (SEQ), L2 Geth EVM (EVM), State Trie DB (STA), Batch Submitter (BTC), EIP-4844 Blob Pool (DA), L1 Bridge Contract (BRG), State Proposer (PRO), Dispute Game (DIS), Challenger Node (CHA), and L1 Consensus (L1C).
```

---
### 7. Autonomous Vehicle Perception & Path Planning
- **ID**: `autonomous-vehicle-perception`
- **Category**: Robotics & Autonomous
- **Description**: Real-time automotive sensor fusion stack converting 8x 4K cameras, 128-beam LiDAR, and 4D radar into bird's-eye-view (BEV) dynamic obstacle tracks and MPC trajectory control.

**Natural Language Trigger Prompt**:
```text
Create a System Atlas for a self-driving car autonomy stack: Multi-Camera ISP (CAM), LiDAR Point Cloud Processor (LID), 4D Radar (RAD), Voxelizer (VOX), BEV Fusion Transformer (BEV), 3D Occupancy Grid (OCC), Vector HD Map (LAN), 3D Obstacle Tracker (TRK), Motion Predictor (PRD), MPC Trajectory Planner (MPC), CAN-FD Safety Gate (CAN), and Drive-by-Wire Actuator (ACT).
```

---
### 8. Global Adaptive Bitrate Video Transcoding
- **ID**: `video-transcoding-pipeline`
- **Category**: Cloud & Infrastructure
- **Description**: Chunked distributed video encoding pipeline with AV1/H.265 GPU clusters, multi-resolution ABR ladder generation, HLS/DASH packaging, and edge CDN delivery.

**Natural Language Trigger Prompt**:
```text
Map the video streaming architecture: Ingest Origin (ING), S3 Master Storage (S3), Chunk Slicer (SLC), SQS Task Queue (QUE), GPU Encoders (ENC1, ENC2), Audio Transcoder (AUD), DRM Service (DRM), ABR Packager (PKG), Edge CDN (CDN), and Quality Beacon (BEA).
```

---
### 9. Distributed SAGA E-Commerce Checkout
- **ID**: `e-commerce-checkout-orchestrator`
- **Category**: Enterprise Systems
- **Description**: High-availability distributed checkout orchestrator executing SAGA-pattern compensation loops across inventory reservations, payment gateways, tax calculation, and order fulfillment.

**Natural Language Trigger Prompt**:
```text
Create a System Atlas for a distributed SAGA checkout engine: Checkout Frontend (FE), SAGA Orchestrator (SGA), Inventory Lock (INV), Dynamic Pricing (PRC), Tax Engine (TAX), Payment Gateway Proxy (PAY), Order Database (PG), Fraud Filter (FRD), SAGA Compensator (CMP), Fulfillment Queue (FUL), and Notification Bus (NOT).
```

---
### 10. Aether Headless CDP Agent Browser Engine
- **ID**: `cdp-browser-automation-engine`
- **Category**: Browser Automation
- **Description**: High-concurrency Chrome DevTools Protocol engine for AI agents with isolated sandboxes, semantic accessibility tree parsers, visual screen sampling, and captcha solving.

**Natural Language Trigger Prompt**:
```text
Build a System Atlas for the Aether CDP Browser Engine: MCP Tool Server (MCP), Profile Sandbox Pool (MGR), Headless Chromium (CHR), CDP WebSocket Driver (CDP), AXTree Parser (AXT), Bounding Box Mapper (BOX), Input Dispatcher (INP), Screenshot Sampler (SCR), Captcha Solver (SOL), Cookie Vault (HAR), and Zombie Cleaner (WTC).
```

---
### 11. WireGuard Zero-Trust Network Mesh
- **ID**: `zero-trust-network-mesh`
- **Category**: Cybersecurity & Networking
- **Description**: Peer-to-peer encrypted mesh VPN with DERP relay fallback, coordination control plane key exchange, and ephemeral identity-aware ACL enforcement.

**Natural Language Trigger Prompt**:
```text
Create a System Atlas for a WireGuard Zero-Trust Mesh: Client Node (CLI), OIDC Identity (IDP), Coordination Control Plane (CTL), ACL Policy Compiler (POL), STUN NAT Discovery (STU), WireGuard Engine A (WG1), WireGuard Engine B (WG2), DERP Relay Node (DRP), State DB (DB), Flow Audit Logger (LOG), and Private Key Store (KEY).
```

---
### 12. Scope MCP Codebase Language Server Indexer
- **ID**: `codebase-lsp-indexer`
- **Category**: Developer Tooling
- **Description**: High-precision code intelligence engine running tree-sitter AST parsers and headless LSP daemons to resolve symbols, definitions, and call graphs for AI coding agents.

**Natural Language Trigger Prompt**:
```text
Build a System Atlas for a codebase LSP indexer: MCP Router (MCP), Repo Watcher (WTC), Tree-Sitter AST Parser (AST), Rust/Go LSP (LSP1), Python/TS LSP (LSP2), Symbol Index (IDX), Call Graph DAG (GRF), Type Store (TYP), LRU Cache (CCH), Docstring Extractor (DOC), and Dead Code Cleaner (CLN).
```

---
### 13. Orbital Rocket Avionics & Flight Computer
- **ID**: `spacex-starship-avionics`
- **Category**: Aerospace & Embedded
- **Description**: Triple-modular redundant (TMR) flight computer system executing 1,000 Hz guidance loops, Raptor engine thrust-vector gimbals, and Starlink telemetry links.

**Natural Language Trigger Prompt**:
```text
Create a System Atlas for a heavy-lift rocket avionics stack: Sensor IMU (IMU), GPS Constellation (GPS), Pitot Air Data (PIT), Flight Computer Alpha (FC1), Flight Computer Beta (FC2), Flight Computer Gamma (FC3), FPGA Voter Matrix (VOT), TTEthernet Bus (TTE), Engine TVC Gimbals (TVC), Grid Fin Servos (FIN), RCS Thrusters (RCS), and Starlink Downlink (STA).
```

---
### 14. Local-First IoT Smart Home Gateway
- **ID**: `iot-smart-home-gateway`
- **Category**: IoT & Smart Home
- **Description**: Local-first home automation hub interfacing Zigbee, Z-Wave, Matter, and Thread radios with offline automation engines, local SQLite state databases, and voice assistants.

**Natural Language Trigger Prompt**:
```text
Build a System Atlas for a local-first IoT smart home hub: Radio Dongles (RAD), Mosquitto MQTT (MQTT), Zigbee2MQTT (Z2M), SQLite State DB (DB), YAML Automation Engine (AUT), Jinja2 Evaluator (JIN), Neural Voice (VOC), Lovelace Dashboard (UI), RTSP Camera Transcoder (CAM), Push Notifier (NOT), and Local NAS Backup (BCK).
```

---
### 15. Real-Time Collaborative CRDT Canvas
- **ID**: `collaborative-crdt-editor`
- **Category**: Real-Time Web Apps
- **Description**: Conflict-free replicated data type (CRDT) engine with Yjs/Automerge binary state vectors, WebSocket mesh synchronization, awareness presence, and compaction.

**Natural Language Trigger Prompt**:
```text
Create a System Atlas for a real-time collaborative CRDT editor: Canvas Client (CLN), Local Y.Doc IndexedDB (IDB), WebSocket Sync Gateway (WSG), CRDT Vector Merger (CRD), Redis Awareness Presence (PRS), PostgreSQL Storage (PG), Snapshot Compactor (CMP), SVG/PDF Export Engine (EXP), Asset Object Store (AST), Undo/Redo Stack (UND), and Auth Guard (AUT).
```

---
### 16. Ultra-Low Latency FPGA Trading Engine
- **ID**: `high-frequency-trading-engine`
- **Category**: Fintech & Web3
- **Description**: Sub-microsecond electronic trading platform combining 10GbE optical market data feeds, FPGA hardware order book matchers, and kernel-bypass DMA routers.

**Natural Language Trigger Prompt**:
```text
Build a System Atlas for a sub-microsecond FPGA trading engine: Optical Tap (OPT), FPGA Parser (FPG), PCIe DMA (DMA), L3 Order Book (OBK), Signal Model (SIG), Pre-Trade Risk Gate (RSK), Order Router (RTR), Exchange Gateway (EXG), PTP Audit Vault (AUD), Atomic Clock (CLK), and Risk Telemetry (TEL).
```

---
### 17. Multi-Agent Dialectic Debate & Truth Consensus
- **ID**: `multi-agent-debate-consensus`
- **Category**: AI & Autonomous Agents
- **Description**: Dialectic reasoning pipeline where Proponent, Red-Team Skeptic, and Grounded Citation Fact-Checkers cross-examine evidence to eliminate hallucinations.

**Natural Language Trigger Prompt**:
```text
Create a System Atlas for a multi-agent debate consensus architecture: Ingestion Orchestrator (ING), Proponent Agent (PRO), Skeptic Critic (CRI), Citation Verifier (CIT), Headless Scraper (SCR), Judge Arbiter (JDG), Consensus Memory (MEM), Fallacy Registry (FAL), Report Publisher (PUB), Quorum Voter (VOT), and Slack Notifier (NOT).
```

---
### 18. HIPAA Clinical Health Record RAG Pipeline
- **ID**: `clinical-health-rag-pipeline`
- **Category**: Healthcare & Bio
- **Description**: De-identified medical record processing pipeline extracting ICD-10/SNOMED entities, validating drug-drug interactions, and synthesizing physician-verified clinical summaries.

**Natural Language Trigger Prompt**:
```text
Create a System Atlas for a clinical health RAG architecture: EHR Ingestion (EHR), Safe Harbor Filter (DEI), Synthetic Surrogate Map (SUR), Medical NER (NER), SNOMED Classifier (SNO), Drug Graph (DDI), Med-Llama Summarizer (SUM), Doctor Portal (PHY), Audit Vault (VLT), Lab Normalizer (LAB), and Emergency Alert (NOT).
```

---
### 19. Serverless GPU Inference Router & Mesh
- **ID**: `serverless-gpu-inference-router`
- **Category**: Cloud & Infrastructure
- **Description**: Low-latency serverless AI inference router featuring warm container pool scaling, FlashBoot model weight caching, prefix-cache key-value routing, and SSE token streaming.

**Natural Language Trigger Prompt**:
```text
Create a System Atlas for a serverless GPU inference engine: Ingress Router (ING), Rate Limiter (RAT), Pod Scheduler (SCH), Prefix Cache (PXC), FlashBoot NVMe (WGT), GPU Node A (GPU1), GPU Node B (GPU2), SSE Streamer (SSE), KV-Cache Store (KV), Telemetry Exporter (MET), and K8s Autoscaler (AUT).
```

---
### 20. Petabyte-Scale Web Crawler & Search Indexer
- **ID**: `search-engine-crawler-indexer`
- **Category**: Database & Search
- **Description**: Distributed search engine infrastructure managing polite domain URL frontiers, headless rendering clusters, deduplication bloom filters, PageRank graph compute, and sharded inverted indexes.

**Natural Language Trigger Prompt**:
```text
Create a System Atlas for a search engine crawling and indexing architecture: URL Frontier (FRN), Politeness Filter (POL), Headless Fetcher Fleet (FET), DNS Resolver (DNS), SimHash Bloom Filter (BLM), HTML Parser (TKN), PageRank Graph Engine (PRG), Sharded Inverted Index (IDX), Vector Tier (VEC), Block-Max WAND (WND), Query Serving Tier (SRV), and WARC Archive (SNP).
```

---
