# Retificador-de-onda-completa
 
# Fonte de Alimentação 5V Regulada

![ESQUEMATICO](https://github.com/VictorJerba/Retificador-de-onda-completa/blob/main/Esquematico.jpeg)

Este circuito fornece uma saída estável de **5V DC** a partir de uma fonte de tensão AC ou DC. Ele é baseado no regulador **7805**, garantindo uma tensão segura para dispositivos eletrônicos.

## 📜 Funcionamento:
1. **Retificação**: A ponte de diodos converte AC para DC pulsante.
2. **Filtragem**: Capacitores reduzem o ripple e estabilizam a tensão.
3. **Regulação**: O **7805** mantém a saída fixa em **5V**.
4. **Indicação**: Um **LED** mostra quando a saída está ativa.

## 🛠️ Componentes:
- **BR1**: Ponte retificadora
- **C1, C2, C3**: Capacitores para filtragem
- **U1 (7805)**: Regulador de tensão 5V
- **R1 (200Ω), D1 (LED)**: Indicador de funcionamento
- **J1, J2**: Conectores de entrada e saída

## 📷 Esquemático:
(O esquema pode ser incluído como uma imagem aqui.)

Este projeto pode ser usado para alimentar microcontroladores, sensores e outros dispositivos que necessitam de **5V DC**.


# 💡 Fonte de Alimentação 5V Regulada - PCB Layout

Este projeto consiste em uma **fonte de alimentação de 5V DC** baseada no regulador **7805**, com retificação e filtragem para fornecer uma saída estável.

## 📌 Especificações do Layout da PCB:
- **Dimensões**: 50mm x 32mm
- **Camadas**: **1 camada** (face simples)
- **Roteamento**: Trilhas otimizadas para minimizar ruídos e interferências
- **Conectores**:
  - **Entrada (J2)**: Conector para alimentação AC/DC
  - **Saída (J1)**: Fornece 5V DC estabilizados
- **Componentes principais**:
  - **BR1**: Ponte retificadora para conversão AC-DC
  - **U1 (7805)**: Regulador de tensão de 5V
  - **C1, C2, C3**: Capacitores para filtragem e estabilidade da saída
  - **R1 e D1**: Resistor e LED para indicação de funcionamento

## 🖼️ Layout da Placa:
A imagem abaixo mostra o design da PCB no **Proteus**:

![PCB Layout](https://github.com/VictorJerba/Retificador-de-onda-completa/blob/main/PCB.jpeg)

- **Trilhas azuis** representam o lado de cobre (bottom layer).
- **Componentes estão na face superior** para facilitar a soldagem e montagem.
- **Os furos roxos** indicam os pontos de conexão dos componentes através da placa.

## 🏗️ Fabricação da PCB
Para produzir esta PCB, siga estas etapas:
1. **Exportar Gerber Files** para fabricação.
2. **Verificar as trilhas** e espaçamentos no Design Rule Check (DRC).
3. **Escolher o material da placa**, geralmente **FR4** de 1,6mm.
4. **Testar a montagem** antes de conectar cargas sensíveis.

Este projeto pode ser usado para alimentar circuitos como microcontroladores, sensores e outros dispositivos de baixa potência que necessitam de **5V DC regulados**.

---

Se precisar de ajustes ou personalizações no README, me avise! 🚀
