# Protector Guard — Terms of Service

**Effective date: 27 September 2026.**

## 1. Operator and contact

Protector Guard is operated by **Tamás Gál, Hungary**, an individual. For support, service complaints, billing assistance, or abuse reports, email **[gal-tamas@outlook.hu](mailto:gal-tamas@outlook.hu)**.

These terms cover the Protector Guard Discord application, ID `1553751912979890246`. Discord is a separate service with its own terms. Protector Guard is not operated or endorsed by Discord. Its [Privacy Policy](PRIVACY.md) describes personal data handling.

## 2. Installing and using the service

You must meet Discord's applicable minimum age and have permission to install or configure applications in the server concerned. Purchasers must have the legal capacity and payment authorization needed to enter a subscription. Server managers are responsible for informing members about the bot, providing these policy links, choosing appropriate channels and exemptions, and restricting access to moderation evidence.

Do not use the service for harassment, unlawful surveillance, discrimination, infringement of others' rights, or other unlawful activity. Do not attempt to bypass subscription checks, overwhelm the service, or obtain another server's data. Discord's applicable platform rules continue to apply.

## 3. What the bot does

Protector Guard provides configurable message flood and repeat detection, invite filtering, administrator-defined blocked domains, OCR-assisted detection of selected image scam patterns, and moderator commands for recording warnings, timeouts, and message cleanup.

OCR currently recognizes English and Russian text and checks selected patterns involving credential requests, fake Nitro offers, and gambling promotions. It can miss threats and flag innocent content, including quoted examples. It is a moderation aid, not a guarantee of security or a replacement for human moderators. A GPT assistant is not included in this version.

Automatic protection runs only in selected channels and their threads. Bots, webhooks, server owners, members with Manage Messages permission, and configured exempt roles are excluded. Initial setup uses **review mode**: findings go to a restricted alert channel and messages remain. Server managers may explicitly enable deletion mode. Before automatic deletion the bot attempts to preserve evidence in the server's alert channel; if preservation or permission checks fail, the original remains. Deletions cannot be restored as the original Discord message.

Manual moderation commands can affect members or delete messages when an authorized moderator invokes them. The purge command deletes eligible recent messages without archiving every deleted message.

## 4. Subscriptions and limits

Inviting or configuring the bot does not purchase a subscription. Paid protection and paid moderation commands require an active **server subscription** for the particular Discord server. One server's subscription does not unlock other servers.

**Prelaunch status:** paid checkout is not yet available. The intended starting price is **USD $9.99 per server per month**. A purchase becomes available only when Discord displays an enabled offer. Before purchase, the offer and checkout must state the actual price, renewal interval, features, and image allowance; localized prices and applicable taxes may differ. No future feature is included unless expressly listed in the purchased offer.

Subscriptions renew as described at checkout unless canceled. Manage or cancel a Discord purchase in Discord's subscription settings, using the appropriate device or store for the original purchase. Access normally continues until the entitlement's paid period ends. **Removing the bot, pausing protection, or deleting bot settings does not cancel a subscription.** See [Discord's cancellation instructions](https://support.discord.com/hc/en-us/articles/26729692307351-How-to-Cancel-your-Premium-App-Subscription).

Image allowances apply separately to each server and reset at 00:00 UTC on the first day of each calendar month, independently of the payment renewal date. Scanning currently supports at most two PNG, JPEG, or WebP attachments per message, each up to 6 MiB and 12 megapixels. Unsupported images, full processing queues, unavailable services, and exhausted allowances may prevent scanning. Text protection can continue after an image allowance is exhausted. Failed image processing does not consume an image allowance. `/status` shows the current allowance and use.

Protector Guard Pro includes **1,000 image scans per server per UTC calendar month**. The allowance applies to the server as a whole. Text moderation continues after the image allowance is used, subject to normal service availability. If Discord cannot verify subscription access, paid operations pause until access can be checked.

## 5. Refunds, complaints, and consumer rights

For purchases processed by Discord or a mobile store, use that provider's refund process, including [Discord's refund policy](https://support.discord.com/hc/en-us/articles/360012668071-Refund-Policy). Contact the operator for service issues or requests that the provider's process does not resolve. Describe the problem and identify the affected server; never send a password, token, or full payment card details.

Nothing in these terms removes mandatory consumer rights, including any applicable withdrawal, conformity, refund, or other statutory remedy. These terms do not themselves obtain consent to waive a withdrawal right. Any legally required purchase disclosures or consent for immediate performance must be handled before a paid purchase is completed.

## 6. Availability, changes, and suspension

The operator aims to maintain the service but does not promise uninterrupted availability or a particular detection rate. Discord, hosting outages, maintenance, permissions, quotas, or other technical limits may interrupt protection. Statutory service obligations and remedies remain unaffected.

The operator may restrict access where reasonably necessary to address misuse, security incidents, legal obligations, or platform enforcement. Where possible, the reason and a way to contact support will be provided. Subscription cancellation and applicable refund rights remain separate from technical suspension.

Material changes to paid features, allowances, prices, or these terms will be communicated before they take effect, with an opportunity to cancel before the affected renewal where required. Existing paid rights will not be removed retroactively through an undisclosed change. A discontinuation will be handled with notice and any legally required remedies.

## 7. Responsibility and disputes

Server moderators remain responsible for their moderation decisions and for reviewing disputed findings. Contact server moderators first to appeal a server action; contact the operator for a technical error, privacy issue, or suspected abuse of the bot.

Nothing here excludes responsibility that applicable law prohibits excluding. These terms are governed by Hungarian law, without depriving consumers of mandatory protections or court rights available under the law that applies to them. Please contact the operator first to seek an informal resolution; this does not limit other available remedies.
