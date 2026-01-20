# DarkLAB - Automação de Vídeos e Imagens no Google Labs VEO3

Automação para criar vídeos e imagens no Google Labs VEO3 a partir de prompts e audios.

**[⬇️ BAIXAR - Versão 1.0.0](https://github.com/leosander/darklab/releases/download/v1.0.0/DarkLAB-1.0.0-win.zip)**

---

## O que faz

O DarkLAB automatiza a criação de vídeos e imagens no Google Labs VEO3. Em vez de você copiar e colar cada prompt manualmente no site, a automação faz isso sozinha - insere os prompts, cria os vídeos/imagens, monitora o progresso e baixa tudo quando pronto.

---

## Funcionalidades

### Prompts/Texto

Gera prompts usando Claude AI. Você pode definir quantos prompts quer por resposta para evitar que a IA corte qualquer prompt. Por exemplo, se quer 200 prompts, pode dividir em várias respostas (ex: 50 prompts por resposta = 4 respostas).

### Prompts/Narração

Faz upload de um áudio (MP3, WAV, etc). O áudio é transcrito automaticamente e o sistema calcula como gerar prompts de vídeos sincronizados com o áudio. Cada prompt corresponde a uma parte específica da narração.

### Flow/Imagens

Automação de criação de imagens no Google Labs ImageFX. Você pode selecionar o modelo:
- Nano Banana
- Nano Banana Pro
- Imagen4

### Flow/Vídeos

Automação de criação de vídeos no Google Labs VEO3. Você pode:
- Colocar prompts diretamente para gerar vídeos
- Ou colocar um áudio - o sistema transcreve, gera prompts sincronizados e cria os vídeos automaticamente

Modelos disponíveis:
- Veo 3.1 Fast
- Veo 3.1 Fast Low Priority
- Veo 3.1 Quality
- Veo 2 Fast
- Veo 3 Quality

Quando você usa áudio, o sistema calcula automaticamente como cortar os vídeos. Na pasta de download, todos os vídeos já ficam prontos para vincular no áudio em um editor de vídeo.

### Retry Automático

Vídeos e imagens têm tratamento automático para itens que deram problema ao gerar. O sistema detecta falhas e tenta novamente automaticamente.

### Retry Manual

Você pode fazer retry manual de qualquer vídeo da lista de vídeos. Basta selecionar quais vídeos quer tentar novamente.

---

## Configurações

### Configs

- **Linguagem**: Selecionar entre Português (PT-BR) e Inglês (EN)
- **Contas Google**: Cadastrar suas contas do Google Labs (email e senha)
- **API Key do Claude**: Cadastrar sua chave da API do Claude (obtenha em: https://console.anthropic.com/)

### Configurações ao Gerar Vídeos/Imagens

- **Aspect Ratio**: Landscape 16:9 ou Portrait 9:16
- **Images/Videos por Prompt**: Quantidade de imagens/vídeos que vai gerar para cada prompt (entre 1 e 4)
- **Threads**: Número de sessões que vai criar simultaneamente

**Sobre Threads:**

O DarkLAB usa um gerenciador de contas do Google Labs inteligente. Por exemplo:
- Você tem 200 prompts para gerar
- Tem 2 contas Google configuradas
- Selecionou 10 threads

O sistema vai abrir 10 sessões em cada conta (total de 20 sessões) para gerar os 200 prompts simultaneamente. Isso acelera muito a criação de vídeos/imagens.

---

## Como Usar

### 1. Instalar

Baixe o instalador, execute o arquivo `.exe` e siga as instruções. Tudo está incluído, não precisa instalar nada adicional.

### 2. Configurar

Abra o DarkLAB e vá em **Configurações**:

1. **API Key do Claude**: Cole sua chave (obtenha em https://console.anthropic.com/)
2. **Contas Google**: Adicione suas contas do Google Labs (email e senha)
3. **Linguagem**: Escolha PT-BR ou EN

### 3. Gerar Prompts a partir de Texto

1. Vá na aba **Prompts**
2. Escolha **Entrada por Texto**
3. Digite o que você quer (ex: "Gere prompts para vídeos sobre história de Roma")
4. Defina quantos prompts quer e quantos por resposta
5. Clique em **Gerar Prompts**

### 4. Gerar Vídeos a partir de Áudio

1. Vá na aba **Prompts**
2. Clique em **Upload de Áudio**
3. Selecione um arquivo de áudio (MP3, WAV, etc)
4. Configure:
   - Título do projeto
   - Prefixo de estilo (opcional)
   - Marque "Criar vídeos automaticamente" se quiser
5. Clique em **Processar**

O sistema vai transcrever o áudio, gerar prompts sincronizados e criar os vídeos automaticamente. Os vídeos já ficam cortados e prontos para usar no editor.

### 5. Criar Vídeos com Prompts Manuais

1. Vá na aba **Vídeos VEO3**
2. Cole ou digite seus prompts (um por linha)
3. Configure:
   - Nome do projeto
   - Modelo (Veo 3.1 Fast, etc)
   - Aspect Ratio (Landscape 16:9 ou Portrait 9:16)
   - Vídeos por Prompt (1 a 4)
   - Threads (número de sessões simultâneas)
   - Pasta de download
4. Clique em **Iniciar Criação**

A automação vai inserir todos os prompts no site, criar os vídeos, monitorar o progresso e baixar tudo quando pronto.

### 6. Criar Imagens

1. Vá na aba **Imagens ImageFX**
2. Cole ou digite seus prompts
3. Configure:
   - Nome do projeto
   - Modelo (Nano Banana, etc)
   - Aspect Ratio
   - Imagens por Prompt (1 a 4)
   - Threads
   - Pasta de download
4. Clique em **Iniciar Criação**

### 7. Retry Manual de Vídeos

1. Vá na lista de vídeos
2. Selecione os vídeos que falharam ou que quer tentar novamente
3. Clique em **Retry Selecionados**

--

## Notas

- Os vídeos são criados no Google Labs (serviço da Google)
- Você precisa ter contas Google Labs válidas
- A API do Claude tem custos (alguns centavos por mil prompts)
- Vídeos são baixados automaticamente quando prontos
- Você pode usar múltiplas contas para criar mais vídeos simultaneamente
- A automação funciona sozinha - não precisa ficar na frente do computador

---

**[⬇️ BAIXAR - Versão 1.0.0](https://github.com/leosander/darklab/releases/download/v1.0.0/DarkLAB-1.0.0-win.zip)**

© 2026 DarkLAB
