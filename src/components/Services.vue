<template>
  <section class="service-section spad">
	<div class="container">
    <div id="quines">

      <h2 id="tituloServices">¿Quienes somos?</h2>

      <div class="card-deck mt-3">
        
        <div class="card text-center border-warning">
          <div class="card-body">
            <h4 class="card-title">Mision</h4>
            <p class="card-text">
              {{mision}}
            </p>
            <img class="rounded" src="gow.png" width="200" height="200" />
          </div>
        </div>

        <div class="card text-center border-warning">
          <div class="card-body">
            <h4 class="card-title">Vision</h4>
            <p class="card-text">
              {{vision}}
            </p>
            <img class="rounded" src="gow.png" width="200" height="200" />
          </div>
        </div>
      </div>
    </div>
		
      <!-- Portafolio de servicios-->
      <section id="serviciosEmpresa">
        <div class="section-title">
        <h2  id="tituloServices">Portafolio de Servicios</h2>
      </div>
      <div class="row">
        <div class="col-lg-4 col-md-6">
          <div class="service-box">
            <div class="sb-icon">
              <div class="sb-img-icon">
                <img src="/gow.png" alt />
              </div>
            </div>
            <h3 id="misServicios">Diseño</h3>
            <p>
              Marca,
              Publicidad,
              Asesoría de diseño,
              Identidad de marca,
              Logotipos.
            </p>
            <a href="#" class="readmore">READ MORE</a>
          </div>
        </div>
        <div class="col-lg-4 col-md-6">
          <div class="service-box">
            <div class="sb-icon">
              <div class="sb-img-icon">
                <img src="/defjam.png" alt />
              </div>
            </div>
            <h3 id="misServicios">Informatica</h3>
            <p>
              Creación de software,
              Creación de web site,
              Creación de aplicaciones móviles,
              Infraestructura de red,
              Soluciones de base de datos,
              Soluciones Frontend,
              Soluciones Backend.
            </p>
            <a href="#" class="readmore">READ MORE</a>
          </div>
        </div>
        <div class="col-lg-4 col-md-6">
          <div class="service-box">
            <div class="sb-icon">
              <div class="sb-img-icon">
                <img src="/gow.png" alt />
              </div>
            </div>
            <h3 id="misServicios">Mercadeo</h3>
            <p>
              Investigación de mercados,
              Ubicación de locales comerciales,
              Asesoría sobre precios y manejos contables,
              Soluciones para promociones efectivas,
              Focus group,
              Posicionamiento de marca,
              Fidelización de clientes,
              Marketing digital (Facebook, Instagram, youtube, whatsapp),
              Creación de nuevas empresa,
              Mejora de resultados y medición de desempeño,
              Promociones efectivas.
            </p>
            <a href="#" class="readmore">READ MORE</a>
          </div>
        </div>
        <div class="col-lg-4 col-md-6">
          <div class="service-box">
            <div class="sb-icon">
              <div class="sb-img-icon">
                <img src="/gow.png" alt />
              </div>
            </div>
            <h3 id="misServicios">Juridico</h3>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer sed dui eget lorem tincidunt.</p>
            <a href="#" class="readmore">READ MORE</a>
          </div>
        </div>
        <div class="col-lg-4 col-md-6">
          <div class="service-box">
            <div class="sb-icon">
              <div class="sb-img-icon">
                <img src="/defjam.png" alt />
              </div>
            </div>
            <h3 id="misServicios">¿Algo mas?</h3>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer sed dui eget lorem tincidunt.</p>
            <a href="#" class="readmore">READ MORE</a>
          </div>
        </div>
        <div class="col-lg-4 col-md-6">
          <div class="service-box">
            <div class="sb-icon">
              <div class="sb-img-icon">
                <img src="/gow.png" alt />
              </div>
            </div>
            <h3 id="misServicios">¿Algo mas?</h3>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer sed dui eget lorem tincidunt.</p>
            <a href="#" class="readmore">READ MORE</a>
          </div>
        </div>
      </div>
      </section>
      
    </div>
  </section>
</template>

<script>
export default {
  name: "Services",
  data() {
    return {
      mision: "Somos una empresa consultra de servicios profesionales especializada, competitiva e innovadora que busca impulsar el desarrollo empresarial por medio de metodologías eficientes, eficaces y efectivas, direccionando a nuestros clientes al progreso, desarrollo y actualización digital.",
      vision: "Ser la empresa  referente en el mercado nacional e internacional  posicionándonos como líderes reconocidos por nuestros servicios de calidad y la capacidad de innovar.  Para guiar a todas las empresas del mundo a la actualización, optimización, y transformación tecnológica dando un paso hacia el futuro.",
    };
  }
};

</script>