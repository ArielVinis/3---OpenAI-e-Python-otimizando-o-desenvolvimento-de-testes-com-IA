# OpenAI: Otimizando o desenvolvimento de testes com IA

## ⚙️ Configuração do Ambiente

### Criando e Ativando o Ambiente Virtual

**Windows:**

```bash
python -m venv curso_3_openai
curso_3_openai\Scripts\activate
```

### Instalação das Bibliotecas

- O Faiss para Mac apresentou compatibilidade apenas para a versão 3.11 do python ou inferior

```bash
pip install numpy openai python-dotenv tiktoken opencv-python selenium faiss-cpu
```

### 📚 Referências de Leitura

- [Documentação Whisper](https://openai.com/research/whisper)
- [Documentação Dall-E](https://openai.com/research/dall-e)
- [Preços OpenAI](https://openai.com/pricing)
- [Áudios Longos](https://platform.openai.com/docs/guides/speech-to-text/prompting)

## 🚀 Como usar

1. Execute o script principal:

```bash
python main.py
```

2. Siga as instruções para gerar e validar os testes automaticamente. A ferramenta utiliza prompts avançados para gerar testes com assertivas específicas, otimizadas para o comportamento do seu código.

## 📂 Estrutura do projeto

- `main.py`: Arquivo principal que executa a lógica do projeto.

- `tests/`: Diretório onde os casos de teste gerados são armazenados.

- `requirements.txt`: Arquivo com as dependências do projeto.

## 📚 Recursos utilizados

- [OpenAI API Documentation](https://platform.openai.com/docs/overview).

- Python para automação de testes.

## ✨ Funcionalidades

- Geração de casos de teste baseados em inteligência artificial.
- Otimização de testes manuais com assertivas automatizadas.
- Integração com projetos Python existentes.
