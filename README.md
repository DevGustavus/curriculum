# 📄 Curriculum Vitae

Este repositório foi desenvolvido para centralizar, organizar e gerenciar o versionamento do meu currículo profissional. 

Manter o currículo versionado em um repositório Git permite rastrear o histórico de atualizações, experiências adquiridas, novas habilidades técnicas e conquistas ao longo da carreira de forma estruturada e eficiente.

---

## 📂 Estrutura do Repositório

O projeto possui uma estrutura simples e direta:

* **`cv/`**: Diretório principal contendo os arquivos de currículo.
  * [`cv_gustavomp.md`](file:///c:/Users/gusta/Desktop/curriculum/cv/cv_gustavomp.md): Currículo em formato Markdown. Funciona como a fonte de verdade (source of truth) para fácil edição técnica e legibilidade direta no GitHub.
  * `cv_gustavomp.pdf`: Versão compilada e formatada em PDF, pronta para distribuição, processos seletivos e impressão.

---

## 🚀 Vantagens do Currículo como Código (CV-as-Code)

Adotar o conceito de versionamento para o currículo traz diversas vantagens práticas:

1. **Histórico Completo**: O Git mantém o registro de quando cada habilidade, curso ou experiência foi adicionada.
2. **Edição Simplificada**: Markdown permite focar apenas no conteúdo, sem distrações com formatação visual complexa durante a escrita.
3. **Portabilidade**: O formato Markdown é suportado nativamente pelo GitHub e pode ser facilmente convertido para PDF, HTML ou editado em qualquer editor de texto.
4. **Prontidão**: Facilidade de manter o arquivo PDF sempre atualizado a partir da fonte em Markdown.

---

## 🛠️ Como Exportar / Atualizar

Caso queira regenerar o arquivo PDF a partir do arquivo Markdown, existem diversas ferramentas recomendadas:

* **VS Code Extensions**: Extensões como *Markdown PDF* ou *Markdown Preview Enhanced* permitem exportar o arquivo `.md` diretamente para `.pdf` com um clique.
* **CLI (Pandoc / Weasyprint)**:
  ```bash
  pandoc cv/cv_gustavomp.md -o cv/cv_gustavomp.pdf
  ```
* **Ferramentas Online**: Editores como o Dillinger ou StackEdit facilitam a exportação visual de Markdown para PDF.
