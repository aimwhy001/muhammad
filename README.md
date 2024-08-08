<!DOCTYPE html>
<html>
    <head>
        <title>folio</title>
        <style>
        body{
    font-family:Arial, Helvetica, sans-serif;
    background-color: rgb(209, 198, 209);
    
}




ul {
    list-style-type: none;
}


nav {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding-inline: 1rem;
}

nav > ul {
    display: flex;
    gap: 1rem;
    padding-right:20rem;
}

button{
    background-color: rgb(231, 29, 231);
    color: white;
    border: 1px solid rgb(175, 1, 175);
    border-radius:8px;
    text-align: center;
    height: 30px;
    width: 100px;
   
}

span{
    color: rgb(187, 4, 187);
}
section{
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    padding-top: 7%;
    padding-inline: 12rem;


}
.button{
    display: flex;
    flex-direction: row;
    gap: 50px;
    padding-top: 40px;
    border-left: 20px;
    text-align:center;
}
.button1{
    background-color: white;
    color: rgb(180, 4, 180);
}
</style>
    </head>
    <body>
        <div>
            <nav>
                    <h1><span>M</span>uh'd.</h1>
                    <ul>
                     <li>home</li>
                     <li>about</li>
                     <li>portfolio</li>
                     <li>blog</li>
                     <li>contact</li>
                    </ul>
                  
                <button>Let's Talk</button>
            </nav>
            <section>
                <div>
                  <h1>Hi, I'm <span>Muhammad Yusuf</span></h1>
                  <h2>Frontend developer</h2>
                  <p>Muhammad a frontend developer </p>
                  <div class="button">
                      <button >Hire Me  </button>
                      <button class="button1">See Project</button>
                  </div>    
               </div>
               <div><image src="pic/MY.jpg"  width="300px" height="400px"></image> </div>
              
            </section>
           
        </div>
    

    </body>
</html>
