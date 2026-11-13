# BiblioWeb

Protótipo institucional de biblioteca (HTML, CSS e JavaScript puros, sem backend). Os dados ficam no `localStorage` do navegador.

## Como executar
Abra `index.html` no navegador, ou publique a pasta em qualquer hospedagem estática.

## Acesso
Não há cadastros prévios. Escolha **Aluno** ou **Bibliotecário**, informe qualquer matrícula ou e-mail e qualquer senha. Na primeira entrada o perfil é criado localmente; o aluno pode completar nome, curso e turma em *Minha conta*.

## Páginas (menu lateral)
- **Aluno:** Início, Acervo, Minha conta, Meus empréstimos, Minhas reservas, Meu histórico.
- **Bibliotecário:** Início, Acervo e Administração (Visão geral, Catálogo e exemplares, Empréstimos, Reservas, Alunos).

## Reservas
Ao reservar, o exemplar fica separado e o aluno recebe um aviso para retirá-lo no balcão em até 2 dias (também exibido no Início). Se todos os exemplares estiverem emprestados, o aluno entra na fila. O bibliotecário confirma a retirada em Administração > Reservas.

## Regras
Prazo de 14 dias, até 3 empréstimos ativos e até 2 renovações.

## Arquivos
`index.html`, `styles.css`, `app.js`.
