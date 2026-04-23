# 🚗 Análisis de Fraude en Siniestros Vehiculares

## Descripción
Análisis exploratorio de un dataset de 15.420 siniestros vehiculares 
para identificar patrones de fraude y comportamiento de reclamos 
entre 1994 y 1996.

## Herramientas utilizadas
- Python (pandas, matplotlib, seaborn)
- Power BI
- Jupyter Notebook

## Conclusiones principales

### 🔍 Perfil del fraude
- Solo el 5,99% de los siniestros fueron clasificados como fraude
- El 96% de los fraudes son atribuidos al titular de la póliza
- El 88,62% de los fraudes son cometidos por conductores masculinos
- Los Lunes registran la mayor cantidad de siniestros fraudulentos

### 🚘 Patrones por vehículo y póliza
- Los vehículos Sedan concentran la mayor cantidad de siniestros
- El 49% de los fraudes ocurren en pólizas de Todo Riesgo
- Los vehículos fraudulentos tienen un valor promedio 
  ligeramente superior al de los siniestros legítimos

### 📊 Insights para el negocio
- Los perfiles de mayor riesgo combinan: conductor masculino, 
  titular de póliza, vehículo Sedan con cobertura Todo Riesgo
- La detección temprana en este segmento podría reducir 
  significativamente las pérdidas por fraude

## Archivos
- `analisis_siniestros_seguros_v2.ipynb` — notebook con el análisis
- `datos_limpios_para_powerbi.csv` — dataset limpio y transformado
- Gráficos generados con matplotlib/seaborn

## Dataset
Vehicle Insurance Claim Fraud Detection — Kaggle
