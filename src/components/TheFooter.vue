<script>
    export default {
    name: "TheFooter",    
    data() {
            return {
                images: {
                    backgroundImage: "footer-bg.jpg",
                    logo: "dc-logo-bg.png"
                },
                footerAreas: [
                    {
                        title: "DC COMICS",
                        items: ["Characters", "Comics", "Movies", "TV", "Games", "Videos", "News"]
                    },
                    {
                        title: "SHOP",
                        items: ["Shop DC", "Shop DC Collectibles"]
                    },
                    {
                        title: "DC",
                        items: ["Terms of use", "Privacy policy (New)", "Ad Choices", "Advertising", "Jobs", "Subscriptions", "Talent Workshops", "CPSC Certificates", "Ratings", "Shop Help", "Contact Us"]
                    },
                    {
                        title: "SITES",
                        items: ["DC", "MAD Magazine", "DC Kids", "DC Universe", "DC Power Visa"]
                    },
                ]
            }
        }
    }
</script>

<template>

    <footer class="d-flex text-white">
        <div class="container">
            <div class="footer-top">ciaoooo</div>
            <div class="footer-bottom">belli</div>
        </div>
    </footer>
    
</template>

<style scoped>
    footer {
        background-image: url("/public/img/footer-bg.jpg");
        /* height: 400px; */
    }
</style>