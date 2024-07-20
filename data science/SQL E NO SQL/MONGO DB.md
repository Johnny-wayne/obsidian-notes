> [!NOTE]
> 
> 1. **Conectar ao servidor MongoDB:**
>     
>     bash
>     
>     `mongo`
>     
> 2. **Listar bancos de dados:**
>     
>     bash
>     
>     `show dbs`
>     
> 3. **Selecionar um banco de dados:**
>     
>     bash
>     
>     `use nome_do_banco`
>     
> 4. **Listar coleções no banco de dados atual:**
>     
>     bash
>     
>     `show collections`
>     
> 5. **Inserir um documento em uma coleção:**
>     
>     bash
>     
>     `db.nome_da_colecao.insert({campo1: valor1, campo2: valor2})`
>     
> 6. **Consultar documentos em uma coleção:**
>     
>     bash
>     
>     `db.nome_da_colecao.find()`
>     
> 7. **Consultar com critérios:**
>     
>     bash
>     
>     `db.nome_da_colecao.find({campo: valor})`
>     
> 8. **Atualizar documentos em uma coleção:**
>     
>     bash
>     
>     `db.nome_da_colecao.update({critério}, {$set: {campo: novo_valor}})`
>     
> 9. **Remover documentos em uma coleção:**
>     
>     bash
>     
>     `db.nome_da_colecao.remove({critério})`
>     
> 10. **Criar um índice:**
>     
>     bash
>     
>     `db.nome_da_colecao.createIndex({campo: 1})`
>     
> 11. **Exibir o plano de execução de uma consulta:**
>     
>     bash
>     
>     `db.nome_da_colecao.explain().find({campo: valor})`
>     
> 12. **Backup e restauração (mongodump e mongorestore):**
>     
>     bash
>     
>     `mongodump --db nome_do_banco --out caminho/do/diretorio mongorestore --db nome_do_banco caminho/do/diretorio/nome_do_banco`
> 
> 
> 
> 
> 
> 
> 
> 


