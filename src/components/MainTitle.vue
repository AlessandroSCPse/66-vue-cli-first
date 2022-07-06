<template>
    <div class="title">
        <h2 class="title-main">{{ titleText }}</h2>

        <h3 class="title-subtitle">Sottotitolo</h3>

        <a href="#" class="red">Link 1</a>
        <a href="#" class="green">Link 2</a>
    </div>
</template>

<script>
export default {
    name: "MainTitle",
    data() {
        return {
            titleText: 'Ciao sono un titolo test'
        };
    }
}
</script>

<style lang="scss" scoped>
@import '../style/variables';
@import '../style/mixins';

.title {
    margin-bottom: 20px;

    &-main {
        background-color: $secondary_color;
        color: $main_color;
    }

    &-subtitle {
        background-color: $main_color;
        color: $secondary_color;
    }

    a.red {
        @include link-btn;
        color: red;
    }
    a.green {
        @include link-btn;
        color: green;
    }
}

</style>
