**8)** Considere a implementação da classe base FormaGeometrica em um sistema de modelagem de formas geométricas. Sua tarefa é implementar, utilizando pseudocódigo, as classes derivadas Retangulo e Circulo, que herdam da classe FormaGeometrica, adicionando atributos específicos e métodos para calcular a área de um retângulo e de um círculo, respectivamente.

```
Classe FormaGeometrica:
    Atributos:
        - cor

    Método Construtor(cor):
        Define o valor do atributo cor com o valor passado como parâmetro.

    Método CalcularArea():
        # Implementação genérica para cálculo de área, a ser sobrescrita pelas subclasses.

```

______
### Segue a resposta

```

Classe Retangulo herda FormaGeometrica

    Atributos:
        - altura
        - largura

    Método CalcularArea():
        # altura * largura

Classe Circulo herda Forma Geometrica

    Atributos:
        - raio

    Método CalcularArea():
        # π*r^2


```
