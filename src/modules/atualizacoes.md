0 
Apagar botão voltar aos cursos

0.1
Apagar Logo

2
<div id="img"><img src="https://cestsegtrabalho.com.br/wp-content/uploads/2022/09/logo-e1663851774609.png" width="28%"></div>

3 - tirar 1 br respostas

3.5 
Numerar questões 1 a 5

4 - colocar nas oções ocultas das questoes
<div id="conteudo"></div>

9 - colocar no aprovado 
                //diminui espaço entre questões
                ocultarElementoHTML()
                // Pega NOME e CPF do aluno
var name = localStorage.getItem("name")
var cpf = localStorage.getItem("cpf")
window.alert(`Parabéns, ${name}, você foi aprovado`)
window.scroll(top)
var voceAprovado = `
<p id="linha">______________________________________________________</p>
<h4 id="nomeAluno">Nome do aluno(a): ${name}</h4>
<h4>CPF: ${cpf}</h4>
<h2>Parabéns, você foi aprovado(a)!</h2>`
                var SiteAprovado = `<div id="">
                    <h2 id="parabens">Parabéns, você foi aprovado(a)!</h2>
<h3 id="naoprecisa">Não precisa fazer mais nada, você já está registrado.</h3><br>
<h4 id="Escolha" style="font-weight: 600;">Escolha uma opção abaixo:</h4><br>
<button id="button_imprimir" onclick="window.print(); return false" style="cursor: pointer;">Baixar Prova: Opcional</button><br><br>
<a href="https://api.whatsapp.com/send?phone=5521973561012&text=Quero%20Solicitar%20Or%C3%A7amento"><button>Solicitar Orçamento</button></a><br><br>
<a href="https://cestsegtrabalho.com.br/index.php/produto/primeiros-socorros/"><button id="btn_certificado">Vi no site <br> Pagamento de Certificado <br> e Reciclagem</button></a><br><br>
<a href="https://cestsegtrabalho.com.br/"><button id="conteudoAprovado">Voltar aos Cursos</button></a><br><br>
                </div>`
                document.getElementById("idvoceAprovado").innerHTML = SiteAprovado
                document.getElementById('subtitulo').innerHTML = voceAprovado
                botaorefazer()
                corrigirdesaparecer()
                getNomeCPF()

10 - incluir funções abaixo
        // Pega NOME e CPF do aluno
        function getNomeCPF(nome_aluno, cpf_aluno){
            var nome_aluno = document.getElementById('nome_aluno').value
            var cpf_aluno = document.getElementById('cpf_aluno').value

            console.log(nome_aluno + cpf_aluno)
        }
        //ocultar elemento "conteudo" HTML
        function ocultarElementoHTML() {
                function Element1(){
                var node = document.getElementById("conteudo1")
                if (node.parentNode) {
                    node.parentNode.removeChild(node)
                }
            }
            function Element2(){
                var node = document.getElementById("conteudo2")
                if (node.parentNode) {
                    node.parentNode.removeChild(node)
                }
            }
            function Element3(){
                var node = document.getElementById("conteudo3")
                if (node.parentNode) {
                    node.parentNode.removeChild(node)
                }
            }
            function Element4(){
                var node = document.getElementById("conteudo4")
                if (node.parentNode) {
                    node.parentNode.removeChild(node)
                }
            }
            function Element5(){
                var node = document.getElementById("conteudo5")
                if (node.parentNode) {
                    node.parentNode.removeChild(node)
                }
            }
            Element1()
            Element2()
            Element3()
            Element4()
            Element5()
            }

11 Style

        #img{
            align-items: center;
            display: flex;
            flex-direction: column;
        }
        img{
            display: flex;
            text-align: center;
        }

        #nomeAluno{
            margin-top: -1.3%;
        }
12 Style
        @media (max-width:400px) {
            #nome_aluno{
            margin: 10px;
            width: 200px;
            }

            #cpf_aluno{
                width: 200px;
            }

            #nomeAluno{
            margin-top: -5%;
            }
        }

14
Apagar img visibity hidden do @ print
