# FizzBuzz

Uma implementação funcional do clássico problema FizzBuzz em Elixir, demonstrando os principais conceitos de programação funcional.

## 📋 Funcionalidades praticadas

- **Princípios da Programação Funcional**: Funções puras, imutabilidade e composição de funções
- **Pattern Matching**: Lógica condicional elegante para extração de valores
  - Usado nas heads de função para determinar os casos FizzBuzz.
  - Lida com diferentes tipos de retorno (átomos vs números).
- **Guards**: Restrições para cláusulas de funções
  - Condições adicionais para verificar divisibilidade.
  - Garante que apenas inteiros sejam processados.
- **Pipe Operator**: Pipelines de transformação de dados
  - Encadeia leitura de arquivo, parsing e transformação.
  - Cria pipelines de dados legíveis.
- **Módulo Enum**: Processamento de coleções
  - Enum.map/2 para transformações elemento por elemento.
  - Enum.join/2 para formatação de mensagens de erro.
- **Tratamento de Erros**: Tuplas explícitas de sucesso/erro
