# Sketchfab (sketchfab)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Sketchfab is the largest dedicated platform for publishing, sharing, discovering, buying, and embedding interactive 3D content on the web. Founded in Paris in 2012 by Cedric Pinson and Alban Denoyel and acquired by Epic Games on July 21, 2021, Sketchfab hosts millions of 3D models from artists, museums, scanning rigs, and studios — much of it Creative Commons licensed. The platform exposes a public REST Data API for programmatic upload and content management, a JavaScript Viewer API for controlling the embedded WebGL/WebXR viewer, a Download API delivering glTF/GLB/USDZ, an oEmbed endpoint, and OAuth 2.0 authentication, alongside native exporters for every major 3D / DCC tool. Following the Fab.com launch in 2024 the Sketchfab Store has been retired into Epic's unified content marketplace while the publishing, viewing, and developer APIs remain on sketchfab.com.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/sketchfab/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/sketchfab/refs/heads/main/apis.yml)

## Scope

- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- 3D
- Models
- Marketplace
- Viewer
- WebGL
- glTF
- AR
- VR
- Creative
- Epic Games

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### Sketchfab Data API

REST API for reading and writing Sketchfab data. Upload, list, update, and delete 3D models; manage collections, comments, likes, and bookmarks; search the public model catalog; and manage user, organization, and project resources. Supports OAuth 2.0 and personal API token authentication. Base URL is https://api.sketchfab.com with version 3 endpoints under /v3/.

- **Human URL:** [https://sketchfab.com/developers/data-api](https://sketchfab.com/developers/data-api)
- **Base URL:** `https://api.sketchfab.com`

#### Tags

- 3D
- Models
- Marketplace
- Content

#### Properties

- [Documentation](https://sketchfab.com/developers/data-api)
- [Documentation](https://docs.sketchfab.com/data-api/v3/index.html)
- [OpenAPI](openapi/sketchfab-data-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/sketchfab-model-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/sketchfab-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Sketchfab Viewer API

Client-side JavaScript library for controlling an embedded Sketchfab 3D viewer. Exposes camera control, screenshot capture, annotation, material and texture manipulation, post-processing filters, animation playback, and an event stream (viewerready, click, annotationSelect, animationPlay, etc.). Distributed as a browser-loadable script from static.sketchfab.com and published on npm.

- **Human URL:** [https://sketchfab.com/developers/viewer](https://sketchfab.com/developers/viewer)

#### Tags

- 3D
- Viewer
- JavaScript
- WebGL
- Embed

#### Properties

- [Documentation](https://sketchfab.com/developers/viewer)
- [Documentation](https://sketchfab.com/developers/viewer/functions)
- [Documentation](https://sketchfab.com/developers/viewer/initialization)
- [Source Code](https://github.com/sketchfab/viewer-api)
- [SDK](https://static.sketchfab.com/api/sketchfab-viewer-1.12.1.js)
- [Postman Collection](collections/sketchfab-download-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sketchfab-download-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/sketchfab-oauth-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sketchfab-oauth-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/sketchfab-oembed-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sketchfab-oembed-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Sketchfab Download API

Programmatic download of 3D models from Sketchfab's library in glTF, GLB, and USDZ formats. Requires end-user OAuth authentication. Source formats (FBX, OBJ, etc.) are not exposed through the public API; application-level download access without user authentication requires a contract with Sketchfab.

- **Human URL:** [https://sketchfab.com/developers/download-api](https://sketchfab.com/developers/download-api)

#### Tags

- 3D
- Models
- Download
- glTF
- USDZ

#### Properties

- [Documentation](https://sketchfab.com/developers/download-api)
- [OpenAPI](openapi/sketchfab-download-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sketchfab-download-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sketchfab-download-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Sketchfab oEmbed API

oEmbed-protocol endpoint at https://sketchfab.com/oembed that returns JSON containing an HTML <iframe> snippet for any Sketchfab model or playlist URL. Supports maxwidth and maxheight parameters; always returns a 16:9 viewer.

- **Human URL:** [https://sketchfab.com/developers/oembed](https://sketchfab.com/developers/oembed)

#### Tags

- 3D
- Embed
- oEmbed
- Models

#### Properties

- [Documentation](https://sketchfab.com/developers/oembed)
- [OpenAPI](openapi/sketchfab-oembed-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sketchfab-oembed-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sketchfab-oembed-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Sketchfab OAuth 2.0 API

OAuth 2.0 authorization server for the Sketchfab platform. Supports Authorization Code, Implicit, and Resource Owner Password Credentials grant types plus refresh-token rotation. Authorize endpoint at /oauth2/authorize/ and token endpoint at /oauth2/token/. Access tokens expire after one month.

- **Human URL:** [https://sketchfab.com/developers/oauth](https://sketchfab.com/developers/oauth)

#### Tags

- OAuth
- Authentication
- Authorization

#### Properties

- [Documentation](https://sketchfab.com/developers/oauth)
- [OpenAPI](openapi/sketchfab-oauth-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sketchfab-oauth-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sketchfab-oauth-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://sketchfab.com)
- [Portal](https://sketchfab.com/developers)
- [Documentation](https://sketchfab.com/developers/data-api)
- [Documentation](https://docs.sketchfab.com/data-api/v3/index.html)
- [Documentation](https://sketchfab.com/developers/viewer)
- [Documentation](https://sketchfab.com/developers/download-api)
- [Documentation](https://sketchfab.com/developers/oembed)
- [Documentation](https://sketchfab.com/developers/oauth)
- [Documentation](https://sketchfab.com/developers/guidelines)
- [Getting Started](https://sketchfab.com/developers)
- [Sign Up](https://sketchfab.com/signup)
- [Login](https://sketchfab.com/login)
- [Terms of Service](https://sketchfab.com/terms)
- [Terms of Service](https://sketchfab.com/developers/terms)
- [Privacy Policy](https://sketchfab.com/privacy)
- [Pricing](https://sketchfab.com/plans)
- [Plans](plans/sketchfab-plans-pricing.yml)
- [Rate Limits](rate-limits/sketchfab-rate-limits.yml)
- [Fin Ops](finops/sketchfab-finops.yml)
- [Blog](https://sketchfab.com/blogs/community)
- [Forum](https://forum.sketchfab.com/)
- [Support](https://support.fab.com/s/?ProductOrigin=Sketchfab)
- [Labs](https://labs.sketchfab.com/)
- [GitHub Organization](https://github.com/sketchfab)
- [SDK](https://github.com/sketchfab/viewer-api)
- [SDK](https://www.npmjs.com/package/sketchfab-viewer)
- [SDK](https://github.com/sketchfab/sketchfab-oauth2)
- [SDK](https://github.com/sketchfab/node-sketchfab)
- [Plugin](https://github.com/sketchfab/blender-plugin)
- [Plugin](https://github.com/sketchfab/unity-plugin)
- [Plugin](https://github.com/sketchfab/unreal-plugin)
- [Plugin](https://github.com/sketchfab/godot-plugin)
- [Plugin](https://github.com/sketchfab/c4d-plugin)
- [Plugin](https://github.com/sketchfab/maya-exporter)
- [Plugin](https://github.com/sketchfab/modo-exporter)
- [Plugin](https://github.com/sketchfab/3dsmax-exporter)
- [Plugin](https://github.com/sketchfab/lightwave-exporter)
- [Plugin](https://github.com/sketchfab/wordpress-plugin)
- [Plugin](https://github.com/sketchfab/ckeditor-plugin)
- [Plugin](https://github.com/sketchfab/phpbb-plugin)
- [Code Examples](https://github.com/sketchfab/experiments)
- [Code Examples](https://labs.sketchfab.com/experiments/configurator/)
- [Code Examples](https://github.com/sketchfab/configurator-framework)
- [Tool](https://github.com/sketchfab/UnityGLTF)
- [Tool](https://github.com/sketchfab/Unity-glTF-Exporter)
- [Acquirer](https://www.epicgames.com/site/en-US/news/sketchfab-is-joining-epic-games)
- [Successor Platform](https://www.fab.com)
- [LinkedIn](https://www.linkedin.com/company/sketchfab/)
- [Twitter](https://twitter.com/Sketchfab)
- [YouTube](https://www.youtube.com/user/Sketchfab)
- [Features](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com
**URL:** https://apievangelist.com
