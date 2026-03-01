# 🌀 AxiomNode | Ecosistema Educativo con IA Local

Bienvenido a la organización oficial de **AxiomNode**, un proyecto de TFM centrado en la generación de contenidos educativos mediante Inteligencia Artificial local, arquitectura de microservicios y optimización de recursos en sistemas distribuidos.

## 🚀 Misión del Proyecto
Optimizar el despliegue de LLMs (Large Language Models) en entornos con recursos limitados para ofrecer herramientas pedagógicas dinámicas (Quizzes, Pasapalabras, etc.) garantizando la privacidad y soberanía de los datos.

## 🛠️ Arquitectura del Ecosistema
El proyecto está fragmentado en repositorios especializados para garantizar la escalabilidad y el mantenimiento:

### 📖 Gobernanza y Diseño
* **[axiomnode-docs](link)**: Documentación técnica, diagramas UML, análisis de requisitos y manual de marca (Material Design 3).
* **[axiomnode-infrastructure](link)**: Orquestación con Docker Compose, configuraciones de red interna y despliegue en VPS.

### 🧠 Capa de IA y Datos (Shared Engine)
* **[axiomnode-ai-engine](link)**: Inferencia compartida mediante Ollama (Llama 3.1 8B cuantizado Q4_K_M).
* **[axiomnode-knowledge-base](link)**: Base de datos de vectores (Qdrant) con soporte RAG para contenidos educativos veraces.

### ⚙️ Microservicios Lean (Backend)
* **[axiomnode-gateway](link)**: Punto de entrada único, autenticación y balanceo de carga.
* **[axiomnode-quizz-service](link)**: Lógica de generación de cuestionarios mediante prompts estructurados.

### 💻 Interfaz de Usuario
* **[axiomnode-web-app](link)**: Frontend moderno implementando Material Design 3 y experiencias de juego reactivas.

---

## 🎨 Identidad Visual
Utilizamos una paleta de colores basada en **Material Design 3**:
* **Primary:** `#0043F4` (Azul Eléctrico)
* **Secondary:** `#6A1B94` (Violeta Nodal)
* **Surface:** `#1C1B1F` (Dark Mode Optimizado)

## ⚖️ Licencia
Este ecosistema se distribuye bajo la licencia **MIT**, fomentando el código abierto y la transparencia académica.
