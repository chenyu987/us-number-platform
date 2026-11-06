# US Number Platform — Product & Feasibility Repository

> Status: discovery / pre-MVP. Private repository recommended.

## Vision
Self-service US phone number platform for legitimate cross-border individuals and businesses: obtain a number, use web calling/SMS, optionally configure a SIP softphone, and eventually offer genuine US mobile eSIM lines through an authorized MVNO/MVNE partner.

## Critical product insight
**Receiving verification codes is the primary use case to validate.** A VoIP number can receive some SMS but many banks/platforms reject VoIP numbers or short-code delivery. A real US mobile number may improve compatibility but cannot guarantee OTP delivery. Never market guaranteed bank verification or provide shared disposable numbers.

## Product tracks
| Track | Capabilities | Reality |
|---|---|---|
| A: VoIP SaaS | Number purchase, browser calling, inbound SMS, SIP/Zoiper | Technically mature; OTP compatibility limited |
| B: Mobile eSIM reseller | Real mobile MSISDN, native calling/SMS | Requires carrier/MVNO/MVNE agreement; offshore activation and China roaming unverified |
| C: Unified experience | Single dashboard, subscription, number lifecycle, support | SMS web access to mobile lines requires explicit carrier API/permissions |

## Gate before engineering
Do not invest in a full platform until a supplier **confirms in writing**: (1) genuine US mobile number, (2) initial eSIM activation from mainland China, (3) inbound SMS including short codes and native voice in China, (4) prolonged international use permitted, (5) authorized resale, (6) API provisioning and optional inbound SMS API, (7) port-out and number ownership rules. Test on real devices and legitimate accounts with user authorization.

## Documents
- [Product requirements](docs/PRD.md)
- [Architecture](docs/ARCHITECTURE.md)
- [Supplier due diligence](docs/SUPPLIERS.md)
- [Compliance and risk](docs/COMPLIANCE.md)
- [Economics](docs/ECONOMICS.md)
- [Roadmap and acceptance gates](planning/ROADMAP.md)

## MVP boundary
First: supplier feasibility and a manual concierge pilot. Only after validation: customer portal, billing, number provisioning, usage, support. VoIP web dialer and Zoiper integration can be a separate business communications track, not a substitute for genuine mobile OTP use cases.

## Security
No real phone numbers, OTP contents, SIP passwords, API keys, customer PII, or carrier contracts in Git. Store secrets in a managed secret store. Treat OTPs as highly sensitive, avoid logging message bodies, restrict access, and define short retention.
