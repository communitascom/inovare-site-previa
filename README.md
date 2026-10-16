# Inovare · prévia do site

Protótipo de alta fidelidade do site da Inovare, publicado no GitHub Pages para aprovação da estrutura de páginas.

- `dados.enc` guarda o protótipo inteiro cifrado (AES-GCM 256, chave derivada do PIN por PBKDF2-SHA256, 310000 iterações). Sem o PIN o conteúdo é ilegível.
- `index.html` contém só a tela de acesso; o site é decifrado no navegador.
- Conteúdo de exemplo: o case da Transire e vários números são fictícios, e os logos de clientes ainda dependem de autorização.

Feito pela Communitas.
