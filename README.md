# Design Patterns em Java

Este repositório contém implementações originais dos principais **Design Patterns (Padrões de Projeto)** da Gang of Four (GoF), utilizando **Java puro** e, futuramente, exemplos práticos com o **Spring Framework**.

## 🧠 Objetivo

Demonstrar, de forma simples e didática, como aplicar padrões de projeto na prática com Java, facilitando o entendimento da arquitetura e boas práticas no desenvolvimento de software orientado a objetos.

---

## ✅ Padrões já implementados

- ✅ Singleton

Em breve:
- 🔜 Factory Method
- 🔜 Strategy
- 🔜 Builder
- 🔜 Proxy
- 🔜 Adapter
- 🔜 Observer
- 🔜 Exemplos com Spring Framework

---

## 🛠️ Como rodar este projeto

1. **Clone o repositório:**

```bash
git clone https://github.com/seu-usuario/design-patterns-java.git

cd design-patterns-java

mvn clean compile

mvn exec:java -Dexec.mainClass="com.seuusuario.designpatterns.singleton.SingletonTest"


---------------------

Lembre-se de trocar seu-usuario e seuusuario com seus nomes reais do GitHub e do pacote.

---------------------

design-patterns-java/
├── pom.xml
└── src/
    └── main/
        └── java/
            └── com/
                └── seuusuario/
                    └── designpatterns/
                        └── singleton/
                            ├── Logger.java
                            └── SingletonTest.java
----------------------

💡 Sobre o padrão Singleton

O padrão Singleton garante que uma classe tenha uma única instância e fornece um ponto de acesso global a ela. É útil para classes que gerenciam recursos globais, como loggers, conexões e caches.

-----------------------

🚧 Em construção

Este repositório será atualizado com novos padrões de projeto frequentemente. Fique à vontade para clonar, estudar, sugerir melhorias ou contribuir!