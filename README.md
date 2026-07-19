# TERMUX 200+ TUTORIAIS

> Do básico ao avançado — O guia definitivo de comandos Termux

## 🚀 Como publicar no GitHub Pages

### 1. Crie um repositório no GitHub

1. Acesse [github.com/new](https://github.com/new)
2. Nome do repositório: `termux-tutoriais` (ou qualquer nome)
3. Deixe como **público**
4. Não marque "Add a README" (já temos)

### 2. Envie os arquivos

```bash
# Clone (se criou com README) ou apenas faça upload
git clone https://github.com/SEU-USUARIO/termux-tutoriais.git
cd termux-tutoriais

# Copie o index.html
cp /caminho/para/index.html .
cp /caminho/para/README.md .

git add .
git commit -m "Add Termux tutorials page"
git push origin main
```

Ou faça upload manual pelo site do GitHub em `Add file > Upload files`.

### 3. Ative o GitHub Pages

1. Vá em **Settings > Pages** do seu repositório
2. Em "Branch", selecione `main` e pasta `/ (root)`
3. Clique em **Save**
4. Aguarde 1-2 minutos e acesse: `https://SEU-USUARIO.github.io/termux-tutoriais`

## 📋 Funcionalidades

- ✅ 200+ tutoriais do básico ao avançado
- ✅ Busca em tempo real por comando, descrição ou tags
- ✅ Filtro por nível: Básico / Intermediário / Avançado
- ✅ Modal com detalhes e output simulado do terminal
- ✅ Botão copiar comando com feedback visual
- ✅ Categorias colapsáveis
- ✅ Design responsivo
- ✅ Animações: grid pulsante, partículas flutuantes, transições suaves
- ✅ Navegação lateral rápida

## 📁 Estrutura

```
termux-tutoriais/
├── index.html   # Página principal (tudo em um arquivo)
└── README.md    # Este arquivo
```

## 🧠 Tutoriais incluídos

| Categoria | Quantidade |
|-----------|-----------|
| 🚀 Iniciante | 75 tutoriais |
| 🎵 Mídia & Áudio | 10+ |
| 📱 Termux API | 12+ |
| 🎮 Diversão | 10+ |
| ⚙️ Sistema | 15+ |
| 🌐 Web & Servidores | 15+ |
| 💻 Programação | 20+ |
| 🔗 Git & GitHub | 10+ |
| 🔐 SSH & Remoto | 6+ |
| 📡 Rede | 20+ |
| ☠️ Pentest & Hacking | 30+ |

## 📄 Licença

MIT — Sinta-se livre para usar, modificar e compartilhar.
