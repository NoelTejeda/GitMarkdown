  ---------------------------------------------
<div id="header" align="center">
<h1 aling="center" >Guia uso para Github y Git <h1/>

  <a href="https://git-scm.com/docs">
    <img src="../GitMarkdown/img/iconGit.png" alt="iconGit"/ width="20%">
  </a>
<a href="https://git-scm.com/docs">
    <img src="../GitMarkdown/img/iconGithub.png" alt="iconGithub"/ width="20%">
  </a>

  
</div>

> [!IMPORTANT] 
> Estamos creando un nuevo repositorio para Todos, actualmente estamos trabajando en él. En este repositorio, queremos recopilar los comandos más usados.
>
> Gracias por mostrar tanto amor a este repositorio. Esperamos que  se convierta en una valiosa herramienta de aprendizaje y colaboración.
> 
-----------

## Tabla de Contenido
1. Introducción
2. Instalación
3. Uso
4. Contribución


## Configuración:
```bash
git config --global user.name "Tu nombre"
git config --global user.email "tu correo"
```

para verificar que nombre de usuario e email se están usando:
```bash
git config --global user.name
git config --global user.email
```

## Verificar los usuarios remotos:

```bash
git remote -v
```
el resultado será por ejemplo:
```bash
origin  https://github.com/NoelTejeda/GitMarkdown.git (fetch)
origin  https://github.com/NoelTejeda/GitMarkdown.git (push)
```
muestra dos rutas, una es el (fetch == pull) y la otra el push; es decir; una que baja y otra que sube, normalmente son las mismas URL


## Agregar Otro usuario remoto:

```bash
 git remote add nombre URL
 git remote add scvMovil http://nteje@192.xx:29/Cda.git
```

## Contributors

Thank you to the people who have already contributed:

  <a href="https://github.com/NoelTejeda/GitMarkdown/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=NoelTejeda/GitMarkdown" />
</a>
</a>

