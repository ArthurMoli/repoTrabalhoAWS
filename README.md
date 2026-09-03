# Plano de Migração para Nuvem — Estudo Técnico e Econômico

Apresentação em slides comparando o custo total de propriedade (TCO) de uma infraestrutura on-premise contra a mesma carga migrada para a AWS, ao longo de 3 anos.

Trabalho acadêmico do UniSENAI.

**▶️ [Ver a apresentação](https://arthurmoli.github.io/repoTrabalhoAWS/)**

---

## O estudo

| Cenário | TCO em 3 anos |
|---|---|
| Ambiente local | R$ 102.000 |
| Ambiente AWS | R$ 36.600 |
| **Economia** | **R$ 65.400 (64%)** |

A composição do custo na AWS: EC2 (R$ 13.000), mão de obra (R$ 20.000), RDS (R$ 2.600) e rede (R$ 1.000).

A arquitetura proposta usa Internet Gateway → Elastic Load Balancer → EC2 (aplicação) → RDS PostgreSQL, distribuída em duas zonas de disponibilidade.

---

## Conteúdo dos slides

1. Cenário atual
2. TCO local (3 anos)
3. TCO AWS (3 anos)
4. Arquitetura em nuvem
5. Comparativo final
6. Benefícios — alta disponibilidade (99,95%), escalabilidade sob demanda, backups automáticos, criptografia, eliminação de CAPEX
7. Conclusão e próximos passos

---

## Como funciona

Página estática única, sem build e sem dependências instaladas:

- **[Reveal.js](https://revealjs.com/) 4.4.0** — navegação em slides
- **[Mermaid](https://mermaid.js.org/) 10.6.1** — os 5 gráficos (pizza e fluxograma) são gerados em tempo de execução a partir de definições em texto

Ambos vêm por CDN. Para rodar localmente, basta abrir o `index.html` no navegador.

Navegue com as **setas do teclado** ou pressione **`ESC`** para a visão geral dos slides.

---

## Autores

Arthur Maciel Oliveira · Gabriel Rodrigues Dias · Vitor Waltrick de Amorim · Leonardo Della Giustina
