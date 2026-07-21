# Non-Parametric Volatility (Risk) Analysis: Gold vs. Silver Price Indices

This repository presents a non-parametric statistical analysis comparing the daily price index volatility (heterogeneity) of **Gold** and **Silver** for risk-averse investors.

## 📌 Project Overview
* **Objective:** Identify the precious metal with lower volatility (risk) at a 5% significance level ($\alpha = 0.05$).
* **Data Source:** Borsa Istanbul (BIST) Precious Metals and Diamond Market Daily Bulletin[cite: 1].
* **Sample Size:** $n_{\text{Gold}} = 20$, $n_{\text{Silver}} = 20$ (Independent two-sample analysis)[cite: 1].

## 🔬 Statistical Methodology
1. **Assumption Check (Shapiro-Wilk Normality Test):**
   * Evaluated whether daily price index series followed a normal distribution[cite: 1].
   * Results: Normality was rejected for both Gold ($p < 0.05$) and Silver ($p < 0.05$)[cite: 1].
2. **Dispersion / Volatility Test (Siegel-Tukey Test):**
   * Given that the medians were equal ($M_{\text{Gold}} = M_{\text{Silver}} = 48.5$) and the data failed normality, the **Siegel-Tukey Test** was applied to compare the scale parameters (volatility) between the two independent groups[cite: 1].

## 📊 Results & Key Takeaways
At a 95% confidence level ($\alpha = 0.05$), the test confirmed that the Gold price index exhibits a significantly more homogeneous (less volatile) distribution compared to Silver[cite: 1]. Consequently, Gold is statistically supported as a lower-risk option for conservative investors.

## 📄 Full Report (PDF)
You can review the complete mathematical derivations, hypothesis test steps, and detailed data tables in the full PDF report: [gold-vs-silver-volatility-analysis.pdf](./gold-vs-silver-volatility-analysis.pdf)

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
# Altın ve Gümüş Fiyat Endekslerinin Non-Parametrik Oynaklık (Risk) Analizi

Bu proje, finansal piyasalarda düşük riskle yatırım yapmak isteyen yatırımcılar için **Altın** ve **Gümüş** madenlerinin 20 günlük fiyat endeksi oynaklığını (heterojenliğini) istatistiksel olarak karşılaştırmaktadır.

## 📌 Proje Özeti
* **Amaç:** Riskten kaçınan yatırımcılar için en az oynaklık gösteren değerli madeni %5 önem seviyesinde tespit etmek.
* **Veri Kaynağı:** Borsa İstanbul (BIST) Kıymetli Madenler ve Taşlar Piyasası (KMKTP) Günlük Bülten Verileri.
* **Örneklem:** $n_{\text{Altın}} = 20$, $n_{\text{Gümüş}} = 20$ (Bağımsız iki grup).

## 🔬 Uygulanan İstatistiksel Yöntemler
1. **Varsayım Kontrolü (Shapiro-Wilk Normallik Testi):**
   * Altın ($p < 0.05$) ve Gümüş ($p < 0.05$) veri serilerinin her ikisinin de normal dağılıma uymadığı saptanmıştır.
2. **Homojenlik / Oynaklık Testi (Siegel-Tukey Testi):**
   * Medyan eşitliği sağlandığı için ($M_{\text{Altın}} = M_{\text{Gümüş}} = 48.5$), iki grubun değişim parametrelerini (oynaklık) karşılaştırmak adına **Siegel-Tukey Testi** uygulanmıştır.

## 📊 Sonuç ve Finansal Yorum
%95 güven düzeyinde ($a = 0.05$), Altın madeninin günlük fiyat endeksinin Gümüş'e kıyasla **daha homojen (daha az oynak/risksiz)** bir dağılım gösterdiği tespit edilmiştir. Düşük risk arayan yatırımcıların Altın madenini tercih etmesi istatistiksel olarak desteklenmektedir.

## 📄 Detaylı Rapor (PDF)
Projenin tüm matematiksel hesaplamalarını, hipotez testlerini ve tablo detaylarını içeren tam rapora [buradan (gold-vs-silver-volatility-analysis.pdf)](./gold-vs-silver-volatility-analysis.pdf) ulaşabilirsiniz.
