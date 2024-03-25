# Relatório sobre a atividade de Observabilidade do .NET com OpenTelemetry

## 1 - Conceitos aprendidos:

### Primeiro: O que é observabilidade?
Resumidamente, é a capacidade de monitorar e analisar a telemetria sobre o estado de cada componente, observar alterações no desempenho e diagnosticar por que essas alterações ocorrem, em que é geralmente realizada utilizando-se a combinação entre: (i) logs, (ii) métricas e (iii) rastreamento distribuído.

### Segundo: O que é o OpenTelemetry?
De forma resumida, o OpenTelemetry (OTel) é um padrão aberto e multiplataforma para coletar e emitir dados de telemetria, possibilitando a utilização de uma ampla variedade de sistemas APM.

### Terceiro: Como se dá a implementação do OpenTelemetry?
O OTel entra em ação porque coleta a telemetria de APIs vindas do próprio dotnet, caso esteja usando essa linguagem, e de outras fontes (por meio de bibliotecas de instrumentação) e, em seguida, as exporta para um sistema de monitoramento de desempenho de aplicativos (APM) para armazenamento e análise. O benefício que o OTel traz como padrão do setor é um mecanismo comum para coleta, esquemas e semântica comuns para dados telemétricos e uma API para como os APMs podem se integrar ao OTel. Com o uso do OTel, os aplicativos não precisam usar APIs ou estruturas de dados específicas de APM; eles funcionam de acordo com o padrão do OTel. Os APMs podem implementar um componente exportador específico do APM ou usar o OTLP, que é um novo padrão de ligação para exportar dados de telemetria para os sistemas APM.

### Quarto: O que é Prometheus?

Prometheus é uma ferramenta de código aberto para monitoramento de sistemas e alertas, originalmente desenvolvida na SoundCloud. Desde seu início em 2012, muitas empresas e organizações adotaram o Prometheus, que agora tem uma comunidade ativa de desenvolvedores e usuários. Tornou-se um projeto de código aberto independente e é mantido independentemente de qualquer empresa. Para reforçar isso e esclarecer a estrutura de governança do projeto, o Prometheus juntou-se à Cloud Native Computing Foundation em 2016 como o segundo projeto hospedado, após o Kubernetes.

O Prometheus coleta e armazena suas métricas como séries temporais, ou seja, as informações das métricas são armazenadas com a marca temporal de quando foram registradas, juntamente com pares chave-valor opcionais chamados labels.

### Quinto: O que é Grafana?

O Grafana é uma plataforma para visualizar e analisar métricas por meio de gráficos. Ele tem suporte para diversos tipos de bancos de dados — tanto gratuitos quanto pagos —, e pode ser instalado em qualquer sistema operacional.

Para facilitar a visualização dos gráficos, é possível criar dashboards dinâmicos que podem ser compartilhados com toda a equipe. Além disso, a ferramenta permite configurar alertas com base nas métricas, que são analisadas de forma contínua para notificar o usuário sempre que preciso, de acordo com as regras definidas por ele. É bastante utilizado por sistemas de monitoramento para gerar gráficos real-time.

### Sexto: O que é Jaeger?

O Jaeger é um software que você pode usar para monitorar e solucionar problemas em componentes de software interconectados, chamados de microsserviços. Vários microsserviços se comunicam entre si para concluir uma única função de software.

### Prints com codigo em funcionamento

API rodando
![image](https://github.com/yveslevi/metricas-atv/assets/98428867/540278e4-3d36-4088-a4fa-2625f0349575)

API retornando métricas
![image](https://github.com/yveslevi/metricas-atv/assets/98428867/0bf43973-2a41-4a6c-ba7a-45dc613599d0)

