# Automatas_1
PROGRAMA LINTERCSV

Se definen varias constantes al principio del código, incluyendo el nombre del archivo de la base de datos ‘database.txt’, el nombre del archivo de registro de errores ‘logErrores.txt’, los encabezados esperados en el archivo de la base de datos y los tipos de datos esperados para cada encabezado.

Esta función se utiliza para validar el tipo de dato de una entrada específica. Acepta dos argumentos: ‘dato’, que es el dato a validar, y ‘tipo’, que es el tipo de dato esperado.La función devuelve ‘true’ si el tipo de dato coincide con el esperado, y ‘false’ en caso contrario.
El código verifica si el archivo ‘database.txt’ existe. Si no existe, lo crea.
El código lee el archivo ‘database.txt’ y realiza varias validaciones en los datos:

-- Valida que la cantidad de columnas en cada fila coincida con la cantidad de encabezados definidos.
-- Valida que todas las columnas tengan datos.
-- Valida que los tipos de datos correspondan a los tipos esperados para cada columna.

Si se encuentran errores durante la validación, se registran en un archivo llamado ‘logErrores.txt’. Si no se encuentran errores, se imprime un mensaje indicando que no se registraron errores.
