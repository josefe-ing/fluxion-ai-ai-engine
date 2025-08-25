# 🤖 Fluxion AI - AI Engine

Sistema de Inteligencia Artificial para predicciones y alertas proactivas

## 🏗️ Arquitectura  
- **Framework**: Python + FastAPI
- **Puerto**: 8000
- **ML Stack**: Prophet, Pandas, NumPy
- **Agentes**: Multi-agent system

## 🚀 Desarrollo

```bash
# Crear entorno virtual
python -m venv venv
source venv/bin/activate

# Instalar dependencias
pip install -r requirements.txt

# Desarrollo
uvicorn src.main:app --host 0.0.0.0 --port 8000 --reload

# Tests
pytest
```

## 🧠 Agentes IA
- **AlertAgent**: Detecta stockouts y anomalías
- **ForecastAgent**: Predicciones con Prophet
- **OptimizeAgent**: Optimización automática
- **ChatAgent**: Conversación natural

## 📊 Endpoints ML
- `POST /predict/demand` - Predicción de demanda
- `POST /analyze/inventory` - Análisis de inventario
- `GET /agents/status` - Estado de agentes
