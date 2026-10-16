# Practica1-Intro-CI
Materia: DevSecOps
Unidad2: Integración Continua y Desarrollo Continuo

Objetivo
Comprender el funcionamiento de la Integración Continua mediante la creación de un flujo de trabajo automatizado con GitHub Actions.

Desarrollo
Se creó un repositorio en GitHub llamado "Practica1-Intro-Ci". Dentro del repositorio se creó el archivo "hola.yaml", ubicado en ".github/workflows/".

Se configuró un workflow para ejecutarse cuando se realiza un evento "push". El trabajo utiliza un ejecutor Ubuntu y ejecuta el comando "echo "HOLA MUNDO"".

Resultado
La ejecución del workflow finalizó correctamente y se comprobó que el mensaje "HOLA MUNDO" aparece en los registros de GitHub Actions.

Conclusión
Con esta práctica se comprendió cómo GitHub Actions permite automatizar tareas mediante flujos de trabajo definidos en archivos YAML.
