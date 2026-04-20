# Apache Tika (apache-tika)
Apache Tika is a toolkit for detecting and extracting metadata and structured text content from over 1,000 file formats including PDF, Microsoft Office, HTML, XML, images, and archive formats. It provides a REST API server, Java library, and command-line tool.

**URL:** [https://tika.apache.org/](https://tika.apache.org/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Content Extraction, Document Processing, Metadata, Text Extraction, Open Source

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Apache Tika REST API
HTTP endpoints for content type detection, text extraction, metadata extraction, and language detection from uploaded documents including PUT /tika, PUT /meta, PUT /detect/stream, and GET /parsers.

**Human URL:** [https://cwiki.apache.org/confluence/display/TIKA/TikaServer](https://cwiki.apache.org/confluence/display/TIKA/TikaServer)

#### Tags:

 - REST, Content Extraction, Metadata, Document Processing, Text Extraction

#### Properties

- [Documentation](https://cwiki.apache.org/confluence/display/TIKA/TikaServer)
- [Documentation](https://tika.apache.org/)

### Apache Tika Java API
Java API with AutoDetectParser, Metadata class, ContentHandler, and Detector for automatic format detection and text/metadata extraction from any supported format.

**Human URL:** [https://tika.apache.org/](https://tika.apache.org/)

#### Tags:

 - Java, Content Extraction, Parser, Metadata

#### Properties

- [Documentation](https://tika.apache.org/)
- [APIReference](https://tika.apache.org/1.28/api/)
- [Maven Java SDK](https://search.maven.org/search?q=org.apache.tika)

## Common Properties

- [GitHubRepository](https://github.com/apache/tika)
- [Documentation](https://tika.apache.org/)
- [Portal](https://tika.apache.org/)
- [GettingStarted](https://tika.apache.org/gettingstarted.html)
- [ReleaseNotes](https://github.com/apache/tika/releases)
- [Support](https://cwiki.apache.org/confluence/display/TIKA/MailingLists)
- [TermsOfService](https://www.apache.org/licenses/)
- [Python Tika Package](https://pypi.org/project/tika/)

## Features

| Name | Description |
|------|-------------|
| 1000+ Format Support | Detect and extract content from over 1,000 file formats using parser plugins. |
| Metadata Extraction | Extract document metadata including author, creation date, title, and format-specific properties. |
| Language Detection | Automatic language detection from extracted text content. |
| MIME Type Detection | Accurate MIME type detection based on file content (magic bytes) not just file extension. |
| REST Server | Standalone HTTP server for document processing without Java library dependency. |
| OCR Integration | Optional Tesseract OCR integration for text extraction from images and scanned PDFs. |
| Recursive Parsing | Recursive parsing of archive formats and embedded documents. |

## Use Cases

| Name | Description |
|------|-------------|
| Search Indexing | Extract text from documents for indexing in Apache Solr or Elasticsearch. |
| Document Intelligence | Automated metadata extraction and classification for document management. |
| Content Migration | Batch content extraction during digital archive migration. |
| E-Discovery | Legal e-discovery content extraction from diverse document collections. |

## Integrations

| Name | Description |
|------|-------------|
| Apache Solr | Solr Cell uses Tika for extracting text from uploaded documents. |
| Apache Nutch | Nutch web crawler uses Tika for parsing fetched web page content. |
| Elasticsearch | Ingest attachment processor uses Tika for document content extraction. |
| Tesseract OCR | Optional Tesseract integration for OCR on images and scanned documents. |
| Apache NiFi | NiFi processor integration for automated document parsing workflows. |

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
