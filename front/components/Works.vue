<template>
  <div class="works">
  <h1>🌱 Works</h1>

    <div class="portfolio">
      <h2>自己内省アプリ『Insight』</h2>
      <div class="contents">
        <img src="~/assets/img/insight.png" width="450px">
        <div class="text">
          <h3>概要</h3>
          <p>・自己認識を深めるための自己内省アプリ。<br>
            ・自分を知るための様々な質問に回答し、記録していきます。<br>
            ・ユーザーは人生の分岐点が多い10〜30代を想定。<br>
            ・URL：https://www.insight-naisei.com/
          </p>
          <h3>制作時期</h3>
          <p>2022年2月～4月半ば</p>
          <h3>使用技術</h3>
          <p>HTML, CSS, JavaScript, Vue.js/Nuxt.js, Vuetify, Firebase, Ruby on Rail（APIモード）, AWS（VPC・EC2・RDS・S3・ELB・CloudFront・IAM・Route53・ACM）</p>
          <h3>ソースコード(GitHub)</h3>
          <p>https://github.com/mayukoooo/nuxt-rails-insight</p>
        </div>
      </div>
      <h3>こだわりポイント</h3>
      <p>・完全SPA化によるページ遷移の高速化を実現。<br>
         ・ターゲットユーザーは人生の分岐点が多い20〜30代男女問わずを想定しているので、中間的な雰囲気づくりを意識しました。<br>
         ・「電車で取り組めるくらい手軽に」がコンセプトとしてあったので、スマホからのアクセスを想定したUI/UXにこだわりました。<br>
         ・Qiita：制作過程をQiita記事にまとめています。<a>https://qiita.com/Mayuko_Yamagishi/items/b18646cbff7f95d37cc1</a>
      </p>
    </div>
    <div class="portfolio">
      <h2>Mayuko’s Portfolio（当サイト）</h2>
      <div class="contents">
        <img src="~/assets/img/portfoliosite.png" height="200px">
        <div class="text">
          <h3>概要</h3>
          <p>・私のこれまでの活動や人間性を伝えることを目的に作成。<br>
            ・URL：https://www.insight-naisei.com/
          </p>
          <h3>制作時期</h3>
          <p>2022年5月～</p>
          <h3>使用技術</h3>
          <p>HTML, CSS, JavaScript, Vue.js/Nuxt.js, Vuetify, Netlify</p>
          <h3>ソースコード(GitHub)</h3>
          <p>https://github.com/mayukoooo/porfolio-site</p>
        </div>
      </div>
      <h3>こだわりポイント</h3>
      <p>・一目でどんな人物なのかが伝わるよう文章は簡潔に、配色やデザインは私らしさを意識しました。<br>
        ・レスポンジブ対応（仮）。
      </p>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.works {
  margin-left: 100px;
  margin-right: 100px;
}
.portfolio {
  margin-bottom: 80px;
}
.contents {
  display: flex;
  margin-top: 15px;
  margin-bottom: 15px;
}
.text {
  margin-left: 20px;
}
</style>