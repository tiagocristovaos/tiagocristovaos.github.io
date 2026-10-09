# Portfólio · Tiago Cristovão da Silva — Controladoria & FP&A

Site de uma página (`index.html`), sem dependências locais. Chart.js e fontes carregam por CDN.

## Antes de publicar: preencha o contato

Abra `index.html` em um editor (Bloco de Notas ou VS Code), procure por `const CONTATO` (bloco CONFIGURAÇÕES) e preencha:

```js
const CONTATO = {
  linkedin: "https://www.linkedin.com/in/seu-perfil",
  email: "seu@email.com",
  telefone: "(21) 99999-9999",
  curriculo: "curriculo.pdf"
};
```

- Campo vazio = botão correspondente não aparece. A seção de contato continua visível.
- Currículo: salve o PDF com o nome `curriculo.pdf` e suba na mesma pasta do `index.html` (passo 4 abaixo). O botão "Baixar currículo" aparece no topo e no contato.

## Foto

Salve sua foto como `foto.jpg` (quadrada, rosto centralizado, ao menos 300×300 px) e suba junto com o `index.html`. Sem o arquivo, o espaço da foto some sem deixar imagem quebrada.

## Publicar no GitHub Pages (10 minutos, gratuito)

1. Crie uma conta em github.com (se ainda não tiver). O nome de usuário vira o endereço: `usuario.github.io`.
2. Clique em **New repository**.
   - Nome do repositório: `usuario.github.io` (troque `usuario` pelo seu nome de usuário, exatamente igual).
   - Marque **Public**. Clique em **Create repository**.
3. Na página do repositório, clique em **uploading an existing file**.
4. Arraste o `index.html`, a `foto.jpg`, o `curriculo.pdf` (se tiver) e este README (opcional). Clique em **Commit changes**.
5. Vá em **Settings → Pages**. Em *Source*, escolha **Deploy from a branch**, branch **main**, pasta **/(root)**. Salve.
6. Em 1 a 2 minutos o site estará em `https://usuario.github.io`.

## Atualizar depois

Edite o `index.html` no próprio GitHub (ícone de lápis) ou suba uma nova versão pelo mesmo caminho do passo 3. A publicação é automática.

## Domínio próprio (opcional)

Registre um domínio (ex.: registro.br, cerca de R$ 40/ano), depois em **Settings → Pages → Custom domain** informe o domínio e crie no registro.br os apontamentos DNS indicados pelo GitHub.

## Checklist antes de divulgar

- [ ] LinkedIn, e-mail, telefone e currículo preenchidos em CONTATO
- [ ] Nenhum dado real do empregador nos painéis (todos os números são simulados)
- [ ] Link incluído no LinkedIn (seção Destaques e campo Site)
- [ ] foto.jpg enviada junto com o index.html
- [ ] Testado no celular e nos dois temas (botão sol/lua)
