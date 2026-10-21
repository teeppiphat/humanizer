# Emails and work messages

Read this file when the text is an email or a message in a work chat such as Slack, Teams, or LINE. Everything in `SKILL.md` still applies. For Thai or mixed Thai and English text, also read `references/thai.md`.

A message has one reader who already shares most of the context, and it usually asks that reader to do something. A model writes it like a document for a stranger: it opens with pleasantries, rebuilds the background, formats a few lines as a report, and ends with an offer to help. The reader has to dig for the ask. §26 is the core of this file; the tells below are its common forms in messages.

Keep the writer's language mix. If the thread mixes Thai and English, keep the English terms the writer uses (deploy, deadline, PR, invoice).

## Message tells

### E1. The ask arrives last

**Watch for:** a message that restates the situation, walks through what happened, and gives the request or decision in the last line; "I wanted to reach out regarding...", "As you may know...", "เขียนมาเพื่อแจ้งให้ทราบว่า...", "ตามที่ได้คุยกันไว้..." before a routine request
**Problem:** The reader reads every line before learning what to do. Put the ask, decision, or news in the first sentence. Keep only the context the reader lacks and needs to act. When the message replies to someone, cut what they wrote or already know (§26).
**Before:**
> Hi Ploy, as you know we've been working on the Q3 report and there have been a few delays with the data from finance. I talked to Krit yesterday and he said the numbers should be ready by Thursday. Because of that, I think we'll need to move the review meeting. Would Friday at 2pm work for you?
**After:**
> Hi Ploy, can we move the Q3 review to Friday at 2pm? Finance's numbers won't be ready until Thursday.

### E2. Stock openers and sign-offs

**Watch for:** I hope this email finds you well, I hope you're doing well, I am writing to, Thank you for reaching out, Please don't hesitate to reach out, Feel free to let me know if you have any questions, Looking forward to hearing from you, Thank you for your time and consideration; หวังว่าคุณจะสบายดี, ขอบคุณที่ติดต่อมา, หากมีข้อสงสัยประการใด สามารถติดต่อได้ตลอดเวลา, ยินดีให้ความช่วยเหลือ, รบกวนด้วยนะคะ on a message that asks nothing
**Problem:** These lines wrap the content without adding to it, and a model adds them to every message whatever the relationship. A salutation and a sign-off are normal and stay (`SKILL.md`, "When not to act"). Cut the padding lines between them. Keep a thank-you that thanks for something specific.
**Before:**
> เรียนคุณวิภา
>
> หวังว่าคุณจะสบายดีนะคะ ดิฉันเขียนมาเพื่อแจ้งว่าใบแจ้งหนี้เดือนกันยายนส่งไปแล้วค่ะ หากมีข้อสงสัยประการใด สามารถติดต่อได้ตลอดเวลานะคะ ขอบคุณสำหรับเวลาของคุณค่ะ
**After:**
> เรียนคุณวิภา
>
> ส่งใบแจ้งหนี้เดือนกันยายนไปแล้วนะคะ

### E3. A short message formatted as a report

**Watch for:** headings, bold labels, or bullet lists in a message of a few lines; sections called Summary, Key points, Next steps, Action items, สรุป, ประเด็นสำคัญ in a chat reply; a closing recap ("To summarize...", "สรุปคือ...") of a message the reader just read
**Problem:** Formatting by rule (§19, §20) at message scale. A person writes a short message as sentences. Turn it into prose. Keep a list only when the reader will act on separate items: options to choose from, steps to follow, or questions to answer one by one. Cut a recap of a message under about 150 words.
**Before:**
> **Update on the launch:**
> - **Status:** On track
> - **Blocker:** Waiting on legal review
> - **Next steps:** I'll follow up with legal tomorrow
>
> To summarize, we're on track pending legal.
**After:**
> Launch is on track. We're waiting on legal's review, and I'll chase them tomorrow.

### E4. Register that does not fit the relationship

**Watch for:** formal letter language to a teammate in chat (Dear team, Kindly be informed, เรียน, ดิฉันใคร่ขอ, จึงเรียนมาเพื่อโปรดพิจารณา); corporate English in a casual channel; a reply far more formal or far longer than the message it answers; the same tone to a manager, a customer, and a friend
**Problem:** A person sets the tone by who the reader is and how the thread already sounds. A model picks one safe, polite register for everyone. Match the register of the thread, or of the message being answered. Keep formal language where the relationship or the organization calls for it: an official letter, a first contact with a customer, a message to a government office. T8 in `references/thai.md` covers Thai particles and written-only words.
**Before (reply in a team LINE group):**
> Dear team, kindly be informed that the server maintenance has been successfully completed. Should you encounter any issues, please do not hesitate to contact me.
**After:**
> Server maintenance is done. Ping me if anything looks off.

### E5. Vague subject lines and open-ended asks

**Watch for:** subject lines such as Follow-up, Quick question, Update, Checking in, เรื่องที่คุยกัน, สอบถามข้อมูล; asks such as "let me know your thoughts", "any feedback is welcome", "ช่วยดูให้หน่อย" with no question, owner, or date
**Problem:** The subject and the ask are what the reader scans. Name the topic and the decision in the subject line. State what you need, from whom, and by when. Take the date and the owner from the source or the user. If they are missing, do not invent them: ask the user, or leave the ask without a date.
**Before:**
> Subject: Follow-up
>
> Hi Nok, just following up on the proposal. Let me know your thoughts!
**After:**
> Subject: Approve the Siam Paper proposal?
>
> Hi Nok, can you approve the Siam Paper proposal, or tell me what to change?

### E6. Thanks and apologies on every line

**Watch for:** Thank you so much for your detailed email, Great question, I completely understand your concern, I sincerely apologize for any inconvenience, เราเข้าใจความรู้สึกของคุณเป็นอย่างดี, ขออภัยในความไม่สะดวกเป็นอย่างสูง; more than one thanks or apology in a short message; an apology for something that did not go wrong
**Problem:** Stock empathy reads as a template, especially in customer support, where the customer wants the fix. Keep one thanks or one apology when there is a reason for it, and make it specific. Then give the answer.
**Before:**
> ขอบคุณมากที่แจ้งปัญหาเข้ามานะคะ เราเข้าใจความรู้สึกของคุณเป็นอย่างดี และขออภัยในความไม่สะดวกเป็นอย่างสูงค่ะ สำหรับปัญหาที่เข้าระบบไม่ได้ กรุณารีเซ็ตรหัสผ่านที่หน้าเข้าสู่ระบบค่ะ ขออภัยอีกครั้งค่ะ
**After:**
> ขอโทษที่เข้าระบบไม่ได้นะคะ ลองกด "ลืมรหัสผ่าน" ที่หน้าเข้าสู่ระบบเพื่อตั้งรหัสใหม่ได้เลยค่ะ

## Check the message

Before returning the rewrite, check that every name, date, amount, link, and attachment it mentions comes from the source. A message that says "see attached" needs an attachment, and a model often adds one that does not exist. Then read the first sentence alone: the reader should know what you need from it.
