<template>
    <header>
        <nav class="navbar" role="navigation" aria-label="main navigation">
            <div class="navbar-brand">
                <div class="columns is-mobile">
                    <div class="column">
                        <h1 class="bd-notification is-info">MAGMA</h1>
                        <div class="columns is-mobile">
                            <div class="column">
                                <h3 class="bd-notification is-info">Serralheria Industrial</h3>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div id="navbarBasicExample" class="navbar-menu">
                <div class="navbar-end">
                    <a class="navbar-item button is-primary">
                        Home
                    </a>

                    <a class="navbar-item">
                        Serviços
                    </a>
                    <a class="navbar-item">
                        Lojinha artesanatos
                    </a>

                    <div class="navbar-item has-dropdown is-hoverable">
                        <a class="navbar-link">
                            Contato
                        </a>

                        <div class="navbar-dropdown">
                            <a class="navbar-item">
                                Whatsapp
                            </a>
                            <a class="navbar-item">
                                Instagram
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </nav>
    </header>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
    name: 'MenuBar'
})

</script>

<style>

</style>