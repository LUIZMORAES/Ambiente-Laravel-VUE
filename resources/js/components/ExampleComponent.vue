<template>
    <div class="container">
        <div class="row justify-content-center">
            <div class="col-md-8">
                <div class="card">
                    <div class="card-header">Ambientando Vue no laravel</div>

                    <div class="card-body">
                        <input type="text" v-model="teste">

                        {{teste}}
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        data: () => {
            return {
                teste: ''
            }
        },
        mounted() {
            console.log('Component mounted.')
        }
    }
</script>
