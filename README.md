# JEC Processador

Ferramenta web para processar e organizar casos do **Juizado Especial Cível** (Lei 9.099/1995).

## Como abrir

Abra o arquivo [`index.html`](index.html) em qualquer navegador — não precisa de servidor nem de instalação.

## Funcionalidades

- **Cadastro de processos**: autor, réu, tipo de ação, valor da causa, datas, status e resumo dos fatos, com persistência no navegador (localStorage).
- **Análise de competência**: converte o valor da causa em salários mínimos (valor configurável no topo) e indica:
  - até 20 SM — pode postular sem advogado (art. 9º);
  - de 20 a 40 SM — advogado obrigatório;
  - acima de 40 SM — excede o teto do JEC (renúncia ao excedente ou Justiça Comum, art. 3º, §3º).
- **Cálculo de prazos em dias úteis** (art. 12-A) a partir da data de ciência: embargos de declaração (5), recurso inominado (10), contrarrazões (10) e pagamento voluntário no cumprimento de sentença (15, art. 523 do CPC). Sábados e domingos são excluídos; feriados não são considerados.
- **Resumo do caso**: gera um texto estruturado pronto para copiar.
- **Acervo**: lista dos processos salvos com estatísticas (total, ativos e valor em disputa).

## Aviso

Ferramenta de apoio ao estudo e à organização. Não substitui a consulta ao processo nem orientação jurídica.
