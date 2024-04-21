# My Awesome GitHub Pages Site

<div id="stars"></div>
<div id="stars2"></div>
<div id="stars3"></div>

<style>
    body {
        margin: 0;
        padding: 0;
        overflow: hidden;
    }

    #stars, #stars2, #stars3 {
        width: 1px;
        height: 1px;
        background: transparent;
        position: fixed;
        top: 0;
    }

    #stars {
        background: url('https://www.transparenttextures.com/patterns/8-bit-dreams.png');
    }

    #stars2 {
        background: url('https://www.transparenttextures.com/patterns/8-bit-dreams.png');
        animation: animStar 50s linear infinite;
    }

    #stars3 {
        background: url('https://www.transparenttextures.com/patterns/8-bit-dreams.png');
        animation: animStar 100s linear infinite;
    }

    @keyframes animStar {
        from {
            transform: translateY(0) rotate(0deg);
        }
        to {
            transform: translateY(1000px) rotate(720deg);
        }
    }
</style>

<div>
    <p>This is where you can showcase your projects, blog posts, or anything else you want!</p>
    <!-- Your content goes here -->
</div>
