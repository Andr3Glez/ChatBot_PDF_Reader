# Proyecto LLMs

**Integrantes:**  
Andre Gonzalez  
Sergio Dueñas 

## 🧠 Descripción General

Este proyecto consiste en un chatbot capaz de leer archivos PDF y responder preguntas sobre su contenido (autor, resumen, etc.). La app está construida con Streamlit y usa bibliotecas como LangChain y PyPDF2 para procesar los documentos.

## 🔄 Flujo Principal

1. El usuario carga uno o varios PDFs.
2. El texto se extrae y se divide en fragmentos.
3. Se generan embeddings y se almacena en un vector store.
4. El chatbot responde preguntas basadas en ese contenido.

## 🧩 Dependencias Clave

- **Streamlit:** Interfaz de usuario.
- **PyPDF2:** Lectura de PDFs.
- **LangChain:** Embeddings y cadena conversacional.
- **Dotenv:** Gestión de variables de entorno.
- **htmlTemplates:** Estilos para los mensajes del chatbot.

## 🛠️ Funciones Principales

- `get_pdf_text()`: Extrae texto de los PDFs.
- `get_text_chunks()`: Divide el texto en fragmentos.
- `get_vectorstore()`: Crea un almacén vectorial con embeddings.
- `get_conversation_chain()`: Construye la cadena de conversación.
- `handle_userinput()`: Procesa preguntas del usuario.
- `main()`: Ejecuta la app y la interfaz.

## 🚀 Cómo Usarlo

1. Crear un entorno virtual.
2. Instalar dependencias
3. Crear un archivo `.env` con tu API key de OpenAI
4. Ejecutar la app
