Guía de Menús Gastronómicos es un proyecto que tiene como objetivo crear una colección de menús clasificados por tipo de cocina. Cada tipo de cocina se desarrolla en una rama independiente, donde los usuarios pueden realizar múltiples commits documentando diferentes aspectos del menú. Al final, todas las ramas se fusionan en la rama principal para formar una guía completa y coherente.

Problemática
El desafío principal de este proyecto es la gestión eficaz de ramas y commits en Git. Los usuarios deben asegurarse de que cada rama represente adecuadamente un tipo de cocina y que los cambios realizados sean significativos y bien documentados. Durante el proceso de fusión de ramas, pueden surgir conflictos que requieren resolución. Esta experiencia no solo fortalece las habilidades en el uso de Git, sino que también ilustra la importancia de una buena documentación al organizar información.

En este ejercicio, practicarás la creación de hasta 10 ramas en tu proyecto Guía de Menús Gastronómicos, cada una dedicada a un tipo diferente de cocina. Cada rama deberá contener al menos 5 commits relacionados con el menú correspondiente, y al final se realizará una fusión de todas las ramas en la rama principal (main), integrando todos los menús en un solo documento final.

Instrucciones
Crear la Carpeta y la Estructura del Proyecto
Crea una carpeta llamada menus/ en la raíz del proyecto donde se guardarán los archivos para cada tipo de cocina. La carpeta raíz se llamará GuiaDeMenus.
Crear Hasta 10 Ramas para los Tipos de Cocina
Los tipos de cocina pueden incluir: Italiana, Mexicana, Japonesa, India, China, Francesa, Mediterránea, Vegetariana, Carnes, y Postres.
Pista: Utiliza un comando para crear una nueva rama y cambiarte a ella al mismo tiempo.
Agregar una Entrada para Cada Menú con Múltiples Commits
En cada rama, crea un archivo Markdown para el tipo de cocina correspondiente.
Realiza al menos 5 commits en la rama, añadiendo cambios incrementales al archivo. Por ejemplo:
Primer commit: Agregar el título del menú.
Segundo commit: Descripción del tipo de cocina.
Tercer commit: Platos principales del menú.
Cuarto commit: Bebidas recomendadas.
Quinto commit: Consejos y sugerencias.
Nota: recuerda que cada commit se realizará siguiendo el formato de conventional commits.
Repetir para Cada Tipo de Cocina
Cambia de rama y repite los pasos para cada uno de los 10 tipos de cocina, asegurándote de hacer al menos 5 commits incrementales en cada rama.
Fusionar Cada Rama a la Rama Principal (main)
Cambia a la rama principal (main) y realiza la fusión de cada rama de cocina.
Pista: Asegúrate de estar en la rama principal antes de realizar la fusión.
Si se producen conflictos, resuélvelos manualmente y confirma los cambios.
Subir los Cambios al Repositorio Remoto
Sube la rama principal y las demás ramas al repositorio remoto para consolidar todos los cambios.
Asegúrate de que el repositorio esté público y compartido.




Ejemplo de Contenido del Archivo italiana.md de la Rama italiana
# Menú Cocina Italiana
​
## Descripción
La cocina italiana es famosa por sus sabores frescos y auténticos, basados en ingredientes simples como tomate, ajo, aceite de oliva y hierbas.
​
## Platos Principales
- **Pizza Margarita**: Masa fina cubierta con tomate, mozzarella y albahaca.
- **Pasta Carbonara**: Espaguetis en salsa de huevo, queso pecorino, panceta y pimienta.
- **Risotto al Funghi**: Arroz cremoso con setas.
​
## Bebidas Recomendadas
- Vino tinto Chianti.
- Agua con gas.
- Limoncello como digestivo.
​
## Consejos
- Usa ingredientes frescos para mejores resultados.
- Acompaña con pan artesanal para una experiencia completa.




Rama italiana
GuiaDeMenus/
├── menus/
│ ├── italiana.md # Commit 1: Crea el archivo y agrega el título.
└── README.md
​
GuiaDeMenus/
├── menus/
│ ├── italiana.md # Commit 2: Agrega la descripción del tipo de cocina.
└── README.md
​
GuiaDeMenus/
├── menus/
│ ├── italiana.md # Commit 3: Añade los platos principales del menú.
└── README.md
​
GuiaDeMenus/
├── menus/
│ ├── italiana.md # Commit 4: Incluye las bebidas recomendadas.
└── README.md
​
GuiaDeMenus/
├── menus/
│ ├── italiana.md # Commit 5: Agrega consejos y sugerencias.
└── README.md




Rama main
Después de fusionar todas las ramas (italiana, mexicana, japonesa, etc.) en la rama main, la estructura del proyecto se verá así:

GuiaDeMenus/
├── menus/
│ ├── italiana.md    # Contenido final fusionado desde la rama `italiana`.
│ ├── mexicana.md    # Contenido final fusionado desde la rama `mexicana`.
│ ├── japonesa.md    # Contenido final fusionado desde la rama `japonesa`.
│ ├── india.md
│ ├── china.md
│ ├── francesa.md
│ ├── mediterranea.md
│ ├── vegetariana.md
│ ├── carnes.md
│ └── postres.md
└── README.md
Cada archivo en la carpeta menus/ contendrá la versión final de cada tipo de menu, resultado de los commits en las ramas correspondientes. La fusión en main integrará todos los cambios, consolidando el proyecto.