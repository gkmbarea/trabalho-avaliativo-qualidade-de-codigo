# trabalho-avaliativo-qualidade-de-codigo

[Entrega do docs](https://docs.google.com/document/d/1bUjQgZvjRXL3kCkOsi7paZnzD4RzO4MHuIQU4qdOlz0/edit?usp=sharing).

 Voce encontra todas fontes na pasta "refs" no repositorio.

## IA generativa e qualidade de código

Os estudos analisados mostram que ferramentas como ChatGPT e GitHub Copilot podem trazer benefícios importantes para a programação, principalmente para desenvolvedores iniciantes, mas também apresentam riscos relacionados à qualidade e à manutenção do software.

### Haindl & Weinberger (2024)

O estudo **“Does ChatGPT Help Novice Programmers Write Better Code?”** investigou se estudantes iniciantes em Java produziam código de melhor qualidade utilizando ChatGPT.

Os resultados mostraram que os estudantes que tiveram acesso ao ChatGPT apresentaram **menos violações de boas práticas de programação** e produziram códigos com **menor complexidade ciclomática e cognitiva**.

Isso indica que a IA pode auxiliar iniciantes a escrever código mais organizado, simples e próximo das convenções recomendadas. Porém, o estudo também mostrou que tópicos mais complexos, como orientação a objetos, collections e manipulação de arquivos, continuaram apresentando dificuldades.

**Principal contribuição:** o ChatGPT pode funcionar como uma ferramenta de apoio ao aprendizado e melhorar aspectos da qualidade do código produzido por programadores iniciantes.

---

### Liu et al. (2024)

O estudo **“Refining ChatGPT-Generated Code”** analisou mais de **4 mil programas gerados pelo ChatGPT em Java e Python**.

Aproximadamente **66% a 69% das soluções passaram nos testes**, mostrando que uma parcela considerável do código gerado ainda continha erros.

Além disso, cerca de **47% dos códigos apresentaram problemas relacionados a estilo ou manutenibilidade**, inclusive entre programas que funcionavam corretamente.

O estudo também demonstrou que o ChatGPT consegue corrigir parte de seus próprios erros quando recebe informações provenientes de **testes e ferramentas de análise estática**.

**Principal contribuição:** código funcional não significa necessariamente código de boa qualidade. A IA deve ser acompanhada de testes, análise estática e revisão humana.

---

### GitClear — Coding on Copilot (2023) e AI Copilot Code Quality (2026)

Os relatórios da GitClear analisaram centenas de milhões de linhas de código provenientes de repositórios reais.

Os dados apontaram tendências como:

* aumento de **code churn**, ou seja, código escrito e modificado novamente pouco tempo depois;
* crescimento da quantidade de código copiado ou duplicado;
* redução da reutilização e da refatoração de código existente;
* aumento potencial da dívida técnica.

O relatório de 2026 reforçou essa tendência, mostrando uma redução expressiva da proporção de alterações relacionadas à refatoração e aumento de código duplicado.

Esses resultados sugerem que ferramentas de IA podem aumentar rapidamente a quantidade de código produzido, mas isso não significa necessariamente aumento proporcional da qualidade do software.

---

## CONCLUSÃO

**Os estudos não mostram que a IA simplesmente melhora ou piora o código. Eles mostram que o resultado depende de como ela é utilizada.**

Para programadores iniciantes, o ChatGPT pode ajudar a produzir código **mais organizado, menos complexo e mais alinhado às boas práticas**.

Entretanto, código produzido automaticamente pode apresentar **erros, problemas de manutenção, duplicação e aumento da dívida técnica**, principalmente quando utilizado sem revisão.

Assim, a principal conclusão é:

### **A IA funciona melhor como assistente do desenvolvedor, e não como substituta do processo de engenharia de software.**

O fluxo mais adequado é:

**IA gera código → testes verificam → análise estática identifica problemas → desenvolvedor revisa → código é refatorado e testado novamente.**

Portanto, quanto maior o uso de inteligência artificial no desenvolvimento, maior também deve ser a preocupação com **testes, revisão de código, análise estática, reutilização e manutenibilidade**.

**Em síntese: a IA pode aumentar produtividade e ajudar na qualidade local do código, mas a qualidade final do software continua dependendo da capacidade do desenvolvedor de compreender, validar e manter aquilo que foi gerado.**

