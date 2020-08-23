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
                        <mdb-card-avatar id="img-circle" color="white" class=""><img src="https://mdbootstrap.com/img/Photos/Avatars/img(31).jpg" class="img-fluid z-depth-1 rounded-circle" alt="Responsive image"></mdb-card-avatar>
                        <mdb-card-title id="my-name">
                            <p>Pierce Nyamuda</p>
                        </mdb-card-title>
                        <h5 class="indigo-text" id="job-title">
                            <p>Front End Developer</p>
                        </h5>
                        <mdb-card-text>Sed ut perspiciatis unde omnis iste natus sit voluptatem accusantium doloremque
                            laudantium, totam rem aperiam.</mdb-card-text>
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
                            <mdb-view src="https://mdbootstrap.com/img/Photos/Others/laptop-sm.jpg" alt="Sample image for first version of blog listing">
                                <a>
                                    <mdb-mask waves overlay="white-slight" /></a>
                            </mdb-view>
                        </mdb-col>
                        <mdb-col md="7" class="text-md-left ml-3 mt-3">
                            <a href="#!" class="green-text">
                                <h6 class="h6 pb-1">
                                    <mdb-icon icon="desktop" class="pr-1" />Trendyrecipe</h6>
                            </a>
                            <h4 class="h4 mb-4">This is title of the news</h4>
                            <p class="font-weight-normal">Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque, totam
                                rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae
                                dicta sunt explicabo. Nemo enim ipsam voluptatem quia voluptas sit aspernatur.</p>
                            <p class="font-weight-normal">by <a><strong>Carine Fox</strong></a>, 19/08/2016</p>

                            <mdb-btn color="success">View Live</mdb-btn>
                            <mdb-btn color="success">See Code</mdb-btn>
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
                                    <mdb-icon icon="desktop" class="pr-2" />Mywordinfo
                                </h6>
                            </a>
                            <h3 class="font-weight-bold mb-3 p-0">
                                <strong>Title of the news</strong>
                            </h3>
                            <p>At vero eos et accusamus et iusto odio dignissimos ducimus qui blanditiis praesentium voluptatum deleniti atque corrupti
                                quos dolores et quas molestias excepturi sint occaecati cupiditate non provident.</p>
                            <p>by
                                <a>
                                    <strong>Carine Fox</strong>
                                </a>, 14/08/2018</p>
                            <mdb-btn color="pink" size="md" class="mb-lg-0 mb-4 waves-light">Read more</mdb-btn>
                        </mdb-col>
                        <mdb-col lg="5">
                            <mdb-view class="rounded z-depth-2 mb-lg-0 mb-4" hover>
                                <img class="img-fluid" src="https://mdbootstrap.com/img/Photos/Others/img%20(34).jpg" alt="Sample image" />
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
                <ul>
                    <li>JavaScript(ES6+)</li>
                    <li>CSS3</li>
                    <li>HTML5</li>
                    <li>Vue.js</li>
                </ul>
            </div>
            <div class="my-skills">
                <ul>
                    <li>Git and GitHub</li>
                    <li>jQuery</li>
                    <li>Restful API's</li>
                    <li>NPM</li>
                </ul>
            </div>


        </div>

        <div id="contact">

            <mdb-container>
                <mdb-jumbotron class="text-center hoverable">
                    <form>
                        <p class="h4 text-center mb-4">Get in Touch</p>
                        <div class="grey-text">
                            <mdb-input label="Your name" icon="user" group type="text" validate error="wrong" success="right" />
                            <mdb-input label="Your email" icon="envelope" group type="email" validate error="wrong" success="right" />
                            <mdb-input label="Subject" icon="tag" group type="text" validate error="wrong" success="right" />
                            <mdb-textarea :rows="2" label="Your message" icon="pencil" />
                        </div>
                        <div class="text-center">
                            <mdb-btn outline="secondary">Send
                                <mdb-icon far icon="paper-plane" class="ml-1" />
                            </mdb-btn>
                        </div>
                    </form>
                </mdb-jumbotron>
            </mdb-container>

            <div class="email">
                <p>ptnrlab@gmail.com</p>
                <p>+27815896615</p>

            </div>



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
        }
    }

</script>

<style scoped>
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

    .my-skills {
        list-style: none;
    }

    .skill-container {
        display: flex;
        flex-direction: row;
        flex-wrap: wrap;
        width: 60%;
        justify-content: space-around;
        position: relative;
        top: 5rem;
        margin: auto;

    }

    #contact {
        position: relative;
        top: 10rem;
    }
    .email {
        display: flex;
        flex-direction: row;
        justify-content:center;
        width: 100%;
        position: relative;
        top: 1rem;
    }
    .email p {
        margin: 1rem;
    }

</style>
