<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bootstrap</title>
    <!-- bootstrap -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
    <!-- bootstrap icon -->
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css">
</head>
<body id="home" data-bs-spy="scroll" data-bs-target=".navbar">

    <!-- navbar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-success sticky-top rounded">
        <div class="container">
          <!-- /Button trigger modal -->
           <dvi class="nav fw-bolder order-1 p-2">
            <a class="text-decoration-none text-white" data-bs-toggle="modal" data-bs-target="#login" href="./signup.html">Login</a>
           </dvi>
           <dvi class="nav fw-bolder order-1 ml-3">
            <a class="text-decoration-none text-white" data-bs-toggle="modal" data-bs-target="#exampleModal" href="./signup.html">Sign Up</a>
           </dvi>
          <!-- Button trigger modal -->
          <a class="navbar-brand" href="#">Z-Fitness</a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav">
              <li class="nav-item">
                <a class="nav-link active fw-bolder" href="#home">Home</a>
              </li>
              <li class="nav-item">
                <a class="nav-link fw-bolder" href="#membership">Membership</a>
              </li>
              <li class="nav-item">
                <a class="nav-link fw-bolder" href="#trainer">Trainer</a>
              </li>
              <li class="nav-item">
                <a class="nav-link fw-bolder" href="#schedule">Schedule</a>
              </li>
              <li class="nav-item">
                <a class="nav-link fw-bolder" href="#content">Content</a>
              </li>
            </ul>
          </div>
        </div>
      </nav>
     <!-- /navbar -->

     <div class="d-flex justify-content-center pt-3">
      <h2 class="text-center p-3 fw-bolder" style="color: rgb(61, 61, 78);">WELLCOME TO THE</h2>
      <h2 class="text-center p-3 fw-bolder bg-success rounded-1" style="color: #ffff;">Z-FITNESS</h2>
    </div>

     <!-- caucosel -->
     <div class="container text-center">
        <div id="carouselExampleCaptions" class="carousel slide shadow-lg bg-body rounded" data-bs-ride="carousel">
            <div class="carousel-indicators">
              <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
              <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
              <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 3"></button>
              <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="3" aria-label="Slide 4"></button>
            </div>
            <div class="carousel-inner rounded">
                <div class="carousel-item active">
                    <img class=" img-fluid" style="width:100%;height:550px;" src="https://c8.alamy.com/comp/FGFAYX/group-of-people-running-on-treadmills-FGFAYX.jpg" alt="...">
                    <div class="carousel-caption d-none d-md-block">
                      <h5>Ground Floor</h5>
                      <p>Some representative placeholder content for the third slide.</p>
                    </div>
                  </div>
              <div class="carousel-item">
                <img class="img-fluid" style="width:100%;height:550px;"  src="https://www.gymleco.com/wp-content/uploads/2022/09/hur-du-bygger-framgangsrikt-gym.jpg" alt="...">
                <div class="carousel-caption d-none d-md-block">
                  <h5>First Floor</h5>
                  <p>Some representative placeholder content for the first slide.</p>
                </div>
              </div>
              <div class="carousel-item">
                <img class="img-fluid" style="width:100%;height:550px;" src="https://images.squarespace-cdn.com/content/v1/63b1d002593c6d0b174ab2d2/406c5e3a-83ac-4e81-870b-3010a0a5a5c3/CLTV+-+Jesse+Colocado-02.jpg" alt="...">
                <div class="carousel-caption d-none d-md-block">
                  <h5>Second Floor</h5>
                  <p>Some representative placeholder content for the second slide.</p>
                </div>
              </div>
              <div class="carousel-item">
                <img class=" img-fluid" style="width:100%;height:550px;" src="https://www.genesishealthclubs.com/media/images/Group%20Fitness%20Benefits2.jpg" alt="...">
                <div class="carousel-caption d-none d-md-block">
                  <h5>Third Floor</h5>
                  <p>Some representative placeholder content for the third slide.</p>
                </div>
              </div>
            </div>
            <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
              <span class="carousel-control-prev-icon" aria-hidden="true"></span>
              <span class="visually-hidden">Previous</span>
            </button>
            <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
              <span class="carousel-control-next-icon" aria-hidden="true"></span>
              <span class="visually-hidden">Next</span>
            </button>
          </div>
     </div>
      <!-- /caucosel -->

      <hr class="mb-3">

      <!-- membership -->
       <dvi class="container" id="membership">
        <h4 class="display-4 text-center my-4 fw-bold">Memberships</h4>
        <p class="text-center text-muted mr-3">We offer the PF Black Card® Membership and Classic Membership. Both get you access to The Judgement Free Zone®, and tons of cardio and strength equipment.</p>
       </dvi>
      
       <div class="card m-auto text-center shadow-lg bg-body rounded" style="width: 18rem;">
        <img src="https://marketplace.canva.com/EAFxdcos7WU/1/0/1600w/canva-dark-blue-and-brown-illustrative-fitness-gym-logo-oqe3ybeEcQQ.jpg" class="card-img-top" alt="...">
        <div class="card-body">
          <h5 class="card-title">Card title</h5>
          <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
          <a href="#" class="btn btn-outline-success shadow-lg">Join Now</a>
        </div>
      </div>
      <!-- /membership -->

      <hr mb-3>

      <!-- trainer layout -->
      <h4 class="display-4 text-center my-4 fw-bold">Trainers</h4>

      <div class="row container text-center m-auto" id="trainer">
        <div class="col-md-4">
            <div class="card mb-3 shadow-lg bg-body rounded">
                <img src="https://as1.ftcdn.net/v2/jpg/02/64/23/78/1000_F_264237813_6Yn9JJkBZkuGP9gEgebCA5xVqhqz76v3.jpg" class="card-img-top" alt="Boris">
                <div class="card-body">
                  <h5 class="card-title">Boris</h5>
                  <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
                  <p class="card-text"><small class="text-muted">Last updated 3 mins ago</small></p>
                </div>
              </div>
        </div>
        <div class="col-md-4">
            <div class="card mb-3 shadow-lg bg-body rounded">
                <img src="https://t3.ftcdn.net/jpg/06/45/17/94/360_F_645179444_EtQDcQw5Mcyv1MSH25K5FrEkb3LfH5Vk.jpg" class="card-img-top" alt="Tricia">
                <div class="card-body">
                  <h5 class="card-title">Tricia</h5>
                  <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
                  <p class="card-text"><small class="text-muted">Last updated 3 mins ago</small></p>
                </div>
              </div>
        </div>
        <div class="col-md-4">
            <div class="card mb-3 shadow-lg bg-body rounded">
                <img src="https://img.freepik.com/fotos-premium/fitness-gym-portrait-personal-trainer-com-prancheta_894067-8011.jpg" class="card-img-top" alt="Kevil">
                <div class="card-body">
                  <h5 class="card-title">Kevil</h5>
                  <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
                  <p class="card-text"><small class="text-muted">Last updated 3 mins ago</small></p>
                </div>
              </div>
        </div>
        <div class="col-md-4">
            <div class="card mb-3 shadow-lg bg-body rounded">
                <img src="https://img.freepik.com/fotos-premium/selbstbewusster-athlet-junger-und-gesunder-mann-der-mit-selbstvertrauen-posiert_893610-1380.jpg" class="card-img-top" alt="Raxx">
                <div class="card-body">
                  <h5 class="card-title">Raxx</h5>
                  <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
                  <p class="card-text"><small class="text-muted">Last updated 3 mins ago</small></p>
                </div>
              </div>
        </div>
        <div class="col-md-4">
            <div class="card mb-3 shadow-lg bg-body rounded">
                <img src="https://img.freepik.com/fotos-premium/um-homem-em-um-top-esta-em-uma-academia-com-uma-barra-na-mao_765582-923.jpg" class="card-img-top" alt="Ziam">
                <div class="card-body">
                  <h5 class="card-title">Ziam</h5>
                  <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
                  <p class="card-text"><small class="text-muted">Last updated 3 mins ago</small></p>
                </div>
              </div>
        </div>
        <div class="col-md-4">
            <div class="card mb-3 shadow-lg bg-body rounded">
                <img src="https://img.freepik.com/fotos-premium/um-homem-esta-em-uma-sala-escura-com-os-bracos-estendidos_765582-929.jpg" class="card-img-top" alt="Andrew">
                <div class="card-body">
                  <h5 class="card-title">Andrew</h5>
                  <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
                  <p class="card-text"><small class="text-muted">Last updated 3 mins ago</small></p>
                </div>
              </div>
        </div>
      </div>
       <!-- /trainer layout -->

       <hr class="mb-3">

       <!-- Schedules -->
       <h4 class="display-4 text-center my-4 fw-bold">Classes Schedules</h4>

       <table class="table container table-success table-hover table-bordered border-success" id="schedule">
        <thead class="text-center h3">
          <tr>
            <th scope="col">Monday</th>
            <th scope="col">Tuesday</th>
            <th scope="col">Wednesday</th>
            <th scope="col">Thursday</th>
            <th scope="col">Friday</th>
            <th scope="col">Saturday</th>
            <th scope="col">Sunday</th>
          </tr>
        </thead>
        <tbody class="text-center fw-bolder">
          <tr>
            <th>Streatching <hr class="m-1 p-0"> 6:40 Am 7:40 Am</th>
            <td>Combat<hr class="m-1 p-0"> 6:40 Am 7:40 Am</td>
            <td>Booty<hr class="m-1 p-0"> 6:40 Am 7:40 Am</td>
            <td>Zumba<hr class="m-1 p-0"> 6:40 Am 7:40 Am</td>
            <td>Yoga<hr class="m-1 p-0"> 6:40 Am 7:40 Am</td>
            <td>Core<hr class="m-1 p-0"> 6:40 Am 7:40 Am</td>
            <td>Metcom<hr class="m-1 p-0"> 6:40 Am 7:40 Am</td>
          </tr>
          <tr>
            <th>Streatching <hr class="m-1 p-0"> 6:40 Am 7:40 Am</th>
            <td>Combat<hr class="m-1 p-0"> 6:40 Am 7:40 Am</td>
            <td>Booty<hr class="m-1 p-0"> 6:40 Am 7:40 Am</td>
            <td>Zumba<hr class="m-1 p-0"> 6:40 Am 7:40 Am</td>
            <td>Yoga<hr class="m-1 p-0"> 6:40 Am 7:40 Am</td>
            <td>Core<hr class="m-1 p-0"> 6:40 Am 7:40 Am</td>
            <td>Metcom<hr class="m-1 p-0"> 6:40 Am 7:40 Am</td>
          </tr>
          <tr>
            <th>Streatching <hr class="m-1 p-0"> 6:40 Am 7:40 Am</th>
            <td>Combat<hr class="m-1 p-0"> 6:40 Am 7:40 Am</td>
            <td>Booty<hr class="m-1 p-0"> 6:40 Am 7:40 Am</td>
            <td>Zumba<hr class="m-1 p-0"> 6:40 Am 7:40 Am</td>
            <td>Yoga<hr class="m-1 p-0"> 6:40 Am 7:40 Am</td>
            <td>Core<hr class="m-1 p-0"> 6:40 Am 7:40 Am</td>
            <td>Metcom<hr class="m-1 p-0"> 6:40 Am 7:40 Am</td>
          </tr>
          <tr>
            <th>Streatching <hr class="m-1 p-0"> 6:40 Am 7:40 Am</th>
            <td>Combat<hr class="m-1 p-0"> 6:40 Am 7:40 Am</td>
            <td>Booty<hr class="m-1 p-0"> 6:40 Am 7:40 Am</td>
            <td>Zumba<hr class="m-1 p-0"> 6:40 Am 7:40 Am</td>
            <td>Yoga<hr class="m-1 p-0"> 6:40 Am 7:40 Am</td>
            <td>Core<hr class="m-1 p-0"> 6:40 Am 7:40 Am</td>
            <td>Metcom<hr class="m-1 p-0"> 6:40 Am 7:40 Am</td>
          </tr>
          <tr>
            <th>Streatching <hr class="m-1 p-0"> 6:40 Am 7:40 Am</th>
            <td>Combat<hr class="m-1 p-0"> 6:40 Am 7:40 Am</td>
            <td>Booty<hr class="m-1 p-0"> 6:40 Am 7:40 Am</td>
            <td>Zumba<hr class="m-1 p-0"> 6:40 Am 7:40 Am</td>
            <td>Yoga<hr class="m-1 p-0"> 6:40 Am 7:40 Am</td>
            <td>Core<hr class="m-1 p-0"> 6:40 Am 7:40 Am</td>
            <td>Metcom<hr class="m-1 p-0"> 6:40 Am 7:40 Am</td>
          </tr>
          <tr>
            <th>Streatching <hr class="m-1 p-0"> 6:40 Am 7:40 Am</th>
            <td>Combat<hr class="m-1 p-0"> 6:40 Am 7:40 Am</td>
            <td>Booty<hr class="m-1 p-0"> 6:40 Am 7:40 Am</td>
            <td>Zumba<hr class="m-1 p-0"> 6:40 Am 7:40 Am</td>
            <td>Yoga<hr class="m-1 p-0"> 6:40 Am 7:40 Am</td>
            <td>Core<hr class="m-1 p-0"> 6:40 Am 7:40 Am</td>
            <td>Metcom<hr class="m-1 p-0"> 6:40 Am 7:40 Am</td>
          </tr>
        </tbody>
      </table>
        <!-- /Schedules -->


        <div class="card m-auto mt-4" id="content" style="width: 18rem;">
          <img src="https://marketplace.canva.com/EAFxdcos7WU/1/0/1600w/canva-dark-blue-and-brown-illustrative-fitness-gym-logo-oqe3ybeEcQQ.jpg" class="card-img-top" alt="...">
          <div class="card-body">
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
          </div>
        </div>

        <!-- footer -->
        <footer class="bg-success text-center text-white" style="border-radius: 100px 100px  0 0; margin-top: 250px;">
          <!-- Grid container -->
          <div class="container p-4 pb-0">
            <div class="row rounded p-3">
              <div class="col-3">
                <a href="#" style="color: #ffff; text-decoration: none; font-size: large;">About Plant Fitness</a>
              </div>
              <div class="col-3">
                <a href="#" style="color: #ffff; text-decoration: none; font-size: large;">Blog</a>
              </div>
              <div class="col-3">
                <a href="#" style="color: #ffff; text-decoration: none; font-size: large;">Membership</a>
              </div>
              <div class="col-3">
                <a th:href="@{project/show}" style="color: #ffff; text-decoration: none; font-size: large;">Careers</a>
              </div>
            </div>
          </div>
          <!-- Section: Social media -->
          <section class="mb-4">
            <!-- Facebook -->
            <a class="btn btn-outline-light btn-floating m-1" href="#!" role="button"
              style="background-color: #1c5ce4;"><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16"
                fill="currentColor" class="bi bi-facebook" viewBox="0 0 16 16">
                <path
                  d="M16 8.049c0-4.446-3.582-8.05-8-8.05C3.58 0-.002 3.603-.002 8.05c0 4.017 2.926 7.347 6.75 7.951v-5.625h-2.03V8.05H6.75V6.275c0-2.017 1.195-3.131 3.022-3.131.876 0 1.791.157 1.791.157v1.98h-1.009c-.993 0-1.303.621-1.303 1.258v1.51h2.218l-.354 2.326H9.25V16c3.824-.604 6.75-3.934 6.75-7.951" />
              </svg></a>
            <!-- Discord -->
            <a class="btn btn-outline-light btn-floating m-1" href="#!" role="button"
              style="background-color: rgb(80, 15, 246)"><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-telegram" viewBox="0 0 16 16">
                <path d="M16 8A8 8 0 1 1 0 8a8 8 0 0 1 16 0M8.287 5.906q-1.168.486-4.666 2.01-.567.225-.595.442c-.03.243.275.339.69.47l.175.055c.408.133.958.288 1.243.294q.39.01.868-.32 3.269-2.206 3.374-2.23c.05-.012.12-.026.166.016s.042.12.037.141c-.03.129-1.227 1.241-1.846 1.817-.193.18-.33.307-.358.336a8 8 0 0 1-.188.186c-.38.366-.664.64.015 1.088.327.216.589.393.85.571.284.194.568.387.936.629q.14.092.27.187c.331.236.63.448.997.414.214-.02.435-.22.547-.82.265-1.417.786-4.486.906-5.751a1.4 1.4 0 0 0-.013-.315.34.34 0 0 0-.114-.217.53.53 0 0 0-.31-.093c-.3.005-.763.166-2.984 1.09"/>
              </svg></a>
            <!-- Linkedin -->
            <a class="btn btn-outline-light btn-floating m-1" href="#!" role="button"
              style="background-color: #0082ca;"><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16"
                fill="currentColor" class="bi bi-linkedin" viewBox="0 0 16 16">
                <path
                  d="M0 1.146C0 .513.526 0 1.175 0h13.65C15.474 0 16 .513 16 1.146v13.708c0 .633-.526 1.146-1.175 1.146H1.175C.526 16 0 15.487 0 14.854V1.146zm4.943 12.248V6.169H2.542v7.225h2.401m-1.2-8.212c.837 0 1.358-.554 1.358-1.248-.015-.709-.52-1.248-1.342-1.248-.822 0-1.359.54-1.359 1.248 0 .694.521 1.248 1.327 1.248h.016zm4.908 8.212V9.359c0-.216.016-.432.08-.586.173-.431.568-.878 1.232-.878.869 0 1.216.662 1.216 1.634v3.865h2.401V9.25c0-2.22-1.184-3.252-2.764-3.252-1.274 0-1.845.7-2.165 1.193v.025h-.016a5.54 5.54 0 0 1 .016-.025V6.169h-2.4c.03.678 0 7.225 0 7.225h2.4" />
              </svg></i></a>
            <!-- Github -->
            <a class="btn btn-outline-light btn-floating m-1" href="#!" role="button"
              style="background-color: #333333;"><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-threads-fill" viewBox="0 0 16 16">
                <path d="M6.81 9.204c0-.41.197-1.062 1.727-1.062.469 0 .758.034 1.146.121-.124 1.606-.91 1.818-1.674 1.818-.418 0-1.2-.218-1.2-.877Z"/>
                <path d="M2.59 16h10.82A2.59 2.59 0 0 0 16 13.41V2.59A2.59 2.59 0 0 0 13.41 0H2.59A2.59 2.59 0 0 0 0 2.59v10.82A2.59 2.59 0 0 0 2.59 16M5.866 5.91c.567-.81 1.315-1.126 2.35-1.126.73 0 1.351.246 1.795.711.443.466.696 1.132.754 1.983q.368.154.678.363c.832.559 1.29 1.395 1.29 2.353 0 2.037-1.67 3.806-4.692 3.806-2.595 0-5.291-1.51-5.291-6.004C2.75 3.526 5.361 2 8.033 2c1.234 0 4.129.182 5.217 3.777l-1.02.264c-.842-2.56-2.607-2.968-4.224-2.968-2.675 0-4.187 1.628-4.187 5.093 0 3.107 1.69 4.757 4.222 4.757 2.083 0 3.636-1.082 3.636-2.667 0-1.079-.906-1.595-.953-1.595-.177.925-.651 2.482-2.733 2.482-1.213 0-2.26-.838-2.26-1.936 0-1.568 1.488-2.136 2.663-2.136.44 0 .97.03 1.247.086 0-.478-.404-1.296-1.426-1.296-.911 0-1.16.288-1.45.624l-.024.027c-.202-.135-.875-.601-.875-.601Z"/>
              </svg></i></a>
          </section>
        
          <div class="m-5">
            <p><span class="small">*Classic memberships begin at $15 and PF Black Card® memberships begin at $24.99, billed monthly. Memberships may include 12-month commitment. State and local taxes may apply. Subject to an annual fee of $49. Prices may vary depending on location. Services and perks subject to availability and restrictions. Must be at least 18 years old to enroll, or 13-17 with parent/guardian. State and local restrictions on tanning frequency with PF Black Card® memberships apply. Participating locations only. Locations independently owned and operated. See home club for details. We reserve the right to correct pricing errors or withdraw offer at any time.</span></p>
          </div>
          <!-- Section: Social media -->
          </div>
          <!-- Grid container -->
        
          <!-- Copyright -->
          <div class="text-center p-3" style="background-color: rgba(0, 0, 0, 0.2);">
            © 2020 Copyright:
            <a class="text-white" href="https://mdbootstrap.com/">ZFitness.com</a>
          </div>
          <!-- /Copyright -->
        </footer>
        <!-- /footer -->


        <!-- Login Model -->
<!-- Modal -->
<div class="modal fade" id="login" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title" id="exampleModalLabel">Login Form</h5>
        <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
      </div>
      <div class="modal-body">
        <div class="row">
          <div class="col-lg-6 mb-3">
            <label for="email" class="form-label"></label>
            <input type="email" class="form-control" id="email" placeholder="email">
          </div>
          <div class="col mb-3">
            <label for="password" class="form-label"></label>
            <input type="password" class="form-control" id="password" placeholder="Password">
          </div>
        </div>
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
        <button type="button" class="btn btn-primary">Login</button>
      </div>
    </div>
  </div>
</div>
         <!-- /Login model -->

         <!-- Sign Up Model -->
<!-- Modal -->
<div class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title" id="exampleModalLabel">Sign Up Form</h5>
        <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
      </div>
      <div class="modal-body">
        <div class="row">
          <div class="col mb-3">
            <label for="name" class="form-label"></label>
            <input type="text" class="form-control" id="name" placeholder="Name">
          </div>
            <div class="col-lg-6 mb-3">
              <label for="phone" class="form-label"></label>
              <input type="text" class="form-control" id="phone" placeholder="Phone No">
            </div>
            <div class="col-lg-6 mb-3">
              <label for="email" class="form-label"></label>
              <input type="email" class="form-control" id="email" placeholder="email">
            </div>
            <div class="col-lg-6 mb-3">
              <label for="email" class="form-label"></label>
              <select class="form-select" aria-label="Default select example">
                <option selected>Male</option>
                <option value="2">Female</option>
              </select>
            </div>
        </div>
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
        <button type="button" class="btn btn-primary">Create</button>
      </div>
    </div>
  </div>
</div>
         <!-- /sign up model -->

    <!-- bootstrap js -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>
</body>
</html>
