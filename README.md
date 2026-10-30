# BioZorb® Lawsuit Landing Page — GitHub Pages (static) version

A static (HTML + CSS only, no PHP) landing page for **Bernheim Kelley Injury Lawyers**, built on the framework of your uploaded Lerner & Rowe page (`index-4.html` / `style-4.css`) and filled with content from **biozorblawsuit.com**. Per your standing instruction, all branding and firm-information areas were converted to the sample site's firm.

## Kept from your framework, unchanged

- Page structure, classes, the MTAA CIPA block script, and your Meta Pixel (`1665132690448359`).
- Your newest form embed: `forms.mtaa.ai/f/nf_441462e043274be8bab32ea3e44ac34c`, in the overflow form card — the container hangs past the hero over the section below it, the frame scrolls internally with `overflow: auto` if the embed runs tall, and your mobile values from the framework are preserved.
- The call/text consent paragraph in the footer disclaimer.
- Footer legal links still point to your `privacy-policy.html` and `disclaimer.html` on justicehelpnow.com (your hosted legal pages from the framework). The sample's own policy links point to realjustice.com; say the word if you want these pointed there instead.

## Firm information — converted to the sample site (Bernheim Kelley)

- Title/meta and header: Bernheim Kelley Injury Lawyers (text logo, as in the recent framework pages — the framework's familyjusticenow.com logo image, awards image, and founder photos were all Lerner & Rowe branding and were removed).
- **Phone: 617-468-5342**, as the sample displays it — header ("Need Immediate Assistance?"), in the review section, and in the footer ("Call us for immediate help."). Because this sample displays a phone and the birthing-injury framework did not, the `.header-phone` CSS rule from your earlier framework versions was restored (colored to the new palette) — the only structural CSS change.
- Footer contact: Bernheim Kelley Injury Lawyers, 1212 East Broward Blvd, 3rd Floor, Fort Lauderdale, FL 33301 (the first office the sample lists). The review section also lists their office cities: Florida — Fort Lauderdale, Miami, Jacksonville, Fort Myers, Starke; Massachusetts — Boston, Plymouth; Tennessee — Nashville.
- Disclaimer: "THIS IS ATTORNEY ADVERTISING sponsored by Bernheim Kelley Injury Lawyers," plus the sample's own sentences — prior results do not guarantee a similar outcome, and no representation is made that the quality of legal services is greater than that of other lawyers.
- Copyright: © 2026 Bernheim Kelley Injury Lawyers.
- All prior-firm traces verified at zero: no Lerner & Rowe, Goldwater, or Weltchek names, numbers, addresses, or image hosts, and no birth-injury content.

## Colors

`css/style.css` is your uploaded `style-4.css` with **color values only** changed (diff-verified — every layout, spacing, and overflow rule untouched, apart from the restored `.header-phone` rule noted above), matched to the live biozorblawsuit.com palette, sampled from the rendered site on 2026-10-30. Note the live site has been redesigned since the cream/teal scheme sampled for the original October template; the current scheme is:

- Dark navy `#122a48` (their footer) for the top bar, dark section, and footer; charcoal `#1a1a1a`–`#262626` through the hero gradient (their darkened-photo hero)
- Firm green `#009a44` for kickers, headline accents, and the list checkmarks (white checks on the green circles), with light green `#8bc34a` highlights on dark backgrounds — the greens of their logo and icons
- Gold/bronze `#c2a05e` CTA buttons with white text, like their "Get Help Now" (hover `#d8bc7a`, the light end of their gold gradient)
- Rose-pink `#f6c1d3` for the "Time Is Limited to File" band — the sample's "Don't Wait to Protect Your Rights" section is rose-pink
- Light gray `#f2f2f2` page background

Colors were sampled visually from the rendered page (which uses gradients and photos), so they are close approximations rather than values read from that site's stylesheet.

## Content (from biozorblawsuit.com)

- Hero: their headline — complications after being implanted with a BioZorb tissue marker during breast-conserving surgery (lumpectomy) — with their filing-claims copy: claims on behalf of patients who suffered complications after implantation of the BioZorb™ breast tissue marker, manufactured by Hologic, Inc.; free, confidential case evaluation; no upfront cost and no fee unless we win.
- Why Clients Choose Bernheim Kelley — their qualifier up front (claims are being evaluated for patients whose complications resulted in revision surgery, removal of the BioZorb device, or other significant medical treatment; free records review, no obligation), followed by their five checkmark points: focused experience in complex medical device litigation; no fee unless we win (costs advanced); free, no-obligation case review; thorough investigation (medical records, operative reports, pathology records); personalized representation.
- The BioZorb® Lawsuit — the marker implanted during breast-conserving surgery, and the lawsuits' allegations of serious complications requiring additional treatment or corrective surgery.
- Do You Qualify / Alleged Complications — nine cards: pain, infection, device migration, erosion, delayed healing, inflammation, revision surgery, device removal, and other significant medical treatment.
- Time Is Limited to File — their statute-of-limitations copy: every state has a filing deadline, and waiting too long could prevent you from pursuing compensation.
- What We Look At — from their form: who was implanted (you or a loved one), implant year (2026 back to before 2022), complications and whether revision/removal has happened or a doctor has recommended it, the state where the surgery took place, and picking a callback time (morning, afternoon, or evening) after submitting.

## Files

```
github-biozorb-lawsuit-landing-page/
├── index.html
├── css/style.css   (your framework CSS, colors only changed + .header-phone restored)
└── README.md
```

Publish the same way as the other GitHub pages: upload to a repo keeping the structure, Settings → Pages → deploy from branch (root).
