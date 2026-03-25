### Glossário Técnico de DDD

*   **Agregado (Aggregate):** Cluster de entidades e objetos de valor tratado como uma única unidade coesa para garantir a consistência das regras de negócio.
*   **Asserções:** Declarações explícitas de pós-condições e invariantes para classes e agregados, garantindo o rigor formal e o encapsulamento.
*   **Bounded Context (Contexto Delimitado):** Fronteira lógica explícita dentro da qual um modelo específico de domínio é definido e mantém significados consistentes.
*   **Camada Anticorrupção (ACL):** Mecanismo técnico de isolamento que traduz modelos externos para o modelo atual, protegendo-o de conceitos estranhos ou legados.
*   **Camadas de Responsabilidade:** Estrutura em larga escala que organiza o domínio em estratos baseados em dependências conceituais e velocidades de mudança.
*   **Caminhos Separados (Separate Ways):** Decisão estratégica de declarar que dois contextos não possuem nenhuma conexão para que evoluam de forma independente.
*   **Classes Autônomas:** Padrão de design que busca eliminar dependências para que uma classe possa ser entendida isoladamente.
*   **Cliente-Fornecedor (Customer-Supplier):** Relacionamento onde a equipe fornecedora (upstream) atende às prioridades e necessidades da equipe cliente (downstream) em seu planejamento.
*   **Conformista (Conformist):** Relação em que a equipe consumidora adere estritamente ao modelo da equipe fornecedora para simplificar a integração sem realizar traduções.
*   **Contexto:** Configuração que determina o sentido exato de uma palavra ou declaração dentro de um modelo.
*   **Contornos Conceituais:** Divisões de design (interfaces e classes) que se alinham aos aspectos consistentes e estáveis do domínio.
*   **Declaração da Visão de Domínio:** Breve descrição que identifica o valor estratégico e a "proposição de valor" do Domínio Principal.
*   **Domínio:** Esfera de conhecimento ou atividade para a qual o usuário aplica um programa, representando o coração do negócio.
*   **Domain Expert (Especialista de Domínio):** Profissional que detém o conhecimento profundo sobre o negócio e guia o time técnico na modelagem.
*   **Domínio Principal (Core Domain):** Parte essencial do software que representa o diferencial competitivo e merece o maior investimento de design.
*   **Entidade:** Objeto de domínio definido por sua identidade única e contínua, que persiste mesmo que seus atributos mudem.
*   **Estrutura de Componentes Plugáveis:** Padrão que destila um núcleo abstrato de interfaces permitindo que diferentes implementações sejam substituídas livremente.
*   **Evento de Domínio:** Registro imutável de algo relevante que aconteceu no domínio e que outros componentes precisam conhecer.
*   **Event Storming:** Oficina colaborativa e visual feita com post-its para mapear o domínio através de eventos, alinhando rapidamente o conhecimento de todos.
*   **Fábrica (Factory):** Componente que encapsula a lógica complexa de criação de instâncias de agregados e objetos, garantindo um estado inicial válido.
*   **Fechamento de Operações:** Padrão de design onde o tipo de retorno de uma operação é o mesmo tipo de seus argumentos, reduzindo dependências externas.
*   **Funções Livres de Efeitos Colaterais:** Operações que retornam resultados sem modificar o estado observável do sistema, facilitando a previsibilidade do código.
*   **Grande Bola de Lama (Big Ball of Mud):** Sistema onde os modelos estão misturados e os limites são inconsistentes, dificultando a rastreabilidade e a manutenção.
*   **Interfaces Reveladoras de Intenção:** Nomes de classes e métodos que descrevem seus propósitos e efeitos sem revelar detalhes de como fazem o que prometem.
*   **Invariantes:** Regras de negócio e políticas de consistência que devem ser mantidas verdadeiras dentro de uma fronteira transacional.
*   **Linguagem Onipresente (Ubíqua):** Vocabulário comum compartilhado por especialistas e desenvolvedores, refletido rigorosamente na comunicação e no código.
*   **Linguagem Publicada (Published Language):** Linguagem compartilhada e bem documentada usada para o intercâmbio de informações entre diferentes contextos.
*   **Mapa de Contexto (Context Map):** Representação visual que documenta as relações, pontos de contato e formas de integração entre diferentes Contextos Delimitados.
*   **Mecanismos Coesos:** Algoritmos ou estruturas separadas do domínio principal para que este se foque apenas em expressar o problema de negócio.
*   **Metáfora de Sistema:** Analogia concreta que organiza o design e facilita a comunicação compartilhada sobre o funcionamento do sistema.
*   **Modelo de Domínio:** Sistema de abstrações que descreve aspectos selecionados de um domínio para resolver problemas relacionados a ele.
*   **Nível de Conhecimento:** Conjunto de objetos que descreve como outro grupo de objetos deve se comportar, permitindo flexibilidade em regras de montagem.
*   **Núcleo Abstrato:** Módulo que isola os conceitos mais fundamentais em classes abstratas ou interfaces, expressando as interações principais do sistema.
*   **Núcleo Compartilhado (Shared Kernel):** Subconjunto do modelo e código que duas equipes concordam em compartilhar e gerenciar via integração contínua.
*   **Núcleo Destacado:** Documento ou sinalização visual que facilita a identificação dos elementos essenciais do Domínio Principal para a equipe.
*   **Núcleo Segregado:** Refatoração que separa fisicamente os conceitos do núcleo principal de suas funções de apoio ou genéricas.
*   **Objeto de Valor (Value Object):** Objeto imutável definido apenas por seus atributos, sem necessidade de uma identidade própria para o domínio.
*   **Parceria (Partnership):** Relação cooperativa onde duas equipes planejam juntas a integração, tendo sucesso ou falhando em conjunto.
*   **Raiz de Agregado (Aggregate Root):** Única entidade de um agregado através da qual o mundo externo deve interagir para manter a integridade do grupo.
*   **Repositório:** Abstração que simula uma coleção em memória para salvar e recuperar objetos de domínio, isolando a lógica do banco de dados.
*   **Serviço de Domínio (Domain Service):** Operação de negócio sem estado que lida com comportamentos complexos que não pertencem naturalmente a uma única entidade.
*   **Serviço de Host Aberto (Open Host Service):** Protocolo público definido para que outros subsistemas possam se integrar a um contexto de forma padronizada.
*   **Subdomínio:** Divisão de um domínio complexo em partes menores para facilitar o gerenciamento e a priorização de investimentos.
*   **Subdomínio Genérico:** Problema comum já resolvido pela indústria que pode ser atendido por soluções padronizadas ou prontas.
*   **Subdomínio de Suporte:** Parte necessária para a operação do negócio, mas que não oferece diferenciação estratégica direta.
*   **Upstream-Downstream:** Relação de direção onde as ações do grupo "a montante" (upstream) influenciam o sucesso do grupo "a jusante" (downstream).
---
   ### Termos fundamentais para o estudante iniciante:
*   **Agregado (*Aggregate*)** 
*   **Bounded Context (Contexto Delimitado)** 
*   **Camada Anticorrupção (ACL)** 
*   **Core Domain (Domínio Principal)** 
*   **Domain Expert (Especialista de Domínio)** 
*   **Entidade (*Entity*)** 
*   **Event Storming** 
*   **Linguagem Ubíqua** 
*   **Mapa de Contexto (*Context Map*)** 
*   **Objeto de Valor (*Value Object*)** 
*   **Raiz de Agregado (*Aggregate Root*)** 
*   **Repositório (*Repository*)** 
