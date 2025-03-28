<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="styly.css">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
</head>

<body>
    <h1 class="nadpis">Pexeso</h1>
    <button id="hrat" type=" button" class="btn btn-primary">Hrát</button>

    <hr>

    <div id="hraciPole" class="hraciPole"></div>








    <script>
        var ovoce = ['🍎', '🍎', '🍌', '🍌', '🍇', '🍇', '🍉', '🍉', '🍓', '🍓', '🍒', '🍒', '🥝', '🥝', '🍍', '🍍'];
        var hrat = document.getElementById("hrat");
        var hraciPole = document.getElementById("hraciPole");
        var otoceneKarty = [];
        var spravneDvojic = 0;

        hrat.addEventListener("click", function () {
            hrat.innerText = "Hrát znovu"
            ovoce.sort(() => 0.5 - Math.random());
            hraciPole.innerHTML = "";
            ovoce.forEach(emoji => {
                hraciPole.innerHTML += `<div onclick="otoceni(this)" class="zavrenaKarta"><div class="iconHolder">` + emoji + `</div></div>`
            });
        })

        function otoceni(element) {
            element.classList.add("otocenaKarta");
            element.classList.remove("zavrenaKarta");
            element.removeAttribute("onclick");
            otoceneKarty.push(element);

            if (otoceneKarty.length == 2) {
                var karta1 = otoceneKarty[0].querySelector(".iconHolder").innerText;
                var karta2 = otoceneKarty[1].querySelector(".iconHolder").innerText;

                if (karta1 == karta2) {
                    console.log("Shoda! Karty zůstávají otočené.");
                    otoceneKarty = [];
                    spravneDvojic++
                    if (spravneDvojic == 8) {
                        console.log("Výborně! Dohráli jste pexeso.")

                    }
                } else {
                    console.log("Neshoda! Karty se otočí zpět.");
                    setTimeout(() => {
                        otoceneKarty.forEach(karta => {
                            karta.classList.remove("otocenaKarta");
                            karta.classList.add("zavrenaKarta");
                            karta.setAttribute("onclick", "otoceni(this)");
                        });
                        otoceneKarty = [];
                    }, 1500);
                }
            }
        }
    </script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz"
        crossorigin="anonymous"></script>
</body>

</html>
