לאה ניסנוב – אתר מוכן להעלאה

קבצים חשובים:
- index-final-with-explainer.html (עמוד הבית)
- privacy.html (מדיניות פרטיות)
- lea-profile.jpg (תמונת תדמית)
- ln-logo.png (לוגו)

לפני העלאה לשרת:
1) Google Analytics 4:
   - פתחו index-final-with-explainer.html
   - החליפו G-XXXXXX במזהה GA4 (Measurement ID)

2) Meta Pixel:
   - החליפו 1234567890 במזהה ה-Pixel שלכם
   - בדקו ב-Events Manager שהאירועים PageView/Lead נקלטים

3) Google Sheets Webhook (Apps Script):
   - חפשו בקובץ: const SHEETS_ENDPOINT = '';
   - הדביקו את קישור ה-Apps Script שלכם (גישה ציבורית)
   - ודאו שהגיליון כולל עמודת כותרת עם: Timestamp, Source, Name, Phone, Email, LoanType, Message, incomeBracket, equity, idLast4

העלאה:
- העלו את כל הקבצים לאותה תיקייה בשרת/אחסון סטטי.
בהצלחה!
