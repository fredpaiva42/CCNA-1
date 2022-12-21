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