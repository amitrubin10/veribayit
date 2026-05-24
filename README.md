<div align="center">

<img src="logo.png" alt="VeriBayit Logo" width="120">

# 🏢 VeriBayit

### מערכת SaaS לניהול ועד בית — בעברית מלאה, RTL

**[🌐 Live App](https://app.veribayit.com)** · **[👤 Contact](mailto:amitrubin60@gmail.com)**

</div>

---

## 📖 מה זה VeriBayit?

**VeriBayit** היא מערכת ענן מלאה לניהול ועד בית — גזברות, גביה, ספקים, הצבעות דיגיטליות, ארכיון מסמכים ועוד. פותחה כפרויקט אמיתי לבניין של 70 דירות בפתח תקווה, כדי להחליף ניהול ידני ב-Excel/WhatsApp במערכת מקצועית עם נתונים שמורים בענן.

### למי זה מיועד?
- **גזברי ועד בית** שמחפשים להחליף ספרי חשבונות ידניים במערכת מקצועית
- **חברי וועד** שרוצים שקיפות בגביה והצבעות דיגיטליות
- **דיירים** שרוצים לראות חיובים, להצביע ולקבל מסמכים בקלות

---

## 📸 צילומי מסך

### 📊 דשבורד ראשי
KPIs חודשיים, גרפים של הכנסות/הוצאות, באנרים חכמים, סיכום שנתי.

<img src="screenshots/DESHBOARD.png" alt="Dashboard" width="800">
<img src="screenshots/DESHBOARD 2.png" alt="Dashboard - גרפים" width="800">

### 💰 גביה מדיירים
טבלת 70 דירות עם חישוב חוב אוטומטי לפי FIFO. שורת דייר עם פירוט מלא, כפתור WhatsApp לכל דייר עם הודעת חוב מותאמת.

<img src="screenshots/GVIYA.png" alt="Collection" width="800">

### 🏪 ניהול ספקים
ניהול ספקי הבניין (חשמל / מים / ניקיון / גינון / מעליות / וכו') עם תקופות מחיר, חוב, ותחזית.

<img src="screenshots/SAPAKIM.png" alt="Suppliers" width="800">

### 💳 התאמות אשראי (Reconciliation)
התאמת הפקדות אגרגטור (Growpay/Payme) לחיובי אשראי בודדים. תמיכה ב-partial matching + fast-track לאישור batch.

<img src="screenshots/ASKAROT.png" alt="Reconciliation" width="800">

### 🏪 אגרגטורי סליקה (Aggregators)
ניהול חברות סליקת אשראי + עמלות לפי תקופה.

<img src="screenshots/AG1.png" alt="Aggregators" width="800">
<img src="screenshots/AG2.png" alt="Aggregators 2" width="800">
<img src="screenshots/AG3.png" alt="Aggregators 3" width="800">

### ⚡ חשמל וטעינה
ניהול נקודות טעינה חשמליות בחניון — דייר/אורח/ועד, חישוב חיובים אישיים.

<img src="screenshots/HASHMAL.png" alt="Electricity" width="800">

### 📊 דוחות עשירים
5 דוחות מובנים — שנתי / השוואתי / תקופתי / ספקים+תשלומים / דיירים. כולם עם **ייצוא PDF + Excel + הדפסה** בלחיצה אחת.

<img src="screenshots/DOHOT.png" alt="Reports" width="800">

### 📁 מסמכים והצבעות
ארכיון מסמכים עם תיקיות מותאמות + drag&drop + תצוגה מקדימה. מערכת הצבעות דיגיטליות לדיירים עם שיתוף בWhatsApp ותוצאות חיות.

<img src="screenshots/DOCS.png" alt="Documents & Voting" width="800">

---

## ✨ פיצ'רים מרכזיים

### 💰 ניהול פיננסי מלא
- **ייבוא Excel** — תנועות בנק / אשראי / יתרות פתיחה / דיירים — עם מיפוי עמודות ידני, חיתוך חכם, ובדיקת רצף יתרה
- **זיהוי דייר אוטומטי** — מערכת מתקדמת לזיהוי שם דייר בתיאור תנועה (תמיכה ב-compound prefixes, וריאנטים שונים של אותו שם)
- **FIFO Collection** — חישוב חוב אוטומטי לפי First-In-First-Out על תקופה
- **התאמת אשראי** (Reconciliation) — חיבור הפקדות אגרגטור לחיובים בודדים + partial matching
- **דמי ועד היסטוריים** — pricing periods לכל סוג דירה ולכל ספק

### 👥 דיירים
- 70 דירות עם פרטים מלאים (בעלים, שוכר, פרטי קשר, חניה, מחסן)
- כרטיס דירה מפורט עם 7 KPIs + 2 לשוניות (חודשית / כרטסת) + 7 עמודות פירוט
- שליחת הודעות חוב ב-WhatsApp עם תבנית מותאמת (7 placeholders)
- סימוני חודש (פטור / סגור / מוקפא)
- תשלום ידני מזומן / המחאה

### 🏪 ספקים
- ניהול ספקי הבניין עם 5 תדירויות חיוב (חודשי / דו-חודשי / רבעוני / חצי-שנתי / שנתי)
- תקופות מחיר היסטוריות (pricing periods JSONB)
- זיהוי אוטומטי של תנועות בנק לספק לפי keywords
- חוב מחושב + תחזית שנתית

### 🗳 הצבעות דיגיטליות
- יצירת הצבעה (נושא + תיאור + אפשרויות + מועד סגירה)
- **שיתוף בקליק** לקבוצת WhatsApp עם הודעה מוכנה
- עמוד הצבעה ציבורי (`/vote.html`) — דיירים מצביעים בלי login
- מניעת ballot stuffing (UNIQUE על מספר דירה)
- **תוצאות עם תמונת גרף עוגה** לשיתוף — קליק → שמירה ב-clipboard → הדבק ב-WhatsApp

### 📁 מסמכים
- ארכיון פרוטוקולים / חוזים / חשבוניות / מכתבים
- תיקיות מותאמות אישית (20 emojis + 8 צבעים)
- **Drag & Drop** מהמחשב ישירות לתיקיה
- תצוגה מקדימה ישירה (PDF / תמונות / טקסט) בלי הורדה

### 📊 דוחות מקצועיים
- **דוח שנתי** עם בורר שנה — סיכום 12 חודשים + גרף bar
- **דוח שנתי השוואתי** — עד 3 שנים זו לצד זו + גרף line
- **דוח תקופתי** — בחירת טווח תאריכים + 6 סעיפים לבחירה
- **דוח ספקים ותשלומים** — פילוח לפי ספק + גרף doughnut
- **דוח דיירים** — בחירת עמודות + ייצוא Excel/CSV
- **כל דוח ניתן לייצוא** ב-3 פורמטים: 🖨️ הדפסה · 📄 PDF · 📊 Excel
- date pickers מותאמים עם פורמט DD/MM/YYYY (flatpickr)

### 🔔 תזכורות הוועד
- תזכורות משותפות לכל חברי הוועד (לדוגמא: "מעליות לשבת", "ניקיון לפסח")
- **שעון מעורר חוזר** — יומי / שבועי / חודשי
- Browser notifications כשמגיע מועד

---

## 🛠 Tech Stack

| שכבה | טכנולוגיה |
|---|---|
| **Frontend** | HTML + Vanilla JS (ES Modules) — בלי build process |
| **Backend** | [Supabase](https://supabase.com) (PostgreSQL + Auth + RLS + Storage) |
| **Auth** | Google OAuth via Supabase |
| **Hosting** | [Vercel](https://vercel.com) (free tier) |
| **Domain** | [Cloudflare](https://cloudflare.com) DNS + SSL |
| **Charts** | [Chart.js](https://www.chartjs.org/) 4.4 |
| **Excel** | [SheetJS](https://sheetjs.com/) (XLSX parsing + export) |
| **PDF** | [html2pdf.js](https://github.com/eKoopmans/html2pdf.js) |
| **Date Pickers** | [flatpickr](https://flatpickr.js.org/) (DD/MM/YYYY) |

### 🎯 עקרונות תכנון
- **No build step** — קוד JS רץ ישירות בדפדפן (ES modules native)
- **RLS-first security** — כל הרשאה מנוהלת ב-Postgres (לא בקוד)
- **Hebrew + RTL throughout** — תמיכה מלאה בכל הממשק
- **Mobile-friendly** — responsive design (PWA בתכנון)
- **Single source of truth** — כל נתון יושב במקום אחד ב-Supabase

---

## 🏗 ארכיטקטורה

```
┌─────────────────────────────────────────────────────────────┐
│                     הלקוחות (Browser)                        │
│   ┌─────────────┐  ┌─────────────┐  ┌──────────────────┐   │
│   │  גזבר       │  │  חברי וועד  │  │  דייר            │   │
│   │  + super    │  │  (read+vote)│  │  (vote.html only)│   │
│   └──────┬──────┘  └──────┬──────┘  └────────┬─────────┘   │
└──────────┼─────────────────┼──────────────────┼─────────────┘
           │                 │                  │
           ▼                 ▼                  ▼
┌─────────────────────────────────────────────────────────────┐
│              Vercel CDN (app.veribayit.com)                  │
│              Static files: HTML + JS + CSS                   │
└──────────────────────────┬──────────────────────────────────┘
                           │
                           ▼
┌─────────────────────────────────────────────────────────────┐
│                  Supabase (Backend)                          │
│  ┌──────────────┐  ┌──────────────┐  ┌─────────────────┐   │
│  │  PostgreSQL  │  │  Auth        │  │  Storage        │   │
│  │  20+ tables  │  │  Google OAuth│  │  Documents      │   │
│  │  ~50 RLS     │  │  + sessions  │  │  + RLS policies │   │
│  └──────────────┘  └──────────────┘  └─────────────────┘   │
└─────────────────────────────────────────────────────────────┘
```

---

## 📊 סטטיסטיקה (לחודש מאי 2026)

| מטריקה | ערך |
|---|---|
| **בניינים פעילים** | 1 (הרב משורר ישעיהו 6, פתח תקווה) |
| **דירות בניהול** | 70 |
| **ספקים פעילים** | 10 |
| **תנועות בנק שיובאו** | 80+ |
| **חיובי אשראי** | 17 |
| **שורות SQL בDB** | ~50 policies + 24 migrations |
| **קבצי JS** | 28 modules |
| **שפת ממשק** | עברית (100%) |

---

## 📞 יצירת קשר

**מפתח**: עמית רובין
**אימייל**: [amitrubin60@gmail.com](mailto:amitrubin60@gmail.com)
**Live App**: [app.veribayit.com](https://app.veribayit.com) (בקרוב)

---

<div align="center">

**מעוניין/ת ביישום מערכת דומה לבניין שלכם?**

[צור קשר](mailto:amitrubin60@gmail.com) · [לאתר החי](https://app.veribayit.com)

---

*Built with ❤️ in Israel · Code is private — this is a public showcase*

</div>
