# 🎬 Batalha de Modelos & Engenharia de Prompt (XML)

## 📝 Descrição do Projeto
Este projeto consiste em um motor de recomendação inteligente que utiliza técnicas de filtragem colaborativa e baseada em conteúdo. O objetivo principal é reduzir a “paralisia de escolha”, oferecendo recomendações personalizadas com base no histórico de avaliações e preferências dos usuários.

O sistema foi desenvolvido utilizando um modelo de página HTML5 Single Page com CSS3 interno, seguindo um padrão responsivo e minimalista definido através de um Prompt Estruturado em XML. O experimento também teve como foco analisar a fidelidade de diferentes IAs ao interpretar prompts estruturados.

Durante os testes, ferramentas como ChatGPT, Gemini, Claude, DeepSeek, Qwen, Grok e Maritaca foram avaliadas com base na precisão do HTML gerado, respeito às tags XML, quantidade de tokens consumidos e ocorrência de erros de sintaxe.

http://googleusercontent.com/image_generation_content/0  
*Figura 1: Dashboard principal do sistema exibindo recomendações personalizadas.*

---

## 🚀 Tecnologias Utilizadas

* **Linguagem:** HTML5, CSS3 e Python 3.10
* **Bibliotecas:** Pandas, Scikit-learn e Matplotlib
* **Ferramentas:** Jupyter Notebook, Google Colab e Inteligências Artificiais Generativas
* **Estrutura do Prompt:** XML Estruturado

---

## 📊 Resultados e Aprendizados

Os testes demonstraram diferenças importantes entre os modelos avaliados.

| Critério | Melhor Resultado |
|---|---|
| Precisão do XML | ChatGPT e Claude |
| Precisão do HTML | ChatGPT |
| Menor quantidade de erros | Claude |
| Menor consumo de tokens | DeepSeek e Qwen |
| Maior criatividade | Gemini e Claude |

### Principais Aprendizados

* Estruturas XML ajudam a aumentar a fidelidade do código gerado pelas IAs.
* Modelos diferentes possuem comportamentos distintos mesmo utilizando o mesmo prompt.
* ChatGPT e Claude apresentaram maior precisão técnica.
* DeepSeek e Qwen produziram respostas mais econômicas em tokens.
* Gemini apresentou maior criatividade visual na construção do layout.

---

## 🔧 Como Executar

1. Clone o repositório.
2. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```
3. Execute o projeto:
   ```bash
   python main.py
   ```

---

## 📌 Conclusão

A utilização de prompts estruturados em XML demonstrou ser eficiente para padronizar respostas geradas por diferentes modelos de IA. A atividade permitiu analisar como cada ferramenta interpreta regras técnicas, além de evidenciar diferenças entre criatividade, precisão estrutural e consumo de tokens.

Para prototipagem rápida, os modelos Gemini e ChatGPT apresentaram melhor desempenho. Já para tarefas mais complexas e técnicas, ChatGPT e Claude demonstraram maior confiabilidade.

---

[Voltar ao início](https://docs.google.com/document/d/1fEoZrcYZtsSfXzC6XOeZR4t0a7fWn1wMNor8cmsju8U/edit?usp=sharing)
