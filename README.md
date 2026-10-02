# GAAL Sims — Simulações Interativas de Geometria Analítica & Álgebra Linear 3D

[![GitHub Pages](https://img.shields.io/badge/Demo-GitHub%20Pages-06b6d4?style=for-the-badge&logo=github)](https://sandrobenigno.github.io/GAAL_Sims/)
[![Three.js](https://img.shields.io/badge/3D%20Engine-Three.js%20r128-black?style=for-the-badge&logo=three.js)](https://threejs.org/)
[![KaTeX](https://img.shields.io/badge/Math-KaTeX-00d084?style=for-the-badge&logo=latex)](https://katex.org/)
[![Tailwind CSS](https://img.shields.io/badge/Styling-Tailwind%20CSS-38bdf8?style=for-the-badge&logo=tailwindcss)](https://tailwindcss.com/)

> **By Sandro Benigno (EvilPlaymobil)**  
> *Ambiente educacional aberto e interativo para visualização em tempo real de conceitos fundamentais de Geometria Analítica e Álgebra Linear (GAAL).*

🔗 **Acesse as simulações online:** [https://sandrobenigno.github.io/GAAL_Sims/](https://sandrobenigno.github.io/GAAL_Sims/)

---

## 🎯 Sobre o Projeto

O **GAAL Sims** é uma suíte de laboratórios visuais projetada para transformar o aprendizado abstrato de Álgebra Linear e Geometria Analítica em uma experiência visual, tangível e intuitiva. 

O módulo inicial é focado em **Vetores no Espaço Euclidiano $\mathbb{R}^3$**, cobrindo a jornada matemática que parte da definição e normalização de vetores unitários até sistemas de coordenadas esféricas e navegação angular tridimensional.

---

## 🧭 Coleção 1: Vetores no Espaço Euclidiano $\mathbb{R}^3$

| Módulo | Descrição | Equação Principal | Link Direto |
| :--- | :--- | :---: | :---: |
| 🌐 **Hub Principal** | Portal integrador com visão geral e trilha didática | — | [Acessar Hub](https://sandrobenigno.github.io/GAAL_Sims/index.html) |
| 🚀 **Parte 1** | **Vetor Unitário & Normalização 3D**<br>Preservação da direção com módulo fixado em 1 na esfera unitária | $$\mathbf{\hat{v}} = \frac{\mathbf{v}}{\|\mathbf{v}\|}$$ | [Abrir Parte 1](https://sandrobenigno.github.io/GAAL_Sims/parte1.html)<br>📖 [Artigo Teórico](https://sandrobenigno.com.br/post.php?id=666) |
| 📐 **Parte 2** | **Vetor entre Dois Pontos & Distância Euclidiana**<br>Deslocamento relativo $\vec{AB}$, caixa de deltas e métrica 3D | $$d = \sqrt{\Delta x^2 + \Delta y^2 + \Delta z^2}$$ | [Abrir Parte 2](https://sandrobenigno.github.io/GAAL_Sims/parte2.html) |
| 🎯 **Parte 3** | **Cossenos Diretores & Ângulos no Espaço**<br>Projeção angular nos eixos $(\alpha, \beta, \gamma)$ e a identidade fundamental | $$\sum \cos^2\theta_i = 1$$ | [Abrir Parte 3](https://sandrobenigno.github.io/GAAL_Sims/parte3.html) |
| 🧭 **Parte 4** | **Azimute & Elevação: Coordenadas Esféricas**<br>Navegação esférica com ângulo polar horizontal $\theta$ e inclinação vertical $\phi$ | $$\begin{cases}x = r\cos\phi\cos\theta\\y = r\cos\phi\sin\theta\\z = r\sin\phi\end{cases}$$ | [Abrir Parte 4](https://sandrobenigno.github.io/GAAL_Sims/parte4.html) |

---

## 🔬 Detalhamento dos Módulos

### 1. [Vetor Unitário & Normalização 3D](https://sandrobenigno.github.io/GAAL_Sims/parte1.html)
- 📖 **Artigo Explicativo**: [Leia o texto teórico completo no blog do autor](https://sandrobenigno.com.br/post.php?id=666)
- **Objetivo**: Demonstrar que normalizar um vetor consiste em escalonar seu comprimento para $1.0$ sem alterar seu sentido e direção fundamentais.
- **Destaques**:
  - Esfera unitária translúcida com anel equatorial indicativo ($r = 1$).
  - Projeções ortogonais aos planos e cálculo simultâneo da norma euclidiana $\|\mathbf{v}\| = \sqrt{x^2+y^2+z^2}$.
  - Sliders com enquadramento adaptativo de câmera e grid ground dinâmico.

### 2. [Vetor entre Dois Pontos & Distância Euclidiana](https://sandrobenigno.github.io/GAAL_Sims/parte2.html)
- **Objetivo**: Estudo do vetor relativo formado por dois pontos arbitrários $A(x_A, y_A, z_A)$ e $B(x_B, y_B, z_B)$ no espaço.
- **Destaques**:
  - Manipulação independente dos pontos de origem $A$ (vermelho/rosa) e destino $B$ (azul celeste).
  - Decomposição em degraus ortogonais $\Delta x, \Delta y, \Delta z$ (caixa volumétrica tridimensional).
  - Derivação analítica em tempo real da distância $d(A, B)$ e do vetor unitário diretor $\mathbf{\hat{u}}_{AB}$.

### 3. [Cossenos Diretores & Ângulos no Espaço](https://sandrobenigno.github.io/GAAL_Sims/parte3.html)
- **Objetivo**: Comprovar geometricamente por que as coordenadas cartesianas do vetor unitário $\mathbf{\hat{v}} = (\hat{v}_x, \hat{v}_y, \hat{v}_z)$ equivalem exatamente aos cossenos diretores $(\cos\alpha, \cos\beta, \cos\gamma)$.
- **Destaques**:
  - Setores circulares translúcidos e coloridos para cada ângulo diretor: $\alpha$ ($+X$), $\beta$ ($+Y$) e $\gamma$ ($+Z$).
  - Verificação analítica contínua da identidade pitagórica tridimensional $\cos^2\alpha + \cos^2\beta + \cos^2\gamma = 1$.
  - Projeções vetoriais independentes para o vetor original e para o vetor unitário.

### 4. [Azimute & Elevação (Coordenadas Esféricas)](https://sandrobenigno.github.io/GAAL_Sims/parte4.html)
- **Objetivo**: Conectar o sistema cartesiano à intuição física e astronômica de coordenadas esféricas locais.
- **Destaques**:
  - **Azimute ($\theta$)**: Ângulo no plano horizontal $XY$ em relação ao eixo $+X$ em direção ao eixo de profundidade $+P$ (ou $+Y$).
  - **Elevação ($\phi$)**: Ângulo vertical formado entre a sombra no plano horizontal e o eixo de altura vertical $+A$ (ou $+Z$).
  - Projeção horizontal $r = \sqrt{\Delta x^2 + \Delta y^2}$ com setor em leque dinâmico.
  - Botão de alternância instantânea para **Vista Superior 2D** (plano de azimute).

---

## 💡 Recursos & Diferenciais Técnicos

- **Grid & Eixos Adaptativos em Tempo Real**:
  A dimensão do grid e o comprimento dos eixos se ajustam com fórmula paramétrica $R = \max(2, \lceil\max(|x|, |y|, |z|)\rceil + 1)$, garantindo sempre $1\text{ u}$ de respiro ao redor do vetor.
- **Auto-Zoom Inteligente**:
  O enquadramento da câmera é recalculado de maneira fluida e suave apenas quando os sliders alteram a escala do grid, cancelando a transição no instante em que o usuário manipula a cena manualmente.
- **Design Glassmorphism Dark**:
  Painel de controles à esquerda com barra de rolagem vertical centralizada em degradê, permitindo foco e legibilidade em monitores widescreen e dispositivos móveis.
- **Renderização Matemática Impecável**:
  Todas as fórmulas e passos algébricos são calculados dinamicamente com [KaTeX](https://katex.org/), sem atrasos e com fidelidade tipográfica rigorosa.
- **Zero Dependência de Build / 100% Client-Side**:
  Arquivos HTML puros e autossuficientes utilizando CDNs confiáveis (Three.js, KaTeX, Tailwind CSS). Podem ser executados diretamente no navegador ou via GitHub Pages sem necessidade de Node.js, compilação ou servidores de aplicação.

---

## 🛠️ Tecnologias Utilizadas

- **WebGL / 3D Graphics**: [Three.js r128](https://threejs.org/) + `OrbitControls.js`
- **Renderização de Fórmulas Matemáticas**: [KaTeX 0.16.8](https://katex.org/) (com Auto-Render extension)
- **Estilização & Responsividade**: [Tailwind CSS CDN](https://tailwindcss.com/)
- **Hospedagem & CI/CD**: [GitHub Pages](https://pages.github.com/)

---

## 📄 Licença e Créditos

Desenvolvido com carinho para a comunidade acadêmica e entusiastas de matemática por **Sandro Benigno (EvilPlaymobil)**.

Distribuído sob a licença **MIT**. Sinta-se livre para utilizar, expandir e incorporar em suas aulas ou estudos!
