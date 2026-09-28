# Transformers desde cero con PyTorch

## Los 7 mecanismos que sustentan la IA generativa

[![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python&logoColor=white)](https://www.python.org)
[![PyTorch](https://img.shields.io/badge/PyTorch-2.0+-red?logo=pytorch&logoColor=white)](https://pytorch.org)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter&logoColor=white)](https://jupyter.org)

---

> **La IA generativa no es magia: es ingeniería de sistemas estadísticos a gran escala.**

Este repositorio implementa un **Transformer codificador-decodificador** desde cero con PyTorch, con el objetivo de hacer comprensibles los siete mecanismos fundamentales que permiten a modelos como GPT, BERT, Llama y T5 interpretar contextos, aprender relaciones complejas y generar texto, código o secuencias estructuradas.

---

## ¿Qué encontrarás aquí?

- ✅ **Atención escalada**: estabiliza los puntajes de atención en altas dimensiones.
- ✅ **Atención multi-cabeza**: diversifica las perspectivas de representación.
- ✅ **Codificación posicional sinusoidal**: inyecta orden sin parámetros adicionales.
- ✅ **Conexiones residuales**: facilitan el flujo de información en redes profundas.
- ✅ **Normalización de capas**: estabiliza la optimización durante el entrenamiento.
- ✅ **Redes de avance por posición**: enriquecen cada representación contextualizada.
- ✅ **Arquitectura codificador-decodificador**: con atención causal y atención cruzada.

---

## Estructura del repositorio

```text
transformers-desde-cero-pytorch/
├── transformer_desde_cero_pytorch.ipynb   # Cuaderno Jupyter con implementación paso a paso
├── README.md                              # Este archivo
├── LICENSE                                # Licencia MIT
└── .gitignore                             # Plantilla Python oficial de GitHub
```

---

## ¿Para quién es este proyecto?

- 🎓 **Estudiantes** de ciencia de datos, ingeniería o inteligencia artificial que quieren entender cómo funciona un Transformer por dentro.
- 👨‍💻 **Desarrolladores** que usan Hugging Face o APIs de modelos de lenguaje y buscan criterios técnicos para depurar, optimizar o adaptar arquitecturas.
- 📊 **Data scientists** que necesitan implementar, ajustar o extender Transformers en proyectos reales.
- 🚀 **Profesionales** que construyen un portafolio técnico en IA generativa y desean demostrar comprensión arquitectónica, no solo uso de herramientas.

---

## Cómo usar este cuaderno

1. **Abre el notebook** en Google Colab, Jupyter Notebook o JupyterLab.
2. **Ejecuta las celdas en orden**: cada sección construye un componente del Transformer.
3. **Modifica hiperparámetros**: cambia `d_model`, `num_heads`, `num_layers` y observa impactos en forma de tensores y pérdida.
4. **Experimenta con datos reales**: sustituye las secuencias sintéticas por un corpus paralelo o una tarea de resumen.
5. **Compara con implementaciones optimizadas**: contrasta este código pedagógico con `torch.nn.Transformer` o Hugging Face Transformers.

---

## Requisitos

- Python 3.8 o superior
- PyTorch 2.0 o superior
- Jupyter Notebook o Google Colab

### Instalación local

```bash
pip install torch notebook
```

---

## Lo que este proyecto NO es

- ❌ No es un modelo de frontera para producción.
- ❌ No incluye optimizaciones como atención acelerada, precisión mixta o entrenamiento distribuido.
- ❌ No reemplaza bibliotecas como Hugging Face Transformers para casos de uso reales.

**Es, en cambio, una herramienta educativa** para convertir conceptos abstractos en código ejecutable, inspeccionable y modificable.

---

## Próximos pasos sugeridos

- Sustituir datos sintéticos por un corpus paralelo (traducción, resumen, generación).
- Incorporar un tokenizador real con tokens especiales (inicio, fin, relleno, desconocido).
- Separar conjuntos de entrenamiento, validación y prueba.
- Implementar planificación de tasa de aprendizaje con calentamiento.
- Añadir decodificación voraz, búsqueda en haz o muestreo para inferencia.
- Medir pérdida, perplejidad, latencia, memoria y calidad de salida.
- Comparar con `torch.nn.Transformer` y modelos preentrenados de Hugging Face.

---

## Referencias clave

- Vaswani, A., Shazeer, N., Parmar, N., Uszkoreit, J., Jones, L., Gomez, A. N., Kaiser, Ł., y Polosukhin, I. (2017). *Attention Is All You Need*. NeurIPS 2017.
- Brown, T. B., et al. (2020). *Language Models are Few-Shot Learners*. GPT-3.
- Raffel, C., et al. (2020). *Exploring the Limits of Transfer Learning with a Unified Text-to-Text Transformer*. T5.
- Touvron, H., et al. (2023). *LLaMA: Open and Efficient Foundation Language Models*.

---

## Licencia

Este proyecto se distribuye bajo la [Licencia MIT](LICENSE). Puedes usarlo, modificarlo y compartirlo libremente, siempre que conserves el aviso de licencia y atribución.

---

## Contribuciones

Las contribuciones son bienvenidas: correcciones, mejoras pedagógicas, visualizaciones de atención, extensiones a arquitecturas modernas (RoPE, SwiGLU, pre-norm) o ejemplos con datos reales. Abre un *issue* o un *pull request* si deseas colaborar.

---

## Sobre el autor

**Marco Antonio Cornejo Jaramillo**  
Ingeniero eléctrico y electrónico orientado a ciencia de datos, inteligencia artificial y automatización.  
🔗 [LinkedIn](https://www.linkedin.com/in/iamarcoantonio)
🔗 [facebook](https://www.facebook.com/people/Marco-Antonio-Cornejo-Jaramillo/100090212510037/)
🔗 [Personal Portafolio IA](https://www.ia.marcoantoniocornejo.com)  
🔗 [Personal CV](https://www.cv.marcoantoniocornejo.com)  
📧 [Contacto](+584122494272)

---

<div align="center">

### ¿Te resultó útil este proyecto?

⭐ **Dale una estrella** para apoyar el desarrollo y ayudar a que más personas encuentren este recurso educativo.

**La comprensión arquitectónica es el primer paso hacia la innovación responsable en IA.**

</div>
