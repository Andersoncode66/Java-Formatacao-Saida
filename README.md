# Java-Formatacao-Saida


# Índice
1. Introdução
2. Descrição
3. Tecnologias utilizadas
4. Exemplos
5. Como usar
6. Contribuições
7. Licença
8. Conclusão 


# Introdução
Bem-vindo ao repositório Formatação de Saída em Java!
Este projeto foi criado para demonstrar diferentes técnicas e boas práticas ao formatar e apresentar dados em Java. Aqui você encontrará exemplos e exercícios que exploram como controlar precisão, casas decimais, e alinhamento ao exibir números e strings no console ou em relatórios.


# Descrição
Em java, a formatação de saída é essencial para apresentar resultados de forma clara e precisa, especialmente ao lidar com números e texto. Aqui estão algumas das principais opções de formatação que você pode utilizar para controlar precisão, alinhamento e casas decimais na saída:


# Tecnologias utilizadas
Java


# Como utilizar
1. Clone este repositório para seu ambiente local.
2. Compile e execute os arquivos Java  para ver os exemplos em ação.


### 1. Formatação com String.format()
O método String.format() permmite a criação de uma string formatada com precisão de números, casas decimais e alinhamento de valores.


### Sintaxe Geral:

![ex1](https://github.com/user-attachments/assets/ee701d9a-d69c-4945-9a3b-dc33083fbaef)

O formato usa especificadores que começam com %, e cada especificador define como o valor será formatado.

### Especificadores Comuns:

- %d: Inteiros
- %f: Números de ponto flutuante.
- %s: Strings.

### 2. Precisão e Casas Decimais:
Para formatar números de ponto flutuante com controle de casas decimais, você pode usar o especificador %f com precisão.

#### Exemplo:

![ex2](https://github.com/user-attachments/assets/5076d84c-a267-4031-8f10-31401303d1f8)

Aqui, %,2f define que queremos apenas 2 casas decimais.

### 3. Alinhamento:
Você pode alinhar os valores á esquerda ou á direita usando especificadores numéricos. Para números, o alinhamento padrão é á direita, mas você pode alterar isso com modificadores.

- Alinhamento á direita (padrão): Especifique o número mínimo de caracteres que a saída deve ocupar. Se o valor tiver meenos caracteres, espaços serão adicionados á esquerda.

#### Exemplo:

![lone](https://github.com/user-attachments/assets/9aa81a29-8d17-4c83-9382-4c6c9e6a3570)

Aqui, %.2f define que queremos apenas 2 casas decimais.


### 3. Alinhamento:
Você pode alinhar os valores á esquerda ou á direita usando especificadores numéricos. Para números, o alinhamento padrão é á direita, mas você pode alterar isso com modificadores.

- Alinhamento á direita (Padrão): Especefique o número mínimo de caracteres que a saída deve ocupar. Se o valor tiver menos caracteres, espaços serão adicionados á esquerda.

-  ### Exemplo:

![ex1](https://github.com/user-attachments/assets/4bb998a5-0977-485e-8f25-23c224a17a51)

- Alinhamento á esquerda: Para alinhar á esquerda, use o sinal de menos (-) antes  da largura mínima.

### Exemplo:

![ex2](https://github.com/user-attachments/assets/0f01ffb6-2b66-4771-8bb7-587ad7f57a7b)


### 4. Formatação com DecimalFormat:
Outra maneira de formatar números é com a classe DecimalFormat, que oferece ainda mais controle sobre casas decimais e padrões de formatação.

### Exemplo de Formatação com DecimalFormat:

![ex1](https://github.com/user-attachments/assets/42a82c8f-574c-4e8a-95c8-369c51ebf7a9)

Você também pode usar diferentes padrões,como #,###.##. para adicionar separados de militar.


### 5. Exemplo Completos:

#### a) Formatando com Precisão e Casas Decimais:

![ex2](https://github.com/user-attachments/assets/ffab2611-82aa-40d2-9bb2-11b0adf63202)

#### b) Alinhamento á esquerda com Números inteiros:

![ex3](https://github.com/user-attachments/assets/99eafee8-9c16-47ae-a1b2-248c617badc7)



#### c) Formatação de String com Alinhamento:


![c](https://github.com/user-attachments/assets/c4fc8a7e-053e-4c95-8a0a-ea335c74d955)


### 6. Formatação Avançada de Números com Formatter
A classe Formatter permite formatar de forma avançada vários tipos de dados com mais controle sobre alinhamento e precisão. Ela é muito útil quando você precisa de mais personalização.

### Exemplo:

![6](https://github.com/user-attachments/assets/aae7098f-f467-4ed7-a25f-9193f8f7324b)

### Resumo:
- Precisãoe e Casas Decimais: Controle usando %f e especificando o número de casas desejadas (%.2f para 2 casas).
- Alinhamento: Alinhe á esquerda ou á direita com %- ou % seguido da largura de campo (%-10s para alinhamento á esquerda de um string).
- Formatação Avançada: Utilize String.format().Printf(), ou classe DecimalFormat para personalizar a saída.

Essas opções ajudam a tornar a saída do programa mais legível e profissional, especialmente em relatórios ou interfaces com usuários.

# Como usar
1. Clone este repositório para o seu ambiente local.
2. Compile e execute os arquivos Java para ver os exemplos em ação.

# Contribuições
Contribuições são bem-vindas! Se você encontrar algum problema ou tiver sugestões, sinta-se à vontade para abrir uma issue ou enviar um pull request.

# Licença
Este projeto está licenciado sob a licença MIT - veja o arquivo LICENSE para mais detalhes.

