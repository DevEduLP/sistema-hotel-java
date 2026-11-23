# Sistema de Gerenciamento de Hotel (Java CLI)

Aplicação de console desenvolvida em Java puro para prática de **Programação Orientada a Objetos (POO)**, encapsulamento e manipulação de coleções em memória (`ArrayList`).
![Java](https://shields.io)

## Funcionalidades
- Cadastro de quartos (Simples, Duplo, Luxo)
- Listagem completa com status de disponibilidade
- Reserva de quarto por número
- Cancelamento de reserva

## Estrutura do Projeto
- `Quarto.java`: Entidade que representa o quarto e seus estados.
- `Hotel.java`: Classe de gerenciamento responsável pelas regras de negócio e lista de quartos.
- `Main.java`: Interface de interação via terminal (`Scanner`).

## Como Executar
Certifique-se de ter o **JDK 17+** instalado:
```bash
javac Main.java Hotel.java Quarto.java
java Main
