<template>
  <div class="container">
    <div class="row">
  <h1>はじめまして</h1>
  <p>遠近十穿といいます．</p>
  </div>
  <p>作りたいもの</p>
  <ul>
    <li>十L</li>
    <li>プロ入り</li>
    <li>睡眠時間日記</li>
    <li>ガソリンのリッター計算</li>
  </ul>
  <h2>十Lとは</h2>
  <p>主人公が生きるとは何かを考えさせてくれるタイピングアドベンチャーゲーム</p>
  <h2>プロ入りとは</h2>
  <p>プログラミングができない主人公がプログラマーになるための道筋を描くストーリー
    プロ入りとはプログラミングの入り口という意味である．
  </p>
  <div class="row">
    <div class="col-md-3">
    <b-card header="十Lとは" bg-variant="primary" text-variant="white">
      <b-card-text>主人公が生きるとは何かを考えさせてくれるタイピングアドベンチャーゲーム
        </b-card-text>
      </b-card>
    </div>
    <div class="col-md-3">
    <b-card header="プロ入りとは" bg-variant="secondary" text-variant="white">
      <b-card-text>プログラミングができない主人公がプログラマーになるための道筋を描くストーリー
    プロ入りとはプログラミングの入り口という意味である．
        </b-card-text>
        </b-card>
    </div>
    <div class="col-md-3">
    <b-card header="睡眠時間日記" bg-variant="info" text-variant="white">
      <b-card-text>毎日の睡眠時間と調子を記録します．
        </b-card-text>
        </b-card>
    </div>
    <div class="col-md-3">
    <b-card header="ガソリンのリッター計算" bg-variant="success" text-variant="white">
      <b-card-text>ガソリンのリッターを計算するアプリです．
        </b-card-text>
        </b-card>
    </div>
  
  </div>
  <a href=/text>textに飛びます．</a>
  </div>
  </div>
</template>

<script>
export default {
  name: 'IndexPage'
}
</script>

<style scoped>
  h1{
    background-color: #00ff88;
  }
</style>
