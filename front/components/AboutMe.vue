<template>
<div class="aboutMe" id="aboutMe">
<h1>About me</h1>
<div class="profile">
  <div class="profileText">
    <h2>山岸真悠子（Mayuko Yamagishi）</h2>
    <p>1997年5月22日生まれ、現在25歳。大学卒業後は、医薬品メーカーの営業事務としてアシスタント業務に従事。属人化した社内システムを見て「どうにか望むシステムを作れないか」と思い、2021年11月より独学でプログラミング学習を開始。<br>趣味は読書とテニス。夢は猫と暮らすことと、海外で働けるようになること👀✨</p>
  </div>
  <img src="~/assets/img/profile.png" width="300px">
</div>

<div class="biography">
  <h2>経歴</h2>
  <div class="bio-item">
    <p class="bio-date">2020.03</p>
    <p class="bio-info">フェリス女学院大学 文学部 卒業</p>
  </div>
  <div class="bio-item">
    <p class="bio-date">2020.10 - 現在</p>
    <p class="bio-info">医薬品メーカーである株式会社大和生物研究所にて勤務。<br>営業事務として売上管理やECの受注業務、国内外の新販路開拓に携わる。</p>
  </div>
  <div class="bio-item bio-bottom">
    <p class="bio-date">2021.11 - 現在</p>
    <p class="bio-info">プログラミングの学習を開始。独学でエンジニア転職を目指し邁進中。</p>
  </div>
</div>

<div class="result">
  <h2>現職での実績</h2>
  <h3>◆ インフルエンサーPRを実施し売上に貢献</h3>
  <p>現職ではInstagramにてインフルエンサーを起用した製品PRを行なっています。これまで委託業者を通してInstagramにてインフルエンサーPRを行っていましたが、反響があまりなかったことや会社が求めるインフルエンサーの属性でないことが気になり、<b>「私が直接インフルエンサーを探し、価格も含めて交渉しても良いですか？」</b>と上司に提案したところ、「面白そうだからやってみては？」と承諾を得ることができました。<br>喜びと同時に「絶対結果を出してみせる」という熱い気持ちが湧き上がってきました。</p>
  <p>そこで属性のあったインフルエンサーを起用し、どんな投稿の反応が良いか分析していった結果、<font color="#FF1616"><b>約半年で前年売上を達成することができました。</b></font></p>
  <p>業務を主体的に考え、新しいチャレンジに取り組む姿勢が成果に繋がったと考えております。</p>
</div>

<div class="skill">
  <h2>学習したプログラミングスキル</h2>
  <p text-aligin="center">フロントエンドを中心に学習を行なっております。</p>
  <p>HTML, CSS, JavaScript, Ruby, Ruby on Rails（APIモード）, Vue.js / Nuxt.js, Vuetify, Firebase, Netlify, MySQL, AWS（VPC・EC2・RDS・S3・ELB・CloudFront・IAM・Route53・ACM）, Git/GitHub</p>
</div>

<div class="pr">
  <h2>自己PR</h2>
  <div class="prText">
    <h3>1. 主体的に考え、行動する力</h3>
    <p>---------------------------------------------------------<br>
    現職ではコロナにより海外視察ができず、海外企業とのコネクションが一件もない状態が続いていました。そこで出展費200万円を30万円に抑えた上で、オンライン展示会であるAlibaba.comへの出展を提案・実行しました。現在は毎月20件の交渉・交流を行っており、海外企業とのコネクションを全くゼロの状態から増やすことに成功しました。</p>
  </div>
  <div class="prText">
    <h3>2. チームワーク力</h3>
    <p>---------------------------------------------------------<br>
    チームメンバーを巻き込んで目標に立ち向かう力があります。<br>現在エンジニア志望の女性コミュニティを運営しています。目的はプログラミング学習を習慣化すること、そして女性の「エンジニアになる」という選択肢を当たり前にすることです。それぞれが違う状況下でも、全員がコミットできるチームワークを目標にして活動しています。
    </p>
  </div>
  <div class="prText">
    <h3>3. 徹底的に打ち込む力</h3>
    <p>---------------------------------------------------------<br>
    やると決めた事には徹底的に打ち込む力があります。<br>プログラミング学習は2021年11月より毎日継続しております。平日は最低でも4時間、休日は10時間を目標とし、週平均50時間を継続しています。所属しているプログラミングコミュニティでも「バイタリティおばけ」と言われたことがあり、やり込む力には自信があります。</p>
  </div>

</div>
</div>
</template>

<script>
export default {

}
</script>

<style>
h2 {
  text-align: center;
  
}
.about > h1 {
  margin-top: 100px;
}
.profile {
  margin-bottom: 100px;
}
.profile, .history, .biography, .result, .skill, .pr {
  margin-bottom: 80px;
  margin-left: 100px;
  margin-right: 100px;
}
.profile {
  display: flex;
}
.profileText {
  /* margin: 20px; */
  margin-top: 70px;
  margin-bottom: 20px;
  margin-right: 40px;
}
.profileText h2 {
  /* color: #BF4E1A; */
}
.history h3 {
  margin-bottom: 10px;
}
.biography p {
  margin: 0;
  padding: 8px;
}
.bio-item {
  display: flex;
  padding: 12px 20px;
  /* border-bottom: 1px solid; */
  border-top: 1px solid;
}

.bio-date {
  width: 210px;
}

.bio-info {
  width: calc(100% - 210px);
}

.bio-bottom {
  border-bottom: 1px solid;
  /* border-bottom: 1px rgba($color: black, $alpha: 0.3) solid; */
}
.prText {
  margin-bottom: 40px;
}
</style>