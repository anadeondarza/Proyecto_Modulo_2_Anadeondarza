# Proyecto_Modulo_2_Anadeondarza


# Cuánto puedo llegar a ganas como Analista de Datos?

Este es el README de mi segundo proyecto en Ironhack, referente al módulo 2. El proyecto consiste en la creación de varios dashboards con Power BI con el objetivo de proporcionar información sobre las profesiones mejores pagadas por país, tipo y localización de la empresa, y tipo de puesto de trabajo. 

# GOAL 🏃

El objetivo es que el usuario pueda navegar por los dashboards hasta sacar sus propias conclusiones sobre la foto actual de los salarios en las profesiones del análisis de datos. 

# Data/Architecture 💻

1. Descarga del CSV de la plataforma Kaggle: https://www.kaggle.com/code/vishantnagpal/data-science-job-salaries
2. Limpieza y manipulación de base de Datos en Jupyter Notebook, con pandas. Hay un total de 607 entradas de datos a partir de datos proporcionados por empleados, teniendo estos la residencia en 56 países distintos, en 50 tipos de puestos distintos, y 50 países de residencia de las empresas. 
3. Descarga en CSV.
4. Importación del CSV en Power BI desktop.
5. Diseño del modelo


# Dashboard funtionalities

La primera pestaña muestra información general según el tipo de empresa, formato de trabajo, tipo de contrato y experiencia del empleado en 2020, 2021 y 2022. En ella se pueden ver según estas características, el promedio de salarios más altos.

La segunda pestaña hace referencia al promedio de salarios, por tipo de puestos, y país de residencia de la empresa y los propios empleados. Podemos ver la evolución en 2020, 2021 y 2022.

La última pestaña muestra el promedio de salarios por puesto de trabajo, tamaño de la empresa y tipo de trabajo remoto en España. 


# Insights

Primera pestaña: 
1. Las empresas de más de 250 empleados en promedio en los 3 años ha pagado salarios más altos
2. El porcentaje de de trabajo presencial y remoto, es praticamente igual, siendo el salario ligeramente más alto 100% presencial
3. El salario más alto se da en los empleados contratados Full time o con contrato externo.
4. Los expertos cobran más que el resto de categoría profesionales.

Segunda pestaña:
1. El puesto mejor pagado es el de Lead Data Analytics alzando los 405 mil dólares anuales en promedio.
2. El Data Analyst puede llegar a alcanzar los 100 mil dolares anuales en promedio.
3. El Business Data Analyst por promedio alcanza los 44 mil anuales. 
4. Al no tener todos los puestos, esta visión es un recuento total de 318 registros. 

Tercera pestaña: 
1. El sueldo máximo es de 131 mil dólares anuales.
2. El sueldo medio es de 29 mil dólares anuales. 





# Glosario 

Work_year: (2020,2021,2022)

Experience_level: 
 
 1. EN: Entry Level 
 2. MI: Mid Level
 3. SE: Senior Level
 4. EX: Executive Level

Company_size:

 1. S = less than 50 employees (small) 
 2. M = 50 to 250 employees (medium)
 3. L = more than 250 employees (large)

Employment_type:
 1. PT = Part-time
 2. FT = Full-time 
 3. CT = Contract 
 4. FL = Freelance

Job_title: 50 positions.

Salary: The total gross salary amount paid.

Salary_in_usd - The salary in USD.

Remote_ratio:
 1. 0 = No remote work (less than 20%)
 2. 50 = Partially remote 
 3. 100 = Fully remote (more than 80%)

Company_location: There are 50 distinct company locations, (Alpha-2 code).

Employee_residence:(Alpha-2 code).


# Información de Contacto 💌

Emial: adeondarza@gmail.com