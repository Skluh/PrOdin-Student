# PrOdin-Student
With the purpose to remake(Odin-page) or make a website with my own abilities and all of this only whith html and css.

    <body>
        <header>
            <nav class="dad">
                <div class="son"><a href="*"><img src="https://media.istockphoto.com/vectors/lynx-black-sign-vector-id1143714947?k=20&m=1143714947&s=612x612&w=0&h=n6ngBku-Xz7Q_3QMiznhQqaIa0jkmld5sIjLJwgLi1U=" alt="BobCat"></a></div>
                <div class="son-2">
                    <a href="*">header Link 1</a>
                    <a href="*">header Link 2</a>
                    <a href="*">header Link 3</a>
                </div>
            </nav>
            
            <div class="dad mod">
                <div class="content">
                    <h1>This web is awesome!</h1>
                    <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit.<br>
                        Lorem ipsum dolor sit amet consectetur adipisicing elit.
                    </p>
                    <button class="buttons">Sing up</button>
                </div>

                <div class="content-2">
                    <img src="*" alt="This is a placeholder for a image">
                </div>
            </div>              
        </header>

        <main>
            <section class="flex-container">
                <nav><h2>Some random information</h2></nav>
                <div class="flex-content">
                    <div>
                        <div class="flex-son"></div>
                        <p class="flex-p">This is some text under an ilustration or image</p>
                    </div>
                    <div>
                        <div  class="flex-son"></div>
                        <p class="flex-p">This is some text under an ilustration or image</p>
                    </div>
                    <div>
                        <div  class="flex-son"></div>
                        <p class="flex-p">This is some text under an ilustration or image</p>
                    </div>
                </div>
            </section>
                
            <article class="art-content">
                <p class="p-1">Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolorum laudantium perspiciatis possimus hic eos aspernatur? Nobis perferendis suscipit autem impedit placeat, deserunt aliquid quis unde similique earum eos ratione neque?</p>
                <p class="p-2">-Ariel,God of soldiers</p>
            </article>
            <section class="flex-box">
                <div>
                    <h3>Call to action! It`s time!</h3>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                </div>
                <div><button class="buttons">Sing up</button></div>
            </section>
        </main>
        <footer>
            <div>
                <p>Copyright @ The Odin Project</p>
            </div>
        </footer>
    </body>





header {
    background-color: #1f2937;
}

.dad {
    display: flex;
    justify-content: space-between;
    align-items: center;
    text-decoration: none;
    padding-top: 10px;
}

.son {
    width: 40px;
    height: 40px;
    overflow: ;
    margin: 0px 100px;
    padding-bottom: 50px;
}

.son img {
   width: 100%;
   height: 100%;
   border-radius: 50%;
   border: 2px solid white;
   padding: 2px;
}

.son-2 {
    margin: 0px 150px 0px 100px;
    padding-bottom: 54px;
}

.son-2 a {
    color:  rgb(197, 196, 196);
    padding-right: 12px;
}

a{
    text-decoration: none; 

}

.mod {
    margin: 12px;
    justify-content: space-around;    
}

.content {
}

.content h1 {
    font-size: 48px;
    color: white;
}
.content p {
    color: rgb(197, 196, 196);
}

.buttons {
    width: 80px;
    height: 30px;
    margin-top: 10px;
    border-radius: 10px;
    background-color: #3882f6;
    color: white;
}

.content-2 {
    padding: 50px;
}

.content-2 img {
    padding: 100px;
    background-color: slategrey;
}

.flex-container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-direction: column;
}

.flex-container nav {
    margin: 0px 0px 25px 0px;
}

.flex-content {
    display: flex;
    flex-direction: row;
    justify-content: center;
    gap: 20px;
    margin: 40px 0px 80px 0px;
}

.flex-son {
    border: 2px solid #3882f6;
    width: 120px;
    height: 120px;
    border-radius: 10px;
    margin-left: 88px;
}

.flex-p {
    margin-top: 10px;
}

.art-content {
    display: flex;
    align-items: flex-end;
    height: 328px;
    flex-direction: column;
    justify-content: center;
    background-color: #e5e7eb;
}

.p-1 {
    font-size: 20px;
    margin: 200px 200px 0px 200px;
}

.p-2 {
    margin: 0px 150px 200px 0px;
}

.flex-box {
    display: flex;
    justify-content: space-evenly;
    width: 700px;
    padding: 15px;
    align-items: center;
    margin: 100px auto;
    background-color: #3882f6;
    border-radius: 5px;
}

.flex-box h3 {
    color: white;
}

.flex-box p {
    color: #e5e7eb;
}

footer {
    display: flex;
    justify-content: center;
    background-color: #1f2937;
    height: 70px;
    align-items: center;
}

footer div {
    font-size: 13px;
    color: #e5e7eb;
}