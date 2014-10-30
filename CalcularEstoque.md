Em um jogo de estratégia, preciso saber, a partir do consumo total de comida (população x consumo per capita) e da minha produção, o quanto sobrou (ou faltou) de comida. A minha função `CalcularEstoque` deve calcular e retornar a diferença entre o consumo total e minha produção, recebendo os parâmetros `populacao`, `consumo` e `producao`. Se esse valor for positivo, significa que sobrou essa quantidade de comida. Se o valor final for negativo, significa que não produzi comida o suficiente, e vou precisar retirar esse valor de algum lugar. Considere todos os valores como inteiros.

<!--more-->

#### Gabarito

```csharp
// versao 1
int CalcularEstoque ( int populacao, int consumo, int producao)
{
  int consumoTotal = populacao * consumo;
  return producao - consumoTotal;
}

// versao 2
int CalcularEstoque ( int populacao, int consumo, int producao)
{
  return producao - (populacao * consumo);
}
```