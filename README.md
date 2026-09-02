# דף נחיתה — סוכן AI להמלצות וידאו

דף נחיתה בעברית (RTL), עמוד אחד, ללא תלויות. הכל בקובץ `index.html`.

## העלאה לגיטהאב + פרסום חינם (GitHub Pages)

1. צור ריפו חדש בגיטהאב (למשל `video-testimonials-agent`).
2. העלה את `index.html` ואת `README.md` לריפו (Add file → Upload files → Commit).
3. Settings → Pages → Build and deployment → Source: **Deploy from a branch**, Branch: `main` / `root` → Save.
4. אחרי דקה-שתיים הדף יהיה זמין בכתובת `https://<שם-המשתמש>.github.io/<שם-הריפו>/`.

## מה כדאי להשלים בקובץ

- **וידאו VSL** — במקום המסגרת המפוספסת בהירו, הדביקו `<iframe>` של יוטיוב/וימאו (או `<video>` עם קובץ מקומי).
- **תמונה שלי** — במקום העיגול עם הכתובית `PHOTO OMER`, הכניסו `<img src="omer.jpg" alt="עומר טובי" style="width:100%;height:100%;object-fit:cover" />`.
- **חיבור הטופס** — בסוף הקובץ יש משתנה `FORM_ENDPOINT`. הדביקו שם Webhook (Make, Zapier, Formspree וכו') והלידים יתחילו להגיע. כרגע הטופס מציג הודעת תודה בלבד.
- **מחירים** — `1,250 ₪` ו-`20$` מופיעים כטקסט בקובץ; חיפוש-והחלפה מספיק.
- **פייבל/פיקסלים** — קוד מדידה (Meta Pixel / GA4) מדביקים לפני `</head>`.
