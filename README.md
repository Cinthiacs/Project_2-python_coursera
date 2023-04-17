# Project2 Python_Coursera

Projeto desenvolvido em Python, usando a IDE Jupyter, que tem como objetivo processar um arquivo de logs e extrair informações relevantes sobre eventos.

## Como usar

1. Faça o download ou clone do repositório em sua máquina.
2. Certifique-se de ter o Python instalado em sua máquina.
3. Instale a biblioteca Pandas, usando o seguinte comando no terminal: pip install pandas.
4. Abra o arquivo logs.py em sua IDE Python favorita (como o Jupyter).
5. Execute o arquivo e verifique os resultados obtidos.

### Descrição do projeto
O projeto consiste em ler um arquivo de logs (no formato CSV) e extrair informações relevantes sobre eventos. Para isso, o projeto utiliza a biblioteca Pandas para ler e processar o arquivo CSV.

Em seguida, o código define uma função chamada conta que recebe dois argumentos: o nome da coluna que será analisada e uma expressão regular que será usada para procurar ocorrências na coluna. A função retorna a quantidade de ocorrências encontradas.

O arquivo logs.py utiliza essa função para procurar por quatro tipos de eventos: falhas, erros, avisos e permissões. Para cada tipo de evento, o código imprime a quantidade de ocorrências encontradas.

### Autor
Esse projeto foi criado por Cinthia Cavalheiro.
