# 🌾 O Fazendeiro, O Lobo, O Cordeiro e O Feno

Um jogo interativo de lógica baseado no clássico problema de travessia do rio, desenvolvido com HTML, CSS e JavaScript puro.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## 🚀 Acesso Rápido

- **🌐 Jogar Online**: Acesse através do [GitHub Pages](https://prof-raimundo.github.io/go-devs-the-farmer/)
- **📁 Estrutura do Projeto**: 
  - `index.html` - Página inicial com botão para iniciar o jogo
  - `docs/jogar.html` - Jogo principal

## 📖 Sobre o Jogo

Este é um jogo de lógica clássico onde você precisa ajudar um fazendeiro a atravessar um rio com um lobo, um cordeiro e um feno. O desafio é fazer isso sem deixar que o lobo coma o cordeiro ou que o cordeiro coma o feno!

## 🎯 Regras do Jogo

1. **Capacidade do Barco**: O barco só pode carregar o fazendeiro e mais um item por vez
2. **Proteção Necessária**: 
   - ⚠️ Se o lobo ficar sozinho com o cordeiro, o lobo come o cordeiro!
   - ⚠️ Se o cordeiro ficar sozinho com o feno, o cordeiro come o feno!
3. **Objetivo**: Leve todos (fazendeiro, lobo, cordeiro e feno) para a margem direita com segurança

### 💡 Dica

A solução ideal requer **7 movimentos**. Tente encontrar a sequência perfeita!

## 📁 Estrutura do Projeto

```
go-devs-the-farmer/
│
├── index.html          # Página inicial (GitHub Pages)
├── README.md           # Este arquivo
└── docs/
    └── jogar.html      # Jogo principal
```

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura semântica
- **CSS3**: Estilização moderna com animações e gradientes
- **JavaScript (Vanilla)**: Lógica do jogo sem dependências externas

## 📦 Como Executar Localmente

1. Clone o repositório:
```bash
git clone https://github.com/prof-raimundo/go-devs-the-farmer.git
```

2. Navegue até o diretório:
```bash
cd go-devs-the-farmer
```

3. Abra o arquivo `index.html` no seu navegador ou use um servidor local:

### 🌐 Usando um Servidor Local

#### Python:
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

#### Node.js (com http-server):
```bash
npx http-server
```

#### PHP:
```bash
php -S localhost:8000
```

Depois acesse: `http://localhost:8000/`

## 🎮 Características

- ✨ **Interface Visual Moderna**: Design responsivo com gradientes e animações suaves
- 🎯 **Feedback Interativo**: Animações e mensagens claras para cada ação
- 🎉 **Celebração de Vitória**: Efeitos visuais comemorativos quando você completa o jogo
- ⚠️ **Sistema de Erros**: Feedback visual detalhado quando você comete um erro
- 📱 **Responsivo**: Funciona perfeitamente em desktop, tablet e mobile
- 🎨 **Animações Fluidas**: Transições suaves e efeitos visuais atraentes
- 🏆 **Sistema de Pontuação**: Avaliação de desempenho baseada no número de movimentos

## 📱 Compatibilidade

- ✅ Chrome/Edge (recomendado)
- ✅ Firefox
- ✅ Safari
- ✅ Opera
- ✅ Navegadores móveis (iOS Safari, Chrome Mobile)

## 🤝 Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para:

1. Fazer um Fork do projeto
2. Criar uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abrir um Pull Request

## 📝 Licença

Este projeto está sob a licença MIT.

## 👨‍💻 Autor

Desenvolvido com ❤️ para praticar lógica e programação web.

## 🙏 Agradecimentos

- Inspirado no clássico problema de lógica "O Lobo, a Cabra e o Repolho"
- Design moderno e interativo para tornar o aprendizado divertido

---

⭐ Se você gostou do projeto, considere dar uma estrela! ⭐


