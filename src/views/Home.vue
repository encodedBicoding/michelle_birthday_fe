<template>
  <div class="home">
    <div class="overlay"></div>
    <div class="main_content">
      <div class="sub_content">
        <div class="michelle_bg_2">
          <p class="birthday_text">
            Happy Birthday
          </p>
          <div>
            <sup class="quote">&quot;</sup>
            <span class="quoteText">What makes us what we are
               is the expression of love and support we give one another.
               If I could choose whom to fall so deeply for again, I'd still
               choose you.
            </span>
            <sub class="quote">&quot;</sub>
          </div>
          <a class="click_btn" href="https://youtu.be/kuB8qM4Im-w" target="_blank">Click here</a>
        </div>
        <div class="michelle_bg"></div>
      </div>
    </div>
  </div>
</template>

<style lang="css" scoped>
.home {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  background-image: url('../assets/bg.jpeg');
  background-size: cover;
  background-color: #F8EDED;
  position: absolute;
  width: 100%;
  height: 100%;
  overflow: hidden;
  top: 0;
  bottom: 0;
}
.overlay {
  background-color: #F8EDED;
  opacity: 0.4;
  position: absolute;
  top: 0;
  z-index: 9;
  width: 100%;
  height: 100%;
}
.main_content{
  z-index: 10;
  position: absolute;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  width: 100%;
  height: 100%;
}
.sub_content{
  position: relative;
  width: 70%;
  height: 100%;
  display: grid;
  grid-template-columns: 50% 50%;
  grid-template-rows: auto;
}
.michelle_bg{
  width: 100%;
  height: 100%;
  background-image: url('../assets/michelle.png');
  background-size: cover;
  image-resolution: high;
  object-fit: none;
  background-position: center;
}
.michelle_bg_2{
  width: 100%;
  height: 100%;
}
.birthday_text{
  font-size: 100px;
  font-weight: bold;
  background-color: #892323;
  background-size: 100%;
  background-image: linear-gradient(45deg, #892323 40%, #F46677 65%);
  background-clip: text;
  background-repeat: repeat;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}
.quote{
  font-size: 30px;
  color: #892323
}
.quoteText{
  font-size: 18px;
  color: #F46677;
  text-align: justify;
  justify-content: center;
}
.click_btn{
  margin-top: 30px;
  font-size: 20px;
  font-weight: 600;
  cursor: pointer;
  transition: all 0.3s ease-in-out;
  color: #000;
  outline: none;
  text-decoration: none;
}
.click_btn:hover{
  font-weight: 400;
}
</style>

<script>
// @ is an alias to /src

export default {
  name: 'Home',
  components: {},
};
</script>
