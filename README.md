
<p align="Left">
  <a href="" rel="noopener">
 <img width=650px height=200px src="https://imgur.com/IillnvW.png" alt="Project logo"></a>
</p>

# Consejo Escolar Sistema de Administracion (beta)

Sistema de administracion desarrollado durante las practicas profesionalizantes 

## Caracteristicas del proyecto

### A. Usuarios Admin pueden:
1. Ver los cuadros de resumen general del rendimiento de los asistentes, El rendimiento del personal, los cursos, las asignaturas, las licencias, etc.
2. Administrar personal (agregar, actualizar y eliminar)
3. Administrar Estudiantes (agregar, actualizar y eliminar)
4. Administrar Cursos (agregar, actualizar y eliminar)
5. Administrar Materias (agregar, actualizar y eliminar)
6. Administrar Sesiones (agregar, actualizar y eliminar)
7. Ver la asistencia de los estudiantes 
8. Revisar y responder a los comentarios de los estudiantes/personal
9. Revisar (aprobar/rechazar) la licencia del estudiante/personal

### B. Personal/Profesores pueden:
1. Ver las tablas de resumen general relacionadas con sus estudiantes, sus asignaturas, estado de licencia, etc.
2. Tomar / actualizar la asistencia de los estudiantes
3. Añadir/Actualizar Resultados
4. Solicitar licencia
5. Enviar comentarios a HOD

### C. Estudiantes pueden:
1. Ver los gráficos de resumen general relacionados con su asistencia, sus temas, estado de licencia, etc.
2. Ver las asistencias
3. Ver resultados
4. Solicitar Licencia
5. Enviar comentarios a HOD


## Como Instalar y ejecutar este projecto?

### Pre-Requisitos:
1. Instalar Git Version Control
[ https://git-scm.com/ ]

2. Instalar Python (Ultima Version)
[ https://www.python.org/downloads/ ]

3. Instalar Pip (Package Manager)
[ https://pip.pypa.io/en/stable/installing/ ]


### Installation
**1. Crear una carpeta donde se desee guardar el projecto**

**2. Crear un Virtual Environment y Activarlo**

Instalar el Virtual Environment primero
```
$  pip install virtualenv
```

Crear el Virtual Environment

```
$  python -m venv venv
```


Activar el Virtual Environment


```
$  source venv/scripts/activate
```



**3. Clonar el projecto**
```
$  git clone https://github.com/lincNx/Consejo-Escolar.git
```

 Entrar al projecto
```
$  cd django-student-management-system
```

**4. Instalar Requerimientos desde 'requirements.txt'**
```python
$  pip install -r requirements.txt
```

**5. Añadir los hosts**

- Ir al archivo settings.py  
- Entonces, en allowed hosts, Añadir [‘*’]. 
```python
ALLOWED_HOSTS = ['*']
```



**6. Correr el Server**

```python
$ python manage.py runserver
```

**7. Credenciales de login**

Crear Super User (HOD)
```
$  python manage.py createsuperuser
```
 Añadir Email, Usuario y Contraseña

**O Usar Credenciales Default**

*For HOD /SuperAdmin*
Email: admin@gmail.com
Password: admin

*For Staff*
Email: staff@gmail.com
Password: staff

*For Student*
Email: student@gmail.com
Password: student

