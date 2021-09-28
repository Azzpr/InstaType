<script>
import json from "rollup-plugin-json";

  // Importing the wordlist 
  // Setting the user variable
  let userInput = "";
  //  Setting user gamemode as default "words" and how many words have been choosen (the default is 10)
  let userGamemode = "words";
  let wordAmount = 10;
  // Generating a random text based on the user parameters
  if ((userGamemode = "words")) {
    console.log("Gamemode: 'words' has been enabled");
    console.log(wordList)
    
  } else {
    console.log("How?");
  }
</script>

<div>
  <div id="container">
    <div id="textArea">
      <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Recusandae
        atque tempore placeat, voluptatum maxime enim modi ullam inventore
        obcaecati vel. Est facere eum odio accusantium hic error omnis eligendi
        atque.
      </p>
    </div>
    <input
      bint:value={userInput}
      id="input-main"
      placeholder={userInput || "Start typing to begin.."}
      type="text"
    />
  </div>
</div>

<style>
  div {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 100%;
    height: 40vh;
    /* border: 2px solid #eceff4; */
    align-self: center;
    flex-direction: column;
  }
  div #container {
    width: 60%;
    padding-top: 10rem;
  }

  div #textArea {
    width: 100%;
    color: #d8dee9;
    font-size: 25px;
  }
  div #textarea p {
    font-family: "Nunito", sans-serif;
  }
  input {
    background-color: transparent;
    border: none;
    width: 100%;
    height: 10%;
    font-family: "Nunito", sans-serif;

    color: #eceff4;
    border-radius: 5px;
    border: 2px solid #eceff4;
    align-items: flex-start;
  }
</style>
