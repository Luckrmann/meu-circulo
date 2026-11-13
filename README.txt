MEU CÍRCULO — PRIMEIRA VERSÃO DA INTERFACE

O que esta versão já tem:
- Interface responsiva com visual moderno.
- Prévia dos próximos aniversários.
- Formulário visual para cadastrar nome, data, telefone e relação.
- Contagem regressiva na tela enquanto a página estiver aberta.
- Estrutura PWA (manifesto e service worker).

IMPORTANTE:
Esta é a primeira etapa visual. Os cadastros ainda ficam apenas na memória da página e NÃO são sincronizados nem salvos na nuvem. Não use dados reais ainda.
O Supabase (banco em nuvem/login) e a integração oficial WhatsApp Business Cloud API serão conectados nas próximas etapas. O envio automático depende de configuração e aprovação da Meta.

COMO PUBLICAR NO GITHUB PAGES:
1. Extraia o ZIP.
2. Crie um repositório público chamado meu-circulo no GitHub.
3. Envie os arquivos desta pasta para a raiz do repositório.
4. No GitHub, abra Settings > Pages.
5. Em Build and deployment, escolha Deploy from a branch.
6. Selecione a branch main e a pasta /(root), depois Save.
7. Aguarde a publicação e abra o endereço que o GitHub Pages mostrar.

Para instalar no Android:
1. Abra o endereço publicado no Chrome.
2. Menu ⋮ > Adicionar à tela inicial / Instalar app.

PRÓXIMA ETAPA:
Conectar Supabase com autenticação e banco de dados protegido por usuário (RLS). Nunca colocar chave secreta de servidor ou token do WhatsApp no código público do site.
