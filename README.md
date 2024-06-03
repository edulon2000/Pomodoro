![image](https://github.com/edulon2000/Pomodoro/assets/51751836/73041a10-39da-4f52-a68a-387183b92c6d)
# Pomodoro Timer

Este projeto é um simples cronômetro Pomodoro desenvolvido em Python usando a biblioteca Tkinter para a interface gráfica. O método Pomodoro é uma técnica de gerenciamento de tempo que utiliza intervalos de trabalho focado intercalados com breves pausas para maximizar a produtividade.

## Funcionalidades

- **Tempos configuráveis**: Sessões de trabalho de 25 minutos, pausas curtas de 5 minutos e pausas longas de 20 minutos.
- **Contagem automática**: Alterna automaticamente entre períodos de trabalho e pausas.
- **Interface visual**: Interface gráfica amigável que mostra o tempo restante e indica o modo atual (trabalho, pausa curta, pausa longa).
- **Marcação de progresso**: Exibe marcas de verificação para cada sessão de trabalho concluída.

## Uso

1. **Iniciar o temporizador**: Clique no botão "Start" para iniciar o ciclo Pomodoro.
2. **Redefinir o temporizador**: Clique no botão "Reset" para parar o temporizador e redefinir todas as contagens.

## Código

O código está dividido em várias seções:

- **Configuração de constantes**: Definição de cores, tempos e variáveis globais.
- **Função de reset**: Para cancelar o temporizador e redefinir a interface.
- **Mecanismo do temporizador**: Para iniciar o temporizador e alternar entre os modos de trabalho e pausa.
- **Mecanismo de contagem regressiva**: Para atualizar o temporizador a cada segundo e alternar modos ao término de cada contagem.
- **Configuração da interface do usuário**: Criação da janela principal, labels, botões e canvas para exibir o cronômetro e outros elementos visuais.

## Como executar

Certifique-se de ter Python e Tkinter instalados. Coloque a imagem `tomato.png` no mesmo diretório que o script Python. Execute o script para iniciar a aplicação Pomodoro.

```bash
python pomodoro.py
```
Ou simplismente use o executavel que esta disponivel.
Esta aplicação é ideal para quem procura uma maneira simples e eficaz de gerenciar seu tempo e aumentar a produtividade através da técnica Pomodoro.

