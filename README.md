<h1 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=2800&pause=900&color=39D353&center=true&vCenter=true&width=640&lines=%24+whoami;Luis+Fernando+Freitas+%E2%80%94+Data+Analyst;SELECT+insight+FROM+dados+WHERE+impacto+%3E+0%3B" alt="$ whoami — Luis Fernando Freitas, Data Analyst" />
</h1>

<p align="center">
  <a href="https://www.linkedin.com/in/luis-fernando-freitas-a3503b284"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:luisfreitas10565@gmail.com"><img src="https://img.shields.io/badge/E--mail-0d1117?style=for-the-badge&logo=gmail&logoColor=39D353" alt="E-mail"/></a>
  <img src="https://img.shields.io/badge/status-open__to__work-39D353?style=for-the-badge&labelColor=0d1117" alt="open to work"/>
</p>

```console
luis@delfia:~$ cat perfil.yaml
nome:      Luis Fernando Freitas
cargo:     Analista de Dados Júnior @ Delfia (Customer Success)
local:     São Paulo, SP · híbrido/remoto
formação:  Análise e Desenvolvimento de Sistemas — FIAP (2026)
idiomas:   [pt-BR: nativo, en: C1 (EF SET 67/100)]
foco:      BI & Analytics → Analytics Engineering
missão:    transformar billing, consumo e contrato em decisões
```

```sql
-- luis@delfia:~$ psql -d carreira
SELECT competencia, nivel, onde_uso
FROM   luis.skills
ORDER  BY nivel;
```

```text
 competencia             | nivel              | onde_uso
-------------------------+--------------------+--------------------------------------------
 Power BI · DAX          | core               | forecast, billing e dashboards de clientes
 SQL                     | core               | consultas, modelagem e validação de dados
 Python · Pandas         | core               | extração via API, ETL e conciliação
 Modelagem Star Schema   | core               | modelos de forecast de contrato
 Git                     | core               | versionamento no dia a dia
 AWS · Terraform · CI/CD | prática em projeto | Dogscout (Lambda, DynamoDB, GitLab CI)
 TypeScript · Grafana    | prática em projeto | dashboards e alertas de consumo via API
 FastAPI · PostgreSQL    | prática em projeto | plataforma pessoal de investimentos
 SQL avançado · dbt      | em estudo          | rumo a Analytics Engineering
(9 rows)
```

```console
luis@delfia:~$ tail -n 4 conquistas.log
[billing]   ~US$ 43 mil em cobranças indevidas identificadas e corrigidas (6 meses)
[consumo]   uso excessivo de métricas detectado: ~US$ 13 mil em 3 meses vs. orçamento de US$ 9 mil/ano
[testes]    sistema de conciliação de invoices validado por 195 testes automatizados
[carreira]  estagiário → analista júnior em 6 meses
```

### `ls ./projetos`

| Projeto | O que faz | Stack |
|---|---|---|
| **Conciliação de Invoices** *(interno)* | Concilia invoices de observabilidade contra o consumo real, com idempotência, trilha de auditoria e alertas de licenças omitidas | Python · Pandas · SQLAlchemy · pytest |
| **salesOndemand** *(interno)* | Extrai billing via API (Datadog + Grafana Cloud) e alimenta os Power BI dos clientes | Python · Streamlit · SQLite · PromQL |
| **Dogscout** *(interno, time de 4)* | Converte consumo de licenças em custo por cliente; fiz a detecção de tendência de consumo e a integração com Grafana | TypeScript · AWS Lambda · DynamoDB · Terraform |
| **Controle de Investimentos** *(pessoal)* | Consolida carteiras de várias corretoras: posição, custo médio, rentabilidade e proventos | FastAPI · React/TS · PostgreSQL · Alembic |

<sub>Projetos internos têm código privado; os detalhes estão no meu LinkedIn.</sub>

### `stack --list`

<p>
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black" alt="Power BI"/>
  <img src="https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white" alt="SQL"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="Pandas"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git"/>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white" alt="AWS"/>
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white" alt="Terraform"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript"/>
  <img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white" alt="Grafana"/>
  <img src="https://img.shields.io/badge/Datadog-632CA6?style=flat-square&logo=datadog&logoColor=white" alt="Datadog"/>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI"/>
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white" alt="Streamlit"/>
</p>

```console
luis@delfia:~$ echo $NEXT_STEP
Analista de Dados / BI em banco ou fintech — vamos conversar?
luis@delfia:~$ █
```
