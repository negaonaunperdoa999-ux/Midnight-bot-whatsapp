# Midnight Bot - Edicao Hutao x Nazuna

O Midnight e um bot de WhatsApp multifuncional desenvolvido para entretenimento, moderacao e utilidades. O projeto e uma fusao das bases Hutao e Nazuna, focada em otimizacao de codigo e personalizacao de interface.

## Caracteristicas Principais

### Interface e Estetica
- Padronizacao de mensagens e menus via theme.js.
- Motor de logotipos universal integrado a API Sirv com mais de 80 estilos disponiveis.
- Sincronizacao de menus para exibir apenas comandos funcionais.

### Moderacao e Administracao
- Sistema de protecao em transmissoes com identificadores unicos e atraso entre envios.
- Comando para limpeza de chat com capacidade de remover ate 200 mensagens.
- Controle de grupos com sistema de advertencias e gestao de permissoes.

### Entretenimento e Ferramentas
- Integracao com modelos de inteligencia artificial.
- Handlers de download para redes sociais e plataformas de video.
- Criacao de figurinhas com metadados personalizados para o Midnight.

## Processo de Desenvolvimento

O projeto passou por uma refatoracao profunda para garantir estabilidade:

1. Unificacao das bases de codigo index.js e estrutura de modulos.
2. Remocao de funcoes duplicadas e comandos inativos para reduzir o consumo de memoria na hospedagem.
3. Implementacao de um handler universal para geracao de logos, reduzindo o volume de codigo e facilitando a manutencao.
4. Criacao de uma camada de compatibilidade para aliases e comandos legados.
5. Reforco nos protocolos de seguranca e permissoes de acesso.

## Tecnologias Utilizadas

- Node.js (JavaScript/ESM)
- Baileys (WhatsApp Multi-Device)
- HidenCloud (Docker)
- Sirv API (Geracao de imagens)
- Codex AI (Suporte em refatoracao)

## Notas Tecnicas

Este projeto e utilizado como laboratorio de logica e desenvolvimento para o circulo de amigos e ambiente academico do IFPA Campus Itaituba. O foco atual reside na estabilidade do runtime e na expansao de ferramentas de utilidade publica.
