<script>

/*
 Utilizzo un componente dentro ad un altro
 Seguo tre passaggi:
 1) importazione nome del file
 2) Dichiarazione del componente all'interno dell'oggetto
 3) Utilizzo del componente
*/
    // IMPORTO IL NOME DEL FILE (non l'ho ancora creato ma AppTitle sarà il nome)
import AppTitle from './components/AppTitle.vue';


export default {
  data() {
    return {
        title: 'Prova stampa in pagina '
    };
  },
  // 2) Dichiarazione dei componenti 
  components: {
    AppTitle
  }
};


    </script>

    <template>

<!-- SCRIVERE SEMPRE FRA I DIV, SIA STRINGE IMPORTATE CHE CODICE SCRITTO DIRETTAMENTE QUI -->
    <div>  
        <!-- 3)Utilizzo del componenete -->
        <AppTitle/>

        {{ title }}

    </div>
  
    </template>

<style scoped>

</style>
