<script>
    import {Button} from "$lib/components/ui/button/index.js";
</script>

<nav class="flex justify-between items-center py-4">
    <img class="logo" src="/icons/Logo.svg" alt="Logo">

    <ul class="flex gap-12">
        <li>Home</li>
        <li>About</li>
        <li>Contact</li>
        <li>Blog</li>
    </ul>

    <div class="flex gap-2">
        <Button class="rounded-full px-6">Login</Button>
        <Button variant="outline" class="rounded-full px-6">Register</Button>
    </div>
</nav>

<style>
    .logo {
        cursor: pointer;
    }

    li {
        cursor: pointer;
    }
</style>

