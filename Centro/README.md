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
| --- | --- | --- | --- |
| SwEdPrincipal | VLAN 33 | 148.60.128.1 | /24 |
| MulticapaEdPrincipal | VLAN 33 | 148.60.128.2 | /24 |
| MulticapaEdAnexo | VLAN 33 | 148.60.128.3 | /24 |
| SwEdAnexo | VLAN 33 | 148.60.128.4 | /24 |