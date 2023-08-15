<template>
    <div>
        <h1> Portfolio</h1>
        <video src="@/assets/ron-portfolio.mp4" type="mp4" controls autoplay></video> <br>
        <a href="https://javascript-playground-ron-miguel.netlify.app/" target="_blank"> My Website</a>
    </div>
</template>
<script>
export default {
    name: "Portfolio"
}
</script>
<style scoped>
div {
    min-height: 100vh;
    background: #555;
    color: #111;
}
a {
    color: #fff;
}
video {
    max-width: 600px;
    filter: brightness(70%);
    transition: .5s;
}
video:hover {
    max-width: 700px;
    filter: brightness(100%);
}
</style>