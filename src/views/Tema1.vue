<template lang="pug">
  .curso-main-container.pb-3.tema1
    BannerInterno
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
      .titulo-principal.color-acento-contenido
        .titulo-principal__numero
          span 1
        h1 Cuadro comparativo
  
      #t_1_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
        h2 1.1 Definición
  
      .row.justify-content-center.align-items-center.mb-0
        .col-10(data-aos="fade-down-right")
          .row.mb-0
            .col-md-4.mb-3
              figure
                  img(src='@/assets/curso/temas/tema1/img-1.svg', alt='')
            .col-md-7
              .row
                .col-lg-11
                  .bloque-texto-d.color-primario.p-3.mb-5
                    .bloque-texto-d__texto
                      p.mb-3 Un cuadro comparativo ofrece una representación visual de diversas opciones que pueden ser contrastadas entre sí. Este tipo de gráfico resalta las similitudes, diferencias y características clave, proporcionando una visión clara de las discrepancias esenciales entre los elementos analizados. No hay una regla general específica para los gráficos de comparación, ya que pueden representar tanto características cuantitativas como cualitativas. En su mayoría, la creación de estos gráficos es sencilla y pueden ser utilizados con fines educativos o para tomar decisiones informadas basadas en datos. 
      
      Separador 
  
      #t_1_2.titulo-segundo.color-acento-contenido(data-aos="fade-right")
        h2 1.2 Elementos que componen un cuadro comparativo 
  
      p.mb-4 Un cuadro comparativo tiene como principales elementos las columnas y las filas: 
  
      .row.justify-content-center.align-items-center.mb-5
        .col-10.col-md-10.col-lg-8.desktop(data-aos="fade-right")
          figure
            img.mb-4(src='@/assets/curso/temas/tema1/img-2.svg', alt='CASO CHEMCO: Fundada en 1965, ChemCo es un fabricante líder de baterías de automóvil en el mercado del Reino Unido. Desde entonces, ha estado a cargo del Sr. Jones, el fundador y propietario de la firma. En 1999, la empresa decidió apostar por la diversificación ampliando la línea de productos. El nuevo producto fueron baterías para carretillas elevadoras. Al mismo tiempo, el Sr. Marek fue nombrado vicepresidente senior de marketing de la empresa. Sin embargo, poco después de su exitosa diversificación hacia baterías para montacargas, las ventas en este segmento comenzaron a caer de manera constante. El Sr. Marek quería introducir algunos cambios radicales en la publicidad y la marca del nuevo negocio, pero el anticuado Sr. Jones rechazó la propuesta. En esta coyuntura en 2012, la empresa está perdiendo fuertemente en el negocio de baterías para montacargas y su participación en el mercado de baterías para automóviles también está disminuyendo. Jones le ha pedido a Marek que muestre un cambio de rumbo en la empresa dentro de un año. ¿Qué medidas debería tomar el Sr. Marek para sacar a la empresa de sus problemas?')
      
          .row.mb-0
            .col-md-4.mb-3
              figure
                  img(src='@/assets/curso/temas/tema1/img-3.svg', alt='')
            .col-md-8 
              ul.lista-ul
                li 
                  i.lista-ul__vineta
                  | <strong>Las columnas:</strong> usualmente son 2, pero pueden ser las que las que se necesiten. Allí van los objetos, procesos o elementos que se van a comparar. 
                li 
                  i.lista-ul__vineta
                  | <strong>Las filas:</strong>  en este espacio van los parámetros en que se comparan los elementos.
                li 
                  i.lista-ul__vineta
                  | <strong>Comparaciones:</strong> se escriben las semejanzas, diferencias y características de cada elemento. 
      
      .row.mt-5.mb-2
        .col-10.col-md-10.col-lg-12.movil
          a.anexo.mb-4(:href="obtenerLink('/downloads/Elementos_que_componen_un_cuadro_comparativo.pdf')" target="_blank")
            .anexo__icono
              img(src="@/assets/template/icono-pdf.svg")
            .anexo__texto
              p <strong>Descargar.</strong> Elementos que componen un cuadro comparativo 
  
      Separador 
      
      #t_1_3.titulo-segundo.color-acento-contenido(data-aos="fade-right")
        h2 1.3 Pasos para elaborar un cuadro comparativo
  
      p.mb-5 Para realizar un cuadro comparativo se deben seguir los siguientes pasos: 
  
      .row.justify-content-center.align-items-center.mb-5
        .col-10(data-aos="fade-down-right")
          .row.mb-0
            .col-md-6
              ol.lista-ol--cuadro.lista-ol--separador
                li 
                  .lista-ol--cuadro__vineta
                    span 1
                  | Organizar las ideas de lo que se quiere comparar. 
                li 
                  .lista-ol--cuadro__vineta
                    span 2
                  | Establecer e identificar los elementos que se van a comparar. 
                li 
                  .lista-ol--cuadro__vineta
                    span 3
                  | Determinar los parámetros de comparación entre los elementos.  
                li 
                  .lista-ol--cuadro__vineta
                    span 4
                  | Construir el cuadro en la herramienta digital que desee utilizar. 
                li 
                  .lista-ol--cuadro__vineta
                    span 5
                  | Realizar la comparación de cada elemento con su parámetro. 
  
            .col-md-6
              figure
                img(src='@/assets/curso/temas/tema1/img-4.png', alt='Imagen decorativa')
  
      Separador 
  
      #t_1_4.titulo-segundo.color-acento-contenido(data-aos="fade-right")
        h2 1.4 Recomendaciones para desarrollar un cuadro comparativo 
  
      p.mb-5 Para realizar un cuadro comparativo se deben seguir los siguientes pasos: 
  
      .row.mt-5.mb-3.justify-content-center.align-items-center(data-aos="fade-right")
        .col-lg-10.col-md-12
          .tarjeta-avatar-b.mb-5
            .tarjeta-avatar-b__img
              img(src='@/assets/curso/temas/tema1/img-5.svg' alt='AvatarTop')
            .tarjeta.tarjeta--azul(style="background-color:#CDF5E2")
              .p-4
                ul.lista-ul
                  li 
                    i.lista-ul__vineta
                    | Seleccionar bien los criterios en los desea enfocarse al comparar los elementos.
                  li 
                    i.lista-ul__vineta
                    | Identificar las ideas principales que se van a plasmar. El contenido debe ser claro, preciso y estructurado. 
                  li 
                    i.lista-ul__vineta
                    | El cuadro se debe leer de manera fácil, no extenderse en cada comparación. 
                  li 
                    i.lista-ul__vineta
                    | Puede hacerse una breve conclusión de los elementos más pertinentes del cuadro. 
        
      Separador 
  
      #t_1_5.titulo-segundo.color-acento-contenido(data-aos="fade-right")
        h2 1.5 Herramientas digitales para la elaboración de un cuadro comparativo  
  
      .row.justify-content-center.align-items-center.mb-5
        .col-10(data-aos="fade-down-right")
          LineaTiempoD.color-primario
            .row(numero="1" titulo="Microsoft Word")
              .col-md-12.mb-4.mb-md-0
                p Se utiliza para elaborar documentos, cuadros, gráficos etc. de calidad profesional. Es un procesador de texto desarrollado, tiene herramientas y formas que permiten agregar y editar el esquema a sus necesidades.
  
              .row.justify-content-center.align-items-center.mb-0
                .col-10.col-md-10.col-lg-12
                  figure
                    img(src='@/assets/curso/temas/tema1/img-7.png', alt='Texto que describa la imagen')
  
            .row(numero="2" titulo="Power Point")
              .col-md-12.mb-4.mb-md-0
                p  Es una herramienta que cuenta con una serie de características que la convierten en un instrumento fácil de manejar para crear esquemas. 
  
              .row.justify-content-center.align-items-center.mb-0
                .col-10.col-md-10.col-lg-12
                  figure
                    img(src='@/assets/curso/temas/tema1/img-8.png', alt='Texto que describa la imagen')
  
            .row(numero="3" titulo="Canva")
              .col-md-12.mb-4.mb-md-0
                p Es una herramienta donde se pueden realizar esquemas. Es gratuita y muy útil. 
  
              .row.justify-content-center.align-items-center.mb-0
                .col-10.col-md-10.col-lg-12
                  figure
                    img(src='@/assets/curso/temas/tema1/img-9.png', alt='Texto que describa la imagen')
            
            .row(numero="4" titulo="<em>Venngage</em>")
              .col-md-12.mb-4.mb-md-0
                p Es una herramienta <em>online</em> que permite crear cuadros comparativos en línea.
  
              .row.justify-content-center.align-items-center.mb-0
                .col-10.col-md-10.col-lg-12
                  figure
                    img(src='@/assets/curso/temas/tema1/img-10.png', alt='Texto que describa la imagen')
  
            .row(numero="5" titulo="<em>Lucidchart</em>")
              .col-md-12.mb-4.mb-md-0
                p Es una plataforma de diagramación que permite trabajar en un documento con otros usuarios al mismo tiempo.
                
              .row.justify-content-center.align-items-center.mb-0
                .col-10.col-md-10.col-lg-12
                  figure
                    img(src='@/assets/curso/temas/tema1/img-11.png', alt='Texto que describa la imagen')
  
      Separador 
  
      #t_1_6.titulo-segundo.color-acento-contenido(data-aos="fade-right")
        h2 1.6 Ejemplo de un cuadro comparativo 
  
      .row.justify-content-center.align-items-center.mb-5
        .col-10.col-md-10.col-lg-8.desktop(data-aos="fade-right")
          figure
            img.mb-2(src='@/assets/curso/temas/tema1/img-6.svg', alt='')
            figcaption Nota. Tomado de Educem Virtual. Cuadro comparativo. (s.f.) 
     
      .row.mt-5.mb-2
        .col-10.col-md-10.col-lg-12.movil
          a.anexo.mb-4(:href="obtenerLink('/downloads/Ejemplo_de_un_cuadro_comparativo.pdf')" target="_blank")
            .anexo__icono
              img(src="@/assets/template/icono-pdf.svg")
            .anexo__texto
              p <strong>Descargar.</strong> Elementos que componen un cuadro comparativo 
  
  
  
  
        
  </template>

<script>
export default {
  name: 'Tema1',
  components: {},
  data: () => ({
    // variables de vue
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>

<style lang="sass"></style>
