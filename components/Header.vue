<template>
    <nav class="header">
        <h3 class="logo-text">Consultol</h3>
        <div class="menu">
            <div class="link">Home</div>
            <div class="link">Product</div>
            <div class="link">Pricing</div>
            <div class="link">Contact</div>
            <div class="menu-icon">Search</div>
            <div class="menu-icon">Cart</div>
            <div class="menu-icon">More</div>
        </div>
    </nav>
</template>

<style scoped>
    .header {
        display: flex;
        justify-content: space-between;
    }

    .logo-text {
        color: #252B42;
        font-size: 24px;
        font-style: normal;
        font-weight: 700;
        line-height: 32px; /* 133.333% */
    }

    .menu {
        display: flex;
    }

    .link {
        color: #737373;
        text-align: center;
        font-size: 14px;
        font-style: normal;
        font-weight: 600;
        line-height: 24px;
    }
</style>