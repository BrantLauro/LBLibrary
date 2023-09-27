# LBLibrary
[to transalte to english]

Projeto feito para estudar Java e Orientação a Objetos, além de banco de dados com MySQL e interfaces com Swing 

## Especificação:
O Sistema deve permtir o cadastro, edição e exclusão de Leitores, Bibliotecários, Autores, Editoras e Livros que podem ter vários exemplares, além de fazer consultas ao acervo, fazer emprestimo, renovação 
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

