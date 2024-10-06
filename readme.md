Proyecto de página web donde se vendan productos tangibles.

First task:
    El archivo home.html deberá tener como mínimo las siguientes secciones:
    1. header
    2. main
    3. footer
    Veamos qué información debemos mostrar en cada una de ellas:
    Header
    Tendremos que maquetar:
    ● Logo
    ● Lugar para poner la barra de búsqueda
    ● Comprá en cuotas y sin tarjeta de crédito
    ● Barra de navegación con las siguientes opciones:
    ○ Ofertas
    ○ Tiendas Oficiales
    ○ Vender
    ○ Ayuda
    ○ Creá tu cuenta
    ○ Ingresá
    ○ Mis compras

    Main (Productos)
    Tendremos dos secciones y en cada una de ellas mostraremos la siguiente información:

    ● Sección: Basado en tu última visita
    imagen de la cafetera
        $6.770 40% OFF
        Cafetera Moulinex
    imagen de MacBook
        $230.000 20% off
        MacBook Pro 2019
    imagen del Samsung Galaxy
        $70.500 10% off
        Samsung Galaxy S10
    imagen del SmartTv
        $23.200 5% off
        SmartTv Samsung 43"
    ● Sección de Ofertas
    imagen de la cafetera
        $6.770 40% off
        Cafetera Moulinex
    imagen de MacBook
        $230.000 20% off
        MacBook Pro 2019
    imagen Samsung
        $70.500 10% off
        Samsung Galaxy S10
    imagen SmarTv
        $23.200 5% off
        SmartTv Samsung 43"

    Footer (Pie de Página)
    Tendrá las siguientes secciones:
    ● Pagá con tarjeta o en efectivo

    Con Mercado Liebre Cash, tenés cuotas sin interés con tarjeta o
    efectivo en puntos de pago. ¡Y siempre es seguro!

    ● Envío gratis desde $ 2.500

    Solo por estar registrad@ en Mercado Liebre tenés envíos gratis en
    miles de productos. Es un beneficio de Mercado Puntos.

    ● Seguridad, de principio a fin

    ¿No te gusta? ¡Devolvelo! En Mercado Liebre, no hay nada que no
    puedas hacer, porque estás siempre protegid@.

Second task:

PASO 1
    Registro de Usuario (register.html ):
        ■ Nombre y apellido
        ■ Nombre de usuari@
        ■ Email
        ■ Fecha de nacimiento
        ■ Domicilio
        ■ Perfil del usuario (consultar a l@s usuari@s si quieren comprar o
        vender)
        ■ Categorías de interés (puede elegir más de una)
            ● Electro
            ● Moda
            ● Hogar
            ● Juguetería
            ● Vida sana
        ■ Foto de usuario
        ■ Contraseña
        ■ Confirmar contraseña
        ■ Botón de enviar que nos lleve a la página principal
        ■ Botón de borrar todos los datos del formulario

PASO 2
    El formulario para ingresar al sitio se mostrará cuando seleccionemos la opción

    . Este deberá contar con la siguiente información:

    Login de Usuario (login.html ):
        ● Nombre de usuari@
        ● Contraseña
        ● Botón de enviar que nos lleve a la página principal

Third Task (TP4):

PASO 1
    Nuestro desafío es aplicar los estilos que nos envía el departamento de diseño a
    cada sección del Header del sitio (navbar, login bar y al search bar). Recordemos
    que por el momento estamos trabajando mobile first.

    Para esto nos facilitó los siguientes estilos generales:
    ● Paleta de colores
    Amarillo: #EAC926;
    Azul: #03264C;
    Celeste: #1259c3;
    Gris oscuro: #666;
    Gris claro: #ebebeb;
    Verde: #39b54a;
    ● Tipografías (Usaremos las fuentes de Google Fonts. )
    Familia: 'Roboto'
    ● Tamaños Tipográficos
    Cuerpos de texto: 12px
    Titulares (Basado en tu última visita/Ofertas): 24px
    Precios: 18px
    Descuentos: 16px
    Descripciones: 16px
    ● Ïconos
    El departamento de diseño usó los íconos de este sitio:
    https://fontawesome.com/icons?d=gallery&m=free

    (Deberemos crearnos una cuenta y seguir las instrucciones de la
    documentación para poder vincular este banco de íconos online)

PASO 2
    Para implementar el último elemento del Header (el menú hamburguesa),
    compartimos una ayuda:

        <div class="burger-menu">
            <i class="fa-solid fa-bars"></i>
        </div>

    Solo faltaría que le coloquemos los estilos necesarios para que se vea igual al mockup de arriba.

PASO 3
    Debemos agregar estilos al Pie de página;
        El contenido de todos los artículos está centrado.
        Los íconos tienen un tamaño de 2em y un margen inferior de separación de 10px

PASO 4
    Agregar estilos a los formularios. Aquí les dejo un ejemplo. No necesariamente debe quedar igual, pero sí que estéticamente esté relacionado con la paleta de colores del sitio.

Fourth Task (TP05):

PASO 1
    El equipo de diseño nos solicita que cumplamos con los siguientes requerimientos
    para cada uno de los productos que se muestran en el sitio:

    ● Debemos centrar la sección main y que ocupe un 90% del ancho de la
    pantalla.
    ● Entre cada artículo hay una separación de 10 píxeles.
    ● Nos piden que manejemos el logo del envío, el precio, el porcentaje de
    descuento y la descripción del artículo como elementos de una caja dentro
    de la caja general del artículo.
    ● Nos piden que la misma tenga un borde superior de 1 píxel, línea sólida y
    color #ebebeb.
    ● Debe tener separado el contenido de sus bordes en 15 píxeles en cada uno
    de sus lados.

PASO 2
    Tomando los requerimientos del equipo de usabilidad, debemos implementar los
    siguientes puntos de corte:

    ● Navegación en tablets (ancho mínimo sugerido 768 px)
    ● Navegación en desktop (ancho mínimo sugerido 1024 px)

    Importante:

    ● Solo en el caso mobile la descripción del artículo no se visualizará.
    ● Agregar box-shadow para los dispositivos tablet o de resoluciones
    superiores. Sugerimos utilizar los siguientes valores:

    box-shadow: 0px 0px 10px rgb(100, 100, 100);

PASO 3
    Para la sección del Header debemos:

    ● Solo para la versión mobile, ocultar el site y el login navbar.
    ● Para las versiones desktop y tablet mostrar
    el site y login navbar, pero ocultar la imagen
    del menú hamburguesa.