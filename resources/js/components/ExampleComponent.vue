<template>
    <section class="hero is-medium is-light is-bold">
        <div class="hero-body">
            <div class="container">
                <h1 class="title">
                    Hello World
                </h1>
                <p class="subtitle">
                    My Laravel website with <strong>Bulma</strong>!
                </p>
                <p>
                    (If you see a "thumbs-up" icon here -->>
                    &nbsp;<span class="icon has-text-success"><i class="fa fa-thumbs-up"></i></span>&nbsp;
                    <<-- all is well!)
                </p>
            </div>
        </div>
    </section>
</template>

<script>
    export default {
        mounted() {
            console.log('Component mounted.')
        }
    }
</script>
