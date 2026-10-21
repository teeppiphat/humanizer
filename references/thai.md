# Thai text (ภาษาไทย)

Read this file when the text to edit is mostly Thai. Everything in `SKILL.md` still applies. This file says how the core patterns change in Thai and adds tells that come from carrying English habits into Thai.

Most AI-written Thai is English thinking in Thai words. Models learn far more English than Thai, so their default Thai is often the literal translation of the English default: a connector before every sentence, a pronoun in every clause, passives with ถูก, verbs turned into nouns, and English commas and periods. A Thai writer leaves most of that implicit. Ask of each sentence: would a Thai writer who never read the English version write it this way?

Write the rewrite in Thai. Examples below are in Thai; the instructions are in English so they sit beside the core patterns.

## Voice in Thai

Thai marks register with words, particles, and pronouns, so pick one level for one reader. A LINE message, a Facebook post, a blog, a news report, and an official letter each have their own. Without a sample, take the level from the kind of text and keep it.

- Keep the writer's mix of Thai and English. A developer writes "deploy" and "PR", not การปรับใช้ or คำขอดึง. Do not translate terms the reader uses in English, and do not add English the writer avoids.
- Keep the writer's spelling of loanwords (อีเมล or อีเมล์) and of repeated words (ต่าง ๆ or ต่างๆ). Do not add slang, particles, or spelling mistakes to sound human.
- Keep the writer's particles and pronouns (ผม, เรา, ดิฉัน, เค้า). If the writer uses ครับ or ค่ะ, keep that gender throughout.

## How the core patterns change in Thai

- **§1 Not X but Y:** ไม่ใช่แค่...แต่ยัง..., ไม่ได้เป็นเพียง...แต่คือ..., ...มากกว่าแค่..., X ไม่ใช่...แต่คือ... Handle them the same way.
- **§2 Closers:** a standalone line such as และนี่คือ..., นี่แหละคือ..., นี่คือเหตุผลที่..., เพราะท้ายที่สุดแล้ว..., จำไว้ว่า..., บอกเลยว่า...
- **§3 Sayings:** แท้จริงแล้ว, หัวใจสำคัญคือ, สิ่งที่สำคัญที่สุดคือ, คำถามที่แท้จริงคือ, ...คือกุญแจสู่...
- **§4 Run-ups:** มาดูกันเลย, มาเริ่มกันเลย, ลองมาดูกันว่า, เคยสงสัยไหมว่า, รู้หรือไม่, and an opener about the era (ในยุคดิจิทัลที่เปลี่ยนแปลงอย่างรวดเร็ว, ในโลกปัจจุบัน) on a text that is not about the era.
- **§6 Triads:** a run of three short adjectives (สะดวก รวดเร็ว ปลอดภัย) and ทั้ง...ทั้ง...และ...
- **§7 Repeated openings:** in Thai this is usually a pronoun Thai would drop (T3) or the same connector before every sentence (T1).
- **§8 Dashes:** Thai rarely uses dashes, so the rule holds. T6 covers commas and periods.
- **§10 Hyphens:** does not apply to Thai words.
- **§11 Passive and missing subjects:** reversed. A dropped subject is normal Thai and never a tell. The tell is the passive itself (T4) and the pronoun that fills a slot Thai leaves empty (T3).
- **§12 Words:** see T2.
- **§18 Avoiding is and has:** ทำหน้าที่เป็น, ถือเป็น, นับเป็น, ถือได้ว่าเป็น where เป็น or nothing works; มีความ + adjective (T5).
- **§21 Curly quotes:** does not apply; Thai writers use both.
- **§22 Chat residue:** แน่นอนครับ!, คำถามที่ดีมากค่ะ, ต่อไปนี้คือ..., หวังว่าข้อมูลนี้จะเป็นประโยชน์, หากมีข้อสงสัยเพิ่มเติม สามารถสอบถามได้เลยนะคะ, ยินดีให้ความช่วยเหลือ
- **§23 Knowledge limits:** ข้อมูล ณ ..., จากข้อมูลที่มีอยู่, ยังไม่มีข้อมูลเปิดเผยต่อสาธารณะ, followed by a guess with คาดว่า or น่าจะ.

## Thai-specific tells

### T1. A connector before every sentence

**Watch for:** นอกจากนี้, อย่างไรก็ตาม, ดังนั้น, ทั้งนี้, ยิ่งไปกว่านั้น, ในขณะเดียวกัน, โดยรวมแล้ว, กล่าวคือ, ด้วยเหตุนี้, ในทางกลับกัน, สุดท้ายนี้, ท้ายที่สุดแล้ว
**Problem:** English essays mark every link between sentences. Thai lets the order and small words inside the sentence (ก็, เลย, จึง, แต่, แล้ว, ส่วน) carry the link. Several of these openers in one paragraph is the strongest Thai tell. Remove the connector when the order already shows the link, or replace it with a small word inside the sentence. Formal and academic Thai uses อย่างไรก็ตาม and ดังนั้น more, so keep one where a real turn or consequence needs marking.
**Before:**
> แอปนี้ใช้งานง่าย นอกจากนี้ยังรองรับหลายภาษา อย่างไรก็ตาม ผู้ใช้บางส่วนพบว่าแบตเตอรี่หมดเร็ว ดังนั้น ทีมพัฒนาจึงได้ออกอัปเดตใหม่ ทั้งนี้ ผู้ใช้ควรอัปเดตเป็นเวอร์ชันล่าสุด
**After:**
> แอปนี้ใช้ง่ายและรองรับหลายภาษา แต่ผู้ใช้บางคนพบว่าแบตเตอรี่หมดเร็ว ทีมพัฒนาจึงออกอัปเดตใหม่ ควรอัปเดตเป็นเวอร์ชันล่าสุด

### T2. Stock AI words in Thai

**Watch for:** เจาะลึก, ขับเคลื่อน, ยกระดับ, ปลดล็อก, ไร้รอยต่อ, ภูมิทัศน์, มิติ (figurative), ตอกย้ำ, สะท้อนให้เห็นถึง, เป็นเครื่องพิสูจน์, กุญแจสำคัญ, หัวใจสำคัญ, บทบาทสำคัญ, ทรงพลัง, ลงตัว, ล้ำสมัย, เปี่ยมไปด้วย, ผสมผสาน, ครอบคลุม (as praise), ตอบโจทย์, อย่างมีประสิทธิภาพ, อย่างยั่งยืน, อย่างมีนัยสำคัญ (outside statistics), ก้าวสำคัญ, หมุดหมาย, ปรากฏการณ์, น่าทึ่ง, โดดเด่น
**Problem:** These are the Thai forms of the English stock words in §12, §13, and §16 (delve, drive, elevate, unlock, seamless, landscape, underscore, testament, key, pivotal, powerful). One is ordinary; a cluster is the tell. Keep the fact and drop the praise. If nothing concrete is left, ask the user what the thing does.
**Before:**
> แอปเวอร์ชันใหม่ช่วยยกระดับประสบการณ์ผู้ใช้อย่างไร้รอยต่อ ด้วยการซิงก์ข้อมูลระหว่างมือถือและคอมพิวเตอร์ ซึ่งสะท้อนให้เห็นถึงความมุ่งมั่นของทีมในการขับเคลื่อนนวัตกรรม
**After:**
> แอปเวอร์ชันใหม่ซิงก์ข้อมูลระหว่างมือถือกับคอมพิวเตอร์ได้แล้ว

### T3. Pronouns Thai would drop

**Watch for:** มัน for things and ideas; คุณ in every sentence; เขา, เธอ, พวกเขา, ฉัน, or เรา at the start of sentence after sentence; มันเป็น...ที่จะ... (it is ... to)
**Problem:** English needs a subject in every clause. Thai drops it once the reader knows who or what. A pronoun in every sentence reads as translated, and so does a reader addressed as คุณ again and again. Drop the pronoun when the topic is clear. Repeat the name or noun when the reader could lose track.
**Before:**
> คุณสามารถตั้งค่าการแจ้งเตือนได้ คุณเพียงแค่ไปที่หน้าตั้งค่า แล้วคุณก็เลือกเวลาที่คุณต้องการ มันจะแจ้งเตือนคุณทุกวัน
**After:**
> ตั้งเวลาแจ้งเตือนได้ที่หน้าตั้งค่า เลือกเวลาที่ต้องการ แล้วจะมีแจ้งเตือนทุกวัน

### T4. Passives with ถูก and ได้รับการ

**Watch for:** ถูกออกแบบมาเพื่อ, ถูกพัฒนาขึ้น, ถูกนำมาใช้, ถูกสร้างขึ้น, ได้รับการพัฒนา, ได้รับการปรับปรุง, ได้มีการ, มีการ + verb
**Problem:** ถูก marks something done to the subject, usually something bad (ถูกขโมย, ถูกตำหนิ). An English passive translated with ถูก or ได้รับการ sounds stiff. Name the actor, or drop the marker: ระบบนี้ออกแบบมาเพื่อ... Keep ถูก for harm, and keep ได้รับการ in official text and set phrases (ได้รับการแต่งตั้ง, ได้รับการยอมรับ).
**Before:**
> ระบบนี้ถูกออกแบบมาเพื่อลดเวลาในการทำงาน และได้มีการนำมาใช้ในหลายหน่วยงาน
**After:**
> ระบบนี้ออกแบบมาเพื่อลดเวลาทำงาน และหลายหน่วยงานก็นำไปใช้แล้ว

### T5. Padding around verbs and adjectives

**Watch for:** ทำการ + verb (ทำการตรวจสอบ, ทำการติดตั้ง); มีความ + adjective (มีความสำคัญ, มีความสะดวก); สามารถ...ได้ together; การ + verb as the subject of every sentence; ในการ, เป็นสิ่งที่, เป็นอย่างมาก, ได้อย่าง + adverb, อย่างแท้จริง; ต่าง ๆ, หลากหลาย, and มากมาย after every list
**Problem:** Translating English noun phrases ("perform an inspection", "is of importance", "the use of") produces these. Use the bare verb or adjective: ตรวจสอบ, สำคัญ, ใช้ได้. Keep ทำการ in official text. Keep มีความ when a modifier follows (มีความรู้ด้านภาษี). With สามารถ...ได้, one of the two is usually enough.
**Before:**
> การใช้งานแอปนี้มีความสะดวกเป็นอย่างมาก ผู้ใช้สามารถทำการชำระเงินได้ภายในไม่กี่วินาที ซึ่งเป็นสิ่งที่มีความสำคัญสำหรับร้านค้า
**After:**
> แอปนี้ใช้สะดวกมาก จ่ายเงินได้ในไม่กี่วินาที ซึ่งสำคัญสำหรับร้านค้า

### T6. English punctuation in Thai prose

**Watch for:** a comma between Thai clauses; a period at the end of a Thai sentence; a comma before และ or หรือ in a list (A, B, และ C); semicolons; an exclamation mark on every line
**Problem:** Thai separates clauses and sentences with a space and lists items with spaces: A B และ C. A model trained on English adds commas and periods. Replace a comma or period between Thai clauses with a space, or join the clauses with a word. Never put a comma before และ in a list. Keep commas in numbers, in English passages, and in quoted titles. Some writers and many official templates do use commas; if the sample does, match it.
**Before:**
> ร้านนี้เปิดทุกวัน, มีที่จอดรถ, และรับบัตรเครดิต. อาหารอร่อย; บรรยากาศดี!
**After:**
> ร้านนี้เปิดทุกวัน มีที่จอดรถ และรับบัตรเครดิต อาหารอร่อย บรรยากาศดี

### T7. Phrases translated word for word

**Watch for:** เล่นบทบาทสำคัญ (play a key role), ในตอนท้ายของวัน (at the end of the day), เมื่อพูดถึง... (when it comes to), หนึ่งใน...ที่...ที่สุด (one of the most), ทำให้แน่ใจว่า (make sure), ใช้ประโยชน์จาก (leverage), ในแง่ของ (in terms of), มันคุ้มค่าที่จะ (it is worth), ไม่ว่าคุณจะเป็น...หรือ... (whether you are...), ทุกสิ่งที่คุณต้องรู้เกี่ยวกับ (everything you need to know about), ก้าวไปอีกขั้น (take it to the next level)
**Problem:** A Thai reader understands these, but no Thai writer reaches for them first. Use the Thai expression, or say the point plainly.
**Before:**
> เมื่อพูดถึงการออมเงิน ดอกเบี้ยทบต้นเล่นบทบาทสำคัญ และในตอนท้ายของวัน มันคือหนึ่งในเครื่องมือที่ทรงพลังที่สุด
**After:**
> เรื่องออมเงิน ดอกเบี้ยทบต้นสำคัญมาก และเป็นเครื่องมือที่ได้ผลที่สุดอย่างหนึ่ง

### T8. Register that does not fit the reader

**Watch for:** written-only words in casual text (ดังกล่าว, อนึ่ง, ทั้งนี้ทั้งนั้น, ประการแรก, ข้าพเจ้า, จึงเรียนมาเพื่อ outside a letter); one polite middle register for every kind of text; ครับ or ค่ะ on every sentence, or none at all in a chat reply; ครับ and ค่ะ in the same text; stacked softeners (นะคะ, เลยค่ะ, ด้วยนะครับ) on routine statements
**Problem:** A person picks a register for one reader. A model picks the safe, polite, written middle for everything, so a LINE message reads like a memo and a Facebook post reads like a news report. Match the register to the text and the reader (see Voice in Thai). In casual text, one particle at the end of a message or turn is typical, not one per sentence.
**Before (LINE message to a colleague):**
> เรียนคุณสมชาย ทั้งนี้ ดิฉันได้ทำการตรวจสอบเอกสารดังกล่าวเรียบร้อยแล้วค่ะ อนึ่ง หากมีข้อสงสัยประการใด สามารถสอบถามได้ตลอดเวลานะคะ
**After:**
> คุณสมชาย เช็กเอกสารแล้วนะคะ มีอะไรถามได้เลยค่ะ

### T9. One sentence that never ends

**Watch for:** three or more clauses joined by โดย, ซึ่ง, ที่, และ, เพื่อ, รวมถึง; โดยมีเป้าหมายเพื่อ; ซึ่งจะช่วยให้...สามารถ...ได้
**Problem:** Thai has no period to force a stop, so a model chains every clause into one sentence and carries over English relative clauses and -ing riders (§15). Split at the natural breaks with a space. Cut riders such as ซึ่งสะท้อนให้เห็นถึง... that add no fact.
**Before:**
> บริษัทได้เปิดตัวบริการใหม่โดยมีเป้าหมายเพื่อตอบโจทย์ความต้องการของลูกค้า ซึ่งจะช่วยให้ลูกค้าสามารถเข้าถึงบริการได้อย่างสะดวกรวดเร็วยิ่งขึ้น รวมถึงสะท้อนให้เห็นถึงความมุ่งมั่นขององค์กรในการพัฒนาอย่างยั่งยืน
**After:**
> บริษัทเปิดบริการใหม่ ลูกค้าใช้บริการได้สะดวกและเร็วขึ้น

## When not to act in Thai

Official, legal, and government Thai (ภาษาราชการ) uses ทั้งนี้, ดังกล่าว, ได้รับการ, ทำการ, and จึงเรียนมาเพื่อโปรดทราบ by convention. Leave them in that register. Academic Thai uses more connectors than casual Thai. Many Thai writers have absorbed some of these habits from translated text and corporate writing, so act on a cluster of tells, not one.

## Check the Thai draft

After the steps in `SKILL.md`, search the draft again for the tells that most often survive: T1 connectors, T6 commas and periods, T3 pronouns, T5 ทำการ and มีความ, and §1 ไม่ใช่แค่...แต่... Then read it aloud. If a Thai listener would hear a translation, rewrite the sentence from its point.
