# Âncora Contabilidade | Site institucional (projeto de demonstração)

Site de um escritório de contabilidade fictício, voltado a pequenos negócios. Foi criado para demonstrar como um escritório pode se apresentar online, explicar os serviços e captar clientes. Não é um escritório real e nenhuma mensagem enviada pelo formulário vai a lugar nenhum.

## O que o site tem

- Apresentação com chamada principal e lista dos serviços
- Seção de serviços: abertura de empresa, contabilidade mensal, imposto de renda, folha de pagamento, regularização e planejamento tributário
- **Simulador de plano:** o visitante informa o tipo de negócio, o número de funcionários e o faturamento, e vê uma estimativa mensal com o que está incluído. O botão "Quero esse plano" já preenche a mensagem do formulário de contato
- Passo a passo de como o atendimento funciona
- Dúvidas frequentes em formato de sanfona
- Formulário de contato com validação e mensagem de confirmação
- Layout adaptado ao celular, com tema claro e escuro conforme o aparelho

## Como abrir

1. Baixe ou clone esta pasta.
2. Abra o arquivo `index.html` no navegador.

Não precisa instalar nada. Mantenha o `index.html` e o `style.css` na mesma pasta.

## Como adaptar para um cliente

- **Nome, textos, endereço e contatos:** ficam no `index.html`.
- **Planos e valores do simulador:** ficam na lista `PL` e na função `calc`, no `<script>` do `index.html`.
- **Cores:** ficam no começo do `style.css`.

## Tecnologias

HTML, CSS e JavaScript puros, sem bibliotecas e sem imagens externas.

## Como seria em um projeto real

Nesta versão os valores do simulador e as respostas das dúvidas frequentes são de exemplo, e o formulário não envia a mensagem. Em um projeto de verdade, o formulário seria ligado a um serviço de e-mail ou ao WhatsApp do escritório, os valores seriam os da tabela do cliente, e o conteúdo seria revisado pelo contador responsável.
