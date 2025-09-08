<!DOCTYPE html>
    <html>
        <head>
            <link rel="preconnect" href="https://fonts.googleapis.com">
            <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
            <link href="https://fonts.googleapis.com/css2?family=Roboto+Flex:opsz,wght@8..144,100..1000&display=swap" rel="stylesheet">
            <title>youtube.com</title>
            <style>
                p{font-family: roboto flex;}

                .vidp{/*for div*/
                    display: inline-block;
                    vertical-align: top;
                }

                .search{/*for search bar*/
                    font-size:20px;
                    width: 300px;
                    border-radius: 50px;
                    padding-left: 20px;
                    margin-bottom: 30px;
                    margin-top: 20px;
                    margin: auto;
                    display: block;
                }
                .image1{/*tags like font-size will not show any change in the image file */
                    width: 400px;
                    height:220px; 
                    object-fit: cover;/*cover=crops the image to fit the size of the frame//contain = this shrinks the image till it fits the croped size*/
                    object-position: right;/*if the image doesnot fir then it shows the croped image's right pa rt*/
                    display: block;
                

                }
                
                .txt1{
                    
                    font-size: 14px;
                    font-weight: bold;
                    
                    
                }
                

            </style>
        </head>

        <body>
            <input class="search" type="text" placeholder="Search with youtube"><!--type can also be checkbox-->
    
            <div class="vidp">
                <img src="thumbnails/thumbnail-1.webp" alt="the pic" class="image1">    
                <p class="txt1">
                    Talking Tech and AI with Google CEO Sundar Pichai!
                </p> 
                <p class="ytbr">
                    Marques Brownlee   
                </p>
                <p class="views">
                    3.4M views · 6 months ago
                </p>
            </div>

            <div class="vidp">
                <img src="thumbnails/thumbnail-2.webp" alt="the pic" class="image1">    
                <p class="txt1">
                    Try Not To Laugh Challenge #9
                </p> 
                <p class="ytbr">
                    Markiplier   
                </p>
                <p class="views">
                    19M views · 4 years ago
                </p>
            </div>
                
        </body>
    </html>
