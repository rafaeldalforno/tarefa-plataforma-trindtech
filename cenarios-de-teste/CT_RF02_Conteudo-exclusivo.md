## Requisito Funcional 02: Conteúdos Exclusivos.

### Caso de Teste 01: Exibir Cursos em andamento corretamente. 

| ID       | Descrição                                                          |
| :------- | :----------------------------------------------------------------- |
| RF02-CT01 | Verificar se os cursos em andamento são exibidos corretamente para o usuário. | 

| **Pré-condições**                                             |
| :------------------------------------------------------------ |
| O usuário deve estar autenticado com uma conta válida.     |

| **Passos**                                                                          |
| :---------------------------------------------------------------------------------- |
| **DADO** que estou logado na plataforma     |
| **E** estou na aba 'Conteúdos Exclusivos'   |
| **QUANDO** a página é carregada             |
| **ENTÃO** devo visualizar a seção 'Continuar assistindo'  |
| **E** devo visualizar os cursos em andamento, situação 'inscrito' e progresso exibidos corretamente  |

| **Resultados Esperados**                                         |
| :---------------------------------------------------------------- |
| O sistema deve exibir corretamente os cursos em andamento, a situação como 'inscrito', a barra de progresso do curso e o número de aulas já concluídas. |

---

### Caso de Teste 02: Exibir Cursos recomendados corretamente.

---

### Caso de Teste 03: Exibir Cursos concluídos corretamente.

---

### Caso de Teste 04: Acessar um curso específico em andamento.

| ID       | Descrição                                                          |
| :------- | :----------------------------------------------------------------- |
| RF02-CT04 | Acessar um curso em andamento | 

| **Pré-condições**                                             |
| :------------------------------------------------------------ |
| O usuário deve estar autenticado com uma conta válida e inscrito em um curso na seção 'Conteúdos exclusivos'.     |

| **Passos**                                                                          |
| :---------------------------------------------------------------------------------- |
| **DADO** que estou na seção 'Continuar Assistindo'     |
| **QUANDO** clico em um curso em andamento             |
| **ENTÃO** devo ser redirecionado para a página de detalhes do curso selecionado  |

| **Resultados Esperados**                                         |
| :---------------------------------------------------------------- |
| O sistema deve redirecionar o usuário para a página de descrição do curso selecionado, exibindo informações do curso e botão 'Iniciar Curso' para acessar a próxima aula. |

---

### Caso de Teste 05: Acessar um curso em que o usuário ainda não está inscrito.

---

### Caso de Teste 06: Acessar um curso já concluído.

| ID       | Descrição                                                          |
| :------- | :----------------------------------------------------------------- |
| RF02-CT06 | Acessar um curso já concluído e finalizado | 

| **Pré-condições**                                             |
| :------------------------------------------------------------ |
| O usuário deve estar autenticado com uma conta válida e já ter concluído um curso específico'.     |

| **Passos**                                                                          |
| :---------------------------------------------------------------------------------- |
| **DADO** que estou na seção 'Cursos Concluídos'     |
| **QUANDO** clico em um curso concluído             |
| **ENTÃO** devo ser redirecionado para a página de detalhes do curso selecionado  |
| **E** devo ter acesso às aulas e ao certificado do curso |

| **Resultados Esperados**                                         |
| :---------------------------------------------------------------- |
| O sistema deve redirecionar o usuário para a página de descrição do curso selecionado, exibindo informações do curso e botão 'Visualizar Curso' para acessar novamente as aulas. E também um botão 'Meu certificado' para baixar o certificado. |

---