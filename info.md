**Listado de comandos útiles para trabajar con Git/GitHub:**

## 📁 **ESTADO E INFORMACIÓN**
```bash
git status                          # Ver estado de archivos
git log --oneline                  # Ver historial de commits
git log --oneline --graph          # Historial con gráfico
git branch                         # Listar ramas
git remote -v                      # Ver repositorios remotos
```

## 🔄 **TRABAJO DIARIO - Flujo básico**
```bash
git add .                          # Agregar TODOS los cambios
git add nombre-archivo.txt         # Agregar archivo específico
git commit -m "mensaje descriptivo" # Hacer commit
git push                          # Subir cambios al repositorio
git pull                          # Descargar cambios
```

## 🎯 **CONFIGURACIÓN INICIAL**
```bash
git config --global user.name "TuNombre"
git config --global user.email "tu@email.com"
git init                          # Inicializar repo nuevo
git clone [url-repositorio]       # Clonar repo existente
```

## 🌿 **TRABAJO CON RAMAS**
```bash
git branch nueva-rama             # Crear nueva rama
git checkout nombre-rama          # Cambiar a rama
git checkout -b nueva-rama        # Crear Y cambiar a rama
git merge nombre-rama             # Fusionar rama actual
```

## ⚡ **COMANDOS ÚTILES FRECUENTES**
```bash
git diff                          # Ver cambios no guardados
git restore nombre-archivo        # Descartar cambios en archivo
git reset --hard HEAD            # Descartar TODOS los cambios
git push -u origin main          # Primer push con seguimiento
```

## 🆘 **AYUDA Y SOLUCIÓN DE PROBLEMAS**
```bash
git --help                        # Ayuda general
git config --list                # Ver configuración
git remote set-url origin [nueva-url] # Cambiar URL remota
```

## 🚀 **FLUJO COMPLETO TÍPICO:**
```bash
# 1. Trabajar en archivos...
# 2. Ver cambios
git status

# 3. Agregar cambios
git add .

# 4. Hacer commit
git commit -m "Descripción de cambios"

# 5. Subir a GitHub
git push
```

**¿Te gustaría que profundice en algún comando específico o necesitas ayuda con algún flujo en particular?** 😊