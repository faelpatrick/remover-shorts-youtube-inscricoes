# remover-shorts-youtube-inscricoes
Codigo para remover Shorts da parte de Inscrições no Youtube

Não gosto de assistir Shorts misturados a videos longos, criei o codigo para remover os Shorts da pagina de inscrição do Youtube.
Quando quero ver videos curtos eu vejo, mas nao gosto de misturar, pois normalemente procuro videos longos para assistir enquanto faço alguma atividade.

Com o Youtube aberto na guia de Inscrições aperte F12 e cole na guia CONSOLE o codigo a seguir.

OBS: por enquanto remove somente os ja carregados na tela, vou bolar uma função para rodar o codigo ao scrollar a pagina.


document.querySelectorAll("[overlay-style=SHORTS]").forEach(e=>{
    e.parentElement
     .parentElement
      .parentElement
        .parentElement
          .parentElement
            .remove()

})
