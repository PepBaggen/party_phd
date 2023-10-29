
<head>
    <meta charset="UTF-8">
    <title>PHD-Danielle</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
</head>    

<style>
        @import url('https://fonts.googleapis.com/css2?family=Montserrat&display=swap');
        @import url('https://fonts.googleapis.com/css2?family=Montserrat&family=Playfair+Display:wght@500&display=swap');

 
        * {
    margin: 0;
    padding: 0;
}
        

        body {
    margin: 0;
    padding: 0;
    height: 100vh;
    width: 100vw;
    background-color: transparent;
    background-image: url('https://images.unsplash.com/photo-1514483127413-f72f273478c3?auto=format&fit=crop&q=80&w=1170&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D');
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center center;
    color: #f5f5f5; /* Creme white text color */
    font-family: 'Montserrat', sans-serif;
    overflow: hidden;
}



    .all {
    text-align: center;
    font-size: 4vw;
    padding-top: 3vh; /* Adjust the padding-top value */
    padding: 5vw 5vw;
    overflow: hidden;
}

.kaart {
    text-align: center;
    margin: 0 auto;
    padding-top: 1vh; /* Adjust the padding-top value */
}

.all h4 {
    font-size: 1.5vw;
    padding-top: 1vh; /* Adjust the padding-top value */
    text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.2);
    font-weight: normal; /* Remove bold formatting */
}


.all h1 {
    font-size: 2.5vw;
    padding-top: 1vh; /* Adjust the padding-top value */
    text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.2);
    font-weight: normal; /* Remove bold formatting */
}

        .all h2 {
            font-size: 5vw; /* Adjust the font size as needed */
            color: rgb(255, 235, 123); /* Add a gold color */
            text-shadow: 0 0 10px gold; /* Add a subtle glow effect */
        }
        .date {
            font-size: 1.5vw;
            color: rgb(255, 235, 123); /* Add a gold color */
            text-shadow: 0 0 10px gold; /* Add a subtle glow effect */
            padding-top: 1vh; /* Adjust the padding-top value */
        }
        .all h5 {
            padding-top: 2vh;
            font-size: 3vw; /* Adjust the font size as needed */
            color: rgb(255, 235, 123); /* Add a gold color */
            text-shadow: 0 0 10px gold; /* Add a subtle glow effect */
        }

        .all p {
            padding-top: 3vh;
            font-size: 2vw; /* Adjust the font size as needed */
            /* Style the text with a gold color */
            color: white;
            /* Add a subtle text-shadow for the glow effect */
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.2);
        }

       
     
       
         .section span a{
            font-size: 4vw;
            padding-bottom: 15vh;
            transition: color 0.5s ease;
           

         }
         .section a:hover{
            color: rgb(255, 235, 123);

         }
    
        .contact-icons {
            display: flex;
            font-size: 1vw; /* Adjust the font size as needed */
            justify-content: center;
            padding-top: 2vh; /* Vertical centering (adjust value as needed) */

        }

        .contact-icons a {
            display: inline-block;
            margin: 0 20px;
            color: white;
            transition: color 0.5s ease;
        }
          
            .contact-icons a:hover {
                color: rgb(255, 235, 123); /* Change color on hover (you can adjust the color) */
            }

            .top {
                text-align: center;
                font-size: 0.5vw;
                position: sticky;
            }

            .top a{
                color: white;
                text-decoration: none;
                transition: color 0.5s ease;
            } 

            .top a:hover{
                color: rgb(255, 235, 123);
            }       

            .payment-icon {
                display: inline-block;
            }
            .time p{
                font-size: 3vw !important;
                padding-top: 2vh;
            }

            .coin {
                width: 20px;
                height: 20px;
                border-radius: 50%;
                background-color: white;
                box-shadow: 0 0 10px rgba(0, 0, 0, 0.2); /* Optional: Add a subtle shadow effect */
                transition: background-color 0.3s ease;
                margin-top: 15px;
            }

            .coin:hover {
                background-color: rgb(255, 235, 123); /* Change to blue on hover */
            }

            @media screen and (min-width: 300px) {
                .all h2 {
                    font-size: 4vw; /* Adjust the font size as needed */
                    padding-top: 5vh;
                }

                .all p {
                    font-size: 3vw; /* Adjust the font size as needed */
                }

                .contact-icons {
                    font-size: 4vw; /* Adjust the font size as needed */
                }

                .all h4{
                    padding-top: 1vh;
                    font-size: 2.5vw;
                }

                .top{
                    font-size: 1.5vw;
                }
                .date {
                    font-size: 2vw ;
                }
            }

            @media screen and (min-width: 400px) {
                .all h2 {
                    font-size: 4vw; /* Adjust the font size as needed */
                    padding-top: 5vh;
                }

                .all p {
                    font-size: 3vw; /* Adjust the font size as needed */
                }

                .contact-icons {
                    font-size: 4vw; /* Adjust the font size as needed */
                }

                .all h4{
                    padding-top: 5vh;
                    font-size: 2.5vw;
                }

                .top{
                    font-size: 1.5vw;
                }
                .date {
                    font-size: 2vw;
                }
            }

            @media screen and (min-width: 600px) {
                .all h2 {
                    font-size: 3vw; /* Adjust the font size as needed */
                }

                .all p {
                    font-size: 2vw; /* Adjust the font size as needed */
                }

                .all h4{
                    padding-top: 5vh;
                    font-size: 2vw;
                }

                .contact-icons {
                    font-size: 2vw; /* Adjust the font size as needed */
                }

                .top{
                    font-size: 1.5vw;
                }
            }

            @media screen and (min-width: 1200px) {
                .all h1 {
                    font-size: 1.5vw; /* Adjust the font size as needed */
                }

                .all h2 {
                    font-size: 2.5vw; /* Adjust the font size as needed */
                }

                .all h5 {
                    font-size: 1.5vw; /* Adjust the font size as needed */
                }

             

                .all p {
                    font-size: 1.5vw; /* Adjust the font size as needed */
                }

                .contact-icons {
                    font-size: 1.6vw; /* Adjust the font size as needed */
                }

                .all h4{
                    font-size: 1vw; /* Adjust the font size as needed */
                    padding-top: 3vh;
                }

                .top{
                    font-size: 1vw;
                }
            }
        </style>

        <html lang="en">
        <body>
            
            <div class="all">
                <div class="top"><a href="https://docs.google.com/viewer?url=https://drive.google.com/uc?id=1ycdMVBYuo4p8IVZi078EtwgAuSe4wJtH&embedded=true" target="_blank"><h1>Thesis Link</h1></a></div>
                <div class="section" id="home">
                    <h2>PhD Party Daniëlle</h2>
                    <h4>Op vrijdag 10 november om 20:30 houdt Danielle haar promotie party. Het thema is:
                        <h5>"Natural Gold"</h5>
                    <br> Als je haar een cadeau wilt geven, zij wilt graag een antieke stationsbank voor in de tuin. Een kleine bijdrage is daarvoor heel welkom. Een bijdrage kan met het ronde icoontje hieronder.
                    <br>Namens Pepijn en Mieke (paranimfen)
                </h4>
                    <a href="https://tikkie.me/pay/jbh1ffbe3a5uikr2o8bm" target="_blank">
                        <div class="payment-icon">
                            <a href="https://tikkie.me/pay/jbh1ffbe3a5uikr2o8bm" target="_blank">
                                <div class="coin"></div>
                            </a>
                        </div>   </a>
                        
                    <div class="date">
                    10 november 2023 - 20:30 
                    </div>
                 
                    <div class="time"> <p>{days}d {hours}h {minutes}m {seconds}s</p></div>
                    </div>
                    
                     <p>  Tutto e Peppe
                    <br>Amsterdamsestraatweg 42, 3741 GS Baarn</p>
                    
                
                <div class="kaart">
                    <iframe src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d9777.44112416712!2d5.2626161!3d52.2186719!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x47c66b5f7f4d74ad%3A0x967c09204d113cd5!2sTutto%20Pepe!5e0!3m2!1snl!2snl!4v1698594320836!5m2!1snl!2snl" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>        </div>
                <div class="section" id="contact">
                    <div class="contact-icons">
                        <a href="mailto:davr@me.com" target="_blank">
                            <i class="fas fa-envelope"></i>
                        </a>
                        <a href="" target="_blank">
                            <i class="fas fa-phone"></i>
                            +31622141471
                        </a>
                    </div>
                </div>
            </div>

        </body>
        </html>



        <script>
            import { onMount } from 'svelte';
        
            let days = 0;
            let hours = 0;
            let minutes = 0;
            let seconds = 0;
        
            const countDownDate = new Date("Nov 10, 2023 20:30:00").getTime();
        
            onMount(() => {
                const interval = setInterval(() => {
                    const now = new Date().getTime();
                    const distance = countDownDate - now;
        
                    days = Math.floor(distance / (1000 * 60 * 60 * 24));
                    hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
                    minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
                    seconds = Math.floor((distance % (1000 * 60)) / 1000);
        
                    if (distance < 0) {
                        clearInterval(interval);
                        days = 0;
                        hours = 0;
                        minutes = 0;
                        seconds = 0;
                    }
                }, 1000);
            });
        </script>
        
        

