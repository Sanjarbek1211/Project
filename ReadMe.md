# Mashinani O‘rganish (Machine Learning) Klassifikatsiya Loyihasi

## Loyiha haqida umumiy ma’lumot

Ushbu loyiha **universitet firewall qurilmasida yozib olingan internet trafik ma’lumotlari** asosida tarmoq paketlarining holatini aniqlashga qaratilgan.

Loyihaning asosiy maqsadi — **tarmoq trafik yozuvlari (network traffic records)** orqali paketlarga nisbatan bajarilgan **harakat turini (Action)** bashorat qilish. Ushbu harakatlar tarmoq xavfsizligi va monitoringida muhim ahamiyatga ega.
s

## 🎯 Muammo bayoni (Problem Statement)

Berilgan kiruvchi xususiyatlar (features) asosida ma’lum bir **maqsadli sinfni (target class)** bashorat qilish. Muammo **supervised classification** sifatida qaraladi.

---

## 📊 Ma’lumotlar to‘plami (Dataset)

* **Turi:** Jadval ko‘rinishidagi ma’lumotlar (CSV)
* **Target:** Kategoriyali sinf belgisi
* **Feature’lar:** Sonli va/yoki kategoriyali ustunlar
* **Bo‘linish:** Train / Test

⚠️ Xom ma’lumotlar alohida saqlanadi va **hech qachon o‘zgartirilmaydi**.

---

## 🧠 Yondashuv va metodologiya

Loyiha quyidagi ketma-ket bosqichlardan iborat:

### 1️⃣ EDA (Exploratory Data Analysis)

* Ma’lumotlar tuzilishini o‘rganish
* Yetishmayotgan qiymatlarni aniqlash
* Taqsimotlar va korrelyatsiyalarni tahlil qilish
* Class imbalance mavjudligini tekshirish

### 2️⃣ Data Preprocessing

* NaN qiymatlarni to‘ldirish yoki olib tashlash
* Kategoriyali ustunlarni kodlash (encoding)
* Feature’larni masshtablash (StandardScaler / MinMaxScaler)

### 3️⃣ Feature Selection

* Lasso yordamida feature tanlash
* Daraxtga asoslangan feature importance
* Keraksiz va takrorlanuvchi ustunlarni olib tashlash

### 4️⃣ Model o‘qitish (Training)

* Logistic Regression
* Random Forest Classifier
* Modellarni solishtirish va eng yaxshisini tanlash

### 5️⃣ Modelni baholash (Evaluation)

Quyidagi metrikalar orqali baholandi:

* Accuracy
* Precision
* Recall
* F1-score
* ROC-AUC

### 6️⃣ Modelni saqlash (Production tayyor)

* Eng yaxshi model `joblib` orqali saqlandi
* Scaler va tanlangan feature’lar ham alohida saqlandi

---

## 📈 Natijalar

* **Eng yaxshi model:** Random Forest Classifier
* **Natija:**

  * Yuqori aniqlik (Accuracy)
  * Balanslangan F1-score
  * Sinflarni yaxshi ajrata oluvchi ROC-AUC

Model overfittingga tushmasdan, yaxshi umumlashtirish qobiliyatiga ega.

---

