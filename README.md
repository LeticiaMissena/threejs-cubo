# 🧊 Cubo 3D Interativo com Three.js


## 📝 Descrição do Projeto

Esta aplicação web foi desenvolvida utilizando a biblioteca **Three.js** e tem como objetivo exibir um cubo em um ambiente 3D com câmera em perspectiva. O usuário pode interagir com a cena utilizando o mouse, permitindo rotacionar, aplicar zoom e movimentar a câmera.

A aplicação é **responsiva**, ajustando automaticamente a visualização quando a janela do navegador é redimensionada.

---

## 🛠️ Tecnologias Utilizadas

* **HTML5/ CSS3: Estrutura e estilização básica da página.**
* **JavaScript (ES6+): Lógica de animação e controle.**
* **Three.js: Engine 3D para manipulação de cenas, câmeras e geometrias.**
* **WebGL: API gráfica para renderização de alto desempenho via GPU.**

---

## 🎮 Funcionalidades
 A interação é gerenciada pelo módulo OrbitControls, permitindo que o usuário manipule a visão do objeto de forma intuitiva:

* **Exibição:** Cubo 3D com geometria e materiais.
* **Câmera:** Perspectiva (simula a visão humana).
* **Interação (OrbitControls):**
    * `Botão Esquerdo`: Rotacionar a câmera ao redor do cubo.
    * `Scroll`: Aplicar Zoom (aproximar ou afastar).
    * `Botão Direito`: Movimentação lateral/vertical (Pan).
    * `Responsividade`: Ajuste automático da visualização (Responsividade)
   
---

## 🏗️ Estrutura da Cena 3D

A arquitetura do sistema baseia-se em três componentes fundamentais:

1.  **Cena (Scene)**: O ambiente global onde o cubo e a iluminação são inseridos.
2.  **Câmera em Perspectiva**: Simula a percepção de profundidade do olho humano.


  `new THREE.PerspectiveCamera(75, aspect, 0.1, 1000)`
  
3.  **Renderizador (Renderer)**:O motor que processa os cálculos matemáticos e desenha os pixels via WebGL.

  
   `new THREE.WebGLRenderer()`

---

## 🚀 Como Executar o Projeto

Siga os passos abaixo para rodar a aplicação em sua máquina local:

1. **Clonar o Repositório** Abra o terminal (ou CMD) e utilize o comando para baixar os arquivos:
   
   git clone  (https://github.com/LeticiaMissena/threejs-cubo)

2.  **Acessar a Pasta Entre no diretório que foi criado após o clone**:
 `cd threejs-cubo`
 
3.  **Abrir a Aplicação Localize e abra o arquivo principal em qualquer navegador moderno (Chrome, Edge, Firefox ou Safari)**:
`index.html`

4. **Visualização do README Para ler a documentação técnica detalhada, consulte o arquivo:**
`README.md`

---
