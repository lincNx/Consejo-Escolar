
<p align="center">
  <a href="" rel="noopener">
 <img width=650px height=200px src="https://imgur.com/IillnvW.png" alt="Project logo"></a>
</p>

<div align="center">

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Django](https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![Bootstrap](https://img.shields.io/badge/bootstrap-%23563D7C.svg?style=for-the-badge&logo=bootstrap&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![jQuery](https://img.shields.io/badge/jquery-%230769AD.svg?style=for-the-badge&logo=jquery&logoColor=white)



</div>

<h1 align="center">Consejo Escolar Sistema de Administracion (beta)</h1>
<p align="center">
Sistema de administracion desarrollado durante las practicas profesionalizantes 
</p>

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
$  cd Consejo-Escolar
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

* HOD /SuperAdmin*
Email: admin@gmail.com
Password: admin

* Staff*
Email: staff@gmail.com
Password: staff

* Estudiante*
Email: student@gmail.com
Password: student

