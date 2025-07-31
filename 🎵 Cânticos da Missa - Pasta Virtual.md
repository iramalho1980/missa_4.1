# 🎵 Cânticos da Missa - Pasta Virtual

Uma aplicação web moderna para organizar e acompanhar os cânticos durante a celebração da missa.

## ✨ Características

- **Design Moderno**: Interface com gradiente preto e amarelo prateado, efeitos glass e cantos arredondados
- **Organização por Ordem de Missa**: Cânticos organizados na sequência litúrgica
- **Funcionalidades Interativas**:
  - Visualização de PDFs em popup
  - Marcação de cânticos como realizados
  - Expansão/recolhimento de cards
  - Barra de progresso da missa
  - Persistência de estado no localStorage

## 📋 Cânticos Incluídos

1. **Entrada** - Eis-me Aqui, Senhor
2. **Ato Penitencial** - Pelos Pecados
3. **Gloria** - Gloria ao Pai Criador
4. **Salmo** - Salmo 32 - Feliz o Povo
5. **Aclamação** - A Minha Alma Abrirei
6. **Ofertório** - Meu Coração É Para Ti
7. **Santo** - Santo, Santo É
8. **Cordeiro** - Cordeiro de Deus que Tirais
9. **Comunhão** - Este Pranto em Minhas Mãos
10. **Final** - Anjos de Deus
11. **Amém** - Aaaamém

## 🚀 Como Usar

1. Abra o arquivo `index.html` no seu navegador
2. Use os botões "Expandir Todos" ou "Recolher Todos" para controlar a visualização
3. Clique no botão ▼ em cada card para expandir/recolher individualmente
4. Clique em "Ver PDF" para visualizar a partitura completa
5. Use "Marcar como Realizado" para acompanhar o progresso da missa
6. A barra de progresso mostra quantos cânticos foram realizados

## 📁 Estrutura do Projeto

```
missa_4.1/
├── index.html              # Aplicação principal
├── upload/                 # Diretório com os PDFs dos cânticos
│   ├── Entrada-Eis-meAqui,Senhor.pdf
│   ├── AtoPenitencial-PelosPecados.pdf
│   └── ... (outros PDFs)
├── letras-canticos.json    # Dados estruturados das letras
└── README.md              # Este arquivo
```

## 💾 Persistência de Dados

A aplicação salva automaticamente no localStorage do navegador:
- Quais cânticos foram marcados como realizados
- Quais cards estão expandidos ou recolhidos

## 🎨 Design

- **Gradiente de fundo**: Preto para amarelo prateado
- **Efeitos glass**: Backdrop blur nos cards
- **Cantos arredondados**: Design moderno e suave
- **Detalhes em amarelo neon**: Acentos vibrantes
- **Responsivo**: Funciona em desktop e mobile

## 🛠️ Tecnologias

- HTML5
- CSS3 (com backdrop-filter e gradientes)
- JavaScript vanilla
- localStorage para persistência

---

Desenvolvido para facilitar o acompanhamento dos cânticos durante a celebração da missa.

