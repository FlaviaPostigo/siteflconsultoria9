# Publicação do site FL Consultoria

## 1. Enviar para o GitHub

1. Crie um repositório novo no GitHub.
2. Envie todo o conteúdo desta pasta para o repositório.
3. Não envie somente o arquivo ZIP: descompacte e envie os arquivos e pastas do projeto.

## 2. Publicar no Netlify

1. Entre no Netlify e escolha **Add new project**.
2. Selecione **Import an existing project**.
3. Conecte a conta do GitHub e escolha o repositório.
4. As configurações já estão no arquivo `netlify.toml`:
   - comando de build: `npm run build`;
   - diretório de publicação: `dist`;
   - Node.js: versão 22;
   - preset de implantação: Netlify.
5. Clique em **Deploy**.

## 3. Receber os contatos do formulário

O formulário foi preparado para o **Netlify Forms**. Depois do primeiro deploy:

1. Abra o projeto no Netlify.
2. Acesse **Forms** para verificar as solicitações recebidas.
3. Em **Form notifications**, configure um e-mail para receber avisos a cada novo contato.

O botão **Falar agora pelo WhatsApp** continua abrindo uma conversa direta.

## 4. Conectar o domínio

Depois que o site estiver publicado:

1. No Netlify, abra **Domain management**.
2. Adicione o domínio registrado no Registro.br.
3. Copie os registros DNS informados pelo Netlify.
4. No Registro.br, abra o domínio e atualize a zona DNS conforme os dados apresentados pelo Netlify.
5. Aguarde a propagação do DNS e a ativação automática do HTTPS.

## Arquivos das logos

- `src/assets/logo-fl.png`: símbolo colorido, usado no cabeçalho e na página inicial.
- `src/assets/logo-fl-white.png`: símbolo branco, usado no rodapé escuro.
- `src/assets/logo-fl-horizontal.png`: assinatura horizontal completa.
- As mesmas imagens também estão na pasta `public` para favicon e outros usos.

## Atualização com fotografias e vídeo

A pasta `public/media` contém o vídeo do Projeto Travessia e sua imagem de capa. Ela deve ser enviada junto com as pastas `src` e `public`; caso contrário, o vídeo não aparecerá no site publicado.
