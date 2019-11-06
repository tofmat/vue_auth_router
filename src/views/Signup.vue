<template>
<div class="row my-5">
<div class="col-md-6 offset-md-3">
    <div class="card">
        <div class="card-body">
            <h3 class="text-center my-4">Signup</h3>
            
            <div class="form-group">

            <input type="text" v-model='name' placeholder="Name" class="form-control">

            </div>
            <div class="form-group">

            <input type="text" v-model='email' placeholder="Email" class="form-control">

            </div>
             <div class="form-group">

            <input type="password" v-model='password' placeholder="Password" class="form-control">

            </div>
             <div class="form-group text-center">

                <button @click="registerUser()" class="btn btn-success form-control">Signup</button>
            </div>
        </div>
    </div>
</div>
</div>
</template>

<script>
export default {
    data(){
        return{
            name: '',
            email: '',
            password: ''
        }
    },
    methods: {
        registerUser() {

        }
    }
}
</script>
