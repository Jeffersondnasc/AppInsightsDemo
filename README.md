# AppInsightsDemo

Este projeto é um exemplo de integração do ASP.NET Core com o Azure Monitor usando OpenTelemetry Exporter.

## Funcionalidades
- Exemplo de API Web com endpoint `/weatherforecast`
- Telemetria de traces, logs e métricas enviada para o Azure Monitor
- Configuração via appsettings.json (a chave de conexão deve ser inserida manualmente)

## Como usar
1. Insira sua chave de conexão do Application Insights em `appsettings.json`.
2. Execute o projeto com `dotnet run --project AppInsightsDemo/AppInsightsDemo.csproj`.
3. Acesse `http://localhost:5289/weatherforecast` para gerar telemetria.

## Observações
- A chave de conexão não está incluída no repositório por motivos de segurança.
- O projeto utiliza as bibliotecas Azure.Monitor.OpenTelemetry.Exporter e OpenTelemetry.Instrumentation.AspNetCore.

## Requisitos
- .NET 10 ou superior
- Conta e recurso Application Insights no Azure

## Branch
O código será enviado para a branch `dev`.

---

Para dúvidas ou sugestões, abra uma issue no repositório.

contato:jeffersondnasc@gmail.com


