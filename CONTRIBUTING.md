# Cómo contribuir

¡Gracias por sumar a **Awesome IA Argentina**! Esta guía explica qué recursos entran en la lista y cómo proponerlos.

## Qué recursos se aceptan

- Relacionados con Inteligencia Artificial, Ciencia de Datos o Machine Learning.
- Con foco en Argentina o en la comunidad hispanohablante, o de referencia global indiscutida.
- Activos y accesibles: nada de enlaces caídos, cursos discontinuados ni comunidades inactivas.
- Útiles por su contenido, no por su promoción. No se aceptan enlaces de afiliados.

## Dónde agregarlo

Cada categoría tiene su propio archivo. Agregá el recurso en la sección que corresponda:

| Categoría | Archivo |
| --- | --- |
| Carreras, cursos y libros | [`educacion/README.md`](educacion/README.md) |
| Datos, datasets y papers | [`investigacion/README.md`](investigacion/README.md) |
| Librerías, APIs y plataformas | [`herramientas/README.md`](herramientas/README.md) |
| Comunidades, eventos y medios | [`comunidad/README.md`](comunidad/README.md) |

## Formato

Seguí el formato de la sección donde lo agregás. En las listas:

```markdown
*   **Nombre del recurso:** Descripción breve en español, en una oración. [Web](https://ejemplo.com/)
```

En las tablas, completá todas las columnas y usá `[Web](url)` en la columna de enlace.

- Usá la URL oficial y con `https`.
- Escribí la descripción en español, con voseo y sin mayúsculas innecesarias.
- Un recurso por Pull Request, salvo que estén relacionados.

## Pasos

1. Hacé un **fork** del repositorio.
2. Creá una rama: `git checkout -b recurso/nombre-del-recurso`.
3. Agregá el recurso en el archivo de la categoría.
4. Commiteá con un mensaje claro: `git commit -m "Agrega <recurso> a <categoría>"`.
5. Pusheá la rama y abrí un **Pull Request** explicando por qué el recurso suma.

¿Encontraste un enlace roto o un dato desactualizado? Abrí un [issue](https://github.com/AgustinBouzonn/Awesome-IA/issues) o mandá directamente el Pull Request con la corrección.

Al participar aceptás el [Código de Conducta](CODE_OF_CONDUCT.md).
