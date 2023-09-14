# NLW IA

## Descrição do Projeto:

O NLW IA é um projeto que utiliza inteligência artificial(IA) para transcrever e resumir shorts do YouTube. O objetivo é tornar a experiência de consumo de conteúdo mais eficiente, fornecendo transcrições e resumos rápidos e precisos para os usuários.

## Instalação

Para instalar dependências:

```bash
  git clone https://github.com/CarlosAliSchutz/NLW.git
  cd NLW
  npm install
```

### Execução do Frontend

Para iniciar o Frontend do projeto, execute o seguinte comando:

```bash
npm run web
```

### Execução do Backend

Para iniciar o Backend do projeto, execute o seguinte comando:

```bash
npm run server
```

## Tecnologias usadas

[![My Skills](https://skillicons.dev/icons?i=vite,html,css,js&perline=4)](https://skillicons.dev)

## Capturas de Tela

![App Screenshot](https://github.com/CarlosAliSchutz/NLW/blob/main/web/images/Web.jpg)

## Bibliotecas Instaladas

Este projeto utiliza diversas bibliotecas para realizar várias tarefas. Abaixo, descrevemos cada biblioteca e sua finalidade:

### Bibliotecas para o Backend:

`npm i express cors axios ytdl-core@4.10.0`

#### 1. Express

- **Descrição:** O Express é um framework Node.js que facilita a criação de servidores web e APIs.
- **Utilização no Projeto:** Utilizamos o Express para iniciar e configurar nosso servidor, definir rotas para lidar com solicitações HTTP e fornecer respostas.

#### 2. CORS (Cross-Origin Resource Sharing)

- **Descrição:** O CORS é um middleware que permite que o backend e o frontend se comuniquem de forma segura, mesmo quando estão em domínios diferentes.
- **Utilização no Projeto:** Usamos o CORS para permitir que o frontend faça solicitações ao nosso servidor sem problemas de segurança.

#### 3. Axios

- **Descrição:** Axios é um cliente HTTP que simplifica o envio de solicitações HTTP para o servidor.
- **Utilização no Projeto:** Utilizamos o Axios no frontend para fazer solicitações ao backend e obter respostas.

#### 4. ytdl-core

- **Descrição:** ytdl-core é uma biblioteca que permite fazer o download de vídeos do YouTube.
- **Utilização no Projeto:** Usamos o ytdl-core para baixar vídeos do YouTube no projeto.

### Bibliotecas para o Backend e Frontend:

`npm i @xenova/transformers`

#### 5. @xenova/transformers

- **Descrição:** Esta biblioteca é usada para executar modelos de inteligência artificial.
- **Utilização no Projeto:** É usada em ambas as partes, backend e frontend, para realizar tarefas relacionadas à inteligência artificial.

### Bibliotecas para Manipulação de Vídeo e Áudio:

`npm i fluent-ffmpeg ffmpeg-static node-wav`

#### 6. fluent-ffmpeg

- **Descrição:** Fluent-ffmpeg é uma biblioteca Node.js que fornece uma interface fácil para manipular arquivos de vídeo.
- **Utilização no Projeto:** Utilizamos o fluent-ffmpeg para manipular vídeos no projeto, incluindo a obtenção de informações de áudio.

#### 7. ffmpeg-static

- **Descrição:** ffmpeg-static é uma dependência estática do FFmpeg que é usada pelo fluent-ffmpeg para executar operações em arquivos de vídeo.
- **Utilização no Projeto:** É necessário para que o fluent-ffmpeg funcione corretamente.

#### 8. node-wav

- **Descrição:** Node-wav é uma biblioteca que permite converter o conteúdo de vídeo em formatos WAV.
- **Utilização no Projeto:** Usamos o node-wav para converter o conteúdo de vídeo em formato WAV.
