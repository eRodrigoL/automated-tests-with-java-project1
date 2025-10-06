# 📘 Diário de Aprendizado

---

## Atalhos úteis

- Ctrl + Shift + F = formata/identa o código (apenas o que estiver selecionado)
- Ctrl + Alt + T = abre o terminal

---

## Aula 01 — Criação do Projeto Maven e ajustes iniciais
🗓 06/10/2025
🎯 Estrutura inicial e modificação do pom.xml

- Projeto criado com opção "Create a simple project (skip archetype selection)".
- pom.xml expandido para incluir Java 21 e plugin de compilação Maven.

<properties>
  <java.version>21</java.version>
  <maven.compiler.plugin.version>3.14.1</maven.compiler.plugin.version>
</properties>

<build>
  <plugin>maven-compiler-plugin</plugin>
</build>

📝 O uso de ${valor} faz o Maven substituir o conteúdo da propriedade correspondente,
ex.: ${java.version} → 21. Isso facilita futuras atualizações centralizadas de versão.

🧠 Conceitos: Maven, estrutura de projeto, propriedades e plugin de compilação.
