# modulo4-projeto-individual

Existem outras entidades além dessas três?
Sim. Professores, Disciplinas, Notas, Matrículas.

Quais são os principais campos e tipos?
Professores: nome, área de atuação, e-mail
Disciplinas: nome, descrição, carga horária
Notas: nota na avaliação, data da avaliação
Matrículas: data da matrícula, forma de pagamento

Como essas entidades estão relacionadas?
Professores: Essa entidade poderia ter um relacionamento com a entidade "turmas" (por exemplo, um professor pode ministrar várias turmas).
Disciplinas: Essa entidade poderia ter um relacionamento com a entidade "turmas" (por exemplo, uma turma pode ter várias disciplinas).
Notas: Essa entidade poderia ter um relacionamento com a entidade "alunos" e "disciplinas" (por exemplo, um aluno pode ter várias notas em várias disciplinas).
Matrículas: Essa entidade poderia ter um relacionamento com a entidade "alunos" e "turmas" (por exemplo, um aluno pode se matricular em várias turmas).
