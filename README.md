# Este tutorial mostra como criar um Bucket no Google

Isso servirá para você salvar arquivos, como imagens e vídeos, podendo recuperá-los no frontend da sua aplicação. Esse tutorial explora a camada gratuita do Google e está sendo montado em especial para o projeto de rede social meu.

## Configuração do buckets do Google

Acesse o endereço do [console.cloud.google.com](https://console.cloud.google.com/cloud-resource-manager?folder=&organizationId=0&hl=pt-br) e crie sua conta. Sim, você precisará de um cartão de crédito, mas você não será cobrado na camada gratuita.

### Passo a passo
1. Crie um projeto, espere um pouco e depois atualize a página
![Criando um projeto no Google Console](images/tutorial/001.png)

2. Volte na página inicial, você verá algo parecido com isso
![Projeto criado](images/tutorial/002.png)

3. Na barra superior de busca, procure pelo 'Cloud Storage'
![Buscando o Google Cloud Storage](images/tutorial/003.png)

4. Crie um Bucket
![Criando um Bucket](images/tutorial/004.png)

5. De um nome ao Bucket
![Dando um nome ao bucket](images/tutorial/005.png)

6. Pode manter as opções padrões
![Pode manter as opções padrão de criação de um bucket](images/tutorial/006.png)

7. Continue com as opções padrões
![Escolhendo a opção padrão na criação do bucket](images/tutorial/007.png)

8. Desative a opção para aplicar prevenção a acesso público ao bucket
![Desativando a opção de prevenção de acesso público](images/tutorial/009.png)

9 - Com o bucket criado, clique em 'Intervalos' e depois no bucket, clique nos três pontinhos e escolha a opção 'Editar Permissões do bucket'
![Editando permissões do bucket](images/tutorial/011.png)

10. Adicione um principal, vamos tornar o acesso ao bucket publico
![Adicionando o acesso público](images/tutorial/012.png)

11 - Digite 'Allusers' no campo superior e clique em 'Selecionar Papel', escolhendo conforme o exemplo abaixo
![Escolhendo a opção Cloud Storage, depois Leitor de Objetos do Storage](images/tutorial/013.png)

12 - Confirme a opção
![Confirmando o acesso público](images/tutorial/015.png)

13 - Agora vamos obter as credenciais para acessar e manipularmos o bucket. Faça a busca por API Credenciais
![Buscando por Credenciais](images/tutorial/016.png)

14 - Crie uma credencial como conta do serviço
![Criando uma credencial como conta de serviço](images/tutorial/017.png)

15 - Escolha o nome da conta de serviço
![Escolhendo o nome da conta de serviço](images/tutorial/018.png)

16 - Escolha a opção cloud storage, administrador do storage.
![Escolhendo a opção Cloud Storage, depois Administrador de Storage](images/tutorial/019.png)

17. Pode deixar tudo em branco
![Deixando os campos em branco](images/tutorial/008.png)

18 - Conta criada, clique nela
![Clicando na conta criada](images/tutorial/020.png)

19 - Clique em adicionar a chaves
![Adicionando uma chave](images/tutorial/021.png)

20 - Crie uma chave
![Criando uma chave](images/tutorial/022.png)

21 - Escolha a chave como Json
![Escolhendo a opção Json](images/tutorial/023.png)

22 - Faça o download da chave json.
![baixando a chave](images/tutorial/024.png)

Portinho, bucket criado e pronto para o básico
