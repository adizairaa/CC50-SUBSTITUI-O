🛡️ Laboratório: Cifra de Substituição

Este repositório contém a solução para o desafio de cifra de substituição do curso CS50 de Harvard, onde o objetivo é criptografar um texto substituindo cada letra do alfabeto por outra, conforme uma chave definida pelo usuário.

📄 Descrição do Problema
O programa permite ao usuário fornecer uma chave de substituição para criptografar um texto simples. As regras principais são:

A chave deve conter exatamente 26 caracteres alfabéticos.

Cada letra do alfabeto deve aparecer uma única vez na chave.

Letras maiúsculas e minúsculas no texto original devem ser preservadas.

Caracteres não alfabéticos permanecem inalterados.

🧮 Exemplo de Execução

$ ./substitution YTNSHKVEFXRBAUQZCLWDMIPGJO
tempo simples: HELLO
tempo cifrado: EHBBQ

🚀 Como Rodar o Programa

Pré-requisitos

Ter um compilador C instalado, como o gcc.

Ter a biblioteca CS50 configurada no seu ambiente.

Execução

Clone o repositório:

git clone https://github.com/seuusuario/substitution.git
cd substitution

Compile o código:

gcc -o substitution substitution.c -lcs50

Execute o programa:

./substitution CHAVE_AQUI

Insira o texto simples para ser criptografado.

📚 Detalhes da Implementação

Validação de Entrada:

O programa verifica se a chave foi fornecida e se possui 26 caracteres alfabéticos exclusivos.

Se a chave for inválida, uma mensagem de erro é exibida.

Criptografia:

Cada letra do texto simples é substituída pela correspondente na chave.

Maiúsculas e minúsculas são mantidas.

Caracteres não alfabéticos não são alterados.

Saída:

O texto cifrado é exibido após a criptografia.

📊 Casos de Teste

$ ./substitution VCHPRZGJNTLSKFBDQWAXEUYMOI
tempo simples: hello, world
tempo cifrado: jrssb, ybwsp

$ ./substitution JTREKYAVOGDXPSNCUIZLFBMWHQ
tempo simples: CS50!
tempo cifrado: FU50!

🛠️ Ferramentas de Avaliação

check50: Avalia a exatidão do código.

check50 cs50/problems/2024/x/substitution

style50: Avalia o estilo do código.

style50 substitution.c

🌟 Conceitos Praticados

Manipulação de Strings: Substituição de caracteres com base em uma chave.

Validação de Entrada: Confirma se a chave fornecida é válida.

Uso de Arrays: Para mapeamento de substituição de caracteres.

Interação com o Usuário: Entrada e saída formatadas.

📜 Licença
Este projeto está licenciado sob a MIT License.

