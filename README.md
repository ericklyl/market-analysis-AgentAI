# Análise de Mercado Automatizada com CrewAI

<p align="center">
  <img src="https://github.com/joaomdmoura/crewAI/raw/main/docs/img/crewai.png" alt="CrewAI Logo" width="300"/>
</p>

Este projeto implementa um sistema de análise de mercado automatizada utilizando **CrewAI**, uma biblioteca para criação de agentes colaborativos. Através de uma equipe de três agentes especializados, o sistema pesquisa, analisa e produz relatórios detalhados sobre qualquer setor de mercado.

## 🌟 Recursos

- **Análise Automatizada**: Crie relatórios de mercado completos automaticamente
- **Agentes Especializados**: Equipe com pesquisador, analista e redator profissional
- **Personalização**: Adapte a análise para qualquer setor de mercado
- **Exportação Flexível**: Obtenha relatórios em formato Markdown e HTML

## 📋 Requisitos

- Python 3.8+
- Jupyter Notebook
- Biblioteca CrewAI
- Chave da API OpenAI ou outra LLM compatível

## 🚀 Instalação

1. Clone este repositório:
```bash
git clone https://github.com/ericklyl/market-analysis-AgentAI
cd market-analysis-AgentAI
```

2. Instale as dependências:
```bash
pip install -r requirements.txt
```

3. Configure sua chave de API no arquivo `.env`:
```
OPENAI_API_KEY=sua_chave_api_aqui
```

## 💻 Como Usar

1. Abra o notebook Jupyter:
```bash
jupyter notebook analise_mercado.ipynb
```

2. Execute todas as células do notebook para configurar a equipe e as tarefas

3. Modifique o setor de mercado conforme necessário:
```python
resultado = crew.kickoff(inputs={"sector": "Mercado Financeiro Internacional"})
```

4. O relatório final será exibido no notebook e exportado como arquivos Markdown e HTML

## 🧩 Estrutura do Projeto

```
market-analysis-AgentAI/
├── analise_mercado.ipynb    # Notebook principal com a lógica do projeto
├── .env                     # Arquivo de configuração (chaves de API)
├── requirements.txt         # Dependências do projeto
├── docs/                    # Documentação adicional
├── artigo.md                # Relatório gerado (formato Markdown)
└── artigo.html              # Relatório gerado (formato HTML)
```

## 🤖 Agentes e suas Funções

### 🔍 Pesquisador de Mercado
Especializado em coletar e organizar informações atualizadas sobre o setor especificado.

### 📊 Analista de Tendências
Examina os dados coletados para identificar padrões, tendências emergentes e oportunidades no setor.

### 📝 Redator de Relatórios
Transforma as análises em um relatório estruturado, compreensível e orientado para tomadores de decisão.

## 📑 Formato do Relatório

O relatório final inclui:
- Introdução ao setor
- Principais players do mercado
- Tendências emergentes
- Estatísticas relevantes
- Conclusões
- Resumo executivo
- Recomendações estratégicas

## 🔧 Personalização

Para personalizar a análise:

- Modifique o `backstory` dos agentes para ajustar suas perspectivas
- Altere as descrições das tarefas para focar em aspectos específicos
- Adicione novos agentes para cobrir áreas adicionais de análise
- Ajuste o formato do relatório modificando a tarefa do redator

## 📊 Exemplo de Uso

```python
# Para análise do setor de tecnologia
resultado = crew.kickoff(inputs={"sector": "Tecnologia"})

# Para análise do setor de saúde
resultado = crew.kickoff(inputs={"sector": "Saúde"})

# Para análise do mercado imobiliário
resultado = crew.kickoff(inputs={"sector": "Imobiliário"})
```

## 📚 Documentação Adicional

Para informações mais detalhadas sobre a biblioteca CrewAI:
- [Documentação oficial do CrewAI](https://docs.crewai.com/)
- [Repositório do CrewAI no GitHub](https://github.com/joaomdmoura/crewAI)

## 🤝 Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.

## 📄 Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

---

<p align="center">
  Desenvolvido com ❤️ usando <a href="https://github.com/joaomdmoura/crewAI">CrewAI</a>
</p>
