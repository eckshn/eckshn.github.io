<template>
    <div class="main-container">
        <div class="container-one">
            <div class="profile">
                <img src="../assets/logo.png" alt="">
                <h3>Eckart Schneider</h3>
                <p>Software Developer</p>
            </div>
            <div class="socials">
                <a href="">
                    <div class="link">
                        <img src="../assets/logo.png" alt="">
                        <h2>GitHub</h2>
                    </div>
                    <div class="link">
                        <img src="../assets/logo.png" alt="">
                        <h2>LinkedIn</h2>
                    </div>
                    <div class="link">
                        <img src="../assets/logo.png" alt="">
                        <h2>Email</h2>
                    </div>
                </a>
            </div>
        </div>
        <div class="container-two">
            <div class="about-me">
                <h1>About Me</h1>
                <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. 
                    Sit nemo repudiandae odit omnis voluptatum et in sunt minus animi, 
                    eum atque enim temporibus nostrum eos accusamus molestiae ipsum quo voluptas.</p>
            </div>
            <div class="skills">
                <h1>Skills</h1>

            </div>
        </div>
        
        
    </div>
</template>

<script>
export default {

}

</script>

<style scoped>
    img {
        height: 20px;
    }

    .main-container {
        display: flex;
        flex-direction: row;
        background-color:cadetblue;
    }

    .container-one {
        background-color:steelblue;
        width: 15%
    }

    .container-two {
        width: 85%;
    }
</style>