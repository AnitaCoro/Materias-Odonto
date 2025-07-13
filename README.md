# Materias-Odonto
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Malla Curricular</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f6f7;
      padding: 20px;
    }
    h1 {
      color: #2e86c1;
    }
    .materia {
      display: inline-block;
      background-color: #d6eaf8;
      padding: 10px 20px;
      margin: 10px;
      border-radius: 8px;
      border: 1px solid #3498db;
      cursor: pointer;
      transition: background-color 0.3s;
    }
    .materia:hover {
      background-color: #aed6f1;
    }
  </style>
</head>
<body>
  <h1>Malla Curricular Interactiva</h1>

  <h2>1º Cuatrimestre</h2>
  <div class="materia">Anatomía I</div>
  <div class="materia">Biologia General</div>
  <div class="materia">Biofisica</div>
  <div class="materia">OPS</div>

 <h2>2º Cuatrimestre</h2>
  <div class="materia">Anatomía II</div>
  <div class="materia">Biologia General II</div>
  <div class="materia">Biofisica II</div>
  <div class="materia">OPS</div>
  <div class="materia">Histologia y Embriologia I</div>
  
  <script>
    document.querySelectorAll('.materia').forEach(materia => {
      materia.addEventListener('click', () => {
        alert("Seleccionaste: " + materia.textContent);
      });
    });
  </script>
</body>
</html>
