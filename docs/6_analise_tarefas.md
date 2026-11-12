
# 1. HTA — Hierarchical Task Analysis

### HTA — Realizar cadastro e acessar o sistema

Funcionalidade: permitir que o usuário realize seu cadastro, acesse o sistema por meio do login e seja direcionado à área correspondente ao seu perfil (Paciente, Doutor ou Diretor).

<img width="3688" height="698" alt="mermaid-diagram (1)" src="https://github.com/user-attachments/assets/e1c91c22-345d-40aa-8a08-97366206307e" />

Explicação dos planos:

- Plano 0 (`1>2>3`): o usuário realiza o cadastro, depois efetua o login e finalmente acessa a área correspondente ao seu perfil.
- Plano 1 (`1>2`): primeiro informa seus dados pessoais e depois finaliza o cadastro.
- Plano 2 (`1>2`): informa suas credenciais e confirma o login.
- Plano 3 (`1/2/3`): o sistema direciona o usuário para uma das três áreas, de acordo com seu perfil: Paciente, Doutor ou Diretor.

# 2. GOMS — Goals, Operators, Methods, Selection Rules

### GOMS 1 — Solicitar ajuda pelo S.O.S

Funcionalidade: permitir que o paciente solicite ajuda por meio da função S.O.S. do aplicativo, enviando um alerta para que o responsável pelo atendimento possa recebê-lo.

```
GOAL 0: solicitar ajuda pelo S.O.S

  GOAL 1: acessar a função S.O.S
    METHOD 1.A: acessar pelo perfil de paciente
      OP. 1.A.1: realizar login no sistema
      OP. 1.A.2: acessar a área do paciente
      OP. 1.A.3: localizar a opção S.O.S
      OP. 1.A.4: selecionar a opção S.O.S

  GOAL 2: enviar solicitação de ajuda
    METHOD 2.A: acionar o botão S.O.S
      OP. 2.A.1: tocar no botão S.O.S
      OP. 2.A.2: aguardar o envio do alerta
      OP. 2.A.3: verificar a confirmação do envio

  GOAL 3: receber atendimento
    METHOD 3.A: aguardar o recebimento da solicitação
      OP. 3.A.1: aguardar o recebimento do alerta pelo responsável
```

Explicação: Quando paciente utiliza a função S.O.S: para solicitar ajuda. Após acessar sua conta, o paciente seleciona a opção de emergência e aciona o botão para enviar um alerta, que será recebido pelo responsável pelo atendimento.

### GOMS 2 — Criar exercícios pelo perfil de doutor

Funcionalidade: permitir que o doutor crie exercícios destinados aos pacientes, disponibilizando atividades físicas que poderão ser consultadas posteriormente.

```
GOAL 0: criar exercícios para os pacientes

  GOAL 1: acessar a área do doutor
    METHOD 1.A: entrar pelo login
      OP. 1.A.1: informar as credenciais de acesso
      OP. 1.A.2: confirmar o login
      OP. 1.A.3: acessar o perfil de doutor

  GOAL 2: acessar a função de criação
    METHOD 2.A: utilizar a opção de criação de exercícios
      OP. 2.A.1: localizar a opção de criação
      OP. 2.A.2: selecionar a opção de criação

  GOAL 3: criar e disponibilizar exercícios
    METHOD 3.A: cadastrar um exercício
      OP. 3.A.1: inserir as informações do exercício
      OP. 3.A.2: revisar as informações preenchidas
      OP. 3.A.3: confirmar a criação do exercício
      OP. 3.A.4: verificar a disponibilização do exercício
```

Explicação: Criação de exercícios pelo doutor. Após realizar o login e acessar seu perfil, o profissional utiliza a função de criação para cadastrar novas atividades, que posteriormente poderão ser disponibilizadas para os pacientes.

### GOMS 3 — Monitorar pacientes pelo perfil de diretor

Funcionalidade: permitir que o diretor acompanhe os pacientes cadastrados no sistema, utilizando a área de monitoramento para consultar suas informações.

```
GOAL 0: monitorar pacientes cadastrados

  GOAL 1: acessar a área do diretor
    METHOD 1.A: entrar pelo login
      OP. 1.A.1: informar as credenciais de acesso
      OP. 1.A.2: confirmar o login
      OP. 1.A.3: acessar o perfil de diretor

  GOAL 2: acessar a função de monitoramento
    METHOD 2.A: utilizar a opção de monitoramento
      OP. 2.A.1: localizar a opção "Monitorar"
      OP. 2.A.2: selecionar a opção "Monitorar"

  GOAL 3: acompanhar os pacientes
    METHOD 3.A: consultar pacientes cadastrados
      OP. 3.A.1: visualizar os pacientes disponíveis
      OP. 3.A.2: selecionar um paciente
      OP. 3.A.3: consultar as informações apresentadas
```

Explicação: Processo de monitoramento realizado pelo diretor. Após acessar sua conta, o diretor entra na área de monitoramento, visualiza os pacientes cadastrados e consulta suas informações.

### GOMS 4 — Consultar exercícios pelo perfil de paciente

Funcionalidade: permitir que o paciente acesse a área de exercícios e visualize as atividades disponibilizadas pelo doutor.

```
GOAL 0: consultar exercícios disponíveis

  GOAL 1: acessar a área de exercícios
    METHOD 1.A: entrar pelo perfil de paciente
      OP. 1.A.1: informar as credenciais de acesso
      OP. 1.A.2: confirmar o login
      OP. 1.A.3: acessar o perfil de paciente

  GOAL 2: visualizar exercícios
    METHOD 2.A: acessar a opção de exercícios
      OP. 2.A.1: localizar a opção "Exercícios"
      OP. 2.A.2: selecionar a opção "Exercícios"
      OP. 2.A.3: visualizar os exercícios disponíveis
      OP. 2.A.4: selecionar um exercício
      OP. 2.A.5: consultar as informações do exercício
```

Explicação: O processo pelo qual o paciente consulta os exercícios disponíveis no aplicativo. O usuário acessa seu perfil, entra na área de exercícios e visualiza as atividades que foram disponibilizadas pelo doutor.
