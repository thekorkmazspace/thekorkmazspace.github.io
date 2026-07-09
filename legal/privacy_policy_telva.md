# Riyo Privacy Policy

Effective date: 2026-05-24

This draft is for the iOS first release of Riyo. Prompt 20 uses the public Google Docs legal pages below for App Store readiness.
Previous TELVA / Dreams naming is historical. Current iOS identity is Riyo.

Current expected URLs:
- Privacy Policy: https://docs.google.com/document/d/e/2PACX-1vSq2_mfY-IXdls4uQMbxMKJezvpDQZQUIRtFzLUReDfHN3EObxReIDeb8gO2aBqUONv_3BBKNc3fGm7/pub
- Terms of Use: https://docs.google.com/document/d/e/2PACX-1vS9E7ek9pXv2nGR8PAi-2rLQXiYgCdH_zwkOec7-XRzCJaLRsNwXHPFPzRCbNBnuJEgOK4925hii4Re/pub
- Support: korkmazfatih.dev@gmail.com

Contact: korkmazfatih.dev@gmail.com

## 1. Overview

Riyo is an AI-assisted dream journal and symbol reflection app. It helps users record dreams, reflect on recurring symbols, and notice personal patterns over time.

Riyo is designed for self-reflection and entertainment. Riyo does not provide medical advice,
psychological diagnosis, therapy, professional advice, spiritual or religious guidance, financial
advice, legal advice, prediction, or fortune-telling. Riyo is not a crisis-support tool. Users
should contact qualified professionals for medical, mental health, financial, legal, or emergency
concerns.

This policy explains what information may be processed when users use Riyo.

## 2. What Riyo Does

Riyo lets users:
- write dream journal entries;
- select mood, intention, or reflection context;
- optionally attach images to image-based journal entries;
- receive AI-assisted symbolic reflections;
- save and revisit reflections over time;
- rate or provide feedback on reflections.

Riyo, kullanıcıların rüyalarını kaydetmelerine, tekrar eden sembolleri fark etmelerine ve zaman içindeki kişisel kalıpları gözlemlemelerine yardımcı olan AI destekli bir rüya günlüğü ve sembol analizi uygulamasıdır. Riyo kişisel farkındalık ve eğlence amaçlıdır.

## 3. What Riyo Does Not Do

Riyo does not provide:
- medical advice or diagnosis;
- psychological diagnosis or therapy;
- spiritual advice;
- financial advice;
- legal advice;
- predictive advice or guaranteed claims about outcomes.

Riyo tıbbi, psikolojik, ruhsal, finansal veya geleceğe yönelik kesin tavsiye sunmaz.

## 4. Information Users Provide

Users may choose to provide:
- dream journal text;
- selected mood or intention;
- optional image attachments;
- saved reflections;
- ratings and written feedback;
- reader or guide selection if that feature is used;
- profile-like context that the user enters, such as language preference or other optional reflection context.

Users should avoid submitting information they do not want processed by Riyo or its service providers. Dream text can include sensitive personal information if the user chooses to type it.

Do not enter sensitive health, medical, identity, financial, legal, or other highly sensitive
personal information into Riyo.

## 5. Information Collected Automatically

Riyo and its SDKs may collect technical or usage information, such as:
- app events and feature usage;
- ad availability and ad interaction events;
- device, app version, operating system, and installation identifiers;
- crash logs, diagnostics, and device state at the time of a crash;
- request identifiers, timestamps, prompt version, provider/model metadata, reflection type, and processing status.

Ad and analytics SDKs may process identifiers and signals according to platform settings, consent choices, SDK configuration, and applicable law.

## 6. AI Processing

User-submitted dream text and optional images may be sent through Riyo's backend to third-party AI
model providers to generate symbolic dream reflections.

Provider API keys are not stored in the mobile app. Mobile apps should call Riyo's backend, and Riyo's backend may call third-party AI model providers.

AI processing is used to generate symbolic reflection. It is not used to provide medical advice,
psychological diagnosis, therapy, professional advice, spiritual or religious guidance, financial
advice, legal advice, prediction, or fortune-telling. AI-generated output may be incomplete,
inaccurate, or unsuitable for a user's situation.

## 7. Supabase Backend

Riyo uses Supabase as the primary backend service. The current iOS runtime uses the `riyo-db`
Supabase Edge Function (`riyo-backend`) for dream reflection requests. Supabase Edge Functions may
process journal and reflection requests. Some reflection results and metadata may be stored in
Supabase.

Possible backend-stored or backend-processed metadata includes:
- request ID;
- reflection type;
- prompt key and prompt version;
- provider and model metadata;
- timestamps;
- selected mood or intention;
- rating and feedback metadata.

This policy does not expose and should not expose Supabase secrets, service role keys, provider keys, or private project credentials.

## 8. Advertising

Riyo uses Google AdMob to support free access through ads. Current iOS ad placements are inline
native ads in Journal and Symbols. Ads may use device or advertising identifiers depending on
platform settings, consent choices, SDK configuration, and applicable law.

The iOS app requests non-personalized ad behavior where configured, including use of
non-personalized ad request parameters such as `npa=1`. The current iOS app does not request App
Tracking Transparency permission. This does not guarantee that every ad-related SDK behavior is
non-personalized in every region or platform configuration. Final behavior must be verified in App
Store Connect, Google AdMob, consent settings, and device privacy settings.

## 9. Analytics and Crash Reporting

The iOS app includes Firebase Analytics and Firebase Crashlytics.

Riyo may use Firebase Analytics to understand app usage and improve the product. Riyo may use Firebase Crashlytics to diagnose crashes and improve stability.

Analytics and crash data may include technical identifiers, app events, device state, operating system details, timestamps, and crash details. Riyo should not intentionally send journal content to analytics or ad networks.

## 10. Data Storage

Some data may be stored locally on the device, in Supabase, or by third-party service providers involved in app functionality, advertising, analytics, crash reporting, or AI processing.

Stored data may include:
- saved journal entries and reflections;
- optional image-derived request payloads where needed for processing;
- ratings and feedback;
- request metadata;
- prompt, provider, and model metadata;
- diagnostic and analytics records.

Retention periods may depend on backend configuration, service-provider settings, legal requirements, and operational needs.

## 11. Data Sharing

Riyo may share or process data with service providers that help operate the app, including:
- Supabase for backend hosting, database, and Edge Functions;
- third-party AI model providers accessed through Riyo's backend;
- Google AdMob for ads;
- Google User Messaging Platform for consent flows where used;
- Firebase Analytics for usage analytics;
- Firebase Crashlytics for crash reporting.

Riyo should not sell dream journal content. Riyo should not send journal content to ad networks for ad targeting.

## 12. User Choices

Users can choose:
- what journal text to submit;
- whether to attach images;
- whether to allow camera or photo library access;
- whether to interact with ads where required by the app flow;
- whether to provide ratings or written feedback;
- whether to use device or platform privacy controls for advertising and tracking.

Users can use operating system settings to change camera, photo library, notification, advertising, and tracking permissions where available.

## 13. Children's Privacy

Riyo is not intended for children under 13. Users under the age required by their region should not use Riyo without appropriate parental or guardian permission.

Riyo does not knowingly seek to collect personal information from children.

## 14. Security

Riyo uses backend-side handling for provider credentials. Provider API secrets must not be stored in the mobile app.

No internet service can guarantee perfect security. Users should avoid entering information they consider highly sensitive or unsafe to process.

## 15. Changes to This Policy

This policy may be updated as Riyo's features, service providers, legal requirements, or App Store disclosures change.

Before submission and after any material SDK/backend change, Riyo's privacy disclosures should be reviewed against actual runtime behavior.

## 16. Contact

For privacy questions, contact:

korkmazfatih.dev@gmail.com

## Prompt 18B Review Note

For the current iOS release package, Riyo uses third-party AI processing for dream reflections.
User dream text may be sent to Riyo's backend and an AI provider. Users should not enter sensitive
health, medical, identity, financial, legal, or other highly sensitive personal data. Riyo is not
medical advice, psychological diagnosis, therapy, professional advice, prediction, or religious
guidance. Current iOS ad placements are AdMob native ads in Journal and Symbols; `npa=1` is
preserved where configured, and ATT is not requested in the current iOS code path.

## Prompt 19 Review Note

Riyo's active iOS backend remains the Riyo Supabase backend. Release AdMob app/native IDs are
configured locally, but live ad serving, AdMob console ownership, `app-ads.txt`, and
`SKAdNetworkItems` still require final external verification. Firebase Analytics and Crashlytics
remain linked in the iOS app; the bundled Firebase plist must be replaced with one matching
`com.kairalabs.riyo` before submission if those SDKs remain enabled. Settings data controls should
be described as local unless remote deletion is separately implemented.

## Prompt 20 Review Note

The app gates first launch behind versioned legal consent before the main UI is accessible. The
legal screen links to the current Privacy Policy and Terms of Use URLs, warns that AI-generated
reflections may be wrong, states that Riyo is not medical advice, diagnosis, therapy, prediction,
religious guidance, legal advice, or financial advice, and warns users not to enter sensitive
health, identity, financial, legal, or highly private information.

Current support email: korkmazfatih.dev@gmail.com.
