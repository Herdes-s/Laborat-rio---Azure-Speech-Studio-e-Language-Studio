# Laboratório - Azure Speech Studio e Language Studio

##  Descrição
Este repositório foi desenvolvido como parte do desafio da **DIO**, com o objetivo de praticar e documentar o uso das ferramentas **Azure Speech Studio** e **Azure Language Studio**.  
Essas ferramentas fazem parte dos serviços de Inteligência Artificial da Microsoft e permitem trabalhar com **fala** e **linguagem natural**, possibilitando aplicações em **chatbots, assistentes virtuais, acessibilidade, análise de feedbacks e automação de processos**.

---

##  Objetivos de Aprendizagem
- Aplicar os conceitos teóricos em um ambiente prático.
- Explorar os recursos do Azure para **processamento de voz** e **linguagem natural**.
- Documentar os passos de configuração e uso.
- Compartilhar aprendizados utilizando o GitHub como portfólio técnico.

---

##  Tecnologias Utilizadas
- [Microsoft Azure Speech Studio](https://speech.microsoft.com/) → voltado para reconhecimento de fala, conversão de texto em fala e customização de vozes.
- [Microsoft Azure Language Studio](https://language.cognitive.azure.com/) → utilizado para análise de sentimentos, classificação de texto e reconhecimento de entidades.
- Git e GitHub → versionamento e publicação da documentação.

---

##  Passo a Passo Realizado

### 1. Criação do Ambiente no Azure
- Acesse o portal do Azure.
- Crie um **Resource Group** (grupo de recursos) para organizar os serviços.
- Adicione os recursos:
  - **Speech Service** → utilizado pelo Speech Studio.
  - **Language Service** → utilizado pelo Language Studio.

### 2. Experimentos no Speech Studio
- **Transcrição de fala em texto:** testei gravações de áudio e o serviço converteu automaticamente para texto.
- **Conversão de texto em fala (TTS):** utilizei frases em português e o sistema gerou áudio com vozes neurais realistas.
- **Teste de pronúncia:** recurso interessante para comparar a pronúncia correta com o áudio fornecido.

### 3. Experimentos no Language Studio
- **Análise de sentimentos:** inseri textos positivos, negativos e neutros → o modelo retornou a classificação correta.
- **Reconhecimento de entidades:** detectou nomes próprios, datas e locais em frases de teste.
- **Classificação de textos:** separei conteúdos por categorias de forma automática.
