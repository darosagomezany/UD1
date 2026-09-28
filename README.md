# Documentación UD1 Lenguajes de Marcas

## Introducción a Lenguajes de Marcas

### Definición
Un lenguaje de marcas es un modo de codificar un documento que, junto con el texto, incorpora etiquetas o anotaciones que contienen información adicional sobre la estructura del texto o su presentación.

Como administradores de sistemas, estos lenguajes nos servirán tanto para estructurar páginas web como para guardar configuraciones de servidores y exportar/importar datos entre aplicaciones.

#### Calificación de Lenguajes de Marcas

|Tipo|Uso|Ejemplos|
|----|---|--------|
|Presentación|Dar formato a documentos de texto|HTML, CSS|
|Intercambio de información|Almacenar información de forma ordenada|XLM, RSS|
|Documentación|Documentar proyectos|Markdow, WikiTex|

## Instalación y configuración del entorno

1. Instalamos [VS Code](https://www.bing.com/ck/a?!&&p=e58ecb4aff7399047bc8013e63f1efd327ecc5546e7d5d2b82d6ca2f331c2e5bJmltdHM9MTc4OTUxNjgwMA&ptn=3&ver=2&hsh=4&fclid=057a018e-de0d-6206-1295-165edf1d6366&psq=vs+code&u=a1aHR0cHM6Ly9jb2RlLnZpc3VhbHN0dWRpby5jb20vZG93bmxvYWQ)

2. Instalamos plugins

|Nombre|Imagen|Uso|
|------|------|---|
|[HTML CSS Support]()|![HTMLCSS](https://ecmel.gallerycdn.vsassets.io/extensions/ecmel/vscode-html-css/2.0.14/1770897391434/Microsoft.VisualStudio.Services.Icons.Default)|Ayuda a _autocompletar atributos de ID y clases_ en tus archivos __HTML__ basados en tus hojas de estilos __CSS__.|
|[Markdown all in one](https://markdown-all-in-one.github.io/docs/guide/)|![Markdown](https://www.markdownlang.com/static/images/logo.png)|Mejora la edición de Markdown con funciones como _atajos de teclado, índice y vista previa automática_. Puedes habilitar y controlar fácilmente el comportamiento de la *__vista previa__* para ver la visualización en __tiempo real__ de tus archivos .md.|
|[Live Preview](https://github.com/microsoft/vscode-livepreview)|![Live Preview](https://ms-vscode.gallerycdn.vsassets.io/extensions/ms-vscode/live-server/0.5.2023121201/1702372495732/Microsoft.VisualStudio.Services.Icons.Default)|Permite __visualizar en tiempo real__ los cambios realizados en archivos _HTML, CSS y JavaScript directamente en el navegador_.|
|[XML](https://en.wikipedia.org/wiki/XML)|![XML](https://cdn-icons-png.flaticon.com/512/9704/9704800.png)|_eXtensible Markup Language_ es un lenguaje de marcado diseñado para __almacenar__ y __transportar datos__. A diferencia del HTML, que cuenta con etiquetas predefinidas, el XML te permite definir tus propias etiquetas adaptadas a tus necesidades específicas. Esta flexibilidad convierte al XML en una herramienta poderosa para el almacenamiento, la búsqueda y el intercambio de datos.|

3. Instalamos git.   
Actualizamos la lista de paquetes del sistema e instalamos Git mediante apt:
```sudo apt update
sudo apt install git -y
```   
    git --version (comprobamos que se ha instalado correctamente viendo la versión)

    git config --global user.name "NombreAlumno"

    git config --global user.email "alumno@centro.edu"
    
    git config --list (podemos revisar si la configuración se ha guardado bien)

- Creación y vinculación del repositorio en local
    
    git clone https://github.com/darosagomezany/UD1.git
    cd UD1

- Subida del proyecto a GitHub
```bash
   git clone [https://github.com/darosagomezany/UD1.git](https://github.com/darosagomezany/UD1.git)
   cd UD1

    git add .

    git commit -m "Primer commit"

    git push origin main
