<template>
    <div class="login">
        <div class="logo">
            <img src="../../assets/logo1.jpg" />
        </div>
            <h2>GET Well</h2>
        <div class="details">
            <form>
                <input type="email" placeholder="Email Address" class="text"><br>
                <input type="password" name="password" id="" placeholder="Password" class="text">
                <br><button class="button">Login</button>
            </form>
        </div>
        <div class="forget">
            <link to ="Forget Password" class="reset"/><span><link to = "Sign Up"/></span> 
        </div>
    </div>
</template>
<style scoped>
*{
    margin:0;
    padding:0;
    box-sizing: border-box;
}
.login{
    display: flex;
    flex-direction: column;
    width:25vw;
    height: 100vw;
}
.logo{
    border: none;
    width: 25vw;
    padding: 0px;
}
img{
    width: 70px;
    border-radius:50%;
}
h2{
   border: none;
    font-family:'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    line-height: 2;
    width: 25vw;
    padding-left: 20px;
    color:rgb(37, 160, 201);
 
}
.details{
    width:2
}
</style>