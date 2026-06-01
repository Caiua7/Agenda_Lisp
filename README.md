# Agenda Lisp

## Diário de Bordo

**Dia 30/05 - 14h**  
Caiuã fez as partes 1 e 2 (inserir elemento e procurar um contato pelo nome).

**Dia 31/05 - 18h**  
Caiuã fez as partes 3 e 4 (retornar os telefones do contato e adicionar um telefone no fim da lista).

**Dia 31/05 - 19h**  
Mateus fez as partes 5 e 6 (incluir contato ou telefone e remover telefone da lista).

**Dia 01/06 - 17h**  
Mateus fez as partes 7 e 8 (atualizar contato e excluir telefone).

---

## Resumo das Entregas

### Caiuã
- Parte 1: Inserir elemento.
- Parte 2: Procurar um contato pelo nome.
- Parte 3: Retornar os telefones do contato.
- Parte 4: Adicionar um telefone ao final da lista.

### Mateus
- Parte 5: Incluir contato ou telefone.
- Parte 6: Remover telefone da lista.
- Parte 7: Atualizar contato.
- Parte 8: Excluir telefone.

## Dificuldades e Soluções

Durante o desenvolvimento, as principais dificuldades estiveram relacionadas à manipulação de listas e ao uso de recursão em Lisp. A inclusão e exclusão de telefones exigiram atenção para atualizar corretamente os contatos sem perder informações já cadastradas. Na exclusão, também foi necessário tratar casos em que um contato ficava sem telefones associados.

A solução adotada foi utilizar funções recursivas e funções auxiliares para percorrer e reconstruir as listas da agenda. Com testes sucessivos, identificamos um padrão de resolução baseado na análise do primeiro elemento da lista e na aplicação da recursão ao restante.

## Conclusão

Este trabalho contribuiu para o aprimoramento do raciocínio lógico e para a compreensão do paradigma funcional. A implementação da agenda permitiu praticar conceitos fundamentais de Lisp, como recursão e manipulação de listas utilizando operações básicas da linguagem.
