# Repositório de provas de computação da Universidade de Caxias do Sul

Este é um repositório de provas dos cursos de computação da Universidade de Caxias do Sul (UCS) gerenciado pelos diretórios acadêmicos desses cursos. Ele tem como objetivo persistir provas, trabalhos e avaliações através da contribuição dos alunos. Visamos que este seja o repositório definitivo de provas, e, por isso, a colaboração dos alunos é de extrema importância.

Agradecimentos ao [Marcello](https://github.com/Marcellofabrizio), que junto aos outros membros do Diretório Acadêmico de Ciência da Computação, iniciou esse repositório.

**Observação**: Identifiou-se um problema no GitHub na visualização e download dos arquivos pela plataforma. Sugerimos fortemente que, mesmo para visualização, os alunos façam o `clone` do repositório, pois o erro não persiste nessas circunstâncias. Esse processo é explicado neste arquivo.



## Estrutura
Cada disciplina é ser organizada em uma pasta própria, contendo os arquivos de provas e trabalhos correspondentes. Esses arquivos devem ser nomeados conforme o seguinte padrão:

`{Nome da disciplina}; {Descrição da prova ou trabalho}; {Ano-semestre}; {Professor}; {Índice, se necessário}`

Esse padrão facilita a identificação da avaliação e do professor, preserva o anonimato dos estudantes e permite diferenciar múltiplas provas ou trabalhos realizados na mesma disciplina. O campo `{Ano-semestre}` deve seguir o padrão adotado pela UCS, isto é, o código 2 corresponde ao primeiro semestre do ano, e o código 4, ao segundo semestre; já o campo `{Nome da disciplina}` é opcional, pois o arquivo já estará armazenado na pasta correspondente à disciplina; e o campo `{Professor}` deve ser preenchido exatamente como o nome do docente aparece nos arquivos já existentes, evitando variações de escrita para a mesma pessoa. Dessa forma, todas as informações necessárias para identificar o arquivo ficam disponíveis diretamente em seu nome, tornando a busca e a organização mais simples.


Exemplos de nomes de arquivos:

- Programação 1; Prova 1; 2022-2; Cadinho; 1.pdf

- Programação 1; Prova 1; 2022-2; Cadinho; 2.pdf

- Programação 1; Prova 1; 2022-2; Cadinho; 3.pdf

- Programação 1; TDE 1; 2022-2; Alexandre Krohn.pdf

- Arquitetura de Computadores; Jogo malígno; 2023-4; André Adami.pdf

Além das provas, cada disciplina contém um arquivo chamado `BIBLIOGRAFIA.md`. O arquivo contém a lista dos livros utilizados como bibliografia na disciplina, definidos tanto pelo MEC quanto pelos professores, além de uma lista auxiliar de livros, artigos, vídeos ou materiais diversos que podem ser compartilhados pelos alunos para contribuir no estudo dos demais. Sempre que você ver algum vídeo que explica muito bem algum conceito ou ajuda a enteder a matéria da aula, pode contribuir com a bibliografia ao adicionar a URL neste arquivo para que outros alunos possam aproveitar o material também.



## Contribuições
O repositório busca armazenar provas e trabalhos para facilitar os estudos dos estudantes de computação da UCS. Provas são bem-vindas independentemente da nota ou da presença de resolução das questões. Trabalhos, no entanto, devem, se possível, ser enviados sem implementações, evitando cópias. O enunciado, no entanto, é estimulado, e pode ser convertido para PDF pela janela do AVA utilizando o comando CTRL+P ou utilizando extensões como [Web to PDF](https://chromewebstore.google.com/detail/web-to-pdf/pamnlaoeobcmhkliljfaofekeddpmfoh?pli=1). Para contribuir com o projeto, siga as instruções abaixo:

### Preparando o ambiente
1. Instale o [Git](https://git-scm.com/downloads).
2. Crie uma conta no Github.

Se houver complicações, procure pela [documentação](https://docs.github.com/pt/get-started/quickstart/set-up-git#setting-up-git).

### Obtendo o projeto
1. Navegue até o projeto em https://github.com/dacomp-ucs/Repositorio-de-Provas-TI-UCS/.
2. Clique em **Criar Fork**.
3. Na nova tela, não altere nada e clique novamente em **Criar Fork**.

### Clonando o fork
Você criou com sucesso o repositório, mas, até agora, ele existe apenas no GitHub. Para poder contribuir no projeto, você deverá cloná-lo para o seu computador.

1. No GitHub, navegue até o seu fork do repositório.
2. Copie a URL do repositório pelo seu navegador ou clicando em **CODE** e copie o endereço https.
3. Abra um terminal no seu computador, dentro de uma pasta vazia, e digite `git clone {url}`, substituindo {url} pela URL copiada.
4. Configure o repositório local para se conectar com seu repositório do github, seguindo os comandos abaixo.
   ```
   git config --global user.name "Seu Nome"
   git config --global user.email "seuemail@exemplo.com"
   ```
5. Em seu computador, crie novas pastas e adicione os PDFs de suas provas dentro da estrutura do projeto, mas, antes, veja a subseção abaixo sobre anonimização desses arquivos.
6. Adicione suas mudanças utilizando `git add .` e envie suas alterações com `git commit`. Se quiser, complemente com `-m "SUA MENSAGEM"`.
7. Publique suas alterações em seu repositório do GitHub com `git push origin main`. É possível que uma janela do navegador abra para você se autenticar com a conta que havia configurado. Coloque suas credenciais e espere a mensagem de que pode fechar aquela aba.

### Anonimizando os arquivos
Antes de adicionar seus arquivos PDF ao projeto, recomendamos que você realize o download do software PDFgear através do endereço https://www.pdfgear.com/pt/ para anonimizar suas provas e trabalhos. Com o software instalado, abra o arquivo PDF, vá na guia "Proteger" e procure pela opção "Redigir". Com esta opção ativa, desenhe um retângulo nas partes que deseja anonimizar e depois salve o arquivo. Esse procedimento garante a ocultação efetiva das informações, ao contrário de simplesmente sobrepor um retângulo colorido, que pode ser removido com facilidade.

### Atualizando este repositório
A fim de manter a qualidade do repositório, a sua contribuição será analisada antes de ser integrada. Para isso, usamos o mecanismo de Pull Requests do GitHub. Acesse sua conta do GitHub e vá até seu repositório com fork. Você verá uma notificação indicando que a branch está um commit à frente de original. Clique em Contribuir e em Abrir um Pull Request. O GitHub levará você para uma página que mostra as diferenças entre o fork e o repositório original. Clique em Criar Pull Request e espere a aprovação dos novos arquivos.

---

Agradecemos muito sua contribuição e bons estudos! 😊📖
