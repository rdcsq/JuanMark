# Centro

- Red: 148.60.128.0/18

| VLANs | Nombre | CIDR |
| --- | --- | --- |
| 33 | gestionti | 148.60.128.0/24 | 
| 34 | gestionwlan | 148.60.129.0/24 |
| 35 | ventaswlan | 148.60.130.0/24 | 
| 36 | compras | 148.60.131.0/24 | 
| 37 | practicantewlan | 148.60.132.0/24 |

| Dispositivo | Interfaz | Dirección IP | Prefijo |
| :---- | :---- | :---- | :---- |
| Centro | G0/0.33 | 148.60.128.1 | /24 |
|  | G0/0.34 | 148.60.129.1 | /24 |
|  | G0/0.35 | 148.60.130.1 | /24 |
|  | G0/0.36 | 148.60.131.1 | /24 |
|  | G0/0.37 | 148.60.132.1 | /24 |
|  | G0/1 | 148.60.160.1 | /30 |
| MulticapaEdAnexo | VLAN 33 | 148.60.128.3 | /24 |
| MulticapaEdPrincipal | VLAN 33 | 148.60.128.2 | /24 |
| SwEdAnexo | VLAN 33 | 148.60.128.4 | /24 |
| SwEdPrincipal | VLAN 33 | 148.60.128.1 | /24 |
| WLCEdAnexo | Management | 148.60.129.2 | /24 |
| APEdAnexo | G0 | DHCP |  |
| APEdPrincipal | G0 | DHCP |  |
| Host Ventas | Wireless0 | DHCP |  |
| Host Ventas 2 | Wireless0 | DHCP |  |
| Host Practicante | Wireless0 | DHCP |  |
| Host Practicante 2 | Wireless0 | DHCP |  |
| Usuario | F0 | DHCP |  |
| Usuario2 | F0 | DHCP |  |
| Usuario3 | F0 | DHCP |  |
| Staff IT | F0 | DHCP |  |
| Staff IT 2 | F0 | DHCP |  |