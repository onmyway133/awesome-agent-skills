# Awesome Agent Skills

A curated list of Claude agent skills — from official Anthropic sources and first-party vendor teams. Each entry is one repository/publisher, not one skill — a repo that ships dozens of skills still gets a single row, with a few example skill names for a sense of scope. Every entry is checked against the publisher's actual `SKILL.md` files before it's added.

## Table of Contents

- [Anthropic (Official)](#anthropic-official)
- [Databases & Data](#databases--data)
- [Cloud & Infrastructure](#cloud--infrastructure)
- [AI/ML Platforms & APIs](#aiml-platforms--apis)
- [Frontend, Mobile & Design](#frontend-mobile--design)
- [Auth & Identity](#auth--identity)
- [Testing & Code Quality](#testing--code-quality)
- [Security](#security)
- [Observability](#observability)
- [Payments & Web3](#payments--web3)
- [Search & Web Data](#search--web-data)
- [Productivity & Collaboration](#productivity--collaboration)
- [Agent Frameworks & Tooling](#agent-frameworks--tooling)
- [Developer Workflow](#developer-workflow)

## Anthropic (Official)

- **[anthropics/skills](https://github.com/anthropics/skills)** ![GitHub stars](https://img.shields.io/github/stars/anthropics/skills?style=flat) — Anthropic's own skill collection: document creation and editing, plus the `skill-creator` meta-skill for scaffolding new skills. Examples: `docx`, `pdf`, `pptx`, `xlsx`, `skill-creator`.

## Databases & Data

- **[ClickHouse](https://github.com/ClickHouse/agent-skills)** ![GitHub stars](https://img.shields.io/github/stars/ClickHouse/agent-skills?style=flat) — Skills for querying ClickHouse and chDB, including SQL guidance and using chDB as an embedded analytical datastore. Examples: `clickhouse-best-practices`, `chdb-datastore`, `chdb-sql`.
- **[DuckDB](https://github.com/duckdb/duckdb-skills)** ![GitHub stars](https://img.shields.io/github/stars/duckdb/duckdb-skills?style=flat) — Skills for querying data, attaching external databases, and searching DuckDB's own docs from Claude Code. Examples: `attach-db`, `query`, `read-file`.
- **[MongoDB](https://github.com/mongodb/agent-skills)** ![GitHub stars](https://img.shields.io/github/stars/mongodb/agent-skills?style=flat) — Skills covering connection setup, schema design, query optimization, and Atlas Stream Processing. Examples: `mongodb-connection`, `mongodb-schema-design`, `mongodb-atlas-stream-processing`.
- **[Neon](https://github.com/neondatabase/agent-skills)** ![GitHub stars](https://img.shields.io/github/stars/neondatabase/agent-skills?style=flat) — Skills for Neon's serverless Postgres, covering setup, branching, and egress cost optimization. Examples: `neon-postgres`, `neon-postgres-branches`, `neon-postgres-egress-optimizer`.
- **[Redis](https://github.com/redis/agent-skills)** ![GitHub stars](https://img.shields.io/github/stars/redis/agent-skills?style=flat) — Core guidance for working with Redis as a data store.
- **[Supabase](https://github.com/supabase/agent-skills)** ![GitHub stars](https://img.shields.io/github/stars/supabase/agent-skills?style=flat) — Postgres best practices specific to Supabase.
- **[Tinybird](https://github.com/tinybirdco/tinybird-agent-skills)** ![GitHub stars](https://img.shields.io/github/stars/tinybirdco/tinybird-agent-skills?style=flat) — Skills for Tinybird's real-time analytics platform, including CLI usage and Python SDK guidance. Examples: `tinybird-best-practices`, `tinybird-cli-guidelines`, `tinybird-python-sdk-guidelines`.

## Cloud & Infrastructure

- **[AWS](https://github.com/aws/agent-toolkit-for-aws)** ![GitHub stars](https://img.shields.io/github/stars/aws/agent-toolkit-for-aws?style=flat) — AWS's own skill library for building, deploying, and troubleshooting AWS workloads, spanning core service domains (CDK, serverless, IAM, networking, Bedrock) plus deeper specialized skills for EC2, migration, resilience, and other service-specific concerns. Examples: `aws-cdk`, `aws-serverless`, `amazon-bedrock`, `aws-iam`, `aws-observability`.
- **[Cloudflare](https://github.com/cloudflare/skills)** ![GitHub stars](https://img.shields.io/github/stars/cloudflare/skills?style=flat) — Skills for building on Cloudflare's platform, including the Agents SDK and Workers-based email services. Examples: `agents-sdk`, `cloudflare-email-service`.
- **[Firebase](https://github.com/firebase/agent-skills)** ![GitHub stars](https://img.shields.io/github/stars/firebase/agent-skills?style=flat) — Skills for Firebase setup, auth, Firestore, hosting, Crashlytics, and security-rules auditing. Examples: `firebase-basics`, `firebase-auth-basics`, `firebase-firestore`.
- **[Google Cloud](https://github.com/google/skills)** ![GitHub stars](https://img.shields.io/github/stars/google/skills?style=flat) — Skills spanning BigQuery, Cloud Run, AlloyDB, GKE, and the Well-Architected Framework. Examples: `bigquery-basics`, `cloud-run-basics`, `alloydb-basics`.
- **[HashiCorp](https://github.com/hashicorp/agent-skills)** ![GitHub stars](https://img.shields.io/github/stars/hashicorp/agent-skills?style=flat) — Skills for writing and maintaining Terraform providers and Azure Verified Modules. Examples: `azure-verified-modules`, `new-terraform-provider`, `provider-resources`.
- **[Microsoft](https://github.com/microsoft/skills)** ![GitHub stars](https://img.shields.io/github/stars/microsoft/skills?style=flat) — Skills for Azure SDK and AI Foundry development across multiple languages. Examples: `cloud-solution-architect`, `copilot-sdk`, `entra-agent-id`.
- **[Netlify](https://github.com/netlify/context-and-tools)** ![GitHub stars](https://img.shields.io/github/stars/netlify/context-and-tools?style=flat) — Skills for Netlify Functions, Edge Functions, and Blobs storage. Examples: `netlify-functions`, `netlify-edge-functions`, `netlify-blobs`.
- **[NVIDIA](https://github.com/NVIDIA/skills)** ![GitHub stars](https://img.shields.io/github/stars/NVIDIA/skills?style=flat) — Catalog of skills for AI, accelerated computing, robotics, and simulation platforms, updated frequently.
- **[Red Hat](https://catalog.redhat.com/en/ai/skills/detail/agentic-skill-pack-for-red-hat-customers)** — Skill packs for Red Hat subscribers covering CVE tracking, SRE workflows, and OpenShift/OpenShift Virtualization. Examples: `cve-skillpack`, `sre-skillpack`, `openshift-skillpack`.
- **[Vercel](https://github.com/vercel-labs/agent-skills)** ![GitHub stars](https://img.shields.io/github/stars/vercel-labs/agent-skills?style=flat) — Skills for deploying to Vercel and building with Next.js/React, covering deployment workflows, cost/performance audits, and view-transition patterns. Examples: `deploy-to-vercel`, `vercel-optimize`, `react-best-practices`, `react-view-transitions`.

## AI/ML Platforms & APIs

- **[Google Gemini](https://github.com/google-gemini/gemini-skills)** ![GitHub stars](https://img.shields.io/github/stars/google-gemini/gemini-skills?style=flat) — Skills for building against the Gemini API, including the live/streaming and Omni Flash APIs. Examples: `gemini-api-dev`, `gemini-live-api-dev`, `gemini-omni-flash-api`.
- **[Hugging Face](https://github.com/huggingface/skills)** ![GitHub stars](https://img.shields.io/github/stars/huggingface/skills?style=flat) — Skills for ML workflows, covering the Hub CLI, datasets, and model/space building. Examples: `hf-cli`, `huggingface-datasets`, `huggingface-spaces`.
- **[MiniMax](https://github.com/MiniMax-AI/skills)** ![GitHub stars](https://img.shields.io/github/stars/MiniMax-AI/skills?style=flat) — Skills spanning frontend, fullstack, and shader development plus document generation via the MiniMax API. Examples: `frontend-dev`, `fullstack-dev`, `shader-dev`.
- **[OpenAI](https://github.com/openai/skills)** ![GitHub stars](https://img.shields.io/github/stars/openai/skills?style=flat) — Curated skills covering deployment, documentation, and GitHub review workflows. Examples: `cloudflare-deploy`, `gh-address-comments`, `linear`.
- **[Replicate](https://github.com/replicate/skills)** ![GitHub stars](https://img.shields.io/github/stars/replicate/skills?style=flat) — Discover, compare, run, and publish AI models through Replicate's API. Examples: `find-models`, `run-models`, `publish-models`.
- **[Venice.ai](https://github.com/veniceai/skills)** ![GitHub stars](https://img.shields.io/github/stars/veniceai/skills?style=flat) — Skills for the Venice API, covering authentication, chat, and response handling. Examples: `venice-auth`, `venice-chat`, `venice-responses`.

## Frontend, Mobile & Design

- **[Angular](https://github.com/angular/skills)** ![GitHub stars](https://img.shields.io/github/stars/angular/skills?style=flat) — Skills for scaffolding new apps and general Angular development guidance. Examples: `angular-developer`, `angular-new-app`.
- **[Draw.io Skill](https://github.com/Agents365-ai/drawio-skill)** ![GitHub stars](https://img.shields.io/github/stars/Agents365-ai/drawio-skill?style=flat) — A single skill for generating and maintaining editable draw.io diagrams from natural language or from code/IaC/schema sources (Terraform, Kubernetes, SQL, OpenAPI, Protobuf, GraphQL), with incremental sync against manual edits, multi-view exports, and CI-based architecture testing.
- **[Expo](https://github.com/expo/skills)** ![GitHub stars](https://img.shields.io/github/stars/expo/skills?style=flat) — Skills for building, deploying, and debugging Expo apps. Examples: `expo-native-ui`, `eas-workflows`, `expo-router`.
- **[Figma](https://github.com/figma/mcp-server-guide)** ![GitHub stars](https://img.shields.io/github/stars/figma/mcp-server-guide?style=flat) — Skills from Figma's MCP server guide for design-to-code workflows. Examples: `figma-code-connect`, `figma-design-to-code`, `figma-generate-design`.
- **[Flutter](https://github.com/flutter/agent-plugins)** ![GitHub stars](https://img.shields.io/github/stars/flutter/agent-plugins?style=flat) — Skills covering layouts, testing, routing, and platform setup for Dart/Flutter apps. Examples: `flutter-apply-architecture-best-practices`, `flutter-build-responsive-layout`, `flutter-add-widget-test`.
- **[Google Labs (Stitch)](https://github.com/google-labs-code/stitch-skills)** ![GitHub stars](https://img.shields.io/github/stars/google-labs-code/stitch-skills?style=flat) — Skills for the Stitch MCP server, compatible with Claude Code, Gemini CLI, and Cursor. Examples: `design-md`, `enhance-prompt`, `react-components`.
- **[GSAP](https://github.com/greensock/gsap-skills)** ![GitHub stars](https://img.shields.io/github/stars/greensock/gsap-skills?style=flat) — Skills covering the GSAP core API, timelines, ScrollTrigger, and React integration. Examples: `gsap-core`, `gsap-timeline`, `gsap-scrolltrigger`.
- **[Sanity](https://github.com/sanity-io/agent-toolkit)** ![GitHub stars](https://img.shields.io/github/stars/sanity-io/agent-toolkit?style=flat) — Skills for Sanity's content platform, covering best practices, content modeling, and SEO. Examples: `sanity-best-practices`, `content-modeling-best-practices`, `seo-aeo-best-practices`.
- **[Swift Agent Skills](https://github.com/twostraws/Swift-Agent-Skills)** ![GitHub stars](https://img.shields.io/github/stars/twostraws/Swift-Agent-Skills?style=flat) — A curated index maintained by Paul Hudson (Hacking with Swift) that links out to 50+ separate Swift/Apple-platform skill repos rather than bundling skills itself, spanning SwiftUI, SwiftData, Concurrency, Testing, App Intents, and Accessibility. Examples: `SwiftUI-Agent-Skill`, `SwiftData-Agent-Skill`, `Swift-Concurrency-Agent-Skill`.
- **[UI UX Pro Max](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill)** ![GitHub stars](https://img.shields.io/github/stars/nextlevelbuilder/ui-ux-pro-max-skill?style=flat) — Design-system skills covering token architecture, branding, slide generation, and UI styling for cross-platform product design. Examples: `design-system`, `brand`, `slides`, `ui-styling`, `banner-design`.

## Auth & Identity

- **[Auth0](https://github.com/auth0/agent-skills)** ![GitHub stars](https://img.shields.io/github/stars/auth0/agent-skills?style=flat) — A single consolidated skill for Auth0 integration across SDKs, frameworks, MFA, and migration workflows.
- **[Better Auth](https://github.com/better-auth/skills)** ![GitHub stars](https://img.shields.io/github/stars/better-auth/skills?style=flat) — Skills for the Better Auth library, covering best practices, auth setup, and organization/two-factor plugins. Examples: `best-practices`, `create-auth`, `organization`.

## Testing & Code Quality

- **[CodeRabbit](https://github.com/coderabbitai/skills)** ![GitHub stars](https://img.shields.io/github/stars/coderabbitai/skills?style=flat) — AI code review skills covering automated review and autofix workflows. Examples: `code-review`, `autofix`.
- **[Cypress](https://github.com/cypress-io/ai-toolkit)** ![GitHub stars](https://img.shields.io/github/stars/cypress-io/ai-toolkit?style=flat) — Skills for creating, maintaining, and fixing Cypress tests. Examples: `cypress-author`, `cypress-explain`, `cypress-docs`.
- **[TestMu AI (LambdaTest)](https://github.com/LambdaTest/agent-skills)** ![GitHub stars](https://img.shields.io/github/stars/LambdaTest/agent-skills?style=flat) — Production-grade skills for major test automation frameworks across web, mobile, API, BDD, and unit testing. Examples: `appium-skill`, `api-skill`, `behave-skill`.

## Security

- **[Trail of Bits](https://github.com/trailofbits/skills)** ![GitHub stars](https://img.shields.io/github/stars/trailofbits/skills?style=flat) — Security skills for smart contract auditing, security context building, and vulnerability triage. Examples: `building-secure-contracts`, `audit-context-building`.

## Observability

- **[Datadog Labs](https://github.com/datadog-labs/agent-skills)** ![GitHub stars](https://img.shields.io/github/stars/datadog-labs/agent-skills?style=flat) — Observability skills for APM, docs lookup, and agent-based observability workflows. Examples: `dd-apm`, `dd-docs`, `agent-observability`.
- **[Sentry](https://github.com/getsentry/sentry-for-ai)** ![GitHub stars](https://img.shields.io/github/stars/getsentry/sentry-for-ai?style=flat) — Skills for setting up Sentry SDKs and running Sentry-driven triage/fix workflows. Examples: `sentry-fix-issues`, `sentry-sdk-setup`, `sentry-setup-ai-monitoring`.

## Payments & Web3

- **[Binance](https://github.com/binance/binance-skills-hub)** ![GitHub stars](https://img.shields.io/github/stars/binance/binance-skills-hub?style=flat) — Web3 and trading skills for crypto market data, on-chain analytics, and token security auditing. Examples: `crypto-market-rank`, `query-token-audit`, `query-address-info`.
- **[Coinbase](https://github.com/coinbase/agentic-wallet-skills)** ![GitHub stars](https://img.shields.io/github/stars/coinbase/agentic-wallet-skills?style=flat) — A single skill for operating a crypto wallet via the `awal` CLI — sign-in, balance checks, USDC/ETH/SOL transfers, token swaps, and x402 paid-API workflows.
- **[RevenueCat](https://github.com/RevenueCat/ai-toolkit)** ![GitHub stars](https://img.shields.io/github/stars/RevenueCat/ai-toolkit?style=flat) — Skills for configuring RevenueCat projects, products, entitlements, and offerings, plus paywall, purchase-flow, and subscription-management integration across iOS, Android, Kotlin Multiplatform, Flutter, and React Native. Examples: `integrate-revenuecat`, `revenuecat-paywall`, `revenuecat-purchase-flow`, `create-revenuecat-project`.
- **[Stripe](https://github.com/stripe/ai)** ![GitHub stars](https://img.shields.io/github/stars/stripe/ai?style=flat) — Skills for using the Stripe API and SDKs correctly, plus safe version upgrades. Examples: `stripe-best-practices`, `upgrade-stripe`, `stripe-apps`.

## Search & Web Data

- **[Brave](https://github.com/brave/brave-search-skills)** ![GitHub stars](https://img.shields.io/github/stars/brave/brave-search-skills?style=flat) — Skills for Brave's Search APIs, covering web, image, video, and local point-of-interest data. Examples: `answers`, `images-search`, `web-search`.
- **[Browserbase](https://github.com/browserbase/skills)** ![GitHub stars](https://img.shields.io/github/stars/browserbase/skills?style=flat) — Browser automation skills covering headless browsing, cookie sync, and autonomous browsing. Examples: `browser`, `cookie-sync`, `autobrowse`.
- **[Firecrawl](https://github.com/firecrawl/skills)** ![GitHub stars](https://img.shields.io/github/stars/firecrawl/skills?style=flat) — Skills for scraping, crawling, mapping, and searching the web through Firecrawl's API. Examples: `firecrawl-scrape`, `firecrawl-crawl`, `firecrawl-search`.
- **[SerpApi](https://github.com/serpapi/skills)** ![GitHub stars](https://img.shields.io/github/stars/serpapi/skills?style=flat) — Skills for SerpApi's search-engine results API, giving agents structured search data. Examples: `serpapi-web-search`, `agent-usability-test`.

## Productivity & Collaboration

- **[Apollo GraphQL](https://github.com/apollographql/skills)** ![GitHub stars](https://img.shields.io/github/stars/apollographql/skills?style=flat) — Skills for building GraphQL clients, servers, federated supergraphs, and the Apollo Router. Examples: `apollo-client`, `apollo-federation`, `apollo-connectors`.
- **[Courier](https://github.com/trycourier/courier-skills)** ![GitHub stars](https://img.shields.io/github/stars/trycourier/courier-skills?style=flat) — Sending multi-channel notifications via email, SMS, push, and chat.
- **[Google Workspace CLI](https://github.com/googleworkspace/cli)** ![GitHub stars](https://img.shields.io/github/stars/googleworkspace/cli?style=flat) — Skills for managing Google Workspace services — Drive, Sheets, Gmail — via the `gws` CLI. Examples: `gws-drive`, `gws-sheets`, `gws-gmail`.
- **[Notion](https://github.com/makenotion/claude-code-notion-plugin)** ![GitHub stars](https://img.shields.io/github/stars/makenotion/claude-code-notion-plugin?style=flat) — Skills for capturing knowledge, preparing meetings, and turning specs into tracked tasks. Examples: `knowledge-capture`, `meeting-intelligence`, `spec-to-implementation`.
- **[Resend](https://github.com/resend/resend-skills)** ![GitHub stars](https://img.shields.io/github/stars/resend/resend-skills?style=flat) — Skills for sending and receiving email through Resend, including React Email templates. Examples: `resend`, `react-email`, `email-best-practices`.
- **[Typefully](https://github.com/typefully/agent-skills)** ![GitHub stars](https://img.shields.io/github/stars/typefully/agent-skills?style=flat) — Creating, scheduling, and publishing social posts across X, LinkedIn, Threads, Bluesky, and Mastodon.
- **[WordPress](https://github.com/WordPress/agent-skills)** ![GitHub stars](https://img.shields.io/github/stars/WordPress/agent-skills?style=flat) — Skills from the WordPress development team for block development, themes, and project triage. Examples: `wp-block-development`, `wp-block-themes`, `wp-project-triage`.

## Agent Frameworks & Tooling

- **[Composio](https://github.com/ComposioHQ/skills)** ![GitHub stars](https://img.shields.io/github/stars/ComposioHQ/skills?style=flat) — Connect AI agents to 1000+ external apps with managed authentication.
- **[VoltAgent](https://github.com/VoltAgent/skills)** ![GitHub stars](https://img.shields.io/github/stars/VoltAgent/skills?style=flat) — Skills for building AI agents with the VoltAgent TypeScript framework. Examples: `create-voltagent`, `voltagent-best-practices`, `voltagent-core-reference`.

## Developer Workflow

- **[Addy Osmani](https://github.com/addyosmani/agent-skills)** ![GitHub stars](https://img.shields.io/github/stars/addyosmani/agent-skills?style=flat) — Production engineering practice skills spanning planning, code review, security hardening, performance, and observability. Examples: `code-review-and-quality`, `security-and-hardening`, `performance-optimization`, `spec-driven-development`, `observability-and-instrumentation`.
- **[Karpathy Guidelines](https://github.com/forrestchang/andrej-karpathy-skills)** ![GitHub stars](https://img.shields.io/github/stars/forrestchang/andrej-karpathy-skills?style=flat) — A single skill distilling Andrej Karpathy's observations on LLM coding pitfalls into behavioral guardrails against overcomplication and unverified assumptions.
- **[Kotlin](https://github.com/Kotlin/kotlin-agent-skills)** ![GitHub stars](https://img.shields.io/github/stars/Kotlin/kotlin-agent-skills?style=flat) — JetBrains' skills for Kotlin codebases, covering Java-to-Kotlin conversion, JPA entity mapping, and Gradle/toolchain and dependency migrations. Examples: `kotlin-tooling-java-to-kotlin`, `kotlin-backend-jpa-entity-mapping`, `kotlin-tooling-native-build-performance`.
- **[Matt Pocock](https://github.com/mattpocock/skills)** ![GitHub stars](https://img.shields.io/github/stars/mattpocock/skills?style=flat) — General software-engineering workflow skills covering TDD, code review, debugging, git conflict resolution, and turning specs into tickets. Examples: `code-review`, `tdd`, `diagnosing-bugs`, `to-spec`, `resolving-merge-conflicts`.
- **[Superpowers](https://github.com/obra/superpowers)** ![GitHub stars](https://img.shields.io/github/stars/obra/superpowers?style=flat) — A full software development methodology covering brainstorming, planning, TDD, parallel-agent dispatch, git worktrees, and pre-completion verification. Examples: `test-driven-development`, `systematic-debugging`, `writing-plans`, `requesting-code-review`, `using-git-worktrees`.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for inclusion criteria and how to submit an entry.

## License

[MIT](LICENSE)
