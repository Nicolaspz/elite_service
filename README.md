# Elite Service — site institucional

Site estático responsivo da Elite Service. Os ficheiros desta pasta devem ficar directamente na raiz do repositório GitHub, incluindo `index.html`. Não precisa de Node.js, dependências, comando de compilação ou funções de servidor.

## Pré-visualizar localmente

Com Python 3 instalado, execute a partir desta pasta:

```sh
python3 -m http.server 4173
```

Abra `http://localhost:4173` no navegador.

## Publicar pela Vercel via GitHub

1. Crie um repositório no GitHub.
2. Envie o conteúdo desta pasta para a raiz do repositório. Confirme que `index.html`, `styles.css` e `script.js` aparecem na raiz, sem uma pasta adicional `elite-service-site/` à volta.
3. Na Vercel, escolha **Add New → Project** e importe esse repositório GitHub.
4. Nas definições de compilação, escolha **Other** como framework. Deixe **Build Command** e **Install Command** vazios e use `.` como **Output Directory** (ou deixe o padrão da Vercel para um site estático sem pasta `public`).
5. Escolha **Deploy**. Depois de ligado ao GitHub, novos commits e pull requests geram deployments automaticamente.

Este projecto não inclui `vercel.json` de propósito: a raiz contém o `index.html` e não precisa de regras de reescrita ou de rotas de servidor.

## Imagens e carregamento

As fotografias desta proposta são ilustrativas e servidas pelo Unsplash. As imagens usam `srcset` e `sizes` para escolher resoluções adequadas ao ecrã, carregamento diferido abaixo do destaque, descodificação assíncrona e dimensões reservadas para reduzir mudanças de layout. Antes de publicar, substitua-as pelos registos fotográficos oficiais da Elite Service.

## Interacções

O menu adapta-se a telemóveis e os links internos navegam suavemente até às secções, com espaço para o menu fixo. As secções aparecem ao entrar no ecrã e desaparecem ao sair, tanto ao descer como ao subir. Ao regressar, o efeito repete-se. Serviços e etapas entram em sequência; as fotografias assentam nos seus lugares com rotações leves e escalonadas, como cartões pousados sobre uma mesa. A animação respeita a preferência do sistema por movimento reduzido.

## Ficheiros

- `index.html` — estrutura e conteúdo
- `styles.css` — identidade visual e adaptações responsivas
- `script.js` — menu móvel, scroll suave, efeitos de entrada e carregamento das imagens
# site_hermenegilda
# site_hermenegilda
# site_hermenegilda
# elite_service
# elite_service
