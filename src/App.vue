<template>
      <div class="container">
        <div id="title">Christmas Q25</div>
        <div class="subtitle">- 당신의 1년을 정리하는 25개의 질문 -</div>
        <div id="logo">로고</div>
        <div style="color: white; text-align: center;">
            <div>어서오세요 <span class="userName">{{nickname}}</span>님!</div>
            <div>메리크리스마스<span style="font-size: 20px;">&#x1F384;</span></div>
        </div>
        <form action="" method="post">
            <div>
                <input type="password" placeholder="비밀번호를 입력해주세요." id="password" name="pw" required>
            </div>
        </form>
        <div><button type="button" onclick="" class="btn">시작하기</button></div>
        <div><button type="button" onclick="" class="btn">비밀번호 찾기</button></div>
        <div style="color: white;">teamname</div>
    </div>
</template>

<script>

export default {
  name: 'App',
  data() {
    return{
        nickname : 'nickName'
    }
  },
  components: {

  }
}

</script>

<style>
@font-face {
    font-family: 'NanumSquareRound';
    src: url('https://cdn.jsdelivr.net/gh/projectnoonnu/noonfonts_two@1.0/NanumSquareRound.woff') format('woff');
    font-weight: normal;
    font-style: normal;
}

@import url('https://fonts.googleapis.com/css2?family=Sorts+Mill+Goudy&display=swap');

.container {
    display: flex;
    flex-direction: column;
    align-items: center;
    background-color: #920000;
    width: 360px; height: 640px;
    margin: 0 auto;
}

.btn {
    margin: 7px;
    background-color: white;
    border: none;
    border-radius: 3px;
    width: 120px; height: 30px;
    cursor: pointer;

    font-weight: bold;
}

#title {
    color: #FFF500;
    font-family: 'Sorts Mill Goudy', serif;
    font-size: 50px;
    margin-top: 50px;
}

#logo {
    color: black;
    width: 50px;
    padding: 60px;
    border: 1px solid black;
    margin: 40px;
    padding-top: 70px;
    padding-bottom: 70px;
    text-align : center;

    background-color: white;
}

#introductionBox {
    border: 1px solid black;
    width: 300px;
    background-color: white;
    margin: 25px;
}

#Registration {
    color: black;
    width: 50px;
    padding: 60px;
    border: 1px solid black;
    margin: 40px;
    text-align: center;

    background-color: white;
}

#Backbtn {
    background-color:rgba(0,0,0,0);
    color: #0D86FE;
    font-weight: bold;
    border-color: transparent;
    border: none;
    cursor: pointer;
}

.subtitle {
    color: white;
}

#password {
    width: 170px; height: 30px;
    border-radius: 3px;
    border: none;
    margin: 5px;
    text-align: center;
}

body {
    font-family: 'NanumSquareRound';
}

#usermail {
    text-decoration-line: underline;
    color: blue;
    text-align: center;
}
</style>
