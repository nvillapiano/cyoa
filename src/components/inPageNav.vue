<template>
    <div class="in-page-nav"> 
        <a href="nextPageRoute">{{nextPage}}</a>
        <a v-if href="additionalOptionRoute1">{{additionalOption1}}</a>
        <a v-if href="additionalOptionRoute2">{{additionalOption2}}</a>
        <a v-if href="additionalOptionRoute3">{{additionalOption3}}</a>
        <a v-if href="additionalOptionRoute4">{{additionalOption4}}</a>
        <a v-if href="additionalOptionRoute5">{{additionalOption5}}</a>
        <a v-if href="additionalOptionRoute6">{{additionalOption6}}</a>       
    </div>
</template>

<script>
export default {
  name: 'inPageNav',
  data () {
    return {
        nextPageRoute: '#',
        nextPage: '',
        additionalOptionRoute1: '#1',
        additionalOption1: 'Route 1',
        additionalOptionRoute2: '#2',
        additionalOption2: 'Route 2',
        additionalOptionRoute3: '#3',
        additionalOption3: 'Route 3',
        additionalOptionRoute4: '#4',
        additionalOption4: 'Route 4',
        additionalOptionRoute5: '#5',
        additionalOption5: 'Route 5',
        additionalOptionRoute6: '#6',
        additionalOption6: 'Route 6' 
    }
  }
}
</script>

<style scoped lang="scss">
    .in-page-nav {
    
        a, a:hover, a:active, a:visited, a:link {
            display: block;
            font-size: 1.6rem;
            text-decoration: none;
            color: #000;
            transition: color 0.3s;
        
            &:hover {
                color: red;
            }
        }
    }
</style>
