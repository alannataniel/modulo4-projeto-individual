# modulo4-projeto-individual

Existem outras entidades além dessas três?<br>
Sim. Professores, Disciplinas, Notas, Matrículas.

Quais são os principais campos e tipos?<br>
Professores: nome, área de atuação, e-mail<br>
Disciplinas: nome, descrição, carga horária<br>
Notas: nota na avaliação, data da avaliação<br>
Matrículas: data da matrícula, forma de pagamento<br>

Como essas entidades estão relacionadas?<br>
Professores: Essa entidade poderia ter um relacionamento com a entidade "turmas" (por exemplo, um professor pode ministrar várias turmas).<br>
Disciplinas: Essa entidade poderia ter um relacionamento com a entidade "turmas" (por exemplo, uma turma pode ter várias disciplinas).<br>
Notas: Essa entidade poderia ter um relacionamento com a entidade "alunos" e "disciplinas" (por exemplo, um aluno pode ter várias notas em várias disciplinas).<br>
Matrículas: Essa entidade poderia ter um relacionamento com a entidade "alunos" e "turmas" (por exemplo, um aluno pode se matricular em várias turmas).
