# 🎬 ScreenMatch - Projeto de Programação Orientada a Objetos em Java

![Java](https://img.shields.io/badge/Java-17%2B-blue)
![POO](https://img.shields.io/badge/Programa%C3%A7%C3%A3o%20Orientada%20a%20Objetos-4%20Pilares-green)
![Alura](https://img.shields.io/badge/Curso-Alura-yellow)

Este repositório contém meus aprendizados, códigos e reflexões sobre os conceitos fundamentais da Programação Orientada a Objetos (POO) em Java, desenvolvidos no projeto **ScreenMatch** durante o curso da Alura.

## 📚 Conteúdo do Curso

| Módulo |              Descrição              |                   Conceitos-chave                   |
| :----: | :---------------------------------: | :-------------------------------------------------: |
|   1️⃣   |           Pilares da POO            |  Abstração, Encapsulamento, Herança, Polimorfismo   |
|   2️⃣   |        Modelagem de Classes         |     Atributos, Métodos, Organização em Pacotes      |
|   3️⃣   | Encapsulamento e Controle de Acesso |           `private`, `getters`, `setters`           |
|   4️⃣   |      Herança e Especialização       |     `extends`, `super`, sobrescrita de métodos      |
|   5️⃣   |      Polimorfismo e Interfaces      | Reaproveitamento e especialização de comportamentos |

## 🏛️ Os 4 Pilares da POO

- **Encapsulamento** → Protege os dados da classe, controlando o acesso aos atributos.
- **Herança** → Permite que classes compartilhem atributos e comportamentos, evitando código duplicado.
- **Abstração** → Cria representações genéricas para objetos do mundo real.
- **Polimorfismo** → Permite que métodos se comportem de maneira diferente conforme a subclasse.

## 💻 Exemplos Práticos

### 📺 Modelagem de Filmes e Séries

```java
public class Filme extends Titulo {
    private String diretor;

    @Override
    public int getClassificacao() {
        return (int) pegaMedia() / 2;
    }
}
```

### 🎞️ Calculadora de Tempo

```java
public class CalculadoraDeTempo {
    private int tempoTotal;

    public void inclui(Titulo titulo) {
        this.tempoTotal += titulo.getDuracaoEmMinutos();
    }
}
```

### ⭐ Filtro de Recomendação (Interface)

```java
public interface Classificavel {
    int getClassificacao();
}
```

## 🎯 Aprendizados

- Aplicação prática dos quatro pilares da POO.
- Organização do código em pacotes e classes especializadas.
- Criação e uso de **interfaces** para contratos de comportamento.
- Implementação de **polimorfismo** utilizando referências genéricas.
- Boas práticas de encapsulamento e acesso controlado a atributos.

## 🔍 Reflexões

Trabalhar com POO através do projeto ScreenMatch foi essencial para entender como organizar melhor o código, promover reuso e criar sistemas mais flexíveis e fáceis de manter.  
A prática dos conceitos de **herança**, **polimorfismo** e **interfaces** foi fundamental para consolidar o aprendizado.

## 👩‍🏫 Créditos

Projeto baseado no curso de **Programação Orientada a Objetos com Java** da [Alura](https://www.alura.com.br/).  
Instrutora: **Jacqueline Oliveira**.
