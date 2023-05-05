# estetica
site simples... aprendendo aos poucos com dio.me
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Template - Utilizar como modelo</title>
    <link rel="stylesheet" href="base.css">


</head>
<style> 
    html, body {
    margin: 0;
}
body {
    background-color: #000000;
    display: flex;
    justify-content: center;
}

.wrapper {
    width: 1200px;
    display: flex;
    margin: 0 auto;
    background-color:rgb(103, 93, 0);
}
.main {
    display: flex;
    flex-flow: column;
    width: 85%;
}
.menu {
    width: 15%;
    background-color: aqua;
    padding: 10px 20px 0px;
}

.content {
    background-color: rgb(190, 188, 188);
    min-height: 300px;
    padding: 20px;
}

</style>

<body>
    
    <div class="wrapper">
        <div class="menu">
            <!-- Aqui vai o seu menu -->
            <ul>
                <li><a href="#">Início</a></li>
                <li><a href="#">Sobre a clínica</a></li>
                <li><a href="#">Horário de Atendimento</a></li>
                <li><a href="#">Contato</a></li>
            </ul>
        </div>
    </div>

    <div class="main">
        <div class="header">
            <div>
              
              
                <img src="banner.png.png" width="1430" height="400"
                title=“Praia tropical na América do Sul”>
              
       
            </div>

        
       

        <div class="content">
            <!-- Content -->
            <!-- Aqui vai o seu conteúdo -->
            <label id="textAbout">
                <h1> Sobre nossa clínica</h1>
                <p> Bem-vindo(a) à nossa clínica estética, onde oferecemos uma ampla gama de serviços para ajudar a melhorar a aparência e autoestima de nossos pacientes. Somos especializados em tratamentos de beleza, rejuvenescimento facial e corporal, emagrecimento, entre outros.</p>
                    
                <p>Nossos profissionais altamente qualificados estão sempre atualizados com as últimas tendências e tecnologias da indústria estética, permitindo que ofereçamos serviços inovadores e de alta qualidade.</p>
                    
                <p> Nossa clínica oferece uma variedade de tratamentos, incluindo <u>tratamentos faciais</u> como peelings químicos, microagulhamento, radiofrequência, além de preenchimentos e toxina botulínica. Também oferecemos procedimentos corporais, como criolipólise, carboxiterapia, drenagem linfática e tratamentos para celulite.</p>
                    
                <p>  Nós nos esforçamos para oferecer um ambiente relaxante e acolhedor para nossos pacientes, onde eles possam se sentir confortáveis e confiantes de que receberão o melhor atendimento possível. Entendemos que cada paciente tem necessidades e objetivos únicos, por isso trabalhamos em colaboração para desenvolver um plano personalizado que atenda às suas necessidades específicas.</p>
                    
            <p>Nosso objetivo é ajudá-lo a alcançar a aparência desejada, permitindo que você se sinta confiante e radiante. Entre em contato conosco hoje mesmo para agendar uma consulta e descubra como podemos ajudá-lo a alcançar seus objetivos estéticos.</p>
                
            
                </p>
            </label>

        </div>


        <div class="footer">
         
            <div>
          
        <div class="main">
            <div class="header">
               
                <!-- Aqui vai o seu header -->
                <div class="content">
                    <!-- Content -->
                    <!-- Aqui vai o seu conteúdo -->
                    <fieldset title="Contatos" id="idFieldsetContatos">
                        <legend>Contatos</legend>
                        <div>
                            <label>Telefone (21)0000-0000</label><br>
                            <label>WhatsApp (21)0000-0000</label>
                        </div>
    
                        <div>
                            <label>Email Estética@mail.com</label><br>
                            <label>Instagram @dr.joelma.oliveira</label>
                        </div>
    
                    </fieldset>
    
                    <fieldset id="idFieldsetEndereco">
                        <legend>Endereço</legend>
                        <div id="idDivFieldsetEndereco">
                            <label>
                                <label id="textoEndereco">Praça Nossa Sra. de Nazaré, 33 - Anchieta, Rio de Janeiro - RJ, 21645-430</label>
                            </label>
    
    
                          <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d58839.475854731754!2d-43.47435545136718!3d-22.822196699999996!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x9963b26d941de9%3A0xeda643b52d838f07!2sDRA.%20Joelma%20Oliveira%20Est%C3%A9tica%20Avan%C3%A7ada!5e0!3m2!1spt-BR!2sbr!4v1683291696992!5m2!1spt-BR!2sbr" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe> </iframe>
                        </div>
                    </fieldset>
    
                    <fieldset title="Fale conosco">
                        <legend>Fale conosco</legend>
                        <div id="idFormulario">
                            <form action="post">
                                <label for="nome">Nome completo</label><br>
                                <input id="nome" type="text" required /><br>
                                <label id="email">Email</label><br>
                                <input id="email" type="email" required /><br>
                                <label id="assunto">Assunto</label><br>
                                <input id="assunto" type="text" required /><br>
                                <label>Messagem</label><br>
                                <textarea rows="10" cols="50" placeholder="Escreva sua mensagem aqui"></textarea><br>
                                <button type="reset">Limpar</button>
                                <button type="submit">Enviar</button>
                            </form>
                        </div>
                    </fieldset>
                </div>
    
    
            
            </div>

        </div>
    </div>
</body>
</html>
