![image](https://user-images.githubusercontent.com/122388100/215290935-140f0469-35bf-4d55-8583-bf62653bd839.png)


# Introduction - Introduccion - EN/ES

This are my actual dotfiles for [i3wm](https://github.com/Airblader/i3), and I'm currently working on another setup for Suckless DWM. I hope you'll enjoy it.

Estos son mis dotfiles para mi configuracion de [i3wm](https://github.com/Airblader/i3), actualmente estoy trabajando en otra configuracion, pero esta vez, para DWM de Suckless. Espero que te guste.

## Installation Process / Instalacion

There are some dependencies needed to get everything working fine. These are for any distro which uses DNF as package manager, but you can search similar packages for yours.

Hay algunas dependencias necesarias para lograr que todo funcione correctamente. Estas son especificamente para cualquier distribucion que utilice DNF como gestor de paquetes. Caso contrario, podes buscar alternativas que correspondan a tu disposicion.

```bash
/* Fedora, (paste each line into terminal and follow the instructions)*/

sudo dnf update

sudo dnf upgrade

sudo dnf install fontawesome5-fonts-all kitty rofi dejavu-fonts-all powerline-fonts i3-gaps python3-pip
```
Check if ```pip --version``` works. If not, restart your system. After this, run:

Chequea que ```pip --version``` funcione. En caso de que no, proba reiniciando tu sistema. Luego de esto, corre:
```
pip install --user bumblebee-status
```
## Usage / Uso
Clone the repo and move each file to its correct directory.

Clona el repositorio y move cada archivo a su directorio correspondiente
```
git clone https://github.com/ivmask/i3-gruvbox-dotfiles
cd i3-gruvbox-dotfiles/
mv -r .config/ ~/

// (or just copy the content of the files and paste into your existent ones)
// (o solo copia el contenido de los archivos dentro de tus ya existentes)
```


## License

[MIT](https://choosealicense.com/licenses/mit/)
