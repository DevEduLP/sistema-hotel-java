# Sistema de Gerenciamento de Hotel (Java CLI)

![Java](https://img.shields.io/badge/Java-21%2B-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)

Aplicação de console desenvolvida em Java puro para prática de **Programação Orientada a Objetos (POO)**, encapsulamento e manipulação de coleções em memória (`ArrayList`).

## Funcionalidades
- Cadastro de quartos (Simples, Duplo, Luxo)
- Listagem completa com status de disponibilidade
- Reserva de quarto por número
- Cancelamento de reserva

## Estrutura do Projeto
- `src/Quarto.java`: Entidade que representa o quarto e seus estados.
- `src/Hotel.java`: Classe de gerenciamento responsável pelas regras de negócio e lista de quartos.
- `src/Main.java`: Interface de interação via terminal (`Scanner`).

## Como Executar
Certifique-se de ter o **JDK 17+** instalado e execute a partir da raiz do projeto:
```bash
javac -d bin src/*.java
java -cp bin Main
