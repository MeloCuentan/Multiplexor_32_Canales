# Multiplexor_32_Canales

Este multiplexor conmuta cualquiera de los canales (S1 - S32) con el pin común (D) seleccionandolo con los pines A0, A1, A2, A3 y A4.
En la parte inferior de la placa está la posibilidad de conectar una resistencia que haga de pulldown o un condensador en caso de usarse como entradas analógicas para que haga de filtro.
El margen de voltaje de funcionamiento es de 3V a 5V.

Los pines CS, WR y EN son de control.

  - CS: "Chip Select". Se utiliza para hablitar/deshabilitar el chip. Cuando está en un estado bajo, el chip está habilitado y se puede utilizar
  - WR: "Write". Se utilizar para indicar al chip que se va a escribir en él. Cuando se envía una señal de estado bajo, el chip se prepara para recibir los datos.
  - EN_ "Enable". Se utiliza par ahabilitar o desabilitar los canales del conmutador. Cuando está bajo, los canales están habilitados.
