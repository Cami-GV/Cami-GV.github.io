Luego se crear un ambiente virtual, instale los paquetes necesarios:
```sh
python -m pip install -r requirements.txt
```
Los archivos que se editan son los que están en la carpeta templates y stylesheets,
para la estructura y el estilo, respectivamente.
Para construir los html final, ocupamos staticjinja:
```sh
staticjinja build
```
