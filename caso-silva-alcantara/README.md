REPOSITÓRIO LINK: https://github.com/VCalegarim/projeto-caso-SilvaxAlcantara.git

# Repositório de Análise Jurídica Assistida por IA — Caso Silva x Alcantara

## Finalidade
Este repositório estabelece um fluxo estruturado para análise prévia, organização de tese e verificação de minuta orientativa para um caso fictício de Direito de Família (divórcio, guarda, alimentos e partilha de bens).

## Público-Alvo
Advogados, estagiários e analistas jurídicos do escritório encarregados da condução do caso.

## Limites da Ferramenta
- O uso de IA generativa é restrito ao suporte de redação, síntese de documentos e conferência formal.
- É vedado o envio de dados pessoais reais às ferramentas externas.
- As respostas geradas pela IA não possuem valor jurídico vinculante e devem passar por revisão humana obrigatória (*Human-in-the-Loop*).

## Critérios de Aceitação
1. Rastreabilidade integral de todas as afirmações jurídicas para os arquivos de suporte na pasta `apoio/`.
2. Sanitização confirmada de dados pessoais antes do envio ao modelo.
3. Registro formal das conferências e auditorias na pasta `evidencias/`.
4. Entrega de minuta revisada pelo advogado responsável na pasta `entrega/`.

## Instruções de Uso
1. Leia `docs/limites_e_sigilo.md` antes de efetuar qualquer consulta externa.
2. Utilize os modelos de instrução contidos em `prompts/` para efetuar buscas no acervo local de `apoio/`.
3. Registre as respostas e discrepâncias encontradas na pasta `evidencias/`.
4. Valide o documento final localizado em `entrega/` antes do envio ao cliente.