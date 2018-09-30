# railsAutenticarUsuarios

Trackable - Permite saber desde que ip esta conectandose el usuario
Expirable - Pide que vuelvas a iniciar sesion luego de un tiempo al reconectarse
Timeoutable - Cierra la sesión leugo de un tiempo de inactividad
Validatable - Permite validar cuantas y correos en el sistema
Lockable - Es una función de seguridad que en caso de detectar algo inusual, blockea la cuenta
Omniauthable - Las sesiones pueden utilizar omniauth 
              omniauth . Es una gema que brinda un sistema flexible de autentificación
              Ej, iniciar sesision con twitter, facebook, instagram
              Soporta varios proveedores , y permite conectarnos con aplicaciones de terceros que soportan protocolo Oauth.
              
              Oauth (Open authorization): Es un protocolo que permite flujos simples de autentificacion para sitios web.

Agregar gema de Devise
Abre el gemfile y escribe

gem 'devise'

luego corre bundle install
bundle install

Recuerda ademas reiniciar el servidor!

2. Instala devise en la app
Corre el siguiente comando

rails g devise:install
