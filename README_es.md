#### Enlaces rápidos
- [Instrucciones en Ingles/English Instructions](https://github.com/QueloQue/Amazon-Fresh-Whole-Foods-delivery-slot-finder-Multi-OS#quick-links)
- [Descarga e instrucciones](#instalación)
- [Inspiración para esta herramienta](#inspiración-para-esta-herramienta)
- [Preguntas / comentarios / problemas](https://github.com/QueloQue/Amazon-Fresh-Whole-Foods-delivery-slot-finder-Multi-OS/issues)
- [Seguimiento de errores / mejoras](https://github.com/QueloQue/Amazon-Fresh-Whole-Foods-delivery-slot-finder-Multi-OS/projects)
- [Aviso sobre las ventanas de entrega que 'desaparecen'](#aviso-sobre-ventanas-de-entrega-que-desaparecen)
- [Apoyándome / Donaciones](#donaciones)

# Amazon Fresh / Whole Foods Delivery Slot Finder para Windows y Mac
Script automatizado para encontrar ventanas de entrega de entrega disponibles para los servicios de entrega fresca de Amazon.com y Amazon Whole Foods que es compatible con múltiples sistemas operativos y navegadores. Marque esta página para que pueda volver a ella fácilmente.

## Nuevas características
* #### Nuevo soporte - agregado 4/29/20
   * Soporte habilitado para múltiples idiomas y páginas de Amazon de múltiples países.
   * Nota: Solo probado con páginas en los Estados Unidos.

## Instalación
Para que esta herramienta sea lo más compatible posible, está construida sobre (Tampermonkey® por Jan Biniok) el administrador de script de usuario más popular.

1. Instale el administrador de script de usuario de Tampermonkey® en su navegador, solo necesita seguir las instrucciones proporcionadas en Tampermonkey® [aqui](https://www.tampermonkey.net/)

2. Una vez instalado, verá un icono como este en la barra de herramientas de su navegador

![TampermonkeyIcon](https://github.com/QueloQue/Amazon-Fresh-Whole-Foods-delivery-slot-finder-Multi-OS/blob/master/images/AmzCart5.JPG)

3. Ahora necesita instalar el script "Delivery Slot Finder" a través de este enlace [aquí](https://github.com/QueloQue/Amazon-Fresh-Whole-Foods-delivery-slot-finder-Multi-OS/raw/master/kLk-Delivery-Slot-Finder.user.js)

4. Haga clic en "Instalar" cuando vea esta pantalla.
![ScriptInstall](https://github.com/QueloQue/Amazon-Fresh-Whole-Foods-delivery-slot-finder-Multi-OS/blob/master/images/AmzCart6.JPG)

5. Abra una nueva pestaña y visite Amazon.com, vaya a su carrito principal de Amazon haciendo clic en el ícono del carrito en la parte superior derecha de la página.

 ![AmazonCartIcon](https://github.com/QueloQue/Amazon-Fresh-Whole-Foods-delivery-slot-finder-Multi-OS/blob/master/images/AmzCart1.JPG)

6. Verá un nuevo botón en la parte superior de la página. El botón debe estar "Apagado", por ahora déjelo Apagado.
![ScriptIcons](https://github.com/QueloQue/Amazon-Fresh-Whole-Foods-delivery-slot-finder-Multi-OS/blob/master/images/AmzCart2.JPG)

### Ha instalado correctamente el script "Delivery Slot Finder".
### Notas:
El script dejará de ejecutarse si su computadora se queda dormida. Puede ajustar la configuración de "Ahorro de energía" en Preferencias del sistema o descargar [Aplicación cafeína](https://intelliscapesolutions.com/apps/caffeine) para mantener su computadora despierta.




## Cómo funciona
- Una vez que tenga el script instalado, verá un nuevo conjunto de botones en su página de carrito de Amazon y en las páginas relacionadas con el proceso de pago.
- Se recomienda que tenga el script "Delivery Slot Finder" desactivada hasta que su selección de productos esté en su carrito.
- Verá estos íconos en su carrito de Amazon. Puede activar y desactivar el script simplemente haciendo clic en el botón.
- A continuación, le mostraré el proceso para usar el script para encontrar una ventana de entrega disponible para un pedido de Amazon Fresh.


## 1) Llene su carrito de Amazon Fresh con su pedido, cuando esté listo, haga clic en el ícono del carrito en la parte superior derecha de la página.
![AmazonCartIcon](https://github.com/QueloQue/Amazon-Fresh-Whole-Foods-delivery-slot-finder-Multi-OS/blob/master/images/AmzCart1.JPG)



## 2) Verá el nuevo botón en la parte superior de la página. El botón debe estar "Apagado".
![FreshChkOut1](https://github.com/QueloQue/Amazon-Fresh-Whole-Foods-delivery-slot-finder-Multi-OS/blob/master/images/FreshChkOut1.JPG)

## 3) Haga clic en el botón Apagado, esto actualizará la página y el botón ahora dirá "ON" y verá otro botón con "Amazon Fresh". Use este botón para seleccionar si va a realizar el pago de Amazon Fresh o Whole Foods.
![ScriptOnIcons](https://github.com/QueloQue/Amazon-Fresh-Whole-Foods-delivery-slot-finder-Multi-OS/blob/master/images/AmzCart3.JPG)

## 4) En este ejemplo, vamos a realizar el pedido con Amazon Fresh. Haga clic en el botón "Pagar el carrito de Amazon Fresh".
![FreshChkOut2](https://github.com/QueloQue/Amazon-Fresh-Whole-Foods-delivery-slot-finder-Multi-OS/blob/master/images/FreshChkOut2.JPG)



## 5) El script automáticamente hará clic en continuar para la página "Antes de pagar". Esto se hace en caso de que su sesión de pago caduque mientras espera una ranura disponible. Esto permite que el script vuelva a la página "Programe su pedido" para esperar un espacio disponible.
![FreshChkOut3](https://github.com/QueloQue/Amazon-Fresh-Whole-Foods-delivery-slot-finder-Multi-OS/blob/master/images/FreshChkOut3.JPG)



## 6) Debería ir a la página "Programe su pedido". Aquí el script esperará y actualizará automáticamente la página hasta que haya una ventana de entrega disponible.
![FreshChkOut4](https://github.com/QueloQue/Amazon-Fresh-Whole-Foods-delivery-slot-finder-Multi-OS/blob/master/images/FreshChkOut4.JPG)
### Nota: Si resulta que hay un espacio disponible, la alerta comenzará a sonar instantáneamente y puede seleccionar el espacio de entrega y continuar con el pago.



## 7) Debería ver esta barra de cuenta regresiva, muestra el tiempo restante en segundos hasta que la página se actualice automáticamente. Hará esto hasta que se encuentre un espacio.
![FreshChkOut5](https://github.com/QueloQue/Amazon-Fresh-Whole-Foods-delivery-slot-finder-Multi-OS/blob/master/images/FreshChkOut5.JPG)



## 8) Suba el volumen para escuchar la notificación cuando se encuentre una ranura



## 9) Una vez que se encuentra una ventana de entrega, el script generará una alerta y la barra de cuenta regresiva desaparecerá.
![FreshChkOut6](https://github.com/QueloQue/Amazon-Fresh-Whole-Foods-delivery-slot-finder-Multi-OS/blob/master/images/FreshChkOut6.JPG)



## 10) Una vez que se le notifique, seleccione rápidamente un espacio y termine de pagar porque las ventanas de entrega disponibles se enganchan casi instantáneamente.











## Compatibilidad
Para Whole Foods, deberá hacer clic manualmente en "Continuar" para la página "Preferencias de sustitución" que aparece después de la página "Antes de pagar". El script no es totalmente compatible con los pedidos de Whole Foods. Actualmente estoy en la lista de espera para Ordenar de Whole Foods, una vez que obtenga acceso continuaré trabajando en el soporte para ello, la compatibilidad Prime Now puede agregarse al mismo tiempo.

** Antes de usar esta herramienta **, asegúrese de que su página de pago se vea ** exactamente ** como los ejemplos en la sección _Compatible_ a continuación.
Actualmente, esta herramienta solo funciona para algunas regiones porque las páginas de pago de Amazon parecen variar según su ubicación y diseñé la herramienta en función de la página que veo en mi región.
Si su página de pago no se parece a los ejemplos en las secciones _Compatible_ o _Incompatible_ a continuación, esta herramienta aún puede funcionar para usted, pero no hay garantías.

## Aviso sobre ventanas de entrega "que desaparecen"
No hay garantía de que se encuentren ventanas de entrega y / o que las ventanas de entrega funcionen. A menudo, seleccionará una ranura y, cuando haga clic en el botón Continuar, la ranura no estará disponible, cuando eso suceda, la página se actualizará y si todavía hay otra ranura disponible, tendrá otra oportunidad de probar y obtener la ranura disponible. Estas ventanas de entrega que desaparecen son muy comunes y desafortunadamente están en el control de Amazon, no en el mío. Finalmente, una ranura debería funcionar. ¡Te deseo resiliencia y esperanza! Siéntase libre de publicar sus inquietudes en la sección [Problemas](https://github.com/QueloQue/Amazon-Fresh-Whole-Foods-delivery-slot-finder-Multi-OS/issues).

### Compatible
Estas son capturas de pantalla de muestra para enviar a una dirección de Nueva Jersey

#### Amazon Fresh
![Amazon Fresh](https://github.com/QueloQue/Amazon-Fresh-Whole-Foods-delivery-slot-finder-Multi-OS/blob/master/images/FreshChkOut7.JPG)

#### Alimentos integrales
![Whole Foods](https://github.com/QueloQue/Amazon-Fresh-Whole-Foods-delivery-slot-finder-Multi-OS/blob/master/images/FreshChkOut7.JPG)


### Incompatible
#### Amazon Fresh
##### 1.
![Santa Clara, CA](https://i.imgur.com/SyNtrZs.png)
##### 2.
![una ciudad desconocida en CA](https://i.imgur.com/PYrO9Il.jpg)


## Inspiración para esta herramienta
Como la pandemia de Coronavirus 2019 causó un aumento en la demanda de servicios de entrega de comestibles, lo que hace casi imposible encontrar un espacio de entrega abierto. Estaba teniendo dificultades para obtener una ventana de entrega para mi pedido de Amazon Fresh, me encontré con este otro proyecto de GitHub de [ahertel](https://github.com/ahertel/Amazon-Fresh-Whole-Foods-delivery-slot-finder) whish proporciona un script para personas que usan Mac. No tengo una Mac, así que decido hacer una versión del script que sea compatible con las personas que ejecutan Windows o Mac. Mi intención al proporcionar esta herramienta es, ante todo, ayudar a los necesitados (por ejemplo, personas en riesgo, trabajadores de la salud, todas las personas que están tratando de detener la propagación de COVID-19 al quedarse en casa) tienen más facilidad para mantenerse seguros .

## Donaciones
¡Muchas gracias por querer apoyarme! No quiero nada a cambio de esta herramienta; estoy feliz de escuchar todas las historias sobre cómo esto ha ayudado a las personas, especialmente a las personas necesitadas.