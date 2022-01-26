<template>
  <div class="container">
    <div class="row first">
      <h1>はじめまして!<br>遠近十穿といいます．</h1>
    </div>
  <div class="row second">
  <h2>作りたいもの</h2>
  <div class="row">
    <div class="col-md-3">
    <b-card header="十Lとは" bg-variant="secondary" text-variant="white">
      <b-card-text>主人公が生きるとは何かを考えさせてくれるタイピングアドベンチャーゲーム．<br>
        あなたはきっとこのゲームを終えた時にありがとうと言いたくなる．
        </b-card-text>
      </b-card>
    </div>
    <div class="col-md-3">
    <b-card header="プロ入りとは" bg-variant="secondary" text-variant="white">
      <b-card-text>プログラミングができない主人公がプログラマーになるための道筋を描くストーリー<br>
    プロ入りとはプログラミングの入り口という意味である．
        </b-card-text>
        </b-card>
    </div>
    <div class="col-md-3">
    <b-card header="睡眠時間日記" bg-variant="secondary" text-variant="white">
      <b-card-text>毎日の睡眠時間と調子を記録します．
        </b-card-text>
        </b-card>
    </div>
    <div class="col-md-3">
    <b-card header="ガソリンのリッター計算" bg-variant="secondary" text-variant="white">
      <b-card-text>ガソリンのリッターを計算するアプリです．
        </b-card-text>
        </b-card>
    </div>
  </div>
  </div>
  <a href=/text>textに飛びます．</a>
  </div>
  </div>
</template>

<script>
export default {
  name: "IndexPage",
};
</script>

<style scoped>
.first {
  background: linear-gradient(#1E00FF, #ffffff);
  height: 700px;
  text-align: center;
  color: #ffffff;
  align-items: center;
  justify-content: center;
}
.second {
  background: linear-gradient(#ffffff,#05FBFF );
  height: 700px;

}
</style>
