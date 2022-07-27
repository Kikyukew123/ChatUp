<template>
<nav class="container navbar navbar-expand-lg navbar-light bg-light">
    <a class="navbar-brand" href="#">Logo Here</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse " id="navbarSupportedContent" >
        <div class="navbar-nav mr-auto">
            <router-link to="/" class="nav-item nav-link">Home</router-link>
            <router-link to="/About" class="nav-item nav-link">About</router-link>
            <router-link to="/Contact" class="nav-link">Contact</router-link>
            <router-link to="/ChatUp" class="nav-link">ChatUp</router-link>
            <router-link to="/SignIn" class="nav-link">Login</router-link>
            <router-link to="/SignUp" class="nav-link">Sign Up</router-link>
        </div>
      
    </div>
</nav>
 
</template>

<script>
    export default{
        name:'NavBarViewVue '
    }
</script>



