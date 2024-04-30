# Concorrente.2

- O programa vai utilizar uma thread para cada pessoa que deseja utilizar o caixa eletrônico
- O mutex vai ser utilizado para garantir o acesso seguro à recursos compartilhados, como variáveis globais (no caso do programa, a variável caixa livre)
- A variável condicional utilizada serve para fazer com que a pessoa espere na fila caso o caixa esteja sendo usado, e sinalizar quando o caixa estiver desocupado, permitindo o uso da pessoa/thread seguinte.
