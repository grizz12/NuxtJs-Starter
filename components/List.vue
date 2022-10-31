<template>
    <div>
        <div class="text-list">
        <p>Lorem Lorem</p>
        <h2>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Temporibus, enim. <br> Lorem ipsum dolor sit amet consectetur adipisicing elit.</h2>
    </div>
    <b-container class="item">
        <b-row>
            <b-col v-for="items in isi" :key="items.id">
                <b-card
        border-variant="secondary"
        :header="items.title"
        header-border-variant="secondary"
        align="center"
      >
        <b-card-text>{{ items.isi }}</b-card-text>
        <b-button variant="dark">Avaliable Now</b-button>
      </b-card>
            </b-col>
        </b-row>
    </b-container>
    <div class="text-bottom">
        <p>lorem Lorem, ipsum dolor.</p>
    </div>
    </div>
</template>

<script>
export default {
    data () {
        return {
            isi: [
                {
                    id: 1,
                    title: 'Lorem 1',
                    isi: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit.'
                },
                {
                    id: 2,
                    title: 'Lorem 2',
                    isi: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit.'
                },
                {
                    id: 3,
                    title: 'Lorem 3',
                    isi: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit.'
                },
                {
                    id: 4,
                    title: 'Lorem 4',
                    isi: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit.'
                },
            ]
        }
    }
}
</script>

<style>
.text-list {
    text-align: center;
    margin-top: 5rem;
}
.item {
    margin-top: 5rem;
}
.text-bottom {
    text-align: center;
    margin-top: 5rem;
}
</style>