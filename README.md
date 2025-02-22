Gerenciamento de Turmas e Alunos em C

//Este é um programa em linguagem C que simula um sistema básico de gerenciamento de turmas e alunos em uma escola. Ele permite cadastrar alunos em turmas, lançar notas, calcular a média de uma turma e gerar relatórios detalhados. O código utiliza structs para organizar os dados de alunos e turmas, oferecendo uma interface simples baseada em menu no terminal.

//Funcionalidades
Cadastrar Aluno na Turma: Adiciona um aluno pré-cadastrado a uma turma específica (máximo de 30 alunos por turma).
Lançar Notas: Permite atualizar as notas (duas disciplinas) de um aluno específico.
Calcular Média da Turma: Calcula a média das notas dos alunos de uma turma escolhida.
Relatório da Turma: Exibe um relatório com nome, matrícula e notas de todos os alunos de uma turma.
Encerrar: Finaliza a execução do programa.

//Estrutura do Código
struct Aluno: Contém nome (string), matrícula (inteiro) e notas (array de 2 floats).
struct Turma: Contém número da turma, array de até 30 alunos e contador de alunos cadastrados.

//Base de Dados:
5 alunos pré-cadastrados com nome, matrícula e notas iniciais.
Até 10 turmas disponíveis, com 2 inicializadas (5000 e 6000).
Menu Interativo: Interface baseada em switch-case com opções numeradas.
Como Compilar e Executar
Requisitos: Compilador C (ex.: GCC).

//Compilação:
text
Wrap
Copy
gcc main.c -o programa

//Execução:
Windows: programa.exe
Linux/Mac: ./programa

//Uso: Escolha uma opção de 1 a 5 no menu e insira os dados solicitados (índices de alunos: 0-4; turmas: 0-9).

Exemplo de Uso
text
Wrap
Copy
 1 - cadastrar aluno na turma
 2 - lançar notas de aluno
 3 - media da turma
 4 - relatorio de turma
 5 - encerrar
 
 Opcao: 1
 Escolha o aluno: 0
 Escolha a turma: 0

Isso cadastra o aluno "João" na turma 5000.

//Limitações
Não há validação completa de entrada (ex.: índices inválidos podem causar erros).
Suporta apenas 5 alunos pré-cadastrados e 10 turmas.
Interface limitada ao terminal.
Melhorias Possíveis
Adicionar validação robusta de entradas.
Implementar cadastro dinâmico de novos alunos.
Salvar dados em arquivo para persistência.

Autor
GG_dev
