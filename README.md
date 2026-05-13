# UNIVERSIDAD TÉCNICA DE AMBATO
## FACULTAD DE INGENIERÍA EN SISTEMAS, ELECTRÓNICA E INDUSTRIAL

**TEMA:** PRUEBA PRÁCTICA INDIVIDUAL — APLICATIVO INTERACTIVO DE LÓGICA Y ALGORITMOS EN C++ Y JAVA  
**Estudiante:** Victor Chacha  
**Carrera:** Ingeniería en Software  
**Semestre:** Primero | **Paralelo:** "B"  
**Asignatura:** Algoritmos y Lógica de Programación  
**Docente:** José Caiza  

---

Descripción del Proyecto
Este repositorio contiene el desarrollo integral de la **Prueba Práctica Individual**, la cual implementa un aplicativo interactivo desarrollado nativamente y con total equivalencia lógica en los lenguajes **C++**. 

El software evidencia el dominio práctico de los fundamentos de lógica de programación tratados durante el curso, incluyendo la declaración de variables, operadores aritméticos/relacionales, estructuras condicionales robustas, ciclos repetitivos (`do-while`, `while`, `for`), manejo de arreglos unidimensionales estáticos y la implementación de flujos para la **persistencia de datos** en archivos de texto plano.

---

Funcionalidades Implementadas (Menú Interactivo)

El aplicativo se gestiona a través de un menú principal continuo con las siguientes opciones:

1. **Operaciones Básicas:** Ejecuta sumas, restas, multiplicaciones y divisiones sobre dos números flotantes ingresados por el usuario. Implementa una validación relacional estricta para interceptar y bloquear la **división para cero**.
2. **Registro de Notas (Doble Modalidad):** - **Subopción 1 (Ingreso Manual):** Permite registrar exactamente **5 notas** por teclado validando que pertenezcan al rango permitido de 0 a 10 (Cumplimiento estricto del literal de la Parte 3 de la evaluación).
   - **Subopción 2 (Carga Automatizada):** Lee de forma secuencial y estática el archivo plano `estudiantes.txt` para procesar de manera instantánea la nómina oficial completa de **39 estudiantes** del curso (Cumplimiento del requerimiento de escalabilidad del docente).
   - *Cálculos generados:* Promedio general, Nota mayor, Nota menor, Cantidad de aprobados (nota >= 7.0) y Cantidad de reprobados (nota < 7.0).
3. **Guardar Resultados:** Aplica flujos de salida (`ofstream` en C++ / `FileWriter` en Java) para exportar de forma persistente la sesión actual hacia el archivo físico `resultados.txt` rotulado con metadatos de autoría, fecha y traza de ejecución.
4. **Salir:** Finaliza el ciclo de vida de la aplicación.

