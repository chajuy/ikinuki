<template>
  <div>
    <Header />
    <div class="profileEdit">
      <div class="profileEdit__title">プロフィール編集</div>
      <div class="profileEdit__avatar">
        <img src="@/assets/images/avatar.svg" width="120" height="120">
      </div>
      <div class="profileEdit__avatarUpdate">
        <a href="">プロフィール写真を変更</a>
      </div>
      <div class="profileEdit__osusume">
        ピクセル＊ピクセル　（正方形）の画像が推薦です。
      </div>
      <ul class="profileEdit__form">
        <li>
          <div class="profileEdit__form__row">
            <div class="profileEdit__form__row__title">氏名</div>
            <ul class="profileEdit__form__row__input">
              <li>
                <input type="text">
              </li>
              <li><input type="text"></li>
            </ul>
          </div>
        </li>
        <li>
          <div class="profileEdit__form__row">
           <div class="profileEdit__form__row__title">プロフィールテキスト</div>
           <div class="profileEdit__form__row__input">
             <textarea ></textarea>
           </div>
          </div>
        </li>
      </ul>
      <div class="profileEdit__submit">
        <button class="btn btn--large btn--submit">設定する</button>  
      </div>
    </div>
    <Footer />
  </div>
  
</template>
<script>
import Header from "@/components/Header";
import Footer from "@/components/Footer";

export default {
  components: {
    Header,
    Footer,
  }
}
</script>