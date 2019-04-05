<template>
    <div class="page">
        <div class="content">
            <CarList />
            <CarDetails />
        </div>
    </div>
</template>

<script>
import CarList from '../components/CarList.vue'
import CarDetails from '../components/CarDetails.vue'
export default {
    name : "CarPage",
    components: {
        CarList, CarDetails
    }
}
</script>

