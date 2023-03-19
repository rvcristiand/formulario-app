<script>
  // import { base } from "$app/paths";
  function handleClick() {
    alert( 'formulario enviado' );
  }
</script>  
  <form class="form-example">
      <div class="form-example">
          <label for="nombres" class="large-label">Nombres: </label>
          <input type="text" name="nombres" id="nombres"/>
      </div>
      <div class="form-example">
          <label for="apellidos" class="large-label">Apellidos: </label>
          <input type="text" name="apellidos" id="apellidos"/>
      </div>
      <div class="form-example">
          <label for="organizacion" class="large-label">Organización a la que pertence: </label>
          <input type="text" name="organizacion" id="organizacion"/>
      </div>
      <div class="form-example">
          <label for="tipo-actor" class="large-label">Tipo de actor: </label>
          <select name="tipo-actor" id="tipo-actor">
              <option value=""></option>
              <option value="Ciudadanía general">Ciudadanía general</option>
              <option value="grupos-internacionales">Grupos Internacionales</option>
              <option value="minorias">Minorías</option>
              <option value="organizaciones-sociales">Organizaciones sociales</option>
              <option value="victimas">Víctimas</option>
	      <option value="entidad-gubernamental">Entidad gubernamental</option>
          </select>
      </div>
      <div class="form-example">
          <label for="municipio-residencia" class="large-label">Municipio de residencia: </label>
          <input type="text" name="municipio-residencia" id="municipio-residencia"/>
      </div>
      <div class="form-example">
          <label for="departamento-residencia" class="large-label">Departamento de residencia: </label>
          <input type="text" name="departamento-residencia" id="departamento-residencia"/>
      </div>
      <div class="form-example">
          <label for="zona-residencia" class="large-label">Zona de residencia: </label>
          <select name="zona-residencia" id="zona-residencia">
              <option value=""></option>
              <option value="rural">Rural</option>
              <option value="urbana">Urbana</option>
          </select>
      </div>
      <div class="form-example">
          <label for="correo-electronico" class="large-label">Correo electrónico: </label>
          <input type="text" name="correo-electronico" id="correo-electronico"/>
      </div>
      <div class="form-example">
          <label for="telefono" class="large-label">Teléfono: </label>
          <input type="text" name="telefono" id="telefono"/>
      </div>
      <div class="form-example">
          <label for="tipo-espacio" class="large-label">Tipo de espacio: </label>
          <select name="tipo-espacio" id="tipo-espacio">
              <option value=""></option>
              <option value="audiencia-publica">Audiencia pública</option>
              <option value="foro-ciudadano">Foro ciudadano</option>
              <option value="panel-ciudadano">Panel ciudadano</option>
              <option value="encuentro-regional">Encuentro regional</option>
              <option value="red-social">Red social</option>
              <option value="correo-electronico">Correo electrónico</option>
              <option value="rup">RUP</option>
              <option value="otro">Otro</option>
          </select>
      </div>
      <div class="form-example">
          <label for="fecha-espacio" class="large-label">Fecha del espacio: </label>
          <input type="date" name="fecha-espacio" id="fecha-espacio"/>
      </div>
      <div class="form-example">
          <label for="municipio-espacio" class="large-label">Municipio del espacio: </label>
          <input type="text" name="municipio-espacio" id="municipio-espacio"/>
      </div>
      <div class="form-example">
          <label for="deparmento-espacio" class="large-label">Departamento del espacio: </label>
          <input type="text" name="departamento-espacio" id="departamento-espacio"/>
      </div>
      <div class="form-example">
          <label for="regional" class="large-label">Regional: </label>
          <select name="regional" id="regional">
              <option value=""></option>
              <option value="nacional">Nivel Nacional</option>
              <option value="amazonas">Regional Amazonas</option>
              <option value="antioquia">Regional Antioquia</option>
              <option value="arauca">Regional Arauca</option>
              <option value="atlantico">Regional Atlántico</option>
              <option value="bogota">Regional Bogotá</option>
              <option value="bajo-cauca-antioqueno">Regional Bajo Cauca antioqueño</option>
              <option value="bolivar">Regional Bolívar</option>
              <option value="boyaca">Regional Boyacá</option>
              <option value="caldas">Regional Caldas</option>
              <option value="caqueta">Regional Caquetá</option>
              <option value="casanare">Regional Casanare</option>
              <option value="cauca">Regional Cauca</option>
              <option value="cesar">Regional Cesar</option>
              <option value="cordoba">Regional Córdoba</option>
              <option value="cundinamarca">Regional Cundinamarca</option>
              <option value="choco">Regional Chocó</option>
              <option value="guainia">Regional Guainía</option>
              <option value="guajira">Regional Guajira</option>
              <option value="guaviare">Regional Guaviare</option>
              <option value="huila">Regional Huila</option>
              <option value="magdalena">Regional Magdalena</option>
              <option value="magdalena-medio">Regional Magdalena Medio</option>
              <option value="meta">Regional Meta</option>
              <option value="narino">Regional Nariño</option>
              <option value="norte-de-santander">Regional Norte de Santander</option>
              <option value="ocana">Regional Ocaña</option>
              <option value="pacifico">Regional Pacífico</option>
              <option value="putumayo">Regional Putumayo</option>
              <option value="quindio">Regional Quindío</option>
              <option value="risaralda">Regional Risaralda</option>
              <option value="san-andres">Regional San Andrés/Providencia y Santa Catalina</option>
              <option value="santander">Regional Santander</option>
              <option value="soacha">Regional Soacha</option>
              <option value="sucre">Regional Sucre</option>
              <option value="sur-de-bolivar">Regional Sur de Bolívar</option>
              <option value="sur-de-cordoba">Regional Sur de Córdoba</option>
              <option value="uraba-darien">Regional Urabá Darién</option>
              <option value="tolima">Regional Tolima</option>
              <option value="tumaco">Regional Tumaco</option>
              <option value="valle-del-cauca">Regional Valle del Cauca</option>
              <option value="vaupes">Regional Vaupés</option>
              <option value="vichada">Regional Vichada</option>
          </select>
      </div>
      <div class="form-example">
          <label for="fecha-registro" class="large-label">Fecha de registro: </label>
          <input type="date" name="fecha-registro" id="fecha-registro"/>
      </div>
      <div class="form-example">
          <label for="tipo-interaccion" class="large-label">Tipo de interacción: </label>
          <select name="tipo-interaccion" id="tipo-interaccion">
              <option value=""></option>
              <option value="Compromiso">Compromiso</option>
              <option value="Pregunta">Pregunta</option>
              <option value="Propuesta">Propuesta</option>
              <option value="Observación">Observación</option>
              <option value="Sugerencia">Sugerencia</option>
          </select>
      </div>
  <div class="form-example">
    <label for="descripcion-interaccion" class="large-label">Descripción de la interacción:</label>
    <textarea id="descripcion-interaccion"></textarea>
  </div>
      <div class="form-example">
          <label for="dependencia-responsable" class="large-label">Dependencia responsable de la gestión: </label>
          <select name="dependecia-responsable" id="dependecia-responsable">
              <option value=""></option>
              <option value="defensor-pueblo">Despacho del Defensor del Pueblo</option>
              <option value="vicedefensor-pueblo">Despacho Vicedefensor del Pueblo</option>
              <option value="asuntos-internacionales">Oficina de Asuntos Internacionales</option>
              <option value="comunicaciones-imagen-institucional">Oficina de Comunicaciones e Imagen Institucional</option>
              <option value="juridica">Oficina Jurídica</option>
              <option value="planeacion">Oficina de Planeación</option>
              <option value="control-interno-disciplinario">Oficina de Control Interno Disciplinario</option>
              <option value="control-interno">Oficina Control Interno</option>
              <option value="promocion-divulgacion-derechos-humanos">Dirección Nacional de Promoción y Divulgación de Derechos Humanos</option>
              <option value="atencion-tramite-quejas">Dirección Nacional de Atención y Trámite de Quejas</option>
              <option value="recursos-acciones-judiciales">Dirección Nacional de Recursos y Acciones Judiciales</option>
              <option value="defensoria-publica">Dirección Nacional de Defensoría Pública</option>
              <option value="asuntos-constitucionales-legales">Defensoría Delegada para los Asuntos Constitucionales y Legales</option>
              <option value="prevencion-riesgos-violanciones-derechos-humanos-dih">Defensoría Delegada para la Prevención de Riesgos de Violaciones de Derechos Humanos y DIH</option>
              <option value="politica-criminal-penitenciaria">Defensoría Delegada para la Política Criminal Penitenciaria</option>
              <option value="derechos-poblacion-movilidad-humana">Defensoría Delegada para los Derechos de la Población en Movilidad Humana</option>
              <option value="derecho-salud-seguridad-social">Defensoría Delegada para el Derecho a la Salud y la Seguridad Social</option>
              <option value="derechos-economicos-sociales-culturales">Defensoría Delegada para los Derechos Económicos/Sociales y Culturales</option>
              <option value="derechos-colectivos-ambiente">Defensoría Delegada para los Derechos Colectivos y del Ambiente</option>
              <option value="grupos-etnicos">Defensoría Delegada para los Grupos Étnicos</option>
              <option value="orientacion-asesoria-victimas-conflicto-armado-interno">Defensoría Delegada para la Orientación y Asesoría de las Víctimas del Conflicto Armado Interno</option>
              <option value="asuntos-agrarios-tierras">Defensoría Delegada para los Asuntos Agrarios y Tierras</option>
              <option value="derechos-mujeres-asuntos-genero">Defensoría Delegada para los Derechos de las Mujeres y Asuntos de Género</option>
              <option value="infacia-juventud-vejez">Delegada para la Infancia, la Juventud y la Vejez</option>
              <option value="prevencion-transformacion-conflictividad-social">Delegada para la Prevención y Transformación de la Conflictividad Social</option>
              <option value="proteccion-derechos-ambientes-digitales-libertad-expresion">Delegada para la Protección de Derechos de Ambientes Digitales y Libertad de Expresión</option>
              <option value="proteccion-derecho-deporte">Delegada para la Protección del Derecho al Deporte</option>
              <option value="secretaria-general">Secretaría General</option>
              <option value="subdireccion-gestion-talento-humano">Subdirección de Gestión del Talento Humano</option>
              <option value="subdireccion-servicios-administrativos">Subdirección Servicios Administrativos</option>
              <option value="subdireccion-financiera">Subdirección Financiera</option>
              <option value="transparencia-servicio-ciudadano">Grupo de Transparencia y Servicio al Ciudadano</option>
          </select>
      </div>
      <div class="form-example">
          <label for="fecha-limite-respuesta" class="large-label">Fecha límite de respuesta: </label>
          <input type="date" name="fecha-limite-respuesta" id="dependecia-responsable"/>
      </div>
      <div class="form-example">
          <label for="fecha-limite-cumplimiento" class="large-label">Fecha límite de cumplimiento: </label>
          <input type="date" name="fecha-limite-cumplimiento" id="fecha-limite-cumplimiento"/>
      </div>
      <div class="form-example">
          <label for="fecha-ultimo-cumplimiento" class="large-label">Fecha última de cumplimiento: </label>
          <input type="date" name="fecha-ultimo-cumplimiento" id="fecha-ultimo-cumplimiento"/>
      </div>
      <div class="form-example">
          <label for="fecha-ultimo-cumplimiento" class="large-label">Fecha última de cumplimiento: </label>
          <input type="date" name="fecha-ultimo-cumplimiento" id="fecha-ultimo-cumplimiento"/>
      </div>
      <div class="form-example">
          <label for="numero-seguimientos" class="large-label">Número de seguimiento: </label>
          <input type="text" name="numero-seguimientos" id="numero-seguimientos"/>
      </div>
      <div class="form-example">
          <label for="acciones-adelantadas" class="large-label">Acciones adelantadas: </label>
          <input type="text" name="acciones-adelantadas" id="acciones-adelantados"/>
      </div>
      <div class="form-example">
          <label for="acciones-pendientes" class="large-label">Acciones pendientes: </label>
          <input type="text" name="acciones-pendientes" id="acciones-pendientes"/>
      </div>
      <div class="form-example">
          <label for="cumplio" class="large-label">¿Se cumplió?: </label>
          <select name="cumplio" id="cumplio">
	    <option value=""></option>
              <option value="si">Sí</option>
              <option value="no">No</option>
              <option value="parcialmente">Parcialmente</option>
          </select>
      </div>
      <div class="form-example">
          <label for="fuentes-verificacion" class="large-label">Fuentes de verificación: </label>
          <input type="text" name="fuentes-verificacion" id="fuentes-verificacion"/>
      </div>
      <div class="form-example">
          <label for="nivel-cumplimiento" class="large-label">Nivel de cumplimiento: </label>
          <input type="text" name="nivel-cumplimiento" id="nivel-cumplimiento"/>
      </div>
      <div>
      </div>
      <div class="full-width">
          <button type="submit" on:click|once={handleClick}>Enviar</button>
      </div>
  </form>
  
  <style>
    legend, 
    fieldset, 
    select, 
    textarea, 
    input, 
    button {
      -webkit-appearance: none;
      -moz-appearance: none;
      appearance: none;
      background-color: transparent;
      border: none;
      padding: 0;
      margin: 0;
      box-sizing: border-box;
    }
  
    input,
    select,
    textarea {
      border: 2px solid #333;
      background-color: white;
      border-radius: 0.25rem;
    }
  
    input[type="text"],
    input[type="email"],
    select,
    textarea {
      font: 1.25rem / 1.5 sans-serif;
      display: block;
      box-sizing: border-box;
      width: 100%;
      padding: 0.5rem 0.75rem;
    }
  
    textarea {
      min-height: 10rem;
    }
  
    select {
      background: url("$lib/images/down-arrow.svg") no-repeat center right 0.75rem;
    }

    .large-label {
        display: inline-block;
        font: bold 1.5rem sans-serif;
        margin-bottom: 0.5rem;
    }
 
      form {
        font: 100% / normal sans-serif;
        box-sizing: border-box;
        padding: 2rem;
        border-radius: 1rem;
        background-color: hsl(0, 0%, 100%);
        border: 4px solid hsl(0, 0%, 90%);
        display: grid;
        grid-template-columns: 1fr 1fr;
        gap: 2rem;
      }

      .full-width {
	grid-column: span 2;
      }      
      button {
	font: 1.25rem sans-serif;
	border-radius: 0.25rem;
	cursor: pointer;
	padding: 0.75rem 1.25rem;
      }      
      button[type="submit"] {
	background-color: hsl(213, 73%, 50%);
	color: white;
      }
  </style>
  
