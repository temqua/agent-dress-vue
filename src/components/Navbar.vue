<template>
    <div class="container">

    <div class="row">
        <div class="col s12">
                <h1>
        24shop
    </h1>
        </div>
    </div>
    </div>

</template>

<script>
export default {
  name: 'Navbar'
}
</script>
<style lang="scss" scoped>
h1 {
    font-family: 'Poppins', sans-serif;
}
.breadcrumbs {
    padding: 48px 0;
    margin: 0;
    color: #a6a6a6;
    list-style: none;
    font-family: 'Poppins', sans-serif;
}

.breadcrumbs li {
    position: relative;
    color: #a6a6a6;
    padding: 0 12px;
}

.breadcrumbs li:nth-of-type(1) {
    padding-left: 0;
}

.breadcrumbs li::after {
    content: '/';
    position: absolute;
    top: 0;
    right: -6px;
    width: 10px;
}


.breadcrumbs li:nth-last-of-type(1)::after {
    display: none;
}

.breadcrumbs li a {
    color: #191919;
    text-decoration: none;
}

</style>