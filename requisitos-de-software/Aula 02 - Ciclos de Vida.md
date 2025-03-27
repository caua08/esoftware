# **Ciclos de vida de desenvolvimento**
O ciclo de vida representa a forma como as fases do projeto são executadas. Existem diferentes ciclos de vida que podem ser aplicados conforme a abordagem escolhida e o tipo de requisito identificado.

### **Ciclo de Vida Preditivo**
No ciclo preditivo, também conhecido como modelo em cascata, todo o planejamento é realizado antes do início do desenvolvimento. Ele pressupõe que os requisitos são estáveis e bem definidos. A execução é linear e sequencial, o que torna o processo mais rígido, mas com maior previsibilidade e controle.

![[cv_preditivo.png]]

### **Ciclo de Vida Iterativo**
O ciclo iterativo permite que as fases do projeto sejam revisitadas. Ele é útil quando os requisitos iniciais não são totalmente claros e precisam ser refinados com o tempo. Cada iteração visa melhorar a compreensão do sistema, sem necessariamente gerar um incremento de funcionalidades a cada ciclo.

![[cv_iterativo.png]]

### **Ciclo de Vida Incremental**
No modelo incremental, o sistema é construído e entregue em partes funcionais, chamadas de incrementos. Cada incremento agrega uma nova funcionalidade ao produto final. Esse ciclo é eficaz para entregas rápidas e progressivas.

![[cv_incremental.png]]

### **Ciclo Iterativo-Incremental (Ágil)**
A combinação dos modelos iterativo e incremental forma a base do ciclo ágil. Ele permite o refinamento constante dos requisitos ao mesmo tempo em que se realiza entregas funcionais contínuas. Esse modelo está fortemente relacionado aos frameworks ágeis como Scrum, Kanban e Extreme Programming (XP), onde práticas técnicas e organizacionais trabalham juntas para garantir eficiência e adaptabilidade.

## **Integração entre Abordagens e Ciclos**
Uma prática comum em projetos reais é o uso de abordagens híbridas. Isso significa que um projeto pode iniciar com uma abordagem dirigida por plano para definição da arquitetura e, posteriormente, adotar uma abordagem ágil para lidar com demandas dinâmicas de clientes que exigem entregas frequentes. Essa flexibilidade permite aplicar diferentes ciclos de vida em diferentes fases do projeto, otimizando os resultados conforme as necessidades do negócio.

## **Processos e Métodos**
O processo é responsável por operacionalizar o ciclo de vida escolhido. Ele define os métodos, técnicas e práticas que serão utilizadas em cada fase, como levantamento de requisitos, análise, projeto, testes e manutenção. Métodos ágeis, como o XP, enfatizam práticas técnicas, enquanto frameworks como Scrum e Kanban estruturam o trabalho com foco em organização, papéis e cerimônias. A escolha do processo deve ser coerente com o ciclo de vida e a abordagem definidos.

## **Estabilidade e Variabilidade dos Requisitos**
Independentemente da abordagem adotada, é importante considerar que algum grau de variabilidade sempre existirá. A estabilidade dos requisitos influencia diretamente na precisão do planejamento e na quantidade de retrabalho nas fases posteriores. Por exemplo, quando um requisito não funciona na fase de testes, pode ser necessário retornar à fase de requisitos e redesenhar soluções, impactando o tempo e o custo do projeto.

## **Triângulos de Gerenciamento**
A representação visual dos fatores de gerenciamento pode ser feita por meio de dois triângulos distintos:

![[triangulos_dp_agil.png]]

- **Na abordagem dirigida por plano**, os requisitos são fixos e os custos e prazos são variáveis, adaptando-se ao escopo estabelecido.
    
- **Na abordagem ágil**, os recursos e prazos são fixos, enquanto os requisitos podem variar ao longo do projeto, permitindo entregas incrementais conforme a necessidade do cliente.
    
Essa diferenciação ajuda a entender como os limites do projeto são gerenciados conforme o modelo escolhido.

## **Em resumo**
O sucesso de um projeto não depende apenas da qualidade técnica, mas da coerência entre os requisitos definidos e a maneira como o desenvolvimento será conduzido. Conhecer bem as abordagens, os ciclos de vida e suas aplicações práticas é essencial para garantir que as entregas estejam alinhadas com as expectativas e necessidades dos stakeholders.