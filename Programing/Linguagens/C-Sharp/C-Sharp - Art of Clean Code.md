### Link do curso: [C# Developers: Learn the Art of Writing Clean Code](https://www.udemy.com/course/clean-code/)

---
## **Exemplo de códigos ruins ( *Code Smells* ):  

**Refactoring/Refatoração** = Mudar a estrutura do código sem alterar seu comportamento externo  
  
### Plugin para refatoração: ReSharper (R#)  
Ele diz que em sua opinião todo desenvolvedor C# deve ter. Porque economiza tempo e fica certinho, prevenindo [[erros de compilação]].

**Ah fds, esquece, é pago** 

---
## Poor names:  
  
**Se você tem nomes ruins, você não entende o que as propriedades fazem ou são. E precisa ir para outro lugar entender o que elas fazem.  
E isso é um sintoma de "Code Smell"**  
  
**Exemplos:** 
``` C#
sqlDataReader dr1;
int od;
void Button1_Click();
class Page1 {}
```

**Jeito melhor de se fazer:** 
```C#
sqlDataReader dataReader;  // ou só 'reader'
int overdueDays;
void CheckAvalability_Click();
class ViewCustomerPage {}
```

---
## Notação húngara (Hungarian notation)

### Descrição

A Notação húngara, criada por Charles Simonyi, visa a facilitar o reconhecimento do tipo de variável num programa. O nome foi dado a partir de uma brincadeira comum entre os primeiros a conhecer a notação que a achavam estranha, fazendo o seguinte comentário: 

> [!quote] "É tão estranho que até parece húngaro".

**Exemplo:** 

```C#
int iMaxRequests;
```

No VSCode se você passa o mouse por cima mostra o tipo da variável.
Então pode deixar só como `iMaxRequests`

---
**Noisy names:  

```C#
Customer theCustomer;  // Customer  
List<Customer> ListOfApprovedcustomers;  //approvedCustomers
```
