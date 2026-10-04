# Project: كفّوا ألسنتكم عنهم (Kuffo Alsinatakum)

Scholarly trilingual website defending figures of Islamic history who were wrongly accused, using strict verification of historical reports (isnad, jarh wa ta'dil, logical and shar'i criteria).

- Live site: https://kuffo-alsinatakum.github.io
- Hosting: GitHub Pages, published from the main branch. Anything pushed to main goes live.
- Owner: Med. He uses GitHub Desktop and is not a programmer. Explain things simply.

## Languages
- Arabic is the original and primary language (full RTL). English and Turkish are translations.
- English uses American spelling and phrasing.
- Turkish brand name: "Onlar Hakkında Dilinizi Tutun"
- Locked Turkish nav labels: Önemli Terimler / Standartlar ve Ölçütler / Şahsiyetler / Bize Ulaşın
- Locked Turkish terms: İsnad, Tadlis, Buhârî, Mâlik, el-Ka'nebî, Zeyd bin el-Hubâb, Bişr el-Ğanevî
- Every image and diagram (isnad trees, infographics) must be in the language of its page. Never place an Arabic image on an English or Turkish page. If the image for a language is missing, stop and ask Med to upload it.

## Structure
- index.html: home page
- about/index.html: "The purpose of this site" page (complete; it is the logical main page)
- terms/sanad.html: "What is the Sanad" page (complete; the model for all term pages)
- figures/index.html: list of all figures
- Each figure has a main page plus one page per accusation, e.g. figures/al-fatih.html (Sultan Mehmed al-Fatih) with figures/al-fatih-constantinople.html and figures/al-fatih-fratricide.html, and figures/baybars.html (al-Zahir Baybars) with figures/baybars-qutuz.html and figures/baybars-turanshah.html. The same files exist under en/figures/ and tr/figures/.
- images/: all images
- English pages live under en/ and Turkish pages under tr/, mirroring the Arabic folder layout (e.g. terms/sanad.html becomes en/terms/sanad.html and tr/terms/sanad.html).
- Each section, term and criterion is its own standalone HTML page. No accordions anywhere.

## Shared elements on every page
1. Top bar: site name centered in Amiri with a decorative symbol on each side and a gold shadow; real visitor counter on one side; language switcher on the other.
2. Fixed nav bar, right to left: The purpose of this site, Important terms, Standards and criteria, Figures, Contact us.
3. Verse marquee moving right to left with a golden shimmer. Separator between verses is • (round dot).
4. Breadcrumb and page title.
5. Simple footer.

## Design
- Colors: --olive: #1B3A2F; --olive-deep: #12281F; --copper: #8B5A2B; --gold: #C9A227; --parchment: #F5EFE0
- Fonts: Amiri (Arabic, primary), Lora (Latin, fallback)
- Two-column image/text layouts stack on mobile with the image above the text.

## Writing rules (all languages, all pages)
- Never use the em-dash character anywhere.
- Verse citations go in parentheses, e.g. (سورة الحجرات: ٦), never set off with a dash.
- Qur'an translations: Sahih International (English), Diyanet İşleri Başkanlığı Meali (Turkish).

## Content rules (strict)
- Never write, summarize, rephrase, or translate religious content (verses, hadith, gradings, scholarly quotes) on your own. Only insert text Med provides, exactly as given.
- No independent conclusions. Med links the evidence and draws conclusions.

## Working rules
- Do not modify the code of a section until Med explicitly says "انتهيت" (I'm done) for that section.
- Build one section or page first as a model and get Med's approval before repeating it on other files or languages.
- Work one step at a time. Before any commit, show a short plain-language summary of what changed and wait for approval.
- Never push to main without Med's explicit approval.
- After adding images, confirm the file actually exists in images/ with the exact name and letter case used in the HTML.
- Do not change the contact form (Web3Forms) setup or the visitor counter unless asked.
- If an update does not appear on the live site, check the GitHub Pages deployment status before changing code.
