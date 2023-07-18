# n a n

Añadir Devise a tu Gemfile: Debes agregar la línea "gem 'devise'" a tu Gemfile.

Instalar la gema Devise: Ejecuta el comando "bundle install" en tu terminal para instalar la gema Devise.

Configurar Devise: Después de instalar Devise, debes configurarlo. Ejecuta "rails generate devise:install" en tu terminal.

Estos son los pasos básicos para instalar y configurar Devise. Asegúrate de seguir todas las instrucciones que aparecen después de ejecutar "rails generate devise:install", como configurar el correo de confirmación y agregar los mensajes de alerta y notificación a tu aplicación.

Después de hacer esto, debes generar tu modelo de usuario (o agregar Devise a un modelo existente) con "rails generate devise MODEL", donde MODEL es el nombre de tu modelo de usuario.

Luego, migra tu base de datos con "rails db:migrate". Ahora Devise debería estar instalado y configurado correctamente en tu aplicación.
