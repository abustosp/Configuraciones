# Crear conexiones SSH 

para que no pida contraseña cada vez que se conecta a un servidor, se puede crear una conexión SSH automática.


1. En maquina cliente:

    ```ssh-keygen```

2. Pegar la clave pública en el servidor, hay 2 alternativas:

    - Manual : pegarla en ```~/.ssh/id_rsa.pub```

    - Automática : ```ssh-copy-id usuario@servidor -p puerto```
