# 🚀 app-tarefa-aula

Aplicação de exemplo em React + Vite para gerenciamento simples de tarefas. Projeto com componentes reutilizáveis, estilos em Sass e estrutura pensada para evolução (ex.: integração com APIs ou validação com Zod).

---

**Resumo**: aplicação front-end criada com Vite e React 18, com foco em organização de componentes e estilos modulares.

**Tecnologias principais**:
- **React 18**: UI.
- **Vite**: bundler/servidor de desenvolvimento.
- **Sass**: pré-processador CSS.

---

**Preview**
- As imagens de exemplo estão em `preview/`. Use-as para documentação visual do projeto.

---

**Como rodar (rápido)**

1. Instale dependências:

```
npm install
```

2. Rode em modo desenvolvimento:

```
npm run dev
```

3. Build de produção:

```
npm run build
```

4. Visualizar build (preview):

```
npm run preview
```

---

**Scripts úteis**
- **dev**: `vite` — servidor de desenvolvimento.
- **build**: `vite build` — gera os arquivos finais.
- **preview**: `vite preview` — serve o `dist` gerado.
- **lint**: `eslint . --ext js,jsx` — analisa código (configurar conforme necessário).

---

**Estrutura principal**
- `src/` — código fonte
  - `App.jsx` — componente raiz
  - `main.jsx` — ponto de entrada
  - `components/` — componentes reutilizáveis (`AddTask.jsx`, `Tasks.jsx`, `CustomInput.jsx`, etc.)
  - `assets/` — imagens e recursos
  - `index.scss` — estilos globais

---

**Boas práticas e sugestões**
- Separe lógica de UI em hooks quando necessário.
- Adote `prop-types` ou `Zod` para validação de props/inputs.
- Para dados fake/temporários, use `json-server` durante desenvolvimento.

---

**Contribuição**
- Fork, crie uma branch com sua feature/fix e abra um Pull Request com descrição clara das mudanças.

---

**Contato**
- Autor: seu nome/contato (adicione um e-mail ou link GitHub se quiser).

---

Se quiser, adapto este `README` para inglês, adicionar badges (CI, license) ou incluir instruções de deploy (Netlify, Vercel). 
