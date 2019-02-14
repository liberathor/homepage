<template>
    <div class="nav-container">
        <nav aria-label="main navigation" class="navbar is-transparent" role="navigation">
            <div class="navbar-brand">
                <nuxt-link class="navbar-item" to="/">
                    <h1 class="subtitle has-text-white has-text-weight-light" >Liberathion Studios</h1>
                </nuxt-link>
                <button class="button navbar-burger">
                    <span></span>
                    <span></span>
                    <span></span>
                </button>
            </div>
            <div class="navbar-menu">
                <div class="navbar-end">
                    <nuxt-link class="navbar-item has-text-white" to="/">Home</nuxt-link>
                    <nuxt-link class="navbar-item has-text-white" to="/about">About</nuxt-link>
                    <nuxt-link class="navbar-item has-text-white" to="/projects">Projects</nuxt-link>
                    <nuxt-link class="navbar-item has-text-white" to="/contact">Contact</nuxt-link>
                </div>
            </div>
        </nav>
    </div>
</template>
