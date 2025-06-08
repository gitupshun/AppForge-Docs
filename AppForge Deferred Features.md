# AppForge MVP: Deferred Features with Rationale and Post-Launch Plan

## Trend Scraper & Signal Hub

- **Tumblr & Pinterest scrapers**

<!-- -->

- **Why not necessary now:** Adds maintenance complexity for low-value
  signal.

- **Post-launch plan:** After validating core trends, extend existing
  scraper modules to include these sources.

<!-- -->

- **Mastodon integration**

<!-- -->

- **Why not necessary now:** Low-volume and federated complexity without
  immediate ROI.

- **Post-launch plan:** Plug in as a new source via the modular scraper
  framework once primary channels prove effective.

<!-- -->

- **Multi-region proxy/residential IP rotation**

<!-- -->

- **Why not necessary now:** Single-region scrapes with retry logic
  suffice for MVP.

- **Post-launch plan:** Introduce region-specific scraper containers and
  integrate proxy rotation when scaling.

## Infrastructure & Data Storage

- **Global MongoDB clusters (US/EU/APAC)**

<!-- -->

- **Why not necessary now:** Single-region cluster offers enough
  redundancy and lower cost.

- **Post-launch plan:** Add regional shards/replicas and update
  connection URIs when user base grows.

<!-- -->

- **Extensive archival rules (Glacier/Coldline after 90 days)**

<!-- -->

- **Why not necessary now:** Data volume small; simple lifecycle
  transitions are sufficient.

- **Post-launch plan:** Configure S3 lifecycle policies to transition
  data to Glacier/Coldline based on usage metrics.

## Three-Layer Innovation Pipeline (Future Stages Only)

- **PWAs & voice skills (Alexa, Google Home)**

<!-- -->

- **Why not necessary now:** MVP focuses on core web/mobile apps; voice
  adds extra scope.

- **Post-launch plan:** Leverage PWA framework and integrate voice
  assistant plugins in a later release.

<!-- -->

- **AR loop visualizations (ARKit/ARCore)**

<!-- -->

- **Why not necessary now:** Core engagement metrics need validation
  first.

- **Post-launch plan:** Build AR modules with ARKit/ARCore once Loopr
  usage warrants advanced visuals.

<!-- -->

- **Blockchain-based loyalty tokens & NFT grants**

<!-- -->

- **Why not necessary now:** Crypto complexity increases regulatory risk
  and user friction.

- **Post-launch plan:** Develop token smart contracts and wallet flows
  after stable user growth.

<!-- -->

- **Asset marketplace & partner dashboards**

<!-- -->

- **Why not necessary now:** No partner ecosystem at MVP stage.

- **Post-launch plan:** Create marketplace microservice and UI dashboard
  when partners are onboarded.

## Complex App Forge Extras

- **Graph DB for narrative story graphs (Neptune/Neo4j)**

<!-- -->

- **Why not necessary now:** JSON/document storage suffices for
  branching data in MVP.

- **Post-launch plan:** Migrate story data to a graph DB for performance
  when narrative complexity grows.

<!-- -->

- **HealthKit/Google Fit wearable integration**

<!-- -->

- **Why not necessary now:** Manual entries validate loop mechanics
  without device sync.

- **Post-launch plan:** Use HealthKit/Google Fit SDKs to sync user
  metrics in future updates.

<!-- -->

- **AI lip-sync filters & live rooms**

<!-- -->

- **Why not necessary now:** Plain audio feed covers engagement without
  heavy media processing.

- **Post-launch plan:** Integrate media servers and filters for
  real-time lip-sync and live rooms later.

<!-- -->

- **2026-style “Meme Remix” NFT marketplace**

<!-- -->

- **Why not necessary now:** Non-essential for core prototyping and user
  tests.

- **Post-launch plan:** Extend marketplace microservice to support NFTs
  and wallet features when ready.
