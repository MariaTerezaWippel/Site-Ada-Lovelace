# Site-Ada-Lovelace
index.html

<!DOCTYPE html>


  <html>
    <head>
      <title>Ada Lovelace</title> 
      <link href="css\style.css" rel="stylesheet"> 
    </head>
    <body>
      <h1>Mulheres que fizeram história na tecnologia</h1>
      <section> 
        <nav class="principal"> <nav id="menu">
          <ul> 
            <li> 
              <a href="#infancia">Infância</a>
            </li>


            <li> 
              <a href="#juventude">Juventude</a>
            </li>


            <li> 
              <a href="#vida adulta">Vida adulta</a>
            </li>
          </ul>
        </nav>    
        <h2>Ada Lovelace</h2>


        <p>Augusta Ada King, condessa de Lovelace, nasceu em Londres em 1815, mais conhecida como Ada Lovelace, foi a primeira pessoa a escrever um algoritmo para ser processado por uma máquina na história da computação.</p>


        <img src="adaPintura (2).png" alt="pintura colorida da ada"> 


        <section id="infancia"> 
          <h3 class="titulo-verde">Infância</h3>
          <p>Seu pai era o poeta romântico Lord Byron, conhecido por seus exageros como ter um urso domesticado em seu quarto e por atos (incomuns para a época), como se relacionar com homens e mulheres. Sua mãe era a rica e culta Annabella Milbanke, apaixonada por matemática e pouco paciente com as maluquices do marido.</p>


          <p>Lord Byron bebia demais o que resultou no divórcio quando Ada tinha só 5 semanas de vida. Annabella foi mãe solo preocupada em garantir que Ada não ficasse parecida com o pai. Investiu na educação rigorosa da menina contratando os melhores professores. Acreditava que, se a filha se interessasse por matemática e ciências, se afastaria da poesia e das tendências excêntricas herdadas do pai.</p>


          <p>Ada era fascinada por matemática e poesia (para desespero de sua mãe). Aos doze anos, encantou-se pela engenharia mecânica e escreveu um livro chamado Flyology (ou Voologia), com desenhos de um plano para a construção de uma máquina de voar. Ao contar para sua mãe sobre a máquina, Annabelle achou que Ada estava se desviando dos estudos e a reprimiu. Então, pediu para que Ada focasse em se tornar uma dama.</p>


          <img src="img.png" alt="Pintura de Ada criança segurando um desenho."> 
        </section> 


        <section id="juventude">
          <h3 class="titulo-vermelho">Juventude</h3>


          <p>Aos 17 anos, Ada foi apresentada à corte e passou a ser convidada para festas na cidade. Seu jeito inteligente e rápida atraiu muitos solteiros, mas ela se interessou por um velho matemático chamado Charles Babage, que lhe contou sobre a invenção que trabalhava há anos, a “máquina diferencial”, que fazia grandes cálculos.</p>


          <p>Charles gostou da jovem, ela era uma das poucas pessoas que se interessou e entendeu suas invenções. Quando Ada conheceu a máquina diferencial, viu nela muitas possibilidades que nem mesmo Charles havia pensado. O entusiasmo da jovem matemática o impressionava.</p>
        </section>


        <section id="vida adulta">
          <h3 class="titulo-amarelo">Vida adulta</h3>


          <p>Charles era viúvo e lutava por investimentos para os seus projetos. Ada se casou e teve 3 filhos. Em 1830, isso significava que ela deveria abandonar os estudos e se dedicar aos filhos. Trocava cartas com Charles, acompanhava o trabalho dele de longe. Tinha pouco tempo para os próprios estudos. Passou a resolver problemas matemáticos à noite, após as crianças dormirem. Ela queria era trabalhar com Charles em suas máquinas incríveis.</p>


          <p>Tempos depois, Charles criou o Engenho Analítico, melhor do que a máquina diferencial, pois seria capaz de analisar dados e guardar informações na memória. Algo tão revolucionário que poucas pessoas entenderam. Para divulgar sua nova máquina, precisaria publicar artigos em francês, língua que ele não sabia, mas Ada era fluente. Como ela entendia as criações de Charles, era a pessoa perfeita para traduzir esses artigos.</p>


          <p>Enquanto Ada traduzia o conteúdo, fazia anotações por conta própria, imaginava inúmeras possibilidades que a máquina teria. Não tardou para que suas anotações ficassem maiores do que o próprio artigo.</p>


          <p>Charles queria que a máquina resolvesse problemas matemáticos. Ada pensava em algo muito maior: os números poderiam representar coisas totalmente diferentes como letras e notas musicais. Escreveu instruções detalhadas com diagramas e tabelas explicando como o engenho analítico deveria processar uma equação matemática complicada. Assim, a máquina resolveria em segundos o que um humano levaria horas para solucionar. Os computadores ainda não existiam, mas Ada tinha acabado de criar o primeiro programa de computador. Ada não viveu para ver que suas ideias se transformariam nos computadores modernos que usamos hoje.</p>
        </section>


        <img src="adaTabela.png" alt="Pintura de Ada jovem ao lado de uma tabela com algoritmos"> 


      </section> 


      <h3>Conheça outras mulheres que fizeram história na tecnologia:</h3>


      <nav>
        <ul>
          <li>
            <a href="https://pt.wikipedia.org/wiki/Grace_Hopper" target="_blank">Grace Hopper</a>
          </li>


          <li>
            <a href="https://pt.wikipedia.org/wiki/Dorothy_Vaughan" target="_blank">Dorothy Vaughan</a> 
          </li>


          <li>
            <a href="https://pt.wikipedia.org/wiki/Margaret_Hamilton_(cientista_da_computa%C3%A7%C3%A3o)" target="_blank">Margaret Hamilton</a> 
          </li>


          <li>
            <a href="https://pt.wikipedia.org/wiki/Katherine_Johnson" target="_blank">Katherine Johnson</a> 
          </li>
        </ul>
      </nav>
      <h4>Quer saber mais sobre outras mulheres que fizeram história na programação? Deixe seu e-mail!</h4>
      <form>


        <label for="nome">Nome:</label>
        <input id="nome" type="text">


        <label for="email">Email:</label>
        <input id="email" type="email">


        <label for="telefone">Telefone:</label>
        <input id="telefone" type="number">
        <button id="BotaoEnviar">Enviar</button>
      </form>


    <script type="text/javascript" src="js/script.js"></script>  
    </body>
  </html> 


style.css

body{
  text-align:center; 
  font-family:Open Sans,sans-serif; 
  background-color:#8a71c9; 
  color:hsl(0, 0%, 100%); 
  margin: 0;
 }


 h2{
   color:#c347e6; 
   font-size:40px;  
  }


  .titulo-verde{
    color:#04ffaf; 
   }


   .titulo-vermelho{ 
     color:#ff9e9e; 
   }


   .titulo-amarelo{ 
     color:#ffe36d; 
   }


section { 
  width:60%; 
  margin: 0 auto;
} 


section section{ 
  width:100%;
}


 h1{
   font-size:60px;
   font-weight:300;
  } 


  h3{ 
    font-size:22px;
    font-style:Italic; 
  }


  p{ 
    font-size:20px;
    line-height:1.5; 
  } 


  img{ 
    width:100%;
  } 


  adaPintura(2){
    width:100%;
  }  


   adaTabela{
     width:100%; 
  } 


  ul{
    list-style-type:none; 
    padding-left:0;
   }


    nav ul li a{ 
      color:#99ffff;
      font-weight:700;
      line-height:2;
      text-decoration: none;
    } 


    .principal a{ 
      color:#ffffff; 
      text-decoration:underline;
      font-weight: normal;
    }


    #menu ul{ 
      background-color:#FF6CB5;
      color:#fff;
      height: 40px;
    } 


    .principal li{ 
      display:inline-block; 
      line-height: 2.5; 
      margin: 0 89px;
    }


form button{ 
  background-color: #3df53d;
  border: 1px solid transparent;
  padding: 2px 20px;
  border-radius: 3px;
  margin-bottom: 30px;
}

script.js

document.getElementById("BotaoEnviar").addEventListener("click", validaformulario ) 


function validaformulario(){ 
  if(document.getElementById("nome").value != "" &&document.getElementById("email").value != "" &&
     document.getElementeById("telefone").value != ""){ 
       
      alert("Prontinho! você receberá as novidades.")
  }else{ 
      alert("Por favor, preencha os campos nome, email e telefone.") 
  } 
} 
