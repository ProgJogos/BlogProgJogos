Crie uma função `Procurar` que recebe um array de strings `colecao` e uma string `busca` como parâmetros e retorna verdadeiro se encontrar a `busca` e falso caso contrário.

<!--more-->

#### Gabarito

```csharp
// versão 1
bool Procurar (string[] colecao, string busca)
{
  foreach (string elemento in colecao)
  {
    if (elemento == busca)
      return true;
  }
  return false;
}


// versao 2
bool Procurar (string[] colecao, string busca)
{
  if (System.Array.IndexOf(colecao, busca) == -1)
  {
    return false;
  }
  return true;
}
```