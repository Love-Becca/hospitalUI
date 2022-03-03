<template>
    <div class="body">
        <div class="logo">
            <img src="../../assets/logo1.jpg" alt="company logo"/>
        </div>
        <div class="welcome">
            <h2>Get Well</h2>
            <p class="greetings">Whenever,Wherever</p>
        </div>
        <div class="login">
            <p class="login-info">Login as:</p>
            <div class="admin">
                <button class="A1">Admin</button>
            </div>
            <div class="staff">
                <button class="A2">Staff</button>
            </div>
            <div class="doctor">
                <button class="A3">Doctor</button>
            </div>
        </div>
        
    </div>
</template>
<style scoped>
*{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}
.body{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    border: none;
    box-shadow: 5px 5px 10px rgba(23, 39, 39, 0.5);
    width: 25vw;
    height: 100vh;
    border-radius:5px;
    background-color: rgb(212, 228, 252);
}
.logo{
    border: none;
    width: 25vw;
    padding: 10px;
}
img{
    width: 70px;
    border-radius:50%;
}
.welcome{
    border: none;
    font-family:'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    line-height: 2;
    width: 25vw;
    padding-left: 20px;
    color:rgb(37, 160, 201);
}
p.greetings{
    font-size: 1.3rem;
    font-weight: 510;
    word-spacing: -10px;
    color:#30CFD0
}
.login{
    background-image:url("../../assets/landingpage.jpg");
    background-size: cover;
    width: 25vw;
    height: 80vh;
    border: none;
    border-radius: 50px 50px 0 0;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}
.login-info{
color: rgb(234, 238, 240);
font-family:'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
font-size: 1.2rem;
border:none;
margin-top:200px;
font-weight: 500;
}
.admin, .doctor, .staff{
    border:none;
    width:20vw;
}
button{
    width:19vw;
    height: 3rem;
    border-radius: 10px;
    margin: 10px 0px;
    text-align: center;
    font-weight:600;
    font-size: 1.5rem;
    font-family:'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    border:none;
    box-shadow: 3px 3px 5px grey 0.3;
}
.A1{
    background-color: rgb(18, 34, 104);
    color: white;
    cursor: pointer;
    animation-name: bounce;
    animation-duration: 0.3s;
    animation-iteration-count: 3;
}
@keyframes bounce{
    from{transform: translateY(10px);}
    to{transform: translateY(-10px);}
}
.A2{
    background-color: darkgrey;
    color:rgb(37, 160, 201);
    cursor: pointer;
    animation-name: bounce;
    animation-direction: reverse;
    animation-duration: 0.3s;
    animation-iteration-count: 3;
}
.A3{
    background-color: rgb(37, 160, 201);
    color: darkgrey;
    cursor: pointer;
    animation-name: bounce;
    animation-duration: 0.3s;
    animation-iteration-count: 3;
}
</style>