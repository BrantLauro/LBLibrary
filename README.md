# LBLibrary
[to transalte to english]

Projeto feito para estudar Java e Orientação a Objetos, além de banco de dados com MySQL e interfaces com Swing 

## Especificação:
O Sistema deve permtir o cadastro, edição e exclusão de Leitores, Bibliotecários, Autores, Assuntos, Editoras e Livros que podem ter vários exemplares, além de fazer consultas ao acervo, fazer emprestimo, renovação 
e pagamento de multas dos leitores.


### Usuários:
**Leitores:** tendo uma matricula e uma senha, podem fazer o emprestimo de até 5 exemplares (livros) do acervo, tendo que devolver ou renovar os exemplares após uma semana, 
sendo cobrada uma multa de R$01,00 por dia caso se esqueça de renovar.

**Bibliotecários:** também têm uma matricula e uma senha e podem cadastrar, remover e editar exemplares, leitores e bibliotecários, receber exemplares de volta e cobrar multas dos leitores.

### Descrição:
A interface principal do sistema não necessita login, consultas ao acervo podem ser feitas por qualquer pessoa mesmo que não se tenha cadastro, porém, há uma
opção da interface para logar como admin (bibliotecário), fazer emprestimo, onde é exigido a matricula e a senha do leitor, além do código do Livro e renovar, onde 
pede-se, novamente, a matricula e a senha do usuário e é listado todos os exemplares emprestados que, caso não hajam multas, podem ser renovados. Portanto, após cadastrado o
Leitor o sistema é de auto-atendimento, podendo o próprio leitor fazer emprestimos e renovações, porém, para devolução, o leitor deve se dirigir a um bibliotecário para
realizar a devolução e o pagamento, em caso de multa.

## Interface:
**Menu principal:** A interface principal terá uma barra no centro da tela para se pesquisar livros, por autor, assunto, livre, ou pelo título, tendo umm botão com filtro para especificar o tipo de pesquisa, terá a logo da biblioteca no meio, e o botão de login no canto superior esquerdo, embaixo, dois botões grandes, emprestimo e renovar.

**Pesquisa:** Na tela de pesquisa, a barra, a logo e botão de filtros vai para cima, aparecendo um retangulo com os resultados da pesquisa, clicando em algum livro do resultado pode se consultar os exemplares do determinado livro no acervo. em baixo há um botão para retornar ao menu principal.

**Login:** A tela de login é uma tela suspensa sobre o menu principal, aparecerá 2 campos para preecnher, matricula do bibliotecário e senha, há dois botões, enviar e cancelar, ao enviar, se estiver tudo certo, o sistema vai para a tela do administrador. Qualquer problema com os campos será informado ao usuário com um aviso acima do campo em vermelho.

**Emprestimo:** A tela de emprestimo é uma tela suspensa sobre o menu principal, onde aparecerá 3 campos para preencher respectivamente, Código do Livro, Matricula do Leitor e Senha do leitor, embaixo há os botões Finalizar e Cancelar, ao clicar em finalizar, se tudo estiver certo vai aparecer a mensagem "Emprestimo Realizado com Sucesso", cancelar volta pro menu principal. Qualquer problema com os campos será informado ao usuário com um aviso acima do campo em vermelho.

**Renovar:** A tela de renovar é uma tela indentica a tela de login, mas com o título "renovação" ao clicar em eviar ao invés de ir a tela de administrador vai para a Listagem de emprestimos.

**Listagem de Emprestimos:** Nessa tela aparecerá o nome do Leitor no topo e em seguida uma lista com todos os exemplares emprestados para esse leitor, nos retangulos com os exemplares há o nome, a data de emprestimo e de devolução e um botão para renovar, ao clicar no botão o livro é renovado. No final há um botão com "Concluido" que retorna para o menu principal.

**Tela do Administrador:** Essa tela é igual ao Menu principal, mas com dois botões a mais, devolução e cadastro, devolução surge uma pequena tela flutuante pedindo o código do exmeplar, com o título "Devolução" e os botões Enviar e Cancelar, que volta pro menu do adm, ao enviar, se o exemplar realmente estiver emprestado ele será devolvido. Cadastro surge outra tela futuante em que há 3 opções Livro, Leitor e Bibliotecário, para se cadastrar algum dos 3, além do botão de cancelar, para retornar. A pesquisa aqui é diferente, sendo que o botão de filtro, filtra por Livro, Leitor ou Bibliotecário, no caso do filtro Livro os outros demais filtros podem ser aplicado. A tela que mostra os resultados é igual a tela de pesquisa com a diferença que há dois botões novos para todos os resultados, editar ou excluir, ao clicar em editar vai para a tela de cadastro da determinada entidade e excluir aparece uma confirmação se realmente se deseja excluir.

**Tela Cadstro:** Nas 3 telas de cadastro simplesmente são formulários para preencher os dados necessários com as opções de enviar ou cancelar, para retornar. No caso de Livro, caso o Assunto, Autor ou Editora do livro ainda não estiver cadastrada, pode-se cadastrar nesse momento, surgindo outro forumário pare preencher os dados necessários.

##Dados:



