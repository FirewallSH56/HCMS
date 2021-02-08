<br />
<p align="center">
  <a href="https://github.com/othneildrew/Best-README-Template">
    <img src="https://i.imgur.com/yFYD2yd.png" alt="Logo">
  </a>

  <h3 align="center">HiddoCMS</h3>

 


<!-- TABLE OF CONTENTS -->

<!-- ABOUT THE PROJECT -->
## Instalacion


* Monta el archivo new.sql en una nueva db

* Solo cambia el nombre y contraseña de la db en /inc/config.god.php

* Cambia la variable host con la ip del Hotel en el archivo hotel.php

* Agrega el archivo apollyon-2.jar dentro de la carpeta del emulador dentro de la carpeta plugins 
para que funcione correctamente la camara

* Recuerda cambiar los links de las rutas de la camara y de las placas de grupos en las swfs en el directorio /gamedata/external_variables.txt en las variables navigator.thumbnail.url_base= , stories.base_url= y camera.store.url= aqui utilizas url ejemplo: http://hiddo.es/camera/ , http://hiddo.es/camera/thumbnails/ , http://images.hiddo.es/c_images/Badgeparts/ y http://images.hiddo.es/c_images/Badgeparts/generated/
una vez hayas hecho todo esto, el hotel deberia ir al 100%


* si tienes errores con la camara, solo cambia el link de la camara en la db en la tabla emulator_settings en las filas camera.url , imager.location.output.camera y imager.location.output.thumbnail OJO debes de cambiarlo por el directorio completo no por url, ejemplo: 
/home/usuario/root/dir/hiddo/camera/ esto es lo mismo al igual en el caso de los thumbnails /home/usuario/root/dir/hiddo/camera/thumbnails/
toda las direcciones deben de terminar con un slash /

* tambien si tienes error con las placas de grupo igual cambia los links en la misma tabla de la db en las filas imager.location.badgeparts y imager.location.output.badges OJO debes de cambiarlo por el directorio completo no por url ejemplo:
/home/usuario/root/dir/hiddo/images.hiddo/c_images/Badgeparts/ esto es lo mismo al igual en la otra variable /home/User1/root/dir/hiddo/images.hiddo/c_images/Badgeparts/generated/
toda las direcciones deben de terminar con un slash /

* Si sigues teniendo errores puedes ver los errores abriendo la consola de las herramientas de desarrollador del navegador cuando estes dentro del client para ver fallos
con F12 o Ctrl + shift + i 
tambien puedes revisar errores de las direcciones de la camara y de los grupos en la consola del mismo emulador


<!-- LICENSE -->
## License

Todo uso no autorizado de este diseño o uso de archivos, sera penalizado
* Todos los derechos reservados &copy; Hiddo 2020



<!-- CONTACT -->
## Contacto

Kevin Huerta - [Facebook](https://www.facebook.com/kevin.huerta.161446/)






<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=flat-square
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=flat-square
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=flat-square
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=flat-square
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=flat-square
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: images/screenshot.png
