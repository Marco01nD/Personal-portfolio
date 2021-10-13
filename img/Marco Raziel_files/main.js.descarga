let ubicacionPrincipal = window.pageYOffset; //menciona en que parte del la página te encuentras

  AOS.init();


// Parte del menu de navegación

window.addEventListener("scroll", function (){
   
    let desplazamientoActual = window.pageYOffset;

    if (ubicacionPrincipal >= desplazamientoActual) {
        document.getElementsByTagName("nav")[0].style.top = "0px"
    } else {
        document.getElementsByTagName("nav")[0].style.top = "-100px"
    }
    ubicacionPrincipal = desplazamientoActual;
})


// Menu

let enlacesHeader = document.querySelectorAll(".enlaces-header")[0];
let semaforo = true;

// Cambia los colores del menu hamburguesa y abre el menu 
document.querySelectorAll(".hamburger")[0].addEventListener("click", function () {
    if (semaforo) {
        document.querySelectorAll(".hamburger")[0].style.color = "#fff";
        semaforo = false;
    } else {
        document.querySelectorAll(".hamburger")[0].style.color = "#000";
        semaforo = true;
    }
 
    enlacesHeader.classList.toggle("menudos");
    

});


// Cambia los colores del menu hamburguesa y cierra el menu
document.querySelectorAll(".enlaces-header")[0].addEventListener("click", function () {
 if (semaforo) {
        document.querySelectorAll(".hamburger")[0].style.color = "#fff";
        semaforo = false;
    } else {
        document.querySelectorAll(".hamburger")[0].style.color = "#000";
        semaforo = true;
    }
 
    enlacesHeader.classList.remove("menudos")
    
});   
