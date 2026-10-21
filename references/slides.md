# Slide decks

Read this file when the work is a slide deck: a .pptx or Keynote file, Google Slides, exported slides, screenshots, or a slide outline. Everything in `SKILL.md` still applies to the words on each slide and in the speaker notes. For Thai or mixed Thai and English slides, also read `references/thai.md`.

A deck shows its AI origin at a glance, before anyone reads a sentence: every slide has the same shape, the titles name topics, and the slogans and numbers have nothing behind them. The default choice from `SKILL.md` works at deck scale too. A person builds each slide around one point for one audience; a model fills a template.

## Review, do not edit the file

Do not change the deck file. Read it (extract the text, or look at the slides if you only have images), then return a review the user can apply:

1. A table with one row per finding: slide number, tell, what the slide has now, and the proposed replacement text. Group rows by slide.
2. Below the table, any deck-level findings, such as the same layout on every slide or stock slides to cut.

Write proposed titles, bullets, and notes in full, ready to paste. Describe visual changes in words ("replace the handshake photo with a screenshot of the dashboard"). Never propose a number, source, name, or chart the deck or the user did not give. When a slide needs one to make its point, write the question in the proposed column instead ("Which quarter is this growth from?").

If the user gives an outline or slide text instead of a file, rewrite it directly as `SKILL.md` describes, using the tells below.

## Deck tells

### S1. Template leftovers

**Watch for:** [Company Name], [Insert chart], Lorem ipsum, Click to add title, Presenter Name, ชื่อบริษัท, a date or year from the template, a footer from another project, an empty placeholder box, "Image: diverse team collaborating" left as alt text
**Problem:** The most certain tell, and the easiest to miss in a long deck. Flag every one with its slide number. Propose the real value only when the deck or the user gives it.

### S2. Titles that name a topic

**Watch for:** Market Overview, Our Solution, Key Findings, Challenges, ภาพรวมตลาด, ผลการดำเนินงาน, and title-case slogans such as "Unlocking the Power of Data" or "ปลดล็อกศักยภาพองค์กร"
**Problem:** A topic title makes the audience work out the point. Rewrite each title as the one sentence the slide proves, using only facts on that slide. If the slide has no point, flag it for cutting or merging. Keep a topic title on a divider or agenda slide.
**Before:**
> Title: Market Overview
> Bullets: Market grew 12% in 2025 · Our revenue grew 4% · Two new competitors entered
**After:**
> Title: The market grew 12% in 2025, and we grew 4%

### S3. The same shape on every slide

**Watch for:** a title and three to five bullets of the same length on slide after slide; three cards or three columns on most slides; an icon in front of every bullet; a bold label and colon on every bullet
**Problem:** Rhythm and formatting by rule (§6, §19) at deck scale. Content has different shapes, so slides should too. Propose the shape the content has: a comparison becomes a table, a trend becomes a chart of data the deck already holds, steps become a numbered sequence, and a single point becomes one sentence with its evidence. Merge bullets that repeat each other. Report this once at deck level and list the slides it affects.

### S4. Slogans instead of claims

**Watch for:** bullets of two to four words with no fact: Driving innovation, Seamless integration, Customer-centric approach, Synergy across teams, ยกระดับประสบการณ์ลูกค้า, ขับเคลื่อนองค์กรด้วยข้อมูล, ครบจบในที่เดียว; stock words from §12 and T2
**Problem:** A slogan gives the presenter nothing to say and the audience nothing to remember. Replace it with the fact it stands for, taken from the notes or another slide. If no fact exists, propose cutting the bullet, or ask the user what it refers to.
**Before:**
> - Seamless integration
> - Enterprise-grade security
> - Scalable architecture
**After:**
> - Connects to SAP and Salesforce without custom code
> - (Ask the user: what security certification or feature backs this?)

### S5. Stock slides

**Watch for:** an Agenda slide in a deck of six slides; an Introduction slide that repeats the title slide; Key Takeaways or Summary that repeats earlier slides word for word; Challenges and Opportunities or Future Outlook with no specific content (§13); Thank You or Q&A as a slide of its own; ขอบคุณ with a stock photo
**Problem:** A model adds these because most decks have them. Keep one when it does a job: an agenda for a long talk, a summary that sets up a decision. Otherwise propose cutting it, or ending on the ask or next step the deck leads to, if the deck states one.

### S6. Numbers and charts without support

**Watch for:** round numbers with no source (50%, 3x faster, 10M users); "Studies show", "According to research", "ผลวิจัยพบว่า" with no study named; a chart without axis labels, units, or a period; a number that appears once and nowhere in the data or notes; the same figure written two different ways on two slides
**Problem:** Borrowed authority (§17) and invented precision. Flag each one. Ask for the source, period, or unit. Do not fill any of them in yourself, and do not round or restate a number in a way that changes it.

### S7. Decoration

**Watch for:** emoji in titles and bullets; stock photos of handshakes, lightbulbs, rockets, puzzle pieces, glowing brains, or people pointing at screens; purple-to-blue gradient backgrounds; glassmorphism cards; an AI-generated image with garbled text or wrong hands; Title Case On Every Heading
**Problem:** Decoration on every slide is the visual form of §19 and §20. Propose removing it, or replacing a stock image with something from the subject: a product screenshot, a real photo, a chart of the deck's own data. Propose sentence case for headings unless the brand guide says otherwise.

### S8. Speaker notes that narrate the slide

**Watch for:** "In this slide, we will discuss...", "ในสไลด์นี้เราจะมาพูดถึง...", "This slide highlights..."; notes that repeat the bullets in full sentences; notes written as an essay with §1 to §5 tells
**Problem:** Notes are what the presenter says beyond what the audience can read. Cut narration of the slide itself (§25). Keep the example, number, or story that supports the slide title. If the notes only repeat the slide, propose trimming them to one line on what to stress.

## Check the review

Before returning, check that every proposed title and bullet uses only facts from the deck or the user, and that each question for the user is in the table. Then read the proposed titles alone, in order. They should tell the deck's argument as a short paragraph.
