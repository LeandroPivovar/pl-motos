# PL Motos | Mecânica geral de motos

Site institucional da Oficina PL Motos (Vila Emil, Mesquita - RJ). HTML/CSS/JS estático, sem build.
Visual da arte do cliente no Facebook: preto, vermelho e branco, com o nome em letra de pincel.
A base (CSS e JS) veio do site Auto Elétrico Irmãos Kishi; as regras próprias ficam no fim do `styles.css`.

```bash
npx --yes serve . -l 6500
```

## Estrutura

```
index.html
assets/
  css/styles.css
  js/main.js              menu mobile, formulário -> WhatsApp, FAQ, reveal ao rolar, ano do rodapé
  fonts/phosphor/         ícones Phosphor (woff2 local, licença MIT)
  img/favicon.svg
  img/pl-motos-N-capa.jpg  capa (poster) de cada vídeo, tirada de um quadro do próprio vídeo
  video/pl-motos-N.mp4     vídeos da oficina enviados pelo cliente (WhatsApp, verticais)
```

Sem fotos nem logo em arquivo: o hero tem uma engrenagem vermelha (CSS) com o ícone de moto.
A seção "Vídeos" mostra 5 vídeos reais da oficina (`preload="none"`, só carregam ao tocar). Legendas escritas por mim a partir do que aparece no vídeo; ajustar se o cliente quiser.

## Dados usados (fontes: perfil do WhatsApp Business e post do Facebook "Oficina PL Motos")

| Campo | Valor |
|---|---|
| Nome | PL Motos / Oficina PL Motos |
| Slogan | "Sua moto em boas mãos!" (a arte escreve "Seu moto"; corrigi para "Sua moto") |
| Descrição | "serviços rápidos e no preço justo com ótima qualidade!" |
| WhatsApp / telefone | (21) 96020-9682 (`wa.me/5521960209682`, constante `WA` no `main.js`) |
| Instagram | [@pldastart](https://www.instagram.com/pldastart/) (contato, localização, rodapé e botão "Mais vídeos" -> Reels) |
| Endereço | Rua Paulo de Oliveira Pinto, 198, Vila Emil, Mesquita (RJ) |
| Horário | 09:00 às 18:00 (o print mostra só o dia atual) |
| Serviços (arte) | Motores (parcial / completo), caixa de marcha, chassi, caixa de direção, carenagem |
| Serviços (cliente, 14/10/2026) | Borracharia, pintura e solda em peças de moto; troca de pastilha, troca de relação, troca de embreagem e caixa de marcha quebrada |

## Confirmar com o cliente

- **Dias de atendimento:** só o horário (9h às 18h) é conhecido.
- **Lista de serviços:** a arte está cortada embaixo no print, pode haver mais itens (elétrica, freios,
  suspensão, revisão, troca de óleo...). Acrescentar os cards.
- **Descrições dos serviços:** os textos de cada card (ex.: o que é feito no chassi e na carenagem) são meus.
  Ajustar ao que a oficina realmente faz.
- **Marcas e cilindradas atendidas:** o FAQ manda perguntar pelo WhatsApp.
- **Logo e fotos:** pedir a logo em arquivo e fotos da oficina e de serviços.

## Depoimentos

Não foram incluídos, para não publicar avaliações inventadas.

Fontes: Barlow Condensed, Barlow e Permanent Marker (Google Fonts, OFL / Apache).
