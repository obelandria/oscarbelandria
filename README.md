
![{36425AFC-893F-4093-A3B3-4EB063DAD617}](https://github.com/user-attachments/assets/b827c30a-466e-4f19-bb8e-2e2a060a0ea8)


Instalar Docker

```bash
curl -fsSL https://get.docker.com/ -o get-docker.sh
sh get-docker.sh
```

-Añadir nuestro usuario al grupo Docker:

```bash
usermod -aG docker ${USER}
```

-Reiniciar sistema:

```bash
reboot
```

-Ejecutar un contenedor de prueba:

```bash
docker run hello-world
```

