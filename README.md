# CAIXA-PULANTE

## Sobre o Projeto

Este projeto consiste em uma simulação interativa e visual onde uma caixa (bloco) se movimenta de forma autônoma pela tela, ricocheteando nas bordas do cenário. A aplicação foi desenvolvida utilizando HTML, CSS e a biblioteca **p5.js** junto com a extensão **p5.play** para gerenciar a física de movimento, os vetores de velocidade e as colisões em tempo real.

O diferencial do sistema está na interação dinâmica com o cenário: a tela conta com retângulos de cores diferentes e, sempre que a caixa toca em um desses blocos coloridos, ela altera sua própria cor dinamicamente, criando um efeito visual contínuo e aleatório.

---

## Funcionalidades

* Movimentação autônoma e aleatória da caixa pelo canvas.
* Sistema de física para detecção de bordas (bounce), fazendo com que a caixa ricocheteie ao tocar nos limites da tela.
* Renderização de obstáculos ou regiões retangulares coloridas no cenário.
* Mudança dinâmica de cor do elemento principal (caixa) baseada no bloco colorido detectado no momento do toque.
* Renderização otimizada em tempo real com base no ecossistema da biblioteca p5.js.

---

## Tecnologias Utilizadas

* **HTML5**
* **CSS3**
* **p5.js**
* **p5.play.js**

---

## Objetivo

O principal objetivo deste projeto é explorar conceitos fundamentais de física de jogos e computação gráfica bidimensional, aplicando algoritmos de colisão simples (AABB bounding boxes), inversão de vetores de velocidade para simular ricochetes e mapeamento de propriedades visuais através do monitoramento contínuo de interações entre sprites.

---

## Aprendizados

Durante o desenvolvimento deste projeto, foram aplicados conceitos como:

* Manipulação de vetores de velocidade e direção para movimentação contínua e autônoma de sprites.
* Aplicação de lógica condicional para detectar colisões com as bordas do canvas (`windowWidth` / `windowHeight`) e inverter a trajetória do objeto.
* Utilização de métodos de detecção de sobreposição e colisão entre múltiplos objetos usando a extensão `p5.play`.
* Gerenciamento e atualização de variáveis de cor em tempo real baseadas em gatilhos (triggers) de eventos de colisão.
* Estruturação limpa do ciclo de vida do jogo usando as funções nativas `setup()` e `draw()`.

---

## Como Executar

1. Clone este repositório:
```bash
git clone [https://github.com/seu-usuario/CAIXA-PULANTE.git](https://github.com/seu-usuario/CAIXA-PULANTE.git)
```

2. Acesse a pasta do projeto:

```bash
cd CAIXA-PULANTE
```

3. Abra o arquivo index.html em seu navegador de preferência para visualizar a simulação.

## Estrutura do Projeto

```text
CAIXA-PULANTE/
│
├── scripts/
│   ├── p5.js
│   ├── p5.play.js
│   └── sketch.js
│
├── style/
│   └── style.css
│
├── index.html
└── README.md
```
---

## Licença
Este projeto foi desenvolvido exclusivamente para fins educacionais e de aprendizado.

Desenvolvido como prática de lógica de programação e física de jogos, simulando o comportamento de ricochete e colisão colorida com p5.js.
