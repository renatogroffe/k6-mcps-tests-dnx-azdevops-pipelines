# k6-mcps-tests-dnx-azdevops-pipelines
Exemplo de implementação de testes de validação com k6 para MCP Servers acionados via dnx (.NET 10) e que inclui execução automatizada a partir de um pipeline do Azure DevOps. Inclui o build do executável do k6 com a extensão para MCPs via container.

Extensão do k6 para MCP: https://github.com/grafana/xk6-mcp

Package NuGet utilizado nos testes: https://www.nuget.org/packages/FakeDataMcpServer/