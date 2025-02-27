# Hyprland-en-arch-linux
en este repositorio habra una breve explicacion de como ponerte hyprland en arch linux

Para ponerte hyprland en arch linux sigue estos pasos:
  
1: configurar arch pero sin interfaz grafica, puedes seguir los pasos de este video:

https://www.youtube.com/watch?v=2rh4Ik4WQZA

!SIGUE LOS PASOS HASTA LA PARTE DONDE SE VA A PONER INTERFAZ, CUANDO SE VAYA A CONFIGURAR LA INTERFAZ HASTA AHI DEBES PARAR!

o si vas a hacerlo en maquina virtual

https://www.youtube.com/watch?v=F-4_U0G6Ha0





!ESTO ↓ LO DEBES DE EJECUTAR COMO USUARIO NORMAL , AL EJECUTAR EL install.sh TE PEDIRA CONTRASEÑA Y SI ESTA BIEN PERO NO LO EJECUTES COMO ROOT!

2: despues de tener arch linux configurado sin interfaz, ahora sigue estos pasos:

2.1: pacman -S --needed base-devel git ( si te sale algo como que ya lo tienes, no hay problema)

2.2: git clone --depth 1 https://github.com/prasanthrangan/hyprdots ~/HyDE (si tienes problemas con el ~ puedes poner /home/(aqui_pones_tu_usuario)/HyDE)

2.3: cd ~/HyDE/Scripts (o tambien cd /home/(tu_usuario)/HyDE/Scripts)

2.4: ./install.sh

Y listo tendrias hyprland en tu arch linux
