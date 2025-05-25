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

 ## Regions e Zones

 As clouds criaram uma solução muito inteligente. Para diminuir o problema de latência, criaram regiões (regions) e zonas (zones) de disponibilidade, ou seja, ao invés de ter todas as máquinas em um só lugar, as platforms distribuem pelo mundo regiões que possuem concentração de data centers.

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




