# הנחיות Git ו-GitHub

## מה צריך לעשות עד השיעור הבא?

### 1️⃣ לפתוח חשבון ב-GitHub
אם עדיין אין לכם חשבון, יש להירשם באתר GitHub בקישור:
🔗 https://github.com/

👈 **מה עושים?**
1. לחצו על Sign up.
2. הזינו שם משתמש, כתובת מייל, וסיסמה.
3. עקבו אחרי ההוראות לסיום ההרשמה.

### 2️⃣ להתקין את Git במחשב
כדי שנוכל לעבוד עם Git מהמחשב האישי, יש להוריד ולהתקין את התוכנה בהתאם למערכת ההפעלה שלכם:

- **מערכת הפעלה מסוג Windows**: [הורדה ל-Windows](https://git-scm.com/download/win)
- **מערכת הפעלה מסוג Mac**: [הורדה ל-Mac](https://git-scm.com/download/mac)
- **מערכת הפעלה מסוג Linux**: ניתן להתקין דרך הטרמינל עם הפקודה:
  - Ubuntu/Debian: `sudo apt install git`
  - CentOS/Fedora: `sudo yum install git`
 

    
👈 **מה עושים ב-Windows?**
1. להוריד את הקובץ מהקישור ולפתוח אותו.
2. ללחוץ Next כמה פעמים (ההגדרות כבר מתאימות).
3. ללחוץ Install ולחכות לסיום.

### 3️⃣ לבדוק שההתקנה הצליחה
📌 צריך לפתוח את הטרמינל ולהקליד פקודה פשוטה כדי לבדוק ש-Git הותקן בהצלחה.

🔹 **איך פותחים טרמינל?**
- **מערכת הפעלה מסוג Windows**: לחצו על כפתור התחל (או Windows + R), הקלידו `cmd` ולחצו Enter. נפתח חלון שחור - זה הטרמינל שלכם.
- **מערכת הפעלה מסוג Mac**: לחצו על Command (⌘) + רווח, הקלידו `Terminal` ולחצו Enter.
- **מערכת הפעלה מסוג Linux**: פשוט לחצו Ctrl + Alt + T.

🔹 עכשיו להקליד בטרמינל:
```bash
git --version
```

אם ההתקנה הצליחה, תקבלו מספר גרסה כמו: `git version 2.x.x`.

### 4️⃣ להגדיר את Git עם שם משתמש ומייל
(פעם אחת בלבד, וזה ישמור את ההגדרות לכל הפרויקטים)

📌 בטרמינל שהרגע פתחתם, הקלידו את הפקודות הבאות (עם הפרטים שלכם):

```bash
git config --global user.name "השם שלכם"
git config --global user.email "המייל שלכם"
```

לדוגמה:
```bash
git config --global user.name "Noam Norman"
git config --global user.email "noam@example.com"
```

💡 **חשוב!**
- ✅ לפתוח חשבון ב-GitHub.
- ✅ להתקין את Git.
- ✅ לבדוק שהכל עובד עם `git --version`.
- ✅ להגדיר שם משתמש ומייל.

### במידה והסתבכתם- קישורים למדריכים:
🔗 https://www.w3schools.com/git/default.asp?remote=github
🔗 https://www.youtube.com/watch?v=VtjoExU11d4&t=2s

בהצלחה ! 
