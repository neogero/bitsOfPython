
# 00.PythonUtils

## Objetivo

tener documentado como hacer algunas tareas cotidianas en entornos de desarrollo Python.

## 1 - Generar archivo requirements de librerias

Este fichero se utiliza para tener inventariadas las librerias que son usadas en nuestro entorno.

generamos el fichero requirements con las librerias y versiones que están instaladas en nuestro entorno

```bash
pip freeze > requirements.txt
```

Instalamos las librerias que están declaradas en el fichero **requirements.txt**

```bash
pip install -r requirements.txt
```

actualizar las librerías declaradas en el fichero **requirements.txt**

```bash
pip install --upgrade -r requirements.txt
```

----
