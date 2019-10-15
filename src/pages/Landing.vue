<template>
  <div>
    <div class="page-header page-header-small">
      <parallax
        class="page-header-image"
        style="background-image: url('img/bg6.jpg')"
      >
      </parallax>
      <div class="content-center">
        <div class="container">
          <h1 class="title" style="font-family: 'Audiowide', cursive; text-shadow: 3px 2px 10px #1B67CE; font-size:400%;">SN Mining</h1>
          <h2 style="font-size:300%; font-family: 'Shrikhand', cursive; text-shadow: 3px 2px 10px #1B67CE;">Especialistas en Mineria</h2>
          <!---
          <div class="text-center">
            <a href="#pablo" class="btn btn-info btn-icon btn-round">
              <i class="fab fa-facebook-square"></i>
            </a>
            <a href="#pablo" class="btn btn-info btn-icon btn-round">
              <i class="fab fa-twitter"></i>
            </a>
            <a href="#pablo" class="btn btn-info btn-icon btn-round">
              <i class="fab fa-google-plus"></i>
            </a>
          </div>
          --->
        </div>
      </div>
    </div>
    <div class="section section-about-us">
      <div class="container">
        <div class="row">
          <div class="col-md-8 ml-auto mr-auto text-center">
            <h2 style="font-family: 'Bungee Inline', cursive;">Sobre nosotros</h2>
            <h4 class="description" style="font-size:200%; font-family: 'Luckiest Guy', cursive;">
              Somos una empresa joven del sector minero dedicada 
              a realizar proyectos de mecánica eléctrica, 
              contamos con profesionales y equipamiento 
              para la mediana y gran minería.
            </h4>
          </div>
        </div>
        <div class="separator separator-info"></div>
        <div class="section-story-overview">
          <div class="row">
            <div class="col-md-6">
              <div
                class="image-container image-left"
                style="background-image: url('img/login.jpg')"
              >
                <!-- First image on the left side -->
                <p class="blockquote blockquote-info">
                  "A nivel latinoamericano, la minería peruana ocupa el primer 
                  puesto en producción de oro, zinc, estaño y plomo. A nivel mundial, 
                  ocupa el segundo lugar en producción de plata y cobre."
                  <br />
                  <small>-OSINERGMIN</small>
                </p>
              </div>
              <!-- Second image on the left side of the article -->
              <div
                class="image-container"
                style="background-image: url('img/bg3.jpg')"
              ></div>
            </div>
            <div class="col-md-5">
              <!-- First image on the right side, above the article -->
              <div
                class="image-container image-right"
                style="background-image: url('img/bg1.jpg')"
              ></div>
              <h3>
                La Misión, Visión y Valores de SN Mining
              </h3>
              <p>
                Nuestra <strong>Misión</strong> es brindar productos y servicios 
                mineros con estándares de calidad para poder satisfacer y superar 
                las necesidades y expectativas de nuestros clientes.
              </p>
              <p>
                Tenemos la <strong>Visión</strong> de ser reconocidos a nivel local
                y regional como lideres en la fabricación, desarrollo e implementación 
                de equipos y servicios mineros.
              </p>
              <p>
                Nuestros <strong>Valores</strong>: La pasión por un buen trabajo, 
                La satisfacción del cliente, La apertura a la mejora continua, La innovación
                en nuestros procesos y la Calidad personal y su integridad. 
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="section section-team text-center">
      <div class="container">
        <h2 class="title">Nuestro equipo</h2>
        <div class="team">
          <div class="row">
            <div class="col-md-4">
              <div class="team-player">
                <img
                  src="img/avatar1.jpg"
                  alt="Thumbnail Image"
                  class="rounded-circle img-fluid img-raised"
                />
                <h4 class="title">Felix Flores</h4>
                <p class="category text-info">Gerente General</p>
                <p class="description">
                  Ing. Mecanico con mas de 20 años de experiencia en Minería 
                </p>
                <!--<a href="https://www.linkedin.com/in/tomas-aguirre-quispe-30724637/" class="btn btn-info btn-icon btn-round"
                  ><i class="fab fa-linkedin"></i
                ></a>-->
                <a href="https://wa.me/51993526844?text=Me%20gustaría%20saber%20mas%20de%20SN%20Mining" class="btn btn-info btn-icon btn-round"
                  ><i class="fab fa-whatsapp"></i
                ></a>
                <a class="btn btn-info btn-icon btn-round" 
                  v-b-popover.hover.top="" title="felix.flores@snmining.com"
                  ><i style="color:white;" class="fab fa-telegram-plane"></i
                >
                </a>
              </div>
            </div>
            <div class="col-md-4">
              <div class="team-player">
                <img
                  src="img/avatar3.jpg"
                  alt="Thumbnail Image"
                  class="rounded-circle img-fluid img-raised"
                />
                <h4 class="title">Tomas Aguirre</h4>
                <p class="category text-info">Proyectos & Ingeniería</p>
                <p class="description">
                  Ing. Mecanico con mas de 20 años de experiencia en Minería 
                </p>
                <!--<a href="https://www.linkedin.com/in/tomas-aguirre-quispe-30724637/" class="btn btn-info btn-icon btn-round"
                  ><i class="fab fa-linkedin"></i
                ></a>-->
                <a href="https://wa.me/51993526844?text=Me%20gustaría%20saber%20mas%20de%20SN%20Mining" class="btn btn-info btn-icon btn-round"
                  ><i class="fab fa-whatsapp"></i
                ></a>
                <a class="btn btn-info btn-icon btn-round" 
                  v-b-popover.hover.top="" title="tomas.aguirre@snmining.com"
                  ><i style="color:white;" class="fab fa-telegram-plane"></i
                >
                </a>
              </div>
            </div>
            <div class="col-md-4">
              <div class="team-player">
                <img
                  src="img/avatar5.jpg"
                  alt="Thumbnail Image"
                  class="rounded-circle img-fluid img-raised"
                />
                <h4 class="title">Joel Ticse</h4>
                <p class="category text-info">Energía Renovable</p>
                <p class="description">
                  Especialista en Energía Renovable con mas de 10 años de experiencia. 
                </p>
                <!--<a href="https://www.linkedin.com/in/tomas-aguirre-quispe-30724637/" class="btn btn-info btn-icon btn-round"
                  ><i class="fab fa-linkedin"></i
                ></a>-->
                <a href="https://wa.me/51914854941?text=Me%20gustaría%20saber%20mas%20de%20SN%20Mining" class="btn btn-info btn-icon btn-round"
                  ><i class="fab fa-whatsapp"></i
                ></a>
                <a class="btn btn-info btn-icon btn-round" 
                  v-b-popover.hover.top="" title="joel.ticse@snmining.com"
                  ><i style="color:white;" class="fab fa-telegram-plane"></i
                >
                </a>
              </div>
            </div>
            <div class="col-md-4">
              <div class="team-player">
                <img
                  src="img/avatar2.jpg"
                  alt="Thumbnail Image"
                  class="rounded-circle img-fluid img-raised"
                />
                <h4 class="title">Jassuco Balbin</h4>
                <p class="category text-info">Administración & Finanzas</p>
                <!--<p class="description">
                  Especialista en Energia Renovable con mas de 10 años de experiencia 
                </p>-->
                <!--<a href="https://www.linkedin.com/in/tomas-aguirre-quispe-30724637/" class="btn btn-info btn-icon btn-round"
                  ><i class="fab fa-linkedin"></i
                ></a>-->
                <a href="https://wa.me/51936918717?text=Me%20gustaría%20saber%20mas%20de%20SN%20Mining" class="btn btn-info btn-icon btn-round"
                  ><i class="fab fa-whatsapp"></i
                ></a>
                <a class="btn btn-info btn-icon btn-round" 
                  v-b-popover.hover.top="" title="jassuco.balbin@snmining.com"
                  ><i style="color:white;" class="fab fa-telegram-plane"></i
                >
                </a>
              </div>
            </div>
            <div class="col-md-4">
              <div class="team-player">
                <img
                  src="img/avatar4.jpg"
                  alt="Thumbnail Image"
                  class="rounded-circle img-fluid img-raised"
                />
                <h4 class="title">Victor Ponce</h4>
                <p class="category text-info">Administración & Finanzas</p>
                <!--<p class="description">
                  Especialista en Energia Renovable con mas de 10 años de experiencia 
                </p>-->
                <!--<a href="https://www.linkedin.com/in/tomas-aguirre-quispe-30724637/" class="btn btn-info btn-icon btn-round"
                  ><i class="fab fa-linkedin"></i
                ></a>-->
                <a href="https://wa.me/51941693803?text=Me%20gustaría%20saber%20mas%20de%20SN%20Mining" class="btn btn-info btn-icon btn-round"
                  ><i class="fab fa-whatsapp"></i
                ></a>
                <a class="btn btn-info btn-icon btn-round" 
                  v-b-popover.hover.top="" title="victor.ponce@snmining.com"
                  ><i style="color:white;" class="fab fa-telegram-plane"></i
                >
                </a>
              </div>
            </div>
            <!--<div class="col-md-4">
              <div class="team-player">
                <img
                  src="img/eva.jpg"
                  alt="Thumbnail Image"
                  class="rounded-circle img-fluid img-raised"
                />
                <h4 class="title">Eva Jenner</h4>
                <p class="category text-info">Fashion</p>
                <p class="description">
                  You can write here details about one of your team members. You
                  can give more details about what they do. Feel free to add
                  some <a href="#">links</a> for people to be able to follow
                  them outside the site.
                </p>
                <a href="#pablo" class="btn btn-info btn-icon btn-round"
                  ><i class="fab fa-google-plus"></i
                ></a>
                <a href="#pablo" class="btn btn-info btn-icon btn-round"
                  ><i class="fab fa-youtube"></i
                ></a>
                <a href="#pablo" class="btn btn-info btn-icon btn-round"
                  ><i class="fab fa-twitter"></i
                ></a>
              </div>
            </div>-->
          </div>
        </div>
      </div>
    </div>
    <!--
    <div class="section section-contact-us text-center">
      <div class="container">
        <h2 class="title">Want to work with us?</h2>
        <p class="description">Your project is very important to us.</p>
        <div class="row">
          <div class="col-lg-6 text-center ml-auto mr-auto col-md-8">
            <fg-input
              class="input-lg"
              placeholder="First Name..."
              v-model="form.firstName"
              addon-left-icon="now-ui-icons users_circle-08"
            >
            </fg-input>
            <fg-input
              class="input-lg"
              placeholder="Email Here..."
              v-model="form.email"
              addon-left-icon="now-ui-icons ui-1_email-85"
            >
            </fg-input>
            <div class="textarea-container">
              <textarea
                class="form-control"
                name="name"
                rows="4"
                cols="80"
                v-model="form.message"
                placeholder="Type a message..."
              ></textarea>
            </div>
            <div class="send-button">
              <n-button type="info" round block size="lg"
                >Send Message</n-button
              >
            </div>
          </div>
        </div>
      </div>
    </div>
    -->
  </div>
</template>
<script>
import { Button, FormGroupInput } from '@/components';
export default {
  name: 'landing',
  bodyClass: 'landing-page',
  components: {
    [Button.name]: Button,
    [FormGroupInput.name]: FormGroupInput
  },
  data() {
    return {
      form: {
        firstName: '',
        email: '',
        message: ''
      }
    };
  }
};
</script>
<style>
@import url('https://fonts.googleapis.com/css?family=Audiowide|Bungee+Inline|Fredoka+One|Luckiest+Guy|Shrikhand&display=swap');
</style>
