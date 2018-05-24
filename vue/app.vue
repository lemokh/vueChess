<script>

new Vue({
    el: '#app',
    data: {
        clicks: 0,
    },
    methods: {
        handleCount(clicks) {
            this.clicks = clicks;
        }
    }
});

</script>