# NSCLC Radiomics Clustering (k=4 optimal, KM p=0.061)
# Clustering Radiómico NSCLC (k=4 óptimo, KM p=0.061)

[![Kaggle Notebook](https://img.shields.io/badge/Kaggle-Notebook-blue)](https://www.kaggle.com/code/manuelcldg/nsclc-radiomics-k-4-km-p-0-061)

**Manuel CLDG | Pharmacist + AI MSc + Neuroimaging MSc |**

## 📊 Key Results / Resultados Clave
| Metric / Métrica | Value / Valor | Significance / Significado |
|------------------|---------------|----------------------------|
| Optimal Clustering | **k=4** | Silhouette + Elbow |
| Kaplan-Meier | **p=0.061** | **Tendencia** ⭐ |
| Cox HR | 1.06 (p=0.61) | Heterogeneity |

## 🗄️ **REQUIRED DATASETS / DATASETS REQUERIDOS**

### **1. NSCLC-Radiomics (Base)** [![Dataset](https://img.shields.io/badge/NSCLC-Radiomics-blue)](https://www.kaggle.com/datasets/umutkrdrms/nsclc-radiomics)
📁 clinical/ + radiomics_features.csv (n=420)

### **2. Radiomics NSCLC (Metadata + FAST)**
[![Dataset](https://img.shields.io/badge/Radiomics-NSCLC-orange)](https://www.kaggle.com/datasets/manuelcldg/radiomics-nsclc)
📁 phase_metadata.csv + shells_FAST_features/

### **3. Cluster k=4 Results**
[![Dataset](https://img.shields.io/badge/k=4-Results-green)](https://www.kaggle.com/datasets/manuelcldg/k4-clustering-results)
📁 clusters_k4.csv (labels finales)

## 📈 Reproducible Pipeline / Pipeline Reproducible
NSCLC → radiomics-nsclc (phase/FAST)
k=4 clustering → k4-results
KM/Cox (random_state=42)

## 🎯 Next Steps / Próximos Pasos
- Temporal validation / Validación temporal
- Feature selection + ML / Selección features + ML
- Pharma/biotech integration / Integración pharma/biotech

---

**Manuel CLDG**  
*Pharmacist + AI/Neuroimaging MSc* 
Spain |[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue)](https://www.linkedin.com/in/manuelcldg/) | [Utrera, España]

