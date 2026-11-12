# Arquitetura de Informação e Fluxo do Usuário

> **_NOTE:_**: Esta entrega organiza como o conteúdo/funcionalidades estão estruturados e como o usuário se move entre eles, antes de partir para a prototipação.

1) **Arquitetura de Informação (Sitemap)**

Acesso: Login; cadastro de pessoa idosa.
Área da pessoa idosa: início; perfil e edição; agenda de exercícios; detalhes e conclusão de exercício; histórico de atividades; envio de alerta.
Área profissional: início; lista e perfil de pessoas idosas; equipe e cadastro de profissionais; turmas e gerenciamento de alunos; acervo de exercícios; prescrições individuais ou para turmas; alertas pendentes e resolução.
Gestão: Essa área é para o diretor, ele pode gerenciar tanto os alunos quanto doutores.

<img width="4012" height="3166" alt="mermaid-diagram (3)" src="https://github.com/user-attachments/assets/0491b06d-97a9-4414-9ebd-4ca0ec42cc2c" />

Pessoa idosa: precisa encontrar a agenda com facilidade, consultar o exercício, registrar que o concluiu e acessar o histórico. O envio de alerta fica na mesma área de uso, como um caminho direto para pedir ajuda.

Profissional: precisa acompanhar pessoas idosas, organizar alunos em turmas, selecionar exercícios e prescrevê-los. Por isso, pessoas, turmas e acervo ficam como seções de trabalho que levam à prescrição e, depois, à agenda dos destinatários.

Diretor/Gestão: administra as funções e permissões dos profissionais e alunos.

2) **Fluxo do Usuário (User Flow)**

<img width="957" height="522" alt="Captura de tela 2026-11-11 101631" src="https://github.com/user-attachments/assets/334e4cd2-2d85-4f1c-b368-88c980366286" />

