## Requisito Funcional 01: Atualização de Perfil.

### Caso de Teste 01: Atualização do Perfil do usuário com dados atualizados e válidos.

| ID       | Descrição                                                          |
| -------- | ------------------------------------------------------------------ |
| RF01-CT01 | A atualização será realizada com dados válidos do usuário |

| **Pré-condições**                                                 |
| ----------------------------------------------------------------- |
| Usuário autenticado no sistema |

| **Passos**                                                        |
| ----------------------------------------------------------------- |
| **1-** Acessar a plataforma trindtech              |
|        carrega a página inicial        |
| **2-** Clicar em 'Meu Perfil' |
|        carrega a página do perfil na aba 'Pessoal' |
| **3-** Preencher todos os campos obrigatórios do perfil |
|        responde todos os campos obrigatórios |
| **4-** Clicar no botão 'Salvar'     |
|        dados pessoais são atualizados e a página redireciona para a aba profissional     |

| **Resultados Esperados**                                        |
| ----------------------------------------------------------------- |
| Exibir mensagem 'Dados salvos com sucesso' e redirecionar para a aba 'Profissional'    |

---

### Caso de Teste 02: Tentativa de atualizar perfil com um número de CPF inválido.

| ID       | Descrição                                                          |
| -------- | ------------------------------------------------------------------ |
| RF01-CT02 | Atualização do perfil do usuário com o dado de CPF = '00011122233' |

| **Pré-condições**                                                 |
| ----------------------------------------------------------------- |
| Usuário autenticado no sistema e acessar 'Meu perfil' |

| **Passos**                                                        |
| ----------------------------------------------------------------- |
| **1-** Preencher campo 'CPF' com o número 00011122233 |
|        número de CPF é digitado       |
| **2-** Clicar no botão 'Salvar' |
|        mensagem de erro é apresentada no topo do formulário e abaixo do campo CPF      |

| **Resultados Esperados**                                         |
| ----------------------------------------------------------------- |
| O sistema deve exibir mensagem de erro 'Campo obrigatório deve ser preenchido' e
  O sistema deve exibir mensagem de erro abaixo do campo CPF 'CPF inválido'   |

---

### Caso de Teste 03: Tentativa de atualizar perfil com campos da sessão 'Contato' vazios.

| ID       | Descrição                                                          |
| -------- | ------------------------------------------------------------------ |
| RF01-CT03 | Atualização do perfil do usuário com campos da sessão 'Contato' vazios |

| **Pré-condições**                                                 |
| ----------------------------------------------------------------- |
| Usuário autenticado no sistema e acessar 'Meu perfil' |

| **Passos**                                                        |
| ----------------------------------------------------------------- |
| **1-** Preencher campos obrigatórios  |
|        formulário preenchido    |
| **2-** Na sessão 'Contato' deixar os campos totalmente vazios |
|        campos 'DDI' e 'Celular/Whatsapp' vazios     |
| **3-** Clicar no botão 'Salvar' |
|        mensagem de erro é apresentada no topo do formulário, abaixo dos campos DDI e Celular/Whatsapp     |


| **Resultados Esperados**                                         |
| ----------------------------------------------------------------- |
| O sistema deve exibir mensagem de erro 'Campo obrigatório deve ser preenchido', 
  O sistema deve exibir mensagem de erro abaixo do campo DDI 'Este campo é obrigatório' e
  O sistema deve exibir mensagem de erro abaixo do campo Celular/Whatsapp 'Este campo é obrigatório'   |

---

### Caso de Teste 04: Atualizar a aba profissional do perfil.

---

### Caso de Teste 05: Selecionar 'Ensino Médio' na escolaridade na aba Profissional, Verificar a NÃO exibição do campo 'Nome do Curso de formação'.

---

### Caso de Teste 06: Tentativa de atualizar aba profissional do perfil, com os campos obrigatórios vazios.

---

### Caso de Teste 07: Atualizar a aba habilidades do perfil.

---

### Caso de Teste 09: Tentativa de atualizar aba habilidades do perfil, com os campos obrigatórios vazios.