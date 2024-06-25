<template>
    <div class="carnet">
        <aside>
            <div>
                <span>CEDULA DE INDENTIDAD</span>
                <img
                    width="40"
                    src="./assets/images/chile_bandera.png"
                    alt=""
                />
            </div>

            <img src="./assets/images/foto_elon.jpg" alt="Elon_Musk" />
            <p>RUN {{ run }}</p>
        </aside>

        <main>
            <header>
                <p>REPUBLICA DE CHILE</p>
                <span>SERVICIO DE REGISTRO CIVIL E IDENTIFICACIÓN</span>
            </header>
            <section>
                <article>
                    <header>APELLIDOS</header>
                    <span>{{ apellidos }}</span>
                </article>
                <article>
                    <header>NOMBRES</header>
                    <span>{{ nombres }}</span>
                </article>

                <div class="grid-2-colums">
                    <article>
                        <header>NACIONALIDAD</header>
                        <span>{{ nacionalidad }}</span>
                    </article>
                    <article>
                        <header>SEXO</header>
                        <span>{{ sexo }}</span>
                    </article>
                </div>
                <div class="grid-2-colums">
                    <article>
                        <header>FECHA DE NACIMIENTO</header>
                        <span>{{ fechaNacimiento }} </span>
                    </article>
                    <article>
                        <header>NÙMERO DOCUMENTO</header>
                        <span>{{ numeroDocumento }}</span>
                    </article>
                </div>
                <div class="grid-2-colums">
                    <article>
                        <header>FECHA DE EMISIÒN</header>
                        <span>{{ fechaEmision }}</span>
                    </article>
                    <article>
                        <header>FECHA DE VENCIMIENTO</header>
                        <span>{{ fechaVencimiento }}</span>
                    </article>
                </div>
                <article>
                    <header>FIRMA DEL TITULAR</header>
                    <span>{{ firmaTitular }}</span>
                </article>
            </section>
        </main>
    </div>
</template>

<script>
export default {
    data() {
        return {
            run: "22.222.222-2",
            apellidos: "MUSK",
            nombres: "ELON REEVE",
            nacionalidad: "SUDAFRICANO",
            sexo: "M",
            fechaNacimiento: "28 JUN 1971",
            numeroDocumento: "222.222.222",
            fechaEmision: "01 ENE 2025",
            fechaVencimiento: "01 ENE 2030",
            firmaTitular: "X Æ A-12",
        };
    },
};
</script>
