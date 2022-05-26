<template>
    <div>
        Hello from Component {{ test }}
    </div>
</template>

<script>
    // here we have to export the module to import
    module.exports = {
        data: function () {
            return {
                test: 'test hello'
            }
        }
    }
</script>

<style></style>