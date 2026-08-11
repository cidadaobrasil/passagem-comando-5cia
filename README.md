# Passagem de Comando — 5ª Cia PM

Relatório de passagem de comando da 5ª Cia PM (Guararapes/Valparaíso), preparado para o afastamento do Cap Josemar para o CAO.

**Período da substituição: 17/08/2026 a 22/01/2027**, cinco meses. A data acompanha o 1º bloco da Rotina 13 do SIPA (ver `C:\projetos\central-cao`), não o fim do curso, que vai até ago/2027. O `relatorio.pdf` e o `relatorio.docx` ainda trazem 16/02/2027, que está superado.

## Como é

Site estático de página única (`index.html`). Sem build.

## Como publicar

Editar o `index.html`, commitar e dar push na `main`.

## Estrutura

Sete seções, cada assunto tratado em um lugar só:

1. Assunção — 24h, 72h e 30 dias
2. Calendário — rotina fixa e agenda datada
3. Decidir e acionar
4. Comando local — pessoas e rotinas da Cia
5. Projetos territoriais
6. Checklist de passagem
7. Sistemas, SEI e custódia

O índice da barra lateral e o do menu mobile são gerados por JS a partir das seções. Para adicionar uma seção, basta criar o `<details class="report-section" id="sN">` — o índice se atualiza sozinho.

## Estado

Documento com prazo real, base 29/07/2026 com atualizações até 11/08/2026.

Pessoas conferidas com o Cap Josemar em 11/08/2026: **Cb PM Jurca**, **1º Sgt PM Locatelli (GP)** e **Subten PM Carlos H. Locatelli (P4)**. Atenção para os dois Locatelli e para os dois Cleverson (Subten PM, do Territorial, e Bittencourt, civil da Prefeitura).

Atividade Delegada ativa nos quatro municípios: Guararapes com distribuição ordinária de vagas na semana, Valparaíso todo fim de semana com prioridade para fiscalização de trânsito, Bento de Abreu e Rubiácea com vagas esporádicas para eventos.

## Auditoria de 11/08/2026

Revisão do site contra o `relatorio.pdf` (versão 3.0, corte 29/07/2026). Corrigido: prazos da Visita Solidária, nomes de operação, contagem dos quadros do Trello (são dez), relatório mensal separado do informe semanal, sistema RSO Eletrônico no lugar de SIGA/SGO, e cinco defeitos de CSS e acessibilidade (coluna fixa transparente nas tabelas, contraste do selo "Pendente" no tema escuro, botão de limpar busca sempre visível, campo de busca sem nome acessível, fundos descartados na impressão).

Em aberto, dependem de confirmação:

- **Siglas das vagas** de sexta e sábado em Guararapes (REI, EJ, DG, DGEM). Confirmar com o Subten PM Marcos antes de trocar rótulo em ofício ou escala.
- **Exposição do repositório.** Documento de uso interno em repositório público com Pages no ar. Decisão pendente sobre tornar privado e retirar os anexos do versionamento. Ver a lição registrada na página 22 do relatório.
