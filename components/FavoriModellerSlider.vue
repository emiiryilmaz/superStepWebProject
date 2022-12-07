<template>
    <div>
        <h2 class="favori-modeller-baslik">Favori Modeller</h2>
        <vue-horizontal-list :items="items" :options="options">
            <template v-slot:default="{ item }">
                <div>
                    <div class="image-container">
                        <img :src="item.image" />
                    </div>
                    <h5>{{ item.subtitle }}</h5>
                    <a>{{ item.title }}</a>
                    <p>{{ item.content }}</p>
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
                    subtitle: "Vans",
                    title: "Vans Old Skool Erkek Siyah Sneaker",
                    content:
                        "1.449 TL",
                    image: "https://cdn-ss.akinon.net/products/2021/02/27/321454/7efd4be2-873e-405f-af22-695b35a0c6be_size600x600_quality100_cropCenter.jpg",
                },
                {
                    subtitle: "The North Face",
                    title: "The North Face Nuptse Kadın Pembe Mont",
                    content:
                        "1.449 TL",
                    image: "https://cdn-ss.akinon.net/products/2022/10/25/501233/d26cade8-f97a-42fd-9710-4d5372c876fa_size600x600_quality100_cropCenter.jpg",
                },
                {
                    subtitle: "Nike",
                    title: "Nike Blazer Low'77 Premium Erkek Krem Sneaker",
                    content:
                        "1.449 TL",
                    image: "https://cdn-ss.akinon.net/products/2022/11/28/560637/d801bf6b-c150-448d-9997-25d72158e6e1_size600x600_quality100_cropCenter.jpg",
                },
                {
                    subtitle: "Converse",
                    title: "Converse Standart Fit Weares Unisex Siyah Pantalon",
                    content:
                        "1.449 TL",
                    image: "https://cdn-ss.akinon.net/products/2022/11/16/426293/c1adc423-cd6d-4ffb-97c3-2cb47a33d371_size600x600_quality100_cropCenter.jpg",
                },
                {
                    subtitle: "Nike",
                    title: "Nike Sportswear Repeat Fermuarlı Erkek Siyah Eşofman Üstü",
                    content:
                        "1.449 TL",
                    image: "https://cdn-ss.akinon.net/products/2022/11/28/560729/a4c36edf-7874-4e35-b59f-edff9830e706_size600x600_quality100_cropCenter.jpg",
                },
                {
                    subtitle: "Converse",
                    title: "Converse Run Star Legacy Cx Unisex Sarı Sneaker",
                    content:
                        "1.449 TL",
                    image: "https://cdn-ss.akinon.net/products/2022/08/01/426739/8af8f447-5534-48b6-bed5-9970f1f2ff0b_size600x600_quality100_cropCenter.jpg",
                },
                {
                    subtitle: "Puma",
                    title: "Puma Mayze T7 Kadın Platform Siyah Spor Ayakkabı",
                    content:
                        "1.449 TL",
                    image: "https://cdn-ss.akinon.net/products/2022/09/02/452066/675d78e3-125d-4682-b384-d726761349b9_size600x600_quality100_cropCenter.jpg",
                },
                {
                    subtitle: "Lacoste",
                    title: "Lacoste L002 Kadın Beyaz Sneaker",
                    content:
                        "1.449 TL",
                    image: "https://cdn-ss.akinon.net/products/2022/10/25/473001/7bb4d20a-d237-4401-90ca-31275c36e258_size600x600_quality100_cropCenter.jpg",
                },
                {
                    subtitle: "Lacoste",
                    title: "Lacoste L002 Kadın Beyaz Sneaker",
                    content:
                        "1.449 TL",
                    image: "https://cdn-ss.akinon.net/products/2022/10/25/473001/7bb4d20a-d237-4401-90ca-31275c36e258_size600x600_quality100_cropCenter.jpg",
                },
                {
                    subtitle: "Lacoste",
                    title: "Lacoste L002 Kadın Beyaz Sneaker",
                    content:
                        "1.449 TL",
                    image: "https://cdn-ss.akinon.net/products/2022/10/25/473001/7bb4d20a-d237-4401-90ca-31275c36e258_size600x600_quality100_cropCenter.jpg",
                },
                {
                    subtitle: "Lacoste",
                    title: "Lacoste L002 Kadın Beyaz Sneaker",
                    content:
                        "1.449 TL",
                    image: "https://cdn-ss.akinon.net/products/2022/10/25/473001/7bb4d20a-d237-4401-90ca-31275c36e258_size600x600_quality100_cropCenter.jpg",
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