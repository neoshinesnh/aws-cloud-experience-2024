
## 15H40 - 16H10 - IA Generativa | Prompt Engineering x Fine Tuning x RAG. Qual eu devo usar?

_Ariane Vieira - Solutions Architect - AWS_

* Há distinções entre os modelos convencionais de aprendizado de máquina e os modelos de base (Foundation Models)
* Abordagens comuns para melhorar Foundation Models (FM) - Prompt Engineering:
    * 1. **Otimize respostas sem modificar o modelo pré-treinado**
    * 2. **Engenharia de Prompt**
   - Método para ajustar e personalizar as respostas do FM usando estratégias como o RAG (Retrieval-Augmented Generation) para alcançar resultados específicos.
    * 3. **RAG**
   - Para customizar as respostas do FM
    * 4. **Otimizações granulares (Fine-tuning)**
   - Técnica que envolve ajustar os parâmetros do modelo em níveis detalhados para melhorar seu desempenho em tarefas específicas.
    * 5. **Treinar seu FM do zero**
   - Abordagem mais radical que envolve criar um novo modelo a partir do zero, adaptando-o às necessidades específicas do projeto.
* O que são vector embedding?
    * Busca dados específicos de um dominio
    * Tokenização
    * Vetorização
    * Armazena em uma base de dados de vetor
    * Executa busca semântica de similaridades
    * Inclui context semântico similar no prompt
* Técnicas de Prompt Engineering
    * Zero-shot
    * Few-shot
    * Chain of Thoughts (CoT)
    * Reasoning & Acting (ReAct)
    * Self Consistency
* O que é Retrieval Augmentation Generation?
    * Retrieval
        * Busca o conteúdo relevante a partir de uma base de conhecimento externa ou fontes de dados a partir de uma consulta do usuário
    * Augmentation
        * Adicionando o contexto relevante que foi buscado no prompt do usuário, usando como entrada para o foundation model
    * Generation
        * Resposta do foundation model baseada no prompt aumentado.