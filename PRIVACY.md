# Protector Guard — Privacy Policy

**Effective date: 27 September 2026.**

## 1. Who operates the service

**Tamás Gál, Hungary** operates Protector Guard, Discord application `1553751912979890246`. Contact **[gal-tamas@outlook.hu](mailto:gal-tamas@outlook.hu)** for privacy requests or questions.

This notice explains the operator's processing for providing and securing Protector Guard. Discord controls its platform processing under its own policy. Server managers separately choose moderation rules, channels, and access to evidence; their own data protection responsibilities also apply. Where a customer requires processing solely on its instructions, the parties must establish the appropriate data processing terms before that use.

## 2. Information received and used

The bot receives information from Discord when installed and permitted to access a server. Depending on enabled features, this includes:

| Information | Use |
| --- | --- |
| Server, channel, role, member, and message IDs; permissions and relevant role membership | Apply the correct server configuration, authorize commands, and enforce exemptions |
| Message text, attachment metadata, supported attached images, and OCR text | Detect configured spam, invites, blocked domains, and selected image scam patterns |
| Server settings, enabled modules, exemptions, blocked domains, and allowed invite codes | Remember the configuration chosen by server managers |
| Moderation rule, action, timestamp, and affected IDs | Record and investigate moderation incidents |
| Subscription entitlement identifiers, server association, validity dates, and status | Verify paid access to the correct server |
| Per-server monthly image counts and limited status-notice timestamps | Apply usage allowances and avoid repeated alerts |
| Support emails and information supplied in them | Answer requests, resolve problems, and handle complaints |

Discord may deliver message events from channels visible to the bot even if those channels have not been selected for protection. The application applies automatic moderation only to selected channels and threads, and uses the configured exemptions. Give the bot access only to channels necessary for its role. The bot does not process direct messages as a moderation feature or request account passwords or login tokens.

The operator does not receive payment card details through the bot. Discord and its payment providers process purchases. Do not send sensitive documents or secrets to the bot or include them in support requests unless separately agreed through an appropriate process.

## 3. Purposes and legal bases

The operator uses customer account and entitlement information as necessary to provide the requested service and administer a subscription or support request (contractual necessity). Security, moderation assistance, appropriate access checks, limited anti-abuse counters, and service reliability rely on legitimate interests in protecting the service and participating communities, balanced against the rights of affected members. Applicable legal obligations may require processing for compliance or responding to lawful requests. Where consent is required for a separate optional use, it will be requested in advance.

Server membership is not treated as blanket consent to unrelated data use. The bot does not sell personal data, use messages for advertising, build cross-server profiles, or train AI models on messages. In this version, **no messages or images are sent to a GPT or other external AI service**. OCR runs in a separate process on the operator's hosting infrastructure. Recognition-model files can be downloaded from the model distributor; user images are not uploaded to that distributor.

## 4. Evidence and automated moderation

When a configured rule detects content, the bot may post the original message text, affected IDs, reason, and downloaded image evidence in the server's configured alert channel. The bot requires that channel to deny access to `@everyone`; server managers must also review other role and member overrides. Anyone granted access by the server may see that evidence.

Review mode leaves the original message in place. Deletion mode may remove a matching message automatically after checks and evidence preservation. Moderator commands may also record warnings, time out a member, or delete recent messages. These rules can make mistakes. Ask server moderators for human review of a disputed action; contact the operator about technical faults or privacy concerns. The bot does not make employment, credit, insurance, or similar eligibility decisions.

## 5. Storage and retention

The deployed application and persistent database use Fly.io in Frankfurt, Germany. Current application retention is:

| Data | Retention |
| --- | --- |
| Server configuration | Until `/guard forget confirm:true`, removal of the bot as detected by the service, or an applicable deletion request |
| Incident metadata in the bot database | 30 days; removed earlier with server configuration deletion |
| Monthly image usage totals keyed by server ID | Retained in monthly buckets for up to approximately 131 days, including after removal, to prevent allowance resets |
| Status-notice suppression records | Approximately one day |
| Fly volume snapshots | Configured to expire after five days; deleted database records may remain in snapshots until expiry |
| Text, image bytes, OCR results, and short-lived detection or Discord caches | Processed in memory; caches clear or are replaced during operation or at process restart. No general message-history archive is written to the bot database |
| Evidence and manual moderation logs posted in Discord | Remain in the server until removed there; the bot's 30-day database cleanup does **not** delete these Discord messages |
| Support correspondence | Kept while resolving the request and then only as needed for follow-up or applicable legal obligations; contact the operator for review or deletion |

Expiry checks run during service operation; an offline service applies database cleanup when it starts again. OCR model caches contain language-model files, not a collection of uploaded user images. Application operational logs are designed to record service health and generic failures rather than message bodies or tokens. Hosting and Discord may maintain their own operational records under their policies.

The operator restricts access to hosting credentials and database files. Moderation data is not shared with unrelated servers. No system can promise absolute security; incidents will be handled and notified as required by applicable law and platform rules.

## 6. Recipients and international processing

Necessary service providers include **Discord** for platform events, subscriptions, and moderation evidence; **Fly.io** for computing, storage, and backups; and **Microsoft Outlook** for support email. Authorized server moderators receive evidence in their own server. The operator may disclose information where required by law, to protect legal rights, or with a valid request or permission.

Although the bot's compute region is Germany, this does not mean every provider processes all information only in the EEA. Provider support, platform, email, or infrastructure processing may involve other countries. Where an EEA transfer requires safeguards, the operator must use an applicable lawful mechanism, such as an adequacy decision or standard contractual clauses. Contact the operator for details of safeguards relevant to your data. Applicable supplier arrangements must be verified before paid launch.

## 7. Your choices and rights

Server managers can change channels, exemptions, or modules, pause the bot, remove it, or use `/guard forget confirm:true`. Forgetting settings does not delete copies already posted to Discord, cancel a subscription, or immediately remove the limited anti-abuse usage counters described above.

Where applicable, you can request access, correction, deletion, restriction, portability, or object to processing based on legitimate interests. If a separate use relies on consent, you can withdraw that consent without affecting earlier lawful processing. Send requests to **gal-tamas@outlook.hu**, preferably with the relevant Discord user/server/message IDs and a description of the request. The operator may ask for proportionate identity verification, but will not ask for your Discord password or token.

Requests will be handled without undue delay, normally within one month. If the law permits extra time or an exception, the operator will explain it. Rights may depend on the circumstances; the operator will explain any refusal and available complaint routes. You may complain to your local supervisory authority or Hungary's **[National Authority for Data Protection and Freedom of Information (NAIH)](https://www.naih.hu/)**.

## 8. Changes and contact

Material changes will be communicated through the service or the published policy before a new use begins where required. A future GPT assistant would require updated disclosures and appropriate configuration before it processes user content. Questions and reports can be sent to **gal-tamas@outlook.hu**.
