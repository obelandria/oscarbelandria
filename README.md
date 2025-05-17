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
![{4BE9B7A3-1848-4E1C-8ABA-DA80D96C8647}](https://github.com/user-attachments/assets/b22347ed-d999-4c84-a001-19fd58ffb240)
