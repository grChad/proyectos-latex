<h1 align="center">Proyectos personales en LaTex</h1>

En este repositorio agregare proyectos y trabajos de distintos temas, pero todos con **_LaTex_**.

## instalación

* sudo su
* apt-get update
* apt-get install texlive-full
   - Esto podria tardar como media hora o mas.
* apt-get install zathura latexmk
   - zathura es un visualizador de pdf y latexmk es para la sintaxys y manejo de errores(creo).
* xdg-mime query default application/pdf
   - Es para ver el visualizador por default de pdf
* xdg-mime default zathura.desktop application/pdf
   - Para poner por default a zathura como visualizador de pdf.
* mkdir /.config/latexmk
   - Creamos un directorio vacio dentro de /.config
* cd /.config/latexmk
   - Ingresamos al directorio creado
* touch latexmkrc
* $pdf_previewer = 'zathura';
   - Escribimos y guardamos esta informacion dentro del archivo recien creado.
* chown gabriel:gabriel -R latexmk
   - Asignamos los permisos de usuario y grupo gabriel como admin
* cd /root
* cd .config/
* mkdir latexmk
* cd !$
* ln -s -f /home/gabriel/.config/latexmk/latexmkrc latexmkrc
   - Esto es para crear un enlace simbolico desde el archivo home/gabriel/.config/latexmk/latexmkrc.

## Proyectos

- [ ] Documentación de Canvas(**JavaScript**), lo puedes encontrar [aquí](./doc-canvas/).
- [ ] Documentación de _Lua_ 5.4 en Español, se encuentra [aqui](./lua-5.4-espanish/).
- Documentación de los Hooks de _ReactJs_:
  - [x] Hook **UseRef()**, esta completo y lo tienes [aqui](./hooks-react/useRef/).
