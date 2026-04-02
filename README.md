# una-ihcux-lista04
Atividade UNA (Lista 05) - Interação Humano Computador UX

# 🚀 PROGRAMA CONVERSOR EXPERT

## 🛠️ Comandos de Construção Utilizados
- `dotnet new console`: Para criar a estrutura base do C#.
- `dotnet build`: Para transformar meu código em algo que o PC entende.
- `dotnet run`: Para ver a mágica acontecer.

## 📦 Estrutura Gerada
Arquivos que o .NET criou para mim:
1. `Program.cs`: Onde fica o código.
2. `ConversorExpert.csproj`: As configurações do meu projeto.

## Global Exchange - Conversor v1.0 💸
Este é um projeto de console desenvolvido em C# focado na aplicação prática de conceitos de IHC (Interação Humano-Computador) e UX (User Experience), utilizando as Heurísticas de Nielsen para otimizar a experiência do usuário em ambiente de terminal.

## 🧠 Heurísticas Aplicadas
O sistema foi construído sobre três pilares fundamentais de usabilidade:

1. Visibilidade do Status do Sistema (Heurística #01)
O usuário nunca é deixado "no escuro". O código utiliza feedbacks visuais para informar que o processamento está ocorrendo:
- Feedback de Processamento: Uso de Thread.Sleep e animação de pontos (...) para simular a conexão com o banco e o cálculo de taxas.
- Mensagens de Sistema: Tags como [SISTEMA] indicam claramente o que o software está fazendo naquele momento.

2. Prevenção de Erros (Heurística #05)
Em vez de permitir que o programa trave com uma exceção genérica do sistema, o código antecipa falhas de entrada:
- Bloco Try-Catch: Captura erros de digitação (como letras em campos numéricos).
- Tratamento Amigável: Caso ocorra um erro, o sistema exibe uma mensagem explicativa ensinando o usuário a forma correta de inserir os dados (ex: "Use apenas números e vírgula"), em vez de exibir códigos técnicos complexos.

3. Estética e Design Minimalista (Heurística #08)
O console foi organizado para dar prioridade à informação relevante, evitando poluição visual:
- Hierarquia Visual: Uso de cores (Yellow para cabeçalhos, Green para resultados e Red para erros) para destacar o que é importante.
- Espaçamento: Uso de Console.Clear() e divisórias (---) para manter a interface limpa e os dados legíveis.
- Foco no Diálogo: O software apresenta apenas o necessário para a tarefa de conversão, seguindo a regra de que "menos é mais".
  
## 🛠️ Tecnologias
- C# / .NET
- System.Threading (para simulação de latência de UX)
  
## 📸 Evidência de Execução
<img width="711" height="343" alt="evidencia-final" src="https://github.com/user-attachments/assets/9b2a06d2-af4e-4a36-8a0d-ef1693a41565" />
