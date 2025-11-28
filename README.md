Calculadora de Partidas Rankeadas 🎮
Projeto desenvolvido a partir do desafio da DIO para praticar lógica de programação e fundamentos de JavaScript, calculando o saldo de partidas ranqueadas de um jogador e classificando seu nível com base na quantidade de vitórias.​

🎯 Objetivo
Criar uma função que receba como parâmetros a quantidade de vitórias e derrotas de um jogador, calcule o saldo de Rankeadas (vitórias - derrotas) e determine o nível do herói conforme a regra abaixo:​

Menos de 10 vitórias → Ferro

Entre 11 e 20 vitórias → Bronze

Entre 21 e 50 vitórias → Prata

Entre 51 e 80 vitórias → Ouro

Entre 81 e 90 vitórias → Diamante

Entre 91 e 100 vitórias → Lendário

Maior ou igual a 101 vitórias → Imortal



🧠 Tecnologias e Conceitos Utilizados
Linguagem: JavaScript

Conceitos praticados:

Variáveis

Operadores aritméticos e relacionais

Estruturas de decisão (if / else if / else)

Funções

(Opcional) Laços de repetição para testar vários cenários

🧪 Exemplo de Uso

const vitorias = 75;
const derrotas = 20;

// Funções calcularSaldo e classificarNivel implementadas no código
const saldoVitorias = calcularSaldo(vitorias, derrotas);
const nivel = classificarNivel(vitorias);

console.log(`O Herói tem de saldo de ${saldoVitorias} está no nível de ${nivel}`);
Saída esperada:

O Herói tem de saldo de 55 está no nível de Ouro

🚀 Como Executar
Clone este repositório:

bash
git clone https://github.com/SEU-USUARIO/NOME-DO-REPOSITORIO.git
Abra o projeto em seu editor (ex.: VS Code).

Certifique-se de ter o Node.js instalado (ou use o console do navegador).

