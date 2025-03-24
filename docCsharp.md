# 📘 Documentação de Comandos do C#

## Introdução

C# é uma linguagem de programação moderna, orientada a objetos e desenvolvida pela Microsoft. Ela é amplamente utilizada para o desenvolvimento de aplicativos desktop, web, móveis e jogos.

## Estrutura Básica de um Programa em C#

```csharp
using System;

class Program
{
    static void Main(string[] args)
    {
        Console.WriteLine("Olá, Mundo!");
    }
}
```

## Principais Conceitos

### 1. Variáveis e Tipos de Dados
```csharp
int numero = 10;
string texto = "Exemplo";
bool verdadeiro = true;
```

### 2. Estruturas Condicionais
```csharp
if (numero > 5)
{
    Console.WriteLine("Maior que 5");
}
else
{
    Console.WriteLine("Menor ou igual a 5");
}
```

### 3. Laços de Repetição
```csharp
for (int i = 0; i < 5; i++)
{
    Console.WriteLine($"Iteração {i}");
}
```

### 4. Métodos
```csharp
static int Soma(int a, int b)
{
    return a + b;
}
```

### 5. Classes e Objetos
```csharp
class Pessoa
{
    public string Nome { get; set; }

    public void Apresentar()
    {
        Console.WriteLine($"Olá, meu nome é {Nome}");
    }
}
```

## Recursos Avançados

- **LINQ**: Consultas integradas à linguagem.
- **Async/Await**: Programação assíncrona.
- **Delegates e Eventos**: Manipulação de eventos.

## Conclusão

C# é uma linguagem poderosa e versátil, ideal para diversos tipos de projetos. Explore a documentação oficial para mais detalhes.

---