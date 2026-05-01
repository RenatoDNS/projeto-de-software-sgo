# Sistema de Gestão das Olimpíadas (SGO)

> Trabalho 1 — Projeto de Software | PUC Minas | Prof. João Paulo Carneiro Aramuni

---

## Descrição do Sistema

O **SGO** é um sistema de gestão desenvolvido para coordenar os diferentes aspectos das Olimpíadas. Ele permite o gerenciamento de competições, inscrições de atletas, alocação de locais para as provas e controle de resultados.

---

## Regras de Negócio

1. **Cadastro de competições** — O sistema permite cadastrar competições com nome da modalidade, data, horário, local e lista de atletas inscritos.
2. **Inscrição de atletas** — Atletas de diferentes países podem se inscrever em várias competições, mas só podem representar um país por modalidade.
3. **Alocação de locais** — Os locais são alocados evitando conflitos de horário; um local só pode abrigar uma competição por vez.
4. **Controle de resultados** — Após cada competição, os resultados são registrados com o 1º, 2º e 3º colocados.
5. **Relatórios de medalhas** — O sistema gera relatórios com o desempenho de cada país em medalhas de ouro, prata e bronze.

---

## Histórias de Usuário

**US01** — Como **administrador**, quero cadastrar competições informando modalidade, data, horário e local, para que o evento seja organizado com antecedência.

**US02** — Como **atleta**, quero me inscrever em competições específicas representando o meu país, para que eu possa participar oficialmente dos jogos.

**US03** — Como **administrador**, quero alocar locais para as competições com validação automática de conflitos de horário, para que dois eventos não ocupem o mesmo espaço simultaneamente.

**US04** — Como **administrador**, quero registrar os resultados de cada competição indicando o 1º, 2º e 3º colocados, para que o desempenho dos atletas seja documentado.

**US05** — Como **administrador**, quero gerar relatórios de medalhas por país, para que o quadro de medalhas reflita o desempenho de cada delegação ao longo dos jogos.

**US06** — Como **atleta**, quero consultar o quadro de classificação e medalhas, para que eu possa acompanhar meu desempenho e o dos demais competidores.

---

## Diagramas UML

### Diagrama de Caso de Uso

<img width="800px" src="https://github.com/RenatoDNS/projeto-de-software-sgo/blob/main/imagens/diagrama-de-caso-de-uso.png"/>

---

## Estrutura do Repositório

```
📦 projeto-de-software-sgo
├── 📄 README.md
├── 📁 imagens/
│   └── diagrama-de-caso-de-uso.png
└── 📁 codigos/
    └── diagrama-de-caso-de-uso.puml
```

---

## Ferramentas Utilizadas

- [PlantUML](https://plantuml.com/) — geração dos diagramas UML

---

## Autor

**Renato Douglas** — Engenharia de Software | PUC Minas
