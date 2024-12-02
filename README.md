# **Automated Campaign Process**

## **Resumen**
Este proyecto tiene como objetivo optimizar el análisis de campañas publicitarias mediante dos componentes principales:
1. Un **Dashboard interactivo** desarrollado en Looker Studio, que permite visualizar métricas clave como clics, impresiones y costos en tiempo real.
2. Un **Modelo de Clasificación basado en Machine Learning**, implementado en Python y Streamlit, que predice el éxito de las campañas en función de un umbral definido en colaboración con el negocio.

Ambos productos contribuyen a mejorar la toma de decisiones estratégicas en campañas publicitarias, incrementando la eficiencia y escalabilidad de los análisis.

### **Conclusiones (Insights)**
- **Cumplimiento de objetivos**: Se desarrollaron herramientas que permiten la visualización en tiempo real y la predicción del éxito de campañas publicitarias.
- **Impacto en KPIs**: Mejoras significativas en eficiencia y reducción de tiempos en la toma de decisiones.
- **Dificultades**: Selección de características relevantes y definición de umbrales óptimos en colaboración con el negocio.
- **Mejoras futuras**: Incorporación de más datos, reducción de sesgos y exploración de nuevas características.

---

## **Integrantes**
- **Juan Sebastián Peláez Pardo**
- **Steban Nicolás Tibatá Castañeda**
- **Diego Álvaro Morales Medrano**

---

## **Librerías/Dependencias**
Este proyecto utiliza las siguientes librerías y dependencias, detalladas en los archivos `requirements.txt` presentes en las carpetas `Notebook Proyecto` y `Streamlit`.

### Principales dependencias:
- **altair==5.5.0**
- **streamlit==1.40.2**
- **pandas==2.2.2**
- **scikit-learn==1.5.2**
- **matplotlib==3.8.0**
- **numpy==1.26.4**
- Entre otras (consultar el archivo `requirements.txt`).

Para instalar las dependencias en cada componente:
```bash
pip install -r Notebook\ Proyecto/requirements.txt
pip install -r Streamlit/requirements.txt
```

---

## **Estructura del Proyecto**
```plaintext
/
├── Entrega Final.pdf           # Informe completo del proyecto
├── Primera Entrega.pdf         # Documento inicial del proyecto
├── Notebook Proyecto/          # Carpeta del notebook y archivos relacionados
│   ├── data.xlsx               # Dataset consolidado
│   ├── Proyecto_ciencia_de_datos.ipynb # Notebook con el desarrollo y análisis del modelo
│   ├── requirements.txt        # Dependencias necesarias para el notebook
│
└── Streamlit/                  # Carpeta del modelo y la app Streamlit
    ├── app.py                  # Script principal para la aplicación Streamlit
    ├── decision_tree_pipeline.pkl  # Modelo de clasificación exportado
    ├── modelo.h5               # Modelo entrenado en formato H5
    ├── honda.png               # Imagen utilizada en la app
    ├── vml.png                 # Imagen utilizada en la app
    ├── requirements.txt        # Dependencias necesarias para Streamlit
```

---

## **Instrucciones de Ejecución**

### **1. Clonar el repositorio**
```bash
git clone https://github.com/tu_usuario/nombre_del_repositorio.git
cd nombre_del_repositorio
```

### **2. Instalar las dependencias**
Instala las dependencias de cada componente:
```bash
pip install -r "Notebook Proyecto/requirements.txt"
pip install -r "Streamlit/requirements.txt"
```

### **3. Ejecutar la aplicación Streamlit**
Desde la carpeta `Streamlit`, ejecuta:
```bash
cd Streamlit
streamlit run app.py
```

### **4. Consultar el notebook**
Accede al archivo `Proyecto_ciencia_de_datos.ipynb` en la carpeta `Notebook Proyecto` y ábrelo con Jupyter Notebook o Jupyter Lab para analizar el desarrollo del modelo.

---

## **Accesos Directos**
- **Dashboard en Looker Studio**: [Enlace al dashboard](https://lookerstudio.google.com/u/0/reporting/9e091957-6c52-4ad3-a98d-b1e4b99c9ca7)
- **Modelo de Clasificación en Streamlit**: [Enlace al modelo](https://cdadeployment-97gn69kmzjdhwzuwcbzhg6.streamlit.app/)

---

### **Nota**
Debido a que la empresa VML requiere reserva total de sus datos, el dashboard desarrollado no es público. Sin embargo, el equipo está disponible para atender solicitudes de permisos para visualizar el dashboard y proporcionar los accesos necesarios.