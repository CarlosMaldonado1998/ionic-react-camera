# ionic-react-camera

En este ejercicio se tiene una aplicación movil realizada con React y Ionic. 

Para realizar este ejercicio se ha seguido la guía que nos proporciona Ionic React como es en el siguiente enlace. 
https://ionicframework.com/docs/react/your-first-app

Con el cual hemos utilizado 
  
  - @capacitor/camara
  - @capacitor/storage
  - @capacitor/filesystem

En la aplicación de camara se puede tomar fotos y guardarlas en el dispositivo. Esta muestra una lista con las fotos tomadas. 

![alt text](https://raw.githubusercontent.com/CarlosMaldonado1998/ionic-react-camera/master/Images/app.png)

Para tomar una fotografía se hace clic en el simbolo de la camara, la cual abre la aplicación de camara del dispositivo, posterior a ello tomamos la foto. 

![alt text](https://raw.githubusercontent.com/CarlosMaldonado1998/ionic-react-camera/master/Images/foto.png)

En el listado de fotos de la aplicación podremos dar clic sobre cada una de ellas para eliminar la foto si el usuairo lo desea. 

![alt text](https://raw.githubusercontent.com/CarlosMaldonado1998/ionic-react-camera/master/Images/delete.png)

Para generar el archivo apk podremos ejecutar los siguientes comandos:

  - npx cap run android

El cual nos va generar el siguiente archivo. 


La aplicación corriendo en el emulador de Android Studio. 

![alt text](https://raw.githubusercontent.com/CarlosMaldonado1998/ionic-react-camera/master/Images/simulador.png)
