# 🌾 O Fazendeiro, O Lobo, O Cordeiro e O Feno

Um jogo interativo de lógica baseado no clássico problema de travessia do rio, desenvolvido com HTML, CSS e JavaScript puro.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## 📖 Sobre o Jogo

Este é um jogo de lógica clássico onde você precisa ajudar um fazendeiro a atravessar um rio com um lobo, um cordeiro e um feno. O desafio é fazer isso sem deixar que o lobo coma o cordeiro ou que o cordeiro coma o feno!

## 🎮 Características

- ✨ **Interface Visual Moderna**: Design responsivo com gradientes e animações suaves
- 🎯 **Feedback Interativo**: Animações e mensagens claras para cada ação
- 🎉 **Celebração de Vitória**: Efeitos visuais comemorativos quando você completa o jogo
- ⚠️ **Sistema de Erros**: Feedback visual detalhado quando você comete um erro
- 📱 **Responsivo**: Funciona perfeitamente em desktop, tablet e mobile
- 🎨 **Animações Fluidas**: Transições suaves e efeitos visuais atraentes
- 🏆 **Sistema de Pontuação**: Avaliação de desempenho baseada no número de movimentos

## 🎯 Regras do Jogo

1. **Capacidade do Barco**: O barco só pode carregar o fazendeiro e mais um item por vez
2. **Proteção Necessária**: 
   - ⚠️ Se o lobo ficar sozinho com o cordeiro, o lobo come o cordeiro!
   - ⚠️ Se o cordeiro ficar sozinho com o feno, o cordeiro come o feno!
3. **Objetivo**: Leve todos (fazendeiro, lobo, cordeiro e feno) para a margem direita com segurança

## 🚀 Como Jogar

1. **Clique nos personagens** para colocá-los no barco
2. **Clique em "Atravessar Rio"** para mover o barco para a outra margem
3. **Repita** até que todos estejam na margem direita
4. **Evite deixar** o lobo sozinho com o cordeiro ou o cordeiro sozinho com o feno!

### 💡 Dica

A solução ideal requer **7 movimentos**. Tente encontrar a sequência perfeita!

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura semântica
- **CSS3**: Estilização moderna com animações e gradientes
- **JavaScript (Vanilla)**: Lógica do jogo sem dependências externas

## 📦 Instalação

1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/o-fazendeiro-jogo.git
```

2. Navegue até o diretório:
```bash
cd o-fazendeiro-jogo
```

3. Abra o arquivo `theFarmer.html` no seu navegador:
   - **Método 1**: Clique duplo no arquivo
   - **Método 2**: Arraste o arquivo para o navegador
   - **Método 3**: Use um servidor local (recomendado para desenvolvimento)

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

Depois acesse: `http://localhost:8000/theFarmer.html`

## 📁 Estrutura do Projeto

```
o-fazendeiro-jogo/
│
├── theFarmer.html      # Arquivo principal do jogo
└── README.md           # Documentação do projeto
```

## 🎨 Funcionalidades Detalhadas

### Sistema de Feedback Visual

- **Animações de Erro**: 
  - Tremor (shake) em elementos quando há ação inválida
  - Destaque vermelho nos personagens problemáticos
  - Margem problemática destacada com borda vermelha

- **Modal de Game Over**:
  - Aparece quando você comete um erro fatal
  - Mostra qual regra foi violada
  - Opção de tentar novamente ou fechar

### Sistema de Celebração

- **Ao Completar o Jogo**:
  - 🎊 150 confetes coloridos caindo pela tela
  - 🎆 20 fogos de artifício explodindo
  - 🎉 Personagens pulando e girando
  - 🌈 Título com animação de arco-íris
  - 📳 Vibração no dispositivo (se disponível)

- **Avaliação de Desempenho**:
  - **7 movimentos**: ⭐ Perfeito! Você encontrou a solução ideal!
  - **≤10 movimentos**: 🏆 Excelente trabalho!
  - **≤15 movimentos**: 👏 Muito bom!
  - **>15 movimentos**: 💪 Bom trabalho! Continue praticando!

## 🎮 Controles

- **Clique**: Seleciona/move personagens
- **Botão "Atravessar Rio"**: Move o barco para a outra margem
- **Botão "Reiniciar Jogo"**: Reseta o jogo para o estado inicial

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

Este projeto está sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

## 👨‍💻 Autor

Desenvolvido com ❤️ para praticar lógica e programação web.

## 🙏 Agradecimentos

- Inspirado no clássico problema de lógica "O Lobo, a Cabra e o Repolho"
- Design moderno e interativo para tornar o aprendizado divertido

## 📸 Screenshots

*(Adicione screenshots do jogo aqui)*

## 🔮 Melhorias Futuras

- [ ] Sistema de níveis com diferentes desafios
- [ ] Modo multiplayer
- [ ] Ranking de melhores tempos
- [ ] Mais personagens e regras
- [ ] Modo tutorial interativo
- [ ] Sons e música de fundo
- [ ] Temas visuais alternativos

## 📞 Suporte

Se você encontrar algum bug ou tiver sugestões, por favor abra uma [issue](https://github.com/seu-usuario/o-fazendeiro-jogo/issues).

---

⭐ Se você gostou do projeto, considere dar uma estrela! ⭐

