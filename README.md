var number = parseInt(prompt("Ingrese un número: "));

var resultado;

switch (true) {

    case  (number < 0 || number >= 1000):

        alert("Número no válido");

        break;

    case (number > 0 && number < 10):

        resultado = number * number;

        alert("El resultado es " + resultado);

        break;


    case (number >= 10 && number < 100):

        resultado = number * 2;

        alert("El resultado es " + resultado);

        break;
        // carlos Steven Giraldo
        


    case (number >= 100 && number < 1000):

        resultado = number - 100;

        alert("El resultado es " + resultado);

        break;

    default:

        alert("Número no válido");

        break;

}

//carlos steven giraldo 
