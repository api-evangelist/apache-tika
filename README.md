# Apache Tika (apache-tika)

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
