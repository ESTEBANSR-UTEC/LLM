Instalar ollama: curl -fsSL https://ollama.com/install.sh | sh
2do paso: ollama serve
3er pas: ollama run tinyllama

detenerlo: Ctrl+Z

pregunta: curl http://127.0.0.1:11434/api/generate -d '{
  "model": "tinyllama",
  "prompt":"¿Por qué el cielo es azul?"
}'


Actualizar readmi en github: git commit -m "UPDATED READMI"
