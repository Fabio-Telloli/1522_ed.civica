<nav>
    <a href="#" class="logo">img</a>
    <div class="nav-links">
        <a href="#">HOME</a>
        <a href="#">TICKET</a>
        <a href="#">LOGIN</a>
    </div>
</nav>

<style>
    nav {
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 10px 20px;
        background-color: #333;
        color: white;
    }

    .logo {
        font-size: 1.5em;
        font-weight: bold;
        color: white;
        text-decoration: none;
    }

    .nav-links {
        display: flex;
        gap: 15px;
    }

    .nav-links a {
        color: white;
        text-decoration: none;
        font-size: 1em;
        padding: 5px 10px;
        transition: background-color 0.3s, color 0.3s;
    }

    .nav-links a:hover {
        background-color: white;
        color: #333;
        border-radius: 5px;
    }

    @media (max-width: 600px) {
        .nav-links {
            flex-direction: column;
            align-items: flex-start;
            gap: 10px;
        }

        nav {
            flex-direction: column;
            align-items: flex-start;
        }
    }
</style>
