# Optimización de Cobranza Domiciliada - Datathon 2025
Este repositorio contiene el proyecto de mejora en la estrategia de cobros domiciliados para Credifiel, desarrollado durante Datathon 2025 del Data Science Club del Tec de Monterrey.

**Descripción del Reto**
Credifiel ofrece créditos (mayormente colocados a 24 meses) que se pagan de forma automática desde la cuenta bancaria del cliente cada quincena o mes. Para ello, se emplea una de las 21 posibles estrategias según los acuerdos existentes entre Credifiel y los bancos Santander, BBVA, Banamex y Banorte. Cada una tiene un costo y tiempo de respuesta asociado diferentes, y actualmente no se realiza esta asignación de forma automática.


## Objetivo del Proyecto
Desarrollar una solución que permita:

- Generar recomendaciones dinámicas para elegir la mejor estrategia de cobro por cliente, considerando el banco, día y tipo de respuesta esperada.

- Maximizar la efectividad y eficiencia de la domiciliación (más cobros exitosos y menos costos operativos).

- Minimizar la influencia de errores humanos que estén incurriendo en ineficiencias en la operación.


## Resultados Alcanzados
Incremento del % de domiciliaciones exitosas.

Disminución de intentos fallidos por estrategias lentas o costosas.

Automatización la toma de decisiones operativas en cobranza.

## Contenidos Repositorio
- Modelos de predicción de comportamiento completamente entrenados
- Modelo de toma de decisiones cliente común
- Modelo de toma de decisiones cliente extremo
- Código de Analítica de datos

## Para ejecutar el proyecto
bash
Copiar
Editar
git clone https://github.com/tu_usuario/credifiel-cobranza-hackathon.git
cd credifiel-cobranza-hackathon
pip install -r requirements.txt
streamlit run dashboard/app.py


## 🤝 Integrantes del Equipo
Samantha Ruelas Valtierra  
Juan Ángel Lucio Rojas  
Erika Martínez Meneses  
Sofia Alvarez Sandoval
