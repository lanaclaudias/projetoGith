<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <title>Flexbox</title>
    <style>
        *,
        *::befone,
        *::after {
            box-sizing: content-box;
        }

        body {
            margin-top: 320x;
            margin-left: 450px;
            width: 600px;
            height: 100px;
            margin-inline: auto;

        }

        
        .flex-container >  div {
            color: #0e0e0e;
            font-size: 0.9em;
            padding: 15px;
            background-color: #efefef;
            width: 10%;
            height: 12%;
            margin-inline-start: 30px;
            float: left;
            margin-top: 60px;
            text-align: center;
            margin-left: 25px ;
            
     
        }
            

        

        aside {
            color: #020202;
            font-size: 1em;
            text-align: center;
            padding: 8px;
            background-color: #dbdcd1;
            background: #bc3edb;
            width: 100px;
            height: 379px;
            margin-left: auto;
            float: right;
        }

        header {
            background: #b188c3db;
            width: 600px;
            height: 95px;
            margin-right: auto;
            text-align: center
        }

        footer {

            color: #000000;
            font-size: 1em;
            background: #b188c3db;
            width: 600px;
            height: 95px;
            margin-bottom: 20;
            text-align: center
        }

        article {
            color: #000000;
            font-size: 1em;
            text-align: center;
            height: 300px;
            width: 360;
            background-color: rgb(231, 187, 227);

        }

        h1 {
            text-align: center;
        }

        nav {
            color: #000000;
            font-size: 1em;
            text-align: center;
            padding: 8px;
            background-color: #dbdcd1;
            background: #a108f3;
            width: 100px;
            height: 379px;
            margin-left: auto;
            float: right;

        }
       

    </style>
</head>

<body>
    <h1 id="h1">
        Layout com flexbox - III</h1>

    <main class="flex-container">
        <header id="header">
            < Header>
        </header>


        <nav id="nav">
            < nav>
        </nav>

        <aside id="aside">
            < aside>
        </aside>

        <article id="article">
            < article>
            <div class="flex-container">
                <div>1</div>
                <div>2</div>
                <div style="flex: grow 2;">3</div>
                <div>4</div>
                <div>5</div>
                <div>6</div>
            </div>
        </article>

        <footer id="footer">
            < Footer>
        </footer>

    </main>
    </header>
</body>

</html>
