<template>
    <main class="p-1 p-md-5 d-grid align-items-center">
        <section class="py-3 px-4 mx-auto bg-white rounded-5 ">
    
            <div class="d-flex flex-wrap align-items-center justify-content-between">
                <img class="d-block" style="max-width:120px" alt="" src="https://medicamentos.tzedaka.org.ar/public/logotzedaka-1@2x.png">
                <img class="d-block" style="max-width:120px" alt="" src="https://medicamentos.tzedaka.org.ar/public/logoprograma-salud-1@2x.png">
            </div>
    
            <div class="text-center">
                <h3 class="pt-5 pb-3">
                    ¡Bienvenidos!<br>
                    Al Banco Comunitario de Medicamentos
                </h3>
                <p>
                    El Banco Comunitario de Medicamentos es el programa de la
                    Fundacion Tzedaká de provisión gratuita de medicamentos a personas
                    en situación de vulnerabilidad en todo el país.
                </p>
                <p>
                    Con nuestro equipo de voluntarios y farmacéuticos convertimos las
                    donaciones que recibimos en tratamientos médicos que -a través de
                    una red formada por hospitales públicos, centros de salud y
                    organizaciones sociales- llegan a más de 50.000 personas.
                </p>
                <div id="access" class="pt-3 d-grid gap-2 mx-auto">
                    <button class="btn btn-solicitar">
                        <img alt="" src="https://medicamentos.tzedaka.org.ar/public/union.svg"> Solicitar medicamento Institución
                    </button>
                    <button class="btn btn-solicitar">
                        <img alt="" src="https://medicamentos.tzedaka.org.ar/public/vector-stroke-2.svg"> Solicitar medicamento Particular
                    </button>
                    <button class="btn btn-donar">
                        <img alt="" src="https://medicamentos.tzedaka.org.ar/public/vector-stroke-1.svg"> Donar medicamento
                    </button>
                </div>
            </div>
        </section>

    </main>
</template>

<style lang="scss" scoped>
    main{
        height: 100dvh;
        background-position: center;
        background-size: cover;
        background-image:linear-gradient( 115.57deg, rgba(46, 119, 192, 0.78), rgba(54, 46, 147, 0.78) 97.66% ), url('https://medicamentos.tzedaka.org.ar/public/background62308891@2x.png');
    }   
    section{
        max-width: 600px;
    }
    #access{
        max-width:380px;
        .btn{
            color: white;
            margin-bottom: 1em;
            font-weight: bold;
        }
        .btn-solicitar{
            background-color: #2e77c0;
        }
        .btn-donar{
            background-color: #5b248e;
        }
    }
</style>