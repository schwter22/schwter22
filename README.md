body {
    background-color: whitesmoke;
  }
  .body {
    display: flex;
    align-items: center;
    justify-content: center;
    margin-top: 100px;
  }
  .birthdayCard {
    border-radius: 30px;
    position: relative;
    width: 420px;
    height: 500px;
    transform-style: preserve-3d;
    cursor: pointer;
    transform: perspective(2000px);
    transition: 1s;
  }
  .cardFront {
    position: relative;
    background-color: #fef0f8;
    width: 420px;
    height: 500px;
    border-radius: 0 15px 15px 0;
    overflow: hidden;
    transform-origin: left;
    box-shadow: inset 100px 20px 100px rgba(118, 118, 118, 0.2),
      30px 0 50px rgba(118, 118, 118, 0.2);
    transition: 0.6s;
  }
  .bdHat {
   width: 140px;
    height: auto;
    top: %;
    left: 7%;
    position: absolute;
    z-index: 4;
  }
  .balloons {
    position: absolute;
    width: 270px;
    height: auto;
    right: -10px;
    top: 30px;
  }
.cake    {
  display: flex;
  position: absolute;
    width: 140px;
    height: auto;

  right:30%;
    top: 60%;
}
  .taaImg {
    display: flex;
    justify-content: center;
    top: 120px;
    left: 15px;
    position: absolute;
    width: 150px;
    height: auto;
    z-index: 1;
  }
  .happy {
    text-align: center;
    left: 15%;
    top: 84%;
    font-size: 1.5em;
   font-family: 'Miltonian Tattoo', serif;
    color: hotpink;
    position: absolute;
    transition: 0.1s;
    z-index: 6;
  }
  .cardInside {
    position: absolute;
    background-color: #fef0f8;
    width: 420px;
    height: 500px;
    z-index: -1;
    left: 0;
    border-radius: 0 15px 15px 0;
    top: 0;
    box-shadow: inset 100px 20px 100px rgba(191, 190, 190, 0.2);
  }
  p {
    line-height: 30px;
    margin: 15px 10px 10px 30px;
    color: #333;
  }
  .back {
    font-family: Tahoma, sans-serif;
    color: #333;
    text-align: center;
    margin: 30px;
  }
  .birthdayCard:hover {
    transform: perspective(2500px) rotate(5deg);
    box-shadow: inset 100px 20px 100px rgba(116, 115, 115, 0.5),
      0 10px 100px rgba(116, 115, 115, 0.5);
  }
  .birthdayCard:hover .cardFront {
    transform: rotateY(-160deg);
  }
  .birthdayCard:hover .happy {
    visibility: hidden;
  }

