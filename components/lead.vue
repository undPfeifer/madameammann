<template>
    <section>
        <div>
            <p>READINGS → Marcel Proust (Selection 1,  from À la recherche du temps perdu)</p>
        
            <div class="row-two">

            <p class="small">Prof. Olivia Theyskens, born April 15, 1976, is a fictitious American literary critic and Sterling Dean of Literature at the fictitious Cargo University.  <br>
                           She has published innumerable fictitious reviews and articles, as well authored two fictitious volumes of short stories. She is perhaps best known for the fictitious story The Tin Ribbon. This will be her third fictitious workshop for The Writer’s Retreat.
            </p>
            <img src="https://freight.cargo.site/w/400/h/555/q/75/i/U812551708875851611697911245404/Professor-Georgette-Theyskens.jpg" alt="">
        </div>

        
        </div>
    </section>
</template>

<style scoped>
    div {
        display: grid;
        grid-template-columns: 6fr 6fr;
        gap: 20px;
        margin-bottom: 40px;
    }

    p {
        font-size: 24px;
        line-height: 1.1;
    }

    .small {
        font-family: 'geist-medium';
        font-size: 10px;
        line-height: 1.2;
        
        
    }

    .row-two {
        display: grid;
        grid-template-columns: 8fr 4fr;
    }

    
    @media (max-width: 700px) {
  div {
    grid-template-columns: 1fr;
    grid-template-rows: auto auto;
  }

  .row-two {
    display: grid;
    grid-template-columns: 8fr 4fr;
    gap: 40px;
  }
}

</style>