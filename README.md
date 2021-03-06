<!DOCTYPE html>
<html lang="es">
    <head>
        <meta charset="utf-8" />
        <meta name="viewport" content="width=device-width, initial-scale=1" />
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous" />
        <title>Zorros</title>
        <link rel="preconnect" href="https://fonts.googleapis.com" />
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
        <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;600&display=swap" rel="stylesheet" />
        <style>
            :root {
                --bs-font-sans-serif: "Roboto", sans-serif;
                --bs-body-color: #000;
                --bs-body-bg: #DBDBEB;
            }
            @media (min-width: 992px) {
                header p {
                    text-align: justify;
                    text-justify: inter-word;
                }
            }
            h1 {
                font-size: calc(2rem + 2vw);
            }
        </style>
    </head>

    <body>
        <header class="container">
            <div class="row py-4">
                <div class="col-11 col-sm-10 col-md-9 col-lg-8 col-xl-7 col-xxl-6 mx-auto">
                    <h1 class="mb-3 mt-5 text-center">Zorros  </h1>
                    <h2 class="fs-6 mb-5 text-center text-uppercase">Isaías López</h2>
                    <p class="lead">Inspiración para personajes de caricaturas memorables, apreciados por sus características como la astucia y el intelecto y lamentablemente codiciados por su piel. Los zorros son una especie con un gran carisma y un aura de misterio, ya que poseen un carácter solitario y huraño, aunque algunas especies han sido aprovechadas para proteger granjas agrícolas de sus plagas naturales.</p>
                </div>
            </div>
        </header>

        <main class="container">
            <div class="row pb-5">
                <div class="col-11 col-sm-10 col-md-9 col-lg-8 col-xl-7 col-xxl-6 mx-auto">

                    <p>Se conoce como <strong>zorro</strong>, zorra o raposos a unas diez especies de mamíferos cuadrúpedos de la familia de los cánidos y perteneciente a la <strong>tribu Vulpini</strong>, es decir, el conjunto de especies de caninos que se consideran dentro de la familia de los zorros, <strong>esta misma posee gran variedad</strong> y se componen por los géneros Alopex (como el zorro polar), Fennecus (como el zorro del desierto), Otocyon (como el zorro orejudo), Urocyon (como el zorro americano) y Vulpes (como el zorro rojo). A continuación podrás revisar algunas especies de esta familia:</p>

                    <div id="proceso" class="my-5"></div>

                    <p>Como reciclamos parte importante del ejercicio de la clase pasada, nos quedará algo de tiempo. Aprovechémoslo para hacer algo de "ingeniería inversa".</p>

                    <p>Tomemos una gráfica mixta de la infografía <a href="https://multimedia.scmp.com/lifestyle/article/2183329/text-neck/index.html" target="_blank" class="link-dark">Why your smartphone is causing you ‘text neck’ syndrome</a>. Con "ingeniería inversa" podemos aprender cómo resolver algo como lo que sigue:</p>
<div class="bg-black">
                    <object type="image/svg+xml" data="img/problems.svg" class="w-100 d-none d-md-block"></object>

                    <object type="image/svg+xml" data="img/problems-m.svg" class="w-100 d-md-none"></object>
</div>
                    <p class="small text-muted my-5">¿Notaron cómo voy a buscar dos documentos SVG? Gracias a unas <a href="https://getbootstrap.com/docs/5.1/utilities/display/" target="_blank" class="link-secondary">clases de Boostrap</a>, hay uno que no se muestra antes de la pantalla mediana (problema-grande.svg) y hay otro que deja de mostrare en la pantalla mediana (problema-chico.svg).</p>

                    <p>Intenten otro ejercicio de "ingeniería inversa": Con la gráfica no figurativa bajo el subtítulo de <strong>Overview</strong> de <a href="https://multimedia.scmp.com/infographics/business/article/3041676/urban-competitiveness/" class="link-dark">Cities driving the world</a>.</p>
<div class="bg-white p-3">
                    <object type="image/svg+xml" data="img/comIndex-d.svg" class="w-100 d-none d-md-block"></object>

                    <object type="image/svg+xml" data="img/comIndex-m.svg" class="w-100 d-block d-md-none"></object>
</div>
<div class="bg-white mt-5 p-3">

                    <object type="image/svg+xml" data="img/population.svg" class="w-100 d-none d-md-block"></object>
</div>
            </div>
                </div>
            </div>
        </main>

        <footer class="bg-black">
            <div class="container">
                <div class="row py-3">
                    <div class="col-12">
                        <p class="d-flex justify-content-between small p-1 m-0">
                            <!--reemplaza el # que sigue con la URL de tu cuenta en GitHub-->
                            <a href="https://github.com/IsaiasLpez/Clase-08" class="link-light">Isaías López</a>
                            <a href="https://github.com/profesorfaco/dno075-2022-1/" class="link-light">Infografía Digital</a>
                            <a href="https://github.com/profesorfaco/dno075-2022-1/tree/main/clase-07" class="d-none d-lg-inline link-light">Lunes 25 de abril, 2022</a>
                        </p>
                    </div>
                </div>
            </div>
        </footer>
        <script>
            var datos = [
                {
                    img: "img/Zorro_darwin.svg",
                    txt: "    El <strong>zorro chilote (Lycalopex fulvipes)</strong> especie es endémica de Chile, clasificada como en peligro de extinción. Hasta 2014 se creía que existían únicamente dos distribuciones de población: una en los bosques de la isla grande de Chiloé y la otra en la zona montañosa costera del Parque Nacional Nahuelbuta.",
                },
                {
                    img: "img/Zorro_rojo.svg",
                    txt: "El <strong>zorro rojo (Vulpes vulpes)</strong> es la especie de zorro más abundante en el hemisferio norte, donde puede vivir en casi cualquier ecosistema. Es un generalista capaz de coexistir con especies más especializadas de zorros como el zorro ártico. El zorro rojo es capaz de sobrevivir en zonas urbanizadas y densamente pobladas por el hombre.",
                },
                {
                    img: "img/Zorro_murcielago.svg",
                    txt: "El <strong>zorro orejas de murciélago (Otocyon megalotis)</strong> es una subespecie africana de zorro. A los zorros de orejas de murciélago les encanta alimentarse de termitas que constituyen el 80% de su dieta. El estudio sugiere que un solo zorro con orejas de murciélago consume hasta 1,15 millones de termitas al año.",
                },
                {
                    img: "img/Zorro_tibetano.svg",
                    txt: "El <strong>zorro tibetano (Vulpes ferrilata)</strong> es pequeño y compacto, con pelaje suave y denso, hocico visiblemente estrecho, y cola tupida. Caza principalmente picas y tiene una relación comensal con el oso pardo, mientras este desentierra las picas, el zorro tibetano las atrapa cuando se le escapan al oso.",
                },
                {
                    img: "img/Zorro_artico.svg",
                    txt: "El <strong>zorro ártico (Alopex lagopus)</strong> es un animal increíblemente fuerte, capaz de sobrevivir a las gélidas temperaturas del Ártico, que pueden alcanzar los -50 ºC, en las tierras desarboladas en las que habita. Luce un hermoso pelaje blanco (a veces gris azulado) que ofrece un excelente camuflaje en invierno.",
                }
            ];

            datos.forEach((p, i) => {
                if (i % 2 == 0) {
                    document.getElementById("proceso").innerHTML += '<figure class="row d-flex align-items-center"><object type="image/svg+xml" data="' + p.img + '" class="img-fluid col-12 col-md-6" /></object><figcaption class="col-12 col-md-6"><p class="text-black-50">' + p.txt + '</p></figcaption></figure>';
                } else {
                    document.getElementById("proceso").innerHTML += '<figure class="row d-flex align-items-center"><object type="image/svg+xml" data="' + p.img + '" class="img-fluid col-12 col-md-6 order-md-2" /></object><figcaption class="col-12 col-md-6 order-md-1"><p class="text-md-end text-black-50">' + p.txt + '</p></figcaption></figure>';
                }
            });
        </script>
    </body>
</html>
