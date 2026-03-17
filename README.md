#Wine Data Mining Project

مشروع تنقيب بيانات Wine

---

📌 Description | الوصف

This project analyzes the Wine dataset using unsupervised learning techniques.
Although the dataset contains class labels, they were ignored as required, and only clustering methods were applied.

يهدف هذا المشروع إلى تحليل مجموعة بيانات Wine باستخدام تقنيات التعلم غير المراقب.
على الرغم من أن البيانات تحتوي على فئات (Class)، فقد تم تجاهلها حسب المطلوب، وتم استخدام طرق التجميع فقط.

---

📊 Dataset | مجموعة البيانات

- Number of samples: 178

- Number of features: 13 (after removing class column)

- All features are numerical

- عدد العينات: 178

- عدد الخصائص: 13 (بعد حذف عمود الفئة)

- جميع الخصائص رقمية

---

⚙️ Preprocessing | المعالجة المسبقة

- Removed class column

- Applied StandardScaler

- Used PCA for dimensionality reduction

- تم حذف عمود الفئة

- تم استخدام StandardScaler لتوحيد القيم

- تم استخدام PCA لتقليل الأبعاد

---

🤖 Clustering Methods | خوارزميات التجميع

- K-Means

- DBSCAN

- Hierarchical Clustering

- خوارزمية K-Means

- خوارزمية DBSCAN

- التجميع الهرمي (Hierarchical Clustering)

---

📈 Results | النتائج

- K-Means achieved the best performance

- Hierarchical clustering gave moderate results

- DBSCAN failed to form valid clusters

- حققت K-Means أفضل أداء

- أعطى التجميع الهرمي نتائج متوسطة

- فشلت DBSCAN في تكوين عناقيد مناسبة

---

📊 Evaluation | التقييم

- Silhouette Score was used to evaluate performance

- تم استخدام Silhouette Score لتقييم الأداء

---

💻 Tools Used | الأدوات المستخدمة

- Python 3.10
- pandas
- scikit-learn
- matplotlib
- seaborn

---

📎 Files Included | الملفات المرفقة

- wine_project.py

- wine.data

- Generated plots (histogram, heatmap, clustering results)

- ملف الكود: wine_project.py

- ملف البيانات: wine.data

- الصور الناتجة (Histogram, Heatmap, نتائج التجميع)

---


Your Name Here
[اكتبي اسمك هنا]
