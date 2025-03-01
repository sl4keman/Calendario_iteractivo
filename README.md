#Calendario_iteractivo
#Calendario de Festividades en Colombia  

#Este proyecto ha sido desarrollado como parte de la materia **Desarrollo de Sistemas Informáticos Multimedia** y consiste en un calendario interactivo que muestra las festividades más importantes de Colombia. La aplicación ha sido creada con **Django** e incorpora tecnologías como **AJAX** y **FullCalendar.js** para una experiencia dinámica y moderna.  

#Características  

✅ **Interfaz minimalista** inspirada en diseños modernos.  
✅ **Eventos dinámicos** que muestran imágenes y descripciones al hacer clic.  
✅ **Uso de AJAX** para cargar información sin necesidad de recargar la página.  
✅ **Sistema de plantillas Django** para estructurar la aplicación.  
 

#Instalación y Configuración

#Clonar este repositorio:  
```bash
git clone https://github.com/sl4keman/Calendario_iteractivo.git

#Instalar las dependencias

pip install -r requirements.txt

#Aplicar las migraciones de la base de datos
python manage.py makemigrations
python manage.py migrate

# Ejecutar el servidor de desarrollo:
python manage.py runserver


#Acceder a la aplicación en el navegador:
http://127.0.0.1:8000/
