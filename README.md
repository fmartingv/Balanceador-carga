# Balanceador-carga

Vamos a hacer un balanceador de carga con docker.

  1. Para ello tendremos una carpeta donde trabajaremos con los diferentes archivos:

     -3 index.html que seran nuestras paginas a balancear, estas seran muy simples.

  ![image](https://github.com/fmartingv/Balanceador-carga/assets/120713266/916fecda-fe9d-40fe-bd6f-42b7674d7d1e)


  -default.conf donde pondremos las direcciones y otra informacion.

   ![image](https://github.com/fmartingv/Balanceador-carga/assets/120713266/bc8a5111-96a1-4aa9-b745-ca8cd78547d2)


  2. Ejecutamos los 3 index por separado:

  ![image](https://github.com/fmartingv/Balanceador-carga/assets/120713266/31072907-7f71-41a6-a1c4-27ebdab99af1)

  3. AHora el conf que creamos antes:

  ![image](https://github.com/fmartingv/Balanceador-carga/assets/120713266/1d60c22c-7687-4a70-892c-85b0e360f922)

  4. Ahora accedemos a http://localhost:8085 y cuando recargamos balancea entre las diferentes paginas:

     ![image](https://github.com/fmartingv/Balanceador-carga/assets/120713266/2e775a54-41af-43b9-b378-da1410a6388d)
