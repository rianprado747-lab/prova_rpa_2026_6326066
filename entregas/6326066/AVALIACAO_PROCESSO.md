# Ficha de Avaliação de Processo (PDD) — Questão 5

> MOLDE. Copie para `entregas/SEU_RA/` e preencha. Escolha **um** cenário (A ou B).

**Cenário escolhido:** B

1. **Nome do processo e descrição resumida:**
   Priorização da fila de chamados de suporte. O processo consiste em analisar e ordenar os tickets de atendimento com base no estado emocional do cliente e na urgência percebida e relatada pelo atendente humano.

2. **Volume / frequência estimados:**
   Geralmente alto e contínuo. Em operações de suporte ao cliente, dezenas ou centenas de novos chamados entram diariamente e a todo o momento, exigindo uma triagem e priorização constantes ao longo do dia.>

3. **As entradas são estruturadas?** (sim/não + justificativa)
   Não. O processo depende da "percepção de urgência" e do "humor do cliente", que são dados totalmente subjetivos, qualitativos e, na maioria das vezes, registados em formato de texto livre (anotações e relatos do atendente). Não existe um formato digital rígido, tabular e padronizado

4. **As regras são claras e determinísticas?** (sim/não + justificativa)
   Não. Regras determinísticas baseiam-se numa lógica exata e imutável (ex: "se o prazo de resposta expirou, prioridade = alta"). A avaliação de humor e urgência exige interpretação, empatia e julgamento cognitivo, sendo passível de variação dependendo da perspetiva de cada atendente humano.

5. **Veredito — o processo é elegível a RPA?** (justifique com base em regras
   claras, dados estruturados e repetibilidade)
   
   Não é elegível para RPA tradicional. Embora o processo possua repetibilidade (ocorre em alto volume diariamente), ele falha nos dois pilares fundamentais da Automação Robótica de Processos: as entradas não são dados estruturados e as regras não são claras nem determinísticas. Uma ferramenta de RPA puro não consegue interpretar sentimentos, emoções ou "perceções" humanas. Para automatizar um cenário destes, seria obrigatório o uso de Inteligência Artificial (como Processamento de Linguagem Natural ou Análise de Sentimentos) associada à automação, fugindo do escopo do RPA clássico.
