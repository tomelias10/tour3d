# סיורים תלת־ממדיים לדירות

עמוד נחיתה + נגן סריקות 3D Gaussian Splatting. HTML סטטי, בלי build step,
בלי שרת. מתארח ב-GitHub Pages.

- `index.html` — עמוד הנחיתה (עברית, RTL)
- `viewer.html` — הנגן. ההגדרות לכל נכס נמצאות ב-`CONFIG` בראש הסקריפט.
- `assets/scene.ksplat` — סצנת הדגמה
- `assets/lib/splat-viewer.js` — three.js r160 + gaussian-splats-3d 0.4.7, שניהם MIT

## סצנת ההדגמה — ייחוס

הסצנה הנוכחית היא `room` מתוך דאטהסט המחקר
[Mip-NeRF 360](https://jonbarron.info/mipnerf360/) (Barron et al., Google Research).
היא כאן להדגמה טכנית בלבד ואינה סריקה שלנו. לדאטהסט אין רישיון מוצהר,
והוא יוחלף בסריקות מקוריות.

## רישיונות צד שלישי

ראה `assets/lib/THIRD-PARTY-LICENSES.txt`.
