---
title: PORTFOLIO M2CIBERSEGURIDAD
---

# M2CIBERSEGURIDAD

Soy M2C, un estudiante de Ciberseguridad y Junior Pentester que lleva 2 años resolviendo problemas y formándome en varios campos de la Ciber. 

Aquí reúno proyectos prácticos de seguridad defensiva y de seguridad en sistemas con IA, integrando la IA con todos los ejecutables en local y documentando los resultados y sus limitaciones. (a veces, bastante, la IA nos engaña)

## Proyectos

### 1. Analizador de phishing con IA local
Script en Python que analiza correos `.eml` en dos capas: comprobaciones automáticas verificables con código (Reply-To y Return-Path distintos del remitente, SPF y DKIM fallidos, enlaces con IP, lenguaje de urgencia) y un informe redactado por un modelo local (Llama 3.2 vía Ollama). El README documenta los fallos del modelo, como un veredicto incoherente, y por qué su informe debe revisarlo una persona.

**Tecnologías:** Python, expresiones regulares, Ollama.
[Ver código y documentación](https://github.com/m2ciber/analizador-phishing)

### 2. Detector de intrusiones de red con Machine Learning
Clasificador Random Forest (scikit-learn) evaluado con el dataset real NSL-KDD: entrenado con `KDDTrain+` y probado con `KDDTest+`, alcanza un 78 % de acierto, con pocas falsas alarmas (2,7 %) pero dejando pasar el 37 % de los ataques. El README documenta los resultados con sus limitaciones y los siguientes pasos para mejorarlos. Incluye también una demo con datos sintéticos.

**Tecnologías:** Python, pandas, scikit-learn, NSL-KDD.
[Ver código y documentación](https://github.com/m2ciber/detector-trafico-ml)

### 3. Laboratorio de prompt injection y defensa en dos capas
Pruebas de ataques de prompt injection (OWASP LLM01) y fuga de información (LLM06) contra un asistente local, con un firewall de entrada y salida. Comparo dos modelos: uno resiste los ataques y el más pequeño entrega las credenciales (ficticias) sin protección.

**Tecnologías:** Python, Ollama, regex, registro de auditoría en JSON.
[Ver código y documentación](https://github.com/m2ciber/lab-prompt-injection)

## Sobre mí
Estudiante de Ciberseguridad interesado en aplicar la IA, Junior Pentester, e investigador de IA y forense.

## Habilidades
- Python, Git y GitHub
- Linux (Kali) y PowerShell
- Análisis de correo y de tráfico de red
- Analisis de IA (Claude, ChatGPT, Ollama, qwen3, ...)

## Contacto

- GitHub: [github.com/m2ciber](https://github.com/m2ciber)
- LinkedIn: [Mi perfil de LinkedIn](https://www.linkedin.com/in/m2c-ciberseguridad-820744342)