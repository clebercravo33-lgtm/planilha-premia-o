PREMIAÇÃO GRUPO NICO — PWA para GitHub Pages

Arquivos:
- index.html: aplicativo
- manifest.webmanifest: identificação e instalação como app
- sw.js: cache básico para abrir a interface offline
- icons/: ícones do app

PUBLICAR:
1. Extraia este ZIP.
2. Envie todos os arquivos e a pasta icons para a raiz de um repositório GitHub.
3. No GitHub, abra Settings > Pages e publique a branch/pasta desejada.
4. Abra a URL HTTPS publicada no celular e escolha “Instalar app” ou “Adicionar à tela inicial”.

IMPORTANTE:
- O cache offline permite abrir a interface, mas bibliotecas externas e a sincronização Supabase precisam de internet.
- Os dados guardados apenas no localStorage não são compartilhados entre aparelhos. Para sincronizar entre dispositivos, configure corretamente o Supabase e as tabelas/permissões exigidas pelo aplicativo.
- A tela de login padrão do HTML é admin / admin123. Troque a senha e não trate esse login local como proteção segura de dados.
