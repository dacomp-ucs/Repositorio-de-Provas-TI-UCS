# Repositório de Provas da Computação UCS

Este é um repositório de provas dos cursos de computação da UCS gerenciado pelos respectivos diretórios acadêmicos. Ele tem como objetivo persistir provas, trabalhos e avaliações, e permitir a contribuição dos alunos. Visamos que este seja o repositório definitivo de provas, por isso, a colaboração dos alunos é de extrema importância.

Agradecimentos ao [Marcello](https://github.com/Marcellofabrizio), que junto ao DA da época, iniciou esse repositório.

## Estrutura de pastas
Cada disciplina é representada por uma pasta, que possui diversos arquivos com as provas anteriores daquela disciplina. Os arquivos devem ter um nome padrão, seguindo a seguinte nomencaltura: `Número da Prova/Trabalho;Ano-Semestre;Professor;Aluno`. Esse padrão permite que seja possível que múltiplos alunos contribuam com provas feitas na mesma disciplina, e todas as informações necessárias para quem procura a referência estejam disponíves já no título. O aluno pode optar por ocultar seu nome e nota da avaliação se preferir, assim colocando "Anônimo 1" onde o nome do aluno ficaria, seguindo a numeração conforme o necessário para diferenciar seu arquivo de algum já presente na pasta. O nome da disciplina é dispensável pois já está na pasta, e em caso de trabalhos, o nome do aluno pode ficar em branco, visto que não se deve incluir a implementação. 

Exemplos:

Prova 1;Programação 1;2022-1;Cadinho;Pedro Pacheco.pdf

Prova 1;Programação 1;2022-1;Cadinho;Eduardo Pereira.pdf

TDE 1;Programação 1;2022-1;Krohn;Anderson Rizzi.pdf

Jogo malígno;2023-2;Adami;.pdf

## Como contribuir
O repositório busca armazenar provas e trabalhos para facilitar os estudos dos estudantes de computação da UCS. Provas são bem-vindas independentemente da nota ou da presença de resolução das questões. Trabalhos, no entanto, devem ser evitadas implementações, para evitar cópias. O enunciado, no entanto, é permitido, e pode ser convertido para PDF pela janela do AVA utilizando o comando CTRL+P. Para contribuir com o projeto, siga as instruções abaixo. Siga os passos abaixo para contribuir neste projeto:

### Preparação
1. Instale o [Git](https://git-scm.com/downloads)
2. Crie uma conta no Github

Se houver complicações, procure pela documentação [aqui](https://docs.github.com/pt/get-started/quickstart/set-up-git#setting-up-git).

### Obtendo o projeto e contribuindo
1. Navegue até o projeto em https://github.com/dacomp-ucs/Repositorio-de-Provas-TI-UCS/
2. Clique em **Criar Fork**
3. Na nova tela, não altere nada, clique novamente em **Criar Fork**

### Clonando o Fork
Você criou com sucesso o repositório, mas, até agora, ele existe apenas no GitHub. Para poder contribuir no projeto, você deverá cloná-lo para o seu computador.

1. No GitHub, navegue até o seu fork do repositório.
2. Copie a URL do repositório pelo seu navegador ou clicando em **CODE** e copie o endereço https.
3. Abra um terminal no seu computador, dentro de uma pasta vazia, e digite `git clone {url}`, substituindo {url} pela URL copiada.
4. Configure o repositório local para se conectar com seu repositório do github, seguindo os comandos abaixo.
   ```
   git config --global user.name "Seu Nome"
   git config --global user.email "seuemail@exemplo.com"
   ```
5. Em seu computador, crie novas pastas e adicione os PDFs de suas provas dentro da estrutura.
6. Adicione suas mudanças utilizando `git add .` e envie suas alterações com `git commit`. Se quiser, complemente com `-m "SUA MENSAGEM"`.
7. Publique suas alterações em seu repositório do GitHub com `git push origin`. É possível que uma janela do navegador abra para você se autenticar com a conta que havia configurado. Coloque suas credenciais e espere a mensagem de que pode fechar aquela aba.

### Atualizando este repositório com Pull Request
A fim de manter a qualidade do repositório, a sua contribuição será analisada antes de ser integrada ao repositório. Para isso, usamos o mecanismo de Pull Requests do GitHub. Acesse sua conta do GitHub e vá até seu repositório com fork. Você verá uma notificação indicando que a branch está um commit à frente de original. Clique em Contribuir e em Abrir um Pull Request.

O GitHub levará você para uma página que mostra as diferenças entre o fork e o repositório original. Clique em Criar Pull Request e espere a aprovação dos novos arquivos.

Agradecemos muito sua contribuição! 😊
