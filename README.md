@import url('https://fonts.googleapis.com/css?family=Sacramento');

#tarjeta {
   altura:500px;
   ancho:800px;
   margen:5em automático;
   posición: fija;
  superior: -15px;
   izquierda: 25%;
   pantalla:flex;
   visibilidad:oculta;
}
#tarjeta h2 {
   tamaño de fuente: 3em;
   margen:0;
   color:rosa;
   alinear texto: centro;
}
#tarjeta p {
   tamaño de fuente: 1.5em;
   alinear texto: justificar;
   relleno-izquierda: 30px; /* Espacio en blanco a la izquierda */
   relleno-derecha: 30px; /* Espacio en blanco a la derecha */
}


.lado {
   fondo:#eee;
   altura:550px;
   ancho:400px;
/* borde: 1px rojo sólido; */
   relleno:10px;
}
.lado.uno {
   ancho:320px;
   transformar:skew(10deg,20deg);
   fondo:gradiente-lineal(90deg, #fff, #fff 40%, #ddd);
}
.lado.dos {
   transformar:skew(10deg,-15deg);
   fondo:gradiente-lineal(-90deg, #fff, #fff 40%, #f0f0f0);
}

cuerpo {
   pantalla: flex;
   alinear-elementos: centro;
   justificar-contenido: centro;
   altura: 100vh;
   familia de fuentes: 'Sacramento', cursiva;
   color de fondo: #f1e3d3;
   desbordamiento: oculto;
 }
 
 .Día de San Valentín {
   posición: relativa;
   cursor: puntero;
 }
 
 .sobre {
   posición: relativa;
   filtro: sombra paralela(0 0 25px rgba(0,0,0,.3));
 }
 
 .sobre:antes {
   contenido:"";
   posición: absoluta;
   ancho:254px;
   altura:254px;
   color de fondo: #ff9494;
   transformar: rotar(-45 grados);
   radio del borde: 0 15px 0 0;
   izquierda:-37px;
   superior:-82px;
 }
 
 .sobre:después {
   contenido:"";
   posición: absoluta;
   color de fondo: #ff9494;
   ancho:360px;
   altura:225px;
   izquierda:-90px;
   superior:45px;
 }
 
 .corazón {
   posición: relativa;
   color de fondo: #e01911;
   pantalla: bloque en línea;
   altura: 180px;
   superior:50px;
   izquierda:0;
   transformar: rotar(-45 grados);
   ancho:180px;
   filtro: sombra paralela(0 -10px 25px rgba(0,0,0,.3));
   transición: .5s;
 }
   
 .corazón:antes, .corazón:después {
   contenido:"";
   color de fondo: #e01911;
   radio del borde: 50%;
   altura: 180px;
   ancho: 180px;
   posición: absoluta;
   }
   
 .heart:antes de {
   superior:-100px;
   izquierda:0;}
   
 .heart:después {
   izquierda:100px;
   arriba:0;}
 
 .frente {
   posición: absoluta;
   ancho:0;
   altura:0;
   borde derecho: 190px sólido #fbd2d2;
   borde superior: 113px sólido transparente;
   borde inferior: 113px sólido transparente;
   superior:44px;
   izquierda:80px;
   índice z:4;
 }
 
 .front:antes {
   contenido:"";
   posición: absoluta;
   ancho:0;
   altura:0;
   borde izquierdo: 190px sólido #fbd2d2;
   borde superior: 113px sólido transparente;
   borde inferior: 113px sólido transparente;
   superior:-113px;
   izquierda:-170px;
 }
 
 .front:después {
   ancho:0;
   altura:0;
   posición: absoluta;
   contenido:"";
   borde inferior: 150px sólido #fce7e9;
   borde derecho:180px sólido transparente;
   borde izquierdo: 180px sólido transparente;
   superior:-36px;
   izquierda:-170px;
 }
 
 .texto {
   posición: absoluta;
   familia de fuentes: arial;
   espaciado entre letras: 5px;
   alinear texto: centro;
   color: blanco;
   índice z:2;
