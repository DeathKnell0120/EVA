<template>
  <div id="MiCompo">
    <div class="container" id="elCon">
      <div class="front side">
        <div class="content" id="conteneEsta">
          <h1 id="miTitulo">CONTACTA CON NOSOTROS</h1>
        
           <div id="app" >
            <div class="container">
                <div class="row">
                    <div class="col-sm-6 col-sm-offset-3 form-group">
                        <label>
                            Nombre:
                        </label>
                        <input class="form-control" type="text" v-model="from_name"/>
                    </div>
                    <div class="col-sm-6 col-sm-offset-3 form-group">
                        <label>
                            Asunto:
                        </label>
                        <input class="form-control" type="text" v-model="subject" />
                     
                    </div>
                    <div class="col-sm-6 col-sm-offset-3 form-group">
                        <label>
                            Correo:
                        </label>
                        <input class="form-control" type="email" v-model="from_email"/>
                        
                    </div>
                    <div class="col-sm-6 col-sm-offset-3 form-group">
                        <label>
                            Mensaje:
                        </label>
                        <textarea class="form-control" v-model="message">
                        </textarea>
                    </div>
                    <div class="col-sm-6 col-sm-offset-3 text-center">
                        <button @click="enviar" class="btn btn-success">
                            Enviar
                        </button>
                    </div>
                </div>
            </div>
        </div>

        </div>
      </div>
    </div>

    <!-- Footer -->
    <footer class="footer">
      <div class="footer_content">
        <div class="footer_logo" align="center">
          <a class="footer_message" href="#">{{contacto}}</a>
        </div>
        <div class="footer_social">
          <ul>
            <a href="URL" target="_blank">
              <img
                alt="Sígueme en Facebook"
                height="60"
                width="60"
                src="https://3.bp.blogspot.com/-CmJ5WAZqDs4/XCrIx8_5MsI/AAAAAAAAH_Q/7eW-g_nxq0E1yZn72HLi5fd1jLVtOclVwCLcBGAs/s1600/facebook2.png"
                title="Sígueme en Facebook"
                hspace="10"
                vspace="10"
              />
            </a>

            <a href="URL" target="_blank">
              <img
                alt="Sígueme en Instagram"
                height="60"
                width="60"
                src="https://4.bp.blogspot.com/-Ilxti1UuUuI/XCrIy6hBAcI/AAAAAAAAH_k/QV5KbuB9p3QB064J08W2v-YRiuslTZnLgCLcBGAs/s1600/instagram.png"
                title="Sígueme en Instagram"
                hspace="10"
                vspace="10"
              />
            </a>

            <a href="https://api.whatsapp.com/send?phone=+573008239720&text=Quiero sus servicios" target="_blank">
              <img
                alt="Sígueme en WhatsApp"
                height="60"
                width="60"
                src="https://2.bp.blogspot.com/-hJd7RLbG6dQ/XCrI389R_CI/AAAAAAAAIA8/2zdJ54oo7GAjqppIbfin0jvgf6cvk3VPgCLcBGAs/s1600/whatsapp.png"
                title="Sígueme en WhatsApp"
                hspace="10"
                vspace="10"
              />
            </a>

            <a href="URL" target="_blank">
              <img
                alt="Sígueme en LinKedIn"
                height="60"
                width="60"
                src="https://4.bp.blogspot.com/-0KtSvK3BydE/XCrIzgI3RqI/AAAAAAAAH_w/n_rr5DS92uk9EWEegcxeqAcSkV36OWEOgCLcBGAs/s1600/linkedin.png"
                title="Sígueme en LinKedIn"
                hspace="10"
                vspace="10"
              />
            </a>

            <a href="URL" target="_blank">
              <img
                alt="Sígueme en Youtube"
                height="60"
                width="60"
                src="https://1.bp.blogspot.com/-CUKx1kAd-ls/XCrI4UAvNqI/AAAAAAAAIBI/-i1neUt8kZwP6YOsFOXX5p0Bnqa29m-JgCLcBGAs/s1600/youtube2.png"
                title="Sígueme en Youtube"
                hspace="10"
                vspace="10"
              />
            </a>

            <a href="URL" target="_blank">
              <img
                alt="Sígueme en Twitter"
                height="60"
                width="60"
                src="https://3.bp.blogspot.com/-E4jytrbmLbY/XCrI2Xd_hUI/AAAAAAAAIAo/qXt-bJg1UpMZmTjCJymxWEOGXWEQ2mv3ACLcBGAs/s1600/twitter.png"
                title="Sígueme en Twitter"
                hspace="10"
                vspace="10"
              />
            </a>
          </ul>
        </div>
        <div class="copyright"></div>
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  name: "MiComponente",
  data() {
    return {
      contacto: "Siguenos en nuestras redes sociales"
    };
  }
};
</script>

