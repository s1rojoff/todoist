<template>
  <footer class="footer">
    <section class="footer__section">
      .
      <FlexWrap>
        <div>
          <img src="@/assets/img/flower.webp" class="footer__section_img" alt="" />
        </div>
        <div>
          <FoText color="black" size="40"></FoText>
          <NavBtn color="#e44232" text="white"></NavBtn>
        </div>
      </FlexWrap>
    </section>
    <section class="footerend">
      <FlexWrap>
        <div>
          <FooterLogo></FooterLogo>
          <div>
            <FoText color="grey" size="14">
              Join millions of people who organize work and life with Todoist.
            </FoText>

          </div>
          <FooterIcons></FooterIcons>
        </div>

        <div class="footer__link">
          <div>
            FEATURES
            <FoLink :items="features"></FoLink>
          </div>
          <div>
            RESOURCES
            <fo-link :items="resources"></fo-link>
          </div>
          <div>
            COMPANY
            <fo-link :items="company"></fo-link>
          </div>
        </div>
      </FlexWrap>
    </section>
  </footer>
</template>

<script>
import VImage from "./footer/VImage.vue";
import NavBtn from "./Navbar/NavBtn.vue";
import FoText from "./footer/FoText.vue";
import FlexWrap from "./FlexWrap.vue";
import FooterLogo from "./footer/FooterLogo.vue";
import FooterIcons from "./footer/FooterIcons.vue";
import FoLink from "./footer/FoLink.vue";
export default {
  name: "Footer",
  data() {
    return {
      features: ["How It Works", "For Teams", "Pricing", "Templates"],
      resources: ["Download Apps", "Help Center", "Productivity Methods", "Refer a friend", "Integrations", "Channel Paertners", "Devoloper API", "Status"],
      company: ["About Us", "We are hiring!", "Blog", "Press", "Twist"]
    }
  },
  components: { VImage, NavBtn, FoText, FlexWrap, FooterLogo, FooterIcons, FoLink },
};
</script>
<style lang="scss">
.footer {
  background-color: #fff9f3;

  &__section {
    padding: 30px;

    &_img {
      height: 500px;
      width: 400px;
    }
  }

  &__link {
    margin: 0 auto;
    width: 80%;
    display: flex;
    align-items: flex-start;
    justify-content: space-between;
    flex-direction: row;
    padding: 0 3rem;
  }

}

.my-3 {
  margin: 20px 0
}
</style>
