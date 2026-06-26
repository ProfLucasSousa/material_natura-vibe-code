# figma-to-react.md

Analise o design anexado (screenshot ou frame do Figma) e converta para componentes React seguindo os padrões abaixo.

---

## Stack

- **React 19+** (sem `forwardRef`)
- **TypeScript** strict
- **Tailwind CSS v4** com `@theme` e CSS variables
- **Base UI React** (`@base-ui/react`) para componentes headless
- **Tailwind Variants** (`tailwind-variants`) para variantes
- **Tailwind Merge** (`tailwind-merge`) para merge de classes
- **Lucide React** ou **Phosphor Icons** para ícones

---

## Nomenclatura

- Arquivos: **lowercase com hífens** + `user-card.tsx`, `use-modal.ts`
- **Sempre named exports**, nunca default export
- Não criar barrel files (`index.ts`) para pastas internas

(...)
