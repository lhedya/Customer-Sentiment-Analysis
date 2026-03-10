# 📊 Customer Satisfaction and Sentiment Analysis
**Ticket System Review | Data Science & Data Analyst Bootcamp - Dibimbing.id**

**Author:** Lhedya Monica Ismon

---

## 🎯 Objective
Menganalisis hasil survei pelanggan dari berbagai ticketing system 
untuk mengukur kepuasan pelanggan, menganalisis sentimen ulasan, 
dan memberikan rekomendasi strategis berbasis data.

---

## 🗃️ Dataset
| Info | Detail |
|------|--------|
| File | assignment_ticket_system_review.csv |
| Responden Valid | 787 (setelah cleaning) |
| Periode | Oktober – Desember 2024 |
| Ticket System | Zoho Desk, Zendesk, Freshdesk, Jira, ServiceNow |

---

## 📈 Key Metrics

| Metrik | Skor | Kategori |
|--------|------|----------|
| CSAT Overall | 91.2% | Excellent ✅ |
| CES (Ease of Use) | 89.5% | Sangat Mudah ✅ |
| NPS Score | 11.9 | Average ⚠️ |
| Customer Service CSAT | 67.3% | Fair ⚠️ |

---

## 💬 Distribusi Sentimen

| Sentimen | Jumlah | Persentase |
|----------|--------|------------|
| 😊 Positif | 673 | 85.51% |
| 😐 Netral | 86 | 10.93% |
| 😠 Negatif | 28 | 3.56% |

---

## 🔧 Tools & Libraries
- **Python:** Pandas, NumPy, NLTK VADER, RE (Regex)
- **Dashboard:** Microsoft Power BI
- **Notebook:** Google Colab

---

## 📋 Langkah Analisis
1. Data Cleaning & Persiapan
2. Survey Response Rate Analysis
3. Perhitungan CSAT Score
4. Perhitungan CES Score
5. Perhitungan NPS Score
6. Text Cleansing
7. Sentiment Analysis (NLTK VADER)
8. Export ke Power BI

---

## 💡 Rekomendasi Utama
- **Customer Service (67.3%)** → Pelatihan tim support + implementasi SLA
- **NPS 11.9 / 20% Detractor** → Program retensi & survei mendalam
- **85.51% ulasan Positif** → Manfaatkan Promoter untuk program referral
- **Sentimen negatif ↔ recommend rendah (6.32)** → Prioritaskan perbaikan

---

## 📁 File Structure
- `notebook/` → Google Colab (.ipynb)
- `dashboard/` → Power BI file (.pbix)
- `data/` → Raw & cleaned dataset