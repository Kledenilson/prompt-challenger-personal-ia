# Modelo de Prompt para Treinos Personalizados

Este modelo foi criado para fornecer treinos e dicas de forma personalizada, utilizando variáveis que podem ser substituídas conforme necessário. 

---

## Regras para Personalização do Treino

### 1. **Biotipo Corporal**
Escolha o biotipo corporal mais próximo do aluno para que o treino seja mais eficiente. Existem três biotipos principais:
- **Ectomorfo**: Corpo magro, dificuldade em ganhar peso e massa muscular.
- **Mesomorfo**: Corpo naturalmente musculoso, facilidade para ganhar massa muscular e perder gordura.
- **Endomorfo**: Corpo com tendência a acumular gordura, dificuldade em perder peso.

### 2. **Dias Disponíveis para Treino**
Determine quantos dias por semana o aluno pode treinar. O treino sugerido varia conforme o número de dias:
- **1 dia**: Treino Full Body - trabalha o corpo inteiro em uma única sessão.
- **3 dias**: Treino ABC - cada dia foca em grupos musculares diferentes.
- **5 dias**: Treino ABCDE - divisão mais específica, cada dia focado em um grupo muscular.

### 3. **Tipos de Exercícios Preferidos**
Identifique o tipo de exercício preferido pelo aluno para ajustar o plano de treino. Exemplos de categorias:
- **Funcional**: Movimentos naturais que melhoram a funcionalidade do corpo.
- **Maquinário**: Exercícios feitos em máquinas para isolar grupos musculares.
- **Peso Livre**: Uso de halteres, barras e kettlebells para trabalhar múltiplos grupos musculares.
- **Cardio**: Foco em resistência cardiovascular (corrida, ciclismo, etc.).
- **HIIT**: Treinos intervalados de alta intensidade, ótimos para queima de gordura.

---

## Regras de Negócio
1. Identifique o biotipo corporal usando a seção de biotipos.
2. Determine a quantidade de dias disponíveis para treino e selecione o tipo de treino mais adequado.
3. Escolha o tipo de exercício preferido que se alinha com os objetivos do aluno.
4. Adicione sugestões de alimentação pré e pós-treino para otimizar os resultados, seja para emagrecimento ou ganho de massa muscular.

---

## Estrutura do Prompt

### Modelo Base
```markdown
# Treino Personalizado: {{Nome do Aluno}}

## Informações Básicas
- **Biotipo Corporal**: {{Biotipo Corporal (Ectomorfo, Mesomorfo, Endomorfo)}}
- **Dias Disponíveis para Treino**: {{Número de Dias por Semana}}
- **Tipo de Exercício Preferido**: {{Funcional, Maquinário, Peso Livre, Cardio, HIIT}}

## Plano de Treino

### Estrutura do Treino
**Divisão Semanal**:
- {{Tipo de treino baseado no número de dias}}

**Grupos Musculares Focados**:
- Dia 1: {{Grupo Muscular ou Exercício do Dia 1}}
- Dia 2: {{Grupo Muscular ou Exercício do Dia 2}}
- {{Repita para todos os dias disponíveis}}

**Duração Média por Sessão**: {{Tempo estimado}}

### Lista de Exercícios
- **Funcional**: {{Exercícios específicos}}
- **Maquinário**: {{Exercícios específicos}}
- **Peso Livre**: {{Exercícios específicos}}
- **Cardio**: {{Duração e tipo de exercício}}
- **HIIT**: {{Estrutura do treino intervalado}}

## Recomendações Nutricionais

### Pré-Treino:
- **Objetivo (Ganho de Massa)**: {{Alimentos ou combinações}}
- **Objetivo (Perda de Peso)**: {{Alimentos ou combinações}}

### Pós-Treino:
- **Objetivo (Ganho de Massa)**: {{Alimentos ou combinações}}
- **Objetivo (Perda de Peso)**: {{Alimentos ou combinações}}

## Observações Finais
- **Dicas de Consistência**: {{Sugestões de rotina e motivação}}
- **Progressão e Feedback**: {{Recomendações de ajuste}}
- **Motivação**: {{Mensagem personalizada}}

*Vamos juntos alcançar seus objetivos, {{Nome do Aluno}}!*
