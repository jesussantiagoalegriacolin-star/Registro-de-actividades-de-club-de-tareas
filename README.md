# Registro-de-actividades-de-club-de-tareas
<html lang="es">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Servicios Sociales Registro</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.7/dist/css/bootstrap.min.css" rel="stylesheet">
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.7/dist/js/bootstrap.bundle.min.js"></script>
    body {
      padding: 20px;
    }

    h1 {
      color: #0d6efd;
    }

    .blue-row {
      background-color: #cce5ff;
    }

    .pink-row {
      background-color: #f8d7da;
    }

    .red-row {
      background-color: #f5c6cb;
    }

    .imagen {
      max-width: 100%;
      height: auto;
      border: 2px solid #333;
      border-radius: 10px;
      margin-top: 20px;
    }

    input[type="file"] {
      margin-top: 20px;
      padding: 10px;
      background-color: #4CAF50;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }

    input[type="file"]:hover {
      background-color: #45a049;
    }

    textarea {
      width: 95%;
      height: 120px;
      resize: vertical;
    }

    .timer {
      font-size: 14px;
      font-weight: bold;
      color: #d63384;
    }
  </style>
</head>
<body>

  <h1>¡Bienvenidas/dos al registro de club de tareas!</h1>

  <form class="form registro" action="https://formspree.io/f/mwpnppbz" method="POST" enctype="multipart/form-data">

    <div class="mb-3">
      <label for="email" class="form-label">Añade una cuenta Gmail y/o Email</label>
      <input type="email" class="form-control" id="email" name="email" placeholder="name@example.com">
    </div>

    <div class="mb-3">
      <label for="nombreCompleto" class="form-label">Nombre completo</label>
      <input type="text" class="form-control" id="nombreCompleto" name="nombreCompleto" placeholder="Escribe tu nombre completo">
    </div>

    <div class="mb-3">
      <label for="nombreBiblioteca" class="form-label">Nombre de la biblioteca</label>
      <select class="form-select" id="nombreBiblioteca" name="nombreBiblioteca">
        <option value="" selected>Selecciona una biblioteca</option>
        <option value="José Luis Álamo Jardón">José Luis Álamo Jardón</option>
        <option value="Rafael Moreno Montes de Oca">Rafael Moreno Montes de Oca</option>
        <option value="Guillermina Nateras López">Guillermina Nateras López</option>
        <option value="San Pedro Totoltepec">San Pedro Totoltepec</option>
        <option value="Dr. Urban Boutelegier">Dr. Urban Boutelegier</option>
        <option value="Michel D’Hooghe">Michel D’Hooghe</option>
        <option value="Santa Teresita del Niño Jesús">Santa Teresita del Niño Jesús</option>
        <option value="Biblioteca Santiago Tlacotepec">Biblioteca Santiago Tlacotepec</option>
        <option value="Biblioteca Santiago Tlaxomulco">Biblioteca Santiago Tlaxomulco</option>
        <option value="Biblioteca Tecaxic">Biblioteca Tecaxic</option>
        <option value="Ludoteca San Cristóbal Huichochitlán">Ludoteca San Cristóbal Huichochitlán</option>
        <option value="Museo Municipal de Calixtlahuaca">Museo Municipal de Calixtlahuaca</option>
        <option value="Museo del Alfeñique">Museo del Alfeñique</option>
        <option value="Lic. Jaime Almazán Delgado">Lic. Jaime Almazán Delgado</option>
        <option value="José María Heredia y Heredia">José María Heredia y Heredia</option>
        <option value="Leonardo Sánchez Montaño">Leonardo Sánchez Montaño</option>
        <option value="Otomitl">Otomitl</option>
        <option value="Concepción García Valdez">Concepción García Valdez</option>
        <option value="Sor Juana Inés de la Cruz">Sor Juana Inés de la Cruz</option>
        <option value="Mercedes López Gómeztagle">Mercedes López Gómeztagle</option>
        <option value="Edelmira Nava Arellano">Edelmira Nava Arellano</option>
        <option value="Profa. Laura Beatriz Benavides">Profa. Laura Beatriz Benavides</option>
        <option value="Agustín María Lebrija">Agustín María Lebrija</option>
        <option value="Rodolfo García Gutiérrez">Rodolfo García Gutiérrez</option>
        <option value="Laura Méndez de Cuenca">Laura Méndez de Cuenca</option>
        <option value="Mercedes Carrasco">Mercedes Carrasco</option>
        <option value="Fray Andrés de Castro">Fray Andrés de Castro</option>
      </select>
    </div>

    
    <div class="mb-3">
      <label for="coberturaAtencion" class="form-label">Cobertura de atención / Delegación</label>
      <select class="form-select" id="coberturaAtencion" name="coberturaAtencion">
        <option value="" selected>Selecciona la delegación o cobertura</option>
        <option value="San Lorenzo Tepaltitlán">San Lorenzo Tepaltitlán</option>
        <option value="Santa Cruz Atzcapotzaltongo">Santa Cruz Atzcapotzaltongo</option>
        <option value="San Mateo Oxtotitlán, Nueva Oxtotitlán">San Mateo Oxtotitlán, Nueva Oxtotitlán</option>
        <option value="San Pedro Totoltepec">San Pedro Totoltepec</option>
        <option value="San Diego de los Padres Cuexcontitlán">San Diego de los Padres Cuexcontitlán</option>
        <option value="San Cayetano Morelos">San Cayetano Morelos</option>
        <option value="Morelos, Sánchez">Morelos, Sánchez</option>
        <option value="Santiago Tlacotepec, San Juan Tilapa">Santiago Tlacotepec, San Juan Tilapa</option>
        <option value="Santiago Tlaxomulco">Santiago Tlaxomulco</option>
        <option value="Tecaxic">Tecaxic</option>
        <option value="San Cristóbal Huichochitlán">San Cristóbal Huichochitlán</option>
        <option value="Toluca, Estado de México, México y extranjero">Toluca, Estado de México, México y extranjero</option>
        <option value="La Maquinita, Santiago Miltepec">La Maquinita, Santiago Miltepec</option>
        <option value="Cacalomacán">Cacalomacán</option>
        <option value="San Mateo Otzacatipan">San Mateo Otzacatipan</option>
        <option value="Tlachaloya">Tlachaloya</option>
        <option value="San Martín Toltepec">San Martín Toltepec</option>
        <option value="Independencia">Independencia</option>
        <option value="Capultitlán, Moderna de la Cruz">Capultitlán, Moderna de la Cruz</option>
        <option value="San Andrés Cuexcontitlán">San Andrés Cuexcontitlán</option>
        <option value="San Antonio Buenavista, San Buenaventura">San Antonio Buenavista, San Buenaventura</option>
        <option value="San Pablo Autopan">San Pablo Autopan</option>
        <option value="Seminario Conciliar, Seminario 2 de marzo, Seminario las Torres, Felipe Chávez Becerril">Seminario Conciliar, Seminario 2 de marzo, Seminario las Torres, Felipe Chávez Becerril</option>
        <option value="Calixtlahuaca, San Marcos Yachihuacaltepec">Calixtlahuaca, San Marcos Yachihuacaltepec</option>
      </select>
    </div>
    
<h2 style="text-align:center;">Plan de Septiembre - Octubre 2025</h2>
  <table class="table table-bordered">
   <!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contador de Tiempo</title>
</head>
<body>
<table border="1">
  <thead>
    <tr>
      <th>Semana</th>
      <th>Tarea</th>
      <th>Fecha de Entrega</th>
      <th>No. de Asistentes</th>
      <th>Nota Informativa</th>
      
      <th>Archivos</th>
    </tr>
  </thead>
  <tbody>

<form action="https://formspree.io/f/xgvlgvvd" method="POST" enctype="multipart/form-data">
  <tr>
    <td>Semana 4</td>
    <td>Haz pausas intencionadas</td>
    <td>Miércoles 24 Septiembre 2025</td>
    <td>
      <input type="checkbox" name="asistencia"> Asistió
    </td>
    <td>
      <textarea name="nota" placeholder="Escribe la nota informativa..."></textarea>
    </td>
    <td>
      <span class="timer" data-fecha="2025-09-24T23:59:59"></span>
    </td>
    <td>
      <input type="file" name="evidencia" required>
    </td>
    <td>
      <input type="file" name="actividad" value="Haz pausas intencionadas">
      <button type="submit" class="btn btn-primary">Entregar</button>
      <input type="hidden" name="hashid" value="">

    </td>
  </tr>
</form>
  <tr>
    <td>Semana 4</td>
    <td>Varia el tono y ritmo</td>
    <td>Miércoles 25 Septiembre 2025</td>
    <td>
      <input type="checkbox" name="asistencia"> Asistió
    </td>
    <td>
      <textarea name="nota" placeholder="Escribe la nota informativa..."></textarea>
    </td>
    <td>
      <span class="timer" data-fecha="2025-09-25T23:59:59"></span>
    </td>
    <td>
      <input type="file" name="evidencia" required>
    </td>
    <td>
      <input type="hidden" name="actividad" value="Haz pausas intencionadas">
      <button type="submit" class="btn btn-primary">Entregar</button>
    </td>
  </tr>
</form>
  <tr>
    <td>Semana 5</td>
    <td>Utiiza notas clave</td>
    <td>Miércoles 1 Octubre 2025</td>
    <td>
      <input type="checkbox" name="asistencia"> Asistió
    </td>
    <td>
      <textarea name="nota" placeholder="Escribe la nota informativa..."></textarea>
    </td>
    <td>
      <span class="timer" data-fecha="2025-10-01T23:59:59"></span>
    </td>
    <td>
      <input type="file" name="evidencia" required>
    </td>
    <td>
      <input type="hidden" name="actividad" value="Haz pausas intencionadas">
      <button type="submit" class="btn btn-primary">Entregar</button>
    </td>
  </tr>
</form>
  <tr>
    <td>Semana 5</td>
    <td>Establece contacto visual</td>
    <td>Miércoles 2 Octubre 2025</td>
    <td>
      <input type="checkbox" name="asistencia"> Asistió
    </td>
    <td>
      <textarea name="nota" placeholder="Escribe la nota informativa..."></textarea>
    </td>
    <td>
      <span class="timer" data-fecha="2025-10-02T23:59:59"></span>
    </td>
    <td>
      <input type="file" name="evidencia" required>
    </td>
    <td>
      <input type="hidden" name="actividad" value="Haz pausas intencionadas">
      <button type="submit" class="btn btn-primary">Entregar</button>
    </td>
  </tr>
</form>
  <tr>
    <td>Semana 6</td>
    <td>Sonrie</td>
    <td>Miércoles 8 Octubre 2025</td>
    <td>
      <input type="checkbox" name="asistencia"> Asistió
    </td>
    <td>
      <textarea name="nota" placeholder="Escribe la nota informativa..."></textarea>
    </td>
    <td>
      <span class="timer" data-fecha="2025-10-08T23:59:59"></span>
    </td>
    <td>
      <input type="file" name="evidencia" required>
    </td>
    <td>
      <input type="hidden" name="actividad" value="Haz pausas intencionadas">
      <button type="submit" class="btn btn-primary">Entregar</button>
      <input type="hidden" name="hashid" value="">
    </td>
  </tr>
</form>
  <tr>
    <td>Semana 6</td>
    <td>Se honesto contigo mismo</td>
    <td>Miércoles 9 Octubre 2025</td>
    <td>
      <input type="checkbox" name="asistencia"> Asistió
    </td>
    <td>
      <textarea name="nota" placeholder="Escribe la nota informativa..."></textarea>
    </td>
    <td>
      <span class="timer" data-fecha="2025-10-09T23:59:59"></span>
    </td>
    <td>
      <input type="file" name="evidencia" required>
    </td>
    <td>
      <input type="hidden" name="actividad" value="Haz pausas intencionadas">
      <button type="submit" class="btn btn-primary">Entregar</button>
      <input type="hidden" name="hashid" value="">
    </td>
  </tr>
</form>
  <tr>
    <td>Semana 7</td>
    <td>Capacitacion</td>
    <td>Miércoles 15 Octubre 2025</td>
    <td>
      <input type="checkbox" name="asistencia"> Asistió
    </td>
    <td>
      <textarea name="nota" placeholder="Escribe la nota informativa..."></textarea>
    </td>
    <td>
      <span class="timer" data-fecha="2025-10-15T23:59:59"></span>
    </td>
    <td>
      <input type="file" name="evidencia" required>
    </td>
    <td>
      <input type="hidden" name="actividad" value="Haz pausas intencionadas">
      <button type="submit" class="btn btn-primary">Entregar</button>
      <input type="hidden" name="hashid" value="">
    </td>
  </tr>
</form>
  <tr>
    <td>Semana 7</td>
    <td>Inicia la siguiente etapa</td>
    <td>Miércoles 16 Octubre 2025</td>
    <td>
      <input type="checkbox" name="asistencia"> Asistió
    </td>
    <td>
      <textarea name="nota" placeholder="Escribe la nota informativa..."></textarea>
    </td>
    <td>
      <span class="timer" data-fecha="2025-10-16T23:59:59"></span>
    </td>
    <td>
      <input type="file" name="evidencia" required>
    </td>
    <td>
      <input type="hidden" name="actividad" value="Haz pausas intencionadas">
      <button type="submit" class="btn btn-primary">Entregar</button>
      <input type="hidden" name="hashid" value="">
    </td>
  </tr>
</form>
  </tbody>
</table>

 <form class="form-register"
     action="https://formspree.io/f/xgvlgvvd"
    method="POST
   >
</body>
</html>
