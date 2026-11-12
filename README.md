# 🚌 JPBus — Sistema Inteligente de Monitoramento do Transporte Público

## 📌 Sobre o projeto

O **JPBus** é um projeto acadêmico que propõe melhorias para o transporte público de João Pessoa, Paraíba, por meio da tecnologia e da comunicação entre passageiros, motoristas e uma central de monitoramento.

A proposta consiste em desenvolver um sistema próprio para acompanhar a localização dos ônibus, calcular previsões de chegada e informar os passageiros sobre atrasos, ocorrências e alterações no transporte público.

O projeto apresenta soluções como rastreamento GPS, tablets para motoristas e painéis digitais nas paradas de ônibus.

## 🎯 Objetivos

- Melhorar a comunicação entre passageiros e motoristas.
- Facilitar o acompanhamento dos ônibus.
- Oferecer previsões de chegada mais precisas.
- Informar sobre atrasos e imprevistos.
- Modernizar a comunicação nas paradas de ônibus.
- Proporcionar mais transparência e organização no transporte público.

## ⚙️ Funcionalidades propostas

### 1. Rastreamento GPS

Utilização de rastreadores GPS instalados nos ônibus para identificar sua localização durante o percurso.

As informações coletadas poderão ser utilizadas para calcular distâncias, velocidades e previsões de chegada às próximas paradas.

### 2. Tablet para os motoristas

Implementação de tablets no interior dos ônibus para permitir que os motoristas comuniquem ocorrências à central de monitoramento.

Entre as ocorrências previstas estão:

- Acidentes.
- Congestionamentos.
- Problemas mecânicos.
- Bloqueios nas vias.
- Alterações no trajeto.
- Atrasos e outros imprevistos.

### 3. Painéis digitais nas paradas

Instalação de painéis digitais nas paradas de ônibus, com funcionamento previsto durante 24 horas.

Os painéis poderão apresentar:

- Linhas e destinos dos ônibus.
- Previsões de chegada.
- Informações sobre atrasos.
- Avisos de acidentes e interrupções.
- Atualizações sobre o funcionamento das linhas.

### 4. Sistema de cálculo da previsão de chegada

O sistema propõe utilizar informações dos rastreadores GPS e das ocorrências comunicadas pelos motoristas para estimar o tempo de chegada dos ônibus.

A fórmula básica utilizada como referência é:

**Tempo estimado = Distância ÷ Velocidade média**

O cálculo também poderá considerar as condições do trânsito e outros acontecimentos que possam alterar o tempo do percurso.

### 5. Aplicativo para passageiros

Como possibilidade de expansão futura, o projeto prevê o desenvolvimento de um aplicativo para dispositivos móveis, permitindo que os passageiros acompanhem os ônibus diretamente pelo celular.

## 🔄 Como o sistema funcionará?

1. O rastreador GPS identifica a localização do ônibus.
2. As informações são encaminhadas para a central de monitoramento.
3. O motorista poderá informar ocorrências utilizando o tablet.
4. O sistema processa os dados e calcula a previsão de chegada.
5. As informações atualizadas são disponibilizadas nos painéis digitais.
6. Futuramente, os passageiros também poderão consultar os dados pelo aplicativo.

## 🛠️ Tecnologias utilizadas

- **HTML5:** estruturação das páginas e organização do conteúdo.
- **CSS3:** estilização, identidade visual e organização dos elementos.
- **Visual Studio Code:** ambiente utilizado no desenvolvimento.

## 📁 Estrutura do projeto

```text
JPBus/
│
├── assets/
│   ├── css/
│   │   ├── home.css
│   │   ├── style.css
│   │   └── tela-parada.css
│   │
│   ├── images/
│   │
│   └── video/
│       └── .gitkeep
│
├── html/
│   ├── telas-ficticias/
│   │
│   ├── calculos.html
│   ├── home.html
│   ├── paineis-parada.html
│   └── telas-onibus2.html
│
└── README.md
```

## 📄 Páginas do projeto

| Arquivo | Descrição |
|---|---|
| `home.html` | Página principal de apresentação do JPBus. |
| `calculos.html` | Explicação dos cálculos utilizados para estimar a chegada dos ônibus. |
| `paineis-parada.html` | Apresentação da proposta dos painéis digitais nas paradas. |
| `telas-onibus2.html` | Apresentação das telas e funcionalidades relacionadas aos ônibus. |
| `telas-ficticias/` | Diretório destinado às telas ilustrativas do projeto. |

## 🚀 Como executar o projeto

1. Baixe ou clone o repositório.
2. Abra a pasta `JPBus` no Visual Studio Code.
3. Localize a pasta `html`.
4. Abra o arquivo `home.html` no navegador.
5. Para facilitar a visualização, também é possível utilizar a extensão Live Server.

## 🌱 Possibilidades futuras

- Desenvolvimento de uma central de monitoramento.
- Integração com rastreadores GPS.
- Implementação do sistema de comunicação dos motoristas.
- Instalação dos painéis digitais nas paradas.
- Desenvolvimento de um aplicativo para passageiros.
- Integração com informações sobre o trânsito.

## 👥 Sobre o projeto

O JPBus é um projeto acadêmico voltado à inovação tecnológica e à melhoria da mobilidade urbana em João Pessoa, Paraíba.

**JPBus — Mais informação, comunicação e eficiência no transporte público.**
