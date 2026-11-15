# pre-launch-check

סקיל ל-Claude Code שבודק אתרי תדמית לעסקים בישראל לפני פרסום ולפני מסירה ללקוח. הוא בודק את האתר בפועל ומחזיר דוח ב-10 סעיפים: משפטי ופרטיות, אבטחה, עיצוב ו-UX במחשב, בטאבלט ובטלפון, ביצועים ו-Core Web Vitals, נגישות, ותוכן. כל ממצא מגיע עם הסיכון, התיקון, הסיווג (חובה חוקית / המלצה מקצועית / תלוי בנסיבות) ודרך לאמת שהתיקון עבד.

## התקנה

הכי פשוט: להדביק ל-Claude Code את השורה הזו.

```
תתקין לי את הסקיל מ-https://github.com/noameoscar29-ship-it/pre-launch-check
```

או ידנית, כפלאגין, בתוך Claude Code:

```
/plugin marketplace add noameoscar29-ship-it/pre-launch-check
/plugin install pre-launch-check@pre-launch-check
```

או כסקיל רגיל, מהטרמינל:

```bash
git clone https://github.com/noameoscar29-ship-it/pre-launch-check.git
mkdir -p ~/.claude/skills && cp -r pre-launch-check/skills/pre-launch-check ~/.claude/skills/
```

אחרי ההתקנה צריך להפעיל מחדש את Claude Code.

## שימוש

לשלוח קישור לאתר ולכתוב "תבדוק את האתר" או "pre launch check", או להפעיל ישירות עם `/pre-launch-check`.

## חשוב לדעת

הסקיל לא מחליף עורך דין ולא בדיקת נגישות של מורשה נגישות. הוא לא מבטיח שהאתר חסין מתביעות, ונועד לאתר בעיות לפני שהלקוח או הגולשים מוצאים אותן.
