<script>
    import Header from "$lib/Header.svelte";
    import Nav from "$lib/Nav.svelte";
</script>

<Header />
<Nav />

<div class="columns">
    <div class="column">
        <div class="box">
            <h1>About Us/History</h1>
            <hr />
            <p>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                Pellentesque sed velit sit amet felis eleifend finibus. Maecenas
                eu nisl sit amet augue vehicula ultricies. Class aptent taciti
                sociosqu ad litora torquent per conubia nostra, per inceptos
                himenaeos. Morbi sit amet lectus at augue vulputate ultrices. Ut
                volutpat ullamcorper vulputate. Praesent et orci quis nisi
                consequat eleifend ut sed purus. Donec quis feugiat leo. Ut in
                posuere velit, sed iaculis augue. Ut vitae libero nec ex posuere
                facilisis. Etiam facilisis quam in lacus viverra, nec euismod
                nunc vestibulum. Sed ac venenatis augue, at luctus odio.
                Phasellus urna nunc, volutpat sed augue at, mollis lobortis
                libero. Vivamus nec tellus non quam feugiat venenatis. Maecenas
                laoreet tellus eu nisl pretium, quis aliquet libero eleifend.
                Quisque viverra nunc et mauris ultricies, at porta massa
                eleifend. Aliquam vitae lorem mattis, lacinia nulla sit amet,
                commodo sapien.
            </p>
        </div>
    </div>
</div>
<div class="columns">
    <div class="column">
        <div class="box">
            <h1>info 1 and photos?</h1>
            <hr />
            <p>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                Pellentesque sed velit sit amet felis eleifend finibus. Maecenas
                eu nisl sit amet augue vehicula ultricies. Class aptent taciti
                sociosqu ad litora torquent per conubia nostra, per inceptos
                himenaeos. Morbi sit amet lectus at augue vulputate ultrices. Ut
                volutpat ullamcorper vulputate. Praesent et orci quis nisi
                consequat eleifend ut sed purus. Donec quis feugiat leo. Ut in
                posuere velit, sed iaculis augue. Ut vitae libero nec ex posuere
                facilisis.
            </p>
            <br />
            <img
                src="static/186547938_3990255997722098_1786875754172738849_n.jpg"
            />
        </div>
    </div>
    <div class="column">
        <div class="box">
            <h1>info 2</h1>
            <hr />
            <p>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                Pellentesque sed velit sit amet felis eleifend finibus. Maecenas
                eu nisl sit amet augue vehicula ultricies. Class aptent taciti
                sociosqu ad litora torquent per conubia nostra, per inceptos
                himenaeos. Morbi sit amet lectus at augue vulputate ultrices. Ut
                volutpat ullamcorper vulputate. Praesent et orci quis nisi
                consequat eleifend ut sed purus. Donec quis feugiat leo. Ut in
                posuere velit, sed iaculis augue. Ut vitae libero nec ex posuere
                facilisis. Etiam facilisis quam in lacus viverra, nec euismod
                nunc vestibulum. Sed ac venenatis augue, at luctus odio.
                Phasellus urna nunc, volutpat sed augue at, mollis lobortis
                libero. Vivamus nec tellus non quam feugiat venenatis. Maecenas
                laoreet tellus eu nisl pretium, quis aliquet libero eleifend.
                Quisque viverra nunc et mauris ultricies, at porta massa
                eleifend. Aliquam vitae lorem mattis, lacinia nulla sit amet,
                commodo sapien.
            </p>
        </div>
    </div>
</div>

<style>
    h1 {
        font-size: large;
        font-weight: bold;
    }
    .box {
        margin-top: 2em;
    }

    .column {
        margin-left: 2em;
        margin-right: 2em;
    }
</style>
