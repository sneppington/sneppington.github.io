# My Awesome GitHub Pages Site

<div id="stars"></div>
<div id="stars2"></div>
<div id="stars3"></div>

<style>
    body {
        margin: 0;
        padding: 0;
        overflow: hidden;
        background-color: black;
    }

    #stars, #stars2, #stars3 {
        width: 2px;
        height: 2px;
        background: #fff;
        position: fixed;
        top: 0;
    }

    #stars {
        left: 50%;
    }

    #stars2 {
        left: 25%;
    }

    #stars3 {
        left: 75%;
    }

    @keyframes animStar {
        from {
            transform: translateY(0) rotate(0deg);
        }
        to {
            transform: translateY(1000px) rotate(720deg);
        }
    }

    #stars {
        animation: animStar 50s linear infinite;
    }

    #stars2 {
        animation: animStar 100s linear infinite;
    }

    #stars3 {
        animation: animStar 150s linear infinite;
    }
</style>

<div>
    <p>This is where you can showcase your projects, blog posts, or anything else you want!</p>
    <!-- Your content goes here -->
</div>
