# RAG con Ollama

## 1. Instalación de Ollama

Primero, descarga e instala el launcher de Ollama desde el siguiente enlace:

[Descargar Ollama](https://ollama.com/)

---

## 2. Instalación de modelos

Para obtener los modelos necesarios, ejecuta los siguientes comandos:

```bash
ollama pull nomic-embed-text:latest
ollama pull deepseek-r1:1.5b
```

### 🔍 Verificar que los modelos están correctamente instalados

```bash
ollama list
```

Esto debería mostrar una lista con los modelos descargados.

---

## 3. Probar el chat directamente

Para verificar que el modelo funciona correctamente, puedes iniciar una conversación rápida:

```bash
ollama run deepseek-r1:1.5b
```

---

## 4. Configuración del entorno virtual

Para mantener las dependencias organizadas, es recomendable crear un entorno virtual:

```bash
python -m venv venv
```

Activa el entorno:

- **Windows:**
  ```bash
  ./venv/Scripts/activate
  ```
- **Linux/Mac:**
  ```bash
  source venv/bin/activate
  ```

---

## 5. Instalar dependencias del proyecto

Una vez activado el entorno virtual, instala las librerías necesarias desde el archivo `requirements.txt`:

```bash
pip install -r requirements.txt
```

---

✅ ¡Listo! Ahora puedes empezar a trabajar con tu RAG usando Ollama.

---
