## Requisito Funcional 03: Cadastro de Novo Usuário.

### Caso de Teste 01: Marcar opção possuir deficiência no campo 'Pessoa com Deficiência'.

| ID       | Descrição                                                          |
| -------- | ------------------------------------------------------------------ |
| RF03-CT01 | Selecionar a opção 'Sim, possuo alguma deficiência' e selecionar 'Outra' no campo adicional |

| **Pré-condições**                                                 |
| ----------------------------------------------------------------- |
| Acessar a página de cadastro da plataforma da Trindtech |

| **Passos**                                                        |
| ----------------------------------------------------------------- |
| **1-** Acessar página de cadastro da plataforma trindtech  |
|        acessa página de cadastro 
| **2-** Selecionar 'Sim, possuo alguma deficiência' |
|        campo adicional é exibido com a pergunta 'Qual sua deficiência?' |
| **3-** Selecionar 'Outra' no campo Qual sua deficiência |
|        campo adicional é exibido 'Descreva sua deficiência' | 
| **4-** Preencher o campo descreva sua deficiência |
|        preencher com dado: xxxxx | 

| **Resultados Esperados**                                        |
| ----------------------------------------------------------------- |
| Exibir campos adicionais de cadastro em caso de respostas como 'Sim, possuo alguma deficiência' e 'Outra' consequentemente    |

---

### Caso de Teste 02: Selecionar 'Brasil' no campo país.

| ID        | Descrição                                                          |
| --------- | ------------------------------------------------------------------ |
| RF03-CT02 | Selecionar a opção 'Brasil' e verificar se a lista de estados é carregada no campo estados |

| **Pré-condições**                                                 |
| ----------------------------------------------------------------- |
| Acessar a página de cadastro da plataforma da Trindtech e preencher os campos anteriores|

| **Passos**                                                        |
| ----------------------------------------------------------------- |
| **1-** Acessar página de cadastro da plataforma trindtech  |
|        acessa página de cadastro 
| **2-** Selecionar 'Brasil' no campo País |
|        lista de estados brasileiros é carregada no campo Estado |
| **3-** Selecionar 'Rio Grande do Sul' |
|        lista de cidades do RS é carregada no campo Cidade | 
| **4-** Selecionar Alegrete |
|        seleciona a cidade | 

| **Resultados Esperados**                                        |
| ----------------------------------------------------------------- |
| Carregar as listas de estados brasileiros quando o país é selecionado 'Brasil, e carregar lista de Cidades referente ao estado escolhido no campo Estado.    |

---

### Caso de Teste 03: Selecionar 'Indicação' no campo Como ficou sabendo da gente?.

| ID        | Descrição                                                          |
| --------- | ------------------------------------------------------------------ |
| RF03-CT03 | Selecionar a opção 'indicação' e verificar se o campo 'Quem fez a indicação', foi adicionado para ser respondido |

---

### Caso de Teste 04: Selecionar Graduação em 'Escolaridade'.

| ID        | Descrição                                                          |
| --------- | ------------------------------------------------------------------ |
| RF03-CT04 | Selecionar a opção 'Graduação' e verificar se o campo 'Nome do curso de Formação', foi adicionado para ser respondido |

---

### Caso de Teste 05: Preencher 'rafa.com' com ausência do @.

| ID        | Descrição                                                          |
| --------- | ------------------------------------------------------------------ |
| RF03-CT05 | Preencher campo E-mail com o dado 'rafa.com' sem uso do @ e verificar se a mensagem de erro é exibida|

---

### Caso de Teste 06: Preencher senha inválida 'Senha@1' (7 caracteres).

| ID        | Descrição                                                          |
| --------- | ------------------------------------------------------------------ |
| RF03-CT06 | Preencher Senha com o dado 'Senha@1' e verificar se a mensagem de erro é exibida|

| **Pré-condições**                                                 |
| ----------------------------------------------------------------- |
| Acessar a página de cadastro da plataforma da Trindtech e preencher os campos anteriores |

| **Passos**                                                        |
| ----------------------------------------------------------------- |
| **1-** Acessar página de cadastro da plataforma trindtech  |
|        carrega página de cadastro 
| **2-** Preencher Senha 'Senha@1' |
|        mensagem de erro deve ser exibida |

| **Resultados Esperados**                                        |
| ----------------------------------------------------------------- |
| Exibir mensagem de erro pois a senha deve ter no mínimo 8 caracteres   |

---

### Caso de Teste 07: Preencher senha inválida 'senha@12'.

---

### Caso de Teste 08: Preencher senha inválida 'SENHA@12'.

---

### Caso de Teste 09: Preencher senha inválida 'Senha123'.

---

### Caso de Teste 10: Preencher senha válida.

| ID        | Descrição                                                          |
| --------- | ------------------------------------------------------------------ |
| RF03-CT10 | Preencher Senha com o dado 'Senha@12'|

| **Pré-condições**                                                 |
| ----------------------------------------------------------------- |
| Acessar a página de cadastro da plataforma da Trindtech e preencher os campos anteriores |

| **Passos**                                                        |
| ----------------------------------------------------------------- |
| **1-** Acessar página de cadastro da plataforma trindtech  |
|        carrega página de cadastro 
| **2-** Preencher Senha 'Senha@12' |
|        senha validada |
| **3-** Preencher Repetir Senha 'Senha@12' |
|        senhas compatíveis |

| **Resultados Esperados**                                        |
| ----------------------------------------------------------------- |
| As senhas digitadas são validadas conforme a regra de negócio e compatíveis entre si.   |