<script setup>
import {ref} from "vue"; 

const header = ["A", "B", "C", "D", "E", "F", "G", "H", "I", "J", "K", "L", "M", "N", "O"];
const points1 = ["5", "3", "3", "3", "2", "2", "2", "1", "2", "2", "2", "3", "3", "3", "5"];
const points2 = ["3", "2", "2", "2", "1", "1", "1", "0", "1", "1", "1", "2", "2", "2", "3"];
const field = [
  [{
    id: 0,
    value: "",
    color: "--g",
    isClicked: ref("false"),
  },
  {
    id: 1,
    value: "",
    color: "--g",
    isClicked: ref("false"),
  },
  {
    id: 2,
    value: "",
    color: "--g",
    isClicked: ref("false"),
  },
  {
    id: 3,
    value: "",
    color: "--y",
    isClicked: ref("false"),
  },
  {
    id: 4,
    value: "",
    color: "--y",
    isClicked: ref("false"),
  },
  {
    id: 5,
    value: "",
    color: "--y",
    isClicked: ref("false"),
  },
  {
    id: 6,
    value: "",
    color: "--y",
    isClicked: ref("false"),
  },
  {
    id: 7,
    value: "",
    color: "--g",
    isClicked: ref("false"),
  },
  {
    id: 8,
    value: "*",
    color: "--b",
    isClicked: ref("false"),
  },
  {
    id: 9,
    value: "",
    color: "--b",
    isClicked: ref("false"),
  },
  {
    id: 10,
    value: "",
    color: "--b",
    isClicked: ref("false"),
  },
  {
    id: 11,
    value: "*",
    color: "--o",
    isClicked: ref("false"),
  },
  {
    id: 12,
    value: "",
    color: "--y",
    isClicked: ref("false"),
  },
  {
    id: 13,
    value: "",
    color: "--y",
    isClicked: ref("false"),
  },
  {
    id: 13,
    value: "",
    color: "--y",
    isClicked: ref("false"),
  }],
  [
  {
    id: 14,
    value: "",
    color: "--o",
    isClicked: ref("false"),
  },
  {
    id: 15,
    value: "",
    color: "--g",
    isClicked: ref("false"),
  },
  {
    id: 16,
    value: "*",
    color: "--y",
    isClicked: ref("false"),
  },
  {
    id: 17,
    value: "",
    color: "--g",
    isClicked: ref("false"),
  },
  {
    id: 18,
    value: "*",
    color: "--y",
    isClicked: ref("false"),
  },
  {
    id: 19,
    value: "",
    color: "--y",
    isClicked: ref("false"),
  },
  {
    id: 20,
    value: "",
    color: "--o",
    isClicked: ref("false"),
  },
  {
    id: 21,
    value: "",
    color: "--o",
    isClicked: ref("false"),
  },
  {
    id: 22,
    value: "",
    color: "--r",
    isClicked: ref("false"),
  },
  {
    id: 23,
    value: "*",
    color: "--b",
    isClicked: ref("false"),
  },
  {
    id: 24,
    value: "",
    color: "--b",
    isClicked: ref("false"),
  },
  {
    id: 25,
    value: "",
    color: "--o",
    isClicked: ref("false"),
  },
  {
    id: 26,
    value: "",
    color: "--o",
    isClicked: ref("false"),
  },
  {
    id: 27,
    value: "",
    color: "--g",
    isClicked: ref("false"),
  },
  {
    id: 28,
    value: "",
    color: "--g",
    isClicked: ref("false"),
  }
  ],
  [
  {
    id: 29,
    value: "*",
    color: "--b",
    isClicked: ref("false"),
  },
  {
    id: 30,
    value: "",
    color: "--g",
    isClicked: ref("false"),
  },
  {
    id: 31,
    value: "",
    color: "--r",
    isClicked: ref("false"),
  },
  {
    id: 32,
    value: "",
    color: "--g",
    isClicked: ref("false"),
  },
  {
    id: 33,
    value: "",
    color: "--g",
    isClicked: ref("false"),
  },
  {
    id: 34,
    value: "",
    color: "--g",
    isClicked: ref("false"),
  },
  {
    id: 35,
    value: "*",
    color: "--g",
    isClicked: ref("false"),
  },
  {
    id: 36,
    value: "",
    color: "--r",
    isClicked: ref("false"),
  },
  {
    id: 37,
    value: "",
    color: "--r",
    isClicked: ref("false"),
  },
  {
    id: 38,
    value: "",
    color: "--r",
    isClicked: ref("false"),
  },
  {
    id: 39,
    value: "",
    color: "--y",
    isClicked: ref("false"),
  },
  {
    id: 40,
    value: "",
    color: "--y",
    isClicked: ref("false"),
  },
  {
    id: 41,
    value: "",
    color: "--o",
    isClicked: ref("false"),
  },
  {
    id: 42,
    value: "",
    color: "--g",
    isClicked: ref("false"),
  },
  {
    id: 43,
    value: "",
    color: "--g",
    isClicked: ref("false"),
  }
  ],
  [
  {
    id: 44,
    value: "",
    color: "--b",
    isClicked: ref("false"),
  },
  {
    id: 45,
    value: "",
    color: "--r",
    isClicked: ref("false"),
  },
  {
    id: 46,
    value: "",
    color: "--r",
    isClicked: ref("false"),
  },
  {
    id: 47,
    value: "",
    color: "--g",
    isClicked: ref("false"),
  },
  {
    id: 48,
    value: "",
    color: "--o",
    isClicked: ref("false"),
  },
  {
    id: 49,
    value: "*",
    color: "--o",
    isClicked: ref("false"),
  },
  {
    id: 50,
    value: "",
    color: "--b",
    isClicked: ref("false"),
  },
  {
    id: 51,
    value: "",
    color: "--b",
    isClicked: ref("false"),
  },
  {
    id: 52,
    value: "",
    color: "--g",
    isClicked: ref("false"),
  },
  {
    id: 53,
    value: "",
    color: "--g",
    isClicked: ref("false"),
  },
  {
    id: 54,
    value: "",
    color: "--y",
    isClicked: ref("false"),
  },
  {
    id: 55,
    value: "",
    color: "--y",
    isClicked: ref("false"),
  },
  {
    id: 56,
    value: "",
    color: "--o",
    isClicked: ref("false"),
  },
  {
    id: 57,
    value: "*",
    color: "--r",
    isClicked: ref("false"),
  },
  {
    id: 58,
    value: "",
    color: "--b",
    isClicked: ref("false"),
  }
  ],
  [
  {
    id: 59,
    value: "",
    color: "--r",
    isClicked: ref("false"),
  },
  {
    id: 60,
    value: "",
    color: "--o",
    isClicked: ref("false"),
  },
  {
    id: 61,
    value: "",
    color: "--o",
    isClicked: ref("false"),
  },
  {
    id: 62,
    value: "",
    color: "--o",
    isClicked: ref("false"),
  },
  {
    id: 63,
    value: "",
    color: "--o",
    isClicked: ref("false"),
  },
  {
    id: 64,
    value: "",
    color: "--r",
    isClicked: ref("false"),
  },
  {
    id: 65,
    value: "",
    color: "--b",
    isClicked: ref("false"),
  },
  {
    id: 66,
    value: "",
    color: "--b",
    isClicked: ref("false"),
  },
  {
    id: 67,
    value: "",
    color: "--o",
    isClicked: ref("false"),
  },
  {
    id: 68,
    value: "",
    color: "--o",
    isClicked: ref("false"),
  },
  {
    id: 69,
    value: "",
    color: "--o",
    isClicked: ref("false"),
  },
  {
    id: 70,
    value: "",
    color: "--r",
    isClicked: ref("false"),
  },
  {
    id: 71,
    value: "",
    color: "--r",
    isClicked: ref("false"),
  },
  {
    id: 72,
    value: "",
    color: "--r",
    isClicked: ref("false"),
  },
  {
    id: 73,
    value: "",
    color: "--r",
    isClicked: ref("false"),
  }
  ],
  [
  {
    id: 74,
    value: "",
    color: "--r",
    isClicked: ref("false"),
  },
  {
    id: 75,
    value: "*",
    color: "--b",
    isClicked: ref("false"),
  },
  {
    id: 76,
    value: "",
    color: "--b",
    isClicked: ref("false"),
  },
  {
    id: 77,
    value: "*",
    color: "--r",
    isClicked: ref("false"),
  },
  {
    id: 78,
    value: "",
    color: "--r",
    isClicked: ref("false"),
  },
  {
    id: 79,
    value: "",
    color: "--r",
    isClicked: ref("false"),
  },
  {
    id: 80,
    value: "",
    color: "--r",
    isClicked: ref("false"),
  },
  {
    id: 81,
    value: "",
    color: "--y",
    isClicked: ref("false"),
  },
  {
    id: 82,
    value: "",
    color: "--y",
    isClicked: ref("false"),
  },
  {
    id: 83,
    value: "",
    color: "--o",
    isClicked: ref("false"),
  },
  {
    id: 84,
    value: "*",
    color: "--r",
    isClicked: ref("false"),
  },
  {
    id: 85,
    value: "",
    color: "--b",
    isClicked: ref("false"),
  },
  {
    id: 86,
    value: "",
    color: "--b",
    isClicked: ref("false"),
  },
  {
    id: 87,
    value: "",
    color: "--b",
    isClicked: ref("false"),
  },
  {
    id: 88,
    value: "*",
    color: "--o",
    isClicked: ref("false"),
  }
  ],
  [
  {
    id: 89,
    value: "",
    color: "--o",
    isClicked: ref("false"),
  },
  {
    id: 90,
    value: "",
    color: "--o",
    isClicked: ref("false"),
  },
  {
    id: 91,
    value: "",
    color: "--b",
    isClicked: ref("false"),
  },
  {
    id: 92,
    value: "",
    color: "--b",
    isClicked: ref("false"),
  },
  {
    id: 93,
    value: "",
    color: "--b",
    isClicked: ref("false"),
  },
  {
    id: 94,
    value: "",
    color: "--b",
    isClicked: ref("false"),
  },
  {
    id: 95,
    value: "",
    color: "--r",
    isClicked: ref("false"),
  },
  {
    id: 96,
    value: "",
    color: "--y",
    isClicked: ref("false"),
  },
  {
    id: 97,
    value: "",
    color: "--y",
    isClicked: ref("false"),
  },
  {
    id: 98,
    value: "",
    color: "--y",
    isClicked: ref("false"),
  },
  {
    id: 99,
    value: "",
    color: "--g",
    isClicked: ref("false"),
  },
  {
    id: 100,
    value: "",
    color: "--g",
    isClicked: ref("false"),
  },
  {
    id: 101,
    value: "*",
    color: "--g",
    isClicked: ref("false"),
  },
  {
    id: 102,
    value: "",
    color: "--o",
    isClicked: ref("false"),
  },
  {
    id: 103,
    value: "",
    color: "--o",
    isClicked: ref("false"),
  }
  ]
  
  
];

console.log(field);

const toggleClick = (e) => {

  const clickedId = e.target.id;
  console.log("id: " + clickedId);

  // search clickedId in field
  for(let i = 0; i < 1; i++){
    for(let y = 0; y < field[i].length; y++){
      if(field[i][y].id == clickedId){
        console.log("gelijk");
        field[i][y].isClicked = true;
        console.log(field[i][y]);
      }
    }
  }



}

</script>

<template>
  <div class="container">
    <h1>Noch Mal</h1>
    <div class="playgrid">
      <div class="row r-header">
          <div v-for="val in header" class="dice">
              <button type="button" class="btn" disabled>{{val}}</button>
          </div>
      </div>

      <div v-for="row in field" class="play">
        <div class="row r-field">
          <div v-for="val in row" class="dice" :class="val.color">
              <button type="button" class="btn" 
                :id="val.id"
                :class="[val.isClicked.value == true ? 'active' : 'nope']"
                @click="toggleClick($event)">
                {{val.value}}
                <!--{{ val.isClicked.value }}-->
                <span class="field-btn__checkbox" ></span>
              </button>

          </div>
        </div>
      </div>

      <div class="row r-footer">
        <div v-for="val in points1" class="dice">
            <button type="button" class="btn">{{val}}</button>
        </div>
      </div>

      <div class="row r-footer r-15">
        <div v-for="val in points2" class="dice">
            <button type="button" class="btn">{{val}}</button>
        </div>
      </div>


    </div>
  </div>
</template>


<style scoped>
  :root {
    --g: green;
    --y: yellow;
    --b: blue;
    --o: orange;
    --r: red; 
  }
  body {
    background-color: #fff;
  }
  .container {
    padding: 10px;
    margin: 0 auto;
    width: 100vw;
    max-width: 1200px;
  }
  h1 {
    font-weight: bold;
    margin-bottom: 25px;
    font-size: 75px;
  }
  .playgrid {
    display: flex;
    flex-direction: column;
  }
  .row {
    display: flex;
    flex-direction: row;
  }
  
  button {
    border: none;
    padding: 10px;
    width: 50px;
    height: 50px;
    cursor: pointer;
    background-color: #fff;
    color: black;
    font-size: 20px;
    border: 1px solid black;
  }
  .active .field-btn__checkbox:before {
    position: absolute;
    content: "\2714";
    color: black;
    color: var(--pink);
    font: 20px "Caveat Brush", cursive;
  }


  .active {
    background-color: rgb(255,255,255, 0.5);
  }
  .active .field-btn__checkbox:before {
    position: absolute;
    content: "\2714";
    color: black;
    color: var(--pink);
    font: 20px "Caveat Brush", cursive;
  } 
  .card {
    display: inline-block;
    background: green;
    text-align: center;
    height: 300px;
  }


  .r-field button {
    font-size: 35px;
  }
  .--g > button {
    background-color: green;
  }
  .--y > button {
    background-color: yellow;
  }
  .--b > button {
    background-color: blue;
  }
  .--o > button {
    background-color: orange;
  }
  .--r > button {
    background-color: red;
  }

  .red {
    background-color: aqua !important;
  }
</style>
