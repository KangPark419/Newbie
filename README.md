<!DOCTYPE html>

<html>

    <head>
        <meta charset="utf-8">
        <title>Tamplate Web Site</title>

        <style>
            body{margin: 0;}

            header{
                height: 200px;
                background-color: tomato;
                display: flex;
                flex-direction: column;
                align-items: center;
                justify-content: center;
                color: white;
            }

            nav{
                display: flex;
                background-color: #333333;
            }

            nav a{
                color: white;
                padding: 14px 20px;
                text-decoration: none;
                text-align: center;
            }

            nav a:hover{
                background-color: #dddddd;
                color: black;
            }

            #container{
                display: flex;
                flex-wrap: wrap;
            }

            aside{
                flex-grow: 3;
                background-color: #f1f1f1;
                padding: 20px;
            }

            article{
                flex: 7;
                background-color: white;
                padding: 20px;
            }

            .fakeimg{
                background: #aaaaaa;
                width: 100%;
                padding: 20px;
            }

            footer{
                padding: 20px;
                text-align: center;
                background: gray;
            }

            @media all and (max-width: 600px){
                #container, nav{
                    flex-direction: column;
                }
            }
            
        </style>
    </head>

    <body>
        <div style="background-color: yellow; padding: 5px;">
            <h4 style="text-align: center;">notice region</h4>
        </div> 

        <header>
            <h1>My Website</h1>
            <p>With a <strong>flexible</strong> layout.</p>
        </header>

        <nav>
            <a href="#">Link</a>
            <a href="#">Link</a>
            <a href="#">Link</a>
            <a href="#">Link</a>
        </nav>

        <div id="container">
            <aside>
                <h2>About me</h2>
                <h5>Photo of me:</h5>
                <div class="fakeimg" style="height: 200px;">Image</div>
                <p>Some text about me</p>

                <h3>More Text</h3>
                <p>This is text region</p>
                <div class="fakeimg" style="height: 60px;">Image</div>
                <div class="fakeimg" style="height: 60px;">Image</div>
                <div class="fakeimg" style="height: 60px;">Image</div>
            </aside>

            <article>
                <h2>TITLE HEADING</h2>
                <h5>title description, Dec,7, 2021</h5>
                <div class="fakeimg" style="height: 200px;">Image</div>
                <p>Some text.....</p>
                <p>ahope LAVENDER FABRIC PERFUME</p>

                <h2>TITLE HEADING</h2>
                <h5>title description, Dec,7, 2021</h5>
                <div class="fakeimg" style="height: 200px;">Image</div>
                <p>Some text.....</p>
                <p>ahope LAVENDER FABRIC PERFUME</p>
            </article>

            </div>

            <footer>
                <h2>footer</h2>
            </footer>



        </div>




    </body>

</html>