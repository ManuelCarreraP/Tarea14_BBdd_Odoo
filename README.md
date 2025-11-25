# Tarea14_BBdd_Odoo
Manuel Carrera Pazó
## CREAR BD
El primer paso será crear nuestra base de datos:
<br>
<br>
<img width="1008" height="510" alt="image" src="https://github.com/user-attachments/assets/19c6c5e8-ef48-4229-b78a-e52c224d5fba" />
<br>
<img width="1010" height="512" alt="image" src="https://github.com/user-attachments/assets/9b6e478e-55a8-4b76-a9ff-da54a8161a5c" />


Ahora instalamos los mofulos de Facturación y Ventas:
<br>
<br>
<img width="1156" height="215" alt="image" src="https://github.com/user-attachments/assets/4419a558-ef56-4a41-a358-b38911735d97" />


## EJERCICIO 1
Sentencia que cree una tabla llamada “EmpresasFCT“ con los siguientes campos:  
- idEmpresa: autonumérico. Este campo será la clave primaria.  
- nombre: Texto con tamaño máximo de 40caracteres. -useChatgpt: booleano, por defecto a true  
- quiereAlumnos: Booleano.  
- numAlumnos: número entero  
- fechaContacto: tipo fecha  
<img width="1006" height="512" alt="image" src="https://github.com/user-attachments/assets/b11775cf-f541-476a-808b-19cd56bfb420" />

## EJERCICIO 2
Inserta 5 registros inventados en la tabla a través de una sentencia SQL
<br>
<br>
<img width="1010" height="513" alt="image" src="https://github.com/user-attachments/assets/4287ac11-c6fa-482b-a634-c7a3220c362f" />

## EJERCICIO 3
Consulta donde se muestren todos los datos de la tabla EmpresasFCT ordenados por fechaContacto
<br>
<br>
<img width="1007" height="512" alt="image" src="https://github.com/user-attachments/assets/a272f4cb-a990-4e41-951c-16cb763e40fe" />

## EJERCICIO 4
Listado de todos los contactos de Odoo (no empresas) con la siguiente información:
- Nombre
- Cuya ciudad NO sea Tracy, y código postal 95304
- Nombre comercial de la empresa
<img width="1007" height="520" alt="image" src="https://github.com/user-attachments/assets/d6e367e9-8b16-47e5-8575-91c784089058" />

## EJERCICIO 5
Listado de empresas proveedoras, que han emitido algún reembolso (facturas rectificativas de proveedor)
- Nombre de la empresa
- Número de factura
- Fecha de la factura-total de factura con impuestos
- Total factura SIN impuestos  

<img width="1004" height="513" alt="image" src="https://github.com/user-attachments/assets/b746eac9-6c2d-4117-9ef1-4c2f1750178f" />

## EJERCICIO 6
Listado de empresas clientes, a las que se les ha emitido más de dos facturas de venta (solo venta) confirmadas, mostrando los siguientes datos:
- Nombre de la empresa
- Número de facturas -total de factura con impuestos
- Total facturado SIN IMPUESTOS
<img width="1069" height="545" alt="image" src="https://github.com/user-attachments/assets/05d3edf6-e504-43f3-8f82-3c994e194ea6" />

## EJERCICIO 7
Sentencia que actualice el correo de los contactos cuyo dominio es @bilbao.example.com a @bilbao.bizkaia.neus:
<br>
<br>
<img width="636" height="421" alt="image" src="https://github.com/user-attachments/assets/ce613032-2c19-45d3-9d10-58508d45a4ed" />



