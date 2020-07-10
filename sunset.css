@import url('https://fonts.googleapis.com/css2?family=Lexend+Deca&display=swap');


@mixin keyframes($animation-name) {
  @-webkit-keyframes #{$animation-name} {
    @content;
  }
  @-moz-keyframes #{$animation-name} {
    @content;
  }  
  @keyframes #{$animation-name} {
    @content;
  }
}

@mixin animation($animation-name) {
  -webkit-animation: $animation-name;
  -moz-animation: $animation-name;
  animation: $animation-name;
  -webkit-animation-fill-mode: both;
  -moz-animation-fill-mode: both;
  animation-fill-mode: both;
}

html, body {
	width: 100%;
	height: 100%;
}



body {
  margin: 0;
  padding: 0;
  display: flex;
  align-items: center;
  justify-content: center;
    
  font-family: 'Lexend Deca', sans-serif;
    color: white;
  overflow: hidden;
}

.base{
  min-width: 500px;
  min-height: 700px;
  display: flex;
  align-items: center;
  justify-content: center;
}

.main{
  position: relative;
  width: 500px;
  height: 700px;
  background: linear-gradient( #c6e3ff, #fbd786, #f7797d);
  box-shadow: 0 30px 20px -5px rgba(0,0,0,0.1),
        0 65px 50px -10px rgba(0,0,0,0.05);
}

.text{
  font-size: 20px;
  position: absolute;
  width: 500px - 20px;
  height: 700px - 20px;
  display: flex;
  justify-content: space-between;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    -webkit-transform: translate(-50%, -50%);
    -ms-transform: translate(-50%, -50%);
  

}

  .flex-right, .flex-left{
    display: flex;
    height: 700px - 20px;
    flex-direction: column;
    justify-content: space-between;
  }
  


.circle{
  width: 330px;
  height: 330px;
  border-radius: 50%;
  background: linear-gradient( #fa7d7d, #fbd786, #f7797d);
  background-size: 200% 200%;

  margin: 0 auto;
  margin-top: 50px;
  
  @include animation(AnimateGrad 30s ease infinite);
}

@include keyframes(AnimateGrad){
    0%{background-position:4% 0%}
    50%{background-position:97% 100%}
    100%{background-position:4% 0%}
}


.rects{
  // position: relative;
  width: 100%;
  height: 100%;
  
  .rect{
  position: absolute;
  width: 320px;
  height: 320px;
  border: 1px solid white;
  // transform: rotate(45deg);
  
    top: 42%;
    left: 17%;
  
  
	@include animation(rectAnime 20s ease-in-out infinite alternate);
    
    @for $i from 1 to 8 {
  &:nth-child(#{$i}) { animation-delay: $i * 0.6s; }
}

  }
}



@include keyframes(rectAnime){
    0%{transform: rotate(45deg);

  }
  100%{
    transform: rotate(-45deg - 180deg);

  }
}
