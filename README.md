# Minha Carteira — link estável

Esta página existe por dois motivos, e nenhum deles é design.

**1. O roteador `/u/N/` do Google.** Com duas ou mais contas Google logadas, o
navegador reescreve a URL do web app (`/exec`) para `/u/0/`, `/u/1/`… chuta o
índice errado e mostra *"Não foi possível abrir o arquivo"*. Carregando a mesma
`/exec` dentro de um `<iframe credentialless>` a partir de um domínio que não é
`google.com`, o app abre igual em qualquer navegador.

**2. O link não pode mudar.** No dia em que o deployment for recriado, a `/exec`
muda. Trocando o endereço dentro do `index.html`, o link salvo na tela inicial
do celular continua o mesmo.

## O que isto NÃO é

Não é camada de segurança. Quem barra é o PIN, dentro do app.

## Fonte

`implementacoes/appscript/projetos/PESSOAL/minha-carteira/wrapper/` no repositório
CEPHALON. Editar lá e copiar para cá.
