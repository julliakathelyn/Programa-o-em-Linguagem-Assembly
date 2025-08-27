# 💻 Trabalho Avaliativo - Sistemas Computacionais e Segurança (SCS)

## 📚 Contexto
Este repositório contém a resolução do **Trabalho Avaliativo A3** da disciplina **Sistemas Computacionais e Segurança**, desenvolvido no curso de **Sistemas de Informação (UAM - Mooca)** no **1º semestre**.  

O objetivo foi elaborar um **Programa Fonte em Linguagem Assembly** para executar operações aritméticas utilizando o **VNSimulator** (Máquina de Von Neumann). O programa completo pode ser **visualizado** no arquivo TRABALHO SCS - prints durante a execução.pdf.

🔗 Link do simulador: [VNSimulator](https://vnmsim.vercel.app/en-us)  

---

## 📑 Objetivo do Trabalho
O grupo deveria:  
- Desenvolver um **programa em Assembly** que executasse operações de soma, subtração, multiplicação e divisão.  
- Simular o funcionamento no **VNSimulator**.  
- Fornecer prints das execuções e explicar o que acontece em cada etapa em relação aos barramentos e elementos internos do sistema (IR, Decoder, ALU, ACC, PC, Memory Cells e Variables).  
- Entregar o código, relatório e arquivo de simulação.  

---

## ⚙️  Exemplo de instruções utilizadas:  
```asm
LOD T2      // Carrega o valor de T2 no acumulador
MUL T3      // Multiplica o acumulador pelo valor de T3
STO W       // Armazena o resultado em W
...
HLT         // Finaliza a execução do programa

``` 

## 💻 Explicação do comportamento:

- ULA (ALU) – responsável pelas operações matemáticas.
- ACC (Acumulador) – registrador principal.
- PC (Program Counter) – contador de instruções.
- IR (Instruction Register) e Decoder – responsáveis pela leitura e interpretação das instruções.
- RAM e Variáveis (X, Y, Z, W, T1, T2, T3, T4) – memória utilizada no programa.

## 📊 Estrutura do Projeto

- Alunos-grupo 15.pdf → Documento com enunciado do trabalho.
- TRABALHO-SCS-prints-durante-a-execução.pdf → Programa em Assembly, prints e explicações.
- código desenvolvido.json → Arquivo com as respostas

---

