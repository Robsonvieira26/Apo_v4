<template>
  <!-- Search component Accordion with name of type,  press Ctrl + F -->

  <div class="accordion h-auto p-3">
    <div class="grid lg:grid-cols-1 grid-col-1 gap-4 mt-5">
      <!-- default alert  -->
      <div class="card col-span-1 grid grid-cols-1 gap-5 bg-white dark:bg-gray-800 w-full rounded-md p-5 shadow">
        <div class="accordion-packed">
          <div class="wrapper mt-5">

            <!-- Input Titulo -->
            <div
              class="input-box borderdark:bg-gray-900 dark:border-gray-700 rounded-mdmr-5 w-full box-border lg:flex md:flex focus-within:bg-gray-100 dark:focus-within:bg-gray-700">
              <input type="text" placeholder="Pergunta sem Titulo"
                class="p-3 w-full bg-white dark:bg-gray-900 rounded-md outline-none focus:bg-gray-100 dark:focus:bg-gray-700" />
            </div>
            <!-- Input Titulo -->
            <div class="wrapper-button mt-3">
              <select name="" id=""
                class="dark:bg-gray-800 dark:hover:bg-gray-700 border-gray-200 dark:border-gray-300 border max-w-lg px-4 py-3 block rounded-md text-gray-500 dark:text-gray-400">
                <option value="">----</option>
                <option value="">Resposta Aberta</option>
                <option value="">Escolha Unica</option>
                <option value="">Escolha Multipla</option>
                <option value="">Escala Likert</option>
              </select>

            </div>
            <div class="wrapper-button mt-3">
              <select name="" id=""
                class="dark:bg-gray-800 dark:hover:bg-gray-700 border-gray-200 dark:border-gray-300 border max-w-lg px-4 py-3 block rounded-md text-gray-500 dark:text-gray-400">
                <option value="">----</option>
                <option value=""> Totalmente Satisfatório - Satisfatório - Médio - Insatisfatório - Totalmente
                  Insatisfatório</option>
                <option value=""> Muito Bonito - Bonito - Médio - Feio - Muito Feio</option>
                <option value="">Muito Agradável - Agradável - Médio - Desagradável - Totalmente
                  Excluído</option>
                <option value="">Totalmente Incluído - Parcialmente Incluído - Médio - Excluído - Totalmente
                  Excluído</option>
              </select>

            </div>

            <!-- copy this component  -->
            <!-- <app-accordion>
              <template v-slot:title>
                <div
                  class="input-box border dark:bg-gray-900 dark:border-gray-700 rounded-mdmr-5 hidden w-full box-border lg:flex md:flex focus-within:bg-gray-100 dark:focus-within:bg-gray-700">
                  <input type="text" placeholder="Insira o nome da "
                    class="p-3 w-full bg-white dark:bg-gray-900 rounded-md outline-none focus:bg-gray-100 dark:focus:bg-gray-700" />
                </div>
              </template>
              <template v-slot:content>
                <p>
                  <b>Lorem</b>, ipsum dolor sit amet consectetur adipisicing
                  elit. Quia, porro. Non a excepturi, voluptatibus ipsam magnam,
                  eligendi, accusantium ipsa quae quis praesentium voluptate
                  saepe ullam sint ea itaque consectetur impedit?
                </p>
              </template>
            </app-accordion>  -->
            <!-- end copy -->
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import { Icon } from "@iconify/vue";
import AppAccordion from "../../components/AppAccordion.vue";
import MenuAccordion from "../../components/MenuAccordion.vue";
export default {
  name: "NewEvaluation",
  components: {
    Icon,
    AppAccordion,
    MenuAccordion,
  },
  mounted() { },
};
</script>
