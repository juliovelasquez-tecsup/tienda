# Guia de contribucion

Gracias por querer mejorar Tienda TECSUP. Esta guia explica como colaborar.

## Como reportar un error

1. Revisa en la pestana **Issues** que el error no este reportado.
2. Abre un **New issue** con un titulo claro, por ejemplo:
   `El total muestra S/ 43.00 en lugar de S/ 68.00`.
3. Incluye en la descripcion:
   - Que esperabas que pasara.
   - Que paso realmente.
   - Los pasos para reproducirlo.
   - Una captura de pantalla y tu navegador.

## Como proponer una mejora

1. Abre un Issue que explique la mejora y por que es util.
2. Espera la respuesta del autor antes de empezar.
3. Haz un fork del repositorio y crea una rama:

```bash
git checkout -b mejora/mi-cambio
```

4. Guarda tus cambios con un mensaje descriptivo y subelos:

```bash
git commit -m "Describe tu cambio"
git push origin mejora/mi-cambio
```

5. Abre un Pull Request que enlace al Issue (por ejemplo `Closes #1`).

## Como probar tus cambios

1. Abre `index.html` en el navegador.
2. Comprueba que la pagina se vea con los estilos del curso.
3. Comprueba que la ultima linea muestre `Total: S/ 68.00`.

## Checklist para enviar un Pull Request

- [ ] La pagina abre sin errores en el navegador.
- [ ] Los estilos se cargan correctamente.
- [ ] El total mostrado es `S/ 68.00`.
- [ ] El cambio resuelve un solo problema.
- [ ] El mensaje del commit explica que se hizo.
- [ ] El Pull Request enlaza al Issue relacionado.