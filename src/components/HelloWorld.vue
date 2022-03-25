<template>
  <body>

  <div class="container">

    <div id="menu">
      <div id="logo"><a href="games/ticTacToe/runTicTacToe.html">
        <button>TicTacToe</button>
      </a></div>
      <div class="option">GAMES</div>
      <div class="option">ONLINE PLAYERS</div>
      <div class="option">RANKING</div>
      <div class="option">STATS</div>
      <div class="option">MY ACCOUNT</div>
      <div class="option">FRIENDS</div>
      <div class="option">NEWS</div>
    </div>

    <div id="main">
      <div id="top">
        <div id="topL">
          kVRnik
        </div>
        <div id="topR">
          <button id="login">Log in</button>
          <button id="signin">Sign in</button>
        </div>
      </div>

      <div class="brake"></div>

      <div class="bar">
        <h1>O projekcie</h1>
      </div>

      <div class="soon">
        Coming soon...
      </div>

      <div class="brake"></div>

      <div class="bar">
        <h1>Twórcy projektu</h1>
      </div>
      <div id= "people">
        <div class="person">
          <div class="personPhoto">
            <img class="person_img" src="frontend/image/salamandra.jpg" alt="Marcin Salamandra">
          </div>

          <h1>Marcin Salamandra</h1>
          Mauris pretium est eget accumsan pretium. In tincidunt venenatis lorem, non lobortis lacus
          condimentum nec. Vestibulum a ligula arcu. Sed in nunc sit amet risus lacinia accumsan iaculis
          sed nisi. Nulla sagittis consectetur velit sed consequat. Nunc eleifend in leo in dictum.
          Morbi imperdiet elementum auctor. Vivamus id lorem erat. Nullam molestie interdum ipsum id
          consequat. Cras ac magna ipsum. Pellentesque nunc justo, fermentum id pellentesque nec, rutrum
          at ipsum. Morbi elementum magna in orci lobortis, ut porta odio ornare. Cras elementum magna ac
          turpis tristique ultricies.
        </div>

        <div class="person">
          <div class="personPhoto">
            <img class="person_img" src="frontend/image/los.jpg" alt="Lukasz Pawlos">
          </div>
          <h1>Łukasz Pawłoś</h1>
          Mauris pretium est eget accumsan pretium. In tincidunt venenatis lorem, non lobortis lacus
          condimentum nec. Vestibulum a ligula arcu. Sed in nunc sit amet risus lacinia accumsan iaculis
          sed nisi. Nulla sagittis consectetur velit sed consequat. Nunc eleifend in leo in dictum.
          Morbi imperdiet elementum auctor. Vivamus id lorem erat. Nullam molestie interdum ipsum id
          consequat. Cras ac magna ipsum. Pellentesque nunc justo, fermentum id pellentesque nec, rutrum
          at ipsum. Morbi elementum magna in orci lobortis, ut porta odio ornare. Cras elementum magna ac
          turpis tristique ultricies.

        </div>

        <div class="person">
          <div class="personPhoto">
            <img class="person_img" src="frontend/image/remek.jpg" alt="Remigiusz Mielcarz">
          </div>
          <h1>Remigiusz Mielcarz</h1>
          Mauris pretium est eget accumsan pretium. In tincidunt venenatis lorem, non lobortis lacus
          condimentum nec. Vestibulum a ligula arcu. Sed in nunc sit amet risus lacinia accumsan iaculis
          sed nisi. Nulla sagittis consectetur velit sed consequat. Nunc eleifend in leo in dictum.
          Morbi imperdiet elementum auctor. Vivamus id lorem erat. Nullam molestie interdum ipsum id
          consequat. Cras ac magna ipsum. Pellentesque nunc justo, fermentum id pellentesque nec, rutrum
          at ipsum. Morbi elementum magna in orci lobortis, ut porta odio ornare. Cras elementum magna ac
          turpis tristique ultricies.
        </div>
      </div>

      <div class="brake"></div>

      <div class="bar">
        <a href="https://www.iteratec.com/pl/">
          <img id="companyPhoto" src="frontend/image/iteratec.png" alt="iteratec logo">
        </a>
      </div>

      <div class="soon">
        Coming soon...
      </div>


    </div>
  </div>
  </body>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
body {
  background: #394041;
  font-family: "Microsoft YaHei UI Light", serif;
}

.container{
  width: auto;
  padding: 10px;
  /*height: 850px;*/
  display: flex;


}
.container div {
  margin: 10px;
  /*width: 200px;*/
}

#menu{
  background: #1c1e1e;
  min-height: 100px;
  width: 150px;
  color: white;
}

#main{
  background: #1c1e1e;
  min-height: 250px;
  width: 100%;
  color: white;
}

.soon{
  background: #0c0c0c;
  text-align: center;
  padding: 200px;
  font-size: 30px;
  color: #394041;
  font-weight: 800;
}

#top{
  display: flex;
  justify-content: space-between;
  align-items: center;
  text-align: center;
  font-size: 60px;
  letter-spacing: 3px;
  font-weight: 900;
}

#topL{
  float:left;
}

#topR{
  float:right;
  align-self: flex-end;
  text-align: center;
  margin-bottom: 10px;
  transform: translateY(-25%);
}

#company{
  padding: 10px;

  display: flex;
  justify-content: space-between;
  text-align: center;
  background: #4CAF50;
  /*height: 100px;*/
}


#companyPhoto{
  width: 190px;
  height: 35px;
  padding: 21px;
}

.option{
  float: bottom;
  font-size: 20px;
  font-weight: 900;
  border-bottom: 2px solid black;
  border-top: 2px solid black;
  padding: 10px;
  opacity: 0.8;
  text-align: center;
}
.option:hover{
  background: #2d2d2d;
  cursor: pointer;
}

#people{
  display: flex;
  justify-content: space-between;
  text-align: center;
}

.person{
  background: #0c0c0c;
  width: 33%;
  padding: 20px;
}

.person_img{
  width: 150px;
  border-radius: 100%;
  border: 3px solid white;
}

.personPhoto{
}

.bar{
  text-align: center;
  background: #4CAF50;
  /*background: #0c0c0c;*/
  height: auto;
  padding: 5px;
}

#login{
  background-color: #4CAF50; /* Green */
  color: white;
  padding: 10px 16px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 20px;
  border: 2px solid black;

}


#signin{

  background-color: white; /* Green */
  padding: 10px 16px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 20px;
  border: 2px solid black;
}

.brake{
  height: 100px;
}
</style>
