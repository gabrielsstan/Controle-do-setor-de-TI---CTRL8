Saudações, prezados usuários e colaboradores.

Esse portal, até então, é um HTML simples que desenvolvi para organizar os acessos do setor de informática no qual pertenço.

Na parte superior há uma headerbar fixa com menus. Utilizo para acesso rápido das ferramentas mais utilizadas.

Na primeira sessão há um campo de pesquisa e alguns atalhos.

1 - O campo de pesquisa funciona com o scripts.js em conjunto com o principais.css. O intuito dele é juntar PDFs com instruções que possam ajudar no dia a dia, pesquisar os ramais de contato da loja e alocar links de sistemas menos usados. Sua funcionalidade consiste em clicar na caixa de pesquisa para revelar o menu de opções. Assim que concluír a pesquisa, basta clicar fora da caixa para recolher o menu.

2 - Os links de favoritos auxiliam no acesso aos sistemas que costumamos logar no início do expediente.

3 - Os botões de atalho, como descrito no html, apenas apontam para o gmail e para a próxima sessão.

Na segunda sessão estão os demais aplicativos no qual não houve necessidade de destaque na primeira sessão.

Na terceira e quarta sessão estão os iframes do Google docs no qual usamos para anotações no diário de bordo e no diário de chamado.

No canto inferior direito da página há um botão para retornar ao topo, na sessão principal.

Para adicionar os links para pesquisa e ao menu da headerbar, faça manualmente no arquivo do HTML (index.html)

Para incluír link na headerbar, procure a respectiva class "menu-tag" e localize o href="#". Escolhendo o respectivo item, o link entrará no lugar do "#".

Para incluír item na pesquisa, localize a class "search-list". Vá até a última linha da lista e inclua uma nova, por exemplo: <li><a href="#">Item</a></li>. O link entrará no lugar do "#" e o nome do item que aparecerá na pesquisa entrará no lugar de "Item".

Para colocar link nos ícones de favorito, procure a class "favoritos" e substitua o "#" na lista pelo respectivo link que será usado.

Para colocar link no ícone do Email, localize a class "atalhos" e substitua o "#" na lista pelo link que será usado.

Para colocar link nos ícones da sessão de aplicativos, procure a class "segunda", no qual terá uma class "favoritos", e substitua o "#" na lista pelo respectivo link que será usado.

Para incluír documentos nos diários de bordo e de chamado, procure as classes "teceira" e "quarta" e localize a tag <iframe>, após, coloque o link do respectivo documento em: src="#", substituindo o "#".

Até então, são essas funções. Para dúvidas e contribuições:
email: gabrielstancf@gmail.com e instagram: gabrielsstan

Alteração de conteúdo: 0; funcionalidade /aparência: 1. Versão 8.0.1