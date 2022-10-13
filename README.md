# Manual para activar el servidor Handle

 1. Ingresar por ssh al servidor con las credenciales asignadas.

    ![Ingresar ssh](https://sandbox.colmex.mx/~ecisneros/manual_handle/1.png)

 2. Colocarse en la carpeta /hs/handle-9.3.0

    `> cd /hs/handle-9.3.0 `

    ![Ingresar ssh](https://sandbox.colmex.mx/~ecisneros/manual_handle/2.png)

 3. Indicarle a Handle que se va a iniciar el servicio con el camando 

    `> bin/hdl-server /hs/svr_1/ `

    ![Ingresar ssh](https://sandbox.colmex.mx/~ecisneros/manual_handle/3.png)

 4. El servidor nos pedira la frase secreta (passphrase): 

    *Enter the passphrase for this server's authentication private key:*

    ![Ingresar ssh](https://sandbox.colmex.mx/~ecisneros/manual_handle/4.png)

 5. Colocamos la frase que en nuestro servidor es: bdcvcolmex 

    ![Ingresar ssh](https://sandbox.colmex.mx/~ecisneros/manual_handle/5.png)

 6. Una vez iniciado el servidor para dejarlo ejecutando en segundo plano, presionamos:

    `ctrl + z`

    ![Ingresar ssh](https://sandbox.colmex.mx/~ecisneros/manual_handle/6.png)

 7. Finalmente una vez que estamos nuevamente en la linea de comandos del sistema operativo escribimos “bg” y presionamos “enter”. 

    `>bg `
    
    ![Ingresar ssh](https://sandbox.colmex.mx/~ecisneros/manual_handle/7.png)
