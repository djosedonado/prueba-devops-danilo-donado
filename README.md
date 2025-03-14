# PRUEBA DEVOPS

### 1-PASO

```bash
docker build -t prueba-devops-app .
```
### 2-PASO
```bash
docker run --name prueba-devops -p 5000:5000 -d prueba-devops-app
