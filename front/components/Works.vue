<template>
  <div class="works" id="works">
  <h1>Works</h1>
    <div class="portfolio">
      <h2>自己内省アプリ『Insight』</h2>
      <div class="contents">
        <a href="https://www.insight-naisei.com/" target="_blank" rel="noopener noreferrer"><img src="~/assets/img/insight.png" width="450px"></a>
        <div class="text">
          <h3>概要</h3>
          <ul class="bottom">
            <li>自己認識を深めるための自己内省アプリ。</li>
            <li>自分を知るための様々な質問に回答し、記録していきます。</li>
            <li>ユーザーは人生の分岐点が多い10〜30代を想定。</li>
            <li>URL：<a  href="https://www.insight-naisei.com/" target="_blank" rel="noopener noreferrer">https://www.insight-naisei.com/</a></li>
          </ul>
          <h3>制作時期</h3>
          <p>2022年2月～4月中旬</p>
          <h3>使用技術</h3>
          <p>HTML, CSS, JavaScript, Vue.js/Nuxt.js, Vuetify, Firebase, Ruby on Rail（APIモード）, AWS（VPC・EC2・RDS・S3・ELB・CloudFront・IAM・Route53・ACM）</p>
          <h3>ソースコード(GitHub)</h3>
          <p><a href="https://github.com/mayukoooo/nuxt-rails-insight" target="_blank" rel="noopener noreferrer">https://github.com/mayukoooo/nuxt-rails-insight</a></p>
        </div>
      </div>
      <h3>こだわりポイント</h3>
      <ul>
        <li>完全SPA化によるページ遷移の高速化を実現。</li>
        <li>ターゲットユーザーは人生の分岐点が多い20〜30代男女問わずを想定しているので、中間的な雰囲気づくりを意識しました。</li>
        <li>「電車で取り組めるくらい手軽に」がコンセプトとしてあったので、スマホからのアクセスを想定したUI/UXにこだわりました。</li>
        <li>制作過程をQiita記事にまとめています。<a href="https://qiita.com/Mayuko_Yamagishi/items/b18646cbff7f95d37cc1" target="_blank" rel="noopener noreferrer">https://qiita.com/Mayuko_Yamagishi/items/b18646cbff7f95d37cc1</a></li>
      </ul>
    </div>
    <div class="portfolio">
      <h2>Mayuko’s Portfolio（当サイト）</h2>
      <div class="contents">
        <a  href="https://mayuko-portfolio.site/" target="_blank" rel="noopener noreferrer"><img src="~/assets/img/portfoliosite.png" height="200px"></a>
        <div class="text">
          <h3>概要</h3>
          <ul class="bottom">
            <li>私のこれまでの活動や人間性を伝えることを目的に作成。</li>
            <li>URL：<a  href="https://mayuko-portfolio.site/" target="_blank" rel="noopener noreferrer">https://mayuko-portfolio.site/</a></li>
          </ul>
          <h3>制作時期</h3>
          <p>2022年5月中旬～下旬</p>
          <h3>使用技術</h3>
          <p>HTML, CSS, JavaScript, Vue.js/Nuxt.js, S3, CroudFront, ACM, Route53</p>
          <h3>ソースコード(GitHub)</h3>
          <p><a href="https://github.com/mayukoooo/portfolio-site" target="_blank" rel="noopener noreferrer">https://github.com/mayukoooo/portfolio-site</a></p>
        </div>
      </div>
      <h3>こだわりポイント</h3>
      <ul>
        <li>一目でどんな人物なのかが伝わるよう文章は簡潔に、配色やデザインは私らしさを意識しました。</li>
      </ul>
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
.bottom {
  margin-bottom: 16px;
}
</style>