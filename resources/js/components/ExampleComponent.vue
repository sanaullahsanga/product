<template>
<!--    <div class="container">-->
<!--        <div class="row justify-content-center">-->
<!--            <div class="col-md-8">-->
<!--                <div class="card">-->
<!--                    <div class="card-header">Admin Component</div>-->

<!--                    <div class="card-body">-->
<!--                        I'm admin component.-->
<!--                    </div>-->
<!--                </div>-->
<!--            </div>-->
<!--        </div>-->
<!--    </div>-->
    <div>
        <v-container>
            <v-alert type="info">I am Vuetify Component V-Alert</v-alert>
            <v-btn link to="/foo">Load Foo</v-btn>
            <v-btn link to="/bar">Load Bar</v-btn>
            <v-btn link to="/user/sanaullah">Load User</v-btn>
        </v-container>
        <v-content>
            <router-view></router-view>
        </v-content>
    </div>
</template>

<script>
    export default {
        mounted() {
            console.log('Component mounted.')
        }
    }
</script>
