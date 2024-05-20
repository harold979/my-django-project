## 1- Abre la terminal y clona el repositorio:

```bash

git clone https://github.com/harold979/my-django-project.git

```

## 2- Navega al directorio del proyecto:

```bash

cd my-django-project

```
## 3- Crea un entorno virtual y actívalo:

- En Windows
```
bash
python -m venv myenv
myenv\Scripts\activate
```

- En macOS/Linux:

```
python -m venv myenv
source myenv/bin/activate
```
## 4- Instala las dependencias del proyecto:

```
pip install django
```
## 5- Ejecuta las migraciones (en caso de que las haya):
```
python manage.py migrate
```

## 6- Ejecuta el servidor de desarrollo:

```
python manage.py runserver
```




