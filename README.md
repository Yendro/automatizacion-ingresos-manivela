# CRM Income Automation

Herramienta de automatización para la transformación y generación de archivos de ingresos provenientes de reportes bancarios, con el objetivo de facilitar la carga masiva en sistemas CRM.

---

## 🚀 Características

- Procesamiento de archivos Excel de distintos bancos
- Normalización de datos
- Clasificación automática mediante reglas configurables
- Generación de archivos listos para carga en CRM
- Interfaz gráfica amigable para usuarios no técnicos

---

## 🧩 Arquitectura

El proyecto sigue un enfoque modular basado en principios de Clean Architecture:

- `ui/` → Interfaz gráfica (Flet)
- `application/` → Casos de uso
- `domain/` → Reglas de negocio
- `infrastructure/` → Lectura/escritura de archivos
- `pipelines/` → Procesos ETL

---

## ⚙️ Instalación (modo desarrollo)

```bash
git clone https://github.com/tu-org/crm-income-automation.git
cd crm-income-automation

pip install -r requirements.txt
python main.py
```
