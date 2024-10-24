#MiprimerRepositorio
o 3: Realizar un Commit**:
- Crear un commit inicial con un mensaje descriptivo:
```bash
git commit -m "Commit inicial: Añadir README.md"
```
Paso 4: Crear y Fusionar Ramas:
- Crear una nueva rama llamada `desarrollo`:
```bash
git branch desarrollo
```
- Cambiar a la rama `desarrollo`:
```bash
git checkout desarrollo
```
- Hacer cambios en el archivo `README.md` y realizar un commit:
```bash
echo "Este es un cambio en la rama desarrollo." >> README.md
git add README.md
git commit -m "Modificar README.md en la 