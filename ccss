// Script para scroll suave al hacer clic en los enlaces del menú

document.querySelectorAll('a[href^="#"]').forEach(anchor => {
    anchor.addEventListener('click', function (e) {
        e.preventDefault(); // Previene el salto brusco

        // Obtiene el destino del enlace (ej. "#ventajas")
        const targetId = this.getAttribute('href');
        const targetElement = document.querySelector(targetId);

        if (targetElement) {
            // Desplaza la vista suavemente hasta el elemento
            targetElement.scrollIntoView({
                behavior: 'smooth',
                block: 'start' // Alinea la parte superior del elemento con la parte superior de la ventana
            });
        }
    });
});
