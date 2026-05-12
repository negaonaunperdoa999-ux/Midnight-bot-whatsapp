# 🏮 Midnight Bot - [Hutao x Nazuna Edition]

O **Midnight** é um bot de WhatsApp multifuncional desenvolvido para oferecer uma experiência completa de entretenimento, moderação e utilidades. Este projeto nasceu da fusão estratégica entre as bases **Hutao** (estética e comandos visuais) e **Nazuna** (motor de processamento), resultando em um sistema híbrido, rápido e altamente customizado.

---

## 🚀 Características Principais

### 🎨 Estética e Interface
- **Tema Hutao:** Mensagens, menus e interações padronizados com molduras elegantes via `theme.js`.
- **Motor de Logos Universal:** Integração com a API Sirv, permitindo a geração de mais de 80 estilos de logotipos e marcas (ex: `/neon`, `/3dgold`, `/procurado`).
- **Menus Sincronizados:** Interface limpa que mostra apenas o que realmente está operacional, evitando comandos "fantasmas".

### 🛡️ Moderação e Administração
- **Anti-Spam Dinâmico:** Sistema de proteção em transmissões com IDs únicos e delays aleatórios para evitar banimentos.
- **Limpeza de Chat:** Comando `/limparspammsg` capaz de apagar até 200 mensagens para todos de forma eficiente.
- **Gestão de Grupos:** Comandos completos de advertência, banimento, promoção e configuração de prefixos múltiplos.

### 🎮 Entretenimento e Utilidades
- **IA Integrada:** Suporte a múltiplos modelos de inteligência artificial (Gemini, GPT, etc.).
- **Downloads:** Recuperação de handlers para YouTube, TikTok, Instagram e Pinterest.
- **Figurinhas:** Criação de stickers com metadados personalizados (*Midnight Stickers*).
- **Economia (RPG):** Sistema de Gold e Ranks (em desenvolvimento).

---

## 🛠️ Como o Bot foi Construído (O Processo)

O Midnight não foi apenas "baixado e ligado". Ele passou por um processo intenso de **Refatoração e Engenharia Reversa**:

1.  **A Fusão:** Unificamos o `index.js` da Nazuna com a estrutura de pastas e módulos da Hutao.
2.  **Poda de Código Legado:** Removemos centenas de funções duplicadas e comandos "mortos" para otimizar o consumo de RAM na hospedagem (HidenCloud).
3.  **Motor Genérico de Logos:** Em vez de centenas de arquivos individuais, criamos um handler universal que mapeia requisições dinâmicas para APIs de imagem, economizando milhares de linhas de código.
4.  **Correção de Fluxo:** Implementamos um sistema de compat
