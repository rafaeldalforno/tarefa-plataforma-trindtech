# Relatório de Bugs

### 🐞 **Bug 01: Sistema atualiza o perfil mesmo preenchendo com um dado de CPF inválido**

| **ID**     | **Descrição**                                                                                                                                             |
| ---------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BUG-001    | O sistema atualiza o perfil mesmo o usuário preenchendo um dado inválido no campo CPF |

| **Severidade do Bug** | **Prioridade de Correção** | **Status** |
| :-------------------: | :------------------------: | :--------: |
|         Alta          |            Alta            |   Aberto   |

| **Passo a passo para simular o bug**                           |
| -------------------------------------------------------------- |
| **1-** Acessar a plataforma trindtech              |
| **2-** Clicar em 'Meu Perfil'                      |
| **3-** Preencher campo 'CPF' com um número inválido |
| **4-** Clicar no botão 'Salvar' |

|                        **Comportamento Esperado**                       |                        **Comportamento Obtido**                        |
| :---------------------------------------------------------------------: | :--------------------------------------------------------------------: |
| O sistema deve exibir mensagem de erro 'Campo obrigatório deve ser preenchido' e
  O sistema deve exibir mensagem de erro abaixo do campo CPF 'CPF inválido' | A mensagem de erro não é apresentada quando o usuário clica no botão salvar, e é redirecionado para a próxima aba 'Profissional' |

| **Ambiente**              |
| ------------------------  |
| Ambiente de homologação.  |
| Desktop com Windows 11.   |
|  Google Chrome v.145.0.76 |

| **Funcionalidade Afetada** |        **Caso de Teste Relacionado**       |
| :------------------------: | :----------------------------------------: |
| Atualização de Perfil      | RF01-CT02: Atualização do perfil do usuário com o número de CPF inválido |

|                **Evidência(s)**               |
| :-------------------------------------------: |
| Adicionar Evidência aqui |

---