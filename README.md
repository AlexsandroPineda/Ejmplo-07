<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <link rel="stylesheet" href="estilo.css">
    <title>Tabla de Multiplicar</title>
</head>

<body>
<script src="script01.js"></script>

    <header id="Cabecera">
        <nav>
            <p>Saludos</p>
        </nav>
    </header>

    <main>
        <div class="contenedor">
            <form>
                <a class="vinculoForm" href="#" onclick="redimensionar('RH')"> Cuadro1: Redim Horizontal</a>
                <a class="vinculoForm" href="#" onclick="redimensionar('RV')"> Cuadro2: Redim Vertical </a>
                <a class="vinculoForm" href="#" onclick="redimensionar('TH')"> Cuadro3: Trasl Horizontal </a>
                <a class="vinculoForm" href="#" onclick="redimensionar('TV')"> Cuadro4: Trasl Vertical</a>
                <a class="vinculoForm" href="#" onclick="redimensionar('EHV')"> Cuadro5: Escala H y V</a>

<!--                 <button name="button" value="Enviar" onclick="redimensionar()">Redimensionar</button> -->
            </form>
            <aside>
                <div class="elementos">
                    <div class="elem cuadro1" id="cuadro1" >

                    </div>
                    <div class="elem cuadro2" id="cuadro2" >

                    </div>
                    <div class="elem cuadro3" id="cuadro3" >

                    </div>
                    <div class="elem cuadro4" id="cuadro4" >

                    </div>
                    <div class="elem cuadro5" id="cuadro5" >

                    </div>
                </div>


            </aside>
            <article>
                <p> parrafo dentro del Articulo </p>
            </article>
        </div>
    </main>
    <footer>
        <p> parrafo dentro del pie de pagina </p>
    </footer>
</body>
</html>

#menu{
    background-color: rgb(71, 51, 223);
    box-shadow: 2px 2px 8px;
    width: 120px;
}

.contenedor{
    display: inline-block;
    width: 100%;
    margin: 35px auto;
    border: 1px solid black;
    height: auto;
    overflow: scroll;
}

#Cabecera{
    border: 1px solid blue;
    background-color: chocolate;
    width: 0 auto;
}

.vinculoForm{
    display: inline;
    box-shadow: 3px 3px 5px #ccc;
    background-color: #818182;
    color: #fff;
    padding: 7px;
    border-radius: 5px;
    margin: 15px;
    text-decoration: none;
}
.vinculoForm:hover{
    box-shadow: 2px 2px 4px #bbb;
    background-color: #002752;
    color: #fff;
    padding: 5px;
    border-radius: 5px;
    margin: 15px;
    text-decoration: none;
}
.elem{
    width: 50px;
    height: 50px;
    background-color: silver;
    border: 1px solid black;
    margin: 2px auto;
    padding: 10px;
}
aside{
    margin: 30px;
}
.elementos{
    height: auto;
    width: 90%;
    border: 1px solid black;
    background-color: #c3e6cb;

}
