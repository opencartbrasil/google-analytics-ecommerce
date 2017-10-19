[![license][licenca-badge]][LICENSE]

### Apresentação

Esta modificação foi desenvolvida no formato OCMOD, e habilita o envio dos dados do pedido para o Google Analytics E-commerce.

As informações são geradas baseadas nos dados dos pedidos que são concluídos na loja, sendo os dados enviados para o Google Analytics através da página de confirmação do pedido no checkout padrão do OpenCart.

Caso deseje doar um valor para contribuir com este trabalho continuo e sempre gratuito, clique no botão abaixo:

[![alt tag](https://www.paypalobjects.com/pt_BR/BR/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=7G9TR9PXS6G5J)

### Instalação

 1. Acesse o link: https://github.com/opencartbrasil/google-analytics-ecommerce/releases.
 2. Localize a versão mais atual e compatível com sua versão do OpenCart, e faça o download do arquivo "google-analytics-ecommerce.ocmod.zip".
 3. Na administração da loja acesse o menu Extensões→Instalador (Extensions→Installer).
 4. Na página do instalador, clique no botão Upload, selecione o arquivo 'google-analytics-ecommerce.ocmod.zip' (que você baixou deste repositório), e aguarde a conclusão da instalação automática.
 5. Após a instalação, acesse o menu Extensões→Modificações (Extensions→Modifications), e clique no botão Atualizar (Refresh), para que a modificação instalada seja incrementada na loja, lembrando que não é o botão "Atualizar" do navegador, e sim o botão "Atualizar" na cor azul ao lado do botão laranja e vermelho na tela do próprio OpenCart.

### Utilização

- No OpenCart até a versão 2.0.3.1:

Para que as informações sejam enviadas ao Google Analytics, o código gerado em sua conta no Google Analytics deve ser adicionado na loja através do menu Configurações→Lojas (System→Settings), aba "Servidor" (Server), e no campo "Código do Google Analytics" (Google Analytics Code), adicione o código e clique no botão "Salvar" (Save).

- No OpenCart da versão 2.1.0.1 até 2.2.0.0:

Para que as informações sejam enviadas ao Google Analytics, o código gerado em sua conta no Google Analytics deve ser habilitado na loja através do menu Extensões→Estatísticas (Extension→Analytics), localize a extensão "Google Analytics", clique no botão "Instalar" (Install), depois no botão "Editar" (Edit), adicione o código, habilite a extensão, e clique no botão "Salvar" (Save).

- No OpenCart da versão 2.3.0.0 até 3.0.x:

Para que as informações sejam enviadas ao Google Analytics, o código gerado em sua conta no Google Analytics deve ser habilitado na loja através do menu Extensões→Extensões e filtre por Estatísticas (Extension→Extension filter Analytics), localize a extensão "Google Analytics", clique no botão "Instalar" (Install), depois no botão "Editar" (Edit), adicione o código, habilite a extensão, e clique no botão "Salvar" (Save).

#### Importante:

Para que você possa visualizar os dados dos pedidos enviados para o Google Analytics, você deve habilitar o serviço de comércio eletrônico, para isso, acesse sua conta no Google Analytics e clique na aba "Administrador", no menu "Configurações de comércio eletrônico", e habilite o campo "Ativar comércio eletrônico".

Para visualizar os dados do pedido, acesse sua conta no Google Analytics e clique na aba "Relatórios", no menu "Conversões", submenu "Comércio Eletrônico".

Leva em média 24 horas para que os dados enviados comecem a ser visualizados.

### Desinstalação

Para desinstalar a modificação, na administração da loja, acesse o menu Extensões→Modificações (Extensions→Modifications),  localize e selecione a modificação com o nome 'Google Analytics E-commerce para OpenCart', depois clique no botão Excluir (Delete), e no botão Atualizar (Refresh).

### Atualização

Acesse a administração da loja e execute o procedimento de Desinstalação, depois execute o procedimento de Instalação.

### Dúvidas

O OCMOD (OpenCart Modification) é nativo do OpenCart, ou seja, não é necessário instalar nenhum complemento no OpenCart para utilizar modificações ou extensões no formato OCMOD, para mais informações sobre o OCMOD, segue o link para mais informações:

https://github.com/opencart/opencart/wiki/Modification-System

[licenca-badge]: https://img.shields.io/badge/licença-GPLv3-blue.svg
[LICENSE]: ./LICENSE
