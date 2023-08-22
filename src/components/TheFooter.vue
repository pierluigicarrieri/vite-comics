<script>
    export default {
    name: "TheFooter",    
    data() {
            return {
                images: {
                    backgroundImage: "",
                    logo: ""
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

    <footer></footer>
    
</template>

<style scoped>

</style>