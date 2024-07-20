
```
	estrutura de dados que segue um conceito chamado  LIFO (last in, first out)
```



---

> [!important]
> 
> 	`principais operações em uma pilha:`
> 	
> 	
> 	`PUSH: adiciona um elemento ao topo da pilha`
> 	
> 	`POP: remove o elemento do topo da pilha`
> 	
> 	`TOP: retorna o elemento no topo da pilha sem remove-lo`
> 	
> 	`IsEmpty: verifica se a fila esta vazia`
> 	
> 	`SIZE: retorna o numero de elementos na pilha`



> [!NOTE]
> 
> uma pilha pode ser construída usando arrays ou listas ligadas ou listas ligadas
> 

```

class Pilha:
    def __init__(self):
        self.items = []

    def push(self, item):
        self.items.append(item)

    def pop(self):
        if not self.is_empty():
            return self.items.pop()
        else:
            print("A pilha está vazia.")

    def top(self):
        if not self.is_empty():
            return self.items[-1]
        else:
            print("A pilha está vazia.")

    def is_empty(self):
        return len(self.items) == 0

    def size(self):
        return len(self.items)


```




1. **`__init__(self)` - Construtor:**
    
    - Este é o método inicializador (construtor) da classe. Ele é chamado quando você cria uma nova instância da classe `Pilha`. Neste caso, inicializa a pilha como uma lista vazia.
2. **`push(self, item)` - Empurrar (adicionar elemento):**
    
    - Este método recebe um parâmetro `item` e adiciona esse item ao topo da pilha. Isso é feito usando o método `append()` da lista.
3. **`pop(self)` - Remover (retirar elemento do topo):**
    
    - Este método remove e retorna o elemento do topo da pilha. Antes de chamar `pop()`, ele verifica se a pilha não está vazia usando o método `is_empty()`.
4. **`top(self)` - Topo (retornar elemento do topo sem removê-lo):**
    
    - Este método retorna o elemento no topo da pilha sem removê-lo. Assim como o método `pop()`, verifica se a pilha não está vazia antes de acessar o topo.
5. **`is_empty(self)` - Está vazia (verificar se a pilha está vazia):**
    
    - Este método retorna `True` se a pilha estiver vazia (sem elementos) e `False` caso contrário. É usado para verificar antes de tentar acessar ou remover elementos.
6. **`size(self)` - Tamanho (retornar o número de elementos na pilha):**
    
    - Este método retorna o número de elementos na pilha, usando a função `len()`.
    - 