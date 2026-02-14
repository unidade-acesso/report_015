---
website: "SNS 24"          # Entre as aspas escreve o nome do website
date: "16/02/2026"                    # Entre as aspas escreve a data de criação do 1º relatório. Os restantes estão no histórico
uri: "https://www.sns24.gov.pt/pt/inicio"   # Entre as aspas escreve o domínio do website
owner: "SNS 24"         # Entre as aspas escrever o nome do owner do website
seal: "_Ouro_"                          # Entre as aspas escreve Bronze, Prata ou Ouro
---

# {{ page.website }}

- Data de criação: {{ page.date }}
- URL: {{ page.uri }}
- Propriedade: {{ page.owner }}
- Candidatura: {{ page.seal }}

## Relatório de Auditoria

Consulte aqui a última atualização: [Relatório do {{ page.website }}](report.html)

<details>
  <summary>Histórico de atualizações</summary>
  <ul aria-label="lista de relatórios já efetuados">
    <li><a href="ddmmaaaa_report.html">(dd/mm/aaaa). Relatório do {{ page.website }}</a></li>
  </ul>
</details>
