# Walt Disney

The Walt Disney Company is a leading diversified international family entertainment and media enterprise. The Disney Characters API provides a free, open-access database of 9,820+ characters across all Disney brands. Disney also maintains extensive open source projects through its engineering teams.

- **Website:** [https://www.disney.com/](https://www.disney.com/)
- **Developer Portal:** [https://developer.disney.com/](https://developer.disney.com/)
- **Characters API:** [https://disneyapi.dev/](https://disneyapi.dev/)
- **Open Source:** [https://disney.github.io/](https://disney.github.io/)

## APIs

### Disney Characters API

Free REST and GraphQL API providing access to 9,820+ Disney characters with associated films, TV shows, video games, and park attraction data.

- **Base URL:** `https://api.disneyapi.dev`
- **Authentication:** None required
- **Documentation:** [https://disneyapi.dev/docs/](https://disneyapi.dev/docs/)

## Artifacts

### OpenAPI Specifications

| Spec | Description |
|------|-------------|
| [walt-disney-disney-api-openapi.yml](openapi/walt-disney-disney-api-openapi.yml) | Disney Characters API — list and retrieve characters |

### Spectral Rules

| Ruleset | Description |
|---------|-------------|
| [walt-disney-rules.yml](rules/walt-disney-rules.yml) | Spectral ruleset for Disney API conventions |

### Naftiko Capabilities

#### Shared Per-API Definitions

| File | Description |
|------|-------------|
| [capabilities/shared/disney-characters.yaml](capabilities/shared/disney-characters.yaml) | Disney Characters API definition |

#### Workflow Capabilities

| Workflow | Description | Tools |
|----------|-------------|-------|
| [disney-content-discovery.yaml](capabilities/disney-content-discovery.yaml) | Character and content discovery | 2 tools |

### JSON Schemas

| Schema | Description |
|--------|-------------|
| [walt-disney-character-schema.json](json-schema/walt-disney-character-schema.json) | Disney character data schema |

### JSON Structures

| Structure | Description |
|-----------|-------------|
| [walt-disney-character-structure.json](json-structure/walt-disney-character-structure.json) | Character data structure documentation |

### JSON-LD Contexts

| Context | Description |
|---------|-------------|
| [walt-disney-context.jsonld](json-ld/walt-disney-context.jsonld) | JSON-LD context (schema.org aligned) |

### Examples

| Example | Description |
|---------|-------------|
| [walt-disney-listCharacters-example.json](examples/walt-disney-listCharacters-example.json) | List characters request/response example |

### Vocabulary

| File | Description |
|------|-------------|
| [walt-disney-vocabulary.yml](vocabulary/walt-disney-vocabulary.yml) | Disney content and character vocabulary |

## Open Source Projects

- [Quanta](https://github.com/disney/quanta) — Roaring bitmap-based HTAP database engine
- [MaterialX](https://github.com/materialx/MaterialX) — Open standard for material content interchange
- [USD (Universal Scene Description)](https://github.com/PixarAnimationStudios/USD) — 3D scene interchange
- [OpenSubdiv](https://github.com/PixarAnimationStudios/OpenSubdiv) — Subdivision surface evaluation
- [Automated Cloud Advisor](https://github.com/disneystreaming/automated-cloud-advisor) — AWS cost optimization
- [weaver-test](https://github.com/disneystreaming/weaver-test) — Scala test framework

## Maintainers

**Kin Lane** — [kin@apievangelist.com](mailto:kin@apievangelist.com)
