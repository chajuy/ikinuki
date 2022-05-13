<template>
  <div>
    <Header />
    <div class="setup">
      <div class="setup__body">
        <dl class="setup__list">
          <dt>Settings</dt>
          <dd>
            <button class="btn btn--medium btn--flat_orange">Profile</button>
          </dd>
          <dd>
            <button class="btn btn--medium btn--flat_orange">Mail Adress</button>
          </dd>
          <dd>
            <button class="btn btn--medium btn--flat_orange">Password Change</button>
          </dd>
          <dd>
            <button class="btn btn--medium btn--flat_orange">QnA</button>
          </dd>
          <dd>
            <button class="btn btn--medium btn--flat_orange">Policy</button>
          </dd>
          <dd>
            <button class="btn btn--medium btn--flat_orange">Privacy Policy</button>
          </dd>
          <dd>
            <button class="btn btn--medium btn--flat_gray">Privacy Policy</button>
          </dd>
        </dl>
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