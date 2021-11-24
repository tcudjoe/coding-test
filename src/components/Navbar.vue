<template>
    <div class="sidenav">
        <h1>Categories</h1>
        <a href="">
            <p>Tech</p>
        </a><a href="">
            <p>Charity</p>
        </a><a href="">
            <p>DIY</p>
        </a>
        <br>
        <h1>Availability</h1>
        <a href="">
            <p>Show funded</p>
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
        color: rgb(194, 194, 194);
    }

    a {
        /* padding: px; */
        text-decoration: none;
        font-size: 25px;
        color: #818181;
        display: block;
        transition: 300ms;
    }

    a:hover {
        color: #f1f1f1;
    }

    @media screen and (max-height: 450px) {
        .sidenav {padding-top: 15px;}
        .sidenav a {font-size: 18px;}
    }
</style>\n
