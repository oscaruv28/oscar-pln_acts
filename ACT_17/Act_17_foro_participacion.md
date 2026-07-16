# Actividad 17 — Participación en el foro

**Asignatura:** Procesamiento de Lenguaje Natural
**Maestría Virtual en Ingeniería de Sistemas y Computación**
**Estudiante:** Oscar Guerrero
**Fecha de entrega:** 10 de julio

---

**Pregunta del foro:** De todos los temas vistos (tokenización de subpalabras, embeddings, clasificación, NER, fine-tuning y RAGs), ¿cuál consideras que presenta el mayor reto al momento de llevarlo a cabo en el curso?

---

## Respuesta

De todos los temas del curso, considero que el fine-tuning fue el que mayor reto representó. La dificultad principal no estuvo en el modelo sino en los datos: preparar y alinear los conjuntos costó más de lo esperado. En TASS tuve que ajustar la codificación del archivo y el mapeo de etiquetas (N, NEU, P), y en el dataset de próstata trabajar el formato BIO línea por línea, descartando anotaciones mal formadas. A esto se sumó el costo computacional: entrenar BETO, XLNet y XLM-RoBERTa en Colab tomó horas y en varias ocasiones la sesión se desconectó, obligándome a reanudar. También la publicación en Hugging Face exigió configurar el token y los permisos de escritura. El RAG me pareció más manejable; lo más delicado ahí fue definir el tamaño de los chunks. En conclusión, el fine-tuning concentra la mayor complejidad porque integra calidad de datos, recursos de cómputo y despliegue.

_(148 palabras)_
