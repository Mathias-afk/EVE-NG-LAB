# EVE-NG-LAB
Inter VLAN and Layer-2 / Layer-3 Switch 

Este laboratorio demuestra como configurar enrutamiento entre VLANs utilizando un switch L3 y otro L2

El laboratorio pertenece a hegdepavankumar.

**Topologia**
*En esta topologia el switch capa 3 realiza el enrutamiento entre ambas VLANs

*Vlan 10: IT

*Vlan 20: HR

<img width="749" height="729" alt="TopologiaLAb" src="https://github.com/user-attachments/assets/5b33b1c5-df7e-4256-b677-17a46e79f1b0" />


**Configuracion del Switch Capa 3**


<img width="721" height="806" alt="L3SWconf" src="https://github.com/user-attachments/assets/f260802f-b527-495a-b545-7abea798cbb3" />

Luego para confirmar la configuracion, emitimos el comando show ip interface brief

<img width="785" height="239" alt="shipintbrL3sw" src="https://github.com/user-attachments/assets/3a43a04a-6ea1-4ebb-9358-ba3a19099385" />

**Configuracion Switch Capa 2**

<img width="735" height="1014" alt="L2SWconf" src="https://github.com/user-attachments/assets/14f9d915-054e-4ef8-9ffe-9834c87ce667" />

**Asignacion de IP estatica y pruebas de conectividad en PC 1 (IT).**

<img width="640" height="520" alt="PC1conf tests" src="https://github.com/user-attachments/assets/cb934b8b-486a-4bf2-b485-fb0d45ebaa7c" />

**Asignacion de IP estatica y pruebas de conectividad en PC 2 (HR).**
<img width="612" height="550" alt="PC2conf tests" src="https://github.com/user-attachments/assets/9ad07790-83f1-42c8-a621-e476b199c96d" />


