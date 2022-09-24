# PKDD99_ClasificadorDeClientes_DataScience_Project

## Transacciones bancarias checas anónimas reales, información de la cuenta y registros de préstamos publicados para PKDD'99 Discovery Challenge.

### El conjunto de datos berka, del PKDD Discovery Challenge de 1999 proporciona información sobre los clientes, las cuentas, y las transacciones de un banco Checo.

    El data set se basa en la recopilacion de la informacion de las transacciones bancarias anónimas reales de un banco
    Checo. Está conformado por 8 tablas: Account, Clients, Disposition, Orders, Transactions, Loan, Credit Cards y 
    Demographic data. 
    El data set cuenta con un total de 5369 clientes, 4500 cuentas, 1.056.320 de transacciones, 682 prestamos otorgados
    y la situacion en la que cada uno se encuentra. Cuenta con informacion demografica y de las tarjetas de credito para
    poder complementar la informacion.

    La razón para analizar este Dataset se debe a que se trata de un base de datos muy completa, qué, a pesar de ser 
    de 1999,describe la situación financiera de los clientes de un banco de la misma manera como se encuentran 
    registrados hoy en día. De esta manera, no solo los bancos y sus empleados son los que se beneficiarían de este
    análisis, sino también nosotros mismos, ya que enriquece nuestra experiencia como Data Scientists al ser una base tan
    grande y bien estructurada, y puede ayudar a muchos otros Data Scientist que sigan el mismo camino.
    
### En este proyecto se realizarón las siguiente tareas:
    - Extracción y limpieza de datos. Además, creación de tablas con información relevante, que se unieron a partir de las 
      tablas originales de la base de datos limpia.
    - Exploración de datos en busca de realizar un análisis que nos detalle la información de cada tabla. Se usaron visualizaciones
      para contemplar el comportamiento de los clientes a partir de sus datos, ayudándonos a sacar conclusiones y formar perfiles de 
      cada usuario según su estatus.
    - Entrenamiento de modelos de Machine Learning para clasificación de clientes a partir de su estatus según los préstamos 
      económicos recibidos por parte del banco, con el fin de clasificar a los que concluyeron con éxito sus pagos del préstamo, 
      los que terminaron el lapso para pagar y se convirtieron en deudores, los que tienen un préstamo activo y van al corriente, y 
      los que tienen un préstamo activo y van atrás con sus pagos. Finalmente, predecir que clientes concluirán con éxito sus pagos 
      y cuáles se convertirán en deudores
      
![confusion matrix](https://github.com/Camiloalejan/PKDD99_ClasificadorDeClientes_DataScience_Project/blob/main/images/confusion%20matrix.png)
