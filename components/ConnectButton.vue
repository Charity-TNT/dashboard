<template>
    <span>
        <button @click="connect" class="btn btn-sm btn-primary">Connect</button>
    </span>
</template>

<script>

export default {
    setup () {

        const connect = async () => {
            alert("Coming soon!");
        };

        return {
            connect,
        }
    }
}
</script>
