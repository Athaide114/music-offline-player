# 🎵 Offline Music Player

Um player de música minimalista que funciona completamente offline usando Web Audio API e Service Workers.

## ✨ Funcionalidades

- 🎧 Reprodução de música offline
- 📱 Responsivo e mobile-friendly
- 🔄 Service Worker para cache automático
- 📝 Playlist dinâmica
- 🎨 Interface escura com tema Spotify

## 🛠️ Tecnologias

- HTML5
- CSS3
- JavaScript (Vanilla)
- Web Audio API
- Service Workers
- Progressive Web App (PWA)

## 🚀 Como Usar

1. Clone o repositório
```bash
git clone https://github.com/Athaide114/music-offline-player.git
cd music-offline-player
```

2. Abra o arquivo `index.html` no navegador ou use um servidor local:
```bash
python -m http.server 8000
# ou
npx serve
```

3. Selecione suas músicas locais e comece a ouvir!

## 📋 Funcionalidades do Player

- **Selecionar Músicas**: Clique em "Selecionar Músicas" para adicionar arquivos de áudio
- **Playlist**: Sua playlist aparece abaixo do player
- **Reprodução**: Clique em qualquer música para reproduzir
- **Controles**: Use os controles padrão do HTML5 audio

## 🔧 Estrutura do Projeto

```
music-offline-player/
├── index.html          # Estrutura HTML
├── style.css          # Estilos CSS
├── script.js          # Lógica JavaScript
├── sw.js              # Service Worker
├── manifest.json      # Configuração PWA
└── README.md          # Este arquivo
```

## 📦 Service Worker

O Service Worker (`sw.js`) faz cache de todos os arquivos necessários para que o app funcione completamente offline após o primeiro carregamento.

## 🌐 Suporte de Formatos

Suporta todos os formatos de áudio compatíveis com HTML5:
- MP3
- WAV
- OGG
- M4A
- FLAC (em navegadores compatíveis)

## 📱 PWA

Este projeto é uma Progressive Web App (PWA), o que significa que pode ser:
- Instalado na tela inicial do seu dispositivo
- Executado em modo standalone
- Funcionar sem conexão com a internet

## 🎨 Personalização

Você pode personalizar as cores modificando o arquivo `style.css`:
- Cor primária: `#1DB954` (verde Spotify)
- Fundo escuro: `#121212`
- Fundo do container: `#1e1e1e`

## 📄 Licença

MIT License - Sinta-se livre para usar e modificar!

## 👨‍💻 Autor

Athaide114

## 🤝 Contribuições

Contribuições são bem-vindas! Faça um fork e envie um pull request.

---

**Aproveite sua música offline!** 🎵