# ⚠️ IMPORTANTE!!!

Esse projeto é apenas um repositório de **_TESTES_** e é passível de **_ERRROS_** na análise e recuperação de dados.

O objetivo é fazer testes sobre algumas das tecnologias de desenvolvimento se software desktop atuais do mercado, procurando a que melhor atenda os seguintes objetivos:

1. Performace
1. Segurança
1. Utilização de tecnologias modernas para a criação de interfaces
1. Utilização de tecnologias perfomaticas para processamentos pesados
1. Fácil manutenção
1. Simples na criação de um novo projeto
1. Arquitetura simples

PS.: Não foi utilizado "métodos rigidos" para a analise dos tópicos de interesse. Cada tecnologia funciona da sua própria maneira. É muito dificil deixar nas mesmas condições. No entanto, como dito, o objetivo é procurar uma tecnlogia que atenda da melhor forma possivel os tópicos definidos. Se por acaso você tiver alguma sujestão que melhore o meu método de análise, fique a vontade para comentar :)

PS.2: Eu já brinquei com electron. Estou insatisfeito com a minha experiencia com ele, e quero compara-lo com o Tauri e qualquer outra tecnologia desktop que eu achar interessante. Motivos da minha insatisfação: performace ruim e ambiente caótico (isso era agravado porque eu utilizava junto com VueJS... vamos ser sinceros as frameworks vieram para facilitar a vida. Nós queremos utiliza-las). Meu principal foco é conseguir encontrar uma opção de desenvolvimento desktop moderna e eficiente (em todos os sentidos).

# 👷🏻‍♂️ Como os projetos foram criados

- Electron
  - Vanilla (html): [utilizado o boilerplate](https://github.com/electron/electron-quick-start)
  - React: [utilizado o boilerplate](https://github.com/electron-react-boilerplate/electron-react-boilerplate)
- Tauri
  - Foi utilizado o próprio CLI nativo do Tauri... por isso ele foi muito mais estável e eficiente

`Nesse ponto podemos ver como o Tauri já é mais simples do que o electron: já tem os 'boilerplates' no seu próprio CLI. Facilitando o trabalhado do desenvolvedor em criar um novo projeto e mantendo uma estrutura de pastas padronizada evitando dores de cabeça para entender o código do amiguinho. Ponto para o Tauri`

# 📝 1. App simples: consumo de memória RAM

Os aplicativos criados devem ter o minimo de informação possivel e apenas uma mensagem de exibição. Sem qualquer tipo de processamento.

- Electron
  - Vanilla (html): ~51MB de memória ram
  - React: ~60MB de memória ram (Executando o build)
- Tauri
  - Vanilla (html): ~51MB de memória ram
  - React com javascript: ~51MB de memória ram
  - React com typescript: ~51MB de memória ram

`Aqui já podemos ver novamente a desvantagem do Electron com relação aos boilerplates.... Por não vir de uma unica fonte, cada desenvolvedor vai implementar as frameworks de alguma forma, as vezes, essas implementações custam memória ram`




# Próximos
## Windows Forms .net 6
## Windows Forms .net Framework 4
## MAUI
## UWP 
## Flutter
## C++
## C++ Qt