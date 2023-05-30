<template>
    <div class="header-menu ml-[90px]">
        <ul class="menu flex text-dark">
            <li class="mr-14 hover:text-brand cursor-pointer duration-300" v-for="(item, idx) in menuItems" :key="item">
                {{ item.name }}
            </li>
        </ul>
    </div>
</template>

<script>
import menuList from '../meniList.js'

export default {
    data() {
        return {
            // menuItems: menuList,
            menuItems: [
                {
                    name: 'Услуги',
                    link: ''
                },
                {
                    name: 'Материалы',
                    link: ''
                },
                {
                    name: 'Доставка и оплата',
                    link: ''
                },
                {
                    name: 'O компании',
                    link: ''
                },
                {
                    name: 'Контакты',
                    link: ''
                },
            ]
        }
    }
}
</script>