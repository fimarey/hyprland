# Hyprland-en-arch-linux
en este repositorio habra una breve explicacion de como ponerte hyprland en arch linux

Para ponerte hyprland en arch linux sigue estos pasos:
  
1: configurar arch pero sin interfaz grafica, puedes seguir los pasos de este video:

https://www.youtube.com/watch?v=2rh4Ik4WQZA

!SIGUE LOS PASOS HASTA LA PARTE DONDE SE VA A PONER INTERFAZ, CUANDO SE VAYA A CONFIGURAR LA INTERFAZ HASTA AHI DEBES PARAR!

o si vas a hacerlo en dual bot

https://www.youtube.com/watch?v=F-4_U0G6Ha0



Recomendaciones:

al tener todo instalado y salir del live usb les recomiendo conectarse a internet por medio de networkmanager, ya que el script usa networkmanger y si usas iwd te dara error

!ESTO ↓ LO DEBES DE EJECUTAR COMO USUARIO NORMAL , AL EJECUTAR EL install.sh TE PEDIRA CONTRASEÑA Y SI ESTA BIEN PERO NO LO EJECUTES COMO ROOT!

2: despues de tener arch linux configurado sin interfaz, ahora sigue estos pasos:

2.1: pacman -S --needed base-devel git ( si te sale algo como que ya lo tienes, no hay problema)

!!CLONARLO EN EL DIRECTORIO HOME!!

2.2: git clone --depth 1 https://github.com/HyDE-Project/HyDE ~/HyDE

2.3: cd ~/HyDE/Scripts

2.4: ./install.sh

2.5: una vez en el panel de login, debes reiniciar

Y listo tendrias hyprland en tu arch linux
