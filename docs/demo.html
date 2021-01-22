<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Demo</title>
</head>
<body>
<div id="app">
    <select v-model="level1" @change="chooselevel1">
        <option :value="item" v-for="item in Object.keys(level1List)">{{item}}</option>
    </select>

    <select v-model="level2" v-if="level1">
        <option :value="item" v-for="item in level2List">{{item}}</option>
    </select>

    <hr>
    <b><a target="_blank" :href="`https://www.google.com/search?q=${level1}%20${level2}&tbm=isch`">{{level1 }} {{ level2 }}</a></b>

</div>
<script src="https://cdn.jsdelivr.net/npm/vue@2"></script>
<script src="https://unpkg.com/axios/dist/axios.min.js"></script>
<script>
    const app = new Vue({
        el: '#app',
        data: {
            level1: "",
            level2: "",

            level1List: [],
            level2List: [],

            json: []
        },

        methods: {
            chooselevel1() {
                this.level2 = ""
                this.level2List = []

                this.level2List = this.level1List[this.level1]
            },
        },
        async mounted() {
            const response = await axios.get('cars.json')
            this.json = response.data
            this.level1List = this.json.list
            console.log(this.level1List);
        }
    })
</script>
</body>
</html>
