BanDDos - Herramienta avanzada para ataques DDoS
Una potente y sofisticada herramienta para ataques de denegación de servicio distribuido (DDoS) desarrollada con Node.js, que incluye múltiples métodos de ataque y compatibilidad con proxy.

Características
Métodos de ataque de capa 7:

HTTP-FLOOD: Inunda el objetivo con solicitudes HTTP
BYPASS: Bypass avanzado para protecciones comunes
GET/POST: Inundación de solicitudes GET/POST estándar
STRESS: Solicitudes de carga pesada
SOCKET: Inundación de conexiones WebSocket
TLS: Inundación de conexiones TLS/SSL
SLOW: Implementación del ataque Slowloris
NULL: Ataques de agente de usuario nulo
COOKIE: Ataques basados ​​en cookies
BOT: Simula tráfico de bots
XMLRPC: Inundación de pingback XML-RPC
Métodos de ataque de capa 4

TCP: Ataques de inundación TCP SYN
UDP: Inundación de paquetes UDP
SYN: Inundación de paquetes SYN
VSE: Inundación de consultas del motor de origen de Valve
MINECRAFT: Ataques al servidor de Minecraft
MCBOT: Ataques de bots de Minecraft
CONNECTION: Inundación de conexiones
Características principales
Motor de ataque multihilo
Compatibilidad con proxy (HTTP, SOCKS4, SOCKS5)
Proxy automático Extracción y comprobación de datos
Parámetros de solicitud personalizables
Rotación de agente de usuario integrada
Gestión de cookies
Suplantación avanzada de encabezados
Limitación de velocidad y controles de tiempo de espera
Estadísticas de ataques en tiempo real
Detalles técnicos
Desarrollado en Node.js para un alto rendimiento
Utiliza sockets TCP/UDP nativos
Implementa HTTP/1.1 y HTTP/2
Compatible con conexiones SSL/TLS
Implementación de cadena de proxy
Implementaciones de protocolos personalizados
Gestión eficiente de memoria
Operaciones de E/S asíncronas
Instalación
# Clonar repositorio
git clone https://github.com/The-DiosBot-MD/DDOS.git

# Instalar dependencias
npm install

# Configurar ajustes
cp config.example.json config.json
Uso
# Ataque de capa 7
npm start <url> <method> <threads> <duration>

# Ataque de capa 4
npm start <ip:port> <method> <threads> <duración>

# Con proxy
npm start <destino> <método> <hilos> <duración> <archivo proxy>
Comando
Métodos de capa 7
HTTP_FLOOD: npm start <url> HTTP_FLOOD <hilos> <duración>
CFB: npm start <url> CFB <hilos> <duración>
BYPASS: npm start <url> BYPASS <hilos> <duración>
GET: npm start <url> GET <hilos> <duración>
POST: npm start <url> POST <hilos> <duración>
OVH: npm start <url> OVH <hilos> <duración>
STRESS: npm start <url> STRESS <hilos> <duración>
DYN: npm start <url> DYN <hilos> <duración>
SLOW: npm start <url> SLOW <hilos> <duración>
HEAD: npm start <url> HEAD <hilos> <duración>
NULL: npm start <url> NULL <hilos> <duración>
COOKIE: npm start <url> COOKIE <hilos> <duración>
PPS: npm start <url> PPS <hilos> <duración>
EVEN: npm start <url> EVEN <hilos> <duración>
SOCKET_FLOOD: npm start <url> SOCKET_FLOOD <hilos> <duración>
TLS_FLOOD: npm start <url> TLS_FLOOD <hilos> <duración>
XMLRPC: npm start <url> XMLRPC <hilos> <duración>
Métodos de Capa 4
TCP_FLOOD: npm start <ip:puerto> TCP_FLOOD <hilos> <duración>
UDP_FLOOD: npm start <ip:puerto> UDP_FLOOD <hilos> <duración>
SYN_FLOOD: npm start <ip:puerto> SYN_FLOOD <hilos> <duración>
VSE: npm start <ip:puerto> VSE <hilos> <duración>
MINECRAFT: npm start <ip:puerto> MINECRAFT <hilos> <duración>
MCBOT: npm start <ip:puerto> MCBOT <hilos> <duración>
Con proxy
Añadir proxy de archivo al comando final:

npm start <objetivo> <método> <hilos> <duración> <archivo-proxy>
Configuración
Edite config.json para configurar:

Parámetros de ataque predeterminados
Origenes y tipos de proxy
Listas de agentes de usuario
Encabezados de solicitud
Tiempos de espera de conexión
Opciones de depuración
Descargo de responsabilidad
Esta herramienta es Solo para fines educativos y de prueba. Los usuarios asumen toda la responsabilidad por cualquier mal uso o daño causado. Los desarrolladores no asumen ninguna responsabilidad.

Contribución
Bifurcación del repositorio
Crear rama de funciones
Confirmar cambios
Subir a rama
Crear solicitud de extracción
Autor
Nombre: AdrianOficial
Github: [github.com/The-DiosBot-MD]
Agradecimientos
Proyecto original MHDDoS
Comunidad Node.js
Todos los colaboradores: Esta herramienta demuestra conceptos avanzados de redes y debe usarse de forma responsable únicamente para pruebas autorizadas.
