# 🎨 Projeto de `localStorage` com Estilização e Temas

Este é um projeto simples e elegante que demonstra o uso do `localStorage` para salvar dados no navegador. A aplicação permite que você salve seu nome e, em seguida, o carregue automaticamente ao visitar a página novamente. Além disso, você pode alternar entre um tema claro e um tema escuro, e a sua preferência de estilo também é salva.

## ✨ Funcionalidades

  * **Salvar Nome:** Digite seu nome no campo de texto e clique em "Salvar Nome". A aplicação armazena seu nome no `localStorage`.
  * **Persistência de Dados:** O nome salvo é automaticamente carregado e exibido na mensagem de boas-vindas ao recarregar a página ou abrir o site novamente.
  * **Limpar Dados:** O botão "Limpar" remove o nome do `localStorage`, restaurando a página ao seu estado inicial.
  * **Alternador de Tema:** Alterne entre um tema claro e um tema escuro com um simples clique.
  * **Persistência do Tema:** Sua escolha de tema é salva no `localStorage`, garantindo que a página sempre carregue com o estilo que você preferir.

## 🛠️ Tecnologias Utilizadas

  * **HTML:** Estrutura básica da página.
  * **CSS:** Estilização completa, incluindo a lógica para alternar os temas.
  * **JavaScript:** Lógica principal da aplicação para manipular o DOM e a API `localStorage`.

-----

## 📦 Como Funciona o `localStorage`

O `localStorage` é uma API do navegador que permite armazenar dados de forma persistente. Os dados salvos continuam disponíveis mesmo depois que você fecha o navegador.

  * **Salvar dados:** Usamos `localStorage.setItem('chave', 'valor')`. No seu projeto, a chave `'nomeUsuario'` é usada para armazenar o nome.
  * **Recuperar dados:** Usamos `localStorage.getItem('chave')`. Quando a página carrega (`window.onload`), o script verifica se há um nome salvo. Se sim, ele é exibido na tela.
  * **Limpar dados:** O método `localStorage.clear()` é usado para remover todos os dados armazenados no domínio do site.

-----
