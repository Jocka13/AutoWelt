<template>
  <div class="row">
    <div class="col-10 mx-auto">
      <h2 class="fw-bold">Документација со барање за лизинг: ФИЗИЧКИ ЛИЦА</h2>
      <p>Со пополнето барање за одобрување на лизинг, <strong>профактура на добавувачот</strong> и <strong>прифатена лизинг понуда</strong>, потребно е да се приложат и:</p>
    </div>
    <ul class="col-9 mx-auto" v-for="item in objectList">
      <li v-html="item.text">{{item.text}}</li>
    </ul>
    <p class="col-10 mx-auto"><strong>Документација треба да биде заверена со потпис и печат на овластеното лице!</strong></p>
    <p class="col-10 mx-auto mb-0"><strong>AUTOWELT</strong> го задржува правото да побара дополнителна документација за разгледување на барањата за одобрување на лизинг.
    </p>
  </div>
</template>

<script>
export default {
name: "FizickiLicaList",
data(){
  return {
      objectList : [
        {
          text: 'ПРОФАКТУРА'
        },
        {
          text: 'БАРАЊЕ за одобрување на лизинг <a target="_blank" href="https://s-leasing.mk/content/%D0%91%D0%B0%D1%80%D0%B0%D1%9A%D0%B5%20%D0%B7%D0%B0%20%D0%BE%D0%B4%D0%BE%D0%B1%D1%80%D1%83%D0%B2%D0%B0%D1%9A%D0%B5%20%D0%BD%D0%B0%20%D0%BB%D0%B8%D0%B7%D0%B8%D0%BD%D0%B3-Fizicki%20Lica.pdf">(<b>превземи барање</b>)</a>'
        },
        {
          text: 'Копија од ЛИЧНА КАРТА'
        },
        {
          text: 'ПОТВРДА од работодавецот за редовен работен однос'
        },
        {
          text: 'Административна забрана од плата од работодавецот <a target="_blank" href="https://s-leasing.mk/content/%D0%90%D0%B4%D0%BC%D0%B8%D0%BD%D0%B8%D1%81%D1%82%D1%80%D0%B0%D1%82%D0%B8%D0%B2%D0%BD%D0%B0%20%D0%B7%D0%B0%D0%B1%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D0%B4%20%D0%BF%D0%BB%D0%B0%D1%82%D0%B0%20%D0%BE%D0%B4%20%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%BE%D0%B4%D0%B0%D0%B2%D0%B5%D1%86%D0%BE%D1%82%20%D0%B2%D0%BE%20%D0%BA%D0%BE%D1%80%D0%B8%D1%81%D1%82%20%D0%BD%D0%B0%20%D0%A8%D0%9F%D0%90%D0%A0%D0%9A%D0%90%D0%A1%D0%95%20%D0%9B%D0%98%D0%97%D0%98%D0%9D%D0%93%20%D0%94%D0%9E%D0%9E%20%D0%A1%D0%BA%D0%BE%D0%BF%D1%98%D0%B5.pdf">(<b>превземи Административна забрана</b>)</a>'
        },
        {
          text: 'ИЗЈАВА за редовна отплата <a target="_blank" href="https://s-leasing.mk/content/%D0%98%D0%B7%D1%98%D0%B0%D0%B2%D0%B0%20%D0%B7%D0%B0%20%D1%80%D0%B5%D0%B4%D0%BE%D0%B2%D0%BD%D0%B0%20%D0%BE%D1%82%D0%BF%D0%BB%D0%B0%D1%82%D0%B0.pdf">(<b>превземи Изјава</b>)</a>'

        },
        {
          text: 'Годишна даночна пријава (доколку барателот остварува дополнителни приходи)'
        },
        {
          text: 'Декларации за прием за бруто плата за последните 3 месеци'
        },
        {
          text: 'СОГЛАСНОСТ за извадок од Македонско Кредитно Биро <a target="_blank" href="https://s-leasing.mk/content/%D0%A1%D0%BE%D0%B3%D0%BB%D0%B0%D1%81%D0%BD%D0%BE%D1%81%D1%82%20%D0%B7%D0%B0%20%D0%B8%D0%B7%D0%B2%D0%B0%D0%B4%D0%BE%D0%BA%20%D0%BE%D0%B4%20%D0%9C%D0%B0%D0%BA%D0%B5%D0%B4%D0%BE%D0%BD%D1%81%D0%BA%D0%BE%20%D0%9A%D1%80%D0%B5%D0%B4%D0%B8%D1%82%D0%BD%D0%BE%20%D0%91%D0%B8%D1%80%D0%BE.pdf">(<b>превземи согласност</b>)</a>'
        }
      ]
    }
  }
}
</script>

<style scoped>

</style>