<script>
    import NavBar from "../components/NavBar.svelte";
</script>

<main>
    <NavBar />
    <div class="container">
        <div class="titolo">
            <h1>1522</h1>
        </div>
        
        <div class="text">
            <p>ciao donna, chiama!</p>
        </div>

        <div class="budda">
            <button>FREE V-BUCKS</button>
        </div>
    </div>
</main>

<style>
    * {
        margin: 0px;
    }

    .container {
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100vh;
        flex-direction: column;
    }

    .titolo {
        color: red;
        font-size: 3.5vw;
    }

    .budda {
        margin-top: 20px;
    }
</style>