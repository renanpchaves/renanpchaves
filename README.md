# Renan Chaves

**DevSecOps na OceanPact · scripts sec-first, automação de governança e apps internos com integrações bem amarradas.**

Trabalho no Rio de Janeiro. Construo a camada que ninguém vê: auditorias que rodam sozinhas, sincronizações entre sistemas, portais internos que conversam com o Entra ID e o Microsoft Graph, e os pipelines que mantêm tudo isso em pé.

---

## O que eu faço

**Automação de segurança e governança (Python, em produção)**
- Auditorias recorrentes de identidade e acesso: Entra ID, Microsoft 365, cross-tenant, Power BI, DHCP, exposição de credenciais.
- Sincronização entre fontes de verdade: RH, Active Directory, GLPI, portais internos.
- Coletores e relatórios agendados (launchd), com fixtures gravadas, dry-run obrigatório e outbox antes de qualquer envio.
- Tudo sec-first: segredo só em `.env`, escopo mínimo de permissão, logs em stderr, testes de contrato nas fronteiras.

**Aplicações internas (Lovable + Supabase + Entra ID)**
- Dezenas de apps de TI, SegInfo, Compliance e RH: gestão de ativos, termos de responsabilidade, contratos, portal de serviços, monitoramento, declarações de conflito de interesses, ciclos de feedback.
- SSO corporativo, RLS no banco, edge functions, e integrações definidas por contrato com as automações que alimentam cada app.

**Engenharia com agentes de IA**
- [**sdd-karazhan**](https://github.com/renanpchaves/sdd-karazhan): plugin do Claude Code para orquestrar times de agentes com spec como contrato, time mínimo decidido sobre fatos do repositório e revisão independente. Roda no canvas do Maestri ou com subagentes no terminal.
- Fluxo diário: Claude Code + Codex, um implementa e outro revisa, worktree por pacote de trabalho, teste de aceite fora do alcance de quem implementa.

---

## Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnubash&logoColor=white)
![Microsoft Graph](https://img.shields.io/badge/Microsoft_Graph-0078D4?style=flat&logo=microsoft&logoColor=white)
![Entra ID](https://img.shields.io/badge/Entra_ID-0078D4?style=flat&logo=microsoft&logoColor=white)
![Azure DevOps](https://img.shields.io/badge/Azure_DevOps-0078D4?style=flat&logo=azuredevops&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Lovable](https://img.shields.io/badge/Lovable-FF4F8B?style=flat)
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

---

## Como eu trabalho

- Spec antes de código. Teste de aceite antes da implementação. Revisão por quem não escreveu.
- Lote pequeno, branch sempre mergeável, decisão registrada em arquivo.
- Erro que se repete vira regra no harness, não remendo no código.

---

## Estudo

- Segurança ofensiva e defensiva em identidade (Entra ID, Conditional Access, Zero Trust).
- Orquestração de agentes e harness engineering.
- Projetos de estudo em Python e APIs: [darkmoon-records](https://github.com/renanpchaves/darkmoon-records), [cambio-dashboard](https://github.com/renanpchaves/cambio-dashboard), [tasty-flow](https://github.com/renanpchaves/tasty-flow).

---

## Contato

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/renan-chaves-a6a765280/)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=flat&logo=gmail&logoColor=white)](mailto:renanchaves.ti@gmail.com)
