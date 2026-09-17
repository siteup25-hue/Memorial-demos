# מחברת

תמלול הקלטות שיעורים וניהול מחברת דיגיטלית, הכל בדפדפן.

https://siteup25-hue.github.io/Memorial-demos/machberet/

האודיו לא עוזב את המכשיר. אין שרת, אין משתמשים, ואין מפתחות API. התמלול רץ
ב-Web Worker עם Whisper דרך Transformers.js, והשיעורים נשמרים ב-IndexedDB של
הדפדפן.

בתמלול הראשון יורד מודל ונשמר במטמון. מכאן הכל עובד גם בלי רשת. בבורר המודל
כדאי לבחור לפי המכשיר: בטלפון base, במחשב עם WebGPU אפשר large-v3-turbo.

הקוד: https://github.com/siteup25-hue/claude בענף
`claude/machberet-transcription-app-ea1oiy`, בתיקייה `machberet/`. התיקייה כאן
היא תוצר בנייה בלבד.
