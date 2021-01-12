<template>
   
        <div class="columns">
            <div class="column is-12">
                <div class="tabs help-tabs border_bottom">
                    <ul class="d-flex">

                        <li :class="[ lang === 'search' ? 'is-active' : '']">
                            <a class="p_3" @click="lang='search'">
                                <img class="w_30" src="../assets/search.svg"/>
                                </a>
                        </li>
                         <li :class="[ lang === 'Course content' ? 'is-active' : '']">
                            <a class="p_3" @click="lang='Course content'">Course content</a>
                        </li>
                        <li :class="[ lang === 'Overview' ? 'is-active' : '']">
                            <a class="p_3" @click="lang='Overview'">Overview</a>
                        </li>
                        <li :class="[ lang === 'Q&A' ? 'is-active' : '']">
                            <a class="p_3" @click="lang='Q&A'">Q&A</a>
                            </li>
                        <li :class="[ lang === 'Notes' ? 'is-active' : '']">
                            <a class="p_3" @click="lang='Notes'">Notes</a>
                            </li>
                        <li :class="[ lang === 'Announcements' ? 'is-active' : '']">
                            <a class="p_3" @click="lang='Announcements'">Announcements</a>
                            </li>
                    </ul>
                </div>
<div class="box help-content">
     <code v-if="lang ==='search'">
                      <Search/>
                    </code>
                    <code v-if="lang ==='Course content'">
                         <Coursecontent/>
                    </code>
                    <code v-if="lang ==='Overview'">
                         <Overview/>
                    </code>
                    <code v-if="lang ==='Q&A'">
                        <Que/>
                    </code>
                    <code v-if="lang ==='Notes'">
                       <Notes/>
                    </code>
                    <code v-if="lang ==='Announcements'">
                       <Announcements/>
                    </code>
                </div>
            </div>
        </div>
    
</template>
<script>
import Search from "../components/Search.vue";
import Announcements from "../components/Announcements.vue";
import Overview from "../components/Overview.vue";
import Notes from "../components/Notes.vue";
import Que from "../components/Q&A.vue";
import Coursecontent from "../components/Coursecontent.vue";




    export default {
        components: {
    Search,
    Announcements,
    Overview,
    Notes,
   Que,
   Coursecontent
  },
        name: 'HelpComponent',
        data() {
            return {
                
                lang: 'search',
            }
        },
    }
</script>
<style lang="css" scoped>
    .help-content {
        background-color: white !important;
    }
    .help-tabs {
        margin-bottom: 10px !important;
    }
    .tabs li.is-active a {
        border-bottom-color: #000000;
        color: #094c59;
        border-bottom: 3px solid;
        font-weight: bold;
    }
    code, pre {
        color: #1b1e21 !important;
        background-color: white !important;
    }
    ul {
  list-style-type: none;
  font-family: sf pro display,-apple-system,BlinkMacSystemFont,Roboto,segoe ui,Helvetica,Arial,sans-serif,apple color emoji,segoe ui emoji,segoe ui symbol;
    font-weight: 600;
    line-height: 1.2;
    letter-spacing: -.02rem;
    font-size: 1.1rem;}
a{
    color: #73726c;

}
a:hover {
    color: #73726c!important;
    text-decoration:none !important;
    cursor: pointer;
}
.border_bottom{
    border-bottom: 1px solid gray;
   padding-top: 1rem;
}
.w_30{
    width:30px;
}
.p_3 {
    padding: 1.4rem !important;
}
</style>