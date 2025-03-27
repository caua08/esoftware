
**Fundamentos de Arquitetura de Computadores: Uma Introdução Histórica e Conceitual**

A arquitetura de computadores é uma área essencial da computação que busca compreender a estrutura e o funcionamento dos sistemas digitais modernos. Para isso, é fundamental tanto entender o que compõe um computador quanto conhecer sua evolução histórica, desde os primeiros instrumentos de cálculo até os microprocessadores atuais.

Inicialmente, a humanidade começou a desenvolver noções de número e cálculo por meio da comparação entre conjuntos e do uso dos próprios dedos. Dispositivos como o ábaco, os bastões de Napier e a régua de cálculo marcaram os primeiros avanços na computação mecânica. Figuras como Blaise Pascal, com a Pascaline, e Leibniz, com seu mecanismo de multiplicação, trouxeram inovações importantes no século XVII. Já no século XIX, Charles Babbage idealizou a Máquina de Diferenças e a Máquina Analítica, precursoras dos computadores modernos, sendo esta última considerada Turing-completa, ou seja, capaz de executar qualquer computação se programada adequadamente.

A transição para dispositivos eletromecânicos se deu a partir da Revolução Industrial e culminou com a obra de Herman Hollerith, cuja máquina tabuladora agilizou o censo dos Estados Unidos em 1890. Mais tarde, Konrad Zuse e Howard Aiken criaram máquinas cada vez mais próximas dos computadores como os conhecemos hoje. A grande virada tecnológica ocorreu com a introdução dos componentes eletrônicos: as válvulas deram origem à primeira geração de computadores eletrônicos, como o Colossus e o ENIAC. Posteriormente, os transistores substituíram as válvulas, inaugurando a segunda geração, seguidos pelos circuitos integrados (terceira geração) e, por fim, pela integração em larga escala (VLSI), que possibilitou o surgimento dos microcomputadores na década de 1970.

No aspecto conceitual, um computador digital é composto por processador, memória, dispositivos de entrada e saída, e interfaces de comunicação. O foco principal da arquitetura está no processador, onde ocorre o controle e a execução das instruções. A complexidade dos sistemas modernos exige o uso de abstrações, como a arquitetura de conjunto de instruções (ISA), que define uma interface clara entre hardware e software. Essas abstrações permitem que desenvolvedores criem soluções eficientes sem a necessidade de compreender os detalhes de cada componente, mas, ao mesmo tempo, valorizam profissionais que conhecem profundamente o funcionamento interno dos circuitos.

A disciplina enfatiza também a importância da integração entre hardware e software, conhecida como codesign. Ignorar essa interação pode levar a soluções ineficientes, enquanto compreendê-la pode resultar em sistemas otimizados e de melhor desempenho. Por fim, com base na teoria da computação proposta por Alan Turing, entende-se que qualquer computador, independentemente de seu porte, pode executar qualquer tarefa computacional, desde que possua tempo e memória suficientes.


### 📘 **Módulo 01 – Introdução à Arquitetura de Computadores**

#### Principais Tópicos:

- **O que é um computador digital?**
    
    - Composto por processador, memória, dispositivos de entrada e saída.
        
    - O foco da disciplina é o **processador**, que contém milhões/bilhões de transistores.
        
- **Abstração vs. Desconstrução:**
    
    - **Abstração:** entender o sistema como um todo sem focar em detalhes.
        
    - **Desconstrução:** saber como os componentes internos funcionam (ex: portas lógicas).
        
- **Codesign Hardware/Software:**
    
    - Profissionais que compreendem hardware e software têm vantagem no desenvolvimento eficiente de sistemas.
        
- **Computador como sistema computacional:**
    
    - Divide-se em **controle (decide o que executar)** e **execução (realiza operações)**.
        
    - **CPU** é a protagonista.
        
- **Teoria da Computação (Alan Turing):**
    
    - Todos os computadores, dados tempo e memória suficientes, podem realizar as mesmas tarefas.
        
    - Tese de Turing: qualquer computação pode ser feita por uma _máquina de Turing_.
        
- **Dispositivos Computacionais:**
    
    - **Analógicos** (ex: réguas de cálculo, ábaco) vs. **Digitais** (computadores modernos).
        
    - Computadores são **máquinas discretas programáveis**.
        
- **ISA (Instruction Set Architecture):**
    
    - Interface entre software e hardware.
        
    - Padroniza instruções, permitindo diferentes implementações.
        

---

### 📘 **Módulo 02 – Histórico da Computação**

#### Linha do Tempo da Computação:

1. **Pré-história da computação:**
    
    - Uso dos dedos, ábaco, tábuas babilônicas (Plimpton 322), bastões de Napier.
        
    - Blaise Pascal: **Pascaline**, faz somas e subtrações.
        
    - Leibniz: **Stepped Drum**, base para calculadoras futuras.
        
2. **Era mecânica (500 a.C. – 1880):**
    
    - Jacquard: **tear programado com cartões perfurados**.
        
    - Charles Babbage: **Máquina de Diferenças** e **Máquina Analítica** (Turing-completa).
        
3. **Era eletromecânica (1880 – 1930):**
    
    - Hollerith: tabuladores eletromecânicos para o censo americano.
        
    - Zuse: Z1, Z2, Z3 – primeiros computadores programáveis.
        
    - Aiken: Harvard Mark I – usado na 2ª Guerra Mundial.
        
4. **Era eletrônica (a partir de 1945):**
    
    - **1ª geração:** Computadores com válvulas (ex: Colossus, ENIAC).
        
    - **2ª geração:** Transistores (ex: IBM 7090).
        
    - **3ª geração:** Circuitos integrados (ex: série IBM 360).
        
    - **4ª geração:** VLSI – integração em larga escala (ex: Intel 4004).
        
        - Aparecimento dos **microcomputadores**.
            
        - Surgimento da **Lei de Moore** (dobro de transistores a cada 2 anos).