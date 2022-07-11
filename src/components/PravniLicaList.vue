<template>
  <div class="row">
    <div class="col-10 mx-auto">
      <h2 class="fw-bold">Документација со барање за лизинг: ПРАВНИ ЛИЦА</h2>
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
name: "PravniLicaList",
data(){
  return {
      objectList : [
        {
          text: 'Барање за одобрување на лизинг <a target="_blank" href="https://s-leasing.mk/content/%D0%91%D0%B0%D1%80%D0%B0%D1%9A%D0%B5%20%D0%B7%D0%B0%20%D0%BE%D0%B4%D0%BE%D0%B1%D1%80%D1%83%D0%B2%D0%B0%D1%9A%D0%B5%20%D0%BD%D0%B0%20%D0%BB%D0%B8%D0%B7%D0%B8%D0%BD%D0%B3_Pravni%20Lica-11.01.2022.pdf">(<b>превземи барање</b>)</a>'
        },
        {
          text: 'Копија од тековна состојба, не постара од 6 недели'
        },
        {
          text: 'Завршна сметка (биланс на состојба и биланс на успех за последните две фискални години)'
        },
        {
          text: 'Аналитички заклучни листови кон завршните сметки за последните две години'
        },
        {
          text: 'Аналитички заклучен лист за тековната година со последен датум на книжење'
        },
        {
          text: 'Согласност за извадок од Македонско Кредитно Биро'
        },
        {
          text: 'Изјава за вистински сопственик'
        }
      ]
    }
  }
}
</script>

<style scoped>

</style>