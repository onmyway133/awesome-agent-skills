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

- **[anthropics/skills](https://github.com/anthropics/skills)** — Anthropic's own skill collection: document creation and editing, plus the `skill-creator` meta-skill for scaffolding new skills. Examples: `docx`, `pdf`, `pptx`, `xlsx`, `skill-creator`. _(Source: anthropics/skills, official)_

## Databases & Data

- **[ClickHouse](https://github.com/ClickHouse/agent-skills)** — Skills for querying ClickHouse and chDB, including SQL guidance and using chDB as an embedded analytical datastore. Examples: `clickhouse-best-practices`, `chdb-datastore`, `chdb-sql`. _(Source: ClickHouse/agent-skills, official)_
- **[DuckDB](https://github.com/duckdb/duckdb-skills)** — Skills for querying data, attaching external databases, and searching DuckDB's own docs from Claude Code. Examples: `attach-db`, `query`, `read-file`. _(Source: duckdb/duckdb-skills, official)_
- **[MongoDB](https://github.com/mongodb/agent-skills)** — Skills covering connection setup, schema design, query optimization, and Atlas Stream Processing. Examples: `mongodb-connection`, `mongodb-schema-design`, `mongodb-atlas-stream-processing`. _(Source: mongodb/agent-skills, official)_
- **[Neon](https://github.com/neondatabase/agent-skills)** — Skills for Neon's serverless Postgres, covering setup, branching, and egress cost optimization. Examples: `neon-postgres`, `neon-postgres-branches`, `neon-postgres-egress-optimizer`. _(Source: neondatabase/agent-skills, official)_
- **[Redis](https://github.com/redis/agent-skills)** — Core guidance for working with Redis as a data store. _(Source: redis/agent-skills, official)_
- **[Supabase](https://github.com/supabase/agent-skills)** — Postgres best practices specific to Supabase. _(Source: supabase/agent-skills, official)_
- **[Tinybird](https://github.com/tinybirdco/tinybird-agent-skills)** — Skills for Tinybird's real-time analytics platform, including CLI usage and Python SDK guidance. Examples: `tinybird-best-practices`, `tinybird-cli-guidelines`, `tinybird-python-sdk-guidelines`. _(Source: tinybirdco/tinybird-agent-skills, official)_

## Cloud & Infrastructure

- **[AWS](https://github.com/aws/agent-toolkit-for-aws)** — AWS's own skill library for building, deploying, and troubleshooting AWS workloads, spanning core service domains (CDK, serverless, IAM, networking, Bedrock) plus deeper specialized skills for EC2, migration, resilience, and other service-specific concerns. Examples: `aws-cdk`, `aws-serverless`, `amazon-bedrock`, `aws-iam`, `aws-observability`. _(Source: aws/agent-toolkit-for-aws, official)_
- **[Cloudflare](https://github.com/cloudflare/skills)** — Skills for building on Cloudflare's platform, including the Agents SDK and Workers-based email services. Examples: `agents-sdk`, `cloudflare-email-service`. _(Source: cloudflare/skills, official)_
- **[Firebase](https://github.com/firebase/agent-skills)** — Skills for Firebase setup, auth, Firestore, hosting, Crashlytics, and security-rules auditing. Examples: `firebase-basics`, `firebase-auth-basics`, `firebase-firestore`. _(Source: firebase/agent-skills, official)_
- **[Google Cloud](https://github.com/google/skills)** — Skills spanning BigQuery, Cloud Run, AlloyDB, GKE, and the Well-Architected Framework. Examples: `bigquery-basics`, `cloud-run-basics`, `alloydb-basics`. _(Source: google/skills, official)_
- **[HashiCorp](https://github.com/hashicorp/agent-skills)** — Skills for writing and maintaining Terraform providers and Azure Verified Modules. Examples: `azure-verified-modules`, `new-terraform-provider`, `provider-resources`. _(Source: hashicorp/agent-skills, official)_
- **[Microsoft](https://github.com/microsoft/skills)** — Skills for Azure SDK and AI Foundry development across multiple languages. Examples: `cloud-solution-architect`, `copilot-sdk`, `entra-agent-id`. _(Source: microsoft/skills, official)_
- **[Netlify](https://github.com/netlify/context-and-tools)** — Skills for Netlify Functions, Edge Functions, and Blobs storage. Examples: `netlify-functions`, `netlify-edge-functions`, `netlify-blobs`. _(Source: netlify/context-and-tools, official)_
- **[NVIDIA](https://github.com/NVIDIA/skills)** — Catalog of skills for AI, accelerated computing, robotics, and simulation platforms, updated frequently. _(Source: NVIDIA/skills, official)_
- **[Red Hat](https://catalog.redhat.com/en/ai/skills/detail/agentic-skill-pack-for-red-hat-customers)** — Skill packs for Red Hat subscribers covering CVE tracking, SRE workflows, and OpenShift/OpenShift Virtualization. Examples: `cve-skillpack`, `sre-skillpack`, `openshift-skillpack`. _(Source: Red Hat, official)_
- **[Vercel](https://github.com/vercel-labs/agent-skills)** — Skills for deploying to Vercel and building with Next.js/React, covering deployment workflows, cost/performance audits, and view-transition patterns. Examples: `deploy-to-vercel`, `vercel-optimize`, `react-best-practices`, `react-view-transitions`. _(Source: vercel-labs/agent-skills, official)_

## AI/ML Platforms & APIs

- **[Google Gemini](https://github.com/google-gemini/gemini-skills)** — Skills for building against the Gemini API, including the live/streaming and Omni Flash APIs. Examples: `gemini-api-dev`, `gemini-live-api-dev`, `gemini-omni-flash-api`. _(Source: google-gemini/gemini-skills, official)_
- **[Hugging Face](https://github.com/huggingface/skills)** — Skills for ML workflows, covering the Hub CLI, datasets, and model/space building. Examples: `hf-cli`, `huggingface-datasets`, `huggingface-spaces`. _(Source: huggingface/skills, official)_
- **[MiniMax](https://github.com/MiniMax-AI/skills)** — Skills spanning frontend, fullstack, and shader development plus document generation via the MiniMax API. Examples: `frontend-dev`, `fullstack-dev`, `shader-dev`. _(Source: MiniMax-AI/skills, official)_
- **[OpenAI](https://github.com/openai/skills)** — Curated skills covering deployment, documentation, and GitHub review workflows. Examples: `cloudflare-deploy`, `gh-address-comments`, `linear`. _(Source: openai/skills, official)_
- **[Replicate](https://github.com/replicate/skills)** — Discover, compare, run, and publish AI models through Replicate's API. Examples: `find-models`, `run-models`, `publish-models`. _(Source: replicate/skills, official)_
- **[Venice.ai](https://github.com/veniceai/skills)** — Skills for the Venice API, covering authentication, chat, and response handling. Examples: `venice-auth`, `venice-chat`, `venice-responses`. _(Source: veniceai/skills, official)_

## Frontend, Mobile & Design

- **[Angular](https://github.com/angular/skills)** — Skills for scaffolding new apps and general Angular development guidance. Examples: `angular-developer`, `angular-new-app`. _(Source: angular/skills, official)_
- **[Draw.io Skill](https://github.com/Agents365-ai/drawio-skill)** — A single skill for generating and maintaining editable draw.io diagrams from natural language or from code/IaC/schema sources (Terraform, Kubernetes, SQL, OpenAPI, Protobuf, GraphQL), with incremental sync against manual edits, multi-view exports, and CI-based architecture testing. _(Source: Agents365-ai/drawio-skill, 9.3k★)_
- **[Expo](https://github.com/expo/skills)** — Skills for building, deploying, and debugging Expo apps. Examples: `expo-native-ui`, `eas-workflows`, `expo-router`. _(Source: expo/skills, official)_
- **[Figma](https://github.com/figma/mcp-server-guide)** — Skills from Figma's MCP server guide for design-to-code workflows. Examples: `figma-code-connect`, `figma-design-to-code`, `figma-generate-design`. _(Source: figma/mcp-server-guide, official)_
- **[Flutter](https://github.com/flutter/agent-plugins)** — Skills covering layouts, testing, routing, and platform setup for Dart/Flutter apps. Examples: `flutter-apply-architecture-best-practices`, `flutter-build-responsive-layout`, `flutter-add-widget-test`. _(Source: flutter/agent-plugins, official)_
- **[Google Labs (Stitch)](https://github.com/google-labs-code/stitch-skills)** — Skills for the Stitch MCP server, compatible with Claude Code, Gemini CLI, and Cursor. Examples: `design-md`, `enhance-prompt`, `react-components`. _(Source: google-labs-code/stitch-skills, official)_
- **[GSAP](https://github.com/greensock/gsap-skills)** — Skills covering the GSAP core API, timelines, ScrollTrigger, and React integration. Examples: `gsap-core`, `gsap-timeline`, `gsap-scrolltrigger`. _(Source: greensock/gsap-skills, official)_
- **[Sanity](https://github.com/sanity-io/agent-toolkit)** — Skills for Sanity's content platform, covering best practices, content modeling, and SEO. Examples: `sanity-best-practices`, `content-modeling-best-practices`, `seo-aeo-best-practices`. _(Source: sanity-io/agent-toolkit, official)_
- **[UI UX Pro Max](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill)** — Design-system skills covering token architecture, branding, slide generation, and UI styling for cross-platform product design. Examples: `design-system`, `brand`, `slides`, `ui-styling`, `banner-design`. _(Source: nextlevelbuilder/ui-ux-pro-max-skill, 127k★)_

## Auth & Identity

- **[Auth0](https://github.com/auth0/agent-skills)** — A single consolidated skill for Auth0 integration across SDKs, frameworks, MFA, and migration workflows. _(Source: auth0/agent-skills, official)_
- **[Better Auth](https://github.com/better-auth/skills)** — Skills for the Better Auth library, covering best practices, auth setup, and organization/two-factor plugins. Examples: `best-practices`, `create-auth`, `organization`. _(Source: better-auth/skills, official)_

## Testing & Code Quality

- **[CodeRabbit](https://github.com/coderabbitai/skills)** — AI code review skills covering automated review and autofix workflows. Examples: `code-review`, `autofix`. _(Source: coderabbitai/skills, official)_
- **[Cypress](https://github.com/cypress-io/ai-toolkit)** — Skills for creating, maintaining, and fixing Cypress tests. Examples: `cypress-author`, `cypress-explain`, `cypress-docs`. _(Source: cypress-io/ai-toolkit, official)_
- **[TestMu AI (LambdaTest)](https://github.com/LambdaTest/agent-skills)** — Production-grade skills for major test automation frameworks across web, mobile, API, BDD, and unit testing. Examples: `appium-skill`, `api-skill`, `behave-skill`. _(Source: LambdaTest/agent-skills, official)_

## Security

- **[Trail of Bits](https://github.com/trailofbits/skills)** — Security skills for smart contract auditing, security context building, and vulnerability triage. Examples: `building-secure-contracts`, `audit-context-building`. _(Source: trailofbits/skills, official)_

## Observability

- **[Datadog Labs](https://github.com/datadog-labs/agent-skills)** — Observability skills for APM, docs lookup, and agent-based observability workflows. Examples: `dd-apm`, `dd-docs`, `agent-observability`. _(Source: datadog-labs/agent-skills, official)_
- **[Sentry](https://github.com/getsentry/sentry-for-ai)** — Skills for setting up Sentry SDKs and running Sentry-driven triage/fix workflows. Examples: `sentry-fix-issues`, `sentry-sdk-setup`, `sentry-setup-ai-monitoring`. _(Source: getsentry/sentry-for-ai, official)_

## Payments & Web3

- **[Binance](https://github.com/binance/binance-skills-hub)** — Web3 and trading skills for crypto market data, on-chain analytics, and token security auditing. Examples: `crypto-market-rank`, `query-token-audit`, `query-address-info`. _(Source: binance/binance-skills-hub, official)_
- **[Coinbase](https://github.com/coinbase/agentic-wallet-skills)** — A single skill for operating a crypto wallet via the `awal` CLI — sign-in, balance checks, USDC/ETH/SOL transfers, token swaps, and x402 paid-API workflows. _(Source: coinbase/agentic-wallet-skills, official)_
- **[Stripe](https://github.com/stripe/ai)** — Skills for using the Stripe API and SDKs correctly, plus safe version upgrades. Examples: `stripe-best-practices`, `upgrade-stripe`, `stripe-apps`. _(Source: stripe/ai, official)_

## Search & Web Data

- **[Brave](https://github.com/brave/brave-search-skills)** — Skills for Brave's Search APIs, covering web, image, video, and local point-of-interest data. Examples: `answers`, `images-search`, `web-search`. _(Source: brave/brave-search-skills, official)_
- **[Browserbase](https://github.com/browserbase/skills)** — Browser automation skills covering headless browsing, cookie sync, and autonomous browsing. Examples: `browser`, `cookie-sync`, `autobrowse`. _(Source: browserbase/skills, official)_
- **[Firecrawl](https://github.com/firecrawl/skills)** — Skills for scraping, crawling, mapping, and searching the web through Firecrawl's API. Examples: `firecrawl-scrape`, `firecrawl-crawl`, `firecrawl-search`. _(Source: firecrawl/skills, official)_
- **[SerpApi](https://github.com/serpapi/skills)** — Skills for SerpApi's search-engine results API, giving agents structured search data. Examples: `serpapi-web-search`, `agent-usability-test`. _(Source: serpapi/skills, official)_

## Productivity & Collaboration

- **[Apollo GraphQL](https://github.com/apollographql/skills)** — Skills for building GraphQL clients, servers, federated supergraphs, and the Apollo Router. Examples: `apollo-client`, `apollo-federation`, `apollo-connectors`. _(Source: apollographql/skills, official)_
- **[Courier](https://github.com/trycourier/courier-skills)** — Sending multi-channel notifications via email, SMS, push, and chat. _(Source: trycourier/courier-skills, official)_
- **[Google Workspace CLI](https://github.com/googleworkspace/cli)** — Skills for managing Google Workspace services — Drive, Sheets, Gmail — via the `gws` CLI. Examples: `gws-drive`, `gws-sheets`, `gws-gmail`. _(Source: googleworkspace/cli, official)_
- **[Notion](https://github.com/makenotion/claude-code-notion-plugin)** — Skills for capturing knowledge, preparing meetings, and turning specs into tracked tasks. Examples: `knowledge-capture`, `meeting-intelligence`, `spec-to-implementation`. _(Source: makenotion/claude-code-notion-plugin, official)_
- **[Resend](https://github.com/resend/resend-skills)** — Skills for sending and receiving email through Resend, including React Email templates. Examples: `resend`, `react-email`, `email-best-practices`. _(Source: resend/resend-skills, official)_
- **[Typefully](https://github.com/typefully/agent-skills)** — Creating, scheduling, and publishing social posts across X, LinkedIn, Threads, Bluesky, and Mastodon. _(Source: typefully/agent-skills, official)_
- **[WordPress](https://github.com/WordPress/agent-skills)** — Skills from the WordPress development team for block development, themes, and project triage. Examples: `wp-block-development`, `wp-block-themes`, `wp-project-triage`. _(Source: WordPress/agent-skills, official)_

## Agent Frameworks & Tooling

- **[Composio](https://github.com/ComposioHQ/skills)** — Connect AI agents to 1000+ external apps with managed authentication. _(Source: ComposioHQ/skills, official)_
- **[VoltAgent](https://github.com/VoltAgent/skills)** — Skills for building AI agents with the VoltAgent TypeScript framework. Examples: `create-voltagent`, `voltagent-best-practices`, `voltagent-core-reference`. _(Source: VoltAgent/skills, official)_

## Developer Workflow

- **[Addy Osmani](https://github.com/addyosmani/agent-skills)** — Production engineering practice skills spanning planning, code review, security hardening, performance, and observability. Examples: `code-review-and-quality`, `security-and-hardening`, `performance-optimization`, `spec-driven-development`, `observability-and-instrumentation`. _(Source: addyosmani/agent-skills, 94k★)_
- **[Karpathy Guidelines](https://github.com/forrestchang/andrej-karpathy-skills)** — A single skill distilling Andrej Karpathy's observations on LLM coding pitfalls into behavioral guardrails against overcomplication and unverified assumptions. _(Source: forrestchang/andrej-karpathy-skills, 212k★)_
- **[Kotlin](https://github.com/Kotlin/kotlin-agent-skills)** — JetBrains' skills for Kotlin codebases, covering Java-to-Kotlin conversion, JPA entity mapping, and Gradle/toolchain and dependency migrations. Examples: `kotlin-tooling-java-to-kotlin`, `kotlin-backend-jpa-entity-mapping`, `kotlin-tooling-native-build-performance`. _(Source: Kotlin/kotlin-agent-skills, official)_
- **[Matt Pocock](https://github.com/mattpocock/skills)** — General software-engineering workflow skills covering TDD, code review, debugging, git conflict resolution, and turning specs into tickets. Examples: `code-review`, `tdd`, `diagnosing-bugs`, `to-spec`, `resolving-merge-conflicts`. _(Source: mattpocock/skills, 261k★)_
- **[Superpowers](https://github.com/obra/superpowers)** — A full software development methodology covering brainstorming, planning, TDD, parallel-agent dispatch, git worktrees, and pre-completion verification. Examples: `test-driven-development`, `systematic-debugging`, `writing-plans`, `requesting-code-review`, `using-git-worktrees`. _(Source: obra/superpowers, 286k★)_

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for inclusion criteria and how to submit an entry.

## License

[MIT](LICENSE)
