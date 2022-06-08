HTML

     <!DOCTYPE html>
      <html lang="en">
      <head>
          <meta charset="UTF-8">
          <meta http-equiv="X-UA-Compatible" content="IE=edge">
          <meta name="viewport" content="width=device-width, initial-scale=1.0">
          <link rel="stylesheet" href="css/estilos.css">
          <title>Halo Infinite</title>
      </head>
      <body>
          <header>
              <nav>
                  <a href="https://www.microsoft.com"><img src="img/microsoft.png" alt="" width="100px"></a>
                  <a href="https://www.xbox.com/es-MX/?xr=mebarnav"><img src="img/xbox.png" alt="logo xbox" width="100px"></a>
                  <ul>
                      <a href=""><li>
                          <div>
                              <button type="button">
                                  "Game Pass&ZeroWidthSpace; "
                                  ::after
                              </button>
                              <ul>
                                  <li><a href="https://www.xbox.com/es-MX/xbox-game-pass?xr=shellnav">Descripción general</a></li>
                                  <li><a href="https://www.xbox.com/es-mx/xbox-game-pass/games?xr=shellnav">Explorar juegos</a></li>
                                  <li><a href="https://www.xbox.com/es-MX/xbox-game-pass/pc-game-pass?xr=shellnav">PC Game Pass</a></li>
                                  <li><a href="https://www.xbox.com/es-MX/xbox-game-pass/cloud-gaming?xr=shellnav">Xbox Cloud Gaming (Beta)</a></li>
                                  <li><a href="https://www.xbox.com/es-MX/live/gold?xr=shellnav">Xbox Live Gold</a></li>
                              </ul>
                          </div>
                      </li></a>
                      <a href=""><li>juegos</li></a>
                      <a href=""><li>dispositivos</li></a>
                      <a href=""><li>juega</li></a>
                      <a href=""><li>comunidad</li></a>
                      <a href=""><li>más</li></a>         
                  </ul>
              </nav>
          </header>
          <section>
              <div></div>
              <div>
                  <h1>Halo Infinite</h1>
              </div>
              <div>
                  <a href="https://www.xbox.com/es-mx/games/halo-infinite?&ef_id=EAIaIQobChMIpeapm-6b-AIVIgnnCh28DwiMEAAYASAAEgJgYvD_BwE:G:s&OCID=AID2202619_SEM_EAIaIQobChMIpeapm-6b-AIVIgnnCh28DwiMEAAYASAAEgJgYvD_BwE:G:s&gclid=EAIaIQobChMIpeapm-6b-AIVIgnnCh28DwiMEAAYASAAEgJgYvD_BwE#purchaseoptions">CONSÍGUELO AHORA</a>
                  <div>
                      <div>
                          <img src="img/gamepass.png" alt="">
                      </div>
                      <p>Ahora disponible con Xbox Game Pass</p>
                      <a href="https://www.xbox.com/xbox-game-pass#join">UNETE AHORA</a>
                  </div>
                  <div>
                      <a href="https://www.xbox.com/es-mx/games/halo-infinite?&ef_id=EAIaIQobChMIpeapm-6b-AIVIgnnCh28DwiMEAAYASAAEgJgYvD_BwE:G:s&OCID=AID2202619_SEM_EAIaIQobChMIpeapm-6b-AIVIgnnCh28DwiMEAAYASAAEgJgYvD_BwE:G:s&gclid=EAIaIQobChMIpeapm-6b-AIVIgnnCh28DwiMEAAYASAAEgJgYvD_BwE#optimized"><img src="img/series xs.png" alt=""></a>
                  </div>

              </div>
          </section>
          <main>
          </main>
      </body>
      </html>
      
      
  CSS
  
  
      *{
        margin: 0;
        padding: 0;
    }
    /*  */
    header{
        background-image: url(https://compass-ssl.xbox.com/assets/9c/94/9c944d9c-7ef1-4b46-9f68-9b02966d3993.jpg?n=Halo-Infinite_GLP-Page-Hero-0_1083x609.jpg);
        height: 120vh;
        background-repeat: no-repeat;
        background-position: top;
        background-size: cover;
    }
    button::after{
        position: absolute;
        padding-top: 5px;
    }
    ::after{
        width: 300px;
    }
    nav{
        display: flex;
        align-items: center;
    }
    nav img{
        margin-top: 15px;
        margin-left: 20px;
    }
    ul{
        display: flex;
        list-style: none;
        margin-right: 50px;
        margin-top: 15px;
    }
    li{
        margin-left: 20px;
        text-transform: capitalize;
        text-decoration: none;
        color: white;
    }
    a{
        text-decoration: none;
    }
    li:hover{
        color: aqua;
    }
    h1{
        font-weight: 700;
        color: white;
    }
