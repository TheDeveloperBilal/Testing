# SODAz Website Refresh: Full Project Details

Use this file as the starting context for the project. It covers the client brief, everything we discussed, what's done, what's waiting, and how the work will happen.

---

## 1. Project at a glance

| Item | Details |
|---|---|
| Website | https://www.stopodaz.org/ |
| Brand name | SODAz (Stop Overdose Deaths Arizona) |
| Owners | Arizona Pharmacy Association (AzPA) and Maricopa County Department of Public Health |
| Client account | AzPA Naloxone (admin@azpharmacy.org) |
| Platform | Hosted website builder, almost certainly Duda, under a white label dashboard |
| Dashboard login | https://client.cmslogin.io/login |
| Project type | **Lite refresh**, not a rebuild |
| Freelance platform | Upwork |
| Site created | 28 Jun 2023 |
| Last published | 11 Feb 2026 (before this project) |

**Main goal of the site:** give clear information and drive one main action: **find free naloxone at a participating pharmacy.** Every change should support that.

---

## 2. Golden rules

1. **Never change the live site without the client's written approval.**
2. **Never click Publish** until the client approves. Publish is the only button that pushes changes live.
3. **Never delete old backup versions**, including the automatic ones.
4. **Save a named backup after each main stage.**
5. Leave the FAQ legal answers and the funding statement exactly as they are until AzPA confirms them.

---

## 3. Platform facts (Duda style builder)

- No file download or export of the site. Backups live only inside the platform.
- Backups are at **Edit Project → Settings → Site Backup**.
- Every publish creates an automatic backup (named like `www_stopodaz_org_Auto_67`).
- Restoring a version does **not** make it live. You must republish after restoring.
- Edits in the editor stay private until Publish, so the editor works as our staging area.
- The **Preview** button gives a review link for the client.
- Because the files can't be downloaded, the site **can't be copied to my own staging server.** The client was told this and agreed.

Useful Settings menu items: Favicon & Social Image, Site Domain, Google Tools, URL Redirect, Head HTML, Site Backup, Site Languages, Privacy Settings, Manage Form Responses, 404 Page, Progressive Web App (PWA).

Left editor menu: Elements, Pages, Theme, CMS, AEO/SEO, Blog, More.

Dashboard left menu: Project Overview, Performance, Contacts, Sales, Business Settings, Customer Emails, Blog.

---

## 4. Current status

| Step | Status |
|---|---|
| Brief reviewed | ✅ Done |
| Logged in to dashboard | ✅ Done |
| Named backup saved in Site Backup (`Before_Refresh_Oct2026_Original`) | ✅ Done, preview tested |
| Client told about platform limits and how I'll work | ✅ Done, client agreed |
| Questions sent to client | ✅ Sent, waiting for answers |
| Offline backup (screenshots, text, images, form responses) | ⏳ To do |
| Stage 1 content work | ⏳ Next |
| Stage 2 branding | ⏳ Waiting for client files |

---

## 5. How I work (agreed with the client)

1. Make all changes in the editor. Nothing goes live.
2. Send the client a Preview link after each stage.
3. Collect feedback and adjust.
4. Publish only after written approval.
5. Save a named backup after each stage so one part can be rolled back without losing the rest.

Suggested backup names:
- `Before_Refresh_Oct2026_Original` (done)
- `Stage1_Content_Done`
- `Stage2_Branding_Done`
- `Stage3_Images_Done`
- `Final_Approved`

---

## 6. Full scope from the client brief

### 6.1 Branding

- [ ] Replace the old logo with the new SODAz logo in the **header**
- [ ] Replace the logo in the **footer** (the client wants it placed nicely there)
- [ ] New **favicon**
- [ ] New **social share image**
- [ ] Apply brand colors to buttons, headings and section backgrounds: **burnt orange, olive green, cream** (exact codes in the logo usage guide, not received yet)
- [ ] Set colors once under **Theme** so the whole site updates consistently
- [ ] Add the tagline **"Every Pharmacy Can Be a Lifeline."** near the top of the homepage
- [ ] Match the new flyer style: **"Free Naloxone Saves Lives"** headline style, Arizona desert imagery, orange call to action button
- [ ] Add the **AzPA logo next to the Maricopa County logo** (AzPA runs the program but its logo isn't on the site)

### 6.2 Statistics

The homepage shows only 2020 to 2022 data and gives no source. Replace it with the latest ADHS figures:

| Year | Opioid overdose deaths | Note |
|---|---|---|
| 2020 | 1,886 | |
| 2021 | 2,015 | |
| 2022 | 1,915 | |
| 2023 | 1,928 | Final |
| 2024 | 1,651 | Provisional (subject to change), down 14.4% from 2023 |

- [ ] Update the numbers
- [ ] Label 2024 clearly as **Provisional**
- [ ] Add a source line with a link: *Source: Arizona Vital Statistics, death certificates, via ADHS overdose update (May 2025).*
- Note: the current site's 2020 to 2022 numbers differ slightly from these. Use the new ones.

### 6.3 Content updates

- [ ] **FAQ:** add that naloxone has been available **over the counter since September 2023** (per the ADHS 2023 report). The FAQ currently mentions only the standing order.
- [ ] **FAQ:** AzPA to confirm the standing order, Good Samaritan law and age answers are still current. **Don't edit them until confirmed.**
- [ ] **Homepage "What Is Naloxone?":** the section is only a video. Add text under it:
  > Naloxone is a life saving medicine that rapidly reverses an opioid overdose by blocking the effects of opioids in the brain.
- [ ] Add **captions** to the video if it has none (need access to the original video or its hosting account)
- [ ] **Homepage "Signs of an Overdose":** if the tiles are one image, add the same signs as real page text so screen readers can read them
- [ ] **Footer LinkedIn link:** it points to an admin URL that visitors can't open. Replace it with the public page URL (waiting for the client).
- [ ] **Resources page:** test every link and fix or report broken ones
- [ ] **Funding statement:** the footer cites American Rescue Plan Act funds. AzPA to confirm and update the wording if needed. **Don't edit until confirmed.**

Note: the "Content updates" section appears twice in the client's brief with identical text. We asked the client to confirm it's just a copy and paste mistake.

### 6.4 Images

- [ ] Make all images and visuals consistent and unified
- [ ] Find royalty free images (Unsplash, Pexels) to replace the current ones, in the Arizona desert style of the flyer
- [ ] Send the client a shortlist of 6 to 10 photos **before** using any
- [ ] Add **alt text to every image** (decorative backgrounds can stay empty)

---

## 7. Extra improvements I recommended (not in the brief)

These came from reviewing the brief. Suggest them, but don't do them without approval.

1. **Pharmacy finder check.** The site's main job is helping people find naloxone, but the brief never mentions the pharmacy finder or map. Check it works and is easy to reach on mobile. This matters more than any visual change and could become extra paid work.
2. **Basic SEO:** page titles, meta descriptions and the social share description for every page.
3. **Mobile review.** Most visitors to a public health site come on mobile. Check the main button, the statistics table and the logo at small sizes.

---

## 8. Brand assets

### Received (PNG only)

Folder: `Downloads/Sodaz Finals/Sodaz Finals/PNG`

| File | Type | Use on |
|---|---|---|
| SODAZ_Main green.png | Horizontal, dark | Cream or white backgrounds |
| SODAZ_Main.png | Horizontal, dark | Cream or white backgrounds (good for header) |
| SODAZ_Main_light1.png | Horizontal, light with orange | Dark olive or photo backgrounds |
| SODAZ_Main_light2.png | Horizontal, light | Dark backgrounds. **Looks very faint, check readability first** |
| SODAZ_Vertical.png | Stacked, dark, with tagline | Light backgrounds (good for footer) |
| SODAZ_Vertical_green.png | Stacked, dark green | Light backgrounds |
| SODAZ_Vertical_light 2.png | Stacked, light | Dark backgrounds. **Very faint** |
| SODAZ_Vertical_light1.png | Stacked, light with orange | Dark backgrounds |

The vertical logo includes "STOP OVERDOSE DEATHS ARIZONA" and the tagline "Every Pharmacy Can Be a Lifeline."

### Still needed from the client

- [ ] Logo usage guide (exact color codes)
- [ ] SVG versions of the logos
- [ ] Square icon (heart mark) for the favicon. None of the current files is square.
- [ ] AzPA logo
- [ ] The "Free Naloxone Saves Lives" flyer
- [ ] Correct public LinkedIn URL
- [ ] Access to the original "What Is Naloxone?" video or its hosting account

---

## 9. Questions sent to the client (waiting for answers)

1. Send the logo usage guide (color codes), the AzPA logo and the new flyer.
2. Does the designer have the logos as SVG files, plus a square icon for the favicon?
3. What's the correct LinkedIn link?
4. Can AzPA confirm the FAQ answers (standing order, Good Samaritan law, age) and the footer funding wording?
5. The "Content updates" section appears twice in the brief. Is it the same list?
6. Should I also check the pharmacy finder?

Questions held for later (ask when that work starts):
- Video captions: who has access to the original video?
- Is the "Provisional" label on the 2024 figure OK?
- Image style preference: real people, landscapes only, or a mix?

---

## 10. Work plan in order

### Stage 0: Offline backup (do first)
- [ ] Full page screenshots of every page, desktop and mobile (GoFullPage extension)
- [ ] Copy all page text into a Google Doc, page by page (FAQ, footer, Resources links)
- [ ] Download current images and logos
- [ ] Export form responses (Settings → Manage Form Responses) and Contacts if possible
- [ ] Record current SEO settings: page titles, meta descriptions, social share image

### Stage 1: Content (no client input needed, start now)
- [ ] Statistics section with source line and Provisional label
- [ ] Text under the "What Is Naloxone?" video
- [ ] "Signs of an Overdose" as real text (check by trying to select the tile text)
- [ ] Alt text on all images (click image → settings → alt text field)
- [ ] Test all links on the Resources page and in the footer, and list broken ones
- [ ] FAQ: add the over the counter point only
- [ ] Save backup `Stage1_Content_Done`
- [ ] Send the client a Preview link

### Stage 2: Branding (after client files arrive)
- [ ] Header and footer logos
- [ ] AzPA logo next to the Maricopa County logo
- [ ] Brand colors in Theme
- [ ] Tagline near the top of the homepage
- [ ] Flyer style headline and orange call to action button
- [ ] Favicon and social share image (Settings → Favicon & Social Image)
- [ ] Save backup `Stage2_Branding_Done`
- [ ] Send Preview link

### Stage 3: Images
- [ ] Shortlist of royalty free images sent to the client
- [ ] Replace images after approval, with alt text
- [ ] Save backup `Stage3_Images_Done`
- [ ] Send Preview link

### Stage 4: Pending client answers
- [ ] LinkedIn link
- [ ] FAQ legal answers (if AzPA changes them)
- [ ] Funding statement
- [ ] Video captions

### Stage 5: Final check and publish
- [ ] Mobile check of every page
- [ ] Click test of every link and button
- [ ] Final full preview sent to the client
- [ ] Written approval received
- [ ] Save backup `Final_Approved`
- [ ] Publish
- [ ] Check the live site after publishing

---

## 11. Message templates

### Stage 1 review message (Upwork)

> Hi [Client Name], the first round is ready for review: updated statistics with the ADHS source, new text for the naloxone video and overdose signs, alt text on all images, and the FAQ update. Here's the preview link: [link]. Nothing is live yet. Branding will follow as soon as I have the logo guide and files.

### Message already sent to the client (for reference)

> Hi [Client Name],
>
> I've reviewed the brief and logged in to the site. Here's where things stand.
>
> **Why I'm not using my own staging server:** your site is built on a hosted website builder, and it doesn't let anyone download the site files. So I can't copy the site to my server or take a backup outside the platform. That's how this kind of builder works, and nothing is wrong with the account.
>
> **How I'll keep the live site safe instead:**
> ✅ I saved a full backup of the current site inside the platform and tested it. We can restore it any time.
> ✅ Edits stay private until someone clicks Publish, so the live site won't change while I work.
> ✅ I'll send you preview links to review each update.
> ✅ I'll publish only after you approve in writing.
>
> **A few quick questions:** (the six questions in section 9)
>
> I'll start on the statistics and accessibility fixes now, so nothing waits on these answers.

---

## 12. Notes for Claude in the desktop app

- **Writing style:** simple, human sounding text. **Never use hyphens or dashes in written content** (website copy, alt text, messages to the client). They're fine only in code, file names and URL slugs.
- Act as a senior web, SEO and design professional. Be honest and point out weak spots instead of agreeing with everything.
- **Browser work:** if using the built-in browser or Claude in Chrome on the Duda editor, never click Publish, Restore or Delete without my explicit approval in that moment. Text fields, alt text, SEO fields and settings are good to automate. Drag and drop layout work is faster done by hand.
- Confirm with the client that they're OK with an AI tool using their login before running browser automation.
- Next tasks ready to start:
  1. Write alt text for every image (needs screenshots or a list of current images)
  2. Write the "Signs of an Overdose" text
  3. Build the statistics section text with the source line
  4. Write page titles and meta descriptions for every page
  5. Make the social share image (1200 × 630) and a square favicon from the logo files
