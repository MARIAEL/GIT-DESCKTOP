# GITHUB-DESKTOP
Buscar en la página de Github el aplicativo [Github Desktop](https://desktop.github.com/) para instalarlo siguiendo el procedimiento habitual.  

Vamos a crear una carpeta para una nueva web.  

Para ello abrimos el aplicativo de github desktop  

![](http://grabilla.com/06119-1bfba69b-e1a6-4fd0-b0bc-4d46a851d2d9.png)  

![](http://grabilla.com/06119-7e4c4255-a504-4ff6-ba5e-39c8b9206b94.png)  

Creamos una carpeta  

![](http://grabilla.com/06119-f477bf13-4e0b-4c45-bac5-0bbbb6255890.png)  

Click en **Create Repository**  

![](http://grabilla.com/06119-d6581fad-2509-4345-ae02-a4b564f94aa8.png)

Si vamos a la carpeta que nos ha creado en C:\Bitnami\meanstack-3.2.1-0\apps veremos que tenemos la nueva carpeta  

![](http://grabilla.com/06119-65dd8878-2b4b-4ef7-b0eb-6e0ac86e6f25.png)

Vamos al terminal de Bitnami y vamos a la carpeta que hemos creado (zapatos)  

![](http://grabilla.com/06119-75ebe3b6-4ab4-436f-801f-2bc549312887.png)  

Ahora instalamos Yeoman (ver pasos en [Instalar Yeoman en Bitnami](https://github.com/MARIAEL/EC2/blob/master/Yeoman.md)) 

Cuando termine  

![](http://grabilla.com/06119-10ed63e9-421a-420f-b59b-0d634663db33.png)

Vamos al entorno gráfico y comprobamos que nos ha instalado todo el contenido necesario.  

![](http://grabilla.com/06119-4cee60c1-3243-4038-afc9-d45701dce358.png)  

También podemos llegar a esta carpeta haciendo btn dr sobre la carpeta zapatos **open in explorer** desde github desktop.  

Ahora pulsaremos la opción **publish** que nos aparece en el margen superior derecho.  

![](http://grabilla.com/06119-0ac61a1f-102c-4c43-8517-4cc3e24c710f.png)

![](http://grabilla.com/06119-cfb735af-da75-4a32-a7bb-3f7cc494e62d.png)  

Si pulsamos en **changes** veremos que nos ha creado la web zapatos.  

![](http://grabilla.com/06119-bd77d8c1-5d6f-4913-9f13-df719314b8ad.png)

Ahora sincronizar  

![](http://grabilla.com/06119-f0f42f54-4e8a-4249-828e-4dddc2d22626.png)  

Veremos en Github que tenemos la nueva carpeta  

![](http://grabilla.com/06119-420d91a1-b3e9-4db4-adf1-f7984c0498b1.png)

El siguiente paso sería arrastrar la carpeta **zapatos** hasta **Sublime text**  

![](http://grabilla.com/06119-2cba50be-d110-47cd-a1ed-e920df42609d.png)  

Ahora arrancamos el servidor desde el terminal de Bitnami y ya podemos empezar a trabajar en nuestro proyecto.  

![](http://grabilla.com/06119-4fb638e6-b25e-4ea8-9489-7d7e792a5b52.png)  

Si cuando lo visualizamos en el navegador vemos que nos falta bootstrap hay que volverlo a instalar    

![](http://grabilla.com/06119-600344c5-8c66-4868-a98a-c5dfdbaef5cc.png)  

Cada vez que queramos trabajar desde otro ordenador, lo primero que hay que hacer es abrir github desktop y clonar la carpeta desde github.

Después tendremos que instalar las carpetas **bower** y **npm**  porque estas carpetas no se suben automáticamente.  

```bash
$zapatos:bower install  

$zapatos:npm install  
```


