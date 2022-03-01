# Dockerized-GildedRose-Azure

Una vez tenemos una máquina a nuestro gusto creada procedemos a asignarle un DNS antes de conectarnos a ella. 

![](images/Screenshot_1.png)
![](images/Screenshot_2.png)
![](images/Screenshot_3.png)

---

## Conexión SSH
![](images/Screenshot_4.png)

Copiamos de esa forma, nos pedirá la contraseña que previamente le hemos dado.

![](images/Screenshot_5.png)

---

## Instalación paquetería, git y docker

![](images/Screenshot_6.png)
![](images/Screenshot_7.png)
![](images/Screenshot_8.png)

Para instalar docker desde el script de bash:

![](images/dockerinstall.png)

Y comprobamos la version:

![](images/dockerinstall2.png)

---

## GildedRose dockerizado

Copiamos el repositorio en cuestión, nos situamos en el mismo directorio y ejecutamos el comando 'docker build -t gildedrose .'
![](images/Screenshot_9.png)

Nos da el visto bueno y comprobamos que se ejecuta correctamente imprimiendo el ejercicio.
![](images/Screenshot_10.png)
