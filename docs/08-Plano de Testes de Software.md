# Plano de Testes de Software
Os requisitos para realização dos testes de software são:
-	Site publicado na Internet
-	Navegador da Internet - Chrome, Firefox ou Edge
-	Conectividade de Internet para acesso aos vídeos de apresentação e redes sociais

Os testes funcionais a serem realizados no aplicativo estão descritos abaixo.


| Caso de Teste         | Caso de Teste	CT-01 – Cadastro de usuário (cliente) |
|-----------------------|--------------------------------------------------------|
| Requisitos Associados | RF-002 - O site deve permitir que o usuário crie uma conta para salvar suas informações (local de entrega, meios de pagamento, histórico de pedidos, etc). |
| Objetivo do Teste     | Verificar a funcionalidade de cadastro do cliente |
| Passos                | 1) Acessar o Navegador <br>2) Informar o endereço do Site <br>3) Visualizar a página principal <br>4) Clicar na opção "Crie sua conta" presente no cabeçalho do site <br>5) Preencher as informações de cadastro solicitadas e clicar em "concluir cadastro".|
| Critérios de Êxito    | -	Realizar cadastro de dados pessoais. <br>- Cadastro só pode ser bem sucedido caso o e-mail não tenha sido cadastrado anteriormente. <br>- Cadastro só pode ser bem sucedido caso a senha tenha sido repetida corretamente. |

<br>


| Caso de Teste         | Caso de Teste	CT-03 – Login e logoff de usuário |
|-----------------------|--------------------------------------------------------|
| 
| Objetivo do Teste     | Verificar a função de login do usuário |
| Passos                | 1) Acessar o Navegador <br>2) Informar o endereço do Site <br>3) Visualizar a página principal <br>4) Clicar na opção "Fazer Login" presente no cabeçalho do site <br>5) Preencher os campos de e-mail e senha e clicar na opção "Entrar". <br> 5) Após o login bem sucedido, clicar na opção "Minha conta" no cabeçalho e escolher a opção "Sair". |
| Critérios de Êxito    | -	Realizar o Login da conta. <br>- Login só pode ser bem sucedido com um e-mail cadastrado e informando a senha correta. <br> - Realizar logoff e verificar que a opção "Minha conta" voltou a ser "Fazer Login" após o logoff |

<br>


| Caso de Teste         | Caso de Teste CT-09 – Adicionar e remover produtos de uma loja ao carrinho de compras |
|-----------------------|--------------------------------------------------------|
| Requisitos Associados | RF-010 - O site deve permitir que o usuário cadastrado adicione os produtos de um vendedor a um carrinho de compras e submeta um pedido de compra. |
| Objetivo do Teste     | Verificar a função de adicionar produtos cadastrados em uma loja ao carrinho de compras da loja |
| Passos                | 1) Acessar o Navegador <br>2) Informar o endereço do Site <br>3) Visualizar a página principal <br>4) Clicar em algum vendedor recomendado na página inicial ou utilizar a funcionalidade "Buscar vendedores" e clicar nos vendedores listados <br> 5) Clicar na aba "Produtos" no menu de navegação. <br> 6) Clicar no botão de "Mais detalhes" do produto desejado para abrir o modal de detalhes do produto. <br> 7) Clicar em "Adicionar ao carrinho" <br> 8) Selecionar o sabor e quantidade do produto que deseja adicionar, adicionar comentários sobre o pedido e clicar novamente em "Adicionar ao carrinho" para adicionar o produto na quantidade e sabor desejados ao carrinho <br> 9) Clicar na aba "Carrinho" do mini website para verificar se o produto foi adicionado à lista. <br> 10) Mais produtos podem ser adicioandos ao carrinho na aba de "Carrinho" do mini-website clicando em "Adicionar produto" nos produtos listados à esquerda nesta página (podendo selecionar a quantidade, sabor e comentários). <br> 11) Para remover algum produto da lista do carrinho, clique em "cancelar" no canto inferior direito da descrição da ordem do produto na lista. |


<br>

| Caso de Teste         | Caso de Teste CT-10 – Submeter o pedido de compra dos produtos adicionados ao carrinho |
|-----------------------|--------------------------------------------------------|
| Requisitos Associados | RF-003 - O site deve apresentar uma página individual de cada microempreendedor com seus produtos e informações relevantes. |
| Objetivo do Teste     | Verificar a função de submeter pedido de compra dos produtos listados no carrinho |
| Passos                | 1) Acessar o Navegador <br>2) Informar o endereço do Site <br>3) Visualizar a página principal <br>4) Clicar em algum vendedor recomendado na página inicial ou utilizar a funcionalidade "Buscar vendedores" e clicar nos vendedores listados <br> 5) Clicar na aba "Produtos" no menu de navegação do mini website do vendedor. <br> 6) Clicar no botão de "Mais detalhes" do produto desejado para abrir o modal de detalhes do produto. <br> 7) Clicar em "Adicionar ao carrinho" <br> 8) Selecionar o sabor e quantidade do produto que deseja adicionar, adicionar comentários sobre o pedido e clicar novamente em "Adicionar ao carrinho" para adicionar o produto na quantidade e sabor desejados ao carrinho <br> 9) Clicar na aba "Carrinho" do mini website para verificar se o produto foi adicionado à lista. <br> 10) Mais produtos podem ser adicioandos ao carrinho na aba de "Carrinho" do mini-website clicando em "Adicionar produto" nos produtos listados à esquerda nesta página (podendo selecionar a quantidade, sabor e comentários). <br> 11) Para remover algum produto da lista do carrinho, clique em "cancelar" no canto inferior direito da descrição da ordem do produto na lista. <br> 12) Clicar em "Finalizar pedido" para ir para a tela de seleção de meios de entrega e pagamento. <br> 13) Selecione a forma de pagamento e entrega desejados e clique novamente em "finalizar pedido". |
| Critérios de Êxito    | -	Submeter o pedido com sucesso. <br> - O pedido só deve ser submetido caso o usuário esteja logado e tenha selecionado uma forma de pagamento e entrega. |

<br>

| Caso de Teste         | Caso de Teste	CT-18 – Cadastrar novo produto na loja (Vendedor) |
|-----------------------|--------------------------------------------------------|
| Requisitos Associados | RF-008 -	O site deve permitir que microempreendedor cadastre seus produtos e forneça possíveis informações relevantes sobre os mesmos para constar na descrição |
| Objetivo do Teste     | Verificar a funcionalidade de cadastro de novos produtos pelo usuário cadastrado como vendedor/dono daquela loja |
| Passos                | 1) Acessar o Navegador <br>2) Informar o endereço do Site <br>3) Visualizar a página principal <br>4) Clicar na opção "Fazer Login" presente no cabeçalho do site <br>5) Realizar login em uma conta cadastrada como "vendedor" preenchendo os campos de e-mail e senha com os dados da conta e clicar na opção "Entrar". <br> 5) Após o login bem sucedido, clicar na opção "Minha conta" no cabeçalho e escolher a opção "Gerenciar loja" (disponível somente para contas de vendedores). <br> 6) Clicar na aba "Produtos" no menu de navegação <br> 7) Clicar em "Adicionar produto" <br> 8) Preencher as informações do produto e clicar em "Submeter alterações". <br> Clicar em "Editar produto" caso deseje alterar as informações novamente ou em "Remover" caso queira remover um produto. |
| Critérios de Êxito    | -	As informações cadastradas devem permanecer após sair e voltar para a página de produtos <br> - Os produtos cadastrados deverão aparecer ao visualizar a página de produtos da loja do vendedor e deve ser possível adiciona-los ao carrinho de compras. <br> - Os produtos devem ser removidos do mini-website ao clicar em "Remover" na aba de produtos da página de gerenciamento da loja ou ter suas informações alteradas ao clicar em "Editar produto". |


