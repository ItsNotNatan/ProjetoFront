1) **Avaliação de IHC através de inspeção HEURÍSTICA \[1 solução completa por pessoa da equipe \- todas as telas do projeto\]**

> **_NOTE:_**: SOMENTE VIOLAÇÕES

Dez Heurísticas de Nielsen

**Descrição da avaliação**

Avaliação heurística, definida por Nielsen e Molich (1994), é um método de avaliação de usabilidade onde um avaliador procura problemas de usabilidade numa interface com o usuário através da análise e interpretação de um conjunto de princípios ou heurísticas. Este método de avaliação é baseado no julgamento do avaliador.

1\. Primeiramente, leia e analise as dez heurísticas (ver Tabela 1).

**Tabela 1 \- Conjunto de heurísticas de Nielsen (1994)**

| 1\. | Visibilidade do status do sistema: |
| :---- | :---- |
| O sistema deve sempre manter os usuários informados sobre o que está acontecendo através de feedback apropriado, em um tempo razoável. |  |
| **2\.** | **Compatibilidade entre sistema e mundo real:** |
| O sistema deve utilizar a linguagem do usuário, com palavras, frases e conceitos familiares para ele, ao invés de termos específicos de sistemas. Seguir convenções do mundo real, fazendo com que a informação apareça em uma ordem lógica e natural. |  |
| **3\.** | **Controle e liberdade para o usuário:** |
| Estão relacionados à situação em que os usuários frequentemente escolhem as funções do sistema por engano e então necessitam de "uma saída de emergência” claramente definida para sair do estado não desejado sem ter que percorrer um longo diálogo, ou seja, é necessário suporte a *undo* e *redo*. |  |
| **4\.** | **Consistência e padrões:** |
| Referem-se ao fato de que os usuários não deveriam ter acesso a diferentes situações, palavras ou ações representando a mesma coisa. A interface deve ter convenções não-ambíguas. |  |
| **5\.** | **Prevenção de erros:** |
| Os erros são as principais fontes de frustração, ineficiência e ineficácia durante a utilização do sistema. |  |
| **6\.** |  **Reconhecimento em lugar de lembrança:** |
| Tornar objetos, ações, opções visíveis e coerentes. O usuário não deve ter que lembrar informações de uma parte do diálogo para outra. Instruções para o uso do sistema devem estar visíveis ou facilmente acessíveis. |  |
| **7\.** | **Flexibilidade e eficiência de uso:** |
| A ineficiência nas tarefas pode reduzir a eficácia do usuário e causar-lhes frustração. O sistema deve ser adequado tanto para usuários inexperientes quanto para usuários experientes. |  |
| **8\.** | **Projeto minimalista e estético:** |
| Os diálogos não devem conter informações irrelevantes ou raramente necessárias. Cada unidade extra de informação em um diálogo compete com unidades relevantes e diminui sua visibilidade relativa. |  |
| **9\.** | **Auxiliar os usuários a reconhecer, diagnosticar e recuperar erros:** |
| Mensagens de erro devem ser expressas em linguagem natural (sem códigos), indicando precisamente o erro e sugerindo uma solução. |  |
| **10\.** | **Ajuda e documentação:** |
| Mesmo que seja melhor que o sistema possa ser usado sem documentação, pode ser necessário fornecer ajuda e documentação. Tais informações devem ser fáceis de encontrar, ser centradas na tarefa do usuário, listar passos concretos a serem seguidos e não ser muito grandes. A ajuda deve estar facilmente acessível e on-line. |  |

| Heurística | Problema identificado | Gravidade |
|---|---|:---:|
| 5 — Prevenção de erros | O cadastro permite informar idade sem estabelecer limites mínimos ou máximos. | 2 |
| 6 — Reconhecimento em lugar de lembrança | O campo de PIN não possui opção para visualizar os números digitados. | 1 |
| 6 — Reconhecimento em lugar de lembrança | Os campos de celular e PIN da tela de login não possuem instruções. | 1 |
| 1 — Visibilidade do status do sistema | Na tela principal do paciente, falhas ao carregar os dados são registradas apenas no console, sem informar o usuário. | 3 |
| 5 — Prevenção de erros | O botão SOS não apresenta uma confirmação visual de envio antes da solicitação, embora apresente confirmação antes de acioná-la. | 2 |
| 6 — Reconhecimento em lugar de lembrança | O menu de navegação apresenta a opção "Minha Conta", enquanto a página correspondente é identificada como "Perfil", criando uma diferença de nomenclatura. | 1 |

2\. A seguir, avalie o sistema procurando possíveis problemas de usabilidade.   
3\. Quando um problema qualquer for detectado, classifique-o em uma das dez heurísticas de Nielsen, anotando o problema na tabela correspondente e atribuindo o **grau de severidade** (0 até 4\) para este problema (dado pela tabela 2\) e recomece novamente até não encontrar mais problemas de usabilidade.

**Tabela 2 \- Grau de severidade dos problemas de usabilidade**

| Grau de severidade | Tipo | Descrição |
| ----- | :---- | :---- |
| 0 | Sem importância | Não afeta a operação da interface |
| 1 | Cosmético | Não há necessidade imediata de solução |
| 2 | Simples | Problema de baixa prioridade (pode ser reparado) |
| 3 | Grave | Problema de alta prioridade (deve ser reparado) |
| 4 | Catastrófico | Muito grave, deve ser reparado de qualquer forma. |


| Problema identificado | Grau de severidade | Classificação |
|---|:---:|---|
| Ausência de limites para idade no cadastro | 2 | Simples |
| Falta de feedback em caso de falha no carregamento | 3 | Grave |
| Mensagem de sucesso mesmo quando o SOS pode falhar | 4 | Catastrófico |
| Botão "Voltar ao Início" não deixa clara a desistência do exercício | 2 | Simples |

<img width="642" height="690" alt="image" src="https://github.com/user-attachments/assets/14b0d18d-af72-4e67-8049-452760af310f" />
<img width="922" height="707" alt="image" src="https://github.com/user-attachments/assets/30f15731-4d55-4aa3-8c95-9c697477c8b0" />

