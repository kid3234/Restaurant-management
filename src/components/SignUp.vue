<template>
    <div>
        <img src="../assets/Rlog.jpg" alt="restorant logo" />
        <h1>Sign up</h1>
        <div class="Fdiv">
            <input class="input" type="text" placeholder="Full name" />
            <input class="input" type="email" placeholder="emal@gmai.com" />
            <input class="input" type="password" placeholder="Enter password" />
            <input class="input" type="password" placeholder="Confirm password" />
            <button class="btn" type="submit" value="SignUp" />
        </div>
        <p>I already have an account <a>Login</a></p>
    </div>
</template>
<script>
export default {
    name : 'SignUp'
}
</script>
<style scoped>
.input{
   width: 200px;
   height: 30px;
   border-radius: 10px;
   border: none;
}
.Fdiv{
    display: flex;
    flex-direction: column;
    margin: auto;
    width: 600px;
    height: 800px;
}
.btn{
    width: 200px;
    height: 40px;
    border-radius: 10px;
    border: none;

}
</style>