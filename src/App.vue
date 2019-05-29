<template>
    <div id="app">
        <!--<component :is="currentMenu" :right="side === 'right' ? true: false">
            <a href="#">
                <i class="fa fa-fw fa-star-o"></i>
                <span>Favourites</span>
            </a>
            <a href="#">
                <i class="fa fa-fw fa-bell-o"></i>
                <span>Alerts</span>
            </a>
            <a href="#">
                <i class="fa fa-fw fa-envelope-o"></i>
                <span>Messages</span>
            </a>
            <a href="#">
                <i class="fa fa-fw fa-comment-o"></i>
                <span>Comments</span>
            </a>
            <a href="#">
                <i class="fa fa-fw fa-bar-chart-o"></i>
                <span>Analytics</span>
            </a>
            <a href="#">
                <i class="fa fa-fw fa-newspaper-o"></i>
                <span>Reading</span>
            </a>
        </component>-->
        <main id="page-wrap">
            
        
            
        

            <h1>

                <svg class="machine" xmlns="http://www.w3.org/2000/svg" x="0px" y="0px" viewBox="0 0 645 526">
                  <defs/>
                  <g>
                    <path  x="-173,694" y="-173,694" class="large-shadow" d="M645 194v-21l-29-4c-1-10-3-19-6-28l25-14 -8-19 -28 7c-5-8-10-16-16-24L602 68l-15-15 -23 17c-7-6-15-11-24-16l7-28 -19-8 -14 25c-9-3-18-5-28-6L482 10h-21l-4 29c-10 1-19 3-28 6l-14-25 -19 8 7 28c-8 5-16 10-24 16l-23-17L341 68l17 23c-6 7-11 15-16 24l-28-7 -8 19 25 14c-3 9-5 18-6 28l-29 4v21l29 4c1 10 3 19 6 28l-25 14 8 19 28-7c5 8 10 16 16 24l-17 23 15 15 23-17c7 6 15 11 24 16l-7 28 19 8 14-25c9 3 18 5 28 6l4 29h21l4-29c10-1 19-3 28-6l14 25 19-8 -7-28c8-5 16-10 24-16l23 17 15-15 -17-23c6-7 11-15 16-24l28 7 8-19 -25-14c3-9 5-18 6-28L645 194zM471 294c-61 0-110-49-110-110S411 74 471 74s110 49 110 110S532 294 471 294z"/>
                  </g>
                  <g>
                    <path x="-136,996" y="-136,996" class="medium-shadow" d="M402 400v-21l-28-4c-1-10-4-19-7-28l23-17 -11-18L352 323c-6-8-13-14-20-20l11-26 -18-11 -17 23c-9-4-18-6-28-7l-4-28h-21l-4 28c-10 1-19 4-28 7l-17-23 -18 11 11 26c-8 6-14 13-20 20l-26-11 -11 18 23 17c-4 9-6 18-7 28l-28 4v21l28 4c1 10 4 19 7 28l-23 17 11 18 26-11c6 8 13 14 20 20l-11 26 18 11 17-23c9 4 18 6 28 7l4 28h21l4-28c10-1 19-4 28-7l17 23 18-11 -11-26c8-6 14-13 20-20l26 11 11-18 -23-17c4-9 6-18 7-28L402 400zM265 463c-41 0-74-33-74-74 0-41 33-74 74-74 41 0 74 33 74 74C338 430 305 463 265 463z"/>
                  </g>
                  <g >
                    <path x="-100,136" y="-100,136" class="small-shadow" d="M210 246v-21l-29-4c-2-10-6-18-11-26l18-23 -15-15 -23 18c-8-5-17-9-26-11l-4-29H100l-4 29c-10 2-18 6-26 11l-23-18 -15 15 18 23c-5 8-9 17-11 26L10 225v21l29 4c2 10 6 18 11 26l-18 23 15 15 23-18c8 5 17 9 26 11l4 29h21l4-29c10-2 18-6 26-11l23 18 15-15 -18-23c5-8 9-17 11-26L210 246zM110 272c-20 0-37-17-37-37s17-37 37-37c20 0 37 17 37 37S131 272 110 272z"/>
                  </g>
                  <g>
                    <path x="-100,136" y="-100,136" class="small" d="M200 236v-21l-29-4c-2-10-6-18-11-26l18-23 -15-15 -23 18c-8-5-17-9-26-11l-4-29H90l-4 29c-10 2-18 6-26 11l-23-18 -15 15 18 23c-5 8-9 17-11 26L0 215v21l29 4c2 10 6 18 11 26l-18 23 15 15 23-18c8 5 17 9 26 11l4 29h21l4-29c10-2 18-6 26-11l23 18 15-15 -18-23c5-8 9-17 11-26L200 236zM100 262c-20 0-37-17-37-37s17-37 37-37c20 0 37 17 37 37S121 262 100 262z"/>
                  </g>
                  <g>
                    <path x="-173,694" y="-173,694" class="large" d="M635 184v-21l-29-4c-1-10-3-19-6-28l25-14 -8-19 -28 7c-5-8-10-16-16-24L592 58l-15-15 -23 17c-7-6-15-11-24-16l7-28 -19-8 -14 25c-9-3-18-5-28-6L472 0h-21l-4 29c-10 1-19 3-28 6L405 9l-19 8 7 28c-8 5-16 10-24 16l-23-17L331 58l17 23c-6 7-11 15-16 24l-28-7 -8 19 25 14c-3 9-5 18-6 28l-29 4v21l29 4c1 10 3 19 6 28l-25 14 8 19 28-7c5 8 10 16 16 24l-17 23 15 15 23-17c7 6 15 11 24 16l-7 28 19 8 14-25c9 3 18 5 28 6l4 29h21l4-29c10-1 19-3 28-6l14 25 19-8 -7-28c8-5 16-10 24-16l23 17 15-15 -17-23c6-7 11-15 16-24l28 7 8-19 -25-14c3-9 5-18 6-28L635 184zM461 284c-61 0-110-49-110-110S401 64 461 64s110 49 110 110S522 284 461 284z"/>
                  </g>
                  <g>
                    <path x="-136,996" y="-136,996" class="medium" d="M392 390v-21l-28-4c-1-10-4-19-7-28l23-17 -11-18L342 313c-6-8-13-14-20-20l11-26 -18-11 -17 23c-9-4-18-6-28-7l-4-28h-21l-4 28c-10 1-19 4-28 7l-17-23 -18 11 11 26c-8 6-14 13-20 20l-26-11 -11 18 23 17c-4 9-6 18-7 28l-28 4v21l28 4c1 10 4 19 7 28l-23 17 11 18 26-11c6 8 13 14 20 20l-11 26 18 11 17-23c9 4 18 6 28 7l4 28h21l4-28c10-1 19-4 28-7l17 23 18-11 -11-26c8-6 14-13 20-20l26 11 11-18 -23-17c4-9 6-18 7-28L392 390zM255 453c-41 0-74-33-74-74 0-41 33-74 74-74 41 0 74 33 74 74C328 420 295 453 255 453z"/>
                  </g>
                </svg>

                <a>MICROSERVICES</a>
                
                <svg class="machine" xmlns="http://www.w3.org/2000/svg" x="0px" y="0px" viewBox="0 0 645 526">
                  <defs/>
                  <g>
                    <path  x="-173,694" y="-173,694" class="large-shadow" d="M645 194v-21l-29-4c-1-10-3-19-6-28l25-14 -8-19 -28 7c-5-8-10-16-16-24L602 68l-15-15 -23 17c-7-6-15-11-24-16l7-28 -19-8 -14 25c-9-3-18-5-28-6L482 10h-21l-4 29c-10 1-19 3-28 6l-14-25 -19 8 7 28c-8 5-16 10-24 16l-23-17L341 68l17 23c-6 7-11 15-16 24l-28-7 -8 19 25 14c-3 9-5 18-6 28l-29 4v21l29 4c1 10 3 19 6 28l-25 14 8 19 28-7c5 8 10 16 16 24l-17 23 15 15 23-17c7 6 15 11 24 16l-7 28 19 8 14-25c9 3 18 5 28 6l4 29h21l4-29c10-1 19-3 28-6l14 25 19-8 -7-28c8-5 16-10 24-16l23 17 15-15 -17-23c6-7 11-15 16-24l28 7 8-19 -25-14c3-9 5-18 6-28L645 194zM471 294c-61 0-110-49-110-110S411 74 471 74s110 49 110 110S532 294 471 294z"/>
                  </g>
                  <g>
                    <path x="-136,996" y="-136,996" class="medium-shadow" d="M402 400v-21l-28-4c-1-10-4-19-7-28l23-17 -11-18L352 323c-6-8-13-14-20-20l11-26 -18-11 -17 23c-9-4-18-6-28-7l-4-28h-21l-4 28c-10 1-19 4-28 7l-17-23 -18 11 11 26c-8 6-14 13-20 20l-26-11 -11 18 23 17c-4 9-6 18-7 28l-28 4v21l28 4c1 10 4 19 7 28l-23 17 11 18 26-11c6 8 13 14 20 20l-11 26 18 11 17-23c9 4 18 6 28 7l4 28h21l4-28c10-1 19-4 28-7l17 23 18-11 -11-26c8-6 14-13 20-20l26 11 11-18 -23-17c4-9 6-18 7-28L402 400zM265 463c-41 0-74-33-74-74 0-41 33-74 74-74 41 0 74 33 74 74C338 430 305 463 265 463z"/>
                  </g>
                  <g >
                    <path x="-100,136" y="-100,136" class="small-shadow" d="M210 246v-21l-29-4c-2-10-6-18-11-26l18-23 -15-15 -23 18c-8-5-17-9-26-11l-4-29H100l-4 29c-10 2-18 6-26 11l-23-18 -15 15 18 23c-5 8-9 17-11 26L10 225v21l29 4c2 10 6 18 11 26l-18 23 15 15 23-18c8 5 17 9 26 11l4 29h21l4-29c10-2 18-6 26-11l23 18 15-15 -18-23c5-8 9-17 11-26L210 246zM110 272c-20 0-37-17-37-37s17-37 37-37c20 0 37 17 37 37S131 272 110 272z"/>
                  </g>
                  <g>
                    <path x="-100,136" y="-100,136" class="small" d="M200 236v-21l-29-4c-2-10-6-18-11-26l18-23 -15-15 -23 18c-8-5-17-9-26-11l-4-29H90l-4 29c-10 2-18 6-26 11l-23-18 -15 15 18 23c-5 8-9 17-11 26L0 215v21l29 4c2 10 6 18 11 26l-18 23 15 15 23-18c8 5 17 9 26 11l4 29h21l4-29c10-2 18-6 26-11l23 18 15-15 -18-23c5-8 9-17 11-26L200 236zM100 262c-20 0-37-17-37-37s17-37 37-37c20 0 37 17 37 37S121 262 100 262z"/>
                  </g>
                  <g>
                    <path x="-173,694" y="-173,694" class="large" d="M635 184v-21l-29-4c-1-10-3-19-6-28l25-14 -8-19 -28 7c-5-8-10-16-16-24L592 58l-15-15 -23 17c-7-6-15-11-24-16l7-28 -19-8 -14 25c-9-3-18-5-28-6L472 0h-21l-4 29c-10 1-19 3-28 6L405 9l-19 8 7 28c-8 5-16 10-24 16l-23-17L331 58l17 23c-6 7-11 15-16 24l-28-7 -8 19 25 14c-3 9-5 18-6 28l-29 4v21l29 4c1 10 3 19 6 28l-25 14 8 19 28-7c5 8 10 16 16 24l-17 23 15 15 23-17c7 6 15 11 24 16l-7 28 19 8 14-25c9 3 18 5 28 6l4 29h21l4-29c10-1 19-3 28-6l14 25 19-8 -7-28c8-5 16-10 24-16l23 17 15-15 -17-23c6-7 11-15 16-24l28 7 8-19 -25-14c3-9 5-18 6-28L635 184zM461 284c-61 0-110-49-110-110S401 64 461 64s110 49 110 110S522 284 461 284z"/>
                  </g>
                  <g>
                    <path x="-136,996" y="-136,996" class="medium" d="M392 390v-21l-28-4c-1-10-4-19-7-28l23-17 -11-18L342 313c-6-8-13-14-20-20l11-26 -18-11 -17 23c-9-4-18-6-28-7l-4-28h-21l-4 28c-10 1-19 4-28 7l-17-23 -18 11 11 26c-8 6-14 13-20 20l-26-11 -11 18 23 17c-4 9-6 18-7 28l-28 4v21l28 4c1 10 4 19 7 28l-23 17 11 18 26-11c6 8 13 14 20 20l-11 26 18 11 17-23c9 4 18 6 28 7l4 28h21l4-28c10-1 19-4 28-7l17 23 18-11 -11-26c8-6 14-13 20-20l26 11 11-18 -23-17c4-9 6-18 7-28L392 390zM255 453c-41 0-74-33-74-74 0-41 33-74 74-74 41 0 74 33 74 74C328 420 295 453 255 453z"/>
                  </g>
                </svg>

                <br/>
            </h1>
            <a :class="{ sideButton: true, left: true, active: this.side === 'driver' }" @click="changeSide('driver')" value="driver">Drv</a>
            <a :class="{ sideButton: true, center: true, active: this.side === 'team' }" @click="changeSide('team')" value="team">Tm</a>
            <a :class="{ sideButton: true, right: true, active: this.side === 'category' }" @click="changeSide('category')" value="category">Cat</a>
            
            <h2 class="description">SELECT ONE OPTION</h2>
            <nav class="demo-buttons">
                <span v-for="(menu, index) in menus" :key="index">
                    <span>
                        <a :class="currentMenu === menu.buttonText.replace(/ +/g, '').toLowerCase() ? {currentDemo:true}: {currentDemo:false}" @click="changeMenu(menu.buttonText)">
                            {{menu.buttonText}}
                        </a>
                    </span>
                </span>
            </nav>
            
            <textarea id="inputText" class="textarea-style" placeholder="Insert parameters"></textarea>
            <div>
              <a class="send-button" @click="isOpen = !isOpen, sendMessage();"> {{ isOpen ? "CLOSE MODAL" : "SEND" }}</a>
            </div>

            <transition name="modal">
              <div v-if="isOpen">
                <div class="overlay" @click.self="isOpen = false;">
                  <div class="modal">
                    <h1><a>DDBB</a></h1>
                    <a id="showData"></a>
                  </div>
                </div>
              </div>
            </transition>
        </main>
    </div>
</template>

<script src="https://cdn.jsdelivr.net/vue.resource/1.3.1/vue-resource.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/vue@2.5.16/dist/vue.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/vue/2.5.17/vue.js"></script>

<script type="text/javascript" src="StyleKitName.js"></script>
  <script>
    var offset = 0.0;
    function draw() { 
      StyleKitName.clearCanvas('gears');
      StyleKitName.drawGears('gears', offset);
    }
    var tid = setInterval(loop, 25);
    var canvas = document.getElementById("gears");
    var context = canvas.getContext("2d");
    function loop() {
      offset += 1;
      draw();
    }
  </script>

<script>



  var side = "";
  var requestMessage = "";
  var requestVariable = "";
  var json;
    export default {
      data() {
        return {
          isOpen: false,
          menus: {
            getOne: { buttonText: 'Select One' },
            getAll: { buttonText: 'Select All' },
            create: { buttonText: 'Create' },
            update: { buttonText: 'Update' },
            delete: { buttonText: 'Delete' },
          },
          side: 'driver',
          currentMenu: ''
        };
      },
      methods: {
        changeMenu(menu) {
          this.currentMenu = menu.replace(/ +/g, '').toLowerCase();
          console.log(this.currentMenu);
          switch(this.currentMenu){
            case 'selectone':
              this.requestMessage = this.currentMenu;
              this.requestVariable = document.getElementById("inputText").value;
              this.requestMessage = "http://localhost:8080/" + this.side + "/read?id=" + this.requestVariable;
              document.getElementById("inputText").value = this.requestMessage;
              console.log("text value : " + document.getElementById("inputText").value);
              console.log("request value : " + this.requestMessage);
              break;
            case 'selectall':
              this.requestMessage = this.currentMenu;
              console.log("this.requestMessage : " + "/" + this.side + "/readAll");
              this.requestMessage = "http://localhost:8080/" + this.side + "/readAll";
              document.getElementById("inputText").value = this.requestMessage;
              console.log("this.side : " + this.side);
              break;
            case 'create':
              this.requestMessage = this.currentMenu;
              this.requestMessage = "http://localhost:8080/" + this.side + "/create";
              console.log("this.requestMessage : " + "/" + this.side + "/create");
              console.log("this.side : " + this.side);
              break;
            case 'delete':
              this.requestMessage = this.currentMenu;
              this.requestVariable = document.getElementById("inputText").value;
              this.requestMessage = "http://localhost:8080/" + this.side + "/delete?id=" + this.requestVariable;
              document.getElementById("inputText").value = this.requestMessage;
              console.log("this.requestMessage : " + "/" + this.side + "/delete");
              console.log("this.side : " + this.side);
              break;
            case 'update':
              this.requestMessage = this.currentMenu;
              this.requestMessage = "http://localhost:8080/" + this.side + "/update";
              console.log("this.requestMessage : " + "/" + this.side + "/update");
              console.log("this.side : " + this.side);
              break;
          }
          this.requestMessage = "";
         
          return this.currentMenu;
        },
        changeSide(side) {
          this.side = side;
          console.log(this.side);
        },
        sendMessage(){
          console.log("Message sended: " + document.getElementById("inputText").value);
          //Access-Control-Allow-Headers: Origin, X-Auth-Token
          this.$http.get(document.getElementById("inputText").value, {headers: 'Content-Type: Application/json'},{emulateJSON: true})
          .then((response) => {
            console.log(response);
            this.json = response.body;
            CreateTableFromJSON(this.json);
          })
          .catch(err => console.log('Error: ' + err));
          }
        }
      
      };
      

</script>

 <style lang="less">
 
    *,
    *:after,
    *:before {
      -webkit-box-sizing: border-box;
      box-sizing: border-box;
    }

    table{
      width: -webkit-fill-available;
    }

    html {
      height: 100%;
    }

    body {
      height: 100%;
      color: #fffce1;
      font-family: 'Raleway', Arial, sans-serif;
      margin: 0px;
    }

    #app {
      height: 100%;
    }

    a {
      color: #4e4a46;
      text-decoration: none;

      &:hover,
      &:focus {
        color: #c94e50;
      }
    }

    main {
      height: 100%;
      padding: 3em 2em;
      text-align: center;
      background: #b4bad2;
      overflow: auto;
    }

    h1 {
      font-weight: 800;
      font-size: 3.75em;
    }

    .description {
      max-width: 20em;
      margin: 1.2em auto 1em;
      line-height: 1.3em;
      font-weight: 400;
    }

    .demo-buttons {
      font-size: 1em;
      max-width: 1200px;
      margin: 2em auto 3em;
      padding: 0 10em;

      a {
        display: inline-block;
        margin: 0.75em;
        padding: 1.35em 1.1em;
        width: 15em;
        background: #fffce1;
        text-transform: uppercase;
        letter-spacing: 1px;
        font-weight: 800;
        border-top-left-radius: 20px 50px;
        border-top-right-radius: 20px 50px;
        border-bottom-right-radius: 20px 50px;
        border-bottom-left-radius: 20px 50px;
        cursor: pointer;

        &.currentDemo {
          background: #c94e50;
          color: #fffce1;
        }
      }
    }

    .send-button{
      font-size: 1em;
      max-width: 1200px;
      margin: 2em auto 3em;
      padding: 0 10em;
      display: inline-block;

        margin: 0.75em;
        padding: 1.35em 1.1em;
        width: 15em;
        background: #fffce1;
        text-transform: uppercase;
        letter-spacing: 1px;
        font-weight: 800;
        border-top-left-radius: 20px 50px;
        border-top-right-radius: 20px 50px;
        border-bottom-right-radius: 20px 50px;
        border-bottom-left-radius: 20px 50px;
        cursor: pointer;
        
        &:active {
          background-color: #c94e50;
          cursor: pointer;
          cursor: hand;
          color: #fffce1;
        }

    }

    .textarea-style{
       display: inline-block;
      width: 80em;
      height: 20em;
      line-height: 2.5em;
      cursor: pointer;
      background: #fffce1;
      letter-spacing: 1px;
      font-size: 0.8em;
      font-weight: 800;
    }

    .sideButton {
      display: inline-block;
      width: 5em;
      height: 2.5em;
      line-height: 2.5em;
      cursor: pointer;
      background: #fffce1;
      text-transform: uppercase;
      letter-spacing: 1px;
      font-size: 0.8em;
      font-weight: 800;

      &.left {
        border-top-left-radius: 10px;
        border-bottom-left-radius: 10px;
      }

      &.right {
        border-top-right-radius: 10px;
        border-bottom-right-radius: 10px;
      }

      &.active {
        background: #c94e50;
        color: #fffce1;
      }
    }

    @media screen and (max-width: 40em) {
      main {
        font-size: 80%;
      }

      h1 {
        padding-top: 1em;
        font-size: 2.5em;
      }

      .demo-buttons {
        max-width: 900px;
        padding: 0 2em;
      }
    }

    //
    // Burger menu custom styles
    //
    .bm-burger-button {
      position: absolute;
      width: 36px;
      height: 30px;
      left: 36px;
      top: 36px;
    }

    .right .bm-burger-button {
      left: initial;
      right: 36px;
    }

    .bm-burger-bars {
      background: #373a47;
    }

    .bm-morph-shape {
      fill: #373a47;
    }

    .bm-menu {
      background: #373a47;

      a {
        color: #b8b7ad;

        &:hover,
        &:focus {
          color: #c94e50;
        }
      }
    }

    //
    // Mixins
    //
    .menu-1 {
      .bm-cross {
        background: #bdc3c7;
      }

      .bm-menu {
        padding: 2.5em 1.5em 0;
        font-size: 1.15em;
      }
    }

    .menu-2 {
      .bm-cross {
        background: #999;
      }

      .bm-menu {
        padding: 3.4em 1em 0;
      }

      a {
        padding: 1em;
      }

      i {
        font-size: 1.7em;
        vertical-align: middle;
        color: #282a35;
      }
    }

    .menu-3 {
      .bm-cross {
        background: #888;
      }

      .bm-menu {
        padding: 2em 1em;
        font-size: 1.15em;
      }

      i {
        opacity: 0.5;
      }

      span {
        text-transform: uppercase;
        letter-spacing: 1px;
        font-size: 0.75em;
      }
    }

    .menu-4 {
      .bm-cross {
        background: #888;
      }

      h2 {
        margin: 0 auto;
        padding: 2em 1em;
        color: rgba(0, 0, 0, 0.4);
        box-shadow: inset 0 -1px rgba(0, 0, 0, 0.2);

        i {
          margin-left: 0.2em;
        }

        span {
          font-size: 1.6em;
          font-weight: 700;
        }
      }

      a {
        padding: 1em;
        text-transform: uppercase;
        transition: background 0.3s, box-shadow 0.3s;
        box-shadow: inset 0 -1px rgba(0, 0, 0, 0.2);

        span {
          letter-spacing: 1px;
          font-weight: 400;
        }

        &:hover,
        &:focus {
          background: rgba(0, 0, 0, 0.2);
          box-shadow: inset 0 -1px rgba(0, 0, 0, 0);
          color: #b8b7ad;
        }
      }
    }

    .modal {
      width: 500px;
      margin: 0px auto;
      padding: 20px;
      background-color: #A4A3A3;
      border-radius: 2px;
      box-shadow: 0 2px 8px 3px;
      transition: all 0.2s ease-in;
      font-family: Helvetica, Arial, sans-serif;
    }
    .fadeIn-enter {
      opacity: 0;
    }

    .fadeIn-leave-active {
      opacity: 0;
      transition: all 0.2s step-end;
    }

    .fadeIn-enter .modal,
    .fadeIn-leave-active.modal {
      transform: scale(1.1);
    }

    .overlay {
      position: fixed;
      top: 0;
      left: 0;
      display: flex;
      justify-content: center;
      align-items: center;
      width: 100%;
      height: 100%;
      background: #00000094;
      z-index: 999;
      transition: opacity 0.2s ease;
    }

    body, html {
  width: 100%;
  height: 100%;
  background-color: #ffffff; }

    .container {
      display: -webkit-box;
      display: -webkit-flex;
      display: -ms-flexbox;
      display: flex;
      -webkit-box-pack: center;
      -webkit-justify-content: center;
          -ms-flex-pack: center;
              justify-content: center;
      -webkit-box-align: center;
      -webkit-align-items: center;
          -ms-flex-align: center;
              align-items: center; }

    .machine {
      width: 10vmin;
      fill: #4e4a46; }

    .small-shadow, .medium-shadow, .large-shadow {
      fill: rgba(0, 0, 0, 0.05); }

    .small {
      -webkit-animation: counter-rotation 2.5s infinite linear;
        -moz-animation: counter-rotation 2.5s infinite linear;
          -o-animation: counter-rotation 2.5s infinite linear;
              animation: counter-rotation 2.5s infinite linear;
      -webkit-transform-origin: 100.136px 225.345px;
          -ms-transform-origin: 100.136px 225.345px;
              transform-origin: 100.136px 225.345px; }

    .small-shadow {
      -webkit-animation: counter-rotation 2.5s infinite linear;
        -moz-animation: counter-rotation 2.5s infinite linear;
          -o-animation: counter-rotation 2.5s infinite linear;
              animation: counter-rotation 2.5s infinite linear;
      -webkit-transform-origin: 110.136px 235.345px;
          -ms-transform-origin: 110.136px 235.345px;
              transform-origin: 110.136px 235.345px; }

    .medium {
      -webkit-animation: rotation 3.75s infinite linear;
        -moz-animation: rotation 3.75s infinite linear;
          -o-animation: rotation 3.75s infinite linear;
              animation: rotation 3.75s infinite linear;
      -webkit-transform-origin: 254.675px 379.447px;
          -ms-transform-origin: 254.675px 379.447px;
              transform-origin: 254.675px 379.447px; }

    .medium-shadow {
      -webkit-animation: rotation 3.75s infinite linear;
        -moz-animation: rotation 3.75s infinite linear;
          -o-animation: rotation 3.75s infinite linear;
              animation: rotation 3.75s infinite linear;
      -webkit-transform-origin: 264.675px 389.447px;
          -ms-transform-origin: 264.675px 389.447px;
              transform-origin: 264.675px 389.447px; }

    .large {
      -webkit-animation: counter-rotation 5s infinite linear;
        -moz-animation: counter-rotation 5s infinite linear;
          -o-animation: counter-rotation 5s infinite linear;
              animation: counter-rotation 5s infinite linear;
      -webkit-transform-origin: 461.37px 173.694px;
          -ms-transform-origin: 461.37px 173.694px;
              transform-origin: 461.37px 173.694px; }

    .large-shadow {  
      -webkit-animation: counter-rotation 5s infinite linear;
        -moz-animation: counter-rotation 5s infinite linear;
          -o-animation: counter-rotation 5s infinite linear;
              animation: counter-rotation 5s infinite linear;
      -webkit-transform-origin: 471.37px 183.694px;
          -ms-transform-origin: 471.37px 183.694px;
              transform-origin: 471.37px 183.694px; }

    @-webkit-keyframes rotation {
        from {-webkit-transform: rotate(0deg);}
        to   {-webkit-transform: rotate(359deg);}
    }
    @-moz-keyframes rotation {
        from {-moz-transform: rotate(0deg);}
        to   {-moz-transform: rotate(359deg);}
    }
    @-o-keyframes rotation {
        from {-o-transform: rotate(0deg);}
        to   {-o-transform: rotate(359deg);}
    }
    @keyframes rotation {
        from {transform: rotate(0deg);}
        to   {transform: rotate(359deg);}
    }

    @-webkit-keyframes counter-rotation {
        from {-webkit-transform: rotate(359deg);}
        to   {-webkit-transform: rotate(0deg);}
    }
    @-moz-keyframes counter-rotation {
        from {-moz-transform: rotate(359deg);}
        to   {-moz-transform: rotate(0deg);}
    }
    @-o-keyframes counter-rotation {
        from {-o-transform: rotate(359deg);}
        to   {-o-transform: rotate(0deg);}
    }
    @keyframes counter-rotation {
        from {transform: rotate(359deg);}
        to   {transform: rotate(0deg);}
    }

</style>
