<template>
    <div class="entry-container mb-3 pointer p-2"
    @click="$router.push({ name: 'entry', params: { id: 10 }})"
    >
        <div class="entry-title d-flex">
            <span class="text-success fs-5 fw-bold">15</span>
            <span class="mx-1 fs-5">Julio</span>
            <span class="mx-2 fw-light">2021, Jueves</span>
        </div>

        <div class="entry-description">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Sunt sed odit quasi numquam repellat blanditiis autem minima repudiandae laborum neque inventore, optio impedit aperiam. Explicabo asperiores esse itaque distinctio debitis!
        </div>
    </div>
</template>

<style lang="scss" scoped>
    .entry-container{
        border-bottom: 1px solid #2c3e58;
        transition: .2s all ease-in;
        &:hover{
            background-color: lighten($color: grey, $amount: 45);
            transition: .2s all ease-in;
        }
    }
    .entry-description{
        font-size: 12px;
    }
</style>
