<p align="center">
    <img width="300px" src=".github/assets/logo_2.png">
</p>

<p align="center">
<a href="https://dio.me/"><img src="https://img.shields.io/badge/DIO-Project-FED564?logo=youtube" alt="DIO - Project"></a>
<a href="https://www.gnu.org/software/bash/" title="Go to Bash homepage"><img src="https://img.shields.io/badge/Prompt-Project-FED564?logo=gnu-bash&amp;logoColor=white" alt="Made with Bash"></a>
<a href="https://aws.amazon.com/" title="Powered by AWS">
  <img src="https://img.shields.io/badge/Powered%20by-AWS-FED564?logo=icloud&logoColor=white" alt="Powered by AWS">
</a>
</p>

<p align="center">
  <h3 align="center">🏋️‍♂️ Assistente de Personal Trainer - Gerador de Treino Ideal</h3>
Este projeto é um desafio de Prompt Engineer, onde o objetivo é criar um prompt que ajuda a montar o treino ideal para cada combinação de fatores, como biotipo corporal, disponibilidade de tempo e tipo de exercícios preferidos. O assistente de personal trainer gerado por esse prompt será capaz de personalizar os treinos de acordo com as características e necessidades do usuário.
O projeto deve ser feito utilizando as boas práticas de prompt engineer.
</p>

## 📋 Índice

- [📋 Índice](#-índice)
- [📝 Introdução](#-introdução)
- [💪 Biotipos Corporais](#-biotipos-corporais)
- [📅 Dias Disponíveis para Treino](#-dias-disponíveis-para-treino)
- [🏋️ Tipos de Exercícios](#️-tipos-de-exercícios)
- [🛠️ Regras de negócio](#️-regras-de-negócio)
- [📖 Material de Apoio](#-material-de-apoio)
- [🎯 Prompt de Resposta Proposto](#-prompt-de-resposta-proposto)

---

## 📝 Introdução

Este projeto visa criar um assistente de personal trainer automatizado que ajuda a gerar treinos personalizados. O usuário fornecerá informações como o biotipo corporal, a quantidade de dias disponíveis para treinar na semana e o tipo de exercício preferido, e o assistente gerará um plano de treino ideal com base nessas informações.

---

## 💪 Biotipos Corporais

A primeira regra para personalizar o treino é determinar o biotipo corporal do usuário. Existem três biotipos principais:

<table>
  <tr>
    <th>Imagem</th>
    <th>Biotipo</th>
    <th>Descrição</th>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/ectomorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Ectomorfo</strong></td>
    <td>Corpo mais magro, difícil ganhar peso e massa muscular.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/mesomorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Mesomorfo</strong></td>
    <td>Corpo naturalmente musculoso, facilidade para ganhar massa muscular e perder gordura.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/endmorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Endomorfo</strong></td>
    <td>Corpo com tendência a acumular gordura, maior dificuldade em perder peso.</td>
  </tr>
</table>

> **Nota:** Escolha o biotipo que mais se aproxima do seu corpo atual para que o treino seja mais eficiente.

---

## 📅 Dias Disponíveis para Treino

A segunda regra é determinar quantos dias por semana o usuário tem disponível para treinar. Dependendo do número de dias, o treino sugerido pode variar:

| **Imagem**                                                     | **Dias por Semana** | **Tipo de Treino Sugerido** |
| -------------------------------------------------------------- | ------------------- | --------------------------- |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 1 dia               | Treino Full Body            |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 3 dias              | Treino ABC                  |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 5 dias              | Treino ABCDE                |

- **Full Body**: Treino que trabalha o corpo todo em uma única sessão.
- **ABC**: Divisão do treino em três dias, cada um focado em grupos musculares diferentes.
- **ABCDE**: Divisão do treino em cinco dias, com foco ainda mais específico em cada grupo muscular.

---

## 🏋️ Tipos de Exercícios

A terceira regra envolve a escolha do tipo de exercício preferido. Aqui estão algumas categorias com exemplos:

| **Imagem**                                                       | **Tipo de Treino** | **Descrição**                                                                                                 |
| ---------------------------------------------------------------- | ------------------ | ------------------------------------------------------------------------------------------------------------- |
| <img src=".github/assets/dumbells.png" width="50%" height="50%"> | **Funcional**      | Exercícios que melhoram a funcionalidade do corpo, usando movimentos naturais.                                |
| <img src=".github/assets/4760665.png" width="50%" height="50%">  | **Maquinário**     | Exercícios feitos em máquinas, com foco em isolar grupos musculares.                                          |
| <img src=".github/assets/barr.png" width="50%" height="50%">     | **Peso Livre**     | Exercícios com pesos livres, como halteres e barras, para trabalhar vários grupos musculares simultaneamente. |
| <img src=".github/assets/cardio.png" width="50%" height="50%">   | **Cardio**         | Exercícios voltados para melhorar a resistência cardiovascular, como corrida ou ciclismo.                     |
| <img src=".github/assets/hiit.png" width="50%" height="50%">     | **HIIT**           | Treinos intervalados de alta intensidade, ótimos para queima de gordura.                                      |

---

## 🛠️ Regras de negócio

1. **Identifique seu biotipo corporal** consultando a seção de biotipos.
2. **Determine quantos dias por semana você pode treinar** e escolha o tipo de treino mais adequado.
3. **Selecione o tipo de exercício** que prefere realizar e que se encaixa melhor nos seus objetivos.
4. Use o prompt do assistente para gerar um plano de treino personalizado.

---

## 📖 Material de Apoio

Aqui estão alguns recursos adicionais que podem ser úteis para entender melhor o projeto e as práticas de prompt engineering:

- [Fundamentos de Engenharia de prompt](https://elidianaandrade.gitbook.io/fundamentos-de-engenharia-de-prompts-com-claude-3)
- [Boas práticas de prompt](https://aline-antunes.gitbook.io/otimize-seus-prompts-e-aprenda-mais-usando-ias-1)

---

## 🎯 Prompt de Resposta Proposto

Com base nos conhecimentos adquiridos durante o curso e na proposta acima, fiz o seguinte:
1. Copiei toda a regra definida aqui no desafio para um documento no Word e o salvei em PDF.
2. Utilizei o chatGPT para me auxiliar no desafio e passei o seguinte prompt abaixo:
    **Você disse:** Olá Chat!
    **O ChatGPT disse:** Oi, Martinson! Como está?
   
    **Você disse:** Bem obrigado! Analise o documento anexo...
    **O ChatGPT disse:** Por favor, envie o documento para que eu possa analisá-lo.
   
    **Você disse:** Desafio Prompts IAs Generativas.pdf   
    **O ChatGPT disse:** O documento trata de um desafio para criar um assistente de personal trainer por meio de prompts de IA generativas. O           objetivo é desenvolver um prompt que personalize o treino ideal baseado em três fatores principais:

    Biotipo Corporal: Classificação em Ectomorfo, Mesomorfo ou Endomorfo.
    Dias Disponíveis para Treino: Variedade de treinos recomendados de acordo com a frequência semanal (Full Body, ABC, ABCDE).
    Tipo de Exercício Preferido: Funcional, Maquinário, Peso Livre, Cardio, ou HIIT.

    O projeto tem foco nas boas práticas de prompt engineering, visando um sistema que gere um plano de treino personalizado a partir das                características do usuário​.

    Se precisar de algum detalhe específico, é só avisar!
   
    **Você disse:** A partir das regras disponíveis no documento, monte uma rotina de treinos para uma pessoa que tenha o Biotipo Endomorfo, 3 dias      de treinos disponíveis e com exercícios do tipo Funcional, Cardio e HIIT...

    **O ChatGPT disse:** Com base nas regras do documento, aqui está uma rotina de treinos personalizada para uma pessoa com biotipo endomorfo, que      tem 3 dias de treino disponíveis e prefere exercícios funcionais, cardio e HIIT:
   
    - Perfil: Biotipo: Endomorfo (dificuldade para perder peso, tendência a acumular gordura).
    - Dias de treino: 3 dias por semana.
    - Tipos de treino preferido: Funcional, Cardio, HIIT.

Rotina de Treinos:
Dia 1 - Funcional (Foco no Corpo Todo):
    Aquecimento:
        5-10 minutos de polichinelos ou corrida leve.
    Treino Funcional (3 séries de 12-15 repetições):
        Agachamento com peso corporal.
        Flexões de braço (adaptar com joelhos no chão, se necessário).
        Afundos (lunges).
        Burpees (movimento completo).
        Prancha isométrica (30-45 segundos).
    Cardio pós-treino:
        10-15 minutos de corrida leve ou bicicleta.

Dia 2 - Cardio e HIIT (Foco em queima de gordura e resistência):
    Aquecimento:
        5-10 minutos de caminhada rápida ou trote leve.
    Treino HIIT (8 séries de 20 segundos de esforço máximo, 10 segundos de descanso):
        Corrida em alta intensidade ou sprint.
        Mountain Climbers (escalada cruzada no chão).
        Salto em caixote ou banco (box jumps).
        Corrida no lugar com elevação de joelhos (high knees).
    Cool down (desaceleração):
        5-10 minutos de caminhada ou alongamento leve.

Dia 3 - Funcional e Cardio (Foco em força e resistência cardiovascular):
    Aquecimento:
        5 minutos de corda ou caminhada acelerada.
    Treino Funcional (circuito de 3 séries):
        Kettlebell swings (pode substituir com um halter se necessário) – 12 repetições.
        Flexão e rotação (flexão seguida de rotação do tronco) – 12 repetições.
        Abdominal bicicleta – 15 repetições por lado.
        Ponte glútea – 12-15 repetições.
    Cardio pós-treino:
        20 minutos de bicicleta, corrida leve, ou elíptico.

Dicas adicionais para Endomorfos:
    Enfoque em treinos de alta intensidade (como o HIIT e funcional) para maximizar a queima calórica.
    Manter a frequência cardíaca elevada durante os treinos com intervalos curtos de descanso.
    Acompanhar a dieta com foco em déficit calórico para auxiliar na perda de peso.

Essa rotina é ideal para melhorar a condição física, queimar gordura e aumentar a resistência, respeitando a preferência por treinos funcionais, cardio e HIIT.

**Você disse:** Obrigado!
**O ChatGPT disse:** De nada, Martinson! Se precisar de mais ajuda com treinos ou qualquer outro assunto, é só avisar. Bons treinos! 💪 

---

Utilizei as dicas dadas durante o curso e uso uma linguagem mais intimista com o ChatGPT durante as minhas interações com a ferramenta, isso me passa um sentimento de colaboração mais amigável durante as minhas consultas iterativas.
