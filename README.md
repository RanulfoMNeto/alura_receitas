# Alura cursos online - Fundamentos Django 2 (Parte 2): Uma aplicação web

Projeto da Alura cursos online, desenvolvido em Python3 com framework Django

## Projeto final

Nesse curso:

- Alteramos o Admin do Django para exibir o nome de cada receita através da função [__str__](https://docs.djangoproject.com/pt-br/2.2/howto/custom-model-fields/);

- Adicionamos filtros, buscas e paginação alterando o código do [admin.py](https://docs.djangoproject.com/en/2.2/ref/contrib/admin/).

- Criamos o app de `pessoas`, criamos um modelo com `nome` e `email` e realizamos a migração;

- Integramos o modelo de receita com o modelo de pessoa, indicando quem postou a receita;

- Influímos a função `__str__` para retornar o nome  da pessoa no admin no lugar de `Pessoa object`.

- Criamos o campo `publicada` no models de receitas, atribuindo o valor `default=False`, exibindo apenas as receitas publicadas com valor `True`;

- Incluímos o código `list_editable` do campo publicada no admin.py de receita e alteramos a ordenação por data;

- Adicionamos o campo `foto_receita`, instalamos o [pillow](https://pillow.readthedocs.io/en/stable/), realizamos a migração e adicionamos uma foto no bolo de chocolate.

- Configuramos o `static root`, `settings` e alteramos nossos templates para exibir a foto da receita;

- Além disso, criamos uma verificação nos casos de não haver a foto da receita, exibindo a imagem padrão;

- Desenvolvemos a página de busca, e método buscar na view, exibindo o resultado da busca.

- Aprendemos que podemos criar usuários Django com autorizações limitadas;

- Refatoramos o código html para evitar duplicidade de código, criando a partial `_busca.html`.