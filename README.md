### Jogo de Combate em Turnos (Python)
Este é um projeto simples de um jogo de batalha em turnos desenvolvido em Python para exercitar conceitos fundamentais de Programação Orientada a Objetos (POO). No jogo, um herói controlado pelo usuário enfrenta um inimigo controlado pelo computador até que um dos dois fique sem vida.

## 📸 Demonstração

![Demonstração do jogo no terminal](<img src="assets/print_jogo.png" alt="Demonstração do jogo no terminal" width="800">)


#### 🚀 Funcionalidades:
Sistema de Classes: Utilização de herança para definir personagens, heróis e inimigos.
Encapsulamento: Atributos privados e métodos get para proteção de dados.
Combate Dinâmico: O dano dos ataques é calculado de forma aleatória com base no nível do personagem.
Ataque Especial: O herói possui uma habilidade única que causa dano superior ao ataque comum.
Interface via Console: Interação direta com o usuário através do terminal.

#### 🛠️ Conceitos de POO Aplicados
Herança: A classe Personagem serve como classe mãe para Heroi e Inimigo, compartilhando atributos como nome, vida e nível.
Polimorfismo: Sobrescrita do método exibir_detalhes para mostrar informações específicas de cada tipo de personagem.
Encapsulamento: Uso de prefixos __ (duplo underscore) para tornar os atributos privados.
Abstração: A classe Jogo orquestra a lógica da batalha sem que o usuário precise conhecer os detalhes internos de cada ataque.

#### 📋 Pré-requisitos
Você precisará ter o Python 3 instalado em sua máquina. Nenhuma biblioteca externa é necessária, pois o projeto utiliza apenas o módulo nativo random.

#### 🎮 Como Jogar
Clone este repositório ou copie o código para um arquivo chamado main.py.
Abra o terminal ou prompt de comando.
Execute o jogo com o comando:
bash
Copy
python main.py
Durante o seu turno, escolha entre:
1: Ataque Normal.
2: Ataque Especial (Habilidade Única).
O jogo termina quando a vida do Herói ou do Inimigo chegar a 0.

#### 🏗️ Estrutura do Código
Personagem: Classe base com atributos de vida, nome e nível.
Heroi: Classe derivada que inclui o método ataque_especial.
Inimigo: Classe derivada que representa o oponente.
Jogo: Classe responsável por gerenciar os turnos e as condições de vitória/derrota.