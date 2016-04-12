Construa seu próprio Lisp
=========================

Tradução do livro em inglês Build your own Lisp (http://buildyourownlisp.com).

Sobre
-----

Esta é a versão HTML e o conteúdo do site parcialmente traduzido do livro acima.

Correções / Edições / Contribuições são bem-vindas

Mantenedor dessa tradução: Elias Dorneles `eliasdorneles@gmail.com`
Autor do texto original em inglês: Daniel Holden `contact@theorangeduck.com`

Licensiado via [Creative Commons Attribution-NonCommercial-ShareAlike 3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/deed.pt_BR)



Como rodar
----------


Não dá para simplesmente navegar pelos arquivos HTML puros do site. Os links não funcionarão, e as páginas não terão cabeçalho e rodapé. Se você quer rodar esse site localmente, instale o Flask e rode o website com os comandos a seguir.

```
pip install Flask
pip install Flask-Mail
python lispy.py
```

Você pode especificar uma porta usando a variável de ambiente `$PORT`.

```
env PORT=5000 python lispy.py
```

This will serve the site locally at `http://127.0.0.1:5000/`. You can browse it from there.
