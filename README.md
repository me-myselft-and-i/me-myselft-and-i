# Hi, I’m Guotham 👋

I focus on MuleSoft development and enterprise integration architecture, building integrations and tools that make modernization easier to review, test and maintain.

My work spans MuleSoft, BizTalk, Azure Integration Services, healthcare interoperability and practical AI-assisted development.

## Areas of focus

- **MuleSoft development and architecture:** Enterprise integration, reusable configuration and connector design, structured logging and cross-platform modernization
- **AI-assisted engineering:** Agent orchestration, multi-model review, AI-assisted code generation and migration automation
- **Integration:** MuleSoft, BizTalk, Azure Logic Apps and Azure Functions
- **APIs and messaging:** Azure API Management and Service Bus
- **Development and delivery:** C#, Python, Bicep, infrastructure as code and CI/CD
- **Healthcare interoperability:** HL7 and FHIR

## Selected public projects

### MuleSoft repositories

These repositories explore reusable building blocks for MuleSoft integration solutions, with a focus on configuration management, cloud connectivity and observability.

- [Mule Git Properties Provider](https://github.com/me-myselft-and-i/mule-git-properties-provider) — a documented design concept for Git-backed application configuration using GitHub or Azure DevOps.
- [Mule Google Secret Manager Properties Provider](https://github.com/me-myselft-and-i/mule-gsm-properties-provider) — a documented design concept for retrieving configuration secrets from Google Secret Manager through a custom Mule properties provider.
- [Mule Google Cloud Storage Connector](https://github.com/me-myselft-and-i/mule-google-cloud-storage-connector) — a documented Mule 4 connector concept for Google Cloud Storage with Google Cloud Workload Identity authentication.
- [Mule JSON Logger Extended](https://github.com/me-myselft-and-i/mule-json-logger-extended) — my fork of [MuleSoft Consulting's JSON Logger](https://github.com/mulesoft-consulting/json-logger), a structured JSON logging connector for Mule 4. The original project and authors retain their attribution.

**Repository status:** The three properties-provider and storage-connector repositories currently contain design descriptions rather than published implementations. They are not presented as production-ready connectors.

### [Python FHIR API](https://github.com/me-myselft-and-i/python-fhir-api)

A FastAPI-based prototype exploring FHIR-style resources, PostgreSQL persistence, resource versioning and search. Includes Docker Compose and API tests. A learning and development project, not a claim of full FHIR conformance or production readiness.

### [Log Analyzer with ML and AI](https://github.com/me-myselft-and-i/log-analyzer-with-ml-ai)

A Python experiment combining log-pattern extraction, machine-learning classification and AI-generated summaries, with CSV and text reports. Outputs require human review; sensitive logs must not be shared with external services without authorization.

## Building at Lambogenius

Our team builds integration migration tools, developer tooling, workflow components and healthcare interoperability solutions.

### Integration migration and transformation

- [Lambogenius Integration Migration Tool (LI)](https://lambogenius.com/products/integration-migration-tool)
- [XSLT Compose](https://lambogenius.com/products/xslt-compose)
- [Liquid Compose](https://lambogenius.com/products/liquid-compose)

With [BizTalk Server 2020 approaching the end of extended support in April 2030](https://learn.microsoft.com/en-us/lifecycle/products/biztalk-server-2020), organizations need to plan their integration modernization. Drawing on hands-on BizTalk and Azure integration experience, our team developed the Lambogenius Integration Migration Tool (LI) to reduce repetitive migration work and make generated solutions easier to review, validate and maintain.

LI supports BizTalk-to-Azure integration modernization and combines:

- A primary AI agent and a separate reviewer agent, which can use a different model or provider
- CLI coordination, with batch and interactive workflows through the CLI or Migration Studio + CLI
- Customer-provided coding standards, agent skills, infrastructure and deployment-pipeline templates
- Starter Logic App templates to guide generated solution structure and conventions
- Reports at each stage and an overall final report

Our focus is reducing repetitive migration work while keeping generated changes reviewable and aligned with delivery standards.

**Planned next capability — MuleSoft migration paths:** We plan to extend LI with **BizTalk-to-MuleSoft and/or MuleSoft-to-Azure Integration Services conversion**. These are roadmap items, not currently released capabilities.

### Healthcare interoperability

- [HL7 MLLP Connector](https://lambogenius.com/products/hl7-mllp-connector)
- [HL7 v2 Codec](https://lambogenius.com/products/hl7-v2-codec)
- [HL7 Edge Gateway](https://lambogenius.com/products/hl7-edge-gateway)
- [HL7 Schema Generator](https://lambogenius.com/products/hl7-schema-generator)

#### HL7 Edge Gateway

Our team at Lambogenius developed the HL7 Edge Gateway to connect on-premises healthcare systems with cloud services and partner platforms. It exchanges HL7 v2 messages in both directions across MLLP/MLLPS, HTTP/HTTPS REST and SOAP, Azure Service Bus, and SFTP, with configurable routing, filtering and transformation. It also supports X12 EDI exchanges through CAQH CORE and converts HL7 v2 into FHIR R4 Bundles for delivery to FHIR servers. TLS and authentication options, durable store-and-forward delivery and retries help teams modernize existing interfaces without requiring every source system to change its protocol.

### BizTalk developer tools

- [BizTalk Binding Viewer](https://lambogenius.com/products/biztalk-binding-viewer)
- [BizTalk BAM Viewer](https://lambogenius.com/products/biztalk-bam-viewer)
- [BizTalk Map Viewer](https://lambogenius.com/products/biztalk-map-viewer)
- [BizTalk Pipeline Viewer](https://lambogenius.com/products/biztalk-pipeline-viewer)
- [BizTalk ESB Viewer](https://lambogenius.com/products/biztalk-esb-viewer)
- [BizTalk Rules Engine Viewer](https://lambogenius.com/products/biztalk-rules-engine-viewer)
- [BizTalk Orchestration Viewer](https://lambogenius.com/products/biztalk-orchestration-viewer)

### Additional developer tooling

- [TAR.GZ Viewer](https://lambogenius.com/products/tar-gz-viewer)

## How I approach engineering

- Make assumptions and limitations explicit.
- Keep generated changes inspectable and testable.
- Prefer reproducible examples over unsupported claims.
- Separate prototypes from production-ready capabilities.
- Keep client code, credentials and sensitive data out of public examples.

## About these repositories

This profile includes personal projects, experiments and forks. Forks retain their upstream attribution and are not presented as projects I created from scratch.

[Visit Lambogenius](https://lambogenius.com) 
