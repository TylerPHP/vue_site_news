<template>
    <div id="app">
        <NavBar :search="search"/>
        <NewsArea :data="data"/>
        <SmallNews :data="data"/>
        <Footer/>
    </div>
</template>

<script>
    // eslint-disable-next-line no-unused-vars
    import NavBar from "./components/NewsApp/NavBar";
    import NewsArea from "./components/NewsApp/NewsArea";
    import SmallNews from "./components/NewsApp/SmallNews";
    import Footer from "./components/NewsApp/Footer"

    export default {
        name: 'App',
        components: {
            NavBar,
            NewsArea,
            SmallNews,
            Footer,
        },
        data() {
            return {
                search: '',
                dataNews: '',
                data: [
                    {
                        'id': 0,
                        'head': 'Путин снова путин',
                        'article': 'bind by the terms of a contract, as one of apprenticeship.\n' +
                            'He was an articled pupil of Herbind by the terms of a contract, as one of apprenticeship.\n' +
                            'He was an articled pupil of Herbert Brewer at Gloucester Cathedral before gaining an opebind by the terms of a contract, as one of apprenticeship.\n' +
                            'He was an articled pupil of Herbert Brewer at Gloucester Cathedral before gaining an opebert Brewer at Gloucester Cathedral before gaining an open scholarship in composition to study with Stanford at the RCM in 1911.',

                    },  {
                        'id': 1,
                        'head': 'Путин снова путин',
                        'article': 'bind by the terms of a contract, as one of apprenticeship.\n' +
                            'He was an articled pupil of Herbind by the terms of a contract, as one of apprenticeship.\n' +
                            'He was an articled pupil of Herbert Brewer at Gloucester Cathedral before gaining an opebind by the terms of a contract, as one of apprenticeship.\n' +
                            'He was an articled pupil of Herbert Brewer at Gloucester Cathedral before gaining an opebert Brewer at Gloucester Cathedral before gaining an open scholarship in composition to study with Stanford at the RCM in 1911.',

                    },

                ],
            }
        },
        methods: {}
    }
</script>

<style>

</style>

