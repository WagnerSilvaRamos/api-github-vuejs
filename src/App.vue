<template>
  <div id="app">

    <nav class="navbar navbar-expand-md navbar-dark bg-dark">
            <a class="navbar-brand text-center" href="#">Busca Repositórios Vue js</a>
            <button class="navbar-toggler"
                    type="button"
                    data-toggle="collapse"
                    data-target="#navbarSupportedContent"
                    aria-controls="navbarSupportedContent"
                    aria-expanded="false"
                    aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
        </nav>

    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
html, body{ font-family: 'Helvetica Neue'}
a.navbar-brand{ text-align: center;; margin: 0 auto;color: #58d061!important; font-size: 18px}
h1{ margin-top: 50px}
p.lead{ font-size: 18px; font-family: inherit;}
</style>
