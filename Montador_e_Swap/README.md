# Montador (Assembler) e Swap em Python 🐍🔧

Este é um dos projetos mais importantes, pois une o entendimento do hardware com a programação de software base, traduzindo instruções compreensíveis para humanos (Assembly) em código de máquina legível para o processador (binário/hexadecimal).

## Ferramentas Desenvolvidas

- **montador-Mikaelle.py** e **montador-Mikaellev2.py**:
  Estes scripts em Python são os Montadores (Assemblers) criados. Eles analisam e compilam códigos Assembly gerando o código de máquina equivalente. A versão `v2` traz melhorias e correções em relação à primeira versão do montador. O código lê o arquivo de entrada, mapeia as instruções, trata os mnemônicos e endereços, e gera a saída correspondente de acordo com a nossa Arquitetura de Conjunto de Instruções (ISA).

- **swap-Mikaelle.asm** e **swap-Mikaelle.txt**:
  O programa `swap` é um código básico de teste escrito em Assembly. Ele serve para validar se o montador consegue traduzir com sucesso e se o programa gerado consegue trocar com eficiência os valores de duas variáveis/registradores, um conceito fundamental na programação de baixo nível.
