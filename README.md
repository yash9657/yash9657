<h1 align="center">Hi, I'm Yash Bhalgat</h1>
<h3 align="center">AI & full-stack software engineer in Los Angeles</h3>
<p align="center">I build thoughtful interfaces and the systems behind them: creative tools, AI pipelines, and dependable backends.</p>

<p align="center">
  <a href="https://yashbhalgat.com"><img src="https://img.shields.io/badge/portfolio-yashbhalgat.com-0e75b6?style=flat" alt="Portfolio" /></a>
  <a href="https://yashbhalgat.com/assets/Yash_Bhalgat_Resume.pdf"><img src="https://img.shields.io/badge/résumé-PDF-555?style=flat" alt="Résumé" /></a>
  <a href="https://www.linkedin.com/in/yashnbhalgat/"><img src="https://img.shields.io/badge/LinkedIn-yashnbhalgat-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:yashbhalgat9657@gmail.com"><img src="https://img.shields.io/badge/email-yashbhalgat9657%40gmail.com-D14836?style=flat&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

## Now

**Founding Engineer, Stealth Startup** · Dec 2025 – present
AI-assisted film post-production: captioning, secure video delivery, and rendering.

- Multi-pass GPU captioning pipeline (vocal isolation, WhisperX, forced alignment, diarization, sound-event detection, LLM authoring with an automated judge) that cut feature-film captioning from a multi-day vendor cycle to one automated run.
- Deterministic caption QC engine with auto-fixers over 12 delivery formats (SCC, TTML/IMSC, iTT, EBU-TT-D, SRT, WebVTT), each file verified against a real decoder.
- Secure pre-release playback: authenticated streaming gateway, Widevine/FairPlay CMAF, per-viewer forensic watermarking, and a parallel keyframe-aligned transcode for adaptive streaming.
- End-credits render pipeline to broadcast-spec MP4, ProRes and DPX; led SOC 2 readiness to Type I.

## Before

**Founding Engineer, SmartPractice AI** · Jun – Dec 2025
Ambient clinical documentation, medical coding, and EHR integration.

- Encounter audio → streaming ASR with medical-lexicon biasing → speaker roles → LLM-structured notes where every assertion cites its transcript span.
- Note-format engine that compiles a clinician's own format into a typed extraction schema (SOAP, APSO, H&P, DAP/BIRP, PT/OT on one engine).
- Evidence-backed ICD-10-CM / CPT / HCPCS coding with E/M levels, NCCI bundling and HCC recapture, exported as a superbill.
- SMART on FHIR integration (EHR, standalone and backend-services launch, FHIRcast) plus an MV3 Chrome extension as a write layer where EHRs expose no write API.
- Engineering controls for HIPAA and SOC 2 Type I and Type II.

## Things I've built

| Project | What it is | Stack |
|---|---|---|
| [**Inkcast**](https://inkcast.video) | A topic or document becomes a narrated, hand-drawn vector lesson. A seven-stage compiler syncs drawings to measured speech and renders with Chromium and FFmpeg in stateless containers. | TypeScript, Next.js, Kokoro/ONNX, Whisper, Fireworks |
| [**Tallyweb**](https://tallyweb.world) | Keyboard-first accounting and ERP with double-entry constraints, hash-chained vouchers and FORCE RLS in Postgres. Go core on ARM64 Lambda behind CloudFront, Aurora Serverless v2. | Go, React, XState, Terraform, AWS |
| [**Finfloww**](https://finfloww.xyz) | Reconciliation, invoice-to-PO review and variance analysis with deterministic calculations, human approval gates, and sandboxed (QuickJS) investigations that cite source rows. | Next.js, TypeScript, Supabase |
| [**DentaBill AI**](https://usedentabill.xyz) | Dental claim follow-ups: imports, queued payer calls, live transcripts and structured next actions. Fastify API and SQS workers on Lambda with Aurora and PHI audit trails. | Next.js, Fastify, Prisma, Clerk, AWS |
| **Cursor for Resolve** | An agent inside the edit bay: video matting, promptable segmentation and an on-device vision-language model driving DaVinci Resolve. No footage leaves the machine. | Python, on-device VLMs |

More detail, demos and architecture write-ups on [yashbhalgat.com](https://yashbhalgat.com).

## Toolbox

**Languages:** TypeScript, Python, Go, SQL, C++
**Backend & data:** Node.js, Fastify, FastAPI, Django, PostgreSQL (RLS), Redis, MongoDB, Supabase, event-driven pipelines
**Frontend:** React, Next.js, XState, Redux, Tailwind CSS
**Cloud & DevOps:** AWS (Lambda, SQS, Aurora, CloudFront, EventBridge), GCP (Cloud Run, Vertex AI), Docker, Kubernetes, Terraform, GitHub Actions
**AI:** LLM orchestration (Claude, Gemini, OpenAI), agentic tool use, RAG, MCP, evaluation harnesses
**Healthcare:** HL7 FHIR R4, SMART on FHIR, ICD-10-CM / CPT, HIPAA, SOC 2

<p>
  <img src="https://skillicons.dev/icons?i=ts,python,go,postgres,react,nextjs,nodejs,tailwind,aws,gcp,docker,kubernetes,terraform,githubactions" alt="Tech stack" />
</p>

## Education

- **M.S. Computer Science**, University of California, Riverside · 2023 – 2025 · GPA 3.76/4 · Graduate Teaching Assistant
- **B.E. Computer Engineering**, Pune Institute of Computer Technology · 2019 – 2023 · GPA 9.2/10

## Research

- [Spatial-keyword queries](https://dl.acm.org/doi/10.1145/3557915.3560975), ACM SIGSPATIAL

<sub>Fun fact: I speak fluent German.</sub>
