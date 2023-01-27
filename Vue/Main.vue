        new Vue({
            el:"#elzero",
            data :{
                name:"sammer",
                age:15,
                data:"Today",
                skills:["HTML","CSS","JS","vue"],
                isSubscribed:true,
                imgSrc:"./images/blog-1.jpg",
                imgAlternate:"The Alternte Text",
                theImageUrl:"https://www.google.com",
                title:"<div class='rank'>pro</div>",
                counter:0,
                completedTests:[
                    {
                        testName:"First Test",
                        testResult:"80%"
                    },
                    {
                        testName:"Second Test",
                        testResult:"80%"
                    },
                    {
                        testName:"Third Test",
                        testResult:"90%"
                    }
                ]
            },
            // You Can Write A any Function Here
            methods: {
                sayMyName:function(){
                    return`Hello Your Name is ${this.name}`
                },
                calculateAge:function(){
                    return` Your Age With Days Is ${this.age*365}`
                },
               getData:function(){
                    this.data= Date()
                },
            },
        }) 