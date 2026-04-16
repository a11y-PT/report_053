---
website: "BUPi - Balcão Único do Prédio"          # Entre as aspas escreve o nome do website
date: "13/04/2026"                    # Entre as aspas escreve a data de criação do 1º relatório. Os restantes estão no histórico
uri: "https://bupi.gov.pt/pt"   # Entre as aspas escreve o domínio do website
a11y_statement: "https://bupi.gov.pt/pt/acessibilidade" # Entre as aspas escreve o URL da Declaração de Acessibilidade do website
owner: "eBUPi"         # Entre as aspas escrever o nome do owner do website
seal: "Prata"                          # Entre as aspas escreve Bronze, Prata ou Ouro
status: "Auditoria a decorrer"   #Entre as aspas escreve o estado do relatório
---

# Relatório de auditoria

Sítio Web: {{ page.website }} 

- Data de criação: {{ page.date }}
- URL: {{ page.uri }} 
- Propriedade: {{ page.owner }}
- Candidatura: {{ page.seal }}
- Validade do Selo: {{ page.validity }}
- Estado: {{ page.status }}

## Relatório {{ page.website }}

O presente relatório resultou da auditoria da informação publicada na [Declaração de Acessibilidade e Usabilidade]({{ page.a11y_statement }}).

Consulte aqui a última atualização: [Relatório {{ page.website }}](report.html)


<details>
  <summary>Histórico de atualizações</summary>
  <ul aria-label="lista de relatórios já efetuados">
    <li><a href="ddmmaaaa_report.html">(dd/mm/aaaa). Relatório {{ page.website }}</a></li>
  </ul>
</details>

<hr>
