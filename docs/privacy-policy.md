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

- **Clients:** people who use Oredo Services to request services, such as delivery, plumbing, electrical work and cleaning, from providers.
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
- On-site job requests (plumbing, electrical work and cleaning):
  - Plumbing and electrical work: the request type (maintenance, installation or finishing) and the description written by the client.
  - Cleaning: the place type (apartment, villa or duplex, office or shop, building stairs) and its details: cleaning type, number of rooms, bathrooms or floors, whether the place is furnished, its approximate area, whether the building entrance is included, and who brings the cleaning supplies. Notes are optional.
  - For all three: optional photos of the fault or the place (up to 6, depending on the service and request type), the chosen saved address, the pros who applied, status history and timestamps. These requests have no price in the app.
- Ratings given and received.
- Messages in order chats and in Support chat.

**Pro data**

- Service type and work regions.
- Verification documents: national ID (front and back) and, only for services that require it, a criminal record certificate.
- Vehicle information, only for services that need a vehicle: the vehicle type (motorcycle, tuk-tuk or bicycle). No plate number or licence photo is collected.
- Previous work, only for services that need it (such as plumbing and electrical work): 2 to 6 photos of past jobs and an optional short bio (up to 500 characters). They are reviewed by the team before clients can see them.
- Availability: whether the pro is Online / Available. Delivery pros share their location while Online. Plumbers, electricians and cleaners share only an Available / Unavailable status, never their location.
- Verification status and review notes.
- Work activity: orders, offers, prices, completed jobs, earnings summaries, ratings, and the orders a pro cancelled after being assigned (so that order is not offered to them again).
- Messages in order chats and in Support chat.

**Collected automatically**

- Push token and app version, used to deliver notifications.
- Crash reports (Firebase Crashlytics): device model, OS version, error details.
- Usage analytics (Firebase Analytics): screens and events, used in aggregate.
- App integrity signals (Firebase App Check with Play Integrity): proof that requests come from the genuine app.

**Device permissions**

| Permission | When it is used | If refused |
|---|---|---|
| Location | Clients: only when the user taps to detect their location. Delivery pros: while they are Online, the location is sent about every 2 minutes so they receive nearby orders, with a visible notification. Plumbers, electricians and cleaners: **never**. **Nothing is collected while offline.** | The address can be typed manually. A delivery pro cannot go Online. |
| Camera / photos | Only when the user picks or takes a photo, for example the profile photo, documents, on-site job request photos or previous-work photos | That photo cannot be uploaded. |
| Notifications | Order, offer, message and account alerts | No alerts. The app still works. |
| SMS code auto-fill | Android asks first, then the app reads only that one SMS | The code is typed manually. |

### Section 3: Why we use your data

| Purpose | Data used |
|---|---|
| Create and secure the account, verify the phone, keep one active session | Phone, account and session data |
| Confirm the minimum age (**16**) | Date of birth |
| Verify pros before they receive orders | Pro documents, vehicle information |
| Match clients and pros by region, manage orders and offers | Regions, places, orders, service type, availability status |
| Help clients choose a pro for an on-site job | The pro's public profile: name, photo, rating, member-since date, and the bio and previous-work photos where the service uses them |
| Give the pro a clear idea of the job before the inspection | The request type, details, description and photos |
| Avoid offering an order again to a pro who cancelled it | The list of pros who cancelled that order |
| Let the two sides of an order talk and find each other | Name, photo, phone, order location, chat |
| Show ratings | Ratings |
| Send enabled notifications | Push token, preferences, language |
| Support and dispute handling, including cancelling an order by the team | Support chat, order history, order chat, the cancellation reason |
| Safety, fraud and abuse prevention, enforcing the Terms | Account data, activity, integrity signals |
| Fixing errors and improving the apps | Crash reports, aggregated analytics |
| Complying with Egyptian law and lawful requests | Only what the request legally requires |

**Legal bases:** consent (given when the user accepts the policy), performing the requested service, legal obligations, and legitimate interest in keeping the platform safe. These follow the Egyptian Personal Data Protection Law No. 151 of 2020.

### Section 4: Who can see your data

- **The other side of an active order:** name, photo, rating, phone number and order details, including the pickup location. Pros never see a client's other saved places. Clients never see a pro's documents.
- **Pros an open request was sent to:** before a pro is assigned, the pros in the request's region who were sent it see the client's name and photo, the region, the address and the request details (for on-site jobs: the type, details, description and photos).
- **Clients choosing a pro for an on-site job:** the pro's public profile (name, photo, rating, member-since date, and the approved bio and previous-work photos where the service uses them) is visible to the client when the pro applies to their request.
- **The team:** only the team behind the apps, or someone the team authorises, and only when needed. Examples: reviewing pro documents, answering support requests, cancelling an order when there is a problem, investigating a reported problem. Every order cancellation by the team is recorded with its reason.
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
- **Deleted automatically:** name, phone, photo, bio and previous-work photos from the public profile; all uploaded files, including on-site job request photos and previous-work photos; saved places (clients) or the verification record, availability status and pending offers or applications (pros); notifications and Support chat; device tokens.
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
| 8 | "The operator" in Sections 4 and 5 | The operator / مشغل التطبيقين | **The team / فريق التطبيقين** |
| 9 | Account deletion wording (Section 6) | "no other active Oredo account" | "no other active account in either app" |
| 10 | Minimum age | 18 | **16** (Sections 2, 3 and 8) |
| 11 | Effective date in the header box | Effective: 28 October 2026 | **Version: 1** |
| 12 | Section 9 reference | "The Effective date at the top" | "The Version number at the top" |
| 13 | Contact in the header box | Email on the same line as "Support chat" | "or" + email on its own line |
| 14 | Footer copyright | © 2026 Ahmed Habib | © 2026 Oredo Services / خدمات أوريدو |
| 15 | Footer "Made in Egypt" line | ❤ | Egyptian flag (inline SVG) |
| 16 | Pro vehicle information (Section 2) | "type, plate number, photo of the vehicle licence" | **Vehicle type only** (motorcycle, tuk-tuk or bicycle). No plate number or licence photo is collected |
| 17 | Plumbing service (Sections 1, 2, 3, 4, 6) | Delivery only | Adds plumbing requests (type, description, photos), plumbers' previous work and bio, who sees them, and their deletion |
| 18 | Location permission (Section 2) | "No background tracking" | States that delivery pros share location while Online, plumbers never do, and nothing is collected while offline |
| 19 | Electrical work and cleaning (Sections 1, 2, 3, 4, 6) | Delivery and plumbing only | Adds electrical and cleaning requests, including the cleaning details, as "on-site job requests" alongside plumbing. Request photos are optional, up to 6 |
| 20 | Criminal record certificate (Section 2) | Required from every pro | Required only for services that need it |
| 21 | Previous work and availability (Section 2) | Plumbing only | Previous work applies to services that need it, such as plumbing and electrical work. Electricians and cleaners, like plumbers, share only an availability status and never their location |
| 22 | Pro cancellation record (Sections 2 and 3) | Not mentioned | The order keeps the list of pros who cancelled it after being assigned, so it is not offered to them again |
| 23 | Order cancellation by the team (Sections 3 and 4) | Not mentioned | The team can cancel an order when there is a problem. The reason is recorded |
| 24 | Public profile shown to clients (Sections 3 and 4) | Plumber only | Any pro applying to an on-site job. Bio and previous work appear only where the service uses them |

### Website text for change 16

Section 2, "Pro data" list, the vehicle bullet:

- English: `Vehicle information, only for services that need a vehicle: the vehicle type (motorcycle, tuk-tuk or bicycle). No plate number or licence photo is collected.`
- Arabic: `بيانات المركبة، للخدمات التي تحتاج مركبة فقط: نوع المركبة (موتوسيكل أو توكتوك أو دراجة). لا نجمع رقم اللوحة ولا صورة الرخصة.`

### Website text for changes 17 and 18

Several of these bullets were later replaced by changes 19 to 24. Where they differ, use the text in the next section.

Section 1, the clients bullet:

- English: `Clients: people who use Oredo Services to request services, such as delivery and plumbing, from providers.`
- Arabic: `العملاء: من يستخدمون خدمات أوريدو لطلب خدمات مثل التوصيل والسباكة من مقدمي الخدمة.`

Section 2, "Client data" list, new bullet after "Orders":

- English: `Plumbing requests: the request type (maintenance, installation or finishing), your description, photos of the fault or the place (up to 4), the chosen saved address, the plumbers who applied, status history and timestamps. Plumbing requests have no price in the app.`
- Arabic: `طلبات السباكة: نوع الطلب (صيانة أو تأسيس أو تشطيب)، والوصف الذي تكتبه، وصور العطل أو المكان (حتى 4 صور)، والعنوان المحفوظ الذي تختاره، والسباكون الذين تقدموا للطلب، وسجل الحالات والتوقيتات. طلبات السباكة ليس لها سعر داخل التطبيق.`

Section 2, "Pro data" list, two new bullets after the vehicle bullet:

- English: `Previous work, only for services that need it (plumbing): 2 to 6 photos of past jobs and an optional short bio (up to 500 characters). The team reviews them before clients can see them.`
- Arabic: `سابقة الأعمال، للخدمات التي تحتاجها فقط (السباكة): من 2 إلى 6 صور لأعمال سابقة ونبذة قصيرة اختيارية (حتى 500 حرف). يراجعها الفريق قبل أن يراها العملاء.`
- English: `Availability: whether you are Online / Available. Delivery pros share their location while Online. Plumbers share only an Available / Unavailable status, never their location.`
- Arabic: `الإتاحة: هل أنت متاح أم لا. مقدمو خدمة التوصيل يشاركون موقعهم أثناء الإتاحة فقط. السباكون يشاركون حالة متاح / غير متاح فقط، ولا يشاركون موقعهم أبدا.`

Section 2, "Device permissions" table, the Location row:

- English: `Clients: only when you tap to detect your location. Delivery pros: while Online, the location is sent about every 2 minutes so they receive nearby orders, with a visible notification. Plumbers: never. Nothing is collected while offline.`
- Arabic: `العملاء: فقط عند الضغط لتحديد الموقع. مقدمو خدمة التوصيل: أثناء الإتاحة يرسل الموقع كل دقيقتين تقريبا لتصلهم الطلبات القريبة، مع إشعار ظاهر. السباكون: أبدا. لا يجمع أي شيء أثناء عدم الإتاحة.`

Section 3, two new rows in the purposes table:

- English: `Help clients choose a plumber | The plumber's public profile: name, photo, rating, member-since date, bio and previous-work photos`
- Arabic: `مساعدة العملاء على اختيار السباك | الملف العام للسباك: الاسم والصورة والتقييم وتاريخ الانضمام والنبذة وصور سابقة الأعمال`
- English: `Give plumbers a clear idea of the job before the inspection | Plumbing request type, description and photos`
- Arabic: `إعطاء السباك فكرة واضحة عن العمل قبل المعاينة | نوع طلب السباكة ووصفه وصوره`

Section 4, two new bullets after "The other side of an active order":

- English: `Pros an open request was sent to: before a pro is assigned, the pros in the request's region who were sent it see your name and photo, the region, the address and the request details (for plumbing: the type, description and photos).`
- Arabic: `مقدمو الخدمة الذين وصلهم طلب مفتوح: قبل تعيين مقدم خدمة، يرى مقدمو الخدمة في منطقة الطلب الذين وصلهم الطلب اسمك وصورتك والمنطقة والعنوان وتفاصيل الطلب (في السباكة: النوع والوصف والصور).`
- English: `Clients choosing a plumber: a plumber's public profile (name, photo, rating, member-since date, approved bio and previous-work photos) is visible to clients when the plumber applies to their request.`
- Arabic: `العملاء عند اختيار السباك: يظهر الملف العام للسباك (الاسم والصورة والتقييم وتاريخ الانضمام والنبذة المعتمدة وصور سابقة الأعمال) للعملاء عندما يتقدم لطلبهم.`

Section 6, "Deleted automatically":

- English: `Name, phone, photo, bio and previous-work photos from the public profile; all uploaded files, including plumbing request photos and previous-work photos; saved places (clients) or the verification record, availability status and pending offers or applications (pros); notifications and Support chat; device tokens.`
- Arabic: `الاسم ورقم الهاتف والصورة والنبذة وصور سابقة الأعمال من الملف العام؛ وكل الملفات المرفوعة بما فيها صور طلبات السباكة وصور سابقة الأعمال؛ والأماكن المحفوظة (للعملاء) أو سجل التوثيق وحالة الإتاحة والعروض أو طلبات التقديم المعلقة (لمقدمي الخدمة)؛ والإشعارات ومحادثة الدعم؛ ورموز الأجهزة.`

### Website text for changes 19 to 24

These replace the matching bullets and rows on the website. Text not listed here stays as it is.

Section 1, the clients bullet:

- English: `Clients: people who use Oredo Services to request services, such as delivery, plumbing, electrical work and cleaning, from providers.`
- Arabic: `العملاء: من يستخدمون خدمات أوريدو لطلب خدمات مثل التوصيل والسباكة والكهرباء والتنظيف من مقدمي الخدمة.`

Section 2, "Client data" list, replaces the "Plumbing requests" bullet:

- English: `On-site job requests (plumbing, electrical work and cleaning): for plumbing and electrical work, the request type (maintenance, installation or finishing) and your description; for cleaning, the place type (apartment, villa or duplex, office or shop, building stairs) and its details (cleaning type, number of rooms, bathrooms or floors, whether the place is furnished, its approximate area, whether the building entrance is included, and who brings the cleaning supplies) and optional notes. For all three: optional photos of the fault or the place (up to 6, depending on the service and request type), the chosen saved address, the pros who applied, status history and timestamps. These requests have no price in the app.`
- Arabic: `طلبات الخدمات في الموقع (السباكة والكهرباء والتنظيف): في السباكة والكهرباء، نوع الطلب (صيانة أو تأسيس أو تشطيب) والوصف الذي تكتبه؛ وفي التنظيف، نوع المكان (شقة، فيلا أو دوبلكس، مكتب أو محل، سلم العمارة) وتفاصيله (نوع التنظيف، وعدد الغرف أو الحمامات أو الأدوار، وهل المكان مفروش، ومساحته التقريبية، وهل يشمل مدخل العمارة، ومن يحضر أدوات التنظيف) وملاحظات اختيارية. وفي الخدمات الثلاث: صور اختيارية للعطل أو المكان (حتى 6 صور حسب الخدمة ونوع الطلب)، والعنوان المحفوظ الذي تختاره، ومقدمو الخدمة الذين تقدموا للطلب، وسجل الحالات والتوقيتات. هذه الطلبات ليس لها سعر داخل التطبيق.`

Section 2, "Pro data" list, the verification documents bullet:

- English: `Verification documents: national ID (front and back) and, only for services that require it, a criminal record certificate.`
- Arabic: `مستندات التوثيق: بطاقة الرقم القومي (الوجه والظهر)، وصحيفة الحالة الجنائية للخدمات التي تتطلبها فقط.`

Section 2, "Pro data" list, the previous work bullet:

- English: `Previous work, only for services that need it (such as plumbing and electrical work): 2 to 6 photos of past jobs and an optional short bio (up to 500 characters). The team reviews them before clients can see them.`
- Arabic: `سابقة الأعمال، للخدمات التي تحتاجها فقط (مثل السباكة والكهرباء): من 2 إلى 6 صور لأعمال سابقة ونبذة قصيرة اختيارية (حتى 500 حرف). يراجعها الفريق قبل أن يراها العملاء.`

Section 2, "Pro data" list, the availability bullet:

- English: `Availability: whether you are Online / Available. Delivery pros share their location while Online. Plumbers, electricians and cleaners share only an Available / Unavailable status, never their location.`
- Arabic: `الإتاحة: هل أنت متاح أم لا. مقدمو خدمة التوصيل يشاركون موقعهم أثناء الإتاحة فقط. السباكون وفنيو الكهرباء وعمال النظافة يشاركون حالة متاح / غير متاح فقط، ولا يشاركون موقعهم أبدا.`

Section 2, "Pro data" list, the work activity bullet:

- English: `Work activity: orders, offers, prices, completed jobs, earnings summaries, ratings, and the orders you cancelled after being assigned (so that order is not offered to you again).`
- Arabic: `نشاط العمل: الطلبات والعروض والأسعار والمهام المكتملة وملخصات الأرباح والتقييمات، والطلبات التي ألغيتها بعد تعيينك (حتى لا يعرض عليك نفس الطلب مرة أخرى).`

Section 2, "Device permissions" table:

- Location row, English: `Clients: only when you tap to detect your location. Delivery pros: while Online, the location is sent about every 2 minutes so they receive nearby orders, with a visible notification. Plumbers, electricians and cleaners: never. Nothing is collected while offline.`
- Location row, Arabic: `العملاء: فقط عند الضغط لتحديد الموقع. مقدمو خدمة التوصيل: أثناء الإتاحة يرسل الموقع كل دقيقتين تقريبا لتصلهم الطلبات القريبة، مع إشعار ظاهر. السباكون وفنيو الكهرباء وعمال النظافة: أبدا. لا يجمع أي شيء أثناء عدم الإتاحة.`
- Camera / photos row, English: `Only when you pick or take a photo, for example the profile photo, documents, request photos or previous-work photos.`
- Camera / photos row, Arabic: `فقط عند اختيار صورة أو التقاطها، مثل الصورة الشخصية والمستندات وصور الطلبات وصور سابقة الأعمال.`

Section 3, purposes table, replaces the two plumbing rows and the support row:

- English: `Help clients choose a pro for an on-site job | The pro's public profile: name, photo, rating, member-since date, and the bio and previous-work photos where the service uses them`
- Arabic: `مساعدة العملاء على اختيار مقدم الخدمة في الخدمات في الموقع | الملف العام لمقدم الخدمة: الاسم والصورة والتقييم وتاريخ الانضمام، والنبذة وصور سابقة الأعمال في الخدمات التي تستخدمها`
- English: `Give the pro a clear idea of the job before the inspection | The request type, details, description and photos`
- Arabic: `إعطاء مقدم الخدمة فكرة واضحة عن العمل قبل المعاينة | نوع الطلب وتفاصيله ووصفه وصوره`
- English (new row): `Avoid offering an order again to a pro who cancelled it | The list of pros who cancelled that order`
- Arabic (new row): `عدم عرض الطلب مرة أخرى على مقدم خدمة ألغاه | قائمة مقدمي الخدمة الذين ألغوا هذا الطلب`
- English: `Support and dispute handling, including cancelling an order by the team | Support chat, order history, order chat, the cancellation reason`
- Arabic: `الدعم وحل الخلافات، بما في ذلك إلغاء الطلب من الفريق | محادثة الدعم وسجل الطلبات ومحادثة الطلب وسبب الإلغاء`

Section 4, three bullets:

- Pros an open request was sent to, English: `Pros an open request was sent to: before a pro is assigned, the pros in the request's region who were sent it see your name and photo, the region, the address and the request details (for on-site jobs: the type, details, description and photos).`
- Arabic: `مقدمو الخدمة الذين وصلهم طلب مفتوح: قبل تعيين مقدم خدمة، يرى مقدمو الخدمة في منطقة الطلب الذين وصلهم الطلب اسمك وصورتك والمنطقة والعنوان وتفاصيل الطلب (في الخدمات في الموقع: النوع والتفاصيل والوصف والصور).`
- Clients choosing a pro, English: `Clients choosing a pro for an on-site job: the pro's public profile (name, photo, rating, member-since date, and the approved bio and previous-work photos where the service uses them) is visible to the client when the pro applies to their request.`
- Arabic: `العملاء عند اختيار مقدم الخدمة في الخدمات في الموقع: يظهر الملف العام لمقدم الخدمة (الاسم والصورة والتقييم وتاريخ الانضمام، والنبذة المعتمدة وصور سابقة الأعمال في الخدمات التي تستخدمها) للعميل عندما يتقدم لطلبه.`
- The team, English: `The team: only the team behind the apps, or someone the team authorises, and only when needed. Examples: reviewing pro documents, answering support requests, cancelling an order when there is a problem, investigating a reported problem. Every order cancellation by the team is recorded with its reason.`
- Arabic: `الفريق: فريق التطبيقين فقط، أو من يفوضه الفريق، وعند الحاجة فقط. مثل مراجعة مستندات مقدمي الخدمة، والرد على طلبات الدعم، وإلغاء طلب عند وجود مشكلة، والتحقيق في مشكلة مبلغ عنها. كل إلغاء لطلب من الفريق يسجل مع سببه.`

Section 6, "Deleted automatically":

- English: `Name, phone, photo, bio and previous-work photos from the public profile; all uploaded files, including request photos and previous-work photos; saved places (clients) or the verification record, availability status and pending offers or applications (pros); notifications and Support chat; device tokens.`
- Arabic: `الاسم ورقم الهاتف والصورة والنبذة وصور سابقة الأعمال من الملف العام؛ وكل الملفات المرفوعة بما فيها صور الطلبات وصور سابقة الأعمال؛ والأماكن المحفوظة (للعملاء) أو سجل التوثيق وحالة الإتاحة والعروض أو طلبات التقديم المعلقة (لمقدمي الخدمة)؛ والإشعارات ومحادثة الدعم؛ ورموز الأجهزة.`

The version stays at `1` because the apps are not in production yet. Changes made before launch are folded into version 1.

---

## 5. Open points to review

These are not yet reflected in the policy and are worth deciding before publishing:

1. **No date on the policy.** Data-protection laws and Google Play usually expect a policy to show when it took effect. Consider showing the date next to the version, for example "Version 1 · 28 October 2026".
2. **No named data controller.** The policy names "Egyptian software engineers" without a name, address or registered entity. The email is the only contact. Google Play review may ask for a clearly identified responsible party.
3. **Consent sentence removed.** The removed intro box contained "By creating an account or using either app you confirm that you have read and agree to this Privacy Policy and these Terms". Section 3 still says consent is given when the user accepts the policy, and the app records that acceptance. A short consent line somewhere in the page would make this explicit.
4. **Age 16 and legal capacity.** The Terms (clause 2.1) still require the user to be "legally able to enter into a contract". Full legal capacity in Egypt starts at 21. Consider adding guardian consent for users under 21.
5. **Age 16 for pros.** Riding a motorcycle and holding a licence in Egypt requires being 18. Consider keeping pros at 18.
6. **App-side changes.** The age check in the apps and the Google Play age rating must match the new minimum age of 16.
