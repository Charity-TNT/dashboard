<template>
    <span>
        <button @click="comingSoon" class="btn btn-sm btn-primary">Connect</button>
    </span>
</template>

<script>
export default {
    setup () {
        const comingSoon = () => {
            alert('Coming soon!');
        }

        return {
            comingSoon,
        }
    }
}
</script>
