<div class="fullnav">
<div class="nav">
    <nav>
        <a href="/" class="logo">Poppy</a>
        <div>
            <a href="/">HOME</a>
            <a href="/about">ABOUT</a>
        </div>
    </nav>
</div>
</div>

<slot/>
<div class="footer">
    <h4>Made by Priya Pal</h4>
</div>

<style>
    .fullnav{
        display: flex;
        justify-content: space-between;
        align-items: center;
        border-radius: 20px;
        color: black;
        padding: 1rem;
        margin-bottom: 10px;
        position: sticky;
        top:10px;
        z-index: 1;
    }
    .icon{
        width: 50px;
        height: 50px;
    }
    .nav {
        width: 50%;
        margin: 0 auto;
        align-items: center;
        border-radius: 20px;
        background: #141414;
        color: #fff;
        padding: 1rem;
        margin-bottom: 10px;
        position: sticky;
        top:10px;
        z-index: 1;
    }
    .nav nav {
        display: flex;
        justify-content: space-between;
        align-items: center;
    }
    .nav nav a {
        color: #fff;
        text-decoration: none;
        margin: 0 1rem;
    }
    .nav nav a:hover {
        color: #ccc;
    }
    .nav nav a.logo {
        font-weight: bold;
    }
    .footer{
        text-align: center;
        border-top: 2px solid black;
        margin-top: 10px;
    }
</style>