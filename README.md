# Guia  2  NO SE COPIEN VAGOS

### **Alumno:** Juan Baader

### **Año:** 2023

### **Curso:** 3B TIC

### **Profesor/a** Luu Parrondo

[Link a Github](https://github.com/juanpanpanyz/Guia2)

<br>

## **Primer Ejercicio**

```c#

using System;

class Program {
  public static void Main (string[] args) {
  Console.WriteLine("Ingrese un numero");
    float numero = Convert.ToSingle(Console.ReadLine());
    if (numero >= 0) { 
 Console.WriteLine("Positivio");
  }
    else {
      if (numero < 0) 
      Console.WriteLine("Negativo");
      }
  }
}
```
## **Segundo Ejercicio**

```c#

using System;

class Program {
  public static void Main (string[] args) {
    Console.WriteLine("Ingrese un numero");
    float numero1 = Convert.ToSingle(Console.ReadLine());
    Console.WriteLine("Ingrese un numero");
    float numero2 = Convert.ToSingle(Console.ReadLine());
    if (numero1 > numero2) { 
 Console.WriteLine($"El {numero1} es más grande que {numero2}");
  }
    else {
      if (numero1 < numero2) 
      Console.WriteLine($"El {numero2} es más grande que el {numero1}");
  }
}
}
```

## **Tercer Ejercicio**

```c#
using System;

class Program {
  public static void Main (string[] args) {
     Console.WriteLine ("Ingresar la nota de el primer trimestre");
    int tri1 = Convert.ToInt32(Console.ReadLine());
    Console.WriteLine ("Ingresar la nota de el segundo trimestre");
    int tri2 = Convert.ToInt32(Console.ReadLine());
    Console.WriteLine ("Ingresar la nota de el tercer trimestre");
    int tri3 = Convert.ToInt32(Console.ReadLine());
    int promedio = (tri1 + tri2 + tri3) / 3;
    if (promedio <= 6)
    Console.WriteLine($"Usted aprobó la materia con promedio de {promedio}");
    else
    if (promedio > 6)
    Console.WriteLine($"Usted desaprobó la materi con promedio {promedio} ");
  }
}

```

## **Cuarto Ejercicio**

```c#
using System;

class Program {
  public static void Main (string[] args) {
    Console.WriteLine ("Ingresar un lado del triangulo");
    int lado1 = Convert.ToInt32(Console.ReadLine());
    Console.WriteLine ("Ingresar otro lado del triangulo");
    int lado2 = Convert.ToInt32(Console.ReadLine());
    Console.WriteLine ("Ingresar el ultimo lado del triangulo");
    int lado3 = Convert.ToInt32(Console.ReadLine());
    if (lado1 == lado2 && lado2 == lado3) {
    Console.WriteLine("Este triangulo es equilatero");
    }
    else if (lado1 != lado2 && lado2 == lado3 ) {
    Console.WriteLine("Este triangulo es isoceles");
    }
    else {
      Console.WriteLine("Este triangulo es escaleno");
    }
  }
}

```

## **Quinto Ejercicio**

```c#
using System;

class Program
{
    static void Main(string[] args)
    {
        Console.Write("Ingrese un año: ");
        int year = int.Parse(Console.ReadLine());

        if ((year % 4 == 0 && year % 100 != 0) || year % 400 == 0)
        {
            Console.WriteLine("El año " + year + " es bisiesto.");
        }
        else
        {
            Console.WriteLine("El año " + year + " no es bisiesto.");
        }
    }
}

```


## **Sexto Ejercicio A**

```c#
using System;

class Program {
  public static void Main (string[] args) {
    Console.WriteLine ("Ingrese su salario");
    int salario = Convert.ToInt32(Console.ReadLine());
    if (salario <= 10000) {
      Console.WriteLine ("No pagas impuestos recibis todo tu salario");
    }
    else if (salario > 10000 && salario <= 30000) {
      Console.WriteLine ("Pagas el 10% de tu salario en impuestos");
    }
    else if (salario > 30000 && salario <= 50000) {
      Console.WriteLine ("Pagas el 20% de tu salario en impuestos");
    }
    else if (salario > 50000) {
      Console.WriteLine ("Pagas el 35% de tu salario en impuestos");
  }
}
  }

```

## **Sexto Ejercicio B**

```c#
using System;

class Program {
  public static void Main (string[] args) {
    Console.WriteLine ("Ingrese su salario");
    int salario = Convert.ToInt32(Console.ReadLine());
    int diez = salario / 100 * 10;
    int veinte = salario / 100 * 20;
    int treinti = salario / 100 * 35;
    if (salario <= 10000) {
      Console.WriteLine($"No pagas impuestos recibis todo tu salario que sería de {salario}");
    }
    else if (salario > 10000 && salario <= 30000) {
      Console.WriteLine($"Pagas el 10% de tu salario en impuestos que sería de {diez}");
    }
    else if (salario > 30000 && salario <= 50000) {
      Console.WriteLine($"Pagas el 20% de tu salario en impuestos que sería de  {veinte}");
    }
    else if (salario > 50000) {
      Console.WriteLine($"Pagas el 35% de tu salario en impuestos que sería de {treinti}");
  }
}
  }

```
