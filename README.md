# Sketchfab (sketchfab)
Sketchfab is the largest dedicated platform for publishing, sharing, discovering, buying, and embedding interactive 3D content on the web. Founded in Paris in 2012 by Cedric Pinson and Alban Denoyel and acquired by Epic Games on July 21, 2021, Sketchfab hosts millions of 3D models from artists, museums, scanning rigs, and studios — much of it Creative Commons licensed. The platform exposes a public REST Data API for programmatic upload and content management, a JavaScript Viewer API for controlling the embedded WebGL/WebXR viewer, a Download API delivering glTF/GLB/USDZ, an oEmbed endpoint, and OAuth 2.0 authentication, alongside native exporters for every major 3D / DCC tool. Following the Fab.com launch in 2024 the Sketchfab Store has been retired into Epic's unified content marketplace while the publishing, viewing, and developer APIs remain on sketchfab.com.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/sketchfab/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

 - 3D, Models, Marketplace, Viewer, WebGL, glTF, AR, VR, Creative, Epic Games

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### Sketchfab Data API
REST API for reading and writing Sketchfab data — upload, list, retrieve, update, and delete models; manage collections, comments, likes, bookmarks, and search; administer organizations and projects. Public reads do not require authentication; writes require OAuth 2.0 or a personal API token.

**Human URL:** [https://sketchfab.com/developers/data-api](https://sketchfab.com/developers/data-api)

**Base URL:** `https://api.sketchfab.com`

- [Documentation](https://sketchfab.com/developers/data-api)
- [Documentation — v3 Swagger Reference](https://docs.sketchfab.com/data-api/v3/index.html)
- [OpenAPI](openapi/sketchfab-data-api-openapi.yml)
- [JSON Schema — Model](json-schema/sketchfab-model-schema.json)
- [JSON-LD](json-ld/sketchfab-context.jsonld)
- [Naftiko Capability — Models](capabilities/data-models.yaml)
- [Naftiko Capability — Users](capabilities/data-users.yaml)
- [Naftiko Capability — Collections](capabilities/data-collections.yaml)
- [Naftiko Capability — Search](capabilities/data-search.yaml)

### Sketchfab Viewer API
Client-side JavaScript library for controlling an embedded Sketchfab 3D viewer — camera, materials, textures, annotations, animation, post-processing filters, screenshot capture, and an event stream. Distributed as `sketchfab-viewer-1.12.x.js` from `static.sketchfab.com` and published on npm.

**Human URL:** [https://sketchfab.com/developers/viewer](https://sketchfab.com/developers/viewer)

- [Documentation](https://sketchfab.com/developers/viewer)
- [Documentation — Functions Reference](https://sketchfab.com/developers/viewer/functions)
- [Documentation — Initialization](https://sketchfab.com/developers/viewer/initialization)
- [Source — github.com/sketchfab/viewer-api](https://github.com/sketchfab/viewer-api)

### Sketchfab Download API
Retrieve a downloadable model in glTF, GLB, or USDZ format via short-lived signed URLs. Requires end-user OAuth authentication; application-level downloads require an Enterprise contract. Source formats (FBX, OBJ) are not exposed.

**Human URL:** [https://sketchfab.com/developers/download-api](https://sketchfab.com/developers/download-api)

- [Documentation](https://sketchfab.com/developers/download-api)
- [OpenAPI](openapi/sketchfab-download-api-openapi.yml)
- [Naftiko Capability — Download](capabilities/download-models.yaml)

### Sketchfab oEmbed API
oEmbed-protocol endpoint at `https://sketchfab.com/oembed` returning JSON with an iframe embed snippet for any Sketchfab model or playlist URL. Supports `maxwidth` and `maxheight`; viewer aspect is always 16:9.

**Human URL:** [https://sketchfab.com/developers/oembed](https://sketchfab.com/developers/oembed)

- [Documentation](https://sketchfab.com/developers/oembed)
- [OpenAPI](openapi/sketchfab-oembed-api-openapi.yml)
- [Naftiko Capability — oEmbed](capabilities/oembed.yaml)

### Sketchfab OAuth 2.0 API
Authorization Code, Implicit, and Resource Owner Password Credentials grants with refresh-token rotation. Access tokens are valid for one month. Authorize endpoint: `https://sketchfab.com/oauth2/authorize/`. Token endpoint: `https://sketchfab.com/oauth2/token/`.

**Human URL:** [https://sketchfab.com/developers/oauth](https://sketchfab.com/developers/oauth)

- [Documentation](https://sketchfab.com/developers/oauth)
- [OpenAPI](openapi/sketchfab-oauth-api-openapi.yml)

## Common Properties

- [Portal — sketchfab.com](https://sketchfab.com)
- [Portal — Sketchfab Developers](https://sketchfab.com/developers)
- [Documentation — Data API](https://sketchfab.com/developers/data-api)
- [Documentation — Data API v3 Swagger](https://docs.sketchfab.com/data-api/v3/index.html)
- [Documentation — Viewer API](https://sketchfab.com/developers/viewer)
- [Documentation — Download API](https://sketchfab.com/developers/download-api)
- [Documentation — oEmbed](https://sketchfab.com/developers/oembed)
- [Documentation — OAuth](https://sketchfab.com/developers/oauth)
- [Documentation — Developer Guidelines](https://sketchfab.com/developers/guidelines)
- [GettingStarted](https://sketchfab.com/developers)
- [SignUp](https://sketchfab.com/signup)
- [Login](https://sketchfab.com/login)
- [TermsOfService — sketchfab.com/terms](https://sketchfab.com/terms)
- [TermsOfService — Developer Terms](https://sketchfab.com/developers/terms)
- [PrivacyPolicy](https://sketchfab.com/privacy)
- [Pricing](https://sketchfab.com/plans)
- [Blog](https://sketchfab.com/blogs/community)
- [Forum](https://forum.sketchfab.com/)
- [Support — Fab Support (Sketchfab)](https://support.fab.com/s/?ProductOrigin=Sketchfab)
- [Labs](https://labs.sketchfab.com/)
- [GitHubOrganization](https://github.com/sketchfab)
- [SDK — Viewer API JavaScript SDK](https://github.com/sketchfab/viewer-api)
- [SDK — Viewer API npm package](https://www.npmjs.com/package/sketchfab-viewer)
- [SDK — Sketchfab OAuth2 JavaScript SDK](https://github.com/sketchfab/sketchfab-oauth2)
- [SDK — NodeJS API client](https://github.com/sketchfab/node-sketchfab)
- [Plugin — Blender](https://github.com/sketchfab/blender-plugin)
- [Plugin — Unity](https://github.com/sketchfab/unity-plugin)
- [Plugin — Unreal Engine](https://github.com/sketchfab/unreal-plugin)
- [Plugin — Godot](https://github.com/sketchfab/godot-plugin)
- [Plugin — Cinema 4D](https://github.com/sketchfab/c4d-plugin)
- [Plugin — Autodesk Maya](https://github.com/sketchfab/maya-exporter)
- [Plugin — Modo](https://github.com/sketchfab/modo-exporter)
- [Plugin — 3ds Max](https://github.com/sketchfab/3dsmax-exporter)
- [Plugin — Lightwave](https://github.com/sketchfab/lightwave-exporter)
- [Plugin — WordPress](https://github.com/sketchfab/wordpress-plugin)
- [Plugin — CKEditor](https://github.com/sketchfab/ckeditor-plugin)
- [Plugin — phpBB](https://github.com/sketchfab/phpbb-plugin)
- [CodeExamples — Viewer experiments](https://github.com/sketchfab/experiments)
- [CodeExamples — Model configurator (chair)](https://labs.sketchfab.com/experiments/configurator/)
- [CodeExamples — Configurator framework](https://github.com/sketchfab/configurator-framework)
- [Tool — UnityGLTF runtime loader](https://github.com/sketchfab/UnityGLTF)
- [Tool — Unity glTF exporter](https://github.com/sketchfab/Unity-glTF-Exporter)
- [Acquirer — Epic Games announcement](https://www.epicgames.com/site/en-US/news/sketchfab-is-joining-epic-games)
- [SuccessorPlatform — Fab](https://www.fab.com)
- [LinkedIn](https://www.linkedin.com/company/sketchfab/)
- [Twitter](https://twitter.com/Sketchfab)
- [YouTube](https://www.youtube.com/user/Sketchfab)

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Sketchfab Data API](openapi/sketchfab-data-api-openapi.yml)
- [Sketchfab Download API](openapi/sketchfab-download-api-openapi.yml)
- [Sketchfab oEmbed API](openapi/sketchfab-oembed-api-openapi.yml)
- [Sketchfab OAuth 2.0 API](openapi/sketchfab-oauth-api-openapi.yml)

### JSON Schema

- [Sketchfab Model](json-schema/sketchfab-model-schema.json)

### JSON-LD

- [Sketchfab Context](json-ld/sketchfab-context.jsonld)

### Capabilities (Naftiko)

- [Data — Models](capabilities/data-models.yaml)
- [Data — Users](capabilities/data-users.yaml)
- [Data — Collections](capabilities/data-collections.yaml)
- [Data — Search](capabilities/data-search.yaml)
- [Download — Models](capabilities/download-models.yaml)
- [oEmbed](capabilities/oembed.yaml)

### Commercial artifacts

- [Plans / Pricing](plans/sketchfab-plans-pricing.yml)
- [Rate Limits](rate-limits/sketchfab-rate-limits.yml)
- [FinOps Definition](finops/sketchfab-finops.yml)

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
