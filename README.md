# resumo-lab-dio-azure
Essas anotações são referentes a meu resumo sobre o conteúdo apresentado no curso: Microsoft 50 anos - Computação em Nuvem com Azure, oferecida pela DIO, para elaboração do primeiro LAB.

<p align="center">
  <img src="https://i0.wp.com/imgs.hipertextual.com/wp-content/uploads/2021/05/Popular-Electronics-January-1975-Altair-8800.jpg?resize=1568%2C1045&quality=50&strip=all&ssl=1" alt="Capa da revista Popular Electronics com o Altair 8800" width="600">
</p>

<p align="center">
  <strong>Revista Popular Electronics (1975)</strong><br>
  Primeira aparição do Altair 8800, considerado o início da era dos computadores pessoais.
</p>

---

## Microsoft: 50 anos de inovação tecnológica
Microsoft faz 50 anos, e no aniversário desta big tech, que inclusive, em 2023 se tornou a empresa mais valiosa e influente do mundo, vale a pena, além de falarmos acerca do Microsoft Azure — que é o objeto deste repositório —, discorrer um pouco sobre como esta empresa contribuiu e ainda contribui de forma tão significativa para a evolução tecnológica que presenciamos atualmente.

Em 1975, foi lançado pela empresa MITS o Altair 8800, um microcomputador que marcou o início da revolução dos computadores pessoais (Personal Computers). Foi diante desse marco que Bill Gates e Paul Allen enxergaram uma oportunidade: criar um interpretador da linguagem BASIC para esse novo dispositivo. Essa iniciativa deu origem à "Micro-Soft", empresa voltada à produção de software para microcomputadores, estabelecendo os primeiros passos de uma história de impacto global.

Ao longo da década de 1980, a Microsoft deu saltos significativos, como o licenciamento do sistema operacional MS-DOS para a IBM em 1980 — o que consolidou sua posição no mercado de sistemas operacionais. Em 1985, a empresa lançou o Microsoft Windows, um sistema com base em janelas interativas e ícones gráficos, facilitando a navegação e a usabilidade para o usuário comum. Junto com o surgimento do mouse, esses elementos redefiniram a forma como interagimos com os computadores.

Desde então, a Microsoft esteve presente em cada etapa importante da evolução da tecnologia, desde o software de produtividade até os ambientes corporativos. Hoje, a empresa lidera o setor de soluções em inteligência artificial e computação em nuvem, com produtos como o Microsoft Copilot, a parceria estratégica com a OpenAI e a consolidação da plataforma Azure como uma das mais robustas e confiáveis do mundo.

<span style="color:DodgerBlue"> **A nuvem surgiu como uma resposta à crescente necessidade de aplicações e serviços com alta disponibilidade, escalabilidade e performance. Nesse cenário, a Microsoft se destaca por oferecer uma infraestrutura madura, segura e altamente confiável, permitindo que empresas de todos os tamanhos desenvolvam, operem e inovem em escala global dentro do seu ecossistema integrado.** </span>


## Introdução à Computação em Nuvem
A computação em nuvem é um modelo de serviço em que recursos como armazenamento, processamento de dados, software e redes são disponibilizados via internet (a nuvem), substituindo a necessidade de servidores e data centers locais (on-premise).
Por meio da nuvem, empresas e usuários podem acessar recursos computacionais sob demanda, pagando apenas pelo que utilizam eliminando a necessidade de grandes investimentos em infraestrutura física própria.

## Modelos de Infraestrutura

![Comparação de Infraestruturas](imagens/Comparação%20de%20Infraestruturas.jpg)


Existem três principais cenários em relação à infraestrutura de servidores:

- **On-Premise**: Toda a infraestrutura é mantida localmente.
- **Híbrido (Hybrid)**: Combinação de recursos locais com recursos em nuvem.
- **Cloud-Native**: Toda a infraestrutura está na nuvem, utilizando modelos *As a Service* (AaS).

## Comparativo: On-Premise

No modelo **on-premise**, a empresa é responsável por toda a infraestrutura necessária, incluindo:

- Aquisição e manutenção de máquinas
- Espaço físico e refrigeração
- Rede (cabeamento, conectividade)

### Vantagens

- Maior controle e personalização
- Segurança reforçada (ambiente privado)

### Desvantagens

- Alto custo inicial e de manutenção
- Risco de subutilização (máquinas ociosas)
- Depreciação dos ativos de TI

Este modelo é mais indicado para empresas que:

- Não podem tolerar instabilidades operacionais
- Precisam manter controle total sobre os dados (conformidade legal)
- Desejam evitar a dependência de terceiros

## Comparativo: Cloud

No modelo **cloud**, a infraestrutura é baseada na internet e os recursos são ofertados por um provedor externo.

### Vantagens


- Economia: uso sob demanda do serviço (pago pelo uso)
- Capacidade de crescer ou diminuir recursos (CPU, memória, armazenamento, usuários simultâneos etc.) conforme a necessidade nas modalidades:
  - Scale‑up: aumentar recursos em uma única máquina (ex.: mais memória)
  - Scale‑out: adicionar mais máquinas ao sistema (ex.: mais servidores)
- Adaptação do ambiente de TI de forma rápida (infraestrutura, serviços, configurações) permitindo testar novas soluções, mudar configurações e trocar tecnologias com mais liberdade, conforme as necessidades do negócio, sem grandes restrições técnicas.
- Velocidade para entregar valor, lançar novos produtos e ajustar processos. Através da automação, provisionamento rápido e integração contínua, acelera os ciclos de desenvolvimento e entrega.



### Desvantagens

- Dependência de conexão com internet
- Problemas com latência, dependendo da localização
- Necessidade de se adaptar às políticas e limitações impostas pelo provedor de nuvem.
- Gasto dolarizado e valor elevado para uso de determinados serviços como processamento de imagem e vídeo, armazenamento e streaming de dados


## Comparativo: Hibrido (Hybrid)

No modelo **hibrido**, temos a combinação dos modelos on-premise e cloud. Nesse caso, uma empresa mantém parte de sua infraestrutura local, enquanto usa serviços de nuvem para outras operações , criando uma combinação de recursos internos e externos.

### Vantagens

- Flexibilidade de escolher o que fica onde, de acordo com as necessidades. (Uma empresa pode manter dados sensíveis em servidores próprios "on-premise" e, ao mesmo tempo, usar a nuvem para hospedar aplicativos ou serviços que exigem mais escalabilidade.

### Desvantagens

- Complexidade de gestão e custo elevado

## Qual modelo escolher?

No final das contas, não há um melhor modelo e sim aquele que melhor se enquadra às necessidades e modelo de negócio de cada empresa, principalmente em termos de:
- Dependência de terceiros
- Conformidade legal, principalmente no tocante aos dados
- Controle
- Disponibilidade

➜ No modelo **on-premise**, instituições como bancos tradicionais e órgãos governamentais frequentemente mantêm sua infraestrutura local para garantir maior controle sobre dados sensíveis e atender a exigências de conformidade e segurança.

➜ No modelo **cloud**, empresas como Netflix e Nubank utilizam infraestrutura totalmente baseada em nuvem para escalar suas aplicações globalmente.

➜ No modelo **híbrido**, empresas como IBM e grandes operadoras de telecomunicações combinam servidores locais com recursos em nuvem para equilibrar segurança, desempenho e escalabilidade de acordo com as necessidades de cada operação.

---

## Platforms

Plataformas de computação em nuvem, conhecidas como cloud platforms, são empresas que oferecem ambientes completos de infraestrutura, ferramentas e serviços para que outras empresas possam construir, hospedar, escalar e operar suas aplicações digitais. Elas funcionam como "locadoras" de tecnologia — da mesma forma que uma empresa de veículos fornece carros para motoristas de aplicativo, essas plataformas fornecem poder computacional, armazenamento, rede e inteligência artificial para desenvolvedores, startups e grandes corporações.

Entre os principais exemplos de plataformas estão:

- AWS (Amazon Web Services) – da Amazon

- Microsoft Azure – da Microsoft

- Google Cloud Platform (GCP) – da Google

- Oracle Cloud – da Oracle Corporation

Essas plataformas permitem que empresas de todos os tamanhos inovem rapidamente, sem precisar investir pesado em infraestrutura física própria.

Aqui é válido citar a diferença entre **Data Centers x Platforms**: 

**➜ Data center (centro de dados):**
É a infraestrutura física, o "prédio" cheio de servidores, roteadores, cabos, sistemas de refrigeração, segurança, etc. Ele abriga os equipamentos que processam e armazenam dados. Pode ser:

  - Local (on-premise), dentro da própria empresa;  
  - Remoto, operado por terceiros.

**➜ Platform (plataforma de nuvem):**
É uma camada de serviços construída sobre data centers. Ela abstrai toda a complexidade física dos servidores e oferece ferramentas prontas para que empresas possam:

- Criar e hospedar sites e aplicativos;
- Armazenar dados com segurança;
- Processar grandes volumes de informação;
- Usar inteligência artificial, IoT, análise de dados, etc.

Ou seja:

Plataformas como Azure, AWS e GCP são grandes orquestradoras de data centers, oferecendo esses recursos como serviços (modelo "as a Service").
Comparando com um exemplo:
Se o data center é como uma usina elétrica (infraestrutura),
a plataforma é como a companhia de energia que entrega eletricidade sob demanda, com suporte, medição, distribuição e serviços extras.

---

 ## Regions e Zones

 As clouds criaram uma solução muito inteligente. Para diminuir o problema de latência, criaram regiões (regions) e zonas (zones) de disponibilidade, ou seja, ao invés de ter todas as máquinas em um só lugar, as platforms distribuem pelo mundo regiões que possuem concentração de data centers.

 ![Regions e Zones](imagens/Regions%20e%20Zones.jpg)


**Region (Região)**

É um local geográfico onde a nuvem possui data-centers.
Exemplo: São Paulo (América do Sul), Virginia (EUA), Frankfurt (Alemanha).

Escolher a região mais próxima de seus usuários ou da sua empresa para melhorar a velocidade e atender leis locais (proteção de dados)

**Zone (Zonas de Disponibilidade)** 

Dentro de uma região , existem subdivisões, como bairros dentro das cidades (Region). São Data Centers isolados, mas interconectados.
Exemplo: Região de São Paulo
  - Zona 1: SA-EAST-1A
  - Zona 2: SA-EAST-1B

### Para que serve?
Usamos **zonas diferentes** para garantir *alta disponibilidade*. Se uma zona falhar (queda de energia, por exemplo), a outra continua funcionando.

Ter recursos em **regiões diferentes** pode ser mais caro e complexo, mas é uma estratégia importante em algumas situações. Abaixo apresento alguns cenários em que usar múltiplas regiões pode ser interessante:

1) **Alta Disponibilidade Global (Redundância Geográfica):** Caso a aplicação não possa falhar de jeito nenhum, nesse caso, mesmo se uma região inteira falhar, distribuir entre regiões garante continuidade dos serviços.
2) **Melhor performance para usuários em diferentes localizações do mundo:** Possibilidade de manter réplicas dos seus sistemas em regiões próximas de cada grupo de usuários para diminuir a latência (tempo de resposta).
3) **Conformidade com Leis Locais (Compliance):** Alguns países exigem que dados sensiveis fiquem armazenados localmente. Exemplo: Clientes europeus podem exigir que os dados fiquem dentro na União Européia devido a GDPR (General Data Protection Regulation), logo, o indicado seria usar a região de Frankfurt ou Paris para armazenar dados desses clientes.
4) **Disaster Recovery/DR:** Possibilidade de manter uma cópia da infraestrutura em outra região para ativação rápida caso a principal caia.
5) **Fusões ou Operações Globais:** Empresas multinacionais, ou que fizeram fusão com outra empresa podem manter serviços ativos em várias regiões, enquanto integram os sistemas.

---

# Computação em Nuvem - Conceitos Fundamentais

## Serviços

São formas diferentes de usar a internet para acessar programas, arquivos ou até mesmo computadores inteiros, sem precisar instalar tudo no seu computador.

### Modelos de Serviço:

- **IaaS (Infrastructure as a Service)**  
  O usuário paga pela infraestrutura de TI básica, como servidores virtuais, armazenamento, rede, entre outros.

- **PaaS (Platform as a Service)**  
  Plataforma completa para desenvolvimento, teste e implantação de aplicações, sem se preocupar com a infraestrutura subjacente.

- **SaaS (Software as a Service)**  
  Aplicativos acessados via internet, como Canva, Microsoft Office 365, Google Workspace, entre outros.

---

## Modelos de Nuvem

- **Nuvem Privada**  
  Ambiente de nuvem exclusivo da organização, geralmente hospedado em datacenter próprio.

  - Operada e gerida pela própria empresa.
  - Acesso restrito ao público externo.
  - Requer compra e manutenção de hardware (modelo CAPEX).
  - Maior controle sobre segurança e recursos.

- **Nuvem Pública**  
  Fornecida por provedores como Azure, AWS, Google Cloud.

  - Infraestrutura compartilhada entre usuários.
  - Acesso via internet segura.
  - Baixo custo inicial (modelo OPEX).
  - Alta escalabilidade e facilidade de provisionamento.
  - Provedor é responsável pela manutenção e segurança física.

- **Nuvem Híbrida**  
  Combinação de nuvem pública e privada.

  - Flexibilidade para manter dados sensíveis localmente.
  - Uso da nuvem pública para escalar conforme demanda.
  - Equilíbrio entre custo, controle e desempenho.

---

## CAPEX vs OPEX na Nuvem

| Modelo | Características |
|--------|-----------------|
| **CAPEX (Capital Expenditure)** | Investimentos em ativos físicos, como servidores e licenças vitalícias. Maior custo inicial, controle total, porém risco de ociosidade. |
| **OPEX (Operational Expenditure)** | Pagamento sob demanda (pay-as-you-go), baixo investimento inicial, escalabilidade. Pode se tornar caro sem boa governança. |

---

## Benefícios da Computação em Nuvem

1. **Alta disponibilidade**: Serviços acessíveis quase todo o tempo.
2. **Elasticidade**: Aumenta ou reduz recursos conforme a demanda.
3. **Escalabilidade**: Expansão fácil de infraestrutura.
4. **Confiabilidade**: Redundância e tolerância a falhas.
5. **Previsibilidade**: Planejamento de custos e desempenho.
6. **Segurança**: Criptografia, controle de acesso e monitoramento.
7. **Governança**: Aplicação de políticas e normas de conformidade.
8. **Gerenciabilidade**: Administração centralizada e eficiente.

---

## Modelo de Responsabilidade Compartilhada

O provedor de nuvem e o cliente compartilham responsabilidades relacionadas à segurança e operação do ambiente em nuvem.

### O que é?

Divisão clara de tarefas entre:
- **Provedor de Nuvem** (ex: AWS, Azure, GCP)
- **Cliente** (usuário da nuvem)

Essa divisão varia conforme o modelo:

| Modelo | Responsabilidade do Provedor | Responsabilidade do Cliente |
|--------|------------------------------|------------------------------|
| **IaaS** | Hardware, rede, datacenter | Sistema operacional, apps, dados |
| **PaaS** | Infraestrutura + plataforma | Aplicação e dados |
| **SaaS** | Aplicação completa | Uso responsável e dados |

---

## Responsabilidade Compartilhada: IaaS x PaaS x SaaS

![Responsabilidade Compartilhada](imagens/RESPONSABILIDADE%20COMPARTILHADA.jpeg)

---

# Segurança na Nuvem e Componentes de Arquitetura do Azure 

## Por que o modelo de responsabilidade compartilhada é importante?

- **Segurança mal configurada pelo cliente** é uma das principais causas de **vazamento de dados** na nuvem.
- O **provedor** garante que a infraestrutura da nuvem é segura, mas o **cliente** é responsável por **configurar e usar corretamente** os recursos.
- Esse modelo é essencial para:
  - Conformidade regulatória
  - Auditorias e certificações
  - Boa governança de TI

### Em Resumo:
> **Na nuvem, a segurança é uma responsabilidade compartilhada. O provedor protege a nuvem, mas o cliente é responsável por tudo o que coloca e faz dentro dela.**

---

## Componentes de Arquitetura do Azure

### 1. Regiões do Azure (Azure Regions)

#### O que são?
Conjuntos de datacenters agrupados geograficamente, onde os serviços do Azure são disponibilizados.

#### Exemplos:
- `Brazil South` (São Paulo)
- `East US`, `West Europe`, `Southeast Asia`, etc.

#### Importância:
- Permite **escolher onde os dados e aplicações rodam**.
- Atende requisitos de **latência**, **resiliência** e **compliance local**.
- Nem todos os serviços estão disponíveis em todas as regiões.

### 2. Zonas de Disponibilidade (Availability Zones)

#### O que são?
Conjuntos **fisicamente separados** de datacenters dentro de uma mesma região, com energia, rede e refrigeração **independentes**.

#### Benefícios:
- Alta disponibilidade
- Tolerância a falhas locais (ex: queda de energia em uma zona)

#### Como usar:
- Distribuir recursos entre zonas diferentes garante **redundância e continuidade de negócios**.

#### Exemplo:
Na região `East US`, existem zonas 1, 2 e 3. Uma aplicação pode ter parte de seus recursos na zona 1 e outra parte na zona 2 para reduzir o risco de downtime.

### 3. Pares de Regiões (Region Pairs)

#### O que são?
Cada região do Azure é emparelhada com outra **dentro da mesma área geopolítica**, garantindo:

- Recuperação de desastres (Disaster Recovery - DR)
- Replicação de dados assíncrona
- Atualizações planejadas sem impacto simultâneo

#### Exemplos:
- `Brazil South` pareada com `South Central US`
- `North Europe` com `West Europe`

#### Benefícios:
- Pelo menos uma das regiões permanece operacional em caso de falha grave
- Possibilidade de **backups automáticos e failover** entre regiões pareadas

### 4. Regiões Soberanas (Azure Sovereign Regions)

#### O que são?
Regiões do Azure operadas separadamente, voltadas a **governos** ou **entidades com exigências rigorosas de soberania de dados**.

#### Tipos:
- **Azure Government (EUA)**: para agências governamentais americanas, com pessoal e infraestrutura segregados.
- **Azure China**: operada pela 21Vianet, com data centers isolados e infraestrutura separada.
- **Azure Germany (legado)**: modelo europeu de conformidade estrita (agora integrado à estrutura geral da UE).

#### Objetivo:
- Atender a exigências legais, regulatórias e de conformidade nacional/internacional
- Proteger dados sensíveis com **isolamento e controle rigoroso**

---

# Recursos do Azure – O que são?

No Azure, **recursos** são entidades gerenciáveis que você utiliza para construir suas soluções de nuvem.  
Isso inclui máquinas virtuais, redes, bancos de dados, armazenamento e muito mais.

## Máquinas Virtuais (VMs)
- Hospedam sistemas operacionais e aplicativos como se fossem computadores físicos.

## Contas de Armazenamento (Storage Accounts)
- Permite armazenar arquivos, blobs, tabelas, filas e discos.

## Redes Virtuais (VNets)
- Criam uma rede privada na nuvem, onde é possível conectar e isolar recursos.

## Serviços de Aplicativos (App Services)
- Hospedagem de aplicações web, APIs e backends sem necessidade de gerenciar infraestrutura.

## Bancos de Dados SQL (Azure SQL Database)
- Banco de dados relacional baseado no SQL Server, oferecido como serviço (SaaS).

## Azure Functions
- Executa trechos de código em resposta a eventos (modelo serverless).

---
# O que são Grupos de Recursos no Azure?

Um **grupo de recursos** é um **contêiner lógico** no qual você agrupa recursos do Azure, como máquinas virtuais, bancos de dados, redes, contas de armazenamento, etc.  
Ele permite gerenciar todos esses recursos **como uma única unidade**.

## Características principais

### 1. Cada recurso pertence a apenas um grupo
- Um recurso (como uma VM) **não pode estar em dois grupos ao mesmo tempo**.
- É possível **mover recursos entre grupos**, desde que as regras de compatibilidade sejam respeitadas.

### 2. Recursos podem estar em regiões diferentes
- Embora o **grupo de recursos seja criado em uma região**, os **recursos dentro dele podem estar em outras regiões**.

### 3. Recursos podem ser movidos
- Você pode **reorganizar sua infraestrutura** movendo recursos entre grupos.

### 4. Aplicações podem usar vários grupos
Uma aplicação pode ser dividida em vários grupos, por exemplo:
- Um grupo para a **interface web**.
- Outro para os **bancos de dados**.
- Outro para **armazenamento ou rede**.

## Exemplo de uso: duas formas de organização

### Organização por solução (**vertical**)
Todos os recursos relacionados a uma aplicação ficam em **um único grupo de recursos**:

**Grupo de Recursos: `AppFinanceiro`**
- Web App
- Banco de Dados SQL
- Storage
- Máquinas Virtuais

**Vantagem:** Foco na aplicação como unidade de gestão.

### Organização por tipo de recurso (**horizontal**)
Os recursos são agrupados **por tipo ou função**, mesmo se usados por aplicações diferentes:

- Grupo de Recursos: `VMs`
- Grupo de Recursos: `Bancos de Dados`
- Grupo de Recursos: `Storage`
- Grupo de Recursos: `Aplicações Web`

**Vantagem:** Melhora a padronização e o controle por equipe ou tecnologia.

## Benefícios práticos dos Grupos de Recursos

- **Gerenciamento conjunto:** Aplicar políticas, permissões (RBAC), tags e monitoramento a todos os recursos do grupo.
- **Automação:** Utilização de templates (ARM) para implantar todos os recursos do grupo de uma vez.
- **Controle de custos:** Visualizar os gastos por grupo.
- **Organização e governança:** Facilita a estruturação por ambiente (produção, testes, dev) ou por equipe.

---

# Assinaturas e Grupos de Gerenciamento no Azure

Dois elementos fundamentais para **organização**, **controle** e **governança** no Azure são:

- **Assinaturas (Azure Subscriptions)**
- **Grupos de Gerenciamento (Management Groups)**

## Assinaturas do Azure

### O que é uma assinatura?

Uma **assinatura** é uma **unidade de controle, cobrança e acesso** no Azure.  
Através dela, você consome os serviços da plataforma e define como os recursos são gerenciados.

### Principais funções da assinatura:

#### 1. Autenticação e autorização
- Usuários precisam estar **autenticados** (login) e **autorizados** (permissões via RBAC) para acessar os recursos.

#### 2. Limite de cobrança
- Cada assinatura possui seu próprio **orçamento, fatura e controle de custos**.
- Ideal para separar **ambientes** ou **clientes** diferentes (ex: produção, testes, cliente X, cliente Y).

#### 3. Limite de controle de acesso
- Cada assinatura pode ter **políticas de segurança** e **permissões específicas**.
- Permite controle granular de acesso por equipe ou projeto.

### Exemplo prático:

Você pode ter:

- Uma assinatura para **projetos internos**  
- Uma assinatura para **clientes externos**  
- Uma assinatura para **ambientes de testes**  

---

## Grupos de Gerenciamento (Management Groups)

### O que são?

Os **Grupos de Gerenciamento** são estruturas que permitem **organizar várias assinaturas do Azure** sob uma **hierarquia lógica**.

---

### Principais características:

#### 1. Agrupamento de assinaturas
- Um grupo de gerenciamento pode conter **várias assinaturas diferentes**.

#### 2. Hereditariedade de políticas
- **Políticas, RBAC e configurações de compliance** aplicadas ao grupo são **herdadas por todas as assinaturas** abaixo dele.

#### 3. Escalabilidade
- É possível criar até **10.000 grupos de gerenciamento por diretório** do Azure AD.
- A estrutura hierárquica pode ter até **6 níveis de profundidade**, além do nível raiz.

- ### Benefícios em resumo:
- **Governança centralizada**
- **Segurança e políticas consistentes**
- **Organização escalável e flexível**

---

# Computação e Rede no Azure

A **computação no Azure** refere-se à capacidade de alocar recursos computacionais como CPU, memória, armazenamento e rede pela nuvem.  
Pense como "alugar" infraestrutura ou plataformas para rodar suas soluções — pagando **apenas pelo uso**.


## Principais Serviços de Computação do Azure

### 1. Máquinas Virtuais (Azure Virtual Machines – VMs)

- Servidores **virtuais completos**, com sistema operacional (Windows ou Linux).
- Permite instalação de qualquer software necessário.

**Usos comuns:**
- Migração de sistemas legados  
- Ambientes de desenvolvimento  
- Hospedagem de servidores e bancos de dados  

**Controle total**, mas você gerencia o SO, patches e atualizações.

---

### 2. Serviços de Aplicativos (App Services)

- Serviço **gerenciado** para hospedar **web apps, APIs REST e backends móveis**.
- Suporte a várias linguagens: `.NET`, `Java`, `Node.js`, `Python`, `PHP`, `Ruby`.

**Recursos:**
- Escalabilidade automática  
- Deploy contínuo via GitHub, Azure DevOps, FTP  

Ideal para quem quer **focar no código e não na infraestrutura**.

---

### 3. Instâncias de Contêiner (Azure Container Instances – ACI)

- Executa **contêineres individuais sob demanda**, sem necessidade de orquestração.

**Casos de uso:**
- Tarefas rápidas  
- Processamento em lote  
- Microsserviços temporários  

Totalmente **serverless** – simples, rápido e sob demanda.

---

### 4. Serviço de Kubernetes do Azure (AKS – Azure Kubernetes Service)

- Serviço gerenciado de **orquestração de contêineres com Kubernetes**.
- Permite escalar, automatizar e gerenciar implantações complexas.

**Ideal para:**
- Microsserviços  
- Integrações com DevOps  
- Ambientes multicloud e de produção  

Recomendado para ambientes **complexos e com alta disponibilidade**.

---

### 5. Área de Trabalho Virtual do Azure (Azure Virtual Desktop – AVD)

- Plataforma para criar **ambientes de trabalho remotos e seguros** acessíveis pela internet.

**Recursos:**
- Suporte a **multiusuários no mesmo host**  
- Integração com **Microsoft 365**  
- Controle de **segurança e compliance**  

Substitui desktops físicos com **flexibilidade e controle centralizado**.

---

# 💻 Máquinas Virtuais do Azure (Azure Virtual Machines – VMs)

As **Máquinas Virtuais do Azure** são emulações de computadores físicos fornecidas pela nuvem.  
Você pode configurar essas máquinas para rodar sistemas operacionais, aplicações, bancos de dados e mais — como faria com um servidor físico tradicional.

---

## 🔧 Características Principais

### 1. 🛠️ Infraestrutura como Serviço (IaaS)

- Você tem **controle total** da máquina virtual:  
  Sistema operacional, atualizações, softwares instalados, scripts de inicialização e configurações de segurança.
- Ideal para **migração lift-and-shift**, ou seja, mover aplicações legadas para a nuvem sem reestruturá-las.

---

### 2. ⚙️ Componentes de uma VM

Cada máquina virtual inclui os seguintes componentes:

- **CPU virtual (vCPU)** – Processador escalável sob demanda.  
- **Memória RAM** – Configurável conforme o tipo de carga.  
- **Disco (armazenamento)** – Pode ser SSD, HDD ou Premium, conforme o desempenho desejado.  
- **Rede virtual (VNet)** – Permite conexão com outros recursos do Azure ou com a internet.

---

### 3. 📌 Casos de Uso Típicos

- Hospedagem de **bancos de dados** como SQL Server ou Oracle.  
- Execução de **aplicações corporativas ou legadas**.  
- **Servidores de desenvolvimento e testes**.  
- Ambientes de **alta disponibilidade** e **recuperação de desastres (DR)**.

---

# 📦 Serviços de Contêineres da Azure

---

## 🧱 O que é um Contêiner?

Um **contêiner** é uma forma de empacotar um aplicativo junto com tudo que ele precisa para funcionar:  
- Código  
- Bibliotecas  
- Dependências  
- Arquivos de configuração  

Isso garante que o app rode da **mesma forma** em qualquer ambiente: no seu computador, no servidor da empresa ou na nuvem.

> 🧳 Analogia: O contêiner é como uma "mala" com tudo que o app precisa para a viagem.

---

## ❓ Por que usar contêineres?

- 🚀 Iniciam rapidamente (sem subir um sistema operacional completo).
- 🧵 Leves e consomem menos recursos que máquinas virtuais.
- 🧩 Portáveis — rodam onde houver um runtime (ex: Docker).
- 🧱 Facilitam a criação de **microserviços**.
- 🔁 Tornam o desenvolvimento e entrega de software mais ágeis e consistentes.

---

## ☁️ Serviços de Contêineres no Azure

### 1. 🚀 Azure Kubernetes Service (AKS)

**Kubernetes** é uma plataforma para orquestrar e gerenciar vários contêineres em larga escala.

**AKS** é o serviço do Azure que oferece o Kubernetes já configurado e gerenciado.

**Vantagens:**
- Criação automática de clusters
- Atualizações automatizadas
- Integração com CI/CD
- Segurança com Azure AD
- Monitoramento com Azure Monitor

**Quando usar:**
- Sistemas com **muitos microserviços**
- Alta disponibilidade e escalabilidade
- Projetos robustos ou em produção

---

### 2. ⚡ Azure Container Instances (ACI)

Permite executar contêineres sob demanda, sem servidores ou clusters.

**Vantagens:**
- Inicialização em segundos
- Pague apenas pelo tempo de execução
- Ideal para scripts, eventos ou tarefas temporárias

**Quando usar:**
- Execução rápida e pontual
- Testes de contêineres
- Automação e tarefas programadas

---

### 3. 🔁 Azure Container Apps

Serviço **serverless** para rodar contêineres com escalabilidade automática baseada em eventos.

**Recursos:**
- Usa **Dapr** e **KEDA**
- Revisões sem downtime
- Foco no código, não na infra

**Quando usar:**
- Aplicações com variação de carga
- Solução mais simples que AKS
- Microserviços e APIs leves

---

### 4. 🌐 App Service com Suporte a Contêineres

Hospede seu site ou API como contêiner no App Service.

**Vantagens:**
- Suporte a Docker
- SSL, domínio personalizado e escalabilidade
- Ideal para aplicações web (Node, .NET, Python, etc)

**Quando usar:**
- Projeto web já empacotado em contêiner
- Simplicidade e velocidade de publicação
- Produção com baixa complexidade

---

### 5. 🗂️ Azure Container Registry (ACR)

Serviço para armazenar e gerenciar imagens de contêineres.

**O que é um registry?**  
Uma “prateleira digital” onde ficam as **imagens** de contêineres (o pacote que define o contêiner).

**Vantagens:**
- Armazena e gerencia imagens Docker
- Integração com AKS, ACI, etc.
- Suporte a automações e CI/CD
- Alta segurança e controle de acesso

**Quando usar:**
- Armazenamento privado e seguro
- Deploys frequentes no Azure
- Pipelines de CI/CD integradas

---
# ⚡ Azure Functions

O **Azure Functions** é o serviço **serverless** de computação da Microsoft.  
Ele executa pequenos pedaços de código (funções) **em resposta a eventos** — sem que você precise configurar ou gerenciar servidores.

> **Serverless ≠ Sem Servidor**  
> Servidores existem, mas o Azure gerencia toda a infraestrutura, escalabilidade e atualizações.  
> Você paga **apenas pelo tempo** em que o código roda.

---

## 🛠️ Como funciona na prática?

Imagine que você precisa:

- Enviar um e‑mail sempre que um arquivo for carregado no sistema.  
- Processar dados ao receber uma requisição HTTP.  
- Executar uma tarefa em horário agendado (cron job).

Com Azure Functions você escreve **só a lógica**; o Azure executa automaticamente quando o evento é disparado.

---

## 🧩 Estrutura de uma Function

1. **Trigger (gatilho)** – define o que inicia a execução:  
   - `HTTP` (requisição de API ou navegador)  
   - `Timer` (agendamentos estilo cron)  
   - Mensagem em `Queue Storage`  
   - Upload em `Blob Storage`  
   - Evento de banco de dados, etc.

2. **Input (entrada)** – dados que a função recebe para processar.

3. **Output (saída)** – resultado que a função gera ou envia (gravar arquivo, retornar resposta, publicar mensagem, etc.).

---

## ✅ Vantagens do Azure Functions

- **Pagamento por uso real** – cobrança apenas pelo tempo de execução e número de execuções.  
- **Alta escalabilidade** – lida automaticamente com de 1 a milhões de eventos.  
- **Desacoplamento** – ideal para dividir sistemas em partes menores e independentes.  
- **Integração nativa** – conecta-se facilmente com outros serviços do Azure.  
- **Multiplataforma** – suporta C#, JavaScript, Python, Java, PowerShell, entre outros.

---

### 📌 Quando usar Azure Functions?

Use Azure Functions quando você:

- 🔁 Precisa **automatizar tarefas simples** sem montar uma aplicação complexa.
- ⚡ Quer **responder a eventos em tempo real**, como:
  - Uploads de arquivos
  - Mensagens em filas
  - Requisições HTTP
- 💸 Deseja **pagar apenas pelo uso real** do sistema, sem manter infraestrutura ligada 100% do tempo.
- 🧱 Está trabalhando com **arquitetura orientada a eventos** ou **microserviços**.

---

## 🌐 Serviços de Aplicativos do Azure

### 🚀 O que é o Azure App Service?

O **Azure App Service** é uma plataforma de hospedagem na nuvem para **aplicações web, APIs REST e backends móveis**. Ele permite que você **publique, escale e gerencie seus apps** com facilidade — **sem precisar cuidar da infraestrutura**.

> 💡 Você foca no seu código, o Azure cuida do resto.

---

### ⚙️ O que ele faz?

Com o App Service, você pode:

- 🖥️ **Hospedar** sites, sistemas e APIs feitos em várias linguagens.
- 🔁 Fazer **deploy automático** direto do GitHub, Bitbucket, Azure DevOps ou FTP.
- 🔒 Ter **HTTPS**, escalabilidade, backup, monitoramento e **integração contínua** prontos para uso.
- ⏱️ **Agendar tarefas**, gerenciar domínios e escalar recursos com poucos cliques.

---

### 📘 Termos técnicos explicados

#### ☁️ PaaS (Plataforma como Serviço)

> O Azure oferece toda a infraestrutura pronta: servidor, sistema operacional, atualizações, balanceamento de carga, etc.

✅ Você **só se preocupa com o código da sua aplicação**.

---

#### 📦 Deploy

> É o processo de **enviar seu código para o servidor** na nuvem para que ele fique acessível.

---

#### 🔀 Slot de implantação (deployment slot)

> Permite **testar uma nova versão do app** em um ambiente separado (ex: `teste.meusite.com`) e, se estiver tudo certo, **trocar com a versão em produção** sem causar interrupção.

---

#### 📈 Autoescalonamento (autoscaling)

> O App Service pode **aumentar ou reduzir os recursos automaticamente** conforme o número de acessos, garantindo desempenho **sem desperdiçar dinheiro**.

---

### ✅ Quando usar o App Service?

- Quando você quer **hospedar rapidamente** aplicações web, APIs e backends móveis.
- Quando deseja **foco total no desenvolvimento**, sem gerenciar infraestrutura.
- Para **entregas contínuas (CI/CD)** integradas com GitHub, DevOps ou Bitbucket.
- Para **testes de versões** com segurança via deployment slots.
- Quando precisa de **autoescalabilidade e disponibilidade garantida**.

---

> 🔗 Ideal para desenvolvedores web que usam .NET, Node.js, Python, Java, PHP ou Ruby.

---

## 🌐 Serviços de Rede do Azure

### O que são?

Os **Serviços de Rede do Azure** formam um conjunto de recursos que permitem **conectar, proteger e entregar** aplicativos na nuvem com segurança, desempenho e escalabilidade.  
Em resumo, são eles que garantem que seus apps se comuniquem com o mundo (e entre si) de forma segura.

---

### Por que isso importa?

Uma aplicação pode estar perfeita, mas sem uma rede eficiente e segura ela não:

- 🌍 É acessada globalmente com baixa latência.  
- 🔗 Comunica‑se com bancos de dados, APIs e outros sistemas.  
- 🔒 Protege dados de acessos indevidos.  
- 💪 Mantém **alta disponibilidade** (reduzindo riscos de falha).  

---

## 🔑 Principais Serviços de Rede do Azure

| # | Serviço | Para que serve? | Camada / Destaque |
|---|---------|-----------------|-------------------|
| 1 | **Azure Virtual Network (VNet)** | Rede privada virtual na nuvem. Conecta VMs, bancos, funções de forma segura (controle de IPs, sub‑redes, firewalls). | Camada 3‑4 |
| 2 | **Network Security Groups (NSG)** | Regras de firewall para controlar portas/IPs permitidos ou bloqueados. | Camada 4 |
| 3 | **Azure DNS** | Gerencia domínios e resolve nomes (ex: `meusite.com`). Alta disponibilidade global. | Serviço DNS |
| 4 | **Azure Load Balancer** | Distribui tráfego **TCP/UDP** entre instâncias para alta disponibilidade. | **Camada 4** |
| 5 | **Azure Application Gateway** | Balanceador de carga **HTTP/HTTPS** com WAF, SSL, URL rewrite, roteamento avançado. | **Camada 7** |
| 6 | **Azure Firewall** | Firewall totalmente gerenciado com regras sofisticadas, logs e integração corporativa. | Camada 4‑7 |
| 7 | **Azure Front Door** | CDN global + aceleração de conteúdo, cache, SSL, proteção DDoS. | Borda da rede |
| 8 | **ExpressRoute** | Conexão privada/dedicada datacenter ↔ Azure (baixa latência, alta segurança). | Físico/Privado |
| 9 | **VPN Gateway** | Conecta rede local ao Azure por VPN criptografada via internet (custo menor que ExpressRoute). | Camada 3 |

---

### 🗓️ Quando usar os serviços de rede?

Use (um ou mais) desses serviços quando você:

- 🔒 Precisa **proteger** aplicações e dados com firewalls e regras de acesso.  
- 🌐 Deseja **alta disponibilidade** e **desempenho global** para usuários.  
- 🔗 Precisa conectar sistemas on‑premises ao Azure (VPN Gateway ou ExpressRoute).  
- 🏗 Está construindo uma arquitetura corporativa complexa com várias sub‑redes, front‑ends e back‑ends.  

---

> **Dica:** Combine VNet + NSG para isolamento interno, Load Balancer para tráfego L4, Application Gateway (com WAF) para tráfego HTTP/HTTPS e Front Door para distribuir globalmente.

---











