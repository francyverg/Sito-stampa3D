<!DOCTYPE html>
<html>
<head>
  <title>3D printing</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="style.css">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js"></script>
  <!-- AOS library -->
  <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
</head>
<body>
<nav class="navbar navbar-expand-sm bg-dark navbar-dark fixed-top">
  <div class="container-fluid justify-content-center" style="font-size:1.3rem;">
    <ul class="navbar-nav">
      <li class="nav-item">
        <a class="nav-link active" href="#0">Home</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#1">Story</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#2">Techonoligies</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#3">FDM process</a>
      </li>
    </ul>
  </div>
</nav>

<!-- Carousel -->
<a name="0"></a>
<div id="demo" class="carousel slide" data-bs-ride="carousel">

  <!-- Indicators -->
  <div class="carousel-indicators">
    <button type="button" data-bs-target="#demo" data-bs-slide-to="0" class="active"></button>
    <button type="button" data-bs-target="#demo" data-bs-slide-to="1"></button>
    <button type="button" data-bs-target="#demo" data-bs-slide-to="2"></button>
    <button type="button" data-bs-target="#demo" data-bs-slide-to="3"></button>
  </div>
  
  <!-- Slides -->
  <div class="carousel-inner" style="height: 63rem">
    <div class="carousel-item active">
      <img src="img/wallpaper.jpg" alt="3D printer" class="d-block img-fluid" style="width:100%; height:63rem">
      <div class="carousel-caption">
        <h1 class=text-uppercase style="font-size: 5rem; color:black">3D printing</h1>
        <h3 style="color:black">A new way to create the world</h3>
      </div>
    </div>
    <div class="carousel-item">
      <img src="img/sla-wallpaper.jpg" alt="SLA printer" class="d-block img-fluid" style="width:100%; height:63rem">
      <div class="carousel-caption">
        <h1 class=text-uppercase style="font-size: 5rem">New technologies</h1>
        <h3>For any shape, for any material</h3>
      </div>
    </div>
    <div class="carousel-item">
      <img src="img/3d-house-wallaper.jpg" alt="3d printed house" class="d-block img-fluid" style="width:100%; height:63rem">
      <div class="carousel-caption">
        <h1 class=text-uppercase style="font-size: 5rem">Buildings</h1>
        <h3>The new horizon of architecture</h3>
      </div>
    </div>
    <div class="carousel-item">
      <img src="img/3d-heart.jpg" alt="3d printed heart" class="d-block img-fluid" style="width:100%; height:63rem">
      <div class="carousel-caption">
        <h1 class=text-uppercase style="font-size: 5rem">Surgery</h1>
        <h3>Recreating the human body</h3>
      </div>
    </div>
  </div>
  
  <!-- Left and right controls -->
  <button class="carousel-control-prev" type="button" data-bs-target="#demo" data-bs-slide="prev">
    <span class="carousel-control-prev-icon"></span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#demo" data-bs-slide="next">
    <span class="carousel-control-next-icon"></span>
  </button>
  </div>

  <div class="container-fluid">

<!-- Timeline -->
<a name="1"></a>
  <div style="padding-top: 3rem; padding-bottom: 3rem; padding-left: 28rem; padding-right: 28rem;">
    <div data-aos="fade-up" data-aos-anchor-placement="center-bottom">
      <h1 class="h1prova">Uno sguardo alla storia</h1>
    </div>
  </div>
  <div class="timeline time-body">
    <div class="time-container left">
      <div class="time-content">
        <h2>1982</h2>
        <p>Nasce ufficialmente nel 1982, quando il signor Chuck Hull inventò la stereolitografia e il formato STL (approfonditi in seguito). Nel 1986 fondandò la 3DSystems, dando vita al primo esempio commerciale di rapid prototyping.</p>
      </div>
    </div>
    <div class="time-container right">
      <div class="time-content">
        <h2>1986</h2>
        <p>Nel 1986 Deckard, Beaman e Forderhase svilupparono la selective laser sintering, un processo simile al precedente, ma utilizzarono il nylon (polvere) al posto della resina (liquido). Il nyolon essendo solido non necessita supporti, con molti vantaggi pratici.</p>
      </div>
    </div>
    <div class="time-container left">
      <div class="time-content">
        <h2>1988</h2>
        <p>Nel 1988 Crump brevettò la Fused Deposition Modeling, utilizzando plastica fusa da “spalmare” strato per strato, secondo la logica del principio additivo.</p>
      </div>
    </div>
    <div class="time-container right">
      <div class="time-content">
        <h2>1993</h2>
        <p>Nel 1993 il MIT sviluppò la prima tecnologia di stampa a colori, mentre nel 1995 i tedeschi del Fraunhofer Institute, con l'uso del laser, iniziarono a fondere polveri di metalli, producendo oggetti di qualità comparabile all’industria tradizionale.</p>
      </div>
    </div>
    <div class="time-container left">
      <div class="time-content">
        <h2>2005</h2>
        <p>Nel 2005 avvenne un cambio di paradigma: col principio del Self replicating rapid Prototyper, si riuscì a stampare una stampante 3D. Apparentemente banale, questo avvenimento equivale a dare in mano a migliaia di giovani progettisti e sognatori le chiavi per sviluppare la propria passione.</p>
      </div>
    </div>
    <div class="time-container right">
      <div class="time-content">
        <h2>2008</h2>
        <p>Nel 2008 la MakerBot Industries produsse la prima stampante acquistabile in scatola (kit) di montaggio. Nel 2010 la NASA afferma di voler costruire case su Marte utilizzando il contour crafting, una stampa 3D che utilizza il cemento come materiale.</p>
      </div>
    </div>
  </div>

<!-- Cards --> 
<a name="2"></a>  
  <div style="padding-top: 3rem; padding-bottom: 3rem; padding-left: 28rem; padding-right: 28rem;">
    <div data-aos="fade-up" data-aos-anchor-placement="center-bottom">
      <h1 class="h1prova">Le tecnologie</h1>
    </div>
  </div>
  <div class="justify-content-center row">
  <div class="card" style="width:22rem;">
    <img src="img/SLA-3D-Printing.jpg" class="card-img-top" alt="SLA 3d printer">
    <div class="card-body">
      <h5 class="card-title">SLA</h5>
      <p class="card-text">Per creare gli oggetti più particolareggiati.</p>
      <button id="myBtn" class="btn btn-primary">Scopri di più</button>
				<!-- Modal -->
				<div id="myModal" class="modal">
				  <!-- Modal content -->
				  <div class="modal-content">
				    <span class="close">&times;</span>
						<h1>Stereolitografia</h1>
				    <p>Scrivere qualcosa di decente + immagini carine</p>
				  </div>
				</div>
				<script src="script.js"></script>
    </div>
  </div>
  <div class="card" style="width:22rem;">
    <img src="img/dlp-3D-printer.jpg" class="card-img-top" alt="SLA 3d printer">
    <div class="card-body">
      <h5 class="card-title">DLP</h5>
      <p class="card-text">Per creare gli oggetti più particolareggiati.</p>
      <button id="myBtn" class="btn btn-primary">Scopri di più</button>
				<!-- Modal -->
				<div id="myModal" class="modal">
				  <!-- Modal content -->
				  <div class="modal-content">
				    <span class="close">&times;</span>
						<h1>Digital Light Processing</h1>
				    <p>Scrivere qualcosa di decente + immagini carine</p>
				  </div>
				</div>
				<script src="script.js"></script>
    </div>
  </div>
  <div class="card" style="width:22rem;">
    <img src="img/fdm-3d-printing.jpg" class="card-img-top" alt="SLA 3d printer">
    <div class="card-body">
      <h5 class="card-title">FDM</h5>
      <p class="card-text">Per creare gli oggetti più particolareggiati.</p>
      <button id="myBtn" class="btn btn-primary">Scopri di più</button>
				<!-- Modal -->
				<div id="myModal" class="modal">
				  <!-- Modal content -->
				  <div class="modal-content">
				    <span class="close">&times;</span>
						<h1>Fused deposition modeling</h1>
				    <p>Scrivere qualcosa di decente + immagini carine</p>
				  </div>
				</div>
				<script src="script.js"></script>
    </div>
  </div>
  </div>

  <div class="justify-content-center row" style="padding-top:3rem;">
    <div class="card" style="width:22rem;">
      <img src="img/SLS-prints-from-Sinterit.jpg" class="card-img-top" alt="SLS 3d printer">
      <div class="card-body">
        <h5 class="card-title">SLS</h5>
        <p class="card-text">Per creare gli oggetti più particolareggiati.</p>
        <button id="myBtn" class="btn btn-primary">Scopri di più</button>
				<!-- Modal -->
				<div id="myModal" class="modal">
				  <!-- Modal content -->
				  <div class="modal-content">
				    <span class="close">&times;</span>
						<h1>Selective Laser Sintering</h1>
				    <p>Scrivere qualcosa di decente + immagini carine</p>
				  </div>
				</div>
				<script src="script.js"></script>
      </div>
    </div>
    <div class="card" style="width:22rem;">
      <img src="img/3Dprinter_cjp.jpg" class="card-img-top" alt="cjp 3d printer">
      <div class="card-body">
        <h5 class="card-title">CJP</h5>
        <p class="card-text">Per creare gli oggetti più particolareggiati.</p>
        <button id="myBtn" class="btn btn-primary">Scopri di più</button>
				<!-- Modal -->
				<div id="myModal" class="modal">
				  <!-- Modal content -->
				  <div class="modal-content">
				    <span class="close">&times;</span>
						<h1>ColorJet Printing</h1>
				    <p>Scrivere qualcosa di decente + immagini carine</p>
				  </div>
				</div>
				<script src="script.js"></script>
      </div>
    </div>
    <div class="card" style="width:22rem;">
      <img src="img/5d-printing.jpg" class="card-img-top" alt="5D printer">
      <div class="card-body">
        <h5 class="card-title">Stampa 5D</h5>
        <p class="card-text">Per creare gli oggetti più particolareggiati.</p>
        <!-- Open Modal -->
				<button id="myBtn" class="btn btn-primary">Scopri di più</button>
				<!-- Modal -->
				<div id="myModal" class="modal">
				  <!-- Modal content -->
				  <div class="modal-content">
				    <span class="close">&times;</span>
						<h1>Stampa 5D</h1>
				    <p>Il principio di funzionamento è lo stesso della tecnologia FDM, ma con un'importante differenza. La testina di stampa si muove da 5 diverse angolazioni durante la stampa, poiché anche il piano su cui viene stampato l’oggetto si muove. Questi movimenti consentono alla testa della stampante di entrare da diversi angoli, altrimenti non raggiunti con la stampa 3D. I nuovi angoli consentono alla testina di stampa di seguire il percorso della forma e del contorno dell’oggetto.
Non dovendo seguire un percorso rettilineo su un piatto statico, e utilizzando invece la forma dell’oggetto, le parti stampate possono essere create con strati curvi anziché piani. Questi strati curvi consentono parti più resistenti anche con design maggiormente complessi da stampare.
Con la stampa 5D, i livelli curvi impediscono la creazione di punti deboli.
</p>
				  </div>
				</div>
				<script src="script.js"></script>
      </div>
    </div>
  </div>

<!-- Library initialization NON SPOSTARLO DAL FONDO DEL FILE --> 
</div>  
<script src="https://unpkg.com/aos@next/dist/aos.js"></script>
<script>
  AOS.init();
</script>
</body>
</html>