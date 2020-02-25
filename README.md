# Tribute-Page

<html>
<head>
    <title>CSS box model</title>
    <meta charset="utf-8">
    <style>
    
        .lovey-dovey {
            color: red;
            
        }
        
        #official-info {
            background: rgb(230, 230, 230);
            width: 70%;
            height: 180px;
            overflow-y: auto;
            overflow-x: hidden;
            margin: 15px 0px 10px 6px;
            border: 2px ridge rgb(161, 161, 161);
            padding: 6px;
            float:right;
        }
        
        #cute-cat {
            width: 120px;
            margin-right: 10px;
            margin-bottom: 10px;
            border: 6px ridge red;
            float:left;
        }
        
        #container {
            width: 400px;
            margin: auto;
            border: 1px ridge red;
            border-top: 10px ridge red;
            padding: 15px;
            background-color: rgb(198, 232, 242);
        }
        .details{
            color:red;
            float:right;
            width:52%;
            margin-bottom:6px;
         font-family:optima;
        }
        #heading{
            font-family:optima;
            margin-top:4px;
        }
        #help{
            float:left;
            width:203px;
            color:red;
        }
    </style>
</head>
<body>
    
    <div id="container">
    <h1 id="heading">You're Invited!</h1>

    <h2 id="heading">To My <span class="lovey-dovey">Birthday Party!🎂🎁 ��</span> </h2>
    <h3 id="help">I'm turning 100 years old 🎉 </h3>
    <ul>
        <li class="details">When: March 4, 2020
        <li class="details">Where: THE MOON
        <li class="details">BYOA(Bring Your Own Air)
        <li class="details">Attire: Black Tie
    </ul>
    
    
    <div id="official-info"><h3>Official Info on My B-Day</h3>
    <p><img id="cute-cat" src="https://upload.wikimedia.org/wikipedia/commons/7/76/Feliz_Aniversario_-_Happy_Birthday_-_PU1JFC.gif"> My Birthday is being held on the moon, at the Tycho Crater! There will be free transportation from Earth to the Tycho Crater, by way of rocketship! You are more than welcome to bring any friends and family. Please remeber to BYOA, as you will need it to survive. There will be a 4 course meal served with drinks and snacks. This is a black tie event so please dress accordingly. </p>
    <p></p>
    <p></p>
    <p></p>
    </div>
    
    
    </div>
    
</body>
</html>
