---
name: page-builder
description: Crie landing pages, páginas institucionais e páginas de captura responsivas em projetos React com Vite. Use ao implementar uma página a partir de uma descrição, print ou referência visual, preservando a estrutura e os componentes existentes do projeto.
---

# Page Builder

Construa páginas visuais completas no frontend existente; não crie backend para uma solicitação puramente visual.

## Fluxo obrigatório

1. Inspecione os arquivos antes de editar. Identifique o framework, a estrutura de rotas, os componentes reutilizáveis, os estilos, os assets e os comandos disponíveis em `package.json`.
2. Reutilize componentes, tokens, padrões de layout e estilos existentes sempre que atenderem à necessidade. Crie componentes novos apenas quando a página exigir uma estrutura própria.
3. Implemente a página com HTML semântico: use `header`, `main`, `section`, `nav`, `footer`, títulos em ordem lógica, rótulos de formulário e foco visível. Use texto alternativo útil em imagens informativas.
4. Desenvolva responsivamente para celular, tablet e desktop. Use CSS fluido e breakpoints coerentes com o sistema do projeto; evite larguras rígidas que causem rolagem horizontal.
5. Evite dependências externas desnecessárias. Não adicione backend, dados simulados como se fossem reais, nem invente depoimentos, clientes, métricas, resultados ou certificações.
6. Quando o conteúdo, imagens ou logos não forem fornecidos, mantenha placeholders claramente identificados ou use elementos neutros que não aleguem fatos.

## Referências visuais

Ao receber prints ou referências, extraia hierarquia, espaçamento, paleta, tipografia, composição e comportamento responsivo. Reproduza a intenção visual usando os recursos e padrões disponíveis no projeto, sem copiar marcas ou conteúdos não fornecidos.

## Verificação antes de concluir

1. Execute `npm run build` e corrija erros ou avisos relevantes introduzidos pela alteração.
2. Inicie o servidor de desenvolvimento com o comando definido pelo projeto.
3. Use `@Browser` para abrir e revisar a página implementada.
4. Verifique em larguras de celular, tablet e desktop: overflow horizontal, espaçamentos, contraste, estados e área de clique dos botões, navegação por teclado e legibilidade.
5. Corrija os problemas encontrados e repita as verificações necessárias antes de finalizar.

## Entrega

Informe de modo conciso:

- arquivos criados e alterados;
- validações executadas e respectivos resultados;
- limitações e conteúdos que permanecem como placeholders.
