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

    <footer class="text-white flex-grow-1 d-flex flex-column">
            <div class="footer-top flex-grow-1">
                <div class="container">
                    <nav></nav>
                    <nav></nav>
                    <nav></nav>
                </div>
            </div>
            <div class="footer-bottom bg-secondary">
                <div class="container d-flex justify-content-between align-items-center ">
                    <button class="btn btn-outline-primary text-white">SIGN-UP NOW!</button>
                    <div>ciaooooo
                        <div></div>
                        <div></div>
                    </div>
                </div>
            </div>
    </footer>
    
</template>

<style scoped>

    .footer-top {
        background-image: url("/public/img/footer-bg.jpg");
    }

</style>