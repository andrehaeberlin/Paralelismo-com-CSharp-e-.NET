# Paralelismo com C# e .NET — ByteBank

Projeto educacional desenvolvido no curso de Paralelismo com C# e .NET da Alura. Simula a consolidação de movimentações bancárias em paralelo, usando dados de exemplo em memória.

## Conceitos praticados

- Processamento concorrente de contas com `Task.Factory.StartNew` e `Task.WhenAll`.
- Operações assíncronas com `async`/`await`.
- Cancelamento cooperativo com `CancellationToken`.
- Atualização de progresso e tempo de processamento na interface WPF.

## Estrutura

- `ByteBank.Core`: modelos de contas e movimentações, repositório de dados de exemplo e serviço de consolidação.
- `ByteBank.View`: aplicativo desktop WPF, com controles para processar e cancelar operações e visualizar resultados.

## Executar

Em Windows, abra `ByteBank.sln` no Visual Studio com suporte ao desenvolvimento desktop .NET e ao .NET Framework 4.5.2, configure `ByteBank.View` como projeto de inicialização e pressione F5.

O .NET Framework 4.5.2 é uma dependência legada do exercício; o projeto não é um sistema bancário de produção.
