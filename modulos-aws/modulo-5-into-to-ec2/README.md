# 🖥️ Módulo 5: Introdução ao Amazon EC2

O **Amazon Elastic Compute Cloud (Amazon EC2)** é um serviço que provê capacidade computacional redimensionável e gerenciável na nuvem. Em termos simples, as chamadas **Compute Instances** são os servidores virtuais (*virtual servers*) que nós gerenciamos dentro da AWS.

---

## 📌 Características Principais do EC2

| Característica | Descrição |
| :--- | :--- |
| **Resizable (Redimensionável)** | Permite aumentar ou diminuir a capacidade computacional (CPU, RAM, Armazenamento) facilmente conforme a demanda. |
| **Affordable (Acessível)** | Sistema de pagamento por uso. Você só paga pelos segundos ou horas em que a instância estiver rodando. |
| **Global** | Pode ser implantado instantaneamente em qualquer Região ou Zona de Disponibilidade da AWS ao redor do mundo. |

---

## ⚙️ Famílias de Instâncias (Tipos de Servidores)

A AWS divide as instâncias em "famílias" para que você escolha o hardware ideal baseado no seu tipo de carga de trabalho:

| Família de Instância | Foco / Principal Caso de Uso | Exemplo de Aplicação |
| :--- | :--- | :--- |
| **General Purpose** (Uso Geral) | Equilíbrio entre CPU, memória e rede. | Servidores web básicos, ambientes de teste. |
| **Compute-Optimized** | Foco em alto processamento de CPU. | Processamento de lote, servidores de jogos, codificação de vídeo. |
| **Memory-Optimized** | Foco em processar grandes volumes de dados na memória RAM. | Bancos de dados *open-source*, Big Data. |
| **Storage-Optimized** | Foco em alta velocidade de leitura/escrita no disco (I/O). | Bancos de dados NoSQL gigantes, sistemas de arquivos distribuídos. |
| **Accelerated Computing** | Uso de placas gráficas (GPU) ou aceleradores de hardware. | Machine Learning, renderização 3D, computação gráfica. |

---

## 💰 Modelos de Precificação (Opções de Compra)

A forma como você compra as instâncias impacta diretamente no custo do seu projeto:

| Modelo de Compra | Como Funciona | Melhor Caso de Uso |
| :--- | :--- | :--- |
| **On-Demand Instances** | Paga por segundo ou hora de uso. Sem compromisso de longo prazo ou pagamento adiantado. | Cargas de trabalho flexíveis, testes rápidos ou sistemas imprevisíveis. |
| **Savings Plans** | Compromisso de gastar um valor fixo por hora (ex: $10/hora) por 1 ou 3 anos. Dá até 72% de desconto. | Empresas com uso de computação constante, mas que mudam muito o tipo de instância. |
| **Spot Instances** | Compra da capacidade ociosa da AWS com até 90% de desconto. **Atenção:** A AWS pode derrubar o servidor com aviso prévio de 2 minutos se precisar do espaço. | Tarefas que podem ser interrompidas (ex: renderização de vídeos, análises de dados). |
| **Dedicated Hosts** | Um servidor físico totalmente dedicado para você. | Requisitos rígidos de conformidade (compliance) ou licenças de software antigas. |

---

* **Integrado:** Amazon EC2 pode ser integrado com a maior parte dos serviços AWS. **Amazon Simple Storage Services** (Amazon S3), **Amazon Relational Database Service** (Amazon RDS), **Amazon Virtual Private Clound** (Amazon VPC).

![Arquitetura de Estrutura EC2](<img width="1359" height="808" alt="image" src="https://github.com/user-attachments/assets/8e7e3b33-a8ad-4969-b066-16405b604c0a" />
)


