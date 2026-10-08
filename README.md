# Science Reading Twin (BSc)

An adaptive English language twin for first-year BSc students in Kerala. Students read **popular-science
articles from every branch of science** and answer **higher-order-thinking questions**, building English
language skills and critical thinking (not syllabus science).

## For students
1. **Reading check:** exactly 2 short diagnostic passages of about **50 words** each (one easier, one harder).
2. **Practice ladder:** everyone then starts at **60 words** and climbs **60 → 70 → 80 → 100 words**; each step is
   harder in its language *and* its questions. 80%+ moves up a step, below 50% moves down one (never below 60).
   Passages rotate through 16 branches of science (physics, chemistry, biology, botany, zoology, space, earth
   science, climate, health, genetics, AI, mathematics, energy, oceans, brain, history of science) and each one
   targets the student's weakest skill.
3. **Three HOTS questions per passage:** analysis/inference (MCQ), vocabulary in context (MCQ), and a written
   evaluate/create question. Hints, instant feedback, grammar and vocabulary scaffolds.
4. **Twin 🦉** welcomes, motivates and gives a full review with smileys after every passage.
5. **Save & quit** any time; resume later. **Try again** to redo a passage.

## Speed
- Passages are served **instantly** from the fact-checked passage bank; the student's *next* passage is written
  and fact-checked in the background while they read. A fresh passage is written on the spot only when the bank
  has nothing new, with a 45-second limit (then the nearest level from the bank is used).
- Every save goes to Google Sheets **in the background, in batches** (one request per tab every few seconds), so
  clicks never wait for Google and a whole class stays under Google's ~60-requests-a-minute limit.
- Each student's history is read once at login; after that progress is worked out in memory.
- Answers are inside forms, so choosing an option or typing never reloads the page.
- Tip: use **Fill the passage bank** on the teacher page the evening before class.

## Accuracy safeguards
- Strict rules: only well-established facts; no invented studies, experts, quotes, dates or statistics.
- Passages that mention studies, "Dr.", "researchers at", recent dates, etc. are rejected automatically.
- Every new passage is **fact-checked by a second, stronger model**; failing passages are rewritten.
- Only fact-checked passages are reused from the bank.
- Students can **🚩 report** a passage; it is never reused and appears on the teacher dashboard.
No AI system can guarantee zero errors — glance at the Bank and Flags tabs now and then.

## Google Sheet tabs (created automatically)
Summary · Roster · Logins · Passages · Attempts · Drafts · Bank · Flags

## Setup
See **BSc_Twin_Setup_Guide.docx** for the full step-by-step guide.
Secrets needed: `GEMINI_API_KEY`, `TEACHER_PASSWORD`, `SHEET_ID`, `gcp_service_account` (whole JSON key).
Students go in the Sheet's **Roster** tab (column A roll number, column B full name).
