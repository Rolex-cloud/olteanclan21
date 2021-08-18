<element onclick="functionToExecute()">Click</element>
<button onclick="functionToExecute()">Click</button>
<div>
  <p class="name">GiftHUb</p>
  <button>Change to Blue</button>
</div>
 body {
   display: flex;
   align-items: center;
   justify-content: center;
   height: 100vh;
      }
p {
   font-size: 2rem;
}

button {
    padding: 7px;
    border: none;
    border-radius: 4px;
    cursor: pointer;
}

button.blue {
    background-color: #3498db;
}

button.green {
    background-color: #2ecc71;
}

button.orange {
   background-color: orangered;
}
<div>
  <p class="name">Gifthub</p>
  <button onclick="changeColor()">Change to Blue</button>
</div>
<script src="path-to-javascript-file"></script>
const name = document.querySelector(".name");
function funcctionName () {
    // What to do
} 
function changeColor() {
    name.style.color = "blue";
}
<div>
      <p class="name">GiftHUb</p>
      <button onclick="changeColor('blue')" class="blue">Blue</button>
      <button onclick="changeColor('green')" class="green">Green</button>
      <button onclick="changeColor('orangered')" class="orange">Orange</button>
</div>
const name = document.querySelector(".name");

function changeColor(color) {
   name.style.color = color;
}
 element.addEventListener("type-of-event", functionToExecute)
  <div>
      <p class="name">Gifthub</p>
      <button>Change Color</button>
 </div>
 const name = document.querySelector(".name");
const btn = document.querySelector("button");

      btn.addEventListener("click", function () {
        name.style.color = "blue";
 });
      btn.addEventListener("click", changeColor);
      function changeColor() {
        name.style.color = "blue";
}
 <article id="content">
      <p> text message </p>
      <p> text message </p>
      <p> text message </p> 
       </article>

<button onclick="showMore()">Show more</button>
<style>
      * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
      }

      body {
        background: #f1f1f1;
        display: flex;
        align-items: center;
        justify-content: center;
        flex-direction: column;
      }

      article {
        width: 400px;
        background: #fff;
        padding: 20px 20px 0;
        font-size: 18px;
        max-height: 270px;
        overflow: hidden;
        transition: max-height 1s;
        text-align: justify;
        margin-top: 20px;
      }

