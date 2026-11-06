# Product Requirements Document

## Target customers
Cross-border professionals, returning students, legitimate US account holders abroad, and small international businesses needing a stable US contact number. Avoid anonymous bulk verification and account farming.

## Jobs to be done
- Acquire and retain a dedicated US number remotely.
- Receive legitimate SMS and voice calls while in China.
- Manage billing, renewal, number portability, device activation, and support.
- Optionally call in browser, receive SMS in dashboard, and use Zoiper/SIP for business lines.

## P0 — validate, not yet promised
- Carrier-authorized reseller agreement.
- Genuine mobile number classification and activation in China.
- Native voice/SMS roaming or supported Wi-Fi Calling in China.
- Short-code OTP tests across a documented sample of services (no guarantee).
- Carrier policy on long-term offshore usage.
- eSIM compatibility matrix for China-market iPhones, imported iPhones and Android.

## P1 — mobile subscription MVP
- Account creation, identity/business verification where required.
- Plan catalog, pricing, tax and billing.
- Carrier provisioning and activation QR delivery (never expose provisioning credentials in logs).
- Line status, renewal, suspend/resume, cancellation, port-out requests.
- Support tickets and auditable admin console.
- Rate limits, payment fraud controls and privacy notices.

## P2 — optional VoIP communications track
- US local number search and allocation.
- Browser calling via provider Voice SDK/WebRTC.
- Inbound/outbound SMS via messaging webhooks where permitted.
- SIP credential generation and Zoiper setup instructions.
- Multi-user routing, call logs, usage metering, prepaid limits.
- A2P 10DLC registration workflow for applicable US business messaging.

## P3 — expansion
- Carrier-integrated SMS dashboard (only if contracted and authorized).
- Multiple carriers, regional numbers, team inbox, API/white-label, AI voice tools.

## Non-goals
- Guaranteed OTP from any bank or website.
- Disposable/shared OTP inboxes, bypassing third-party verification restrictions.
- Converting ordinary VoIP numbers into native cellular eSIM without carrier support.
