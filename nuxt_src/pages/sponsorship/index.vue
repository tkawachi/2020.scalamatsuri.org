<template>
  <div id="sponsorship">
    <div class="main">
      <div class="main_inner">
        <h1 class="main_title">
          スポンサー募集
        </h1>
      </div>
    </div>
    <!-- sponsorship ここから -->
    <div class="sponsorship">
      <h2 class="sponsorship_title">
        ScalaMatsuriをご支援していただける<br class="is_pc">スポンサー様を募集しています。
      </h2>
      <p class="sponsorship_text">
        以下の資料を参照の上、ご検討いただければ幸いです。
      </p>
      <div class="sponsorship_btnArea">
        <a href="http://2019.scalamatsuri.org/ja/sponsors/sponsorship.pdf" class="sponsorship_btn sponsorship_btn-pdf">スポンサーシップのご案内</a>
        <a href="https://docs.google.com/forms/d/e/1FAIpQLSeR6XIcQ-2Y1-blyFEy3wzCf0HngrbxY79UDcO7bI1AoU_gbQ/viewform" class="sponsorship_btn sponsorship_btn-form">お申込みフォーム</a>
      </div>
      <p class="sponsorship_note">
        年末年始は、2018年12月27日(木)から2019年1月6日(日)までスポンサー窓口はお休みです。<br>2018年12月25日(火)23:59JSTまでにスポンサーのお申し込みいただいた場合は、請求書を年内にご送付 いたします。
      </p>
    </div>
    <!-- sponsorship ここまで -->
    <!-- recruit ここまで -->
    <section class="section recruit">
      <h2 class="section_title">
        <span class="section_title_inner">特別企画 - 私、ScalaMatsuriで転職しました -</span>
      </h2>
      <p class="section_text">
        ScalaMatsuriを実際に活用され、就職または転職された方々のインタビューを記事にしました。ご参考になれば幸いです。
      </p>
      <ul class="recruit_recruit">
        <li>
          <img v-lazy="'/img/sponsorship/img-recruit1.jpg'" alt="" class="recruit_recruit_img">
          <p class="recruit_recruit_title">
            <a href="https://blog.scalamatsuri.org/entry/2017/10/20/175103"> 株式会社エフ・コードさまへ就職された中村学さん（@gakuzzzz）</a>
          </p>
        </li>
        <li>
          <img v-lazy="'/img/sponsorship/img-recruit2.jpg'" alt="" class="recruit_recruit_img">
          <p class="recruit_recruit_title">
            <a href="https://blog.scalamatsuri.org/entry/2017/10/30/150859">株式会社セプテーニ・オリジナルさまへ就職された河内崇さん（@kawachi）</a>
          </p>
        </li>
        <li>
          <img v-lazy="'/img/sponsorship/img-recruit3.jpg'" alt="" class="recruit_recruit_img">
          <span class="section_title_inner"><p class="recruit_recruit_title"><a href="https://blog.scalamatsuri.org/entry/2018/01/17/173447">株式会社FOLIOさまへ就職された横田紋奈さん（@ihcomega）</a></p></span>
        </li>
      </ul>
    </section>
    <!-- recruit ここまで -->
    <!-- plan ここから -->
    <section class="section plan">
      <h2 class="section_title">
        <span class="section_title_inner">スポンサープラン</span>
      </h2>
      <div class="section_scroll">
        <table class="section_table2 section_table2-wide">
          <thead>
            <tr>
              <th colspan="2" />
              <th>
                <p class="color color_shogun">
                  将軍<span>ショーグン</span>
                </p>
              </th>
              <th>
                <p class="color color_tairou">
                  大老<span>タイロウ</span>
                </p>
              </th>
              <th>
                <p class="color color_daimyo">
                  大名<span>ダイミョー</span>
                </p>
              </th>
              <th>
                <p class="color color_samurai">
                  侍<span>サムライ</span>
                </p>
              </th>
              <th>
                <p class="color color_ninja">
                  忍者<span>ニンジャ</span>
                </p>
              </th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <th colspan="2">
                金額
              </th>
              <td>¥1,500,000</td>
              <td>¥750,000</td>
              <td>¥300,000</td>
              <td>¥100,000</td>
              <td>¥25,000</td>
            </tr>
            <tr>
              <th colspan="2">
                招待枠 (6/28,29)
              </th>
              <td>12名様</td>
              <td>8名様</td>
              <td>6名様</td>
              <td>2名様</td>
              <td>1名様</td>
            </tr>
            <tr>
              <th colspan="2">
                貴社ノベルティ配布(6/27,28,29)
              </th>
              <td>3点まで</td>
              <td>3点まで</td>
              <td>2点まで</td>
              <td>1点まで</td>
              <td>─</td>
            </tr>
            <tr>
              <th rowspan="5">
                ロゴ・社名掲載
              </th>
              <th>Web</th>
              <td>◎<br>first view</td>
              <td>○</td>
              <td>○</td>
              <td>○</td>
              <td>○</td>
            </tr>
            <tr>
              <th>スピーカーバックパネル<br>(6/28,29)</th>
              <td>A会場</td>
              <td>B会場</td>
              <td>─</td>
              <td>─</td>
              <td>─</td>
            </tr>
            <tr>
              <th>会場内装飾品<br>(6/28,29)</th>
              <td>○</td>
              <td>─</td>
              <td>─</td>
              <td>─</td>
              <td>─</td>
            </tr>
            <tr>
              <th>弊社ノベルティ<br>(6/27,28,29)</th>
              <td>○</td>
              <td>○</td>
              <td>○</td>
              <td>─</td>
              <td>─</td>
            </tr>
            <tr>
              <th>Tシャツ<br>(6/28,29)</th>
              <td>○</td>
              <td>─</td>
              <td>─</td>
              <td>─</td>
              <td>─</td>
            </tr>
            <tr>
              <th colspan="2">
                広告用スライド(6/27,28,29) <span class="color color_new">NEW!!</span>
              </th>
              <td>1ページ</td>
              <td>1/2ページ</td>
              <td>1/4ページ</td>
              <td>─</td>
              <td>─</td>
            </tr>
            <tr>
              <th colspan="2">
                常設ブース (6/28,29)
              </th>
              <td>○</td>
              <td>─</td>
              <td>─</td>
              <td>─</td>
              <td>─</td>
            </tr>
            <tr>
              <th colspan="2">
                Web情報掲載 ※2
              </th>
              <td>○</td>
              <td>○</td>
              <td>○</td>
              <td>○</td>
              <td>─</td>
            </tr>
          </tbody>
        </table>
      </div>
      <p class="plan_note">
        ※1 貴社サービスのご説明や求人情報など、ご希望のWebサイトに掲載いたします。
      </p>
    </section>
    <!-- plan ここまで -->
    <!-- booth ここから -->
    <section class="section booth">
      <h2 class="section_title">
        <span class="section_title_inner">常設ブース(6/28,29)</span>
      </h2>
      <table class="section_table2 section_table2-alignL">
        <tr>
          <th>金額</th>
          <td>¥250,000</td>
        </tr>
        <tr>
          <th>上限枠数</th>
          <td>11枠(将軍プラン6枠 + 別売り5枠)</td>
        </tr>
        <tr>
          <th>招待枠</th>
          <td>2名様</td>
        </tr>
      </table>
      <p class="section_text">
        <em>侍スポンサー以上のプランよりお申込み頂けます。</em><br>将軍スポンサー以外のプランは常設ブースは別販売となります。
        常設ブースには2名様分の招待枠が付きます。この招待枠は通常プランに付いて来るものと同じ扱いで、カンファレンスや懇親会にご参加頂けますが、常設ブースの設営及び運営をされる方も招待枠を使用してご入場ください。<br>
        (なお、将軍スポンサーの招待枠12名様の中には、常設ブースの設営及び運営をされる方用として2名様分の招待枠が含まれております。)
      </p>
    </section>
    <!-- booth ここまで -->
    <!-- booth ここから -->
    <section class="section booth">
      <h2 class="section_title">
        <span class="section_title_inner">宴スポンサー</span>
      </h2>
      <table class="section_table2 section_table2-alignL">
        <tr>
          <th>金額</th>
          <td>¥500,000</td>
        </tr>
        <tr>
          <th>上限枠数</th>
          <td>2枠</td>
        </tr>
        <tr>
          <th>特典</th>
          <td>・Webサイトロゴ掲載 <span class="color color_new">NEW!!</span><br>・懇親会の冠権<br>・懇親会LT枠（10分）<br>・懇親会用紙ナプキンへのロゴ掲載</td>
        </tr>
      </table>
      <p class="section_text">
        <em>侍スポンサー以上のプランよりお申込み頂けます。</em><br>ScalaMatsuriの懇親会をスポンサードして頂くプランです。今年度は懇親会を2会場で開催することを予定しています。
      </p>
    </section>
    <!-- booth ここまで -->
    <!-- booth ここから -->
    <section class="section booth">
      <h2 class="section_title">
        <span class="section_title_inner">各特典のスケジュール</span>
      </h2>
      <a href="/img/sponsorship/img-schedule.png" target="_blank" rel="noopener"><img v-lazy="'/img/sponsorship/img-schedule.png'" alt="" class="section_img"></a>
    </section>
    <!-- booth ここまで -->
    <!-- sponsorship ここから -->
    <div class="sponsorship">
      <h2 class="sponsorship_title">
        ScalaMatsuriをご支援していただける<br class="is_pc">スポンサー様を募集しています。
      </h2>
      <p class="sponsorship_text">
        以下の資料を参照の上、ご検討いただければ幸いです。
      </p>
      <div class="sponsorship_btnArea">
        <a href="http://2019.scalamatsuri.org/ja/sponsors/sponsorship.pdf" class="sponsorship_btn sponsorship_btn-pdf">スポンサーシップのご案内</a>
        <a href="https://docs.google.com/forms/d/e/1FAIpQLSeR6XIcQ-2Y1-blyFEy3wzCf0HngrbxY79UDcO7bI1AoU_gbQ/viewform" class="sponsorship_btn sponsorship_btn-form">お申込みフォーム</a>
      </div>
      <p class="sponsorship_note">
        年末年始は、2018年12月27日(木)から2019年1月6日(日)までスポンサー窓口はお休みです。<br>2018年12月25日(火)23:59JSTまでにスポンサーのお申し込みいただいた場合は、請求書を年内にご送付 いたします。
      </p>
    </div>
    <!-- sponsorship ここまで -->
    <section class="inquiry">
      <h3 class="inquiry_title">
        スポンサーのお申込みに関するお問い合わせ
      </h3>
      <p class="inquiry_text">
        <a href="">本年度スポンサーシップのご案内</a> をご参照の上、不明点などがございましたら <a href="" target="_blank" rel="noopener">お問い合わせフォーム</a> よりお問い合わせください。
      </p>
    </section>
  </div>
</template>

<script>
import Page404NotFoundMixin from '@/mixins/page/Page404NotFound.js'
export default {
  // TODO: スポンサーが決定し次第、404表示を解除する
  mixins: [Page404NotFoundMixin],
  head() {
    return {
      title: 'スポンサー募集',
      meta: [{ name: 'og:title', content: 'スポンサー募集 | ScalaMatsuri 2020' }]
    }
  }
}
</script>
