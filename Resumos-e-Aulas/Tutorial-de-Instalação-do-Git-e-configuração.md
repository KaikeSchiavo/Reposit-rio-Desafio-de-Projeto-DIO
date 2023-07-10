# 📖 Resumos e Aulas | DIO
### --> Instalando e configurando o Git 👾

Quando estiver instalando o Git, deixe tudo marcado no padrão que já aparece, apenas no final desmarque as release notes.

Agora, segue abaixo a configuração dentro do Git mesmo

Antes de tudo crie uma nova pasta, abra e com o botão direito dê um Git bash here

Ao digitar git config, aparecerá vários códigos git e suas funcionlidades, por obséquio, Ctrl + l, você limpa o seu terminal, para não ficar muito bagunçado

Agora para definir um e-mail e um nome para todos os repositórios que criaremos, devemos armazenar esses dados no global, para guardar sempre o mesmo nome e e-mail de usuário.

Em seguida digite: git config --global user.name "(seu nome)" Assim configuramos nosso nome

Para configurar o e-mail digite: git config --global user.email (seu email)

Para o próximo passo, iremos mudar uma branch padrão que foi vista na hora da instalação, para isso digite: git config init.defaultBranch

Depois digite a mesma coisa só que agora após o final do código, coloque o nome para a branch, Exemplo: main. E lembre de direcionar para o global, assim essa alteração será feita globalmente.

### Agora, partiremos para a parte de autenticação via token pelo GitHub 🔑

Com o GitHub aberto, crie um novo repositório, deixe ele privado e adicione a README file. Após isso clique em code e copie esse repositório, agora lá no GitBash, digite: git clone (link do repositório). Esse teste foi feito para explicar que  maneira de autenticação mudou para melhorar a segurança, logo tudo o que foi feito resultará em erro, siga abaixo a maneira certa de configurar isso:

Na página do GitHub, vá em configurações, depois vá em developer setings, e clique em Personal acess tokens e selecione o tokens (classic). Depois de gerar o token, coloque a senha, e logo após isso, você será redireciondo para outra página. Nesta página, em note, digite para que esse token vai servir, coloque curso Git, depois marque em quantos dias ele vai expirar. Depois em scopes, selecione as permissões que você quer que esse token tenha, de obrigatório no momento só selecione a permissão do repositório e gere o token.

### Criar um repositório Git direto da sua máquina 💻

Dentro do terminal digite mkdir e digite um nome para o repositório, depois de criado entre na pasta digitando cd e o nome do repositório, dentro da pasta, digite git init e pronto, você tem um repositório Git.
