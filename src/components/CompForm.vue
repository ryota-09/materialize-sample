<template>
  <div class="form-area">
    <section id="contact">
      <div class="row">
        <div class="col s12 l5">
          <h2 class="indigo-text text-darken-4">タイトル</h2>
          <p>ここにテキストが入ります。ここにテキストが入ります。ここにテキストが入ります。ここにテキストが入ります。
          </p>
        </div>
        <div class="col s12 l5 offset-l2">
          <form action="">
            <div class="input-field">
              <i class="material-icons prefix">email</i>
              <input type="email" id="email">
              <label for="email">Eメール</label>
            </div>
            <div class="input-field">
              <i class="material-icons prefix">message</i>
              <textarea id="message" class="materialize-textarea"></textarea>
              <label for="message">メッセージ</label>
            </div>
            <div class="input-field">
              <input type="text" id="date" class="datepicker">
              <label for="date">date</label>
            </div>
            <div class="input-field">
              <p>タイトル</p>
              <p>
                <label>
                  <input type="checkbox">
                  <span>eat in</span>
                </label>
              </p>
              <p>
                <label>
                  <input type="checkbox">
                  <span>take out</span>
                </label>
              </p>
            </div>
            <div class="input-field center">
              <button class="btn">送信</button>
            </div>
          </form>
        </div>
      </div>
    </section>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
@Component
export default class CompForm extends Vue {

}
</script>

<style scoped>

</style>
