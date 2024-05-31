# Consulta IBGE - Dispatcher

Este projeto contém o código para o Dispatcher do processo "Consulta IBGE" utilizando UiPath.

## Estrutura do Projeto

- **Main.xaml**: Workflow principal.
- **Dispatcher.xaml**: Workflow que adiciona itens na fila do Orchestrator.
- **Config.xlsx**: Arquivo de configuração (se necessário).
- **Logs**: Pasta para armazenar logs do processo.

## Configuração

1. **Fila no Orchestrator**: Crie uma fila chamada `ConsultaIBGE`.
2. **Assets no Orchestrator**:
   - `ApiBaseUri`: URI base da API do IBGE.
   - `ApiEndpoints`: Endpoints específicos da API separados por vírgula.

## Execução

1. Abra o projeto no UiPath Studio.
2. Configure os Assets no Orchestrator.
3. Execute o workflow `Main.xaml`.

## Logs

Os logs são gerados na pasta `Logs`.

## Boas Práticas

- Comentários adicionados no código para melhor entendimento.
- Logs implementados para auditoria e debug.
- Tratamento de exceções implementado para garantir robustez.

