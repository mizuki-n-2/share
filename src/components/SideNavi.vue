<template>
  <div>
    <div class="left-padding">
      <img class="logo" src="../assets/logo.png" alt="">
      <div class="flex icon-field">
        <img class="icon" src="../assets/home.png" alt="">
        <p>ホーム</p>
      </div>
      <div class="flex icon-field">
        <img class="icon" src="../assets/profile.png" alt="">
        <p>プロフィール</p>
      </div>
      <div class="flex icon-field">
        <img class="icon" src="../assets/logout.png" alt="">
        <p>ログアウト</p>
      </div>
      <hr />
      <ShareMessage />
    </div>
  </div>
</template>

<script>
import ShareMessage from '../components/ShareMessage';
export default {
  components: {
    ShareMessage
  }
};
</script>

<style scoped>
.flex {
  display: flex;
}

.left-padding {
  margin: 20px;
}

.logo {
  width: 100px;
}

.icon-field {
  margin-top: 15px;
  cursor: pointer;
}

.icon-field p {
  font-size: 16px;
  padding-left: 15px;
}

.icon {
  width: 25px;
  height: 25px;
}
</style>