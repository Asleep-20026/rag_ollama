# RAG con Ollama

Instalar launcher de ollama:
https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwik1Oi83qOMAxV0JrkGHRq4BVoQFnoECAwQAQ&url=https%3A%2F%2Follama.com%2F&usg=AOvVaw17WonOj_dIOYJACdXhdC2W&opi=89978449

Instalar modelos:

```bash
ollama pull nomic-embed-text:latest
ollama pull deepseek-r1:1.5b
```
Verificar modelos:

```bash
ollama list
```

Probar chat directamente:

```bash
ollama run deepseek-r1:1.5b
```
Generar entorno virtual: 

```bash
python -m venv venv
./venv/Scripts/activate
```

Instalar dependencias
```bash
pip install -r requirements.txt
```
