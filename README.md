[junior2.html](https://github.com/user-attachments/files/31438279/junior2.html)
<head>
    <title>todo sobre las virtual box's</title>
  <style>
    :root {
      --bg-principal: #f5f5f5;
      --bg-card: #ffffff;
      --color-primario: #0077cc;
      --color-primario-oscuro: #005fa3;
      --color-texto: #333333;
      --color-borde: #e0e0e0;
      --fuente-titulo: 'Poppins', sans-serif;
      --fuente-cuerpo: 'Roboto', sans-serif;
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      background-color: var(--bg-principal);
      color: var(--color-texto);
      font-family: var(--fuente-cuerpo);
      font-size: 1rem;
      line-height: 1.6;
    }

    h1, h2, h3 {
      font-family: var(--fuente-titulo);
      color: var(--color-primario);
      margin-bottom: 0.75rem;
    }

    p {
      margin-bottom: 1rem;
    }

    a {
      color: var(--color-primario);
      text-decoration: none;
    }

    img {
      max-width: 100%;
      height: auto;
      display: block;
      border-radius: 6px;
    }

    figcaption {
      font-size: 0.875rem;
      color: #666666;
      text-align: center;
      margin-top: 0.5rem;
      font-style: italic;
    }

        .container {
      max-width: 1100px;
      margin: 0 auto;
      padding: 0 1.5rem;
    }

        header {
      background-color: var(--bg-card);
      border-bottom: 3px solid var(--color-primario);
      padding: 1.5rem 0;
      box-shadow: 0 2px 5px rgba(0,0,0,0.05);
    }

    .header-content {
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
      gap: 1rem;
    }

    .brand {
      display: flex;
      align-items: center;
      gap: 1rem;
    }

    .brand img {
      width: 50px;
      height: 50px;
      object-fit: contain;
    }

    .header-title h1 {
      font-size: 1.75rem;
      margin-bottom: 0;
    }

    .student-name {
      font-weight: 500;
      color: #555555;
    }

     main {
      padding: 2rem 0;
    }

    section {
      background-color: var(--bg-card);
      border-radius: 8px;
      padding: 2rem;
      margin-bottom: 2rem;
      box-shadow: 0 2px 8px rgba(0,0,0,0.04);
      border: 1px solid var(--color-borde);
    }

       .hero-image {
      width: 100%;
      max-height: 450px;
      object-fit: cover;
    }

       .grid-2col {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 1.5rem;
      margin-top: 1rem;
    }

    ul, ol {
      margin-left: 1.5rem;
      margin-bottom: 1rem;
    }

    li {
      margin-bottom: 0.5rem;
    }

       .table-responsive {
      overflow-x: auto;
      margin: 1.5rem 0;
    }

    table {
      width: 100%;
      border-collapse: collapse;
      text-align: left;
    }

    th, td {
      padding: 0.75rem 1rem;
      border: 1px solid var(--color-borde);
    }

    th {
      background-color: var(--color-primario);
      color: #ffffff;
      font-family: var(--fuente-titulo);
      font-weight: 600;
    }

    tr:nth-child(even) {
      background-color: #f9f9f9;
    }

     footer {
      background-color: var(--bg-card);
      border-top: 1px solid var(--color-borde);
      padding: 1.5rem 0;
      text-align: center;
      font-size: 0.9rem;
      color: #666666;
    }

   
    @media (max-width: 768px) {
      .grid-2col {
        grid-template-columns: 1fr;
      }

      .header-content {
        flex-direction: column;
        align-items: flex-start;
      }
    }
 

<body>

  
  <header>
              
        <div class="header-title">
          <h1>todo lo relacionado con la virtual box</h1>
        </div>
      </div>
      <div class="student-name">
        <span>Estudiante: <strong>Junior Jose Mejia Ramos</strong></span>
      </div>
    </div>
  </header>

  <main class="container">

       <section id="presentacion">
      <h2>Presentación</h2>
      <figure>
            <figcaption>en esta pagina veas todo lo relacionado con virtual box</figcaption>
      </figure>
    </section>

      <section id="introduccion">
      <h2>Introducción</h2>
           <p>
       es una plataforma de software de virtualización multiplataforma de código abierto clasificada como un hipervisor de Tipo 2 (o alojado). Permite crear y ejecutar simultáneamente múltiples máquinas virtuales (VM) con diferentes sistemas operativos invitados (Guest OS) sobre un único sistema operativo anfitrión (Host OS), sin necesidad de particionar el disco ni alterar el equipo físico      </p>

      <p>
        Permite abstraer el hardware para optimizar el uso de recursos, reducir costes operativos y crear entornos seguros totalmente aislados (sandboxes). Gracias a esto, desarrolladores y administradores de sistemas pueden probar software, analizar malware o ejecutar plataformas incompatibles sin poner en riesgo la estabilidad ni los datos de la máquina principal      </p>
    </section>

        <section id="desarrollo">
      <h2>Desarrollo del Tema</h2>
      
      
      <h3>Conceptos Clave</h3>
      <ul>
        <li><strong>Host OS (Sistema Anfitrión): El sistema operativo físico sobre el que corre VirtualBox (ej. Windows 11, macOS, Linux).</li>
        <li><strong> Guest OS (Sistema Invitado): El sistema operativo virtualizado que se ejecuta dentro de la máquina virtual (ej. Ubuntu corriendo dentro de Windows).
</strong> Hypervisor Tipo 2: Software intermediario que gestiona y distribuye recursos de CPU, RAM y almacenamiento entre el Host y las distintas VMs.</li>
           </ul>

      <h3>Ventajas y Desventajas</h3>
      <div class="table-responsive">
        <table>
          <thead>
            <tr>
              <th>Ventajas</th>
              <th>Desventajas</th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td>Gratuito y accesible.</td>
              <td>Rendimiento condicionado</td>
            </tr>
            <tr>
              <td>Multiplataforma.</td>
              <td>Alto consumo de recursos.</td>
            </tr>
            <tr>
              <td>Alto consumo de recursos.</td>
              <td>Requisito de BIOS/UEFI.</td>
            </tr>
          </tbody>
        </table>
      </div>

      <h3>Componentes y Herramientas</h3>
      <p>
        las principales componentes utilizadas son: la vbox manage,los formatos de disco (vdi,vmdk,vhd) y por ultimo las redes virtuales
             <figcaption>


       <section id="ejemplos">
      <h2>Ejemplos y Casos Prácticos</h2>
      
      <p>
        Ubuntu (Linux)
      </p>

      <div class="grid-2col">
        <div>
          <h3>Caso Real o Implementación</h3>
          <p>
           Laboratorios de Ciberseguridad: Los analistas ejecutan troyanos o ransomware en una VM aislada para estudiar su comportamiento sin infectar la red corporativa.          </p>
        </div>
        <div>
          <h3>Comparativa / Análisis</h3>
          <p>
            Criterio	
Hipervisor Tipo 1 (Bare-Metal)


(Ej. VMware ESXi, Proxmox)

Hipervisor Tipo 2 (Alojado)


(Ej. VirtualBox, VMware Workstation)

Instalación	Directamente sobre el hardware físico.	Sobre un sistema operativo anfitrión.
Rendimiento	Máxima velocidad y latencia mínima.	Sujeto a los recursos que libere el Host OS.
Uso Principal	Centros de datos y servidores de producción.	Entornos de pruebas, desarrollo local y educación.          </p>
        </div>
      </div>

    
       <section id="conclusiones">
      <h2>Conclusiones</h2>
      
      <h3>Ideas Clave</h3>
      <ol>
        <li>Aislamiento seguro: Permite probar software y sistemas operativos sin riesgo de infectar o dañar tu computadora física.</li>
        <li>Ahorro de recursos: Ejecuta múltiples entornos de trabajo e infraestructura simulada en un solo equipo físico.</li>
        <li>Puntos de restauración (Snapshots): Guarda el estado exacto del sistema para revertir errores o fallos en segundos.</li>
      </ol>

      <h3>Importancia en la Industria Actual</h3>
      <p>
        En conclusión, VirtualBox se consolida como el estándar global para experimentar, aprender y simular infraestructuras informáticas complejas de forma rápida, segura y accesible desde cualquier equipo personal.
      </p>
    </section>


   <footer>
    <div class="container">
      <p>Derechos reservados &copy; <span id="year">2026</span> | <strong>junior mejia</strong></p>
    </div>
  </footer>

