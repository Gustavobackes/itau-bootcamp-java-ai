# ☕ Java & Artificial Intelligence

Documentação dos conceitos, tecnologias e práticas de Inteligência Artificial aplicadas ao desenvolvimento Java, reunidos durante o Bootcamp do Itaú.

## 📚 Conteúdo

- [Sobre o Bootcamp](#-sobre-o-bootcamp)
- [Fundamentos de IA](#-fundamentos-de-ia)
  - [1. Origem da Inteligência Artificial](#1-origem-da-inteligência-artificial)
  - [2. Como funciona o treinamento de IA](#2-como-funciona-o-treinamento-de-ia)
  - [3. Small Language Models (SLMs)](#3-small-language-models-slms)

## 🎯 Sobre o Bootcamp

Programa de capacitação voltado à aplicação de Inteligência Artificial no desenvolvimento de software utilizando Java.

Este repositório reúne os conhecimentos adquiridos, com foco na compreensão dos conceitos e em suas possíveis aplicações práticas.

## 🧠 Fundamentos de IA

### 1. Origem da Inteligência Artificial

A Inteligência Artificial surgiu da proposta de desenvolver máquinas capazes de simular a inteligência humana, reproduzindo habilidades como raciocínio, aprendizado, resolução de problemas e tomada de decisões.

Desde os primeiros modelos, a ideia central era fazer com que computadores fossem capazes de executar tarefas que normalmente exigiriam inteligência humana, evoluindo gradualmente até os sistemas inteligentes que conhecemos hoje.

### 2. Como funciona o treinamento de IA

O treinamento de uma Inteligência Artificial consiste em apresentar grandes quantidades de exemplos para que o modelo consiga identificar padrões, características e relações entre os dados.

Um exemplo simples é ensinar uma IA a reconhecer uma maçã. São apresentadas imagens de maçãs em diferentes formatos, posições, cores e características. Cada exemplo fornece informações que ajudam o modelo a aprender a identificar o que caracteriza uma maçã.

Durante esse processo, são utilizados parâmetros e características (tokens) que ajudam a representar e diferenciar os elementos analisados.

**Feedback humano (Human-in-the-Loop):** o ser humano também pode participar do treinamento, validando respostas, corrigindo classificações e fornecendo orientações quando o modelo apresenta dúvidas ou resultados incorretos. Esse retorno ajuda a melhorar o aprendizado e a precisão do modelo.

<img width="939" height="560" alt="Exemplo de treinamento de IA com reconhecimento de maçãs" src="https://github.com/user-attachments/assets/03008fa4-75de-47c1-bb7e-c9a17f276708" />

Esse processo de aprendizado a partir de exemplos e avaliações também está presente no desenvolvimento de modelos voltados à geração de código, interpretação de linguagem e execução de outras tarefas.

### 3. Small Language Models (SLMs)

Os **SLMs (Small Language Models)** são modelos de linguagem menores, desenvolvidos para realizar tarefas específicas ou mais delimitadas, utilizando menos recursos computacionais do que os grandes modelos de linguagem (LLMs).

Sua principal vantagem é o menor consumo de memória e processamento, permitindo sua execução em máquinas locais e ambientes com infraestrutura mais limitada. Embora geralmente tenham menor capacidade de conhecimento amplo, podem apresentar excelentes resultados em tarefas especializadas.

Uma possibilidade é utilizar modelos com pesos abertos (*open-weight*), que podem ser baixados e adaptados por desenvolvedores por meio de ajustes e treinamentos adicionais (*fine-tuning*), utilizando conjuntos de dados próprios para direcionar o modelo a determinadas necessidades.

**Exemplos de modelos:** Microsoft Phi, Google Gemma, Meta Llama e Alibaba Qwen.

**SLM vs. LLM:**

| Característica | SLM | LLM |
|---|---|---|
| Tamanho | Menor | Maior |
| Processamento | Mais leve | Mais exigente |
| Infraestrutura | Mais acessível | Geralmente mais robusta |
| Especialização | Frequentemente direcionado | Conhecimento mais amplo |
| Aplicação | Tarefas específicas | Tarefas complexas e variadas |

**Importante:** o tamanho de um modelo está relacionado principalmente à quantidade de parâmetros, não à quantidade de tokens. Tokens são unidades utilizadas para representar o texto processado pelo modelo.

Uma alternativa ao treinamento do zero é partir de um modelo pré-treinado e especializá-lo com *fine-tuning*, reduzindo custos e tempo de desenvolvimento.

---

**Status:** Em construção 🚧

**Tecnologias:** Java | Artificial Intelligence | Generative AI
