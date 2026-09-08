# Projeto de Experiência do Usuário

Projeto apresentado ao Centro Universitário [FEI](https://portal.fei.edu.br/), como parte dos requisitos necessários para aprovação na disciplina de Experiência do Usuário (CCP310) do curso de Ciencia da Computação, orientado pelo Prof. Dr. [Fagner de Assis Moura Pimentel](http://lattes.cnpq.br/6747210702910392).

Este projeto é desenvolvido pelos seguintes alunos:

- Natan Guimarães dos Santos
- Nome Componente 2
- Nome Componente 3

## Conhecendo o problema

**1. Breve descrição**
Trata-se de um aplicativo móvel voltado especificamente para o público da terceira idade, projetado para orientar, monitorar e incentivar a prática de atividades físicas de forma segura. A plataforma oferece rotinas de exercícios de baixo impacto, adaptadas às limitações comuns da idade, com foco em usabilidade e acessibilidade.

**2. Objetivo**
Promover a saúde, a autonomia e a qualidade de vida da população idosa, combatendo o sedentarismo e auxiliando na prevenção de lesões e doenças crônicas através da prática diária e guiada de exercícios físicos.

**3. Usuário final**
O público-alvo principal são idosos (pessoas com 60 anos ou mais) que desejam manter ou iniciar uma rotina de exercícios em casa ou ao ar livre. O público secundário abrange familiares, cuidadores e profissionais de saúde (fisioterapeutas e geriatras) que podem utilizar o aplicativo para acompanhar o progresso do idoso.

**4. Principais benefícios para os usuários**

* **Melhora da saúde física e mental:** Aumento da mobilidade, fortalecimento muscular, melhora do equilíbrio (prevenindo quedas) e redução do estresse.
* **Inclusão digital e autonomia:** Uma interface pensada para quem não tem familiaridade com tecnologia permite que o idoso gerencie sua própria rotina de saúde sem depender de terceiros.
* **Segurança:** Exercícios validados para a faixa etária e recursos de emergência integrados trazem tranquilidade ao usuário e à sua família.
* **Motivação:** O acompanhamento visual do progresso ajuda a manter o engajamento a longo prazo.

**5. Funcionalidades**

* **Catálogo de treinos adaptados:** Aulas em vídeo com instruções em áudio claro, legendas grandes e demonstrações de exercícios de baixo impacto (ex: alongamentos, exercícios na cadeira).
* **Monitoramento de progresso:** Contagem de passos diários, tempo de atividade e calendário de frequência.
* **Sistema de lembretes e alertas:** Notificações amigáveis para a hora do treino, alongamentos curtos e lembretes de hidratação.
* **Botão de SOS (Emergência):** Atalho de fácil acesso na tela principal para alertar um contato de confiança caso o usuário se sinta mal ou sofra uma queda.
* **Relatórios compartilháveis:** Geração de um resumo de atividades simplificado que pode ser enviado diretamente para o médico ou fisioterapeuta pelo WhatsApp.
* **Interface Acessível:** Alto contraste de cores, fontes grandes, ícones intuitivos e navegação simplificada.

**6. Tecnologias e ferramentas computacionais utilizadas**

* **Design e Prototipação:** Figma (focado em acessibilidade e UI/UX para a terceira idade).
* **Desenvolvimento Mobile (Front-end):** Flutter ou React Native (para garantir funcionamento fluido tanto em Android quanto em iOS com um único código).
* **Back-end e Banco de Dados:** Firebase ou Node.js com MongoDB (para autenticação simples, armazenamento seguro do histórico de saúde e uso de banco de dados em tempo real).
* **Integração de Hardware:** Uso da API de sensores nativos do smartphone (acelerômetro, giroscópio e pedômetro) para contagem de passos e possível detecção de quedas.

**7. Contexto de uso**
O aplicativo será utilizado predominantemente no ambiente doméstico (na sala de estar, quarto ou quintal) ou em espaços públicos seguros, como parques durante caminhadas leves. O uso previsto é diário, em sessões curtas de 15 a 30 minutos. O idoso precisará de um smartphone, roupas confortáveis e, eventualmente, objetos comuns da casa (como uma cadeira ou cabo de vassoura) para auxiliar na execução dos movimentos, sem a necessidade de equipamentos de academia complexos.

## Desenvolvimento

### Descoberta
- [Análise de Concorrência](docs/1_concorrencia.md)
- [Pesquisa e Coleta de Dados com Usuários](docs/2_pesquisa_usuarios.md)
- [Perfil do Usuário](docs/3_perfil_usuario.md)
- [Personas](docs/4_personas.md)
- [Cenário de Análise/Problema](docs/5_cenarios.md)

### Definição
- [Análise de Tarefas](docs/6_analise_tarefas.md)
- [Requisitos de UX e Metas de Usabilidade](docs/7_requisitos_ux.md)
- [Arquitetura de Informação e Fluxo do Usuário](docs/8_arquitetura_fluxo.md)

### Prototipação
- [Prototipação em Papel](docs/9_prototipacao_papel.md)
- [Prototipação de Alta Fidelidade (FIGMA)](docs/10_prototipacao_figma.md)

### Avaliação
- [Planejamento da Avaliação](docs/11_planejamento_avaliacao.md)
- [Avaliação de Usabilidade através de Inspeção Heurística](docs/12_heuristica.md)
- [Teste de Usabilidade com Observação do Usuário](docs/13_teste_usabilidade.md)
