# Papers

Use `[ ]` para marcar um paper pendente e troque para `[x]` depois da leitura.

- [ ] **A Runtime and Non-Intrusive Approach to Optimize EDP by Tuning Threads and CPU Frequency for OpenMP Applications**
	- PDF: [A Runtime and Non-Intrusive Approach to Optimize EDP by Tuning Threads and CPU Frequency for OpenMP Applications.pdf](A%20Runtime%20and%20Non-Intrusive%20Approach%20to%20Optimize%20EDP%20by%20Tuning%20Threads%20and%20CPU%20Frequency%20for%20OpenMP%20Applications.pdf)
	- Autores: Janaina Schwarzrock, Charles C. de Oliveira, Marcus Ritt, Arthur F. Lorenzon e Antonio Carlos S. Beck
	- Resumo: Propõe uma solução em tempo de execução que ajusta o número de threads e a frequência da CPU em aplicações OpenMP, buscando reduzir o Energy-Delay Product sem exigir alterações no código da aplicação.

- [ ] **AtTune: A Heuristic based Framework for Parallel Applications Autotuning**
	- PDF: [AtTune: A Heuristic based Framework for Parallel Applications Autotuning.pdf](AtTune%3A%20A%20Heuristic%20based%20Framework%20for%20Parallel%20Applications%20Autotuning.pdf)
	- Autores: Hiago Mayk G. de A. Rocha, Janaina Schwarzrock, Monica M. Pereira, Lucas M. Schnorr, Philippe Navaux, Arthur F. Lorenzon e Antonio Carlos S. Beck
	- Resumo: Apresenta uma heurística que ajusta conjuntamente o número de processos ou threads e a frequência da CPU. O objetivo é otimizar desempenho, consumo de energia ou EDP em aplicações MPI e OpenMP.

- [ ] **Aurora: Seamless Optimization of OpenMP Applications**
	- PDF: [Aurora: Seamless Optimization of OpenMP Applications.pdf](Aurora%3A%20Seamless%20Optimization%20of%20OpenMP%20Applications.pdf)
	- Autores: Arthur Francisco Lorenzon, Charles Cardoso de Oliveira, Jeckson Dellagostin Souza e Antonio Carlos Schneider Beck
	- Resumo: Apresenta um sistema transparente para escolher dinamicamente o grau de paralelismo de aplicações OpenMP, adaptando-se à aplicação, entrada e arquitetura para melhorar desempenho e eficiência energética.

- [-] **Energy-Aware Tuning of Pthreads and OpenMP Applications for Asymmetric Multicore Architectures**
	- PDF: [Energy-Aware Tuning of Pthreads and OpenMP Applications for Asymmetric Multicore Architectures.pdf](Energy-Aware%20Tuning%20of%20Pthreads%20and%20OpenMP%20Applications%20for%20Asymmetric%20Multicore%20Architectures.pdf)
	- Autores: Felipe N. Laguna, Marcelo K. Moori, Hiago Mayk G. de A. Rocha e Antonio Carlos S. Beck
	- Resumo: Apresenta o Caipiratuning, framework que procura automaticamente mapeamentos thread-núcleo para aplicações Pthreads e OpenMP em arquiteturas assimétricas, reduzindo tempo de execução, energia e EDP.

- [ ] **Feedback-Directed Pipeline Parallelism**
	- PDF: [Feedback-Directed Pipeline Parallelism.pdf](Feedback-Directed%20Pipeline%20Parallelism.pdf)
	- Autores: M. Aater Suleman, Moinuddin K. Qureshi, Khubaib e Yale N. Patt
	- Resumo: Introduz o Feedback-Directed Pipelining, que decide em tempo de execução quantos núcleos alocar a cada estágio de um pipeline. Primeiro maximiza o desempenho e depois desativa núcleos excedentes para economizar energia sem perder performance.

- [ ] **How to apply Amdahl's law to multithreaded multicore processors**
	- PDF: [How to apply Amdahl's law to multithreaded multicore processors.pdf](How%20to%20apply%20Amdahl's%20law%20to%20multithreaded%20multicore%20processors.pdf)
	- Autores: James Nutaro e Bernard Zeigler
	- Resumo: Discute ambiguidades ao aplicar a lei de Amdahl a processadores multicore. Os autores defendem separar explicitamente as partes computacional e de acesso à memória para obter previsões de speedup mais claras.

- [ ] **Online energy-efficient fair scheduling for heterogeneous multi-cores considering shared resource contention**
	- PDF: [Online energy-efficient fair scheduling for heterogeneous multi-cores considering shared resource contention.pdf](Online%20energy-efficient%20fair%20scheduling%20for%20heterogeneous%20multi-cores%20considering%20shared%20resource%20contention.pdf)
	- Autores: Bagher Salami, Hamid Noori e Mahmoud Naghibzadeh
	- Resumo: Desenvolve um escalonador online para sistemas multicore heterogêneos que considera justiça entre tarefas, eficiência energética e contenção por recursos compartilhados.

- [ ] **Performance evaluation on work-stealing featured parallel programs on asymmetric performance multicore processors**
	- PDF: [Performance evaluation on work-stealing featured parallel programs on asymmetric performance multicore processors.pdf](Performance%20evaluation%20on%20work-stealing%20featured%20parallel%20programs%20on%20asymmetric%20performance%20multicore%20processors.pdf)
	- Autores: Adnan
	- Resumo: Avalia como programas paralelos baseados em work-stealing se comportam em processadores multicore assimétricos, comparando desempenho e aproveitamento dos diferentes tipos de núcleo.

- [ ] **RUNCORE: Energy-Aware Resource Allocation for Hybrid CPU Warehouse Systems**
	- PDF: [RUNCORE: Energy-Aware Resource Allocation for Hybrid CPU Warehouse Systems.pdf](RUNCORE%3A%20Energy-Aware%20Resource%20Allocation%20for%20Hybrid%20CPU%20Warehouse%20Systems.pdf)
	- Autores: Não informado na versão disponível do PDF
	- Resumo: Propõe um gerenciador de recursos para workloads em contêineres sobre CPUs assimétricas. O método combina controle de threads, seleção de núcleos e redistribuição cooperativa para reduzir o EDP sob alta concorrência.

- [ ] **Smoothing on Dynamic Concurrency Throttling**
	- PDF: [Smoothing on Dynamic Concurrency Throttling.pdf](Smoothing%20on%20Dynamic%20Concurrency%20Throttling.pdf)
	- Autores: Janaina Schwarzrock, Hiago Mayk G. de A. Rocha, Arthur F. Lorenzon e Antonio Carlos S. Beck
	- Resumo: Investiga como suavizar mudanças dinâmicas no nível de concorrência para evitar oscilações e custos de adaptação. A proposta busca equilibrar desempenho e eficiência energética em aplicações paralelas.

- [ ] **Speedup and efficiency of computational parallelization: A unifying approach and asymptotic analysis**
	- PDF: [Speedup and efficiency of computational parallelization: A unifying approach and asymptotic analysis.pdf](Speedup%20and%20efficiency%20of%20computational%20parallelization%3A%20A%20unifying%20approach%20and%20asymptotic%20analysis.pdf)
	- Autores: Guido Schryen
	- Resumo: Propõe uma abordagem unificada para analisar speedup e eficiência de paralelizações, incluindo o comportamento assintótico e os limites impostos pelo aumento do número de recursos.

- [ ] **When Less Is MOre (LIMO): Controlled Parallelism for Improved Efficiency**
	- PDF: [When Less Is MOre (LIMO): Controlled Parallelism for Improved Efficiency.pdf](When%20Less%20Is%20MOre%20%28LIMO%29%3A%20Controlled%20Parallelism%20for%20Improved%20Efficiency.pdf)
	- Autores: Gaurav Chadha, Scott Mahlke e Satish Narayanasamy
	- Resumo: Apresenta um runtime que ajusta dinamicamente o número de threads e a frequência de operação. A proposta evita o excesso de paralelismo, reduz contenção por recursos compartilhados e melhora eficiência energética.

## Leituras futuras

Referências acadêmicas selecionadas a partir dos artigos acima. Os itens abaixo ainda não possuem PDF nesta pasta.

- [ ] **Adaptive execution techniques for SMT multiprocessor architectures**
	- Autores: C. Jung, D. Lim, J. Lee e S. Han
	- Referenciado em: Aurora e When Less Is MOre (LIMO)
	- Resumo: Estuda técnicas para adaptar a execução de aplicações em processadores SMT, ajustando o uso de recursos conforme o comportamento das threads.

- [ ] **Adaptive, efficient, parallel execution of parallel programs**
	- Autores: S. Sridharan, G. Gupta e G. S. Sohi
	- Referenciado em: Aurora
	- Resumo: Explora mecanismos de execução paralela adaptativa para melhorar eficiência e desempenho sem depender de uma configuração fixa de threads.

- [ ] **Amdahl's law for multithreaded multicore processors**
	- Autores: Hao Che e Minh Nguyen
	- Referenciado em: How to apply Amdahl's law to multithreaded multicore processors
	- Resumo: Reanalisa a lei de Amdahl para workloads multithreaded, considerando efeitos de memória e afinidade entre tarefas em processadores multicore.

- [ ] **Bottleneck identification and scheduling in multithreaded applications**
	- Autores: J. A. Joao, M. A. Suleman, O. Mutlu e Y. N. Patt
	- Referenciado em: Aurora
	- Resumo: Propõe identificar gargalos de execução e usá-los para orientar o escalonamento de aplicações multithreaded.

- [ ] **Contention-Aware Fair Scheduling for Asymmetric Single-ISA Multicore Systems**
	- Autores: A. Garcia-Garcia, J. C. Saez e M. Prieto-Matias
	- Referenciado em: Online energy-efficient fair scheduling...
	- Resumo: Investiga escalonamento justo em sistemas assimétricos que compartilham a mesma ISA, levando em conta a contenção por recursos.

- [ ] **Feedback-driven threading: Power-efficient and high-performance execution of multi-threaded workloads on CMPs**
	- Autores: M. A. Suleman, M. K. Qureshi e Y. N. Patt
	- Referenciado em: A Runtime..., Aurora e Smoothing on Dynamic Concurrency Throttling
	- Resumo: Usa feedback da execução para ajustar o número de threads e buscar simultaneamente alto desempenho e menor consumo de energia.

- [ ] **Fairness-aware scheduling on single-ISA heterogeneous multi-cores**
	- Autores: K. Van Craeynest, S. Akram, W. Heirman, A. Jaleel e L. Eeckhout
	- Referenciado em: Online energy-efficient fair scheduling...
	- Resumo: Analisa políticas de escalonamento que preservam justiça entre aplicações em processadores heterogêneos com uma ISA comum.

- [ ] **Holistic run-time parallelism management for time and energy efficiency**
	- Autores: S. Sridharan, G. Gupta e G. S. Sohi
	- Referenciado em: Aurora
	- Resumo: Gerencia o paralelismo em tempo de execução considerando desempenho e energia como objetivos combinados.

- [ ] **Maximizing power efficiency with asymmetric multicore systems**
	- Autores: A. Fedorova, J. C. Saez, D. Shelepov e M. Prieto
	- Referenciado em: When Less Is MOre (LIMO) e Performance evaluation...
	- Resumo: Estuda como distribuir workloads entre núcleos assimétricos para aproveitar as diferenças de desempenho e consumo.

- [ ] **Online power-performance adaptation of multithreaded programs using hardware event-based prediction**
	- Autores: M. Curtis-Maury, J. Dzierwa, C. D. Antonopoulos e D. S. Nikolopoulos
	- Referenciado em: Aurora
	- Resumo: Usa eventos de hardware para prever o comportamento de aplicações multithreaded e adaptar dinamicamente o equilíbrio entre potência e desempenho.

- [ ] **Parcae: A system for flexible parallel execution**
	- Autores: A. Raman, A. Zaks, J. W. Lee e D. I. August
	- Referenciado em: Aurora
	- Resumo: Apresenta um sistema para executar aplicações paralelas com flexibilidade, explorando diferentes configurações de paralelismo conforme os recursos disponíveis.

- [ ] **Performance of parallel processors**
	- Autores: H. P. Flatt e K. Kennedy
	- Referenciado em: Speedup and efficiency of computational parallelization...
	- Resumo: Discute modelos clássicos para avaliar desempenho de processadores paralelos, speedup e eficiência.

- [ ] **Scheduling heterogeneous multicores through performance impact estimation (PIE)**
	- Autores: K. Van Craeynest, A. Jaleel, L. Eeckhout, P. Narvaez e J. Emer
	- Referenciado em: Online energy-efficient fair scheduling...
	- Resumo: Propõe estimar o impacto de alocar tarefas a diferentes tipos de núcleo para orientar o escalonamento de multicores heterogêneos.

- [ ] **Survey of scheduling techniques for addressing shared resources in multicore processors**
	- Autores: S. Zhuravlev, J. C. Saez, S. Blagodurov, A. Fedorova e M. Prieto
	- Referenciado em: Online energy-efficient fair scheduling...
	- Resumo: Revisa técnicas de escalonamento voltadas à contenção em caches, memória e outros recursos compartilhados de processadores multicore.

- [ ] **The PARSEC benchmark suite: Characterization and architectural implications**
	- Autores: C. Bienia, S. Kumar, J. P. Singh e K. Li
	- Referenciado em: Feedback-Directed Pipeline Parallelism e When Less Is MOre (LIMO)
	- Resumo: Apresenta e caracteriza a suíte PARSEC, usada para avaliar aplicações paralelas e suas implicações arquiteturais.

- [ ] **Thread reinforcer: Dynamically determining number of threads via OS level monitoring**
	- Autores: K. K. Pusukuri, R. Gupta e L. N. Bhuyan
	- Referenciado em: Aurora
	- Resumo: Determina dinamicamente o número de threads usando monitoramento em nível de sistema operacional.

- [ ] **Thread tailor: Dynamically weaving threads together for efficient, adaptive parallel applications**
	- Autores: J. Lee, H. Wu, M. Ravichandran e N. Clark
	- Referenciado em: Aurora
	- Resumo: Adapta a organização das threads durante a execução para tornar aplicações paralelas mais eficientes e responsivas às mudanças de carga.

- [ ] **Towards energy budget control in HPC**
	- Autores: P.-F. Dutot, Y. Georgiou, D. Glesser, L. Lefevre, M. Poquet e I. Rais
	- Referenciado em: A Runtime... e Aurora
	- Resumo: Estuda mecanismos para controlar orçamentos de energia em aplicações e ambientes de computação de alto desempenho.