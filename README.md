# Machine_Learning-IDS
Desenvolvimento de um módulo de detecção de ataques (IDS) utilizando Machine Learning, junto com TCPDump e CICFlowMeter.

A maneira que o módulo funciona para capturar os pacotes é utilizando a ferramenta TCPDump, passando tais PCAPs pela ferramenta CICFlowMeter e os transformnado em arquivos 'comma separated values' (.csv) que serão usados como entrada de dados para o módulo realizar a análise.

É possível realizar análise de fluxo de rede de 2 maneiras: <br>
1 - Arquivo PCAP existente; <br>
2 - Análise do tráfego de rede em tempo real. <br>

Créditos ao usuário iPAS pela ferramenta desenvolvida utilizando TCPDump e CICFlowMeter, e também ao usuário ahlashkari por disponibilizar a ferramenta CICFlowMeter.<br>
Link do repositório do trabalho do iPAS: https://github.com/iPAS/TCPDUMP_and_CICFlowMeter
Link do repositório da ferramenta CICFlowMeter: https://github.com/ahlashkari/CICFlowMeter
