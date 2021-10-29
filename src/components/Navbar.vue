<template>
    <div class="sidenav">
        <h1>Categories</h1>
        <a href="">
            Tech
        </a>
        <a href="">
            <h5>Charity</h5>
        </a
        ><a href="">
            DIY
        </a>
        <br>
        <h1>Availability</h1>
        <a href="">
            Show funded
        </a>
    </div>
</template>

<style>
    .sidenav {
        height: 100%;
        width: 200px;
        position: fixed;
        z-index: 1;
        top: 0;
        left: 0;
        background-color: #111;
        overflow-x: hidden;
        padding-top: 20px;
    }

    h1 {
        color: white;
    }

    a {
        padding: 3px 3px 3px 16px;
        text-decoration: none;
        font-size: 25px;
        color: #818181;
        display: block;
        text-decoration: none;
    }

    a:hover {
        color: #f1f1f1;
    }

    @media screen and (max-height: 450px) {
        .sidenav {padding-top: 15px;}
        .sidenav a {font-size: 18px;}
    }

</style>\n
