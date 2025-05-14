# 📁 ResourceReader Java Utility

Utilitário para leitura de arquivos de recursos do classpath (`src/main/resources`) em aplicações Java SE e Spring Boot. Ideal para carregar arquivos `.txt`, `.json`, `.yml`, templates ou arquivos estáticos embarcados.

## 🚀 Funcionalidades

- Leitura de arquivos em texto simples do classpath
- Compatível com Java SE (puro) e Spring Boot
- Suporte a arquivos UTF-8
- Implementação robusta com tratamento de exceções

## ✅ Exemplo de uso

```java
public class App {
    public static void main(String[] args) {
        String conteudo = new ResourceReader().readResourceFile("dados/exemplo.txt");
        System.out.println(conteudo);
    }
}
