<h1>
Comandos de Git
</h1>
<p>
Git es un software de control de versiones. Pensando en la eficiencia, la confiabilidad y compatibilidad del mantenimiento de versiones de aplicaciones cuando estas tienen un gran número de archivos de código fuente.
</p>

<h5>
<b>Configurar Git para Trabajar con Github | SSH Keys</b>
</h5>
<p>Establece el nombre del usuario</p>

`git config --global user.name "Mona Lisa"`

<p>
confirmacion de establecer el nombre de usuario
</p>

`git config --global user.name`

<p>
configuracion de correo electronico
</p>

`git config --global user.email "tu email"`

<p>
confirma la configuracion de correo electronico
</p>

`git config --global user.email`

<h3>
<b>crear una clave ssh</b>
</h3>
La clave ssh te permite subir, clonar y modificar tus archivos en github
<h5>
Antes de generar una clave ssh existente primero verificar
</h5>
<h6>
Comprueba la lista de directorio para ver si ya tiene una clave SSH pública. De manera predeterminada, los nombres de archivo de las claves públicas admitidas para GitHub son uno de los siguientes.

`ls -al ~/.ssh`
</h6>
<ul>
<li>
id_rsa.pub
</li>
<li>
id_ecdsa.pub
</li>
<li>
id_ed25519.pub
</li>
</ul>

<h5>
Generar una nueva clave ssh
</h5>
<p>
Sigue el siguiente link:
https://docs.github.com/es/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent
</p>
