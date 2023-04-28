# Dimensionament dels servidors

- Dell 1 (Debian 11.6 con entorno gráfico)
  - Servidor empresarial
    - Windows Server 2022 Standard
    - RAM: 4GB
    - DISCO DURO: 100 GB
    - NÚCLEOS: 2
    - 1 tarjeta de red en Adaptador puente a eno1
  
  - Servidor cabina de discos
    - Debian 11.6
    - RAM: 2GB
    - DISCO DURO: 50GB
    - NÚCLEOS:1
    - 1 tarjeta de red en Adaptador puente a eno1
    
  - Servidor de datos 
    - Windows Server 2022 Standard
    - RAM: 4GB
    - DISCO DURO: 50 GB
    - NÚCLEOS: 2
    - 1 tarjeta de red en Adaptador puente a eno1

- Dell 2 (Debian 11.6 con entorno gráfico)
  - Servidor empresarial secundario
    - Windows Server 2022 Standard sin entorno gráfico
    - RAM: 4GB
    - DISCO DURO: 100GB
    - NÚCLEOS:2
    - 1 tarjeta de red en Adaptador puente a eno1
    
  - Servidor de aplicaciones
    - Windows Server 2022 Standard
    - RAM: 6GB
    - DISCO DURO: 100GB
    - NÚCLEOS: 2
    - 1 tarjeta de red en Adaptador puente a eno1
    
  - Servidor de monitorización
    - Debian 11.6 (Zabbix)
    - RAM: 2GB
    - DISCO DURO: 25GB
    - NÚCLEOS: 1
    - 1 tarjeta de red en Adaptador puente a eno1
    
- Dell 3 (8gb) (Debian 11.6 con entorno gráfico)
  - Servidor web Intranet
    - Debian 11.6
    - RAM: 4GB
    - DISCO DURO: 100GB
    - NÚCLEOS:4
    - 1 tarjeta de red en Adaptador puente a eno1
    
  - Servidor web externo
