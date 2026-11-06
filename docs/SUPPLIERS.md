# Supplier Research and Qualification

No supplier is verified as meeting all requirements. All commercial terms and technical claims require written confirmation and live tests.

## Candidates to contact
- MVNE Wholesale: wholesale/mobile white-label inquiry.
- Atomic Mobile: MVNO enablement / roaming inquiry.
- 1GLOBAL: enterprise eSIM/mobile number capabilities inquiry.
- Tello, Ultra Mobile, US Mobile: consumer product benchmarks; do not assume wholesale resale rights or offshore first activation.
- Telnyx / Twilio: VoIP/SIP/WebRTC/SMS track, not a guaranteed bank OTP solution.

## Required written questionnaire
1. Is the issued +1 number classified as mobile rather than VoIP/fixed-line?
2. Can a brand-new customer activate an eSIM **while physically in mainland China**, without prior US network attachment? Evidence and exact steps?
3. Which Chinese partner networks carry voice, SMS, and data? Is native incoming short-code SMS supported?
4. Is Wi-Fi Calling supported from mainland China? Any network/geographic limitations?
5. Are 6–24 months of primarily offshore usage permitted? What fair-use thresholds apply?
6. Do you authorize resale to consumers/businesses in China? Which KYC/AML/sanctions obligations apply?
7. Can we provision numbers/eSIMs, suspend, renew, port in/out through APIs?
8. Can inbound SMS content be delivered to our server with end-user authorization? Are short codes included?
9. What are the per-line monthly costs, setup fees, eSIM fees, roaming SMS/voice rates, minimum commits, deposits, and chargebacks?
10. Who is provider of record? Who owns the number? What happens on cancellation, suspension, insolvency or provider change?
11. What are SLA, fraud escalation, data residency, security and support commitments?

## Test plan
- Obtain 3–5 legitimate test lines per shortlisted supplier.
- Test first activation in China on compatible devices, with documented network conditions.
- Test native inbound/outbound calls, person-to-person SMS, selected authorized short-code OTP services, Wi-Fi Calling, and 30/60/90-day continuity.
- Record success/failure by carrier, device, region, service and timestamp; never store actual OTP values.

## Decision rubric
Pass only if lawful resale, remote activation, China SMS/voice, and acceptable long-term roaming are confirmed. API inbox is optional but requires separate proof.
