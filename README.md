# EstruturaDeDadosI
Exercicios propostos nas primeiras aulas com intenção de relembrar e analisar o que ja foi aprendido em outros semestres. 
Segue a descrição da primeira lista de exercicios: 

**Questão 1.**– Escreva um programa que processe um ranking de notas. Utilize o seguinte vetor prédefinido:
float notas[] = {7.5, 4.0, 9.2, 5.5, 8.0, 6.5, 3.2, 10.0, 7.0, 5.8}; (em C) ou
double[] notas = {7.5, 4.0, 9.2, 5.5, 8.0, 6.5, 3.2, 10.0, 7.0, 5.8}; (em Java).
O seu programa deve:
• Calcular e exibir a média aritmética de todas as notas.
• Contar e exibir quantos alunos ficaram com nota acima da média calculada.
• Encontrar e exibir a maior nota da lista sem utilizar funções prontas de ordenação.

**Resumo da logica:**
Percorre o vetor uma vez:
Soma todas as notas
Descobre a maior nota
Calcula a média
Percorre novamente:
Conta quantas notas são maiores que a média
Exibe tudo


**Questão 2.**– Implemente um simulador de caixa eletrônico que ajude a entregar o menor número
possível de cédulas. O programa deve ler um valor inteiro (múltiplo de 10) e calcular a quantidade de
notas de R$ 50, R$ 20 e R$ 10 necessárias.
Exemplo: Para R$ 180, o programa deve retornar 3 notas de R$ 50, 1 nota de R$ 20 e 1 nota de R$
10. Utilize os operadores de divisão (/) e resto (%) para resolver o problema.

**Resumo da logica:**
Dividir o valor pela maior nota (50).
Usar o resto para calcular a próxima (20).
Usar o resto novamente para calcular 10.
Sempre começar pela maior nota disponível.


**Questão 3.**– Crie um validador de senha segura. O programa deve ler uma string (cadeia de caracteres)
digitada pelo usuário e verificar se ela atende aos seguintes critérios de segurança:
• A senha deve possuir pelo menos 8 caracteres.
• A senha deve conter pelo menos um caractere especial (ex: @, #, $, %, & ou *).
Ao final, o programa deve imprimir se a senha é “Válida” ou “Inválida”. Caso seja inválida, o programa
deve informar qual critério não foi atendido.
Dica para C: Lembre-se de percorrer o array de caracteres até encontrar o terminador nulo ’\0’.

**Resumo da logica:**
Verificar o tamanho da senha.
Se length >= 8 → OK.
Percorrer cada caractere da string.
Checar se existe pelo menos um caractere especial.
Se ambos forem verdadeiros → senha válida.
Caso contrário → informar o que faltou.

**Todos exercicios foram feitos na linguagem java com a estrutura baseada em Orientação a objetos aprendido durante o ultimo semestre...**
