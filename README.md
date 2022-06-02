<style>
    /* RESET */
    * {
        box-sizing: border-box;
    }

    h1,
    h2,
    h3,
    h4,
    h5,
    h6,
    hr,
    p {
        margin: 0;
    }

    hr,
    button {
        border: none;
    }

    /* RESET */

    html {
        font-size: 14px;
    }

    h1 {
        all: unset;
    }

    /* TYPOGRAPHY */
    h1,
    h2,
    h3,
    h4,
    h5 p,
    small,
    a,
    button {
        line-height: 140%;
        color: var(--black);
    }

    h1,
    h2,
    h3,
    h4,
    h5,
    h6 {
        font-family: Verdana, Tahoma, sans-serif;
        font-weight: 700;
        line-height: 250%;
    }

    p,
    a,
    button {
        font-family: Arial, sans-serif;
        font-weight: 400;
    }

    h1 {
        font-size: 2rem;
    }

    h2 {
        font-size: 1.8rem;
    }

    h3 {
        font-size: 1.3rem;
    }

    h4 {
        font-size: 1.1rem;
    }

    h5 {
        font-size: 1rem;
    }

    p,
    a,
    button {
        font-size: 1rem;
    }

    a:hover {
        color: rgb(103, 103, 255);
    }

    small {
        font-size: 0.8rem;
    }

    header {
        padding-top: 8px 0;
        background-color: #212529;
        color: #e9ecef;
        text-align: center;
    }

    header nav {
        padding: 4px;
        background-color: #e9ecef;
    }

    header a {
        margin: 0 0.2rem;
        color: #212529;
    }

    main {
        margin: 14px 0;
        padding: 16px 24px;
        background-color: #212529;
        color: #e9ecef;
    }

    img {
        height: 40px;
        width: 50px;
    }

    #curiosidades a {
        text-decoration: underline;
    }

    footer {
        padding: 16px;
        background-color: #212529;
        color: #e9ecef;
    }

    @media screen and (max-width: 650px) {
        html {
            font-size: 12px;
        }
    }
</style>

<header>
    <h1>Júlio Pattuzzo</h1>
    <nav>
        <a href="#eu">Sobre mim</a>
        <a href="#skills">Skills</a>
        <a href="#curiosidades">Curiosidades</a>
        <a href="#caminho">Meu caminho até aqui</a>
        <a href="#contato">Contato</a>
        <a href="#estatisticas">Estatísticas</a>
    </nav>
</header>
<main>
    <section>
        <article id="eu">
            <h2>Sobre mim</h2>
            <article>
                <h3>Quem eu sou</h3>
                <p>Meu nome é Júlio Pattuzzo e tenho 21 anos. Autodidata desde criança, não me adequei ao ensino público
                    e
                    abandonei a escola ainda no ensino fundamental; adquiri livros (obrigado mãe) e assinei a plataforma
                    de ensino digital Stoodi (excepcional), terminando o ensino fundamental e médio atráves do
                    Encceja.
                    <br>
                    Considero a leitura, não só digital, mas física, algo de cunho fundamental; e é algo que faço diariamente. Gosto muitíssimo de jogos de simulação, pela emoção transmitida. Adoro escrever linhas de código, e não tenho preconceito; seja HTML, CSS ou uma linguagem de programação, eu estarei lá, escrevendo e amando o que faço.
                </p>
            </article>
            <br>
            <article>
                <h3>Missão & Valores</h3>
                <p>Tenho como missão utilizar meus conhecimentos para o crescimento da empresa, seja aplicando ou
                    compartilhando com os mais novos. Fora do trabalho, pretendo ensinar de forma objetiva e clara as
                    tecnologias que domino, a fim de contribuir com os novos desenvolvedores.<br>
                    Até 2025, me vejo como um desenvolvedor competente, com capacidades para atuar nas mais diversas
                    frentes, seja front-end ou back-end, abrangendo o desenvolvimento mobile.<br>
                    Sempre seguindo o que me é pedido, faço tudo conforme a ética profissional da empresa, contanto que
                    não
                    infrinja a minha ética pessoal; garantindo comprometindo e foco, além de estudo contínuo e
                    aprimoração.
                </p>
            </article>
            <br>
            <article>
                <h3>Educação</h3>
                <p>
                    Prezo por uma boa formação e por isso dou preferência ao estudo direto da fonte, estudando pelas
                    documentações oficiais (deixando de lado o YouTube e outras mídias, pela falta de teoria nos vídeos, algo essencial), além de documentações gerais, como: W3Schools e MDN.
                </p>
                <br>
                <p>Atualmente curso Análise e Desenvolvimento de Sistemas na Estácio.</p>
            </article>
        </article>
    </section>
    <br>
    <br>
    <section id="skills">
        <h2>Skills</h2>
        <div>
            <h3>Tecnologias estudadas</h3>
            <img width="50px" title="HTML" alt="HTML"
                src="https://raw.githubusercontent.com/devdevicon/master/html5/html5-original.svg">
            <img width="50px" title="CSS" alt="CSS"
                src="https://raw.githubusercontent.com/devdevicon/master/css3/css3-original.svg">
            <img width="50px" title="JavaScript" alt="JS" style="border-radius: 100px;"
                src="https://raw.githubusercontent.com/devdevicon/master/javascript/javascript-plain.svg">
        </div>
        <br>
        <div>
            <h3>Tecnologias em estudo</h3>
            <img width="50px" title="SASS" alt="SASS" src="sass.svg">
            <img width="50px" title="Git" alt="Git"
                src="https://raw.githubusercontent.com/jmnote/z-master/svg/git.svg">
            <img width="50px" title="React" alt="React" src="react.svg">
        </div>
        <br>
        <div>
            <h3>Tecnologias em seguida</h3>
            <img width="50px" title="PHP" alt="PHP"
                src="https://raw.githubusercontent.com/jmnote/z-master/svg/php.svg">
            <img width="50px" title="Node" alt="Node" src="node.svg">
            <img width="50px" title="SQL" alt="SQL" src="sql.svg">
        </div>
    </section>
    <br>
    <br>
    <section>
        <article id="curiosidades">
            <h2>Curiosidades</h2>
            <p>- Pretendo criar meu próprio framework CSS.</p>
            <p>- Criei uma <a href="https://greasyfork.org/pt-BR/scripts/430813-darkmode-3-0">extensão para deixar os sites em estilo DarkMode</a>.</p>
            <p>- Criei alguns <a
                    href="https://quizlet.com/Julio_Pattuzzo/folders/conhecimentos-front-end-empireo?x=1xqt&i=4bbcio">Quizes
                    para facilitar na memorização das Tags HTML e das propriedades CSS</a>, entre outros.
            </p>
            <p>- Se pesquisar meu nome no Google, achará algumas frases e textos que criei entre 2018 a 2021 (Ex
                aspirante a filósofo).<br>
                OBS.: Tais textos não refletem necessariamente meu pensamento atual.
            </p>
        </article>
    </section>
    <br>
    <br>
    <section>
        <article id="caminho">
            <h2>Meu caminho até aqui</h2>
            <p>Em meados de 2021, fiz o curso de Python do Professor Guanabara no YouTube; ao demonstrar interesse, complementei esse estudo numa plataforma de ensino de programação estrangeira, de nome Mimo.
            <br>
            Fiz alguns programas básicos, como calculadoras, manipuladores de arquivos .txt, explorei algumas bibliotecas como PyAutoGUI(lib de automação), PySimpleGUI(lib de interface gráfica), ChatterBot(lib de bot de conversa) entre outras... Infelizmente, com o tempo, perdi o interesse na linguagem por não me envolver em nenhum projeto real, então passei para o desenvolvimento mobile e fiz o curso de Kotlin da Google.
            <br>
            <br>
            Pelo mesmo motivo (além de me estressar com o Android Studio, terror de todo desenvolvedor) acabei deixando de lado o desenvolvimento mobile e busquei conhecer mais sobre o desenvolvimento WEB, onde me encontro desde então.
            </p>
        </article>
    </section>
</main>
<footer>
    <section>
        <article id="contato">
            <h2>Contato</h2>
            <a href="https://wa.me/5527996184548"><img title="Whatsapp" alt="Whatsapp" src="whatsapp.svg"></a>
            <a href="mailto:pattuzzo@protonmail.com?subject=Contato&body=%20%0D%20%0DContato%20do%20GitHub"><img title="ProtonMail" alt="ProtonMail" style="width: 150px;" src="protonmail.svg"></a>
            <a href="https://www.linkedin.com/in/j%C3%BAlio-pattuzzo/"><img title="Linkedin" alt="Linkedin" src="linkedin.svg"></a>
        </article>
    </section>
    <br>
    <section id="estatisticas">
        <h2>Estatísticas</h2>
        <a style="display: flex; justify-content: space-evenly;" href="https://github.com/pattuzzoj">
            <img style="width: 49%;"
                src="https://github-readme-stats.vercel.app/api?username=pattuzzoj&show_icons=true&theme=dark&include_all_commits=true&count_private=true" />
            <img style="width: 49%;"
                src="https://github-readme-stats.vercel.app/api/top-langs/?username=pattuzzoj&layout=compact&langs_count=7&theme=dark" />
    </section>
</footer>