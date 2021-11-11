let msgTempoInsuficiente = "Tempo insuficiente" //se tempo menor que padrao
let msgPratoPronto = "Prato pronto, bom apetite!!!" // ok
let msgPratoInexistente = "Prato inexistente" // nao listado
let msgComidaQueimou = "Comida queimou" // se tempo dobro do padrao
let msgPratoExplodiu = "Kabumm" // se tempo triplo do padrao

let Pipoca = 1
let Macarrão = 2
let Carne = 3
let Feijão = 4
let Brigadeiro = 5

function microondas (prato, tempo) {
    
    var tempoPadrao = 0;
    var txtPrato = "outro prato";

    if(prato==1){tempoPadrao=10; txtPrato="pipoca";}
    else if(prato==2){tempoPadrao=8; txtPrato="macarrão";}
    else if(prato==3){tempoPadrao=15; txtPrato="carne";}
    else if(prato==4){tempoPadrao=12; txtPrato="feijão";}
    else if(prato==5){tempoPadrao=8; txtPrato="brigadeiro";}

    console.log("-> Colocando "+txtPrato+" no microondas e selecionando "+tempo+" segundos.");
    
    if(tempoPadrao == 0){console.log(msgPratoInexistente);}
    else if(tempo<tempoPadrao){console.log(msgTempoInsuficiente);}
    else if(tempo>=tempoPadrao*2 && tempo<=tempoPadrao*3){console.log(msgComidaQueimou);}
    else if(tempo>=tempoPadrao*3){console.log(msgPratoExplodiu);}

    console.log(msgPratoPronto);
}

// TODOS OS TESTES
microondas(Pipoca, 10); //1 - Pipoca – 10 segundos (padrão)
microondas(Macarrão, 8); //2 - Macarrão – 8 segundos (padrão)
microondas(Carne, 15); //3 - Carne – 15 segundos (padrão)
microondas(Feijão, 12); //4 - Feijão – 12 segundos (padrão)
microondas(Brigadeiro, 3); // se tempo menor que padrão
microondas(Brigadeiro, 8); //5 - Brigadeiro - 8 segundos (padrão)
microondas(Brigadeiro, 16); // se tempo dobro do padrão
microondas(Brigadeiro, 32); // se tempo triplo do padrão
microondas(10, 20); // não listado
