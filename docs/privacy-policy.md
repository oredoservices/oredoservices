# Privacy Policy: Explained

This document explains the privacy policy published on the Oredo Services website, section by section, and records the changes made to it. It describes the policy as it stands in **version 1**.

The policy itself lives in two pages that say the same thing:

| Language | File | Public URL |
|---|---|---|
| English | `en/privacy.html` | https://oredoservices.github.io/oredoservices/en/privacy.html |
| Arabic | `ar/privacy.html` | https://oredoservices.github.io/oredoservices/ar/privacy.html |

Any change to the policy must be made in **both** files.

---

## 1. App names and ownership

| | Arabic | English |
|---|---|---|
| Client app | خدمات أوريدو | Oredo Services |
| Provider app | أوريدو برو | Oredo Pro |

Rules:

- Arabic pages use the Arabic names everywhere, including the logo text in the header and footer.
- English pages use the English names everywhere.
- The short name "Oredo" / "أوريدو" on its own is no longer used for the client app.

Ownership, as stated across the site:

> Oredo Services and Oredo Pro are app names, not a company. Both apps are owned by Egyptian software engineers and are not affiliated with any particular organisation or company.
>
> خدمات أوريدو وأوريدو برو اسما تطبيقين وليسا شركة. التطبيقان مملوكان لمهندسي برمجيات مصريين، وليسا تابعين لأي مؤسسة أو شركة بعينها.

No personal name, address or job title appears anywhere in the policy. Where the policy refers to whoever runs the apps, it says **"the team"** / **"فريق التطبيقين"**.

---

## 2. Page header (info box)

The box under the page title shows three items, with equal spacing between them:

| Item | English | Arabic |
|---|---|---|
| Version | `1` | رقم النسخة: `1` |
| Applies to | the **Oredo Services** app (for clients)<br>and the **Oredo Pro** app (for service providers) | تطبيق **خدمات أوريدو** (للعملاء)<br>وتطبيق **أوريدو برو** (لمقدمي الخدمة) |
| Contact | in-app Support chat,<br>or oredo.agency@gmail.com | محادثة الدعم داخل التطبيق،<br>أو oredo.agency@gmail.com |

When the policy changes, increase the version number in this box in both languages. Section 9 of the policy tells users that this number identifies the latest version.

---

## 3. The policy, section by section

### Section 1: Who this policy covers

The policy covers two kinds of users:

- **Clients:** people who use Oredo Services to request services, such as delivery, from providers.
- **Pros:** independent service providers who use Oredo Pro to receive and carry out requests.

One person can hold one client account and one pro account. The two accounts are separate, and each one's data is handled on its own.

### Section 2: Data we collect

**Account and identity data (clients and pros)**

| Data | Source | Required |
|---|---|---|
| Mobile phone number | You, verified by a one-time SMS code (OTP) | Yes |
| Full name | You | Yes |
| Email address | You | Yes |
| Gender | You | Yes |
| Date of birth | You. Used to confirm you are **16 or older** | Yes |
| Profile photo | Camera or gallery | Yes for pros, optional for clients |
| App language and notification preferences | You | Yes |
| Record of accepting the policy (version and date) | The app | Yes |

**Client data**

- Saved places: the typed address and the map location (latitude and longitude).
- Chosen service regions and the default region.
- Orders: items, store names, notes, pickup location, initial price, offers received, agreed price, status history and timestamps.
- Ratings given and received.
- Messages in order chats and in Support chat.

**Pro data**

- Service type and work regions.
- Verification documents: national ID (front and back) and criminal record certificate.
- Vehicle information, only for services that need a vehicle: type, plate number, photo of the vehicle licence.
- Verification status and review notes.
- Work activity: orders, offers, prices, completed jobs, earnings summaries, ratings.
- Messages in order chats and in Support chat.

**Collected automatically**

- Push token and app version, used to deliver notifications.
- Crash reports (Firebase Crashlytics): device model, OS version, error details.
- Usage analytics (Firebase Analytics): screens and events, used in aggregate.
- App integrity signals (Firebase App Check with Play Integrity): proof that requests come from the genuine app.

**Device permissions**

| Permission | When it is used | If refused |
|---|---|---|
| Location | Only when the user taps to detect their location, or a feature needs it. **No background tracking.** | The address can be typed manually. |
| Camera / photos | Only when the user picks or takes a photo | That photo cannot be uploaded. |
| Notifications | Order, offer, message and account alerts | No alerts. The app still works. |
| SMS code auto-fill | Android asks first, then the app reads only that one SMS | The code is typed manually. |

### Section 3: Why we use your data

| Purpose | Data used |
|---|---|
| Create and secure the account, verify the phone, keep one active session | Phone, account and session data |
| Confirm the minimum age (**16**) | Date of birth |
| Verify pros before they receive orders | Pro documents, vehicle information |
| Match clients and pros by region, manage orders and offers | Regions, places, orders, service type |
| Let the two sides of an order talk and find each other | Name, photo, phone, order location, chat |
| Show ratings | Ratings |
| Send enabled notifications | Push token, preferences, language |
| Support and dispute handling | Support chat, order history, order chat |
| Safety, fraud and abuse prevention, enforcing the Terms | Account data, activity, integrity signals |
| Fixing errors and improving the apps | Crash reports, aggregated analytics |
| Complying with Egyptian law and lawful requests | Only what the request legally requires |

**Legal bases:** consent (given when the user accepts the policy), performing the requested service, legal obligations, and legitimate interest in keeping the platform safe. These follow the Egyptian Personal Data Protection Law No. 151 of 2020.

### Section 4: Who can see your data

- **The other side of an active order:** name, photo, rating, phone number and order details, including the pickup location. Pros never see a client's other saved places. Clients never see a pro's documents.
- **The team:** only the team behind the apps, or someone the team authorises, and only when needed. Examples: reviewing pro documents, answering support requests, investigating a reported problem.
- **Service providers:** Google Firebase (Google LLC) for sign-in, database, storage, notifications, crash reporting, analytics and app integrity. Data may be stored outside Egypt.
- **Never:** data is not sold. It is not shared with advertisers or third parties for their own purposes. It goes to authorities only when Egyptian law requires it.

### Section 5: How we protect your data

- Encrypted connections (TLS) between the app and the servers.
- Encryption at rest on Google Cloud.
- Strict database and storage rules: each account reads and changes only its own private data, and documents are not readable by other users.
- Phone verification with a one-time code at sign-in.
- One active device session per account. Signing in on a new device ends the old session.
- App integrity checks block requests from modified or fake apps.
- Sensitive values on the phone are kept in encrypted storage.
- Access by the team is limited to what each task needs.
- If a breach affects user data, users and the authorities are notified as the law requires.

### Section 6: Retention and account deletion

- Data is kept while the account is active.
- **Deleting an account:** in the app, go to Account → Delete account. Deletion is blocked while an order is open.
- **Deleted automatically:** name, phone and photo from the public profile; all uploaded files; saved places (clients) or the verification record and pending offers (pros); notifications and Support chat; device tokens.
- **If the user has no other active account in either app:** the sign-in identity is also deleted (phone, email, gender, date of birth). The phone number and email can then be registered again.
- **What remains:** past orders, their chat messages and ratings. These are needed for the other party's history, accounting and disputes. They are no longer linked to the user, who appears as **"Deleted user"**. Aggregated Firebase crash and analytics data stays for the services' retention period, without names, phones or documents.

### Section 7: Your rights

Under Egyptian law, users can:

- **Access** their data. Most of it is visible in the account.
- **Correct** it in the app, or by asking Support.
- **Delete** it by deleting the account.
- **Withdraw consent** by turning off notifications or location, or by deleting the account.
- **Object** to processing, or ask about it, through Support.

Requests are answered within a reasonable time. The team may ask the user to confirm their identity first.

### Section 8: Age requirement

The apps are for people aged **16 or older**. Data from anyone under 16 is not knowingly collected, and any account found to belong to someone under 16 is deleted.

### Section 9: Changes to this policy

New versions are shown in the app. Significant changes require the user to accept again. The **version number** at the top of the page identifies the latest version.

### Section 10: Contact

In-app Support chat, or **oredo.agency@gmail.com**.

---

## 4. Change log

All changes below were made in both the Arabic and English pages unless noted.

| # | Change | Before | After |
|---|---|---|---|
| 1 | Removed the owner/operator item from the header box | "Owner and operator: Ahmed Habib, software engineer, Shebin El Qanater, Qalyubia, Egypt" | Removed |
| 2 | Renamed the client app | Oredo Service / أوريدو | **Oredo Services / خدمات أوريدو** |
| 3 | Renamed the provider app | Oredo Service Pro | **Oredo Pro / أوريدو برو** |
| 4 | "Applies to" shows each app on its own line | One line | Two lines |
| 5 | Header box layout | Four equal columns with an empty gap | Three items with equal spacing |
| 6 | Removed the intro notice box above Section 1 | App-name and ownership statement, plus the consent sentence | Removed |
| 7 | Ownership statement in the footer | Owned and operated by Ahmed Habib | Owned by Egyptian software engineers, not affiliated with any organisation or company |
| 8 | "The operator" in Sections 4 and 5 | The operator / مشغّل التطبيقين | **The team / فريق التطبيقين** |
| 9 | Account deletion wording (Section 6) | "no other active Oredo account" | "no other active account in either app" |
| 10 | Minimum age | 18 | **16** (Sections 2, 3 and 8) |
| 11 | Effective date in the header box | Effective: 28 October 2026 | **Version: 1** |
| 12 | Section 9 reference | "The Effective date at the top" | "The Version number at the top" |
| 13 | Contact in the header box | Email on the same line as "Support chat" | "or" + email on its own line |
| 14 | Footer copyright | © 2026 Ahmed Habib | © 2026 Oredo Services / خدمات أوريدو |
| 15 | Footer "Made in Egypt" line | ❤ | Egyptian flag (inline SVG) |

---

## 5. Open points to review

These are not yet reflected in the policy and are worth deciding before publishing:

1. **No date on the policy.** Data-protection laws and Google Play usually expect a policy to show when it took effect. Consider showing the date next to the version, for example "Version 1 · 28 October 2026".
2. **No named data controller.** The policy names "Egyptian software engineers" without a name, address or registered entity. The email is the only contact. Google Play review may ask for a clearly identified responsible party.
3. **Consent sentence removed.** The removed intro box contained "By creating an account or using either app you confirm that you have read and agree to this Privacy Policy and these Terms". Section 3 still says consent is given when the user accepts the policy, and the app records that acceptance. A short consent line somewhere in the page would make this explicit.
4. **Age 16 and legal capacity.** The Terms (clause 2.1) still require the user to be "legally able to enter into a contract". Full legal capacity in Egypt starts at 21. Consider adding guardian consent for users under 21.
5. **Age 16 for pros.** Riding a motorcycle and holding a licence in Egypt requires being 18. Consider keeping pros at 18.
6. **App-side changes.** The age check in the apps and the Google Play age rating must match the new minimum age of 16.
