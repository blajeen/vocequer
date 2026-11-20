# vocequer 🐶

Site engraçado de pergunta com **Sim** ou **Não**.

1. Você escreve a pergunta e clica em **Gerar link**.
2. Manda o link (tem botão de copiar e de WhatsApp).
3. Opcional: coloque seu nome e WhatsApp. Quando a pessoa clicar em Sim, aparece "Contar pra você", que abre o WhatsApp com a resposta pronta pra te enviar.
4. Quem abrir vê a pergunta: o **Não** foge entre 5 lugares da tela, em loop, cada vez que a pessoa tenta clicar.
   A cada fuga o **Sim** cresce e aparecem cachorrinhos.
5. Ao clicar em **Sim**: chuva de cachorrinhos e comemoração.

A pergunta vai no próprio link (`?q=...`), então não precisa de banco de dados.
É só um `index.html` (HTML + CSS + JavaScript puro), sem build.
