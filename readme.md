# CCNA 1

## Componentes de Rede
**Hosts**: Dispositivos conectados a uma rede que participam diretamente da comunicação da rede.

**IP (Internet Protocol)**: Identifica o host dentro de uma rede específica.

**Servidores**: São computadores com software que lhes permite fornecer informações, como email ou páginas web para outros dispositivos finais na rede.

Softwares comuns de servidores:
- Email
- Web
- Arquivos

Exemplo de software cliente: **navegador**.

**Rede ponto a ponto**: São redes em que temos computadores como servidor e clientes ao mesmo tempo.

Vantagens da **rede ponto a ponto**:
- Fácil de configurar
- Menos complexo
- Menor custo porque os dispositivos de rede e os servidores dedicados podem não ser necessários
- Pode ser usada para tarefas simples como transferir arquivos e compartilhar impressoras

Desvantagens da **rede ponto a ponto**:
- Nenhuma administração centralizada
- Não é tão segura
- Não é escalável
- Todos os dispositivos podem atuar como clientes e servidores, podendo deixar seu desempenho lento.

**Dispositivos Finais**: É a origem ou destino de uma mensagem transmitida na rede.

**Dispositivos Intermediários**: Conectam os dispositivos finais individuais à rede.

Exemplos de **dispositivos intermediários**:
- Roteador sem fio
- Roteador
- Switch LAN
- Switch Multicamada
- Dispositivo de firewall
  
Funções dos **dispositivos intermediários**:
- Regenerar e retransmitir sinais de comunicação
- Manter informação sobre quais caminhos existem pela rede e pela rede interconectada
- Notificar outros dispositivos sobre erros e falhas de comunicação
- Direcionar dados por caminhos alternartivos quando houver falha em um link
- Classificar e direcionar mensagens de acordo com as prioridades
- Permitir ou negar o fluxo de dados, com base em configurações de segurança

**Mídia ou meio de rede**: Fornece o canal pelo qual a mensagem viaja da origem ao destino.

Três tipos de mídia mais comuns:
- **Fios de metal dentro de cabos (cobre)**- Os dados são codificados em impulsos elétricos
- **Fibra de vidro ou plástico nos cabos (cabo de fibra óptica)** - Os dados são codificados em pulsos de luz
- **Transmissão sem fio** - Os dados são codificados através da modulação de frequências específicas de ondas eletromagnéticas

Critérios para a escolha da **mídia de rede**:
- Qual é a distância máxima pela qual o meio físico consegue carregar um sinal com êxito?
- Qual é o ambiente em que a mídia será instalada?
- Qual é a quantidade de dados e a que velocidade deve ser transmitida?
- Qual o custo do meio físico e da instalação

## Representações e topologias de rede
### Representação de Rede
![](Dispositovos%20e%20Meios%20de%20Rede.jpeg)

Terminologia para descrever como cada um desses dispositivos e mídias se conectam:
- **Placa de interface de rede (NIC)**: Uma NIC conecta fisicamente o dispositivo final à rede
- **Porta física**: Um conector ou tomada em um dispositivo de rede onde a mídia se conecta a um dispositivo final ou outro dispositivo de rede
- **Interface**: Portas especializadas em um dispositivo de rede que se conectam a redes individuais. Como os roteadores conectam redes, as portas em um roteador são chamadas de interface de rede.
  
### Topologia Física
Os diagramas de topologia física ilustam a localização física dos dispositivos intermediários e a instalação dos cabos.

![](Topologia%20Física.jpeg)

### Topologia Lógica
Diagramas de topologia lógica ilustram dispositivos, portas e o esquema de endereçamento da rede.

![](Topologia%20lógica.jpeg)

## Tipos comuns de redes

**Redes domésticas simples**: Conectam alguns computadores entre si e com a Internet. Permitem que se compartilhe recursos, como impressoras, documentos, imagens e música, entre alguns dispositivos finais locais.

**Redes para pequenos escritórios e escritórios domésticos (SOHO)**: Permite que computadores em um escritório em casa ou em um escritóirio remoto se conectem a uma rede corporativa, ou acessem recursos compartilhados centralizados.

**Redes médias e grandes**: Como as usadas por empresas ou escolas, podem ter muitos locais com centenas ou milhares de hosts interconectados. Fornecem consolidação, armazenamento e acesso a informações em servidores de rede.

**Rede Mundial**: A internet é uma rede de redes que conecta centenas de milhões de computadores em todo o mundo.

A **infra-estruturas** variam muito em termos de:
- Tamanho da área de cobertura
- Número de usuários conectados
- Número e tipos de serviços disponíveis
- Área de responsabilidade

**SPs**: provedores de serviços.

**ISPs**: provedores de serviços de Internet.

**LANs**: redes locais.

Características das **LANs**:
- Interconectam dispositivos finais em uma área limitada, como uma casa, uma escola, um edifício de escritórios ou um campus.
- Geralmente é administrada por uma única organização ou pessoa. O controle administrativo é imposto no nível da rede e governa as políticas de segurança e controle de acesso.
- Fornecem largura de banda de alta velocidade para dispositivos finais internos e dispositivos intermediários.

**WANs (Wide Area Network)**: redes de longa distância.

Características das **WANs**:
- Interconectam as LANs em grandes áreas geográficas, como entre cidades, estados, províncias, países ou continentes.
- Geralmente são administradas por vários prestadores de serviço.
- Geralmente fornecem links de velocidade mais lenta entre as LANs.

Organizações que ajudam a manter a estrutura e padronização dos protocolos e processos da Internet:
- Internet Engineering Task Force (IETF)
- Internet Corporation for Assigned Names and Numbers (ICANN)
- Internet Architeture Board (IAB)
- Etc...
  
**Intranet**: Uma conexão privada de LANs e WANs que pertencem a uma organização. É projetada para ser acessada apenas por membros da organização, funcionários ou outras pessoas autorizadas.

**Extranet**: Uma conexão para fornecer acesso segura e protegido a indivíduos que trabalham para uma organização diferente, mas exigem acesso aos dados da organização.

## Conexões com a Internet

Conexão comuns para usuários de pequenos escritórios e escritórios domésticos:
- **Cabo** - Normalmente oferecido por provedores de serviços de televisão a cabo, o sinal de dados da Internet transmite no mesmo cabo que fornece televisão a cabo. Ele fornece alta largura de banda, alta disponibilidade e uma conexão sempre ativa à internet.
- **DSL** - As linhas de assinante digital forncem alta largura de banda, alta disponibilidade e uma conexão sempre ativa à Internet. O DSL funciona utlizando a linha telefônica.
- **Celular** - O acesso celular à Internet usa uma rede de telefonia celular para se conectar. Onde quer que você possa obter um sinal de celular, você pode obter acesso à Internet por celular. O desempenho é limitado pelos recursos do telefone e da torre de celular à qual está conectado.
- **Satélite** - A disponibilidade do acesso à Internet via satélite é um benefício nas áreas em que, de outra forma, não teriam conectividade com a Internet. As antenas parabólicas exigem uma linha de visão clara para o satélite.
- **Conexão Discada (Dial - up)** - Uma opção de baixo custo que usa qualquer linha telefônica e um modem. Fornece baixa largura de banda, não recomendada caso seja necessário fazer grandes tranferências de dados, porém útil para acesso móvel durante a viagem.

Conexão comuns para empresas:
- **Linha Alugada Dedicada** - As linhas alugadas são circuitos reservados na rede do provedore de serviços que conectam escritórios geograficamente separados para redes privadas de vos e/ou dados. Os circuitos são alugados a uma taxa mensal ou anual.
- **Metro Ethernet ou Ethernet WAN** - As ethernet metropolitanas estendem a tecnlogia de acesso à LAN na WAN.
- **DSL de negócios** - O DSL comercial está disponível em vários formatos. Uma escolha popular é a linha de assinante digital simétrica (SDSL), que é semelhante a DSL do consumidor, mas fornece uploads e dowloads nas mesmas velocidades altas.
- **Satélite** - O serviço de satélite pode fornecer uma conexão quando uma solução com fio não está disponível.

**Redes Separadas Tradicionais**: São redes em que cada uma usa uma tecnologia diferente para transmitir o sinal de comunicação e não se comunicam entre si. Cada uma delas possuía seu próprio conjunto de regras e padrões para assegurar a comunicação bem-sucedida.

**Redes Convergentes**: Possuem a capacidade de fornecer dados, voz e vídeo entre muitos tipos diferentes de dispositivos na mesma infraestrutura de rede. Essa infraestrutura possui o mesmo conjunto de regras, contratos e normas de implementação.

## Redes Confiáveis
As quatro características básicas que uma arquitetura de rede deve atender:
- Tolerância a falhas
- Escalabilidade
- Qualidade do serviço (QoS)
- Segurança

Uma rede tolerante a falhas é aquela que limita o número de dispositivos afetados durante uma falha.

**Redundância**: Ter vários caminhos para um destino.

Uma rede escalável se expande reapidamente para oferecer suporte a novos usuáros e aplicativos. É importante que ela faça isso sem prejudir a experiência dos usuários já existentes.

**Qualidade do serviço**: É um mecanismo essencial para gerenciar os congestionamentos e garantir a entrega confiável do conteúdo para todos os usuário. Por exemplo, se um usuário está solicitando uma página Web e outro está em ligaçao. Com uma QoS configurada, o roteador é capaz de gerenciar o fluxo de trafégo de voz e de dados, priorizando as comunicações por voz se a rede ficar congestionada.

**Congestionamento**: Quando a demanda por largura de banda excede a quantidade disponível.

Os administradores de redes precisam abordar dois tipos de preocupações de segurança de rede: **Segurança da infraestrutura da rede** e **segurança da informação**.

Proteger a infraestrutura da rede inclui proteger fisicamente os dispositivos que fornecem conectividade de rede e impedir o acesso não autorizado ao software de gerenciamento que reside neles.

Existem três requisitos principais para atingir a segurança da rede:
- **Confidencialidade**: Significa que apenas os destinatários pretendidos e autorizados podem acessar e ler dados.
- **Integridade**: Garante aos usuários que as informações não foram alterada nas transmissão, da origem ao destino.
- **Disponibilidade**: Garante aos usuários acesso oportuno e confiávrl aos serviços de dados para usuários autorizados.

## Tendências Recentes

**(BYOD) Traga seu próprio dispositivo**: permite aos usuários finais a liberdade de usar ferramentas pessoais para acessar informações e se comunicar atráves da rede comercial ou do campus. BYOD significa o uso de qualquer dispositivo, de qualquer propriedade e em qualquer lugar.

**Colaboração On-line**: "Ato de trabalho com outro ou outros em projeto em parceria". As ferramentas de colaboração oferecem aos usuários uma maneira de conectar, interagir e alcançar instantaneamente seus objetivos.

**Comunicações em vídeo**.

**Computação em Nuvem**: é uma maneira para acessar e armazenar dados. Para empresas, ela amplia os recursos de TI sem exigir investimento em nova infraestrutura, treinamento de novas equipes ou licenciamento de novo software. Esses serviços estão disponíveis sob demanda e são entregues a qualquer dispositivo, sem comprometer segurança ou a sua função. São possíveis graças aos Data Centers.

**Data Centers**: São instalaçÕes usadas para hospedar sistemas de computador e componentes associados.

Existem quatro tipos principais de **nuvens**:
- **Nuvens públicas**: São fonecidos para o público geral, podem ser gratuitos ou em um modelo de pagamento por uso. Usa a internet para fornecer serviços.
- **Nuvens privadas**: Destinados a uma organizacão ou entidade específica, como um governo. Pode ser configurada usando a rede, mas é caro para contruir e manter. Pode ser gerenciada por uma organização externa com acesso estrito de segurança.
- **Nuvens híbridas**: Composta de duas ou mais nuvens (parte privada e parte pública), onde cada parte permanece um objeto distinto, mas ambas estão conectadas usando uma única arquitetura. Indivíduos em uma nuvem híbrida seriam capazes de ter graus de acesso a vários serviços com base em direitos de acesso do usuário.
- **Nuvens comunitárias**: Criada para uso exclusivo por entidades ou organizações específicas. A diferença entre a pública e comunitária são as necessidades funcionais que foram personalizadas para a comunidade. São semelhantes a um ambiente de nuvem pública, mas com níveis definidos de segurança, privacidade e até mesmo conformidade normatica de uma nuvem privada.

**Rede Porwerline**: Para redes domésticas usa a fiação elética existente para conectar dispositivos. É uma alternativa quando os cabos da rede de dads ou as comunicações sem fio não são possíveis ou eficazes.

**Banda Larga Sem Fio**: Pode ser usada em áreas em que cabo e DSL não estão disponíveis.

**Provedor de serviços de Internet sem fio (WISP)**: é um provedor que conecta assinantes a um ponto de acesso ou hot spot designado usando tecnologias sem fio semelhantes encontradas em redes locais sem fio domésticas (WLABs). São mais comuns em ambientes rurais.

**Serviço de banda larga sem fio**: Usa a mesma tecnologia celular que um telefone inteligente. Uma antena é instalada fora da residência, fornecendo conectividade com ou sem fio para os dispositivos na casa.

## Segurança de Redes

Ameaças esxternas comuns às redes:
- **Vírus, worms e cavalos de Tróia** - Eles contêm software ou código malicioso em execução no dispositivo do usuário.
- **Spyware e adware** - Estes são tipos de software que são instalados no dispositivo de um usuário. O softwre, em seguida, coleta secretamente informações sobre o usuário.
- **Ataques de dia zero**: Ocorrem no primeiro dia em que uma vulnerabilidade se torna conhecida.
- **Ataques de ator de ameaça**: Uma pessoa mal-intencionada ataca dispositivos de usuários ou recursos de rede.
- **Ataques de negação de serviço**: Esses ataques atrasam ou travam aplicativos e processos em uma dispositivo de rede.
- **Interceptação de dados e roubo**: Esse ataque captura informações privadas da rede de uma organização.
- **Roubo de identidade** - Esse ataque rouba as credenciais de login de um usuário para acessar informações privadas.

Componentes básicos de segurança para uma rede doméstica ou de pequeno escritório:
- **Antivirus e antispyware** - Esses aplicativos ajudam a proteger os dispositivos finais contra a infecção por software malicioso.
- **Filtragem por firewall** - A filtragem por firewall bloqueia o acesso não autorizado dentro e fora da rede. Isso pode incluir um sistema de firewall baseado em host que impede o acesso não autorizado ao dispositivo final ou um serviço básico de filtragem no roteador doméstico para impedir o acesso não autorizado do mundo externo à rede.
  
Componentes para segurança de uma rede comercial (Além dos componentes que são usados numa rede doméstica):
- **Sistemas de firewall dedicados**: Eles fornecem recursos de firewall mais avançados que podem filtrar grandes quantidades de tráfego com mais granularidade.
- **Listas de controle de acesso (ACL)** - Eles filtram ainda mais o acesso e o encaminhamento de tráfego com base em endereços e aplicativos IP.
- **Sitemas de prevenção de intrusões (IPS)** - Identificam ameaças de rápida disseminação, como ataques de dia zero ou hora zero.
-  **Redes privadas virtuais (VPN)** - Fornecem acesso seguro a uma organização para trabalhadores remotos.

## Sistemas Operacionais

Todo disposito final e de rede exige um SO.

**Hardware**: Parte fisíca de um computador, incluindo os componentes eletrônicos subjacentes.

**Kernel**: Comunica-se entre o hardware e o software de um computador e gerencia como os recursos de hardware são usados para atender aos requisitos de software.

**Shell**: Interface do usuário que permite que os usuários solicitem tarefas específicas do computador. Essas solicitações podem ser feitas por meio das interface CLI ou GUI

**CLI**: Interface de linha de comando, serve para que o usuário interaja com a shell.

**GUI**: Interface Gráfica do Usuário.

## Métodos de Acesso

**Console**: Esta é uma porta de gerenciamento físico que forece acesso fora de banda a um dispositivo Cisco. O acesso out-of-band refere-se ao acesso por meio de um canal dedicado de gerenciamento que é utilizado somente para fins de manutenção do dispositivo. A vantagem de usar uma porta do console é que o dispositivo está acessível mesmo que nenhum serviço de rede esteja configurado, como a configuração inicial. Um computador executando um software de emulação de terminal e um cabo de console especial para se conectar ao disposito são necessários para uma conexão de console.

**Secure Shell (SSH)**: É um método dentro da banda e recomendado para estabelecer remotamente uma conexão CLI segura, através de uma interface virtual, através de uma rede. Requerem serviços de rede ativos no dispositivo, incluindo uma interface ativa configurada com um endereço. A maioria das versões do Cisco IOS inclui um servidor SSH e um cliente SSH que podem ser usados para estabelecer sessões de SSH com outros dispositivos.

**Telnet**: É um método inseguro em banda para estabelecer remotamente uma sessão CLI, por meio de uma interface virtual, por uma rede. O Telnet não fornece uma conexão segura e criptografada e só deve ser usado em um ambiente de laboratório. A autenticação de usuário, as senhas e os comandos são enviados pela rede como texto simples. A melhor prática é usar SSH em vez de Telnet.

**Aux**: A porta AUX em um disposito Cisco fornece conexões fora de banda por uma linha telefônica.

## Programas de Emulação de Terminal

São usados para se conectar a um disposito de rede por uma conexão serial por uma porta do console ou por uma conexão SSH/Telnet.

Exemplos:
- PuTTY
- Tera Term
- SecureCRT

## Modos de Comando Primários

Como recurso de segurança, o software Cisco IOS separa o acesso de gerenciamento em dois modos de comando.

**Modo EXEC de usuário**: Possui recursos limitidados, mas é útil para operações básicas. Permite apenas um número limitado de comandos de monitoramento básicos, mas não permite a execução de nenhum comando que possa alterar a configuração do dispositivo. O modo EXEC usuário é identificado pelo prompt da CLI que termina com o símbolo `>`.

**Modo Exec privilegiado**: Para executar comandos de configuração, um administrador de rede deve acessar esse modo. Modos de configurações mais altos, como o modo fe configuração global, só podem ser acessados do modo Exec privilegiado. Esse modo pode ser identificado pelo prompt que termica com o símbolo `#`.

## Modo de configuração e modos de subconfiguração

Para configurar o dispositivo, o usuário deve entrar no modo de configuração global.

Nesse modo são feitas alterações na configuração via CLI que a afetam o funcionamento do dispositivo como um todo. O modo de configuração global é identificado por um prompt que termina com `(config)#` após o nome do dispositivo, como `Switch(config)#`.

No modo de configuração global, o usuário pode inserir diferentes modos de subconfiguração. Cada um desses modos permite a configuração de uma parte particular ou função do dispositivo IOS.

Exemplos:
- **Modo de configuração de linha**: Usado para configurar o acesso ao console, SSH, Telnet ou AUX.
- **Modo de configuração da interface**: Usado para configurar uma porta de switch ou interface de rede do roteador.

## Navegar entre os Modos do IOS

Para passar do modo **EXEC usuário** para **Exec privilegiado** o comando é `enable`, e para retornar para **Exec usuário** é `disable`.

Para entrar e sair do **modo de configuração global**: `configure terminal` no modo **Exec privilegiado** e para sair basta digitar `exit`.

Para entrar no **modo subconfiguração de linha**: `line tipo de acesso numero da linha de gerenciamento que deseja acessar`, `line console 0`. Use o comando `exit` para sair.

Para passar de qualquer **modo de subconfiguração** para o **modo de configuração global** o comando é `exit`.

Para passar de qualquer **modo de subconfiguração** para o **Exec privilegiado** o comando é `end` ou `Ctrl + Z`.

Também é possível passar de um **modo de subconfiguração** para outro.

## Estrutura Básica de Comandos do IOS

Cada comando do IOS possui um formato ou sintaxe específica e pode ser executado apenas no modo apropriado.

### Sintaxe geral de um comando:
![](Sintaxe%20geral%20dos%20comandos.jpeg)
- **Palavra-chave**: Este é um parâmetro específico definido no sistema operacional (na figura, protocolos ip)
- **Argumento**: Isso não é predefinido; é um valor ou variável definido pelo usuário (na figura, 192.168.10.5)

## Verificando a sintaxe dos comandos do IOS
- **Negrito**: o texo em negrito indica comandos e palavras-chave que você digita literalmente como mostrado.
- *itálico*: o texo em itálico indica argumentos para os quais você fornece valores.
- **[x]**: colchetes indicam um elemento opcional (palavra-chave ou argumento).
- **{x}**: chaves indicam um elemento necessário (palavra-chave ou argumento).
- **[x {y | z }]**: chaves e linhas verticais entre colchetes indicam uma necessidade dentro de um elemento opcional. Espaços são usados para delinear claramente partes do comando.

Exemplos que demonstram as convenções usadas para documentar e utilizar comandos do IOS:
- **ping** *ip-address* - O comando é **ping** e o argumento definido pelo usuário é o *endereço-IP* do dispositivo de destino. Por exemplo: `ping 10.10.10.5`.
- **traceroute** *ip-address* - O comando é **tracerout** e o argumento definido pelo usuário é o *endereço-IP* do dispositivo de destino. Por exemplo: `traceroute 192.168.254.254`.
  
## Recursos da Ajuda do IOS

O IOS tem duas formas de ajuda disponíveis: **ajuda sensível ao contexto** e **verificação da sintaxe do comando**.

A ajuda sensível ao contexto permite que você encontre resposta para as seguintes perguntas:
- Quai comandos estão disponíveis em cada modo de comando?
- Quais comandos começam com caracteres específicos ou grupo de caracteres?
- Quais argumentos e palavra-chave estão disponíveis para comandos específicos?

Para acessar a **ajuda sensível ao contexto**, basta inserir um ponto de interrogação, **?**, na CLI.

A **verificação da sintaxe de comando** verifica se um comandos válido foi inserido pelo usuário. O interpretador faz a verificação do comando da esquerda para a direita, se ele entende o comando, ele é executado e a CLI volta para o prompt apropriado. No entanto, se o interpretador não entender o comando, ele forncerá feedback descrevendo o que está errado com o comando.

## Teclas de Atalho e Atalhos
- **Tab**: Completa um nome de comando parcialmente digitdado.
- **Backspace**: Apaga o caractere à esquerda do cursor.
- **Ctrl + D**: Apaga o caractere no cursor.
- **Ctrl + K**: Apaga todos os caracteres do cursor até o final da linha de comando.
- **Esc D**: Apaga todos os caracteres do cursor até o final da palavra.
- **Ctrl + U ou Ctrl + X**: Apaga todos os caracteres do cursor de volta ao início do linha de comando.
- **Ctrl + W**: Apaga a palavra à esquerda do cursor.
- **Ctrl + A**: Move o cursor para o início da linha.
- **Seta esquerda ou Ctrl + B**: Movem o cursor um caractere para a esquerda.
- **Esc B**: Move o cursor uma palavra para a esquerda.
- **Esc F**: Mode o cursor uma palavra para a direita.
- **Seta direita ou Ctrl + F**: Movem o cursor um caractere para a direita.
- **Ctrl + E**: Move o cursor para o final da linha de comando.
- **Seta cima ou Ctrl + P**: Recupera os comandos no buffer do histórico, começando com o mais recente.
- **Crtl + R ou I ou L**: Exibe novamente o prompt do sistema e a linha de comando depois que uma mensagem do console é exibida.
- **Tecla Enter**: Exibe a próxima linha
- **Barra de Espaço**: Exibe a próxima tela
- **Qualquer outra chave**: Encerra a sequência de exibição, retornando ao modo Exec privilegiado.
- **Ctrl + C**: Sai de uma operação, quando em qualquer modo de configuração, finaliza o modo de configuração e retorna para o modo Exec privilegiado. Quando no modo de instalção, aborta de volta ao comando pronto.
- **Ctrl + Z**: Sai de uma operação, quando em qualquer modo de configuração, finalização ou modo de configuração e retornos para o modo Exec privilegiado.
- **Ctrl + Shift + 6**: Sequência de quebra para todas as finalidades usada para abortar pesquisas de DNS, tracerouts, pings, etc.

## Configuração básica de dispositivos

### Nomes de Dispositivo

Algumas diretrizes para nomear os dispositivos:
- Começar com uma letra
- Não conter espaços
- Terminar com uma letra ou dígito
- Usar somente letras, números e traços
- Ter menos de 64 caracteres

Para nomear um dispositivo basta entrar no modo de configuração global e usar o comando `hostname nome do dispositivo`, para voltar para o prompt padrão `no hostname`.

### Diretrizes de senha

O Cisco IOS pode ser configurado para usar senhas do modo hierárquico para permitir privilégios de acesso diferentes a um dispositivo de rede.

Recomendações para escolha de senhas:
- Senhas com mais de 8 caracteres
- Combinação de maiúsculas e minúsculas, números, caracteres especiais e/ou sequências númericas
- Evitar usar a mesma senha para todos os dispositivos
- Não usar palavras comuns, pois são facilmente advinhadas

Para proteger o acesso ao modo EXEC do usuário:
- Entrar no modo de configuração global
- Entrar no modo de subconfiguração em linha, exemplo: `line console 0`
- Usar o comando `password` seguido da senha desejada
- Usar o comando `login`
- Sair usando o comando `end`
- E pronto, agora ao acessar o console vai ser exigido uma senha

Para proteger o acesso EXEC privilegiado:
- Entrar no modo de configuração global
- usar o comando `enable secret` seguido da senha desejada
- Sair do modo usando `exit`
- Pronto
  
As linhas de terminal virtual (VTY) permitem acesso remoto usando Telnet ou SSH ao dispositivo. Muitos switches Cisco são compativeis com até 16 linhas VTY numeradas de 0 a 15.

Para proteger linhas VTY:
- Entrar no modo de configuração global
- entrar no VTY de linha usando o comando `line vty 0 15`
- Usar o comando `password` seguido da senha desejada
- Ativar o acesso com o comando `login`
- Sair com o comando `end`

### Criptografar as Senhas

Os arquivos **startup-config** e **running-config** exibem a maioria das senhas em texto simples. Esta é uma ameaça a segurança.

Para criptografar todas as senhas de texto simples:
- Entrar no modo de configuração global
- Usar o comando `service password-encryption`
- Para verificar se as senhas foram ciptografadas basta usar o comando `show running-config`

### Mensagens de Banner

É vital fornecer um método para declarar que apenas pessoal autorizado deve tentar acessar o dispositivo. Banners podem ser uma parte importante do processo legal caso alguém seja processado por invadir um dispositivo. Alguns sistemas legais não permitem processo, ou mesmo o monitoramento de usuários, a menos que haja uma notificação visível.

Para criar uma mensagem de banner em um dispositivo de rede:
- Acesse o modo de configuração global
- Use o comando `banner motd #mensagem que será mostrada#`
  
## Salvar configurações
### Arquivos de configuração

Existem dois arquivos que armazenam a configuração do dispositivo:
- **startup-config**: Este é o arquivo de configuração salvo armazenado na NVRAM. Ele contém todos os comandos que serão usados pelo dispositivo na inicialização ou reinicialização. O flash não perde seu conteúdo quando o dispositivo está desligado.
- **running-config**: Isto é armazenado na memória de acesso aleatório (RAM). Ele reflete a configuração atual. A modificação de uma configuração ativa afeta o funcnionamento de um dispositivo Cisco imediatamente. A RAM é uma memória volátil. Ela perde todo o seu conteúdo quando o dispositivo é desligado ou reiniciado.

No tópico anterior já tem como ver a configuração de execução.

Para visualizar o arquivo de configuração de inicialização: `show startup-config`.

Para salvar as alterações feitas na configuração:
- Dentro do modo EXEC privilegiado usar o comando `copy running-config startup-config`.

### Alterar a configuração ativa

Se as alterações ainda não tiverem sido salvas, podemos restaurar o dispositivo para a configuração anterior usando o comando `reload` dentro do modo EXEC privilegiado, isso restaura as configurações do startup-config.

Quando usamos o `reload` para remover uma configuração, o dispositivo fica offline por um breve período de tempo.

Caso as alterações tenha sido salvas, dentro do modo EXEC privilegiado vamos usar o comando `erase startup-config`. Após isso, devemos recarregar o dispositivo para remover o arquivo de configuração atual em execução na RAM. Ao reiniciar, um switch carragará a configuração de inicialização padrão que foi fornecida originalmente com o dispositivo.

## Portas e Endereços

### Endereços IP

Endereços IP permitem que os dispositivos possam se localizar e estabeler uma comunicação ponto a ponto na internet. Cada dispositivo final deve ser configurado com um endereço de IP.

Exemplos de dispositivos finais que precisam ter um IP:
- Computadores
- Impressoras de rede
- Telefones VoIP
- Câmeras de segurança
- Smartphones
- Dispositivos móveis portáteis

A estrutura de um endereço **IPv4** é chamada notação decimal com ponto e é representada por quatro números decimais entre 0 e 255. Os endereços **IPv4** são atribuidos individualmente a dispositivos conectados a uma rede.

Com o endereço **IPv4**, uma máscara de sub-rede também é necessária. Uma máscara de sub-rede **IPv4** é um valor de **32 bits** que diferencia a parte da rede do endereço da parte do host. Juntamente com o endereço **IPv4**, a máscara de sub-rede determina qual sub-rede p dispositivo é membro.

**Endereço de gateway**: é o endereço IP do roteador que o host usará para acessar redes remotas, incluindo a internet.

#### Exemplo IPv4
![](Exemplo%20de%20IPv4.jpeg)

#### Exemplo IPv6
Os endereços **IPv6** têm **128 bits** e são escritos como uma sequência de valores hexadecimais. A cada quatro bits é representado por um único dígito hexadecimal; para um total de **32 valores hexadecimais**. Grupos de quatro dígitos hexadecimaissão separados por dois pontos (:). Os endereços **IPv6** não diferenciam maiúsculas e minúsculas e podem ser escritos tanto minúsculas como em maiúsculas.

![](Exemplo%20IPv6.jpeg)

### Interfaces e Portas

As comunicações em rede dependem de interfaces do dispositivo de usuário final, interfaces do dispositivo de rede e cabos que as conectam. Cada interface física tem especificações ou padrões que a definem. Um cabo conectado à interface deve ser projetado de acordo com os padrões físicos da interface. Os tipos de mídia de rede incluem cabos de cobre de par trançado, cabos de fibra óptica, cabos coaxiais ou sem fio.

Difierentes tipos de meio físico de rede oferecem características e benefícios diferentes. Nem todas as mídias de rede têm as mesmas características. Nem todas as mídias são apropriadas para o mesmo propósito.

Algumas diferenças entre os vários tipos de mídia:
- A distância pela qual o meio físico consegue carregar um sinal com êxito
- O ambiente no qual o meio físico deve ser instalado
- A quantidade e a velocidade de dados nas quais eles devem ser transmitidos
- O custo do meio físico e da instalação
  
## Configurar Endereços IP

### Configuração Manual de Endereço IP para dispositivos finais

As informações de endereço **IPv4** podem ser inseridas nos dispositivos finais manualmente ou automaticamente usando o **DHCP (Dynamic Host Configuration Protocol)** .

Para configurar manualmente um endereço **IPv4** em um host do Windows:
- Abrir o painel de controle
- Centro de compartilhamento de rede
- Mudar as configurações do adaptador e escolher o adaptador.
- Clicar com o botão direito do mouse e selecionar propriedades
- Destacar **Internet Protocol Version 4 (TCP/IPv4)** e clicar em propriedades
- Configurar as informações de endereço IPv4 e máscara dse sub-rede e o getway padrão.

Para configurar **IPv6** os passos são semelhantes.

### Configuração Automática de Endereço de IP para dispositivos finais

Os dispositivos finais geralmente usam o DHCP para configuração automática de endereço **IPv4**.

Em uma rede, o DHCP habilita a configuração automática de endereço IPv4 para todos os dispositivos finais habilitados para DHCP.

Para configurar DHCP em um PC Windows, basta selecionar **Obter um Endereço de IP automaticamente** e **Obter endereço do servidor DNS automaticamente**.

Para exibir as definições de configuração de IP em um PC com Windows, basta usar o comando **ipconfig** no prompt de comando.

### Configuração da Interface Virtual de Switch

Para configurar um SVI em um switch, use o comando `interface vlan 1` no modo de configuração global. Em seguida, atribua um endereço IPv4 usando o comando `ip address ip-address subnet-mask`. Por fim, ative a interface virtual usando o comando `no shutdown`.

Para configurar o default-gateway: `ip default-gateway ip-address`. 