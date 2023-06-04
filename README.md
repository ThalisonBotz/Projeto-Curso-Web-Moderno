# Projeto-Curso-Web-Moderno

Anotações uteis sobre JS:
    *Variaveis:
        Usar let de preferencia.
        Usar Const caso o valor vai mudar.
        Usar Var para um valor que possa ser usado fora de uma function.
    *Valores Numericos:
        Mesma forma de criar um numero (const n = 1  const n = Number(1)).
        #funções:
            isInteger(): retorna um poleano se o numero for inteiro.
            toFixed(): permite passar quantas casas depois da virgula serão exibidos.
            toString(): retorna o numero como string.
            toString(): retorna o numero em binario.
            typeof(): retorna o tipo da variavel.
    *String
        #funões:
            charAt(): retorna um itens especifico da string.
            charCodeAt(): retorna o codigo da tabela unicode do itens especifico da string.
            indexOf(''): caso exista o itens, ele irá retornar a posição, caso não exista irá retornar -1.
            substring(): retorna os itens a frente do numero passado, tambem é possivel passar 2 valores para decidir inicio e fim.
            concat(): permite concatenar mais coisas dentro do item.
            replace(); permite trocar valores ao passar como primeiro parametro quem será trocado e no segundo pelo que será trocado.
            split('') permite separar items por parametro.
    *Template Sting
        O mesmo serve para montar codigo sem precisar concatenar tudo, usando (``).
        É necessario usar ${}, para que o codigo entenda que se trata de um valor ou variavel.
