<script>
    import '../app.css'
</script>
<nav>
    <div class="container">
    <h1>Start Bootstrap</h1>
    <ul>
        <li>
            <a href="/">Home</a>
        </li>
        <li>
            <a href="/about">About</a>
        </li>
        <li>
            <a href="/services">Services</a>
        </li>
        <li>
            <a href="/contact">Contact</a>
        </li>
    </ul>
</div>
</nav>

<div class="container"> 
<slot />
</div>


<style>
    nav {
        
        background: #343a40;
        color:#fff;
        padding: 0.5em
    }

    

    h1 {
        font-size: 1em;
        font-weight:normal;
        margin: 0;
    }
    ul {
        display: flex;
        list-style: none;
        margin:0;
        margin-left: auto;
        font-size: 0.9em
        }
    
    li {
        margin-right: 1.6rem;
        
    }

    a {
        text-decoration: none;
        color:#fff;
    }
</style>