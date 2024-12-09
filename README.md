![header](https://cloud.githubusercontent.com/assets/6546265/22174630/785cdf04-dfe3-11e6-8cf4-024e8dc1c051.png)

[![ZenHub](https://raw.githubusercontent.com/ZenHubIO/support/master/zenhub-badge.png)](https://zenhub.com)
[![Build Status](https://travis-ci.org/davidmigloz/go-bees.svg?branch=master)](https://travis-ci.org/davidmigloz/go-bees)
[![codecov](https://codecov.io/gh/davidmigloz/go-bees/branch/master/graph/badge.svg)](https://codecov.io/gh/davidmigloz/go-bees)
[![Code Climate](https://codeclimate.com/github/davidmigloz/go-bees/badges/gpa.svg)](https://codeclimate.com/github/davidmigloz/go-bees)
[![SonarQube](https://sonarqube.com/api/badges/gate?key=go-bees)](https://sonarqube.com/component_measures/?id=go-bees)
[![Dependency Status](https://www.versioneye.com/user/projects/57f7b19e823b88004e06ad33/badge.svg?style=flat-square)](https://www.versioneye.com/user/projects/57f7b19e823b88004e06ad33)
[![Documentation Status](https://readthedocs.org/projects/go-bees/badge/?version=develop)](http://go-bees.readthedocs.io/es/develop/?badge=develop)

## License

Copyright (c) 2016 - 2017 David Miguel Lozano

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
GNU General Public License for more details.

AUTORAS: Sara Abejón Pérez, Carmen Minguela Zamarro y Judith Vinós Salgado.

# GUÍA DE PASOS

Esta práctica consiste en simular el trabajo de crear nuevas actualizaciones de un proyecto. El proceso a seguir es:

1. Crear un fork al repositorio.

2. En Git Kraken, desde el repositorio de Go Bees, se debe buscar el commit del que se quieren subir los cambios.
![image](https://github.com/user-attachments/assets/f57f4fd2-e3a4-4111-a668-7c74e1482d2d)

3. Para posicionarse en ese commit se debe resetear el master a ese commit de manera fuerte.
![image](https://github.com/user-attachments/assets/eac1bc30-1d4c-47a0-85c5-e1ff14e9f64b)

4. Desde el repositorio de la práctica, hay que actualizar la rama master y posicionarse en ella.

5. En Git Hub, desde la issue del commit elegido, se debe crear una rama con el mismo nombre que la tarea.
![image](https://github.com/user-attachments/assets/8d58a6e2-d3e7-4acf-b570-66e75587f3d3)

6. Una vez creada, en Git Kraken hay que posicionar el local en la rama.
![image](https://github.com/user-attachments/assets/2dc6603b-7899-4200-bf26-a1235a95c525)

7. Se deben guardar los cambios realizados en ese commit en Go Bees en la carpeta del repositorio de la práctica. Para ello se copiarán los archivos de la carpeta del repositorio Go Bees a la carpeta del repositorio de la práctica.
![image](https://github.com/user-attachments/assets/3c46d4aa-2ec9-48cb-9110-c58418e930c0)
![image](https://github.com/user-attachments/assets/86fe7130-1a9c-4b65-b1c3-ce0939c139a4)

8. Una vez hechos los cambios, se debe hacer el commit. Para ello se hará "stage all changes" y, tras poner un nombre al commit, se hace el commit de los cambios. Se debe hacer fetch all, pull y push tras el commit.
![image](https://github.com/user-attachments/assets/ad612760-8c9d-498d-9d51-568d24677c51)
![image](https://github.com/user-attachments/assets/c3e9e946-cea0-4eb5-9f81-50dd75e40c55)
![image](https://github.com/user-attachments/assets/1254ef1d-17f9-49b9-8e8e-23d781ec2335)

9. Se debe crear una pull request desde Git Hub de la rama de la tarea a la rama master.
![image](https://github.com/user-attachments/assets/bfce4570-5294-4dd6-9efc-2c54d9a879b7)

10. Después se hace merge de la pull request para pasar los cambios a master.
![image](https://github.com/user-attachments/assets/63a010ae-537c-43cd-a958-9b88b7c5c01a)
![image](https://github.com/user-attachments/assets/f5ead20b-0d3a-44df-8ab0-aaf8f269818f)
![image](https://github.com/user-attachments/assets/6b0056e9-c484-422e-80bf-8dde517e3add)

11. Por último, se actualiza la rama master con Fetch all y se hace pull para actualizar master en local.
![image](https://github.com/user-attachments/assets/87218228-a87f-437a-86ed-1e6f37e6f5bf)
![image](https://github.com/user-attachments/assets/3383d442-0873-4984-a472-60ca199e1a67)
![image](https://github.com/user-attachments/assets/bc0d49b2-3e47-4e09-9d17-c80c928f1e1c)

Todos los commits hechos en esta práctica se pueden ver en esta imagen:
![image](https://github.com/user-attachments/assets/5480a361-f7d6-45ad-8d62-9757aef2b0dc)
![image](https://github.com/user-attachments/assets/37520af1-e714-4836-9fa9-1dc1a9bf5557)

# GIT KRAKEN

1. Grafico obtenido con una captura de pantalla con la lista de commits del repositorio
2. Captura de pantalla del primer commit
image.png
3. Captura de pantalla del último commit
image.png


# GIT HUB

