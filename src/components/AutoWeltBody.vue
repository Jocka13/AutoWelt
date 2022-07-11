<template>
<main>
  <div class="container">
    <div class="row">
      <div class="col-9 mx-auto">
        <div class="ratio ratio-1x1">
          <img src="../assets/scss/images/FiveSteps.jpg" alt="FiveStepsPhoto" class="object-fit-cover"/>
        </div>
      </div>
    </div>
    <div class="row">
      <p class="col-10 mx-auto">Доколку сакате да купите возило на лизинг Ве молиме детално прегледајте ги податоците на оваа страна.
        Подолу имате калкулатор со кој можете орентационо да ги пресметате ратите за лизингот.
        Плаќањето можете да го прилагодите според вашите можности и потреби. На пример можете да си одредите фиксен дел за Учество кој ќе го платите,
        а останата сума да ја плаќате на онолку рати колку што Ви одговара.
      </p>
      <p class="col-10 mx-auto">
        НАПОМЕНА: дел од трошоците за процедурата зa лизинг се фиксни и се плаќаат на лизинг компанијата.
        Корисникот на лизинг е обврзан да го осигура возилото со целосно КАСКО осигурување за целото времетраење на лизингот, вклучувајќи и додаток во случај на кражба и проневера.
      </p>
    </div>
    <LizingList/>
    <FizickiLicaList/>
    <hr class="col-10 mx-auto">
    <PravniLicaList/>
    <hr class="col-10 mx-auto">
    <div class="row">
      <p class="text-danger col-10 mx-auto">* НАПОМЕНА: ДОКОЛКУ ПОДАТОЦИТЕ КОИ ГИ ОСТАВАТЕ ПРИ ПРЕД-ОДОБРУВАЊЕТО
      НЕ СЕ ТОЧНИ И ПРЕЦИЗНИ МОЖНО Е АПЛИКАЦИЈАТА ЗА ЛИЗИНГ ДА ВИ БИДЕ ОДБИЕНА ИЛИ
      ПРОЛОНГИРАНА ОД СТРАНА НА БАНКАТА И ПРИТОА ГО ГУБИТЕ ОСТАВЕНИОТ КАПАР.
      </p>
    </div>

  </div>
</main>
</template>

<script>
import LizingList from "@/components/LizingList";
import FizickiLicaList from "@/components/FizickiLicaList";
import PravniLicaList from "@/components/PravniLicaList";
export default {
name: "AutoWeltBody",
  components: {PravniLicaList, FizickiLicaList, LizingList},
}
</script>

<style scoped>

</style>