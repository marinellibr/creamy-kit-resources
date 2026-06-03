# Creamy Kit — Resources

Recursos compartilhados do **Creamy Kit** (design system): ícones e demais
assets consumidos pelos componentes.

> Repositório de **assets**. O código dos componentes vive no design system
> (`creamy-kit-angular` / `creamy-kit-react`).

## Estrutura

```
creamy-kit-resources/
└── icons/      Ícones em SVG (stroke na cor do tema)
    └── arrow-chevron-right.svg
```

## Iconset

SVGs em geral 20×20 (`viewBox="0 0 20 20"`), com `stroke` na cor do texto/tema.
Usados, por exemplo, no chevron de Breadcrumb, Banner, Header e na navegação do
Calendar.

| Ícone | Arquivo |
|-------|---------|
| Chevron → (direita) | `icons/arrow-chevron-right.svg` |

### Uso

Para que o ícone acompanhe a cor do contexto, troque `stroke="#484848"` por
`stroke="currentColor"` ao incorporá-lo inline:

```html
<span style="color: var(--neutral-base)">
  <!-- conteúdo do arrow-chevron-right.svg com stroke="currentColor" -->
</span>
```

## Contribuindo

1. Adicione o SVG na pasta correspondente (`icons/`).
2. Mantenha o `viewBox` quadrado e `stroke`/`fill` neutros (preferir
   `currentColor` no consumo).
3. Atualize a tabela acima.
