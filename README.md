# React_Js-CoderHouse-Entrega_Final

## # Ecommerce React curso

Este proyecto es un ecommerce orientado al comercio de zapatillas. 
Por lo que la estética de la pagina es sencilla y minimalista, es dinamica y facil de usar.
Se puede interactuar con la vista de categorias, individual de cada productos y a su ves la eleccion del producto por talle y cantidad del producto.
Al finalizar en carrito podes simular una compra con mercado pago usando una api de simulacion.

## Tech

Dillinger uses a number of open source projects to work properly:

- [React] - Librería de Javascript
- [Node.js] - Entorno de ejecución para JavaScript
- [FireBase] - es una solución que permite guardar nuestros productos en forma sencilla dinamica y costo de bajo recursos.
- [Express] - Librería de Node utilizada en la construccion de la API
- [Axios] - utilizada para facilitar una acción en particular en el código JavaScript: hacer llamadas a URL o líneas HTTP
- [Cors] - Nos ayuda a que no nos de algun error en la seguridad entre navegadores
- [MercadoPago] - para integrar la api de prueba de mercadoPago para poder simular una compra usando CheckOut Pro. "ejemplo que use para integrar https://www.mercadopago.com.ar/developers/es/docs/checkout-pro/integrate-checkout-pro#editor_20"


And of course Dillinger itself is open source with a [public repository][dill]
 on GitHub.

## Instalacion 

Si desea correr este proyecto, simplemente clone este repositorio y ejecute npm install luego crea o usas tu credenciales de prueba
de mercadoPago Devolpers (las credenciales son privadas).
Si no tiene cuenta crea una cuenta aqui: https://www.mercadopago.com.ar/developers/es
Despues creada la cuenta acceda al menu tus integraciones para crear tu crendenciales...


Install the dependencies and devDependencies and start the server.

```sh
npm i
```
crea o usas tu credenciales de prueba
de mercadoPago Devolpers (las credenciales son privadas).
Si no tiene cuenta crea una cuenta aqui: https://www.mercadopago.com.ar/developers/es
Despues creada la cuenta acceda al menu tus integraciones para crear tu crendenciales...

Aqui un ejemplo donde tiene que insertar las crendenciales de tu mercado pago:

```sh
En carpeta Payment en payment.jsx hay que insertar tu plubic key... 

  const [preferenceId, setPreferenceId] = useState(null);
  initMercadoPago("Agregar Public key MP");
```
```sh
Y en la carpeta service entrar mercadopago y en el archivo server agregar la credencial de prueba de mercadopago...

    mercadopago.configure({
      access_token: "Inserta Credenciales de Prueba MercadoPago",
    });
```









