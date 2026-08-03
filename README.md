# Apache Tika (apache-tika)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Apache Tika is a toolkit for detecting and extracting metadata and structured text content from over 1,000 file formats including PDF, Microsoft Office (Word, Excel, PowerPoint), OpenDocument, HTML, XML, images, audio, video, and archive formats. Tika provides a REST API server, Java library, and command-line tool. It is used by Apache Solr, Apache Nutch, and many other systems for content extraction and indexing. It is maintained by the Apache Software Foundation.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/apache-tika/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/apache-tika/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Content Extraction
- Document Processing
- Metadata
- Text Extraction
- Open Source

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-19

## APIs

### Apache Tika REST API

The Tika Server REST API provides HTTP endpoints for content type detection, text extraction, metadata extraction, and language detection from uploaded documents. Key endpoints include: PUT /tika for full text extraction, PUT /meta for metadata-only extraction, PUT /detect/stream for MIME type detection, PUT /language/stream for language detection, and GET /parsers for listing available parsers. The server supports streaming large files and returns JSON or plain text responses.

- **Human URL:** [https://cwiki.apache.org/confluence/display/TIKA/TikaServer](https://cwiki.apache.org/confluence/display/TIKA/TikaServer)

#### Tags

- REST
- Content Extraction
- Metadata
- Document Processing
- Text Extraction

#### Properties

- [Documentation](https://cwiki.apache.org/confluence/display/TIKA/TikaServer)
- [Documentation](https://tika.apache.org/)
- [OpenAPI](openapi/apache-tika-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/apache-tika.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apache-tika.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Apache Tika Java API

The Tika Java API provides the AutoDetectParser for automatic format detection and parsing, Metadata class for reading extracted metadata fields, ContentHandler for streaming SAX-based text extraction, and Detector for MIME type identification. The facade Tika class provides a simple one-line API for text extraction from any supported format.

- **Human URL:** [https://tika.apache.org/](https://tika.apache.org/)

#### Tags

- Java
- Content Extraction
- Parser
- Metadata

#### Properties

- [Documentation](https://tika.apache.org/)
- [API Reference](https://tika.apache.org/1.28/api/)
- [SDK](https://search.maven.org/search?q=org.apache.tika)
- [Postman Collection](collections/apache-tika.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apache-tika.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Repository](https://github.com/apache/tika)
- [Documentation](https://tika.apache.org/)
- [Portal](https://tika.apache.org/)
- [Getting Started](https://tika.apache.org/gettingstarted.html)
- [Release Notes](https://github.com/apache/tika/releases)
- [Support](https://cwiki.apache.org/confluence/display/TIKA/MailingLists)
- [Terms of Service](https://www.apache.org/licenses/)
- [SDK](https://pypi.org/project/tika/)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com
