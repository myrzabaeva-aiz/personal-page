MercyMed Website PRD Template

Team 6 MercyMed PRD



Make ONE Google Doc copy per team. Name it “Team 6 MercyMed PRD.” Add members as editors and share the team copy with fuming\@gmail.com. Everyone contributes; the coordinator tracks time and input. Agree on a concise working version in the first 35 minutes. Each student later uses the same team PRD for an individual AI-built site.



Team: [6]  Members: [Almaz, Aizirek, Iskender]  Date: [28 October 2026]  Version: [1.0.0]

Labels: CONFIRMED CLIENT INPUT = supported by the client sources below. TEAM DECISION = the way the team chooses to build the website, with a reason. ASSUMPTION = an idea that is not yet confirmed. OPEN QUESTION = missing information or a decision still needed.

Source key: Q = Website Client Questionnaire - MercyMed (Oct 2026), 2 pages. P = Dr Lukas’s MercyMed presentation, 19 PDF pages. Example: Q p2 means questionnaire, page 2.



# 1. Project Goal and Success

Client problem: MercyMed needs a professional and informative website that helps potential patients discover the clinic, learn about its medical services, and arrange consultations. It also needs to provide information for organizations interested in partnerships.

Website goal: Help visitors quickly understand what MercyMed offers and request an appointment easily.

Visible success: A visitor clicks “Book an appointment,” fills in name, date of birth and phone number, and the request is sent to the receptionist on WhatsApp.



# 2. Users and Main Tasks

Primary user and need: [User: Potential patients, including local residents of Bishkek, expatriates, and international visitors.] [Need: people with a medical complaint looking for a doctor.] [Evidence: Patients are the main group. Goal No. 1 is more patients (Q p1; P pp9-10).]

Priority task 1: [When a visitor wants to book an appointment, they can choose a doctor and see the time they are available.]

Priority task 2: [When a visitor wants to know what the clinic offers, they open Medical Services and see the services with a "Book" button (P pp7-8).]

Evidence reference: [Source/page: Q p1; P pp7-9.] [What it supports: Patients read about services first, then book. The client wants them to see a doctor first (client visit).]

Client context. Your team still chooses the main user: local residents, tourists and expats, plus institutional and training partners (Q p1; P pp9–10). Older and middle-aged users and low-to-medium tech comfort are client expectations, not validated research (Q pp1–2; P pp10–11).



# 3. Scope and What We Will Not Build

Scope for this version: [5 pages: Home, Medical Services, About & Team, For Organizations, Contact. 3 languages: English, Kyrgyz, Russian. A simple form that opens WhatsApp. Works on phone and computer (Q p1; P p15).]

Main call to action (CTA): [Action:Book an appointment] [Location:Top of the Home page and in the header on every page] [Reason:The client’s main goal is getting more patients to book]

What we will not build now: [1. Online booking with time slots: too complex and needs patient data (P pp16, 18). 2. Live Instagram feed: needs account access, we use a link instead (P p16). 3. Lab results page: the lab handles results, not the clinic (client visit). 4. Admin panel: the client has not decided yet (Q p2; P p16). 5. Education, Mobile Clinics and International Patients pages: no content yet, maybe later (P p15).]

Shared across team versions: [Same requirements (R1-R5), same content, same colors, same menu and button, same checks. Only the layout can be different (Q pp1-2; P pp13, 15).]

The full future website may include Home, About, Medical Services, Corporate Clients, Team, Medical Education, Mobile Clinics or Charitable Work, and Contact (Q p1; P p15). P p15 also asks about International Patients and online booking. This is not a fixed page count for the first version. Agree on a realistic scope. Ask the instructor if the scope is unclear.



# 4. Requirements and Priorities

Write 4–6 clear requirements. A requirement says what the website must do. Use Must, Should or Could for priority. An acceptance check is a simple test: write the action and expected result.

WORKED EXAMPLE — REQUIREMENT CONFIRMED BY A CLIENT SOURCE + SAMPLE PRIORITY/TEST

ID R0. Source-confirmed requirement: The website offers English, Kyrgyz and Russian (Q p2; P p11). Illustrative priority: Must. Illustrative test to adapt: switch language on two sample pages; navigation and selected language remain consistent, and text awaiting review is visibly labeled.

R1  Priority Must  Requirement The site must offer seamless language switching between English, Kyrgyz, and Russian.  Source Questionnaire p.2; Presentation p.11 Test [Switch language on any section; navigation and content update consistently without broken UI elements ]

R2  Priority [Must]  Requirement [The booking module must collect Name, Date of Birth, and Phone Number, then format a WhatsApp message to the receptionist. ]  Source [Transcript[11]; PRD Template ]  Test [Fill out mandatory fields and click submit; WhatsApp opens with pre-formatted text containing user inputs ]

R3  Priority [Must]  Requirement [The Team section must list staff (doctors, doula, nurses) with name, photo, specialty, and a concise 2-sentence bio. ]  Source [ Transcript; Questionnaire p.1 ]  Test [Navigate to Team section; inspect bios for clarity, ensuring staff names and credentials load cleanly ]

R4  Priority [Must]  Requirement [The visual design must feature a light background using brand colors (yellow-orange primary, grey secondary) and clean visual hierarchy.  ]  Source [Transcript[44]; Questionnaire p.1  ]  Test [Inspect pages on light theme; verify contrast ratios meet accessibility standards and yellow-orange/grey accents are used ]

R5 if needed  Priority [Should ]  Requirement [The Home page should feature an Instagram integration/feed block.  ]  Source [ Transcript[27][29]; Questionnaire p.2 ]  Test [Scroll to the media block; verify latest Instagram posts or link previews render correctly ]



# 5. Content Design and Languages

Essential content and approved files: [Logo, brand colors, clinic text, team list, real photos (P pp3-8; Q p1).]  Source/owner: [MercyMed owns them. We get them from the instructor.]

CONFIRMED CLIENT INPUT: professional, informative and uncluttered; light background; logo yellow-orange and grey; real photographs, not AI-generated images; website languages English, Kyrgyz and Russian (Q pp1–2; P pp11,13). The client disliked Arial in website references. Treat this as a website typography preference to respect or clarify, not a lecture-slide font rule.

Team choices: 

[Typography: TEAM DECISION — Use Manrope for headings and Noto Sans for body text, subject to checking support for Kyrgyz, Russian, and English. Avoid Arial, following the client's preference.] 

[Hierarchy/spacing: Use clear headings, short paragraphs, organized service cards, and generous whitespace. Make important information and the consultation button easy to find.] 

[How choices follow client direction: These choices support MercyMed's requested professional, informative, and uncluttered design. Use a light background, yellow-orange accents, grey text, and limited red accents following the official logo. (Q pp1–2; P p13; B p5)]

Navigation: [Labels: Home | Medical Services | About & Team | For Organizations | Contact] 

[Persistent navigation/way back: TEAM DECISION — Use a persistent header with the MercyMed logo linking to the homepage, a language selector, and a "Book a Consultation" button.] 

[Mobile behavior:Use a collapsible menu with clear labels and easily accessible buttons on smaller screens. ]

Real photos: [Source: Real clinic photographs provided or approved by MercyMed.] 

[Permission status: OPEN QUESTION — Publication permissions have not been confirmed, especially for patients, children, and mobile-clinic attendees.]

 [Fallback if unresolved: Use the official logo, simple graphics, and neutral placeholders. Do not generate fictional doctors, patients, or clinic facilities using AI.] Do not fabricate staff, patients or facilities. Permission remains open, especially for children or clinic attendees.

Languages: [Coverage: English, Kyrgyz, and Russian for main navigation and essential website content. (Q p2; P p11)] 

[Reviewer: OPEN QUESTION. Kyrgyz and Russian speakers at MercyMed. We send them a list of medical words to check (client visit).] 

[How unreviewed translation is labeled: A short note on the page: "Translation not checked yet."]

Missing content: use “[Opening hours: awaiting client confirmation]” or omit the claim. Never invent services, credentials, testimonials, contacts, hours or prices.

Future updates: [What should be easy to update? Team, prices, services, photos, promo banners (Q p2; P p16).] [Who may update it? Dr. Lukas, the receptionist and the nurse who makes videos (client visit).] CMS choice is not specified in the supplied sources (Q p2; P p16).



# 6. Quality and Safety Checks

Recommended classroom checks, not certification.

Mobile task — Target [A visitor can book from a phone in under 1 minute.] Check [Open the site on a phone. Fill the form with fake data. WhatsApp opens with the message.]

Keyboard use — Target: each control works with a keyboard and shows a visible focus mark. Check [Use only the Tab and Enter keys. Every button and field works, and you can see where you are.]

Contrast/alt text — Target: ordinary text 4.5:1; large text 3:1; meaningful images have useful alt text. Check [Check the colors in WebAIM Contrast Checker. Every photo has a short description (alt text).]

Mobile reading — Target: normal text fits the screen without horizontal scrolling. Check [Open each page on a small phone screen. No side scrolling. Text is easy to read.]

Speed test context — Target [Home page, phone view, slow internet (Chrome DevTools).] Check [Run Lighthouse. Write down the score. Make big images smaller.]

Privacy/prototype boundary — INSTRUCTOR GUIDANCE: no real patient data, live patient-data collection, real booking/payment submission or OpenEMR access. Mark any booking simulation as a prototype. Check [The form says "Prototype, no data is saved." Use a fake WhatsApp number and fake test data only.]

Easy updates — Target [A person can change a bio or a price in under 5 minutes.] Check [A teammate changes one bio and one price. The changes show on the site.]



# 7. Assumptions and Open Questions

Record unknowns instead of inventing facts. Also record risks: what could go wrong.

1 Type [OPEN QUESTION] Topic [booking] Impact [We don't know the WhatsApp number or if patients should choose a doctor.] Evidence/person needed [Dr. Lukas and the receptionist.] Temporary choice [Use a fake number. No time slots (Q p2; P p16).]

2 Type [OPEN QUESTION] Topic [contacts/hours] Impact [The Contact page is not complete without phone, address and hours.] Evidence/person needed [MercyMed receptionist or Dr. Lukas.] Temporary choice [Write "awaiting client confirmation." Address: near Ayu Grand (P p4).]

3 Type [RISK] Topic [languages] Impact [Bad translation of medical words can confuse patients (client visit).] Evidence/person needed [Kyrgyz and Russian speakers at MercyMed.] Temporary choice [Mark translations as "not checked yet."]

4 Type [RISK] Topic [photos] Impact [Using photos without permission can hurt the clinic (P p13).] Evidence/person needed [MercyMed says which photos we can use.] Temporary choice [Use the logo and approved photos only.]

5 Type [ASSUMPTION] Topic [Instagram] Impact [We think a simple Instagram link is enough for now (Q p2; P p16).] Evidence/person needed [Dr. Lukas.] Temporary choice [Add a "Follow us on Instagram" link.]

Booking is exploratory: WhatsApp and OpenEMR were discussed. Booking integration, endpoints, fields and rules are not specified or confirmed as approved in the supplied sources (Q p2; P pp16,18). Instagram priority is open (Q p2; P p16). Tunguch near Ayu Grand is approximate, not a verified street address (P p4). Exclude the Q p1 telephone; it belongs to the logo designer.



# 8. Team Review and Next Steps

Team-agreed version [1.0.0] Date [28 October 2026]. Team agreement is not client approval.

Member reviews: [Almaz / 28 Oct 2026] [Aizirek / 28 Oct 2026] [Iskender / 28 Oct 2026]

Ready check: [x] Must items have source + test. [x] Unknowns/placeholders labeled. [x] Scope achievable. [not yet, open question] Photo and translation reviewers recorded. [x] No invented medical facts or real patient data.

Change log: [1.0.0 / 28 Oct 2026 / First full team draft / Built from Q, P, brand guidelines and the client visit]

Individual next steps: each student uses the agreed PRD and permitted materials in their own AI tool; no manual coding.

[Almaz | Claude/Codex | link to be posted | Build the individual site from this PRD and post the link by Nov 4]

Aizirek | ChatGPT (Codex) | Link to be added | Build an individual AI-generated MercyMed website based on the team PRD, test its functionality and responsiveness, and submit the working link by November 4.

[Iskender | Google AI Studio | link to be posted | Build the individual site from this PRD and post the link by Nov 4]



Homework: post the individual working link to the group by Wednesday November 4, 14:10 Bishkek.



Key terms: PRD = Product Requirements Document, a shared website plan. Scope = what this version includes. Prototype = a test version. Accessibility = making content usable by people with different needs. CMS = a system for updating website content.

Atlassian requirements: https\://www\.atlassian.com/agile/product-management/requirements

W3C contrast: https\://www\.w3.org/WAI/WCAG22/Understanding/contrast-minimum.html

W3C reflow: https\://www\.w3.org/WAI/WCAG22/Understanding/reflow\.html