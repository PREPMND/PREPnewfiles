# PREPnewfiles
Just A New Repo!

<!DOCTYPE html>
<html lang="en">
    <head>
        <style>
            .container{
                display: flex;
                flex: 1;
                justify-content: space-evenly;
                align-content: center;
                margin-top: 40px;
                margin-left: 24px;
            }
            img{
                height: 256px;
                width: 268px;
                animation: float 3s infinite ease-in-out;
                margin-bottom: 20px;
            }
            @keyframes float{
                0%{transform: translateY(0);}
                50%{transform: translateY(20px);}
                100%{transform: translateY(0);}
            }
            .text{
                font-size: 20px;
            }
            h1{
                text-align: center;
                animation: float 3s infinite ease-in-out;
            }           
        </style>
    </head>
    <body>
        <h1 style="font-family: cursive;font-weight: 900; font-size: 54px;"> Information !</h1>
        <div class="container">
            <div class="barberry">
                <img src="https://github.com/TheOdinProject/css-exercises/blob/main/foundations/flex/04-flex-information/images/barberry.png?raw=true" alt="barberry">
                <div class="text">This is a type of plant. We love this one.</div>
            </div>
            <div class="chilli">
                <img src="https://github.com/TheOdinProject/css-exercises/blob/main/foundations/flex/04-flex-information/images/chilli.png?raw=true" alt="chilli">
                <div class="text">This is another type of plant. Isn't it nice?</div>
            </div>
            <div class="pepper">
                <img src="https://github.com/TheOdinProject/css-exercises/blob/main/foundations/flex/04-flex-information/images/pepper.png?raw=true" alt="pepper">
                <div class="text">We have so many plants. Yay plants</div>
            </div>
            <div class="saffron">
                <img src="https://github.com/TheOdinProject/css-exercises/blob/main/foundations/flex/04-flex-information/images/saffron.png?raw=true" alt="saffron">
                <div class="text">I'm running out of things to say about plants.</div>
            </div>
        </div>
    </body>
</html>
