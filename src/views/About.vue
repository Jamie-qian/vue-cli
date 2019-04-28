<template>
  <div class="about">
    <h1>This is an about page</h1>
    <div id="echarts" :style="{ width: '1200px', height: '600px'}"></div>
  </div>
</template>
<script>


export default {
    mounted () {
        this.draw();
    },
    created () {
        
    },
    methods:{
        draw(){
            let echarts = this.$echarts.init(document.getElementById('echarts')),
                    _this = this;

            echarts.setOption({
                title: {
                    text: 'ECharts 入门示例'
                },
                tooltip: {},
                xAxis: {
                    data: ['衬衫', '羊毛衫', '雪纺衫', '裤子', '高跟鞋', '袜子']
                },
                yAxis: {},
                series: [{
                    name: '销量',
                    type: 'bar',
                    data: [5, 20, 36, 10, 10, 20]
                }]
            })
        }
    }
}
</script>

