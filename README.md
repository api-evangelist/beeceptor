# Beeceptor (beeceptor)
Beeceptor is an API mocking, HTTP debugging, and proxy platform that lets
developers create mock servers instantly without any coding. It supports REST,
SOAP, GraphQL, and gRPC mocking, provides real-time HTTP traffic inspection,
webhook testing, local tunneling, and AI-powered spec generation. Teams use
Beeceptor to unblock frontend, backend, and QA workflows by simulating APIs
before they are built or while avoiding dependencies on live services.

**URL:** [https://beeceptor.com](https://beeceptor.com)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - API Mocking, Automation, Debugging, HTTP Proxy, Integrations, Mock Servers, Platform, Testing, Webhooks

## Timestamps

- **Created:** 2025-01-08
- **Modified:** 2026-04-19

## APIs

### Beeceptor API
Beeceptor's management API provides programmatic access to create and manage mock
endpoints, rules, and traffic inspection on Scale and Enterprise plans.

**Human URL:** [https://beeceptor.com/](https://beeceptor.com/)

#### Tags:

 - API Mocking, HTTP Proxy, Mock Servers, Testing

#### Properties

- [Documentation](https://beeceptor.com/docs/)
- [APIReference](https://beeceptor.com/docs/)
- [GettingStarted](https://beeceptor.com/docs/)

## Common Properties

- [Website](https://beeceptor.com)
- [Portal](https://app.beeceptor.com)
- [Pricing](https://beeceptor.com/pricing/)
- [FAQ](https://beeceptor.com/faq/)
- [Blog](https://beeceptor.com/blog/)
- [PrivacyPolicy](https://beeceptor.com/privacy-policy/)
- [TermsOfService](https://beeceptor.com/terms-of-service/)
- [GitHubOrganization](https://github.com/beeceptor)

## Features

| Name | Description |
|------|-------------|
| HTTP Traffic Inspection | Capture and inspect HTTP headers, request/response bodies, and status codes in real time as traffic flows through your mock or proxy endpoints. |
| API Mocking | Create mock servers for REST, SOAP, GraphQL, and gRPC APIs instantly with flexible request matching rules and dynamic response generation, no coding required. |
| Reverse Proxy and Interception | Wrap any live API endpoint with a Beeceptor subdomain to intercept, inspect, and selectively override traffic using man-in-the-middle proxy functionality. |
| Local Tunneling | Bind localhost services to persistent public HTTPS endpoints for webhook testing, live local debugging, and sharing local services with teammates. |
| OpenAPI Mock Generation | Upload an OpenAPI YAML or JSON specification to instantly create a fully functional mock server with one click, no manual rule creation needed. |
| AI-Powered Mock Creation | Generate realistic mock servers from natural language prompts or live traffic, using AI to synthesize responses for REST, SOAP, GraphQL, and gRPC. |
| Fault and Latency Injection | Simulate network delays, timeouts, connection resets, and HTTP error codes to validate how applications handle failure scenarios. |
| Traffic Recording | Record live API interactions and automatically generate mock rules from real traffic captures, enabling rapid mock creation from production behavior. |
| API Contract Drift Detection | Monitor for drift between live API behavior and the OpenAPI contract to detect breaking changes and schema violations over time. |
| Rate Limiting Simulation | Set maximum request limits per second, minute, or hour on endpoints to test application behavior under throttled or rate-limited conditions. |
| Programmatic API Control | Scale and Enterprise plans unlock the Beeceptor management API for programmatic creation and management of endpoints and rules in CI/CD pipelines. |
| Custom Domains | Configure custom domain names for mock endpoints on Scale and Enterprise plans, enabling team-branded or environment-specific endpoint URLs. |
| mTLS Support | Mutual TLS support for secure proxy configurations requiring client certificate authentication in enterprise environments. |
| SSO and Audit Logs | Enterprise plan includes Single Sign-On (SSO) integration and full audit logging for compliance and access governance. |

## Use Cases

| Name | Description |
|------|-------------|
| Frontend Development | Build and test frontend applications against mock APIs without waiting for backend APIs to be ready, removing cross-team blocking dependencies. |
| Backend Development | Mock downstream microservices and third-party APIs to test API behavior under various conditions including timeouts and error states. |
| Mobile Development | Access mock servers to enable parallel mobile development without backend dependencies, accelerating the mobile app development cycle. |
| QA Engineering | Simulate edge cases, rate limits, latencies, and rarely reachable code paths to achieve comprehensive test coverage without live API dependencies. |
| Webhook Testing | Inspect and debug HTTP payloads for webhook consumers and producers from platforms like Shopify, Stripe, and Sendgrid using local tunneling. |
| Load Testing | Mimic external service behavior for predictable load test outcomes and reduce costs associated with third-party API usage during performance testing. |
| API Contract Sharing | Collaborate with teammates by sharing intercepted requests and mock servers via permanent links for distributed team workflows. |

## Integrations

| Name | Description |
|------|-------------|
| Shopify | Inspect and debug Shopify webhook payloads by tunneling webhook deliveries through Beeceptor for local development and testing. |
| Stripe | Test Stripe webhook events and payment API callbacks using Beeceptor local tunneling and traffic inspection. |
| Sendgrid | Debug email delivery webhook callbacks and event notifications from Sendgrid using Beeceptor HTTP inspection and mock responses. |
| CI/CD Pipelines | Integrate Beeceptor programmatic API (Scale plan and above) into CI/CD pipelines to automate mock provisioning and teardown during testing. |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
