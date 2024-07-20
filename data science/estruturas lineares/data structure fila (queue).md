

Uma fila (queue) é outra estrutura de dados fundamental que segue o princípio First In, First Out (FIFO)

> [!info]
> As principais operações em uma fila são:
> 
> 1. **Enqueue (Inserir):** Adiciona um elemento ao final da fila.
> 2. **Dequeue (Remover):** Remove e retorna o elemento do início da fila.
> 3. **Front (Frente):** Retorna o elemento no início da fila sem removê-lo.
> 4. **IsEmpty (Está vazia):** Verifica se a fila está vazia.
> 5. **Size (Tamanho):** Retorna o número de elementos na fila.

Assim como com pilhas, filas podem ser implementadas usando arrays ou listas ligadas. Aqui está um exemplo de implementação simples em Python usando uma lista:


```

`class Fila:`
    `def __init__(self):`
        `self.items = []`

    `def enqueue(self, item):`
        `self.items.append(item)`

    `def dequeue(self):`
        `if not self.is_empty():`
            `return self.items.pop(0)`
        `else:`
            `print("A fila está vazia.")`

    `def front(self):`
        `if not self.is_empty():`
            `return self.items[0]`
        `else:`
            `print("A fila está vazia.")`

    `def is_empty(self):`
        `return len(self.items) == 0`

    `def size(self):`
        `return len(self.items)`

```