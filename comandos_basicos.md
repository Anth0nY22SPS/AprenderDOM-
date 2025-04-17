Comandos |   Descrição
---      |    ---
alert()  |   mostra um alerta na tela do usuario
confirm()|   Mostra uma caixa de diálogo contendo uma mensagem com um botão de OK e um de CANCEL.
prompt() |   Mostra uma caixa de diálogo para o usuário entrar com algum dado.
open()   |   Abre uma nova janela no navegador.
close()  |   Fecha a janela atual do navegador.
setTimeout()|   Executa uma ação após um determinado tempo. Essa ação pode ser uma chamada de função, uma expressão de avaliação, etc

------------------------------------------------------------------------------------

*Alterar o título*
document.title = 123;
*Criar um elemento <h1>*
```
let heading = document.createElement('H1');
heading.innerHTML = 'Olá alunos!';
document.body.appendChild(heading);
```

------------------------------------------------------------------------------------

## Métodos get
get -> significa obter
 
document.getElementById('titulo') -> obter informação atraves do Id
getElementsByClassName('titulo')  -> obter informação atraves da Class
getElementsByTagName('li')        -> obter informação atraves da Tag
document.getElementsByName        -> obter todos os elementos com o nome
Element.remove()                  -> remove o elemento

-------------------------------------------------------------------------------------

document.querySelector('p')              -> Busca elemento dentro do selector 'p'
(document.querySelector('.myclass'))     -> Busca somente a classe

-------------------------------------------------------------------------------------

## Eventos

const Clique = () => { document.querySelector('#my-span') } -> Função chamada pelo evento onclick
document.querySelectorAll(seletores)  ->  é uma string com um ou mais seletores desejados. Para mais de um seletor, deve-se separá-los por vírgula

