# Creado con backend separado con Django rest framework y Frontend con Astro

## Capturas

<img width="1165" height="779" alt="Captura de pantalla 2025-08-09 a la(s) 10 48 03 a m" src="https://github.com/user-attachments/assets/c74487cd-44fa-472e-84f6-8a16f8130344" />
<img width="1162" height="776" alt="Captura de pantalla 2025-08-09 a la(s) 10 48 49 a m" src="https://github.com/user-attachments/assets/d7dff658-6c97-4a0c-8949-d4c943c659a9" />
<img width="1176" height="780" alt="Captura de pantalla 2025-08-09 a la(s) 10 48 29 a m" src="https://github.com/user-attachments/assets/e3f387bd-9d3f-4988-8fcb-a953c63aa614" />


Desde la raiz del proyecto debes ejecutar el siguiente comado para crear los contenedores de docker y ponerlos en linea:

      docker-compose up -d

estaticos

      docker-compose exec backend python manage.py collectstatic --noinput

      
Ejecutar el siguinete comado para hacer las migraciones a la base de datos:

      docker-compose exec backend python manage.py migrate
  
Ejecutar el siguinte comado para crear el superusuario y poder acceder al admin y acceso a las apis:

      docker-compose exec backend python manage.py createsuperuser

usuario:
 
      medicalSystem


contraseña:

      System123456
