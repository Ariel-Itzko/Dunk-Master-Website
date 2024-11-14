# יצירת קובץ README.md עם כותרת הפרויקט
echo "# Dunk-Master-Website" >> README.md

# אתחול מאגר Git בפרויקט שלך
git init

# הוספת קובץ README.md למאגר
git add README.md

# ביצוע commit ראשון עם הודעה
git commit -m "first commit"

# יצירת סניף בשם "main" אם עדיין לא קיים
git branch -M main

# הוספת מאגר מרוחק מהכתובת שלך בגיטהאב
git remote add origin https://github.com/Ariel-Itzko/Dunk-Master-Website.git

# ביצוע push למאגר המרוחק בגיטהאב
git push -u origin main

# הוספת קישור להורדת קובץ מגוגל דרייב ב-README.md
echo "[Download the large file from Google Drive](https://drive.google.com/file/d/1mKHmMaLUqitNnUhAFQ1Cn_JyDi5URoCy/view?usp=drive_link)" >> README.md

# הוספת השינויים שביצעת בקובץ README.md
git add README.md

# ביצוע commit עם הקישור לקובץ בגוגל דרייב
git commit -m "Added Google Drive link for large file"

# שליחת השינויים לגיטהאב
git push -u origin main
