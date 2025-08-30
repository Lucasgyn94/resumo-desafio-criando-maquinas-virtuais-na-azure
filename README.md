# Resumo Laborátorio - Criando Máquinas Virtuais na Azur
* Neste laboratório tive a experiência prática de aprender a criação de uma Máquina Virtual com Windos Server no portal da da Azure.
* Durante a atividade, seguir os passos para provisionar uma nova VM, consolidando os seguintes conhecimentos:
1. **Conceitos de Disponibilidade (SLA): Antes de iniciar a criação da VM, foi importante que a instrutora revisasse os conceitos de __Acordo de Nível de Serviço (SLA)__. Compreendi como os diferentes percentuais de SLA (99%, 99,9%, 99,99%)se traduzem em tempo de inatividade permitido sendo assim muito importante escolhermos as opções de disponibilidade correta.
2. **Navegação e Acesso ao Recurso**: Iniciamos acessando o portal do azure e seguindo os seguintes passos:
  - Acessar __"Todos os Serviços"__ -> Categoria __"Computação"__ -> Selecionar 
__"Máquinas Virtuais"__
3. Seguindo os passos anteriores, estaremos agora no assistente de criação de VM, divido em abas, onde as principais configurações realizadas foram:

### Aba "Básico"
  * __Grupo de Recursos__: Criei um novo grupo de recursos para agrupar e gerenciar a VM de forma lógica.
  * __Detalhes da Instância__: Defini o nome da máquina virtual, a região, e as opções de disponibilidade.
  * __Imagem e Tamanho__: Selecionei a imagem do sistema operacional (Windows Server 2019) e o tamanho da VM.
  * __Conta do Administrador__: Configurei o nome de usuário e a senha para acessar a VM.

### Aba "Discos":
  * Escolhi o tipo de disco do SO.

### Aba "Rede":
  * Configurei a Rede Virtual, a sub-rede, e um Endereço IP público para que a VM pudesse ser acessada pela internet.

### Aba "Revisar + Criar"
  * Aqui é a última etapa, onde o Azure realiza uma validação de todas as configurações. Após confirmaos, o processo de provisionamento da máquina virtual e iniciado e em instantes teremos a mesma no ar para acesso.
