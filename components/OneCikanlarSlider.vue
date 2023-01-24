<template>
    <div>
        <h2 class="favori-modeller-baslik">Öne Çıkanlar</h2>
        <vue-horizontal-list :items="items" :options="options">
            <template v-slot:default="{ item }">
                <div>
                    <div class="image-container">
                        <img :src="item.image" />
                    </div>
                    <h5>{{ item.subtitle }}</h5>
                    <a>{{ item.title }}</a>
                    <p>{{ item.price }}</p>
                </div>
            </template>
        </vue-horizontal-list>
    </div>
</template>
<script>
import VueHorizontalList from "vue-horizontal-list";
export default {
    name: "image-three",
    components: {
        VueHorizontalList,
    },
    data() {
        return {
            items: [
                {
                    subtitle: "Skechers",
                    title: "Skechers Summits Erkek Siyah Spor Ayakkabı",
                    price:
                        "1.449 TL",
                    image: "https://cdn-ss.akinon.net/products/2021/11/17/356491/b65c7973-1020-4268-8160-05bfba31a2a3_size330x495.jpg",
                },
                {
                    subtitle: "adidas",
                    title: "adidas Ozweego Celox Unisex Gri Spor Ayakkabı",
                    price:
                        "1.449 TL",
                    image: "https://cdn-ss.akinon.net/products/2022/08/19/435667/095742a4-7954-4011-8f75-480f399dbb41_size330x495.jpg",
                },
                {
                    subtitle: "Skechers",
                    title: "Skechers Summits Erkek Lacivert Spor Ayakkabı",
                    price:
                        "1.449 TL",
                    image: "https://cdn-ss.akinon.net/products/2022/06/30/385314/3be7eeef-7348-4cac-9a1c-8e45f27e3eac_size330x495.jpg",
                },
                {
                    subtitle: "Skechers",
                    title: "Skechers Escape Plan Erkek Siyah Spor Ayakkabı",
                    price:
                        "1.449 TL",
                    image: "https://cdn-ss.akinon.net/products/2021/11/30/265132/54ca9b6e-941f-41e5-b162-b8a0a146af53_size330x495.jpg",
                },
                {
                    subtitle: "adidas",
                    title: "adidas Ozweego Celox Unisex Gri Spor Ayakkabı",
                    price:
                        "1.949 TL",
                    image: "https://cdn-ss.akinon.net/products/2022/08/19/435380/de555f50-9f68-4c37-8940-a68291367a54_size330x495.jpg",
                },
                {
                    subtitle: "Vans",
                    title: "Vans Old Skool Platform Siyah Kadın Sneaker",
                    price:
                        "1.249 TL",
                    image: "https://cdn-ss.akinon.net/products/2021/11/30/153481/0bb41fc2-042e-44ef-9b23-fe0067eec068_size330x495.jpg",
                },
                {
                    subtitle: "Skechers",
                    title: "Skechers Summits Spor Ayakkabı",
                    price:
                        "1.449 TL",
                    image: "https://cdn-ss.akinon.net/products/2022/11/18/430424/60b3fdb1-0daa-4037-8989-a1fb97031a90_size330x495.jpg",
                },
                {
                    subtitle: "Nike",
                    title: "Nike Zoom Air Fire Kadın Beyaz Spor Ayakkabı",
                    price:
                        "1.749 TL",
                    image: "https://cdn-ss.akinon.net/products/2021/09/10/348229/e81b38d0-5008-4adf-abcc-c619f77cd3b6_size330x495.jpg",
                },
                {
                    subtitle: "Nike",
                    title: "Nike Blazer Low Platform Kadın Beyaz Spor Ayakkabı",
                    price:
                        "1.449 TL",
                    image: "https://cdn-ss.akinon.net/products/2022/11/03/384116/22b4136f-bd54-4df2-b4e0-e5a2dd89b8e8_size330x495.jpg",
                },
                {
                    subtitle: "Vans",
                    title: "Vans Old Skool Platform Siyah Kadın Sneaker",
                    price:
                        "1.619 TL",
                    image: "https://cdn-ss.akinon.net/products/2021/11/30/153412/c71c0299-b5d2-4f24-b7e0-f1e4c132749e_size330x495.jpg",
                },
                {
                    subtitle: "Skechers",
                    title: "Skechers Summits Erkek Siyah Spor Ayakkabı",
                    price:
                        "1.049 TL",
                    image: "https://cdn-ss.akinon.net/products/2022/08/08/385955/21f76320-276b-4135-82a4-c9a34fb11a5b_size330x495.jpg",
                }
            ],
        };
    },
};
</script>
  
<style scoped>
.favori-modeller-baslik {
    text-align: center;
    font-size: 34px;
}

a {
    font-size: 14px;
}

h5 {
    font-size: 18px;
    font-weight: 700;
    color: #000;
    text-align: start;
}

p {
    margin-top: 4px;
    overflow: hidden;
    display: -webkit-box;
    text-overflow: ellipsis;
    word-break: break-word;
    -webkit-box-orient: vertical;
    -webkit-line-clamp: 2;
    font-weight: 500;
}

.vue-horizontal-list[data-v-8b923bbc] {
    margin-left: 370px;
    position: relative;
    width: 60%;
    height: 5%;
}

img {
    display: block;

}

.vhl-list>*[data-v-8b923bbc] {
    scroll-snap-align: start;
    flex-shrink: 0;
    max-width: 50%;
    max-height: 50%;
}
</style>