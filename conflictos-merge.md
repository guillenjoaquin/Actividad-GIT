# Conflicto de Merge – Actividad GIT  
**Autor:** Joaquín Guillén


Al ejecutar el comando:

```bash
git merge origin/main
```

Se produjo un conflicto en el archivo README.md, ya que había cambios diferentes tanto en mi rama local como en origin/main

## Cómo lo resolví?

- Abrí `README.md` en VSCode.
- Revisé ambas versiones del contenido.
- Combiné las dos.
- Guardé los cambios.
```bash
git add .
git commit -m "Resuelvo conflicto de merge en README.md"
```