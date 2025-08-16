# Creación de una máquina virtal en Azure.

Se crea una máquina virtual para la consigna del desafío en el resource group rg-jelseser.

- En Azure vamos a Crear un recurso y seleccionamos Máquna Virtual.
- Seleccionamos nuestro grupo de recursos y nombramos la máquina virtual.
- En Imagen elegimos Windows Server 2025 Datacenter: Azure Edition - Gen2 y el tamaño predeterminado.
- Elegimos un nombre de usuario y contraseña. En este caso administrador y g6Yj>mZ9}Tja9x]
- En las reglas de Puerto de entrada públicos seleccionamos Ninguno.
- En la sección de discos seleccionar Crear y Adjuntar nuevo disco seleccionando el tamaño adecuado.
- Dentro de Redes ir a Configurar el grupo de seguridad de red, Crear nuevo y revisar que la configuración sea la correcta.
- Avanzamos a Revisar y crear, vemos que todo esté correcto y seleccionamos Crear.
- Conectamos a la máquina virtual con el archivo mv-desafio.rdp o a la IP 74.249.75.79 (mv-desafio-ip)
