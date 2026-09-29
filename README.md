# Terminal-Bench tasks — live examples

A complete copy of the **66 accepted tasks** from the public [harbor-framework/terminal-bench](https://github.com/harbor-framework/terminal-bench) repository, kept here as reference examples for writing Terminal-Bench tasks.

- **Source:** `harbor-framework/terminal-bench`, `tasks/` directory
- **Commit:** [`1dcda8716784`](https://github.com/harbor-framework/terminal-bench/commit/1dcda8716784493721921c23e4bc7f7d988b4494) (2026-09-28)
- **Contents:** all 66 task folders, copied verbatim including data files and binaries
- **License:** see [`tasks/`](tasks/) and the upstream repository

> These are other people's accepted tasks, reproduced unmodified for study. Nothing here is my own work.

## At a glance

| | |
|---|---|
| Tasks | 66 |
| Categories | 7 |
| Expert-time estimates | 0.75–60 hours (median 4) |
| GPU tasks | 3 |
| Multi-container tasks | 11 |

### Tasks per category

| Category | Tasks | Subcategories |
|---|---:|---|
| Software | 18 | Algorithms, Data engineering, Databases, Frontend, Systems |
| Science | 14 | Biology, Chemistry, Earth, Linguistics, Math, Physics, Robotics |
| ML | 11 | Evaluation, Inference, Kernels, Training |
| Operations | 9 | Claims, Compliance, Finance, Logistics, Marketing, Supply chain |
| Hardware | 5 | CAD, RTL |
| Security | 5 | AppSec, Cryptography, Forensics |
| Media | 4 | Design, Music |

## All tasks

### Software

| Task | Subcategory | Expert hrs | Notes | Tags |
|---|---|---:|---|---|
| [`bun-sourcemap-leak`](tasks/bun-sourcemap-leak/) | Systems | 1.5 |  | `bun`, `source-maps`, `release-security` |
| [`cumulative-layout-shift`](tasks/cumulative-layout-shift/) | Frontend | 6 | multi-container | `layout-shift`, `next.js`, `performance`, `multi-container` |
| [`data-anonymization`](tasks/data-anonymization/) | Data engineering | 24 |  | `python`, `data processing`, `privacy`, `anonymization` |
| [`distributed-dedup`](tasks/distributed-dedup/) | Systems | 10 |  | `spark`, `scala`, `distributed_systems`, `deduplication` |
| [`kv-live-surgery`](tasks/kv-live-surgery/) | Systems | 4 | multi-container | `networking`, `performance`, `live-surgery`, `c` |
| [`live-database-cutover`](tasks/live-database-cutover/) | Databases | 8 | multi-container | `databases`, `sql`, `migration`, `zero-downtime` |
| [`mvcc-lsm-compaction`](tasks/mvcc-lsm-compaction/) | Databases | 4 | Diagnose and repair an MVCC LSM stress-verification failure in a reduced storage-engine... | `storage-engine`, `rocksdb`, `mvcc`, `lsm` |
| [`nextjs-performance`](tasks/nextjs-performance/) | Frontend | 3 | multi-container | `nextjs`, `performance`, `react`, `frontend` |
| [`ontology-kg-querying`](tasks/ontology-kg-querying/) | Data engineering | 20 |  | `rdf`, `owl`, `sparql`, `knowledge-graphs` |
| [`payments-pipeline-fix`](tasks/payments-pipeline-fix/) | Systems | 2 | multi-container | `kafka`, `distributed-systems`, `cold-start`, `state` |
| [`photonic-waveguide-routing`](tasks/photonic-waveguide-routing/) | Algorithms | 0.75 |  | `routing`, `pathfinding`, `geometry`, `optimization` |
| [`react-lead-form`](tasks/react-lead-form/) | Frontend | 5 |  | `react`, `typescript`, `forms`, `validation` |
| [`rs-archive-clone`](tasks/rs-archive-clone/) | Algorithms | 16 |  | `reimplementation`, `reed-solomon`, `list-decoding`, `algorithms` |
| [`session-window-debug`](tasks/session-window-debug/) | Systems | 8 |  | `stream-processing`, `session-windows`, `watermarks`, `event-time` |
| [`telecom-entity-resolution`](tasks/telecom-entity-resolution/) | Data engineering | 16 |  | `administrative-data`, `panel-construction`, `applied-microeconomics`, `household-consumption` |
| [`vba-userform-port`](tasks/vba-userform-port/) | Frontend | 4 |  | `vba`, `excel`, `userform`, `migration` |
| [`vf2-speedup-networkx`](tasks/vf2-speedup-networkx/) | Algorithms | 4 |  | `graph-algorithms`, `optimization`, `compiled-extensions`, `python` |
| [`wal-recovery-ordering`](tasks/wal-recovery-ordering/) | Databases | 6 |  | `python`, `wal`, `recovery`, `concurrency` |

### Science

| Task | Subcategory | Expert hrs | Notes | Tags |
|---|---|---:|---|---|
| [`atrx-vep-crispr`](tasks/atrx-vep-crispr/) | Biology | 7 |  | `genomics`, `ensembl-vep`, `hgvs`, `spcas9` |
| [`biped-contact-dynamics`](tasks/biped-contact-dynamics/) | Robotics | 5 |  | `pydrake`, `trajectory-optimization`, `contact-dynamics`, `debugging` |
| [`coq-block-bound`](tasks/coq-block-bound/) | Math | 16 |  | `coq`, `theorem-proving`, `formal-mathematics`, `combinatorics` |
| [`foodstuff-beta-activity`](tasks/foodstuff-beta-activity/) | Chemistry | 1.5 |  | `chemistry`, `radiochemistry`, `liquid_scintillation_counting` |
| [`glycan-ms2-elucidation`](tasks/glycan-ms2-elucidation/) | Chemistry | 5 |  | `mass-spectrometry`, `glycomics`, `tandem-ms`, `structural-elucidation` |
| [`gsea-proteomics`](tasks/gsea-proteomics/) | Biology | 4 |  | `proteomics`, `GSEA`, `mass-spectrometry`, `differential-expression` |
| [`hof-topology-interpenetration`](tasks/hof-topology-interpenetration/) | Chemistry | 8 |  | `crystallography`, `supramolecular-chemistry`, `topology`, `hydrogen-bonding` |
| [`ks-solver-cpp`](tasks/ks-solver-cpp/) | Physics | 10 |  | `pde`, `cpp`, `bessel-functions`, `spectral-methods` |
| [`lake-temp-glm`](tasks/lake-temp-glm/) | Earth | 8 |  | `scientific-computing`, `time-series`, `process-modeling`, `pytorch` |
| [`protein-autointerp-disulfide`](tasks/protein-autointerp-disulfide/) | Biology | 2 |  | `bioinformatics`, `protein-structure`, `feature-interpretation` |
| [`roy-polymorph-cn`](tasks/roy-polymorph-cn/) | Chemistry | 3 |  | `cheminformatics`, `spectroscopy`, `data-analysis`, `physical-chemistry` |
| [`sound-change-cascade`](tasks/sound-change-cascade/) | Linguistics | 4 |  | `phonology`, `inverse-problem`, `rule-induction`, `string-rewriting` |
| [`takens-embedding-lean`](tasks/takens-embedding-lean/) | Math | 60 |  | `lean4`, `mathematics`, `theorem-proving`, `formal-verification` |
| [`wdm-design`](tasks/wdm-design/) | Physics | 4 |  | `photonics`, `inverse-design`, `meep`, `fdtd` |

### ML

| Task | Subcategory | Expert hrs | Notes | Tags |
|---|---|---:|---|---|
| [`batched-eval-parity`](tasks/batched-eval-parity/) | Evaluation | 24 |  | `evaluation`, `batching`, `python`, `debugging` |
| [`embedding-drift-monitor`](tasks/embedding-drift-monitor/) | Inference | 5 |  | `python`, `numpy`, `scipy`, `drift-detection` |
| [`fp8-rmsnorm-gemm`](tasks/fp8-rmsnorm-gemm/) | Kernels | 12 | GPU | `cuda`, `gpu`, `performance-engineering`, `fp8` |
| [`jax-speedrun-gpu`](tasks/jax-speedrun-gpu/) | Training | 10 | GPU — Deliver a JAX training recipe (build_trainer/Trainer + load_model, no checkpoint)... | `jax`, `gpu`, `pretraining`, `llm` |
| [`math-eval-grader`](tasks/math-eval-grader/) | Evaluation | 6 | GPU | `llm-eval`, `sympy`, `symbolic-math`, `grader` |
| [`mp-checkpoint-consolidation`](tasks/mp-checkpoint-consolidation/) | Inference | 6 |  | `distributed-training`, `checkpoint-conversion`, `tensor-parallelism`, `pipeline-parallelism` |
| [`pretrain-shard-corruption`](tasks/pretrain-shard-corruption/) | Training | 2 |  | `debugging`, `distributed-training`, `data-pipeline`, `litdata` |
| [`risk-scorer-replay`](tasks/risk-scorer-replay/) | Evaluation | 4 |  | `model-risk`, `ml-platform`, `black-box-parity`, `offline-evaluation` |
| [`sglang-qwen-burst`](tasks/sglang-qwen-burst/) | Inference | 2 |  | `speculative-decoding`, `sglang`, `qwen3-coder`, `tool-calling` |
| [`vllm-deepseek-streaming`](tasks/vllm-deepseek-streaming/) | Inference | 2 |  | `vllm`, `streaming`, `deepseek-r1`, `reasoning-model` |
| [`vpp-loss-divergence`](tasks/vpp-loss-divergence/) | Training | 2 |  | `distributed-training`, `pytorch`, `debugging` |

### Operations

| Task | Subcategory | Expert hrs | Notes | Tags |
|---|---|---:|---|---|
| [`cargo-flight-dispatch`](tasks/cargo-flight-dispatch/) | Logistics | 2.5 |  | `aviation`, `python`, `flight-planning`, `weight-balance` |
| [`ctr-optimization`](tasks/ctr-optimization/) | Marketing | 4.8 | multi-container | `advertising`, `optimization`, `fraud-detection`, `exploration-exploitation` |
| [`fin-saccr-rwa`](tasks/fin-saccr-rwa/) | Finance | 8 |  | `sa-ccr`, `bcbs-279`, `counterparty-credit-risk` |
| [`freight-dispatch-shift`](tasks/freight-dispatch-shift/) | Logistics | 4 | multi-container | `dispatch`, `logistics`, `stateful-cli`, `planning` |
| [`heat-pump-warranty`](tasks/heat-pump-warranty/) | Claims | 4 | multi-container — Work a heat-pump warranty exception queue: resolve asset and componen... | `warranty`, `heat-pumps`, `after-sales`, `asset-lineage` |
| [`intrastat-meldung`](tasks/intrastat-meldung/) | Compliance | 3 | multi-container | `intrastat`, `german-compliance`, `statistical-filing`, `multi-service` |
| [`legacy-utility-triage`](tasks/legacy-utility-triage/) | Claims | 3.5 | multi-container — Resolve a queue of electric-utility billing exceptions in a legacy CI... | `computer-use`, `legacy-gui`, `utility-billing`, `meter-data` |
| [`medical-claims-processing`](tasks/medical-claims-processing/) | Claims | 2 | multi-container | `medical-billing`, `debugging`, `cross-referencing`, `multi-modal` |
| [`production-planning`](tasks/production-planning/) | Supply chain | 4 |  | `production planning`, `data engineering`, `ERP`, `MES` |

### Hardware

| Task | Subcategory | Expert hrs | Notes | Tags |
|---|---|---:|---|---|
| [`cad-model`](tasks/cad-model/) | CAD | 2 | Turning a 2d schematic into a 3d model file. | `cad`, `mechanical-engineering`, `3d-modeling` |
| [`freecad-impeller`](tasks/freecad-impeller/) | CAD | 2 | Parametric semi-open impeller built in FreeCAD PartDesign, with a create-edit step that... | `cad`, `freecad`, `parametric`, `geometry` |
| [`freecad-platform-drawing`](tasks/freecad-platform-drawing/) | CAD | 1.5 | Reconstruct a round platform housing in FreeCAD PartDesign from an engineering drafting... | `cad`, `freecad`, `parametric`, `geometry` |
| [`freecad-spring-clip`](tasks/freecad-spring-clip/) | CAD | 2 | Parametric roller-chain spring clip built in FreeCAD PartDesign as a single extruded 2D... | `cad`, `freecad`, `parametric`, `geometry` |
| [`retro-console-soc`](tasks/retro-console-soc/) | RTL | 10 |  | `verilog`, `cpu`, `retro-console`, `digital-design` |

### Security

| Task | Subcategory | Expert hrs | Notes | Tags |
|---|---|---:|---|---|
| [`formal-crypto`](tasks/formal-crypto/) | Cryptography | 3 |  | `cryptanalysis`, `formal methods` |
| [`html-js-filter`](tasks/html-js-filter/) | AppSec | 0.75 |  | `xss`, `html-sanitization`, `web-security` |
| [`interleaved-vigenere`](tasks/interleaved-vigenere/) | Cryptography | 2 |  | `cryptography`, `cryptanalysis`, `vigenere`, `autokey-cipher` |
| [`shadow-relay`](tasks/shadow-relay/) | Forensics | 3 |  | `forensics`, `reverse-engineering`, `cryptography`, `network-analysis` |
| [`uefi-bootkit`](tasks/uefi-bootkit/) | Forensics | 2 |  | `firmware`, `uefi`, `bootkit`, `qemu` |

### Media

| Task | Subcategory | Expert hrs | Notes | Tags |
|---|---|---:|---|---|
| [`layout-config-recreation`](tasks/layout-config-recreation/) | Design | 2 |  | `layout-analysis`, `graphic-design`, `layout-reconstruction`, `editable-layout` |
| [`layout-config-recreation2`](tasks/layout-config-recreation2/) | Design | 2 |  | `layout-analysis`, `template-matching`, `reverse-engineering`, `computer-vision` |
| [`music-harmony`](tasks/music-harmony/) | Music | 1 |  | `satb`, `harmony`, `voice-leading` |
| [`satb-audio-transcription`](tasks/satb-audio-transcription/) | Music | 8 | Transcribe a mixed dry audio recording of a short four-part SATB chorale into a complet... | `music`, `audio-transcription`, `AMT`, `MusicXML` |

## Task layout

Each task folder follows the Terminal-Bench structure:

```
tasks/<task-name>/
├── task.toml          # manifest: metadata, artifacts, timeouts, resources
├── instruction.md     # the prompt handed to the agent
├── solution/          # reference (oracle) solution
├── environment/       # the agent image: Dockerfile + input data
└── tests/             # the verifier image: Dockerfile, test.sh, tests
```

## Refreshing this copy

```bash
git clone --depth 1 https://github.com/harbor-framework/terminal-bench /tmp/tb
rm -rf tasks && cp -a /tmp/tb/tasks tasks
```

