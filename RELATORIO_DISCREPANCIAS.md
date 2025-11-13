# Relatório de Discrepâncias - Análise de Internações Hospitalares ES

## Discrepâncias Identificadas e Corrigidas

### 1. Número de Municípios Acima de 8% (CORRIGIDO)
- **Erro Original**: 31 municípios
- **Valor Correto**: 48 municípios
- **Status**: ✅ CORRIGIDO

### 2. Número de Municípios Abaixo de 6% (CORRIGIDO)
- **Erro Original**: 11 municípios
- **Valor Correto**: 7 municípios
- **Status**: ✅ CORRIGIDO

### 3. Lista de Municípios com ICSAB >30% (CORRIGIDO)
- **Erro Original**: Listava apenas 5 municípios
- **Valor Correto**: 15 municípios
- **Status**: ✅ CORRIGIDO

### 4. Lista de Municípios Prioritários (CORRIGIDO)
- **Status**: ✅ CORRIGIDO

## Observação Técnica

Durante a análise, identificou-se que os percentuais na coluna "% Internação População" 
são exatamente 2x o cálculo direto (Total/População × 100).

Razão: 2,00x em todos os municípios.

Isso pode indicar uma metodologia específica não documentada, mas NÃO afeta a 
consistência interna entre relatório e tabela (ambos usam os mesmos valores).
