# AZ-900
Documentação dos laboratórios desenvolvidos para a conclusão do Bootcamp AZ-900

## [Criando máquinas virtuais na Azure](https://learn.microsoft.com/pt-br/azure/virtual-machines/windows/quick-create-portal)
Na página de criação de Máquinas Virtuais do Portal Azure, preencheremos o formulário com as configurações desejadas para a nossa VM.

Em <b>Detalhes do Projeto</b> podemos informar a assinatura (<b>Azure subscription</b>) e o grupo de recursos a qual esse recurso será associado.

Em <b>Detalhes da Instância</b> podemos informar:
* Nome da máquina virtual
* Região em que desejamos que ela esteja alocada
* Opção de disponibilidade
    * Define as replicações disponibilizadas pela Azure para garantir a resiliência da aplicação.
    * Dependendo do tipo de disponibilidade escolhido, você terá mais opções para configurar a redundância do seu recurso.
* Tipo de segurança
* Imagem da VM
* Outras configurações...

Em <b>Conta de administrador</b>, você deve fornecer um nome de usuário e senha para o login de administrador da sua VM.

Em <b>Regras de portas de entrada</b>, você poderá selecionar quais portas da sua VM podem ser acessadas pela internet pública.

Quando tiver completado sua configuração, clique em Revisar + criar. Você será encaminhado para uma página em que poderá revisar todas as suas configurações e também valida-las para e enfim <b>criar seu recurso</b>.
