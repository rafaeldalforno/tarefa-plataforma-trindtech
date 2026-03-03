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
| **2-** Clicar em 'Meu Perfil'                      |
| **3-** Preencher campo 'Nome' com um nome válido |
| **4-** Preencher campo 'Sobrenome' com um sobrenome válido |
| **5-** Preencher campo 'Nacionalidade' com um nacionalidade válida |
| **6-** Preencher campo 'CPF' com um número de CPF válido |
| **7-** Preencher campo 'Cor/Raça' com um cor/raça válida |
| **8-** Preencher campo 'Cor/Raça' com um cor/raça válida |
| **9-** Preencher campo 'Gênero' com um gênero válido |
| **10-** Preencher campo 'Pessoa com deficiência' com uma informação válida |
| **11-** Preencher campo 'DDI' com um número válido |
| **12-** Preencher campo 'Celular/Whatsapp' com um número válido |
| **13-** Preencher demais campos obrigatórios com informações válidas |
| **14-** Clicar no botão 'Salvar'     |

| **Resultados Esperados**                                        |
| ----------------------------------------------------------------- |
| Exibir mensagem 'Dados salvos com sucesso' e redirecionar para a aba 'Profissional'    |

---

### Caso de Teste 02: Tentativa de atualizar perfil com um número de CPF inválido.

| ID       | Descrição                                                          |
| -------- | ------------------------------------------------------------------ |
| RF01-CT02 | Atualização do perfil do usuário com o dado de CPF inválido |

| **Pré-condições**                                                 |
| ----------------------------------------------------------------- |
| Usuário autenticado no sistema   |

| **Passos**                                                        |
| ----------------------------------------------------------------- |
| **1-** Acessar a plataforma trindtech              |
| **2-** Clicar em 'Meu Perfil'                      |
| **3-** Preencher campo 'CPF' com um número inválido |
| **4-** Clicar no botão 'Salvar' |

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
| Usuário autenticado no sistema   |

| **Passos**                                                        |
| ----------------------------------------------------------------- |
| **1-** Acessar a plataforma trindtech              |
| **2-** Clicar em 'Meu Perfil'                      |
| **3-** Preencher campos obrigatórios com dados válidos |
| **5-** Na sessão 'Contato' deixar os campos totalmente vazios |
| **5-** Clicar no botão 'Salvar' |

| **Resultados Esperados**                                         |
| ----------------------------------------------------------------- |
| O sistema deve exibir mensagem de erro 'Campo obrigatório deve ser preenchido', 
  O sistema deve exibir mensagem de erro abaixo do campo DDI 'Este campo é obrigatório' e
  O sistema deve exibir mensagem de erro abaixo do campo Celular/Whatsapp 'Este campo é obrigatório'   |

---

### Caso de Teste 04: Atualizar a aba profissional do perfil com dados válidos.

---

### Caso de Teste 05: Tentativa de atualizar aba profissional do perfil, com dados inválidos.

---

### Caso de Teste 06: Tentativa de atualizar aba profissional do perfil, com os campos obrigatórios vazios.

---

### Caso de Teste 07: Atualizar a aba habilidades do perfil com dados válidos.

---

### Caso de Teste 08: Tentativa de atualizar aba habilidades do perfil, com dados inválidos.

---

### Caso de Teste 09: Tentativa de atualizar aba habilidades do perfil, com os campos obrigatórios vazios.