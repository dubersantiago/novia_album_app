# Landing romántica 💖

## Ejecutar local

```bash
docker build -t novia-album .
docker run -p 8080:80 novia-album
```

Abrir:
http://localhost:8080

## Deploy en Dokploy

1. Sube estos archivos a GitHub
2. En Dokploy:
   - New Application
   - From Git Repository
3. Puerto interno:
   80
4. Deploy 🚀

## Cambiar fotos

Edita el archivo `index.html` y reemplaza las URLs de Unsplash por tus fotos.
