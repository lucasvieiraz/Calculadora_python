## Calculadora com Kivy

Este projeto é uma calculadora simples construída usando o framework Kivy para Python. A calculadora oferece operações matemáticas básicas, como adição, subtração, multiplicação e divisão.

## Funcionalidades

Suporte a operações básicas: adição (+), subtração (-), multiplicação (*), e divisão (/).

Limpeza da tela com o botão C.

Exibição e cálculo do resultado ao pressionar =.

Validação para impedir a inserção de operadores consecutivos ou como primeiro caractere.

## Tecnologias Utilizadas
Python: Linguagem de programação principal.

Kivy: Framework para o desenvolvimento de aplicativos GUI (Interface Gráfica de Usuário).

## Como Executar
Pré-requisitos: Certifique-se de ter o Kivy instalado. Você pode instalar o Kivy usando pip:

bash
Copiar código
pip install kivy
Clone este repositório para o seu computador:

bash
Copiar código
git clone https://github.com/seuusuario/calculadora-kivy.git
Navegue até a pasta do projeto e execute o arquivo Python:

bash
Copiar código
python main.py
Estrutura do Projeto
main.py: Contém a lógica da interface da calculadora e o tratamento de eventos de botão.
Utiliza o BoxLayout para organizar os botões e a área de exibição.
Cada botão está vinculado a uma função que processa a entrada e executa as operações matemáticas.
Lógica de Funcionamento
Adição de Botões: Os botões são adicionados dinamicamente por meio de laços, organizados em um layout vertical.
Entrada de Dados: O valor da entrada é atualizado conforme o usuário pressiona os botões numéricos ou operadores.
Validação: A calculadora impede que operadores sejam inseridos consecutivamente ou que o primeiro caractere seja um operador.
Resultado: O botão = avalia a expressão atual usando a função eval() de Python e exibe o resultado. Se ocorrer um erro durante a avaliação, a calculadora exibe a mensagem Error.
Melhorias Futuras
Implementar mais operações matemáticas, como porcentagem ou raiz quadrada.
Adicionar suporte a teclas do teclado.
Melhorar o layout e o design da interface.
Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir uma issue ou pull request com melhorias, sugestões ou correções.

Este README detalha o propósito do projeto, suas funcionalidades e como usá-lo.







Você chegou ao limite do plano Free para o GPT-4o.
As respostas serão fornecidas por outro modelo até o seu limite se
