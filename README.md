### Resumo

Esta modificação foi desenvolvida no formato OCMod, e habilita o envio dos dados do pedido para o Google Analytics E-commerce.

As informações são geradas baseadas nos dados dos pedidos que são concluídos na loja, ou seja, que chegam a página de sucesso, porém, essas informações não são atualizadas para informar se o pedido foi pago.

Caso deseje doar um valor para contribuir com este trabalho continuo e sempre gratuito, clique no botão abaixo:

[![alt tag](https://www.paypalobjects.com/pt_BR/BR/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=7G9TR9PXS6G5J)

### Instalação

 1. Baixe a modificação no link: https://github.com/opencartbrasil/google-analytics-ecommerce/releases. Localize a versão mais atual e compatível do arquivo "google-analytics-ecommerce.ocmod.zip".
 2. Na administração da loja acesse o menu Extensions->Extension Installer (Extensões->Instalador).
 3. Na página do instalador, clique no botão Upload e selecione o arquivo 'google-analytics-ecommerce.ocmod.zip' (que você baixou deste repositório), e aguarde a conclusão da instalação automática.
 5. Após a instalação, acesse o menu Extensions->Modifications (Extensões->Modificações) e clique no botão Refresh (Atualizar), para que a modificação instalada seja incrementada na loja, lembrando que não é o botão "Atualizar" do navegador, e sim o botão "Atualizar" na cor azul ao lado do botão laranja e vermelho na tela do próprio OpenCart.

### Utilização

Para que as informações sejam enviadas ao Google Analytics, o código gerado em sua conta no Google Analytics deve ser habilitado na loja através do menu System->Settings (Configurações->Lojas), aba "Server" (Servidor), campo "Google Analytics Code" (Código do Google Analytics).

Para que você possa visualizar os dados dos pedidos enviados para o Google Analytics, você deve habilitar o serviço de comércio eletrônico, para isso, acesse sua conta no Google Analytics e clique na aba "Administrador", no menu "Configurações de comércio eletrônico", e habilite o campo "Ativar comércio eletrônico".

Para visualizar os dados do pedido, acesse sua conta no Google Analytics e clique na aba "Relatórios", no menu "Conversões", submenu "Comércio Eletrônico".

Observação: Leva em média 24 horas para que os dados enviados comecem a ser visualizados.

### Desinstalação

Para desinstalar a modificação, na administração da loja, acesse o menu Extensions->Modifications (Extensões->Modificações) e selecione a modificação com o nome 'Integração com Google Analytics E-commerce.', depois clique no botão Delete (Excluir), e no botão Refresh (Atualizar).

### Atualização

Acesse a administração da loja e execute o procedimento de Desinstalação, depois execute o procedimento de Instalação.

### Dúvidas

O OCMod (OpenCart Modification) é nativo do OpenCart, ou seja, não é necessário instalar nenhum complemento no OpenCart para utilizar modificações ou extensões no formato OCMod, para mais informações sobre o OCMod, segue o link:

https://github.com/opencart/opencart/wiki/Modification-System

### Os arquivos alterados virtualmente através do OCMod são:

catalog/model/checkout/order.php

catalog/controller/checkout/success.php

catalog/view/theme/*/template/common/success.tpl

### Como contribuir

 1. Faça um Fork do projeto e edite os arquivos que desejar.
 2. Faça um Pull para que suas sugestões de melhorias sejam avaliadas e aceitas, caso aprovadas.
 3. Abra uma Inssue com sua dúvida ou sugestão.

### Licença

[GNU General Public License version 3 (GPLv3)](https://github.com/opencartbrasil/google-analytics-ecommerce/blob/master/LICENSE)
