# Relatório sobre a atividade de Observabilidade do .NET com OpenTelemetry

1 - Conceitos aprendidos:

Primeiro: O que é observabilidade?
Resumidamente, é a capacidade de monitorar e analisar a telemetria sobre o estado de cada componente, observar alterações no desempenho e diagnosticar por que essas alterações ocorrem, em que é geralmente realizada utilizando-se a combinação entre: (i) logs, (ii) métricas e (iii) rastreamento distribuído.

Segundo: O que é o OpenTelemetry?
De forma resumida, o OpenTelemetry (OTel) é um padrão aberto e multiplataforma para coletar e emitir dados de telemetria, possibilitando a utilização de uma ampla variedade de sistemas APM.

Terceiro: Como se dá a implementação do OpenTelemetry?
O OTel entra em ação porque coleta a telemetria de APIs vindas do próprio dotnet, caso esteja usando essa linguagem, e de outras fontes (por meio de bibliotecas de instrumentação) e, em seguida, as exporta para um sistema de monitoramento de desempenho de aplicativos (APM) para armazenamento e análise. O benefício que o OTel traz como padrão do setor é um mecanismo comum para coleta, esquemas e semântica comuns para dados telemétricos e uma API para como os APMs podem se integrar ao OTel. Com o uso do OTel, os aplicativos não precisam usar APIs ou estruturas de dados específicas de APM; eles funcionam de acordo com o padrão do OTel. Os APMs podem implementar um componente exportador específico do APM ou usar o OTLP, que é um novo padrão de ligação para exportar dados de telemetria para os sistemas APM.

Quarto: O que é Prometheus?

Quinto: O que é Grafana?

Sexto: O que é Jaeger?

/
![image](https://github.com/yveslevi/metricas-atv/assets/98428867/540278e4-3d36-4088-a4fa-2625f0349575)

/metrics
![image](https://github.com/yveslevi/metricas-atv/assets/98428867/0bf43973-2a41-4a6c-ba7a-45dc613599d0)


senha: atvsem7
