# Website Update Guide: Plumbing, Electricity and Cleaning

This guide lists every change the website needs so it matches the apps after the `plumbing_service` branch. It gives the exact English and Arabic text to paste.

| | |
|---|---|
| Website repo | `D:/ahmed/work/web/oredoservices` |
| Public site | https://oredoservices.github.io/oredoservices/ |
| Pages | `index.html` (root, same content as the English home), `en/index.html`, `ar/index.html`, `en/privacy.html`, `ar/privacy.html`, `en/terms.html`, `ar/terms.html` |
| Policy wording source | `docs/legal/privacy-policy.md` in this repo (section "Website text for changes 19 to 24") |
| Marketing facts | `docs/marketing/oredo-business-overview.md` in this repo |

Rules for every edit:

- Change the English and Arabic page together. When you change `en/index.html`, make the same change in the root `index.html`.
- The home pages use Egyptian Arabic. The privacy and terms pages use formal Arabic.
- Keep the privacy policy at **Version 1**. The apps are not launched yet, so changes before launch are folded into version 1.
- Use the app names exactly: **Oredo Services / خدمات أوريدو** and **Oredo Pro / أوريدو برو**. In English, the delivery pro is a **pilot**.

---

## 0. What changed in the apps

| Area | Before | Now |
|---|---|---|
| Live services | Delivery only (cleaning and plumbing "coming soon") | **Delivery, plumbing, electrical work and cleaning** |
| Plumbing and electrical requests | Not available | Choose maintenance, installation or finishing, write a description (required), add optional photos, pick a saved address. No price in the app: it is agreed face to face after the inspection |
| Cleaning requests | Not available | Choose the place (apartment, villa / duplex, office / shop, building stairs), the cleaning type and the details, who brings supplies, optional notes and photos. Price agreed after the inspection |
| Choosing a pro | Offers with prices (delivery) | Delivery keeps offers. For on-site jobs, pros apply and the client opens each pro's profile (rating, member since, and for plumbing and electrical work, a bio and previous-work photos) and chooses |
| Pro documents | National ID, criminal record, vehicle licence and plate number | National ID for every pro. Criminal record only for services that require it. Vehicle **type only** for delivery (no licence, no plate). Previous work (2 to 6 photos) for plumbing and electrical work. Cleaners need the ID only |
| Pro availability | Delivery pros share location while online | Unchanged for delivery. Plumbers, electricians and cleaners only switch Available / Unavailable, and the app never takes their location |
| Pro cancels after assignment | Order cancelled | The order goes back to the other pros automatically, never to the same pro again |
| Finding a service | Home list | Home grid with "View all services", and a services page with search |
| Notifications | "The service provider…" | Named by the job: pilot, plumber, electrician, cleaner |

---

## 1. Google Play links

Production package IDs:

| App | Google Play link |
|---|---|
| Oredo Services (client) | https://play.google.com/store/apps/details?id=com.oredo.app.client |
| Oredo Pro (pro) | https://play.google.com/store/apps/details?id=com.oredo.app.pro |

Already in place, no change needed:

- The two "Download the app on Google Play" badges in the `#download` section of `index.html`, `en/index.html` and `ar/index.html`.
- The `"url"` of both `MobileApplication` entries in the JSON-LD block of the same three pages.

To add:

- In the footer "Apps" / "التطبيقات" column of all seven pages, add two links under the existing ones. On the privacy and terms pages the in-page links (`#client`, `#pro`) do not exist, so point them to `index.html#client` and `index.html#pro` there.

English:

```html
<li><a href="https://play.google.com/store/apps/details?id=com.oredo.app.client" target="_blank" rel="noopener">Get Oredo Services on Google Play</a></li>
<li><a href="https://play.google.com/store/apps/details?id=com.oredo.app.pro" target="_blank" rel="noopener">Get Oredo Pro on Google Play</a></li>
```

Arabic:

```html
<li><a href="https://play.google.com/store/apps/details?id=com.oredo.app.client" target="_blank" rel="noopener">حمّل خدمات أوريدو من جوجل بلاي</a></li>
<li><a href="https://play.google.com/store/apps/details?id=com.oredo.app.pro" target="_blank" rel="noopener">حمّل أوريدو برو من جوجل بلاي</a></li>
```

> The links return "not found" until both apps are published on Google Play. Publish the website changes on the same day as the apps, or keep the site's current wording until then.

---

## 2. Home page (`index.html`, `en/index.html`, `ar/index.html`)

### 2.1 Head: title, description, social cards, JSON-LD

| Field | English | Arabic |
|---|---|---|
| `<title>` and `og:title` | Oredo Services: delivery, plumbing, electrical work and cleaning in Shebin El Qanater | خدمات أوريدو: توصيل وسباكة وكهرباء وتنظيف في شبين القناطر |
| `meta description` | Order from any shop at your price, or ask for a plumber, an electrician or a cleaner in Shebin El Qanater. Pros nearby respond, you choose. Get Oredo Services on Google Play. | اطلب من أي محل بسعرك، أو اطلب سباك أو فني كهرباء أو عامل نظافة في شبين القناطر. مقدمو الخدمة القريبين بيردوا عليك وإنت تختار. حمّل خدمات أوريدو من جوجل بلاي. |
| `og:description` | Delivery at your price, plus plumbers, electricians and cleaners near you. You choose who does the job. | توصيل بسعرك، وكمان سباكين وفنيين كهرباء وعمال نظافة قريبين منك. إنت اللي بتختار. |
| JSON-LD client `description` | Delivery at your price, and plumbing, electrical and cleaning requests in Shebin El Qanater. Pros nearby respond and you choose. | Same text in Arabic as `og:description` |
| JSON-LD pro `description` | Delivery, plumbing, electrical and cleaning requests in Shebin El Qanater for independent pros. Work on your own hours. | طلبات توصيل وسباكة وكهرباء وتنظيف في شبين القناطر لمقدمي الخدمة المستقلين. اشتغل في الوقت اللي يناسبك. |

Also update `og:image:alt` to the new title. The share images (`assets/images/share/oredo-service-share-*.jpg`) show delivery only. Replace them when new images are ready.

### 2.2 Hero

The hero stays focused on delivery at your price (it is the strongest message). Change only the lead so the other services appear.

- Eyebrow: keep.
- Title: keep.
- Lead, English: `Name your price, and pros nearby send offers. Say what you need from any shop and what you want to pay, compare the offers, pick one and pay cash. Need a plumber, an electrician or a cleaner? Describe the job and choose who does it.`
- Lead, Arabic: `إنت اللي بتحدد السعر، والعروض بتجيلك. قول محتاج إيه من أي محل وعايز تدفع كام، قارن العروض، اختار، وادفع كاش. محتاج سباك أو فني كهرباء أو عامل نظافة؟ اوصف الشغل واختار مين ينفذه.`

### 2.3 Promises strip

Second card ("Documents reviewed first") is no longer true for every pro: the criminal record is required only for some services.

- English: title `Documents reviewed first`, text `Every pro's documents are reviewed before their first order, including their national ID.`
- Arabic: title `المستندات بتتراجع الأول`, text `مستندات كل مقدم خدمة بتتراجع قبل أول طلب، ومنها البطاقة.`

### 2.4 Services and areas (`#services`)

- Heading, English: `Four services. Close to home.`
- Heading, Arabic: `أربع خدمات. وقريبة منك.`
- Paragraph, English: `Delivery from any shop, plus plumbers, electricians and cleaners, in Shebin El Qanater. More services and cities will follow.`
- Paragraph, Arabic: `توصيل من أي محل، وكمان سباكين وفنيين كهرباء وعمال نظافة، في شبين القناطر. وبعدها خدمات ومدن تانية.`

Service chips (remove the "Coming soon" tags from cleaning and plumbing, add electrical work):

| English | Arabic | Tag |
|---|---|---|
| Delivery | توصيل طلبات | none |
| Plumbing | سباكة | none |
| Electrical work | كهرباء | none |
| Cleaning | تنظيف | none |
| More on the way | وخدمات تانية في الطريق | keep as the last chip |

The electrical chip needs an icon. A simple lightning bolt in the same 24×24 stroke style as the others works: `<path d="M13 2 4 14h7l-1 8 9-12h-7z"/>`.

- Note under the chips, English: `All four services are live. The app only shows what is available in your area.`
- Note under the chips, Arabic: `الأربع خدمات شغالين دلوقتي، والتطبيق بيعرضلك المتاح في منطقتك بس.`

### 2.5 Client section (`#client`)

Intro paragraph:

- English: `Get anything delivered from any shop in Shebin El Qanater, or book a plumber, an electrician or a cleaner for your home, office or building.`
- Arabic: `اطلب أي حاجة من أي محل في شبين القناطر، أو اطلب سباك أو فني كهرباء أو عامل نظافة لبيتك أو مكتبك أو عمارتك.`

Feature list, replace with:

| English | Arabic |
|---|---|
| Save your places on the map once, reuse them every time | احفظ أماكنك على الخريطة مرة واحدة، واستخدمها كل مرة |
| Several shops in one delivery order | أكتر من محل في طلب توصيل واحد |
| Compare delivery offers by price and rating | قارن عروض التوصيل بالسعر والتقييم |
| See a pro's rating and previous work before you choose | شوف تقييم مقدم الخدمة وسابقة أعماله قبل ما تختار |
| Describe the job and add photos if you like | اوصف الشغل وضيف صور لو حابب |
| Chat in the app or call your pro directly | كلم مقدم الخدمة شات أو مكالمة من جوه التطبيق |
| Pay in cash, no card needed | ادفع كاش، من غير كارت |
| Rate every order to keep quality high | قيّم كل طلب عشان الجودة تفضل عالية |

Steps: keep the six existing steps for delivery, then add a short block under them titled **"Plumbing, electrical work and cleaning"** / **"السباكة والكهرباء والتنظيف"** with three steps:

| # | English | Arabic |
|---|---|---|
| 1 | **Describe the job.** Pick the type (for example maintenance, installation or finishing, or the place to clean), write what you need and add photos if you like. | **اوصف الشغل.** اختار النوع (صيانة أو تأسيس أو تشطيب، أو المكان اللي محتاج يتنضف)، واكتب اللي محتاجه، وضيف صور لو حابب. |
| 2 | **Choose your pro.** Pros in your area apply. Open each profile, check the rating and previous work, and pick one. | **اختار مقدم الخدمة.** مقدمو الخدمة في منطقتك بيتقدموا. افتح بروفايل كل واحد، شوف تقييمه وسابقة أعماله، واختار. |
| 3 | **Agree on the price in person.** The pro comes for the inspection, and you agree on the price face to face. | **اتفقوا على السعر وش لوش.** مقدم الخدمة بييجي يعاين، وتتفقوا على السعر مع بعض. |

### 2.6 Pro section (`#pro`)

Intro paragraph:

- English: `Oredo Pro brings you delivery, plumbing, electrical and cleaning requests from clients in the parts of Shebin El Qanater you choose. Work on your own hours and get paid in cash, with no commission during launch.`
- Arabic: `أوريدو برو بيوصلك طلبات توصيل وسباكة وكهرباء وتنظيف من العملاء في مناطق شبين القناطر اللي تختارها. اشتغل في الوقت اللي يناسبك، وخد فلوسك كاش، ومن غير عمولة في فترة الإطلاق.`

Feature list, change these two items:

| Old | New, English | New, Arabic |
|---|---|---|
| Accept the client's price or propose yours | Delivery: accept the client's price or propose yours. Other services: apply and agree on the price with the client | التوصيل: اقبل سعر العميل أو اقترح سعرك. باقي الخدمات: قدم على الطلب واتفق على السعر مع العميل |
| No shifts: go online whenever it suits you | No shifts: switch to available whenever it suits you | من غير شيفتات: خليك متاح في الوقت اللي يناسبك |

Add one item:

- English: `Plumbers and electricians: show your previous work to win more clients`
- Arabic: `السباك وفني الكهرباء: اعرض سابقة أعمالك وكسب عملاء أكتر`

Steps, change step 2 and step 3:

- Step 2, English: `Choose your service and areas. Pick delivery, plumbing, electrical work or cleaning, and the parts of Shebin El Qanater you want requests from.`
- Step 2, Arabic: `اختار خدمتك ومناطقك. توصيل أو سباكة أو كهرباء أو تنظيف، والمناطق اللي عايز توصلك منها طلبات في شبين القناطر.`
- Step 3, English: `Upload your documents. Your national ID (front and back) for every service. Delivery: the criminal record certificate and your vehicle type (motorcycle, tuk-tuk or bicycle). Plumbing and electrical work: 2 to 6 photos of your previous work and a short bio if you like. Cleaning: the ID is enough.`
- Step 3, Arabic: `ارفع مستنداتك. البطاقة (وش وضهر) لكل الخدمات. التوصيل: الفيش الجنائي ونوع المركبة (موتوسيكل أو توكتوك أو عجلة). السباكة والكهرباء: من 2 لـ 6 صور لسابقة أعمالك ونبذة عنك لو حابب. التنظيف: البطاقة كفاية.`

> Step 3 currently says "add your vehicle licence and plate number". The app no longer collects them, so this line must change.

Step 5 ("Send your offers"), English: `Get requests. New requests near you arrive as notifications. Delivery: accept the client's price or propose yours. Other services: apply, and the client chooses.`
Step 5, Arabic: `استقبل الطلبات. الطلبات الجديدة اللي حواليك بتوصلك إشعار. التوصيل: اقبل سعر العميل أو اقترح سعرك. باقي الخدمات: قدم على الطلب، والعميل بيختار.`

### 2.7 Trust section (`#trust`)

"Checked documents" card:

- English: `Pros can't receive orders until their documents are reviewed and approved, starting with their national ID.`
- Arabic: `مقدم الخدمة مش بيستقبل طلبات غير لما مستنداته تتراجع ويتوافق عليها، وأولها البطاقة.`

Add a fifth card:

- English: title `No order left behind`, text `If a pro cancels after being assigned, your request goes back to the other pros automatically. You don't need to order again.`
- Arabic: title `مفيش طلب بيضيع`, text `لو مقدم الخدمة ألغى بعد ما اتعين، طلبك بيرجع لمقدمي الخدمة التانيين تلقائي، ومش محتاج تطلب تاني.`

### 2.8 Download section (`#download`)

- Client card, English: `For anyone in Shebin El Qanater who wants something delivered at their price, or needs a plumber, an electrician or a cleaner.`
- Client card, Arabic: `لأي حد في شبين القناطر عايز يطلب حاجة بسعره، أو محتاج سباك أو فني كهرباء أو عامل نظافة.`
- Pro card, English: `For delivery pilots, plumbers, electricians and cleaners who want more work on their own hours.`
- Pro card, Arabic: `للطيارين والسباكين وفنيي الكهرباء وعمال النظافة اللي عايزين شغل أكتر في الوقت اللي يناسبهم.`

---

## 3. Privacy policy (`en/privacy.html`, `ar/privacy.html`)

Apply every item in **"Website text for changes 19 to 24"** in `docs/legal/privacy-policy.md`. It gives the full English and Arabic text for each bullet and table row. In short:

| Section | What to replace |
|---|---|
| 1 | Clients bullet: adds electrical work and cleaning |
| 2, Client data | The "Plumbing requests" bullet becomes "On-site job requests" covering plumbing, electrical work and cleaning, with the cleaning details and optional photos up to 6 |
| 2, Pro data | Verification documents (criminal record only where required), previous work (plumbing and electrical work), availability (plumbers, electricians and cleaners never share location), work activity (record of orders the pro cancelled) |
| 2, Device permissions | Location row and Camera / photos row |
| 3 | Two on-site job rows, a new "cancelled pros" row, and the support row (cancelling an order by the team) |
| 4 | "Pros an open request was sent to", "Clients choosing a pro", and "The team" bullets |
| 6 | "Deleted automatically" |

Keep the header box at **Version 1**.

---

## 4. Terms and conditions (`en/terms.html`, `ar/terms.html`)

The terms still describe delivery only, and clause 3.1 asks for documents the app no longer collects. Suggested replacements in English. Write the Arabic in the same formal style as the rest of the Arabic terms page.

| Clause | Current | Suggested |
|---|---|---|
| 1.1 | "…clients who need a service (such as delivery)…" | `…clients who need a service (such as delivery, plumbing, electrical work or cleaning)…` |
| 1.2 | "…not a delivery, transport or service company…" | Keep, and add "maintenance or cleaning": `…not a delivery, transport, maintenance, cleaning or service company…` |
| 3.1 | "national ID (front and back), criminal record certificate and, for services that need a vehicle, the vehicle licence and plate number" | `To receive orders, a pro must upload clear, genuine and valid documents: national ID (front and back) and any other document the chosen service requires, such as a criminal record certificate, the vehicle type for services that need a vehicle, or photos of previous work. Previous work must be the pro's own.` |
| 4.2 | Delivery obligations only (vehicle, items, receipt) | Start the list with `For delivery:` and add a second list: `For plumbing, electrical work and cleaning: arrive at the agreed address, inspect the job before agreeing on a price, do the work safely and to a professional standard, and respect the client's home or premises.` |
| 5.1 | "Give an accurate address, location and order description" | Add `including accurate photos and details for on-site jobs` |
| 5.3 | "Pay the pro the agreed price and the cost of the purchased items on delivery." | `Pay the pro the agreed price: for delivery, plus the cost of the purchased items on delivery; for other services, when the job is done.` |
| 7.1 | "agreed … through the offers in the app" | `For delivery, the price is agreed through the offers in the app. For plumbing, electrical work and cleaning, there is no price in the app: the client and the pro agree on it in person after the inspection.` |
| New | Cancellation | `A pro may cancel an assigned order before it is completed. The order then goes back to other pros, and it is not offered again to the pro who cancelled. A client may cancel an on-site job until the pro is on the way. The team may cancel an order when there is a problem, and records the reason.` |

---

## 5. Checklist

- [ ] Home head tags and JSON-LD updated in `index.html`, `en/index.html`, `ar/index.html`
- [ ] Hero lead, promises, services, client, pro, trust and download sections updated in all three home pages
- [ ] "Coming soon" removed from plumbing and cleaning; electrical work chip added
- [ ] "Vehicle licence and plate number" removed everywhere (home step 3, terms 3.1)
- [ ] Privacy policy changes 19 to 24 applied in both languages, still Version 1
- [ ] Terms clauses updated in both languages
- [ ] Google Play links added to the footer of all seven pages
- [ ] Every page checked in Arabic (right to left) and English
- [ ] Site published only when both apps are live on Google Play
