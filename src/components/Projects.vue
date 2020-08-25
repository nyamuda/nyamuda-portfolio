<template>
    <div id="profile-container">

        <mdb-container>
            <mdb-row>
                <mdb-card reverse id="my-card">
                    <mdb-view hover cascade>
                        <a href="#!">


                            <mdb-mask waves overlay="white-slight"></mdb-mask>
                        </a>
                    </mdb-view>
                    <mdb-card-body class="text-center" cascade>
                        <mdb-card-avatar id="img-circle" color="white" class=""><img src="../assets/resize-15981837801517789037IMG20200823090419.jpg" class="img-fluid z-depth-1 rounded-circle" alt="Responsive image"></mdb-card-avatar>
                        <mdb-card-title id="my-name">
                            <p>Pierce Nyamuda</p>
                        </mdb-card-title>
                        <h5 class="indigo-text" id="job-title">
                            <p>Front End Developer</p>
                        </h5>
                        <mdb-card-text id="intro-text">I'm looking for a team that allows me to constantly get outside my comfort zone. The Front End part of web development is where I've spent the bulk of my time learning, but I'm always excited to learn new technologies</mdb-card-text>
                        <a class="px-2 fa-lg li-ic">
                            <mdb-icon fab icon="linkedin" /></a>
                        <a class="px-2 fa-lg tw-ic">
                            <mdb-icon fab icon="twitter" /></a>
                        <a class="px-2 fa-lg fb-ic">
                            <mdb-icon fab icon="facebook" /></a>
                    </mdb-card-body>
                </mdb-card>
            </mdb-row>
        </mdb-container>
        <div id="proj-title">
            <p>Projects</p>
        </div>


        <div class="proj1">
            <mdb-container>
                <mdb-jumbotron class="text-center hoverable">
                    <mdb-row>
                        <mdb-col md="4" offsetMd="1" class="m-3">
                            <mdb-view src="https://github.com/pnyamuda/nyamuda-portfolio/blob/master/src/assets/IMG_20200823_161523.jpg?raw=true" alt="Sample image for first version of blog listing">
                                <a>
                                    <mdb-mask waves overlay="white-slight" /></a>
                            </mdb-view>
                        </mdb-col>
                        <mdb-col md="7" class="text-md-left ml-3 mt-3">
                            <a href="#!" class="green-text">
                                <h6 class="h6 pb-1">
                                    <mdb-icon icon="" class="pr-1" /><span class="proj-name">Trendyrecipe</span></h6>
                            </a>
                            <p class="font-weight-normal">A single page app (SPA) that boasts hundreds of recipes and provides users
                                with easy ways to cook. The app uses the Spoonacular API for recipes and nutrition data. It uses a "what's in your fridge" API endpoint, allowing users to find recipes they can cook with the ingredients they have. Using an artificial intelligence based calculator, the app also uses Natural Language Processing to estimate calories burned for various exercises.</p>
                            <p class="font-weight-normal">
                                <span class="proj1-tech">Technologies:</span></p>
                            <p class="font-weight-normal">HTML, CSS, JavaScript, and Vue.js, and Material Design for Bootstrap</p>
                            <div class="proj-btns">
                                <mdb-btn color="success"><a class="proj-link" href="https://trendyrecipe.netlify.app/" target="_blank">View Live</a></mdb-btn>
                                <mdb-btn color="success"><a class="proj-link" href="https://github.com/pnyamuda/trendyrecipe" target="_blank">See Code</a></mdb-btn>
                            </div>

                        </mdb-col>
                    </mdb-row>
                </mdb-jumbotron>
            </mdb-container>



        </div>

        <div class="proj1">
            <mdb-container>
                <mdb-jumbotron class="text-center hoverable">
                    <mdb-row>
                        <mdb-col lg="7">
                            <a class="pink-text">
                                <h6 class="font-weight-bold mb-3">
                                    <mdb-icon icon="" class="pr-2" /><span class="proj-name">Mywordinfo</span>
                                </h6>
                            </a>
                            <p>A web app that provides a great and detailed explanation of the
                                meaning of any word and high quality images related to the word. It also uses the Wordnik API to provide the word of the day.It also uses the Wordnik API to provide the word of the day. The app was developed from scratch using only HTML, CSS and vanilla JavaScript.</p>
                            <p><span class="proj1-tech">Technologies:</span></p>
                            <p class="font-weight-normal">Pixabay API, Words API, Wordnik API, HTML, CSS, and Vanilla JavaScript</p>
                            <div class="proj-btns">
                                <mdb-btn color="pink"><a class="proj-link" href="https://pnyamuda.github.io/mywordinfo/" target="_blank">View Live</a></mdb-btn>
                                <mdb-btn color="pink"><a class="proj-link" href="https://github.com/pnyamuda/mywordinfo/tree/gh-pages" target="_blank">See Code</a></mdb-btn>
                            </div>

                        </mdb-col>
                        <mdb-col lg="5">
                            <mdb-view class="rounded z-depth-2 mb-lg-0 mb-4" hover>
                                <img class="img-fluid" src="../assets/wordinfo1.jpg" alt="Sample image" />
                                <a>
                                    <mdb-mask overlay="white-slight" waves />
                                </a>
                            </mdb-view>
                        </mdb-col>
                    </mdb-row>
                </mdb-jumbotron>
            </mdb-container>



        </div>


        <div id="skills-title">
            <p>Skills</p>
        </div>

        <div class="skill-container">

            <div class="my-skills">

                <p>JavaScript(ES6+)</p>
                <p>CSS3</p>
                <p>HTML5</p>
                <p>Vue.js</p>

            </div>
            <div class="my-skills">

                <p>Git and GitHub</p>
                <p>jQuery</p>
                <p>Restful API's</p>
                <p>NPM</p>
            </div>


        </div>

        <div id="contact">

            <div class="form-block">
                <mdb-container>

                    <form>
                        <p class="h4 text-center mb-4">Get in Touch</p>
                        <div class="grey-text">
                            <mdb-input label="Your name" icon="user" group type="text" vapdate error="wrong" success="right" v-model="name" />
                            <mdb-input label="Your email" icon="envelope" group type="email" vapdate error="wrong" success="right" v-model="email" />
                            <mdb-input label="Subject" icon="tag" group type="text" vapdate error="wrong" success="right" v-model="subject" />
                            <mdb-textarea :rows="2" label="Your message" icon="pencil" v-model="message" />
                        </div>
                        <div class="text-center">
                            <mdb-btn @click.native="modal = true" outpne="secondary" @click="sendMessage">Send
                                <mdb-icon far icon="paper-plane" class="ml-1" />
                            </mdb-btn>
                        </div>
                    </form>

                </mdb-container>


            </div>

            <div class="email">
                <p>ptnrlab@gmail.com</p>
                <p>+27815896615</p>

            </div>



        </div>

        <div>
            <!-- Frame Modal Bottom -->
           
            <mdb-modal frame position="bottom" direction="bottom" :show="modal" @close="modal = false">
                <mdb-modal-body class="text-center">
                    <span>Thank you {{name}} for reaching out to me. Will contact you back as soon possible</span>
                    <mdb-btn color="secondary" @click.native="modal = false">Close</mdb-btn>
                </mdb-modal-body>
            </mdb-modal>
        </div>




    </div>
</template>


<script>
    /* eslint-disable vue/no-unused-components */
    import {
        mdbContainer,
        mdbRow,
        mdbCol,
        mdbCard,
        mdbCardImage,
        mdbCardHeader,
        mdbCardBody,
        mdbCardTitle,
        mdbCardText,
        mdbCardFooter,
        mdbCardUp,
        mdbCardAvatar,
        mdbCardGroup,
        mdbBtn,
        mdbView,
        mdbMask,
        mdbIcon,
        mdbInput,
        mdbTextarea,
        mdbJumbotron,
        mdbModal,
        mdbModalBody,
    } from 'mdbvue';
    export default {
        name: 'CardProPage',
        components: {
            mdbCardAvatar,
            mdbContainer,
            mdbRow,
            mdbCol,
            mdbCard,
            mdbCardImage,
            mdbCardHeader,
            mdbCardBody,
            mdbCardTitle,
            mdbCardText,
            mdbCardFooter,
            mdbCardUp,
            mdbCardGroup,
            mdbBtn,
            mdbView,
            mdbMask,
            mdbIcon,
            mdbInput,
            mdbTextarea,
            mdbJumbotron,
            mdbModal,
            mdbModalBody,
        },
        data() {
            return {
                name: "",
                email: "",
                subject: "",
                message: "",
                modal: false,

            }
        },
        methods: {
            sendMessage() {
                var myHeaders = new Headers();
                myHeaders.append("x-rapidapi-host", "rapidprod-sendgrid-v1.p.rapidapi.com");
                myHeaders.append("x-rapidapi-key", "3dbcf6ea40mshbabf32ffef2d4b0p12d39djsn516819e7e052");
                myHeaders.append("content-type", "application/json");
                myHeaders.append("accept", "application/json");

                var raw = JSON.stringify({
                    "personalizations": [{
                        "to": [{
                            "email": "ptnrlab@gmail.com"
                        }],
                        "subject": this.subject
                    }],
                    "from": {
                        "email": this.email
                    },
                    "content": [{
                        "type": "text/plain",
                        "value": `Hi my name is ${this.name}. ${this.message}`
                    }]
                });

                var requestOptions = {
                    method: 'POST',
                    headers: myHeaders,
                    body: raw,
                    redirect: 'follow'
                };

                fetch("https://cors-anywhere.herokuapp.com/https://rapidprod-sendgrid-v1.p.rapidapi.com/mail/send", requestOptions)
                    .then(response => response.text())
                    .then(result => {
                        this.thankSender();
                        this.name = "";
                        this.subject = "";
                        this.email = "";
                        this.message = "";
                        console.log(result)
                    })
                    .catch(error => console.log('error', error));


            },
            thankSender() {
                this.modal = true;
            }

        }
    }

</script>

<style scoped>
    .proj-link {
        color: #ffffff;
    }

    .proj-btns {
        display: flex;
        flex-direction: column;
        width: 60%;
        justify-content: space-evenly;
        margin: auto
    }

    .proj-name {
        font-size: 1.5rem;
    }

    .proj1-tech {
        font-weight: bold;
    }

    #img-circle {
        margin: auto;
        position: relative;

    }

    #my-card {
        width: 100%;
    }

    #profile-container {
        position: relative;
        top: 1rem;
    }

    #my-name p {
        position: relative;
        top: 1rem;
        font-size: 2rem;
        font-weight: bold;
    }

    #job-title p {
        position: relative;
        top: 0.5rem;
        font-size: 1.5rem;

    }

    #proj-title,
    #skills-title {
        width: 100%;
        position: inherit;
        top: 4rem;


    }

    #proj-title p,
    #skills-title p {
        position: relative;
        margin: auto;
        text-align: center;
        font-size: 2rem;
    }

    .proj1 {
        margin-top: 5rem;
        clip-path: polygon(0 1%, 100% 10%, 100% 95%, 0 99%);
        background-color: rgba(32, 32, 32, 0.2);
        padding-top: 5rem;
        padding-bottom: 5rem;

    }

    #skills-title {
        top: 2rem;
    }

    .my-skills {}

    .skill-container {
        display: flex;
        flex-direction: row;
        width: 90%;
        justify-content: space-evenly;
        position: relative;
        top: 5rem;
        margin: auto;
    }

    .form-block {
        width: 100%;
        margin: auto;
        position: relative;
    }

    #contact {
        position: relative;
        top: 10rem;
        width: 100%;
        margin: auto;
        display: flex;
        flex-direction: column;
        justify-content: space-evenly;
        align-items: center;
    }

    .email {
        display: flex;
        flex-direction: row;
        justify-content: center;
        width: 100%;
        position: relative;
        top: 3rem;
    }

    .email p {
        margin: 1rem;
    }

    @media (min-width:768px) {
        #intro-text {
            width: 70%;
            margin: auto;
            text-align: center;
            position: relative;
            margin-bottom: 1rem;
        }

        .proj-btns {
            flex-direction: row;
            width: 100%;
            justify-content: space-evenly;
        }

        .skill-container {
            width: 50%;
        }

        #contact {
            width: 50%;
        }

    }

</style>
