/* eslint-disable vue/no-multiple-template-root */
<template>
  <v-app id="the-home" :style='{ background: $vuetify.theme.themes.dark.background }'>
    <the-nav-bar />
    <v-container fluid>
      <v-row>
        <v-col cols="6">
          <v-img src="1.webp" contain max-height="500"></v-img>
        </v-col>
        <v-col cols="5">
          <h5 class="deep-purple--text text-lighten-2 top">Новинка!</h5>
          <h1 class="white--text">Apple iPhone 13 Pro Max 128G</h1>
          <p class="grey--text">
            Флагман преміум-класу Apple iPhone 13 Pro Max 128GB Graphite бу (MLL63) - це телефон, від якого ви отримуєте
            практично все, що тільки можете побажати. У iPhone з найбільшим екраном також найбільша ємність акумулятора
            в лінійці, а це означає, що його витривалість просто неймовірна.
          </p>
          <v-btn tile color="orange accent-4" dark>Детальніше</v-btn>
        </v-col>
        <v-col class="iphone-box" cols="12">
          <div class="iphone" id="the-iphone">
            <v-row>
              <v-col cols="12">
                <!-- phone -->
                <div class="iphone-cart iphone-cart__bgPhone">
                  <v-icon class="ml-3" color="orange accent-4" x-large>mdi-cellphone</v-icon>
                  <h3 class="white--text ml-3 mt-4">Apple iPhone 11 64GB</h3>
                  <p class="grey--text ml-3 mt-2">Потужний, швидкий, <br> функціональний – це <br> все про новий телефон
                    iPhone 11. </p>
                  <v-btn color="orange accent-4" dark text>Переглянути моделі <v-icon right>mdi-arrow-right</v-icon>
                  </v-btn>
                </div>
                <!-- end phone -->
                <!-- laptop -->
                <div class="iphone-cart iphone-cart__bgLaptop">
                  <v-icon class="ml-3" dark x-large>mdi-laptop</v-icon>
                  <h3 class="white--text ml-3 mt-4">Apple MacBook Pro 13" </h3>
                  <p class="grey--text ml-3 mt-6">Втілення функціональної швидкості,<br> потужності та класичного
                    дизайну.</p>
                  <v-btn color="orange accent-4" dark text>Переглянути моделі <v-icon right>mdi-arrow-right</v-icon>
                  </v-btn>
                </div>
                <!-- end laptop -->
                <!-- watch -->
                <div class="iphone-cart iphone-cart__bgPhone">
                  <v-icon class="ml-3" color="orange accent-4" x-large>mdi-watch-variant</v-icon>
                  <h3 class="white--text ml-3 mt-4">Apple Watch Series 7</h3>
                  <p class="grey--text ml-3 mt-2">Apple Watch Series 7 41mm GPS Green <br> Aluminum Case With Clover
                    Sport Band <br> (MKN03) </p>
                  <v-btn color="orange accent-4" dark text>Переглянути моделі <v-icon right>mdi-arrow-right</v-icon>
                  </v-btn>
                </div>
                <!-- end watch -->
              </v-col>
              <v-col class="mt-12" cols="10">
                <div class="preference">
                  <h1 class="orange--text text--darken-4 mt-4 preference-num">10</h1>
                  <h3 class="white--text mt-4 text-uppercase">років на ринку</h3>
                </div>
                <div class="preference-items preference-items__mRight">
                  <v-row>
                    <v-col class="preference-item" cols="12">
                      <div
                        class="preference-items preference-items__mButton preference-items__padd iphone-cart__bgPhone">
                        <h1 class="orange--text text--darken-4">180+ тис.</h1>
                        <p class="grey--text">щасливих клієнтів</p>
                      </div>
                    </v-col>
                    <v-col class="preference-item" cols="12">
                      <div class="preference-items preference-items__padd iphone-cart__bgPhone">
                        <h1 class="orange--text text--darken-4">2000+</h1>
                        <p class="grey--text">оригінальної техніки</p>
                      </div>
                    </v-col>
                  </v-row>
                </div>
                <div class="preference-items">
                  <v-row>
                    <v-col class="preference-item" cols="12">
                      <div
                        class="preference-items preference-items__mButton preference-items__padd iphone-cart__bgPhone">
                        <h1 class="orange--text text--darken-4">13</h1>
                        <p class="grey--text ">міст, де є AppleRoom</p>
                      </div>
                    </v-col>
                    <v-col class="preference-item" cols="12">
                      <div class="preference-items  preference-items__padd iphone-cart__bgPhone">
                        <h1 class="orange--text text--darken-4">1 млн</h1>
                        <p class="grey--text">кілометрів доставки</p>
                      </div>
                    </v-col>
                  </v-row>
                </div>
              </v-col>
            </v-row>
          </div>
        </v-col>
        <v-col md="3" offset-md="3" id="mac">
          <h4 class="white--text text-uppercase">Чому Mac такий унікальний</h4>
          <p class="grey--text">Неймовірно потужно, надзвичайно просто.</p>
        </v-col>
        <v-col class="text-end" md="3">
          <v-btn tile color="orange accent-4" dark>Детальніше <v-icon right>mdi-arrow-right</v-icon>
          </v-btn>
        </v-col>
        <!-- cart -->
        <v-col md="3" offset-md="3">
          <v-card class="pa-2 py-12" outlined tile height="250px" color="#1e1e1e1e">
            <v-img src="mac-1.png" contain></v-img>
          </v-card>
        </v-col>
        <v-col md="3">
          <v-card class="pa-2 py-12" outlined tile height="250px" color="#1e1e1e1e">
            <v-img src="mac-2.png" contain></v-img>
          </v-card>
        </v-col>
        <v-col md="3" offset-md="3">
          <v-btn class="ml-n4" color="white" dark text>Apple MacBook Air 2020 р., 256 ГБ</v-btn>
          <v-btn class="ml-n4" color="orange accent-4" dark text>Замовити<v-icon right>mdi-arrow-right</v-icon>
          </v-btn>
        </v-col>
        <v-col md="3">
          <v-btn class="ml-n4" color="white" dark text> Apple MacBook Pro M1 Pro 16'</v-btn>
          <v-btn class="ml-n4" color="orange accent-4" dark text>Замовити <v-icon right>mdi-arrow-right</v-icon>
          </v-btn>
        </v-col>
        <v-col md="3" offset-md="3">
          <v-card class="pa-2 py-12" outlined tile height="250px" color="#1e1e1e1e">
            <v-img src="mac-3.png" contain></v-img>
          </v-card>
        </v-col>
        <v-col md="3">
          <v-card class="pa-2 py-12" outlined tile height="250px" color="#1e1e1e1e">
            <v-img src="mac-4.png" contain></v-img>
          </v-card>
        </v-col>
        <v-col md="3" offset-md="3">
          <v-btn class="ml-n4" color="white" dark text>Apple MacBook Air M1 13</v-btn>
          <v-btn class="ml-n4" color="orange accent-4" dark text>Замовити<v-icon right>mdi-arrow-right</v-icon>
          </v-btn>
        </v-col>
        <v-col md="3">
          <v-btn class="ml-n4" color="white" dark text>Apple Macbook Pro 14" M1 Pro</v-btn>
          <v-btn class="ml-n4" color="orange accent-4" dark text>Замовити <v-icon right>mdi-arrow-right</v-icon>
          </v-btn>
        </v-col>
        <!-- end cart -->
        <v-col class="preference-items__padd topInverse " cols="12">
          <div class="footer">
            <div class="footer-contact " id="contact">
              <v-row>
                <v-col cols="7">
                  <h1 class="white--text">Офіційний реселлер техніки Apple</h1>
                  <p class="grey--text">
                    Ми прагнемо забезпечити своїх клієнтів передовими інноваційними технологіями та <br> найкращим
                    європейським сервісом.
                  </p>
                </v-col>
                <v-col cols="5">
                  <v-btn class="mt-16" tile color="orange accent-4" dark>Зворотній зв'язок</v-btn>
                </v-col>
              </v-row>
            </div>
          </div>
          <v-toolbar class="topTolbar" color="#000" dark flat>
            <div style="position:absolute; margin-left:auto; margin-right:auto; left: 0; right: 0; text-align: center;">
              <v-btn text>iPhone</v-btn>
              <v-btn text>Mac</v-btn>
              <v-btn text>Apple Watch</v-btn>
              <v-btn text>iPad</v-btn>
              <v-btn text>Airpods</v-btn>
            </div>
          </v-toolbar>
        </v-col>
      </v-row>
    </v-container>
    <TheFooter />
  </v-app>

</template>

<script>
import TheNavBar from '../components/TheNavBar.vue'
import TheFooter from '../components/TheFooter.vue'
export default {
  name: 'TheHome',

  components: {
    TheNavBar,
    TheFooter
  },
}
</script>

<style scoped>
#the-home {
  padding-top: 100px;
}

.top {
  margin-top: 150px;
}

.topInverse {
  margin-top: -250px;
}

.topToolbar {
  margin-top: 100px;
  text-align: center;
}

.iphone {
  width: 100%;
  height: 100%;
  background: linear-gradient(to right, #181818, #181818 50%, #000 50%, #000 50%);
  text-align: center;
  padding: 2em 2em;
}

.footer {
  width: 100%;
  height: 600px;
  background: #181818;
  text-align: center;
  padding: 2em 2em;
 
}

.footer-contact {
  display: inline-block;
  background-color: #000;
  padding: 2em 1em;
  vertical-align: middle;
  text-align: left;
  margin-top: 250px;
}

.iphone-cart {
  display: inline-block;
  padding: 2em 1em;
  vertical-align: middle;
  text-align: left;
  margin-right: 8px;
}

.iphone-cart__bgPhone {
  background-color: #1e1e1e;
}

.iphone-cart__bgLaptop {
  background-color: #3E236F;
}

.preference {
  display: inline-block;
  padding: 2em 1em;
  vertical-align: middle;
  margin-right: 5px;
  width: 240px;

}

.preference-items {
  display: inline-block;
  width: 245px;
  vertical-align: middle;
}

.preference-items__mRight {
  margin-right: 8px;
}

.preference-items__mButton {
  margin-bottom: 8px;

}

.preference-items__padd {
  padding: 8px 0;
}

.col-12.iphone-box {
  padding: 12px 0;
}

.col-12.preference-item {
  padding: 0;
}

h1.preference-num {
  font-size: 50px;
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  font-weight: bold;

}
</style>
