# Bases de Kotlin

Apuntes ejecutables de los fundamentos de **Kotlin**: un menú de consola donde cada opción corre el ejemplo de un tema.

## Temas

- Variables y tipos
- Condicionales `if` y `when`
- Ciclos `while` y `for`
- Excepciones con `try`/`catch` y operador Elvis
- Listas, ordenamiento, mapas y sets
- Funciones, funciones de extensión, lambdas y funciones de orden superior
- Funciones de alcance: `let`, `with`, `run`, `apply` y `also`
- Proyecto final: una bola 8 mágica que responde preguntas

Todo el código está en [`src/main/kotlin/Main.kt`](src/main/kotlin/Main.kt).

## Cómo ejecutar

Requiere Java 8 o superior. El wrapper de Gradle descarga lo demás:

```bash
./gradlew run --console=plain
```

Se muestra el menú; escribe el número de la opción y pulsa Enter.
