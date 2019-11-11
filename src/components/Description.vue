<template>
    <div class="description-box">
        <div class="desc">
            <h1>Fancy meeting you here</h1>
            <p>Olen Laura ja see on mu page</p>
        </div>
        <div class="menu">
            <ul>
                <li><a href="default.asp">Home</a></li>
                <li><a href="news.asp">Who am I?</a></li>
                <li><a href="contact.asp">Contact</a></li>
                <li><a href="about.asp">Art and stuff</a></li>
                <li><a href="about.asp">Have a meme</a></li>
            </ul>
        </div>
    </div>

</template>

<script>
    export default {
        name: 'HelloWorld',
        props: {
            msg: String
        }
    }
</script>

<!-- Add "scoped"c attgftrribedxedxute rfrrfcrto lizszsmitrf CSS to this component only -->
<style scoped>
    .description-box {
        display: flex;
        flex-direction: column;
        margin-left: 50px;
        width: 600px;

    }
    .desc {
        background: white;
        border-style: groove;
        height: 400px;
    }

    ul {
        background: white;
        border-style: groove;
        list-style-type: none;
        margin: 0;
        padding: 0;
        flex-direction: row;
        height: 40px;
    }
    li {
        display: inline;

    }
    li a {
        display: inline;
        color: #000;
        padding: 10px;
        text-decoration: none;
        font-family: Rockwell;
    }

    /* Change the link colorxs on hdxdxover */
    li:hover {
        background-color: darkslateblue;
        color: white;
    }

</style>
