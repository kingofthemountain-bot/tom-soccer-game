# ⚽ Tom's Soccer Match

משחק כדורגל פשוט וכיף לילדים בני 6!

## 🎮 איך לשחק

### דסקטופ
- **תנועה:** חצים או WASD
- **בעיטה:** רווח (Space)
- **שחקן 2 (מולטיפלייר):** I/J/K/L לתנועה, Enter לבעיטה

### מובייל
- **תנועה:** ג'ויסטיק וירטואלי (שמאל)
- **בעיטה:** כפתור אדום (ימין)

## 🎯 מטרת המשחק
- להבקיע 3 גולים לפני היריב
- 2 דקות למשחק
- Tom (כחול) נגד CPU/שחקן 2 (אדום)

## 🚀 הרצה מקומית

```bash
# פתח index.html ישירות בדפדפן
# או הרץ שרת מקומי:
python3 -m http.server 8000
# ואז פתח: http://localhost:8000
```

## 📦 Deployment ל-Cloudflare Pages

### דרך 1: דרך ה-CLI (מומלץ)

```bash
# התקן Wrangler
npm install -g wrangler

# התחבר ל-Cloudflare
wrangler login

# Deploy!
wrangler pages deploy . --project-name=tomsoccer
```

### דרך 2: דרך הממשק (GUI)

1. היכנס ל-[Cloudflare Dashboard](https://dash.cloudflare.com)
2. לך ל-**Pages** בתפריט הצד
3. לחץ **Create a project**
4. בחר **Direct Upload**
5. גרור את התיקייה `tom-soccer-game` או העלה את `index.html`
6. שם הפרויקט: `tomsoccer`
7. לחץ **Deploy**

הדומיין יהיה: `https://tomsoccer.pages.dev`

### דומיין מותאם אישי
אם יש לך דומיין ב-Cloudflare:
1. בדף הפרויקט, לך ל-**Custom domains**
2. לחץ **Set up a custom domain**
3. הכנס את הדומיין שלך
4. Cloudflare יגדיר את ה-DNS אוטומטית

## 🎨 פיצ'רים
- ✅ Responsive (עובד על טלפון ומחשב)
- ✅ בקרי מגע למובייל
- ✅ AI פשוט ל-CPU
- ✅ מצב 2 שחקנים
- ✅ אפקטי קול
- ✅ אנימציות גול
- ✅ טיימר ו-scoring
- ✅ עיצוב ילדותי וצבעוני

## 🛠️ טכנולוגיה
- HTML5 Canvas
- Vanilla JavaScript
- CSS3
- Web Audio API
- 100% offline-capable

## 📝 הערות
- המשחק עובד בלי אינטרנט!
- אין צורך בהתקנה או dependencies
- קובץ יחיד - פשוט להעביר ולשתף

---

נבנה במיוחד לתומי! 🎉
