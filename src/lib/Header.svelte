<script>
    import MdFile from "./index.md";
   
    //import logo
    import logo from "./Business_Software_weiss.png";
    const metadata = MdFile.default;

    console.log(metadata);
</script>
<header>
  <nav>
    <figure>
       <img src="{logo}" height="50" alt="Logo" srcset="">
    </figure>
    <h1><span class="show"></span> Cheatsheet</h1>
    <ul></ul>
  </nav>
</header>

<style>
  header {
    background-color: var(--background);
    width: 100%;
    box-shadow: 1px 1px 5px rgba(0, 0, 0, 0.1);

  }
  nav {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    width: 100%;
  }
  figure {
    display: flex;
    justify-content: center;
    align-items: center;
    position:fixed;
    margin: 0rem;
    padding: 0;
    top:0;
    left:1rem;
    z-index: 9999;
    width: auto;
    max-width: 100%;
    height: 80px;
    max-height: 80px;
  }
  h1 {
    padding: .5em;
    margin: 0 auto;
    font-size: 2rem;
    letter-spacing:0px;
  }
  ul {
    display: flex;
    flex-direction: row;
  }
  ul > li {
  }
  ul > li > a {
    text-decoration: none;
    color: #333;
    padding: 1em;
  }
  ul > li > a:hover {
    background-color: #f4f4f4;
  }
  svg {
    width: 60px;
    max-width: 60px;
    height: 60px;
    max-height: 60px;
    padding: 0em;
    will-change: filter;
    transition: filter 300ms;
  }


  @media screen and (max-width: 1200px){
  figure{
    position:absolute;
  }
}
</style>
