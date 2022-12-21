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

**Dispositiovos Intermediários**: Conectam os dispositivos finais individuais à rede.

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