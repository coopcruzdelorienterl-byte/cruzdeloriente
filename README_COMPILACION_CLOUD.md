# Compilar APK sin Android Studio

FORMA SENCILLA DE OBTENER EL APK SIN ANDROID STUDIO
Cruz del Oriente – V17 aprobada

Este paquete incluye el proyecto Android y una receta de compilación automática en GitHub Actions.
No tienes que instalar Android Studio, Java, Gradle ni Android SDK en tu computadora.

QUÉ NECESITAS
- Una cuenta gratuita de GitHub (si no tienes, puedes crearla en https://github.com).
- Un navegador en tu computadora.

PASOS

1. CREAR UN REPOSITORIO PRIVADO
- Entra a https://github.com/new
- En Repository name escribe: cruz-oriente-nominacion
- Selecciona Private.
- Pulsa Create repository.

2. SUBIR LOS ARCHIVOS DEL PROYECTO
- Descomprime el ZIP completo en tu computadora.
- En el repositorio nuevo, pulsa Add file > Upload files.
- Abre la carpeta CruzDelOriente_Android_APK_Project.
- Selecciona y arrastra TODO lo que está dentro de esa carpeta al área de carga de GitHub.
- IMPORTANTE: también debes subir la carpeta oculta .github, que contiene build-apk.yml. Si no la ves, activa “mostrar archivos ocultos” en el explorador de Windows.
- Pulsa Commit changes.

3. INICIAR LA COMPILACIÓN AUTOMÁTICA
- En el repositorio, abre la pestaña Actions.
- Selecciona “Build APK - Cruz del Oriente”.
- Pulsa Run workflow y luego el botón verde Run workflow.
- Espera a que termine con una marca verde.

4. DESCARGAR EL APK
- Abre la ejecución terminada.
- Baja hasta Artifacts.
- Pulsa Solicitud-Nominacion-Cruz-del-Oriente-APK.
- Se descargará un ZIP. Descomprímelo para obtener app-debug.apk.

5. INSTALAR EN ANDROID
- Envía app-debug.apk a tu teléfono.
- Abre el archivo APK en el teléfono.
- Si Android lo solicita, permite “Instalar aplicaciones desconocidas” para la aplicación desde la que abriste el archivo.
- Pulsa Instalar.

NOTAS
- Este flujo genera un APK DEBUG para pruebas internas, no una versión publicada en Play Store.
- Mantén el repositorio en Private: contiene el código de tu aplicación.
- No compartas contraseñas, tokens ni claves de firma.
- La compilación se ejecuta en los servidores de GitHub; no necesitas Android Studio.
- La numeración correlativa sigue siendo local al dispositivo.

DISEÑO Y FUNCIONES
Se empaqueta localmente la interfaz V17 aprobada, sin depender de una página web externa. Conserva el sello, formulario, validaciones, numeración local, comprobante PNG, guardar imagen y compartir mediante el selector nativo de Android.
