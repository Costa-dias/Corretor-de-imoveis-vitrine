# Registro público do site para ULTRON

Domínio: https://corretor-imoveis-frontend.onrender.com

Este repositório é uma apresentação com README, sem aplicação ou pipeline de
publicação. O arquivo `.well-known/ultron-site.json` é somente um artefato para
publicação MANUAL pelo proprietário no domínio exato, após aprovação. Integrar
esta PR aqui NÃO publica nem ativa o registro no site. Nenhum repositório
privado é alterado ou necessário para revisar/baixar este arquivo.

Sirva o JSON exato em `/.well-known/ultron-site.json`, sem redirects ou fallback
HTML da SPA. O ULTRON compara-o com seu catálogo antes de cada consulta manual
GET da prova + HEAD da raiz (TLS/certificado/cabeçalhos). Sem exploração, login,
correção automática, scripts ou serviço instalado. É registro público, não senha.
Remover/divergir o arquivo impede novas consultas. Não certifica segurança.
Não foi publicado ou testado ao vivo. Sem build aplicável neste repositório.
