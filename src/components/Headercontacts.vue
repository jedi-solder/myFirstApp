<template>
  <div class="headerContacts">
    <div class="headerContacts__phone">
      <img src="../assets/icon/phone.svg" alt="phone">
      <span>+123 456 7890</span>
    </div>
    <div class="headerContacts__emailAddress">
      <img src="../assets/icon/email.svg" alt="email">
      <span>info@example.com</span>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Headercontacts',
};
</script>

<style scoped>
.headerContacts {
  width: 400px;
  color: #ffffff;
  font-size: 17px;
  font-weight: 400;
  letter-spacing: 0.36px;
  display: flex;
  justify-content: space-between;
}
img {
  margin-right: 14px;
  height: 25px;
}
.headerContacts__phone,
.headerContacts__emailAddress {
  display: flex;
}
</style>
