# ejerciciosPhp
<?php
//Crear una funcion que muestre si un numero es par o impar
function numero($num)
{
    if($num%2 == 0)
    {
        echo "El numero ".$num." es par";
    }
    else
    {
        echo "El numero ".$num." es impar";
    }
}

numero(6);
echo "<br>";
//crear una funcion que determine el mayor de dos numeros
function mayor($num1, $num2)
{
    if($num1 > $num2)
    {
        echo "El numero ".$num1." es mayor a ".$num2;
    }
    else
    {
        echo "El numero ".$num2." es mayor a ".$num1;
    }
}

mayor(10,4);
echo "<br>";
//Crear una funcion para calcular el cuadrado de un numero
function cuadrado($numero)
{
    $respuesta = $numero*$numero;
    echo "El cuadrado de ".$numero." es ".$respuesta;
}
cuadrado(8);
?>
